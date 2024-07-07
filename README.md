# cf-wkrs-sub

使用 CloudFlare Workers 订阅免费节点

## 部署教程

- Workers 教程地址：worker.js（我现在使用的），worker_2.js（效果差不多）
- 在部署好后，打开的dev页面后面加上/sub/干净IP。就是订阅地址
- 干净IP网站：https://cloudflare-scanner.vercel.app/
- 在部署好后，打开的dev页面也可以直接点网站会出来节点。

## 鸣谢项目

- vfarid：https://github.com/vfarid/v2ray-worker-sub

## 注意事项

1. 由于默认 workers 从节点池的海量节点筛选时，不是按照国内环境筛选，因此需要二次在本地测试所有节点，筛选后使用可用的节点
2. 由于 workers.dev 域名被墙，所以需要绑定自己的域名
3. 由于节点均为公用节点，因此请勿在节点上登录自己的重要账户数据
4. 请勿滥用！
