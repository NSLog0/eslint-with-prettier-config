------------------------------
1 ```.eslintrc.json``` and ```.jshintrc``` to your root project

------------------------------
2. install these plugin to via npm or yarn

```
eslint
eslint-config-prettier
eslint-plugin-react
prettier
prettier-eslint
```

### Config for VSCode 
add these to settting of VSCode
```
// Format a file on save. A formatter must be available, the file must not be auto-saved, and editor must not be shutting down.
"editor.formatOnSave": true,
// Enable/disable default JavaScript formatter (For Prettier)
"javascript.format.enable": false,
// Use 'prettier-eslint' instead of 'prettier'. Other settings will only be fallbacks in case they could not be inferred from eslint rules.
"prettier.eslintIntegration": true
```
### Config for vim
Vim use ale pluing here https://github.com/w0rp/ale.

go to see a config https://github.com/w0rp/ale/issues/683 and workaround
