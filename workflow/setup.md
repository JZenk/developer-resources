# Setup

My current setup.

## Equipment

+ [MacBook Pro](https://www.apple.com/macbook-pro/)
+ [Ducky Mini Keyboard](http://www.duckychannel.com.tw/en/ducky-mini/)
+ [Sony 7506 Headphones](https://pro.sony.com/bbsc/ssr/product-MDR7506/)

## Global installs
+ [Node](https://nodejs.org/en/)
+ [Homebrew](https://brew.sh/)

### npm Global packages

```
# Output globally installed packages (but not their dependencies)
npm list -g --depth=0
```
+ [Current npm list](./npm.txt)

### Homebrew packages
```
# Output installed packages (but not their dependencies)
brew leaves
```
+ [Current brew list](./brew.txt)

```
# Install all packages in brew.txt file
brew.txt | xargs brew install
```