# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list

  ## Project interface
![image](https://github.com/VitorAlkindar/NLW-IA/assets/54691720/8e61ebdb-05e8-43c5-a12b-dc5b6e2542fc)

## Tecnical details

In the past week, the Rocketseat NLW event took place, with a special edition focused on Artificial Intelligence (AI). A project was developed using the OpenAI API, which involves uploading a video for the API to transcribe into text. Additionally, it generates coherent titles and descriptions based on the content of the uploaded video.

For the front-end development, React.js, Tailwind.css, Shadcn for styled components, and Web Assembly were used. Web Assembly is a technology that allows us to run things on the web that are not traditionally web-based, among other technologies.

On the back-end side, Node.js was employed, along with Fastify to handle API requests and routes, and Prisma as the database ORM, among other technologies.

