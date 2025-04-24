```js

export default {
entry: {
main: './src/index.js',
admin: './src/admin.js'
},
output: {
filename: '[name].bundle.js',
path: new URL('./dist', import.meta.url).pathname,
},
mode: 'development'
};



```




```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
Run  later on ubuntu
```