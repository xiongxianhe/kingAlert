# kingAlert
v1.0
一个自定义用户弹窗控件，该控件依赖jquery，所以在使用时，要先把jQuery包含进web项目中。

用法：
只要在需要的web页面中包含js/kingAlert.js，然后在页面需要弹窗的位置调用KingAlert();
或者再进行如下封装：

<button onclick="kingAlert('Hello KingAlert');">CLICK</button>
<script>
function kingAlert(msg) {
    KingAlert({
        coverColor: 'rgba(0,0,0,0.36)',
        title: msg,
        okFun: function () {

        },
        cancelFun: null
    });
}
</script>
