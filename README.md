# FTP deployer

fix committing stroked
reason in here [Hexo-ftpsync错误分析](https://codeplot.top/2019/05/12/Hexo-ftpsync错误分析/)
easy way in here [Hexo-ftpsync错误分析&修复](https://www.easyulife.com/2019/07/18/Hexo-ftpsync错误分析-修复/)

change your package.json file 
``` json
"dependencies": {
    ...
   "hexo-deployer-ftpsync": "git+ssh://git@github.com:ChaosTong/hexo-deployer-ftpsync.git",
   ...
```

Deploy your site via FTP.

## Install

```
$ npm install hexo-deployer-ftpsync --save
```

## Usage

See https://hexo.io/docs/deployment.html#FTPSync

## Warning

This application will delete files and directories on the remote server to match the local machine. Use this application in production at your own risk.
