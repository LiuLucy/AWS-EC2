![AWS](http://www.ureka.cc/weicloud/wp-content/uploads/sites/25/2017/11/AWS_Icons-300x200.png "AWS-Logo")

學習AWS EC2雲端主機
=================

#### 1. 打開AWS網頁

[官網連結](https://aws.amazon.com/tw/free/)

#### 2. 登入Lucy的帳號（我幫你們登入）

        輸入帳號密碼
		
#### 3.登入主控台

	    進入後台後點選右上方的
		
#### 4. 找到「EC2」

	    Amazon Elastic Compute Cloud (Amazon EC2)
        稱為有彈性的雲端主機，在前期可以避免投入在硬體中，可以快速的在主機上開發以及部署應用程式，
        使用EC2根據自身的需求可以調整雲端主機的數量、安全、網路和管理儲存。EC2也可以用來應對高峰期的流量等...

#### 5. 新增一個 Instance

        選擇畫面上的 Launch Instance

#### 6. 選擇免費的主機

        在畫面左邊有一個[Free tier only]請打勾
        拉到下面選擇Microsoft Windows Server 2016 Base 雲端主機
        Launch雲端主機

#### 7. 建立key pair

        選擇Choose an existing key pair 


開啟雲端主機
=================

#### 1. 安裝 Microsoft Remote Desktop

        選擇上面的 Connect 下載 Microsoft Remote Desktop File

#### 2. 取得密碼

        在 Connect 下面有 Get Password 點選
        把剛剛下載的 key pair 給他，取得登入密碼

#### 3. 設定 Microsoft Remote Desktop

        按下 New
        Connection name : 填雲端伺服器的名字
        PC name : 填入Public IP
        User name : Administrator
        Password : 剛剛得到的密碼

#### 4. 選擇同步的資料夾

        Rediraction 選擇想要同步的資料夾
        登入

#### 5. 使用 Server Manager

        點選 Add roles and features
        Next 
        Next
        把 Web server IIS 勾選起來
        Next
        Install

#### 6. 放入網站

        打開我的電腦 -> inetpub -> wwwroot -> 放入網站

#### 7. 打開 Internet Infomation Server IIS Manage

        點選 Bindings -> 把自己的 Domain Name 放上去

### 完成


 



###### 地址翻譯：https://www.post.gov.tw/post/internet/Postal/index.jsp?ID=207\
###### 參考文件：https://docs.aws.amazon.com/zh_cn/AWSEC2/latest/UserGuide/concepts.html#how-to-get-started

