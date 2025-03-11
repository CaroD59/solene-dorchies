![screencapture-127-0-0-1-5173-2025-03-11-15_51_40](https://github.com/user-attachments/assets/ee29fc20-94fd-4bbd-a730-e692d24e780f)

![screencapture-127-0-0-1-5173-about-2025-03-11-15_51_53](https://github.com/user-attachments/assets/6ba39553-aebc-4ce7-94ca-aa22371bdc42)

![screencapture-127-0-0-1-5173-about-2025-03-11-15_52_02](https://github.com/user-attachments/assets/b2ca33dc-6aee-4780-b3f6-f8dba9e8507e)

![screencapture-127-0-0-1-5173-about-2025-03-11-15_52_08](https://github.com/user-attachments/assets/b614530b-80c4-4154-822e-15634c3df517)

![screencapture-127-0-0-1-5173-about-2025-03-11-15_52_16](https://github.com/user-attachments/assets/1c04d61d-00aa-4a1f-85c1-ca5ff1d804f9)

![screencapture-127-0-0-1-5173-contact-2025-03-11-15_52_22](https://github.com/user-attachments/assets/9d6b9323-bf9c-49af-866f-a0102d0cde39)


# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
