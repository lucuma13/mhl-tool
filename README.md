# mhl-tool

This is a community-maintained archive of the discontinued [mhl-tool](https://github.com/pomfort/mhl-tool) by Pomfort, for the sole purpose of preserving the v1.31 installers which are no longer available from the official source, and adding support to install it with Homebrew. Please refer to the original repository or to the [MHL website](https://mediahashlist.org) for historical documentation.

Also, be aware that there are some known [issues](https://github.com/pomfort/mhl-tool/issues) with this tool regarding xxhash64. If you need to seal or verify MHL v1 manifests consider using the more modern `simple-mhl` (part of [mhl-suite](https://github.com/lucuma13/mhl-suite)).

### 🚀 Installation

You can download and install the file for your operative system in the relevant folder of this repository.

Alternatively, if you are on macOS or Linux you can use Homebrew:

1. Install [Homebrew](https://brew.sh/) (if not already installed):
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

2. Tap and install:
```
brew tap lucuma13/dit
brew install mhl-tool
```

