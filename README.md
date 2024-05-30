## eslint + prettier + vscode 配置

`vscode`保存自动格式花

### `vscode`插件
只需要安装`eslint`插件即可，不需要安装`prettier`插件

### `prettier-plugin-tailwindcss`
自动排序`tailwindcss`类名[参考](https://tailwindcss.com/blog/automatic-class-sorting-with-prettier)
> This plugin scans your templates for class attributes containing Tailwind CSS classes, and then sorts those classes automatically following our recommended class order.

### `eslint-plugin-prettier`
格式化错误时触发eslint报错 [参考](https://github.com/prettier/eslint-plugin-prettier/tree/master)
> Runs Prettier as an ESLint rule and reports differences as individual ESLint issues.

### `eslint-config-prettier`
配合`eslint-plugin-prettier`插件使用，用于禁止eslint自带的格式化规则 [参考](https://github.com/prettier/eslint-plugin-prettier/tree/master)
> Our recommended configuration automatically enables eslint-config-prettier to disable all formatting-related ESLint rules.

### `.eslintignore`
`eslint` `flat`模式下，忽略该文件[参考](https://eslint.org/docs/latest/use/configure/migration-guide#ignoring-files)
> To ignore files with flat config, you can use the ignores property in a config object. The ignores property accepts an array of glob patterns. Flat config does not support loading ignore patterns from .eslintignore files, so you’ll need to migrate those patterns directly into flat config.