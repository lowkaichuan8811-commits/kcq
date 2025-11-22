<!DOCTYPE html>
<html lang="zh-CN">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>仿抖音快手网页版</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      list-style: none;
    }

    body {
      font-family: Arial, sans-serif;
      overflow: hidden;
    }

    /* 顶部导航栏通用样式 */
   .header {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      background-color: #000;
      padding: 10px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      z-index: 10;
    }

   .header a {
      color: white;
      text-decoration: none;
      font-size: 20px;
    }

    /* 搜索栏样式 */
   .search-bar {
      display: flex;
      align-items: center;
      background-color: #fff;
      border-radius: 20px;
      padding: 5px 10px;
    }

   .search-bar input {
      border: none;
      outline: none;
      background: none;
      margin-left: 5px;
    }

   .search-bar img {
      width: 20px;
      height: 20px;
    }

    /* 简单添加一些页面背景样式区分 */
   .page {
      display: flex;
      justify-content: center;
      align-items: center;
    }

    /* 头像样式，可根据需要调整 */
    #avatar {
      width: 50px;
      height: 50px;
      border-radius: 50%;
      cursor: pointer;
    }

    /* 视频推荐区域样式 */
   .video-recommendation {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      margin-top: 60px;
    }

   .video-item-recommendation {
      width: 300px;
      height: 400px;
      margin: 20px;
      background-color: #f4f4f4;
      border: 1px solid #ccc;
      border-radius: 10px;
      overflow: hidden;
    }

    /* 视频封面图片样式 */
   .video-cover {
      width: 100%;
      height: 200px;
    }

    /* 视频信息区域样式 */
   .video-info-area {
      padding: 10px;
    }

    /* 视频标题样式 */
   .video-title {
      font-size: 16px;
      margin-bottom: 10px;
    }

    /* 点赞和评论按钮样式 */
   .interaction-buttons {
      display: flex;
      justify-content: space-around;
      margin-top: 10px;
    }

   .interaction-button {
      cursor: pointer;
      font-size: 14px;
      padding: 5px 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    /* 评论区域样式 */
   .comment-area {
      margin-top: 10px;
    }

   .comment {
      margin: 5px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
      padding: 5px;
    }
  </style>
</head>

<body>
  <!-- 主页 -->
  <div id="home-page" style="display: none; width: 100%; height: 100vh;" class="page">
    <div class="header">
      <a href="#" onclick="showUserProfile()">我的</a>
      <div class="search-bar">
        <img src="search-icon.svg" alt="搜索图标">
        <input type="text" placeholder="搜索视频">
      </div>
      <a href="#" onclick="showDiscoverPage()">发现</a>
    </div>
    <p>这里是主页的一些示例内容</p>
  </div>

  <!-- 发现页 -->
  <div id="discover-page" style="display: none; width: 100%; height: 100vh;" class="page">
    <div class="header">
      <a href="#" onclick="showHomePage()">主页</a>
      <div class="search-bar">
        <img src="search-icon.svg" alt="搜索图标">
        <input type="text" placeholder="搜索视频">
      </div>
      <a href="#" onclick="showUserProfile()">我的</a>
    </div>
    <div class="video-recommendation">
      <div class="video-item-recommendation">
        <img class="video-cover" src="https://via.placeholder.com/300x200" alt="视频封面">
        <div class="video-info-area">
          <p class="video-title">这是一个有趣的视频标题</p>
          <div class="interaction-buttons">
            <button class="interaction-button" onclick="likeVideo(this)">点赞</button>
            <button class="interaction-button" onclick="commentVideo(this)">评论</button>
          </div>
          <div class="comment-area">
            <p class="comment">这里显示评论内容</p>
          </div>
        </div>
      </div>
      <div class="video-item-recommendation">
        <img class="video-cover" src="https://via.placeholder.com/300x200" alt="视频封面">
        <div class="video-info-area">
          <p class="video-title">这是另一个视频标题</p>
          <div class="interaction-buttons">
            <button class="interaction-button" onclick="likeVideo(this)">点赞</button>
            <button class="interaction-button" onclick="commentVideo(this)">评论</button>
          </div>
          <div class="comment-area">
            <p class="comment">这里显示评论内容</p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- 用户主页 -->
  <div id="user-profile" style="display: none; width: 100%; height: 100vh;" class="page">
    <div class="header">
      <a href="#" onclick="showHomePage()">主页</a>
      <div class="search-bar">
        <img src="search-icon.svg" alt="搜索图标">
        <input type="text" placeholder="搜索视频">
      </div>
    </div>
    <div style="display: flex; flex-direction: column; align-items: center; margin-top: 60px;">
      <img id="avatar" src="default-avatar.jpg" alt="头像">
      <input type="file" id="fileInput" accept="image/*" style="display: none;">
      <button onclick="switchAccount()">切换账号</button>
      <button onclick="selectAvatar()">更换头像</button>
    </div>
    <p>这里是用户主页的一些示例内容</p>
  </div>

  <!-- 模拟注册页面，实际应根据需求完善 -->
  <div id="register-page" style="display: none; width: 100%; height: 100vh;" class="page">
    <p>这里是注册页面的一些示例内容</p>
  </div>

  <script>
    // 模拟用户数据数组
    let users = [];
    let nextUserId = 100000;

    // 显示主页
    function showHomePage() {
      document.getElementById('home-page').style.display = 'block';
      document.getElementById('discover-page').style.display = 'none';
      document.getElementById('user-profile').style.display = 'none';
      // 可以在这里添加主页初始化相关逻辑，比如加载视频列表等
    }

    // 显示发现页
    function showDiscoverPage() {
      document.getElementById('discover-page').style.display = 'block';
      document.getElementById('home-page').style.display = 'none';
      document.getElementById('user-profile').style.display = 'none';
      // 可以在这里添加发现页初始化相关逻辑，比如加载推荐视频等
    }

    // 显示用户主页
    function showUserProfile() {
      document.getElementById('user-profile').style.display = 'block';
      document.getElementById('home-page').style.display = 'none';
      document.getElementById('discover-page').style.display = 'none';
      // 可以在这里添加用户主页初始化相关逻辑，比如加载用户信息和视频等
    }

    // 切换账号功能，简单示例为清空当前用户信息并回到注册页
    function switchAccount() {
      // 清空当前用户相关数据，这里简单示例
      users = [];
      nextUserId = 100000;
      document.getElementById('username-display').textContent = '';
      document.getElementById('user-id-display').textContent = '';
      document.getElementById('following-count').textContent = '0';
      document.getElementById('follower-count').textContent = '0';
      document.getElementById('user-avatar').src = "default-avatar.jpg";
      document.getElementById('user-profile').style.display = 'none';
      document.getElementById('register-page').style.display = 'block';
    }

    function selectAvatar() {
      document.getElementById('fileInput').click();
    }

    function updateAvatar() {
      var file = document.getElementById('fileInput').files[0];
      if (file) {
        var reader = new FileReader();
        reader.onload = function (e) {
          document.getElementById('avatar').src = e.target.result;
        };
        reader.readAsDataURL(file);
      }
    }

    document.getElementById('avatar').onclick = selectAvatar;
    document.getElementById('fileInput').onchange = updateAvatar;

    // 模拟点赞功能
    function likeVideo(button) {
      button.textContent = '已点赞';
      button.disabled = true;
    }

    // 模拟评论功能，这里只是简单添加一个输入框和显示评论
    function commentVideo(button) {
      var commentArea = button.closest('.video-item-recommendation').querySelector('.comment-area');
      var input = document.createElement('input');
      input.placeholder = '写下你的评论';
      input.style.width = '80%';
      input.style.padding = '5px';
      input.style.marginBottom = '5px';
      var sendButton = document.createElement('button');
      sendButton.textContent = '发送';
      sendButton.onclick = function () {
        var commentText = input.value;
        if (commentText) {
          var comment = document.createElement('p');
          comment.classList.add('comment');
          comment.textContent = commentText;
          commentArea.appendChild(comment);
          input.value = '';
        }
      };
      commentArea.innerHTML = '';
      commentArea.appendChild(input);
      commentArea.appendChild(sendButton);
    }
  </script>
</body>

</html>
