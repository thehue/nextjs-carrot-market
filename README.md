# Carrot Market

Serverless Carrot Market Clone using NextJS, Tailwind, Prisma, PlanetScale and Cloudflare

## Setup

- [**TailwindCSS Setup**](https://github.com/thehue/nextjs-carrot-market/commit/fb919cabed7bea43f71a0b1337ef904c90d85bcf)

    ```bash
    yarn add -D tailwindcss postcss autoprefixer
    ```

  초기화 파일 생성

    ```bash
    # postcss.config.js 파일 생성
    npx tailwindcss init -
    ```

  TailwindCSS 자동 정렬 플러그인

    ```bash
    yarn add -D prettier prettier-plugin-tailwindcss
    ```

  base layer - components layer(ex. `container`) - utilities layer(ex. `p-4 pt-2`) 순으로 정렬된다.