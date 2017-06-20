# NodeJS.CookBoock
Cook Book
========
## Installation
### Node.js 6.11.0 on OLE-7.3
#### Prepare
```
sudo mkdir -p /opt/nodejs
sudo chown -R gda:gda /opt/nodejs
```

#### [Download File](https://nodejs.org/en/) to /opt/nodejs
##### See the example of installation instruction in right-buttom conner [Get Help](https://github.com/nodejs/help/issues)
#### Unpack binary files
```
sudo tar -xJvf node-v6.11.0-linux-x64.tar.xz -C /opt/nodejs 
sudo mv node-v6.11.0-linux-x64 node-v6.11.0
sudo chown -R gda:gda /opt/nodejs
```

#### Set Environment :
`vim ~/.bash_profile`
```
NodeJS
export NODEJS_HOME=/opt/nodejs/node-v6.11.0
export PATH=$NODEJS_HOME/bin:$PATH
```
`source ~/.bash_profile` __or reboot__

#### Testing :
```
node -v
npm version
```
#### Troubleshooting :
```
npm config get prefix
vim ~/.npmrc
```
#### Source :
> [Installation](https://github.com/nodejs/help/wiki/Installation)

> [How to install nodejs and npm using binary file .tar.xz](https://www.youtube.com/watch?v=gQIv4GgsWf4)

> [Fixing npm permissions](https://docs.npmjs.com/getting-started/fixing-npm-permissions)

> [How do I completely uninstall Node.js ](https://stackoverflow.com/questions/11177954/how-do-i-completely-uninstall-node-js-and-reinstall-from-beginning-mac-os-x)

! Important npm variable located in ~/.npmrc
