# hyper-samewd

Simple extension for hyper terminal that maintains the current working directory when opening new tabs.

## Installation

Simply run `hyper i hyper-samewd` if you have added hyper to path.

or open `~/.hyper.js` and add `"hyper-samewd"` to `plugins` list manually.

## Config Options

Currently the only option supported is `initialWorkingDirectory`. This allows you to set the initial directory when opening hyper for the first time.

Add the following to the `config` object in `~/.hyper.js`

```javascript
config: {
  // Default config options
  hyperwd: {
    initialWorkingDirectory: '/tmp' // Replace /tmp with your preferred working directory
  }
}
```
