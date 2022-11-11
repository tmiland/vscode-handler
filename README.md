# Visual Studio Code URL Handler
A `vscode://` *URL handler* for **[VSCodium](https://vscodium.com/)** on Debian.

Will translate `vscode:extension/url` to `vscodium:extension/url` to open extensions in VSCodium when clicking the install links on [visualstudio Marketplace](https://marketplace.visualstudio.com).

# Installing on Linux (Debian)

#### Steps:

  1. clone this repository
```
git clone https://github.com/tmiland/vscode-handler.git
```
  2. run 
```
./install
```
  3. delete cloned folder
```
rm -rf ./vscode-handler
```


#### Notice:

- Tested on Debian Linux Desktop (Firefox 106)

#### Source:

Forked from [shengyou/vscode-handler](https://github.com/shengyou/vscode-handler)