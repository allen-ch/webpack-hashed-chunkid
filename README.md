
## Install
> $ npm i webpack-hashedChunkid --save

## Usage
> const hashedChunkIdPlugin = require('webpack-hashed-chunkid')

> webpackConfig = {
  plugins: [
    new hashedChunkIdPlugin()
  ]
}

You can specify the hash length you want (defualt 4):

> new hashedChunkIdPlugin({
  length: 6
})
