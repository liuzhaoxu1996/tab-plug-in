tab插件(功能比较全)
=====================

## 插件介绍：
`tab.js`是jquery开发的，所以引入`tab.js`之前要引入jquery

## 插件安装：
`clone tab.js` 

## 配置参数
在标签中添加`data.config`属性  `data-config`里可以配置4种属性

形如：
```
data-config='{
            "triggerType" : "click",   // 触发方式 click mouseover
            "effect" : "fade",         // 切换方式 fade（淡入淡出） default
            "invoke" : 2,              // 初始显示第几个选项卡
            "auto" : 2000              // 切换速度/ms 
        }'
  ```
