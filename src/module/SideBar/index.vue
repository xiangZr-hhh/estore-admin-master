<template>
  <div id="sideBar" style="overflow-x: hidden;">
    <!-- 右侧导航 -->
    <div class="layui-side layui-bg-black">
      <div class="user-photo">
        <a class="img" title="我的头像"><img src="../../assets/logo.png"></a>
        <p>你好！<span class="userName"></span> 欢迎登录</p>
      </div>
      <div class="navBar layui-side-scroll" style="height: 514px;">
        <ul class="layui-nav " lay-bar="disabled" >
          <li class="layui-nav-item">
            <router-link to="/"><i class="layui-icon layui-icon-home" ></i>
              <cite>首页</cite>
            </router-link>
          </li>
          <!--          <li class="layui-nav-item">-->
          <!--            <router-link to="/ContentArticle"><i class="iconfont icon-text"-->
          <!--                                                 data-icon="icon-text"></i><cite>文章列表</cite>-->
          <!--            </router-link>-->
          <!--          </li>-->
          <!--          <li class="layui-nav-item">-->
          <!--            <router-link to="/"><i class="iconfont icon-text" data-icon="icon-text"></i><cite>用户列表</cite>-->
          <!--            </router-link>-->
          <!--          </li>-->
          <!--          <li class="layui-nav-item">-->
          <!--            <router-link to="/ChangePassword"><i class="iconfont icon-text"-->
          <!--                                                 data-icon="icon-text"></i><cite>修改密码</cite></router-link>-->
          <!--          </li>-->
          <li class="layui-nav-item">
            <router-link to="/"><i class="layui-icon layui-icon-template-1" ></i>
              <cite>我的课程</cite>
            </router-link>
          </li>
          <li class="layui-nav-item">
            <router-link to="/"><i class="layui-icon layui-icon-form " ></i>
              <cite>课表</cite>
            </router-link>
          </li>
          <li class="layui-nav-item">
            <router-link to="/"><i class="layui-icon layui-icon-edit" ></i>
              <cite>笔记</cite>
            </router-link>
          </li>
          <li class="layui-nav-item">
            <router-link to="/"><i class="layui-icon layui-icon-reply-fill" ></i>
              <cite>话题讨论</cite>
            </router-link>
          </li>
          <li class="layui-nav-item">
            <router-link to="/"><i class="layui-icon layui-icon-star-fill" ></i>
              <cite>收藏</cite>
            </router-link>
          </li>
          <li class="layui-nav-item">
            <router-link to="/"><i class="layui-icon layui-icon-log" ></i>
              <cite>收件箱</cite>
            </router-link>
          </li>
          <li class="layui-nav-item">
            <router-link to="/"><i class="layui-icon layui-icon-friends" ></i>
              <cite>通讯录</cite>
            </router-link>
          </li>
          <li class="layui-nav-item">
            <router-link to="/"><i class="layui-icon layui-icon-username" ></i>
              <cite>个人中心</cite>
            </router-link>
          </li>


        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.layui-side {
  top: 60px;
  width: 200px;
  overflow-x: hidden;
  overflow-y: hidden;
}

.user-photo {
  width: 200px;
  height: 120px;
  padding-top: 15px;
  padding-bottom: 5px;
}

.user-photo a.img {
  display: block;
  width: 76px;
  height: 76px;
  margin: 0 auto;
  margin-bottom: 15px;
}

.user-photo a.img img {
  display: block;
  border: none;
  width: 100%;
  height: 100%;
  border-radius: 50%;
  -webkit-border-radius: 50%;
  -moz-border-radius: 50%;
  border: 4px solid #44576b;
}

.user-photo p {
  text-align: center;
}

.layui-icon {
  font-size: 20px;
  padding: 0 10px;
  vertical-align: middle;
}

.layui-nav-item {
  font-size: 20px;
  color: #fff;
  text-align: center;
}

.layui-nav .layui-nav-item > a {
  font-size: 20px;
  color: #fff;
}

.iconfont {
  padding: 0 10px;
  font-size: 20px;
}
</style>
