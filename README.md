# apfs-reseal

This is a fork of the original i made to fit my use case

## Usage

### macOS
```
sudo xcode-select --install

sudo xcodebuild -license accept

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

brew tap hudochenkov/sshpass

brew install hudochenkov/sshpass/sshpass libimobiledevice jq python3

sudo python3 -m pip install pyimg4 remotezip

sudo curl -Lo /usr/local/bin/irecovery https://github.com/palera1n/palera1n/raw/legacy/binaries/Darwin/irecovery

sudo chmod +x /usr/local/bin/irecovery

sudo curl -Lo /usr/local/bin/palera1n https://github.com/palera1n/palera1n/releases/download/v2.0.0-beta.6.2/palera1n-macos-universal

sudo chmod +x /usr/local/bin/palera1n

git clone https://github.com/0xallie/apfs-reseal

cd apfs-reseal

./apfs_reseal.command
```
