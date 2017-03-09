# hyper-startup-tabs

Specify a set of directories to be opened in separate tabs when hyper terminal is launched.

## Install

1. Add `hyper-startup-tabs` to your plugins array in `~/.hyperterm.js`
2. Create array of directories in `startupTabs` inside the `config`

```js

module.exports = {
  config: {
    startupTabs: ['/Source', '~']
  },
  plugins: [
    'hyper-startup-tabs'
  ]
}
```