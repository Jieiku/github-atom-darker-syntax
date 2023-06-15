# GitHub atom darker

> GitHub's official dark syntax theme as an atom theme, modified for higher contrast.

![](https://raw.githubusercontent.com/Jieiku/github-atom-darker-syntax/master/screenshot.png)

I am now using [atom-ng](https://github.com/Alex313031/atom-ng) instead of the now unmaintained atom.

This theme's contrast is meant to improve the readability of the text, especially when using the split-diff package.

*Split Diff allows you to press Ctrl+Alt+D while you have two files side by side, and you get a live editable diff view.*

![](https://raw.githubusercontent.com/Jieiku/github-atom-darker-syntax/master/screenshot-split-diff.png)

## Install

To install this syntax theme on linux:

```bash
mkdir -p ~/.atom/packages/
cd ~/.atom/packages/
git clone https://github.com/Jieiku/github-atom-darker-syntax.git
```


## Usage

After installation, you can enable this theme in your Atom theme settings. (menu > edit > preferences, or alt+s, then select the Themes section from the left menu, then pick this theme from the syntax dropdown)


## Contributing

For any bugs, open an [issue](https://github.com/Jieiku/github-atom-darker-syntax/issues).

This was originally forked from: https://github.com/primer/github-atom-dark-syntax

The package.json file is still there, before atom was abandoned apm could grab these packages from atom.io, I stripped the file down and its only there so that the package will still load in atom-ng.

If you know how to cleanup the package.json so that it is more useful in some way then contributions are welcome.


## License

[MIT](./LICENSE) &copy; [GitHub](https://github.com/)

[docs]: http://primercss.io/
[npm]: https://www.npmjs.com/
[install-npm]: https://docs.npmjs.com/getting-started/installing-node
[install-apm]: https://github.com/atom/apm#installing
[sass]: http://sass-lang.com/
[apm]: https://atom.io/themes
