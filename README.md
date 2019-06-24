# vue-vc
vue环形进度条bug修改
# 原插件 vue-vue-circleprogressbar

beforeDestroy() {
    // 清除旧组件的样式标签
    document.getElementById(this.idStr) &&
    document.getElementById(this.idStr).remove();
    window.addEventListener(() => {});
},

报错

# 如有侵权
联系 chaixiaoduo@126.com