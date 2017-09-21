# 简要说明

## 备注
    因为在国内无法翻墙, 因此把google的相关链接注释掉，使用国内jquery cdn来作为替代

## 编写说明
> 1. 通过toBeDefined来判断变量allFeeds是否被定义，然后通过not.toBe(0)来判断allFeeds的长度来确认allFeeds是否为空数组  
> 2. 以一个for循环来取得allFeeds里的各个元素，再对单个的url和name进行测试  
> 3. 检查代码后确认菜单的显示隐藏是通过body中是否含有"menu-hidden"这个class来进行控制的，页面加载后测试有无menu-hidden来判断初始菜单是否隐藏，对"menu-icon-link"这个icon绑定点击事件来测试点击后是否显示隐藏切换  
> 4. loadFeed()函数因为是异步的，所以加入了beforeEach方法以及done函数来进行测试  
