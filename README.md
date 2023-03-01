<!-- this is a readme file that explains this gh extension including two screenshots from the images folder
 The extension name is gh-brew-outdated and it highlight all brew outdated formulas in their dependency tree as shown in the image gh-brew-outdated.png as well as list them in the traditional way (brew-outdated-output.png)-->

# gh-brew-outdated

This is a gh extension that highlights all brew outdated formulas in their dependency tree as shown in the image gh-brew-outdated.png as well as list them in the traditional way (brew-outdated-output.png).

## Installation

```bash
gh extension install davidraviv/gh-brew-outdated
```

## Usage

```bash
gh brew-outdated
```

## Screenshots

Traditional brew outdated output:
![brew-outdated-output](images/brew-outdated-output.png)

This extension highlights all outdated formulas in their dependency tree:
![gh-brew-outdated](images/gh-brew-outdated-output.png)

## Dependencies
- brew
- zsh

## Contributing
Contribution is welcomed! Please open an issue or a pull request.

## Possible improvements
- Make `brew deps` and `brew outdated` run in parallel
- Add a spinner while each phase is running





