# LinterConfigs!

We're collecting our eslint configs in one place. This allows us to use the same rules very quickly in other projects, and also allows us to share our configs with other teams.

## Usage

### NextJS with Typescript

Install dependencies:

```bash
yarn add -D @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint eslint-config-airbnb eslint-config-airbnb-typescript eslint-config-next eslint-config-prettier eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-only-warn eslint-plugin-prettier eslint-plugin-react eslint-plugin-react-hooks prettier 
```

Download the files from the `nextjs` folder in this repo, and place them in the root of your project.

```bash
curl -OL https://raw.githubusercontent.com/MiniHacks/linterconfigs/main/nextjs/.eslintrc.json

curl -OL https://raw.githubusercontent.com/MiniHacks/linterconfigs/main/nextjs/.prettierrc.js

curl -OL https://raw.githubusercontent.com/MiniHacks/linterconfigs/main/nextjs/tsconfig.json

curl -OL https://raw.githubusercontent.com/MiniHacks/linterconfigs/main/nextjs/tsconfig.eslint.json
```
