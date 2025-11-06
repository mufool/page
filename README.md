# page
## 项目简介

xxxxx

## Vercel部署(推荐)
[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/mufool/page)


1. 点击部署按钮⬆️一键部署。
2. 国内使用需要配置自定义域名


## Deno部署 (WIP)

1. [fork](https://github.com/mufool/page/fork)本项目
2. 登录/注册 https://dash.deno.com/
3. 创建项目 https://dash.deno.com/new_project
4. 选择此项目，填写项目名字（请仔细填写项目名字，关系到自动分配的域名）
5. Entrypoint 填写 `src/deno_index.ts` 其他字段留空 
   <details>
   <summary>如图</summary>
   
   ![image](/docs/images/3.png)
   </details>
6. 点击 <b>Deploy Project</b>
7. 部署成功后获得域名
8. 国内使用需要配置自定义域名


## Cloudflare Worker 部署
[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/mufool/page)

0. CF Worker有可能会分配香港的CDN节点导致无法使用(Gemini不允许香港IP连接)
0. 广东地区不建议使用Cloudflare Worker 部署
1. 点击部署按钮
2. 登录Cloudflare账号
3. 链接Github账户，部署
4. 打开dash.cloudflare.com，查看部署后的worker
6. 国内使用需要配置自定义域名


## Netlify部署
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/mufool/page)
<br>点击部署按钮，登录Github账户即可
<br>免费分配域名，国内可直连。
<br>但是不稳定

<details>
<summary>将分配的域名复制下来，如图：</summary>

![image](/docs/images/1.png)
</details>

## 本地查看
1. 打开终端
2. 进入项目目录：
```
cd /Users/zhangjiaxing/leadsout/page
```
3. 启动本地服务器：
```
python3 -m http.server 8000
```
4. 在浏览器中访问：http://localhost:8000