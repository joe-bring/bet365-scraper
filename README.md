# bet365-live-scraper
# English
#### Function:
Retrieve Live Football and Basketball Match Information from Bet365.

#### Features:
Get real-time football and basketball match information from Bet365, including teams, time, and score, encapsulated as an HTTP service for easy access.

#### Principle:
Intercept WebSocket messages from Bet365’s webpage in the browser and send the data to an HTTP API service.

#### Deployment and Installation Steps:
1.Install the Chrome extension chrome_extension on Chrome.

2.Set up a Python environment and install the required libraries, Flask and Flask-CORS.

3.Run local_api.py ,for better HTTP performance, you may deploy a dedicated web server.

4.Open the browser extension panel and configure the upload URL to ensure data is successfully sent to local_api, the default URL is already set to http://127.0.0.1:8485

5.Open the Bet365 live betting page in your browser.

#### How to Use the API:
1.Get Football Matches (GET):

http://127.0.0.1:8485/live?sport=1

2.Get Basketball Matches (GET):

http://127.0.0.1:8485/live?sport=18

### Any question contact
Telegram: https://t.me/JoeBili

# 中文
#### 功能：
获取bet365的足球篮球滚球比赛信息，包括队伍、时间、比分，封装为http以便读取。

#### 原理：
拦截浏览器中bet365网页的websocket消息，通过http发送到接口服务。

#### 部署和安装步骤：
1.在chrome上安装浏览器插件chrome_extention。

2.部署python环境，安装好第三方库flask和flask_cors。

3.运行local_api.py，如果为了更好的http接口性能可以自行部署专用的web。

4.在浏览器插件中打开面板，配置upload url，确保数据能上传到local_api，默认已经配置都是http://127.0.0.1:8485

5.在浏览器中打开bet365的滚球页面。

#### 如何调用接口:
1.获取足球(GET)：

http://127.0.0.1:8485/live?sport=1

2.获取篮球(GET)：

http://127.0.0.1:8485/live?sport=18

### 问题交流
Telegram: https://t.me/JoeBili
