# open-ethereum-pool
以太坊开源开采矿池-开源
该池正在进一步开发中，为以太坊矿工提供一个易于使用的游泳池。该软件功能正常，但预计不久将优化版本库。欢迎测试和错误提交！

支持HTTP和Stratum挖掘
具有运气比例和全部奖励的详细区块统计数据
故障转移geth实例：geth内置高可用性
现代美丽的Ember.js前端
单独的工人统计数据：可以突出显示超时工人，以便矿工可以执行钻机维护
JSON-API用于统计
代理
以太网代理 HTTP代理与Web界面
以太坊的阶层代理人
建立在Linux上
依赖关系：

去> = 1.9
geth或平价
redis-server> = 2.8.0
nodejs> = 4 LTS
nginx的
我强烈建议使用Ubuntu 16.04 LTS。

首先安装 go-ethereum。

克隆和编译：

git config --global http.https://gopkg.in.followRedirects true
git clone https://github.com/sammy007/open-ethereum-pool.git
cd open-ethereum-pool
make
安装redis-server。

运行池
./build/bin/open-ethereum-pool config.json
