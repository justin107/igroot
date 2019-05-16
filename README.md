# igroot
NPM设置淘宝镜像
1.查询当前配置的镜像

npm get registry 

> https://registry.npmjs.org/

设置成淘宝镜像

npm config set registry http://registry.npm.taobao.org/

 

2.换成原来的

npm config set registry https://registry.npmjs.org/

 

Yarn 设置淘宝镜像
1.查询当前配置的镜像

yarn config get registry

> https://registry.yarnpkg.com

设置成淘宝镜像

yarn config set registry http://registry.npm.taobao.org/
    
    
    
    const RandomId = len => Math.random().toString(36).substr(3, len);
    const id = RandomId(10);
    id => "jg7zpgiqva"

    const RoundNum = (num, decimal) => Math.round(num * 10 ** decimal) / 10 ** decimal;
    const num = RoundNum(1.69, 1);
