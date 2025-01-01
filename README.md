# Centic 自动领取任务
![banner](image.png)

本脚本自动领取任务以获取Centic积分（CTP）

## 功能

- **自动领取任务**
- **自动领取每日奖励**
- **支持多账号**
- **支持使用代理**

## 前提条件

- 已安装Node.js
- `tokens.txt`文件包含来自Centic平台的token apikey，获取方法如下：
- 打开Centic平台 [https://centic.io/quests/](https://centic.io/quests/daily?refferalCode=eJwNyckRACAIBLCWllvKwQFrsHzNN7haq8bJg1OyFMJqEWMbx1c3gWx-8APqvQrb)
- 使用钱包登录
- 按F12打开开发者工具，找到Application选项卡
- 在Local Storage中找到`apiKey_`并复制所有值
![Apikey](image-1.png)

## 安装

1. 克隆仓库：
    ```sh
    git clone https://github.com/huaguihai/CenticBot.git
    cd CenticBot
    ```

2. 安装依赖：
    ```sh
    npm install
    ```
3. 在`tokens.txt`文件中输入你的Centic apikey，每行一个用户；
    ```sh
    nano tokens.txt
    ```
4. 可选使用代理：
- 在`proxy.txt`中粘贴代理，格式为`http://用户名:密码@IP:端口`
    ```sh
    nano proxy.txt
    ```
5. 运行脚本：
    ```sh
    npm run start
    ```

## ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

本项目采用 [MIT License](LICENSE) 许可证。
