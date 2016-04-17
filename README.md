# jQuery的完整日历材料设计

为jQuery完整的日历插件材料设计主题

<img src="http://i.imgur.com/TH3VsJU.gif">

实际的安卓材料设计日历的样子：
<img src="http://dab1nmslvvntp.cloudfront.net/wp-content/uploads/2014/09/1410153384GIF2.gif">

这是默认的fullcalendar看起来像。电子战！

<img src="http://imgur.com/vKTKUTx.png">

而fullcalendar是非常可怕的，它看起来很可怕的不

任何造型。我受到了谷歌的材料设计的启发

巧合的是，我需要为我的德崇证券一个合适的主题
[Schedulizer](http://loop.tf/schedulizer) 服务。做一些基本的

研究，似乎没有任何材料设计日历

插件或主题，如fullcalendar的灵活

功能，所以我把事情自己的手，把这个

在一起。

### 建立完整的日历

使用以下设置初始化你的fullcalendar对象

    editable: false, //不允许编辑事件
    handleWindowResize: true,
    weekends: false, // 隐藏的周末
    defaultView: 'agendaWeek', //只显示周视图
    header: false, // 隐藏按钮/标题
    minTime: '07:30:00', // 开始时间为日历
    maxTime: '22:00:00', //比时间的日志
    columnFormat: {
        week: 'ddd' //只 显示 天 本 周 的 名字
    },
    displayEventTime: true, //显示事件时间
    
### Usage

Compile `_materialFullCalendar.scss`使用您最喜爱的SASS编译，或简单地改变文件
扩展 `.css`. 有没有实际的SASS元素
在这里.

推和添加新的事件仍然是相同的，虽然你申请`color` 属性。

    events.push({
        title: 'This is a Material Design event!',
        start: 'someStartDate',
        end: 'someEndDate',
        color: '#C2185B'
    });

### 材料设计颜色

<img src="http://i.imgur.com/HCeR1PB.png"></img>

Color palette was pulled from the Google Material Design [documentation](https://www.google.com/design/spec/style/color.html#color-color-palette). 

Highly recommend the 700 level palette to achieve the same color effect as I do.

An opacity of `0.65` is automatically applied to each event to achieve a softer look. 

请注意             这个主题是不完整的。我没有测试它在每月或             每日意见，因为我的目的，我只需要它在一个             ` agendaweek `。这也可能是车的时候，用在其他方面。感觉             免费使用以下说明作出贡献。 
### Please Note

This theme is in no way complete. I did not test it in the monthly or
daily views, since for my purposes, I only needed it to be used in an
`agendaWeek`. It might also be buggy when used in other contexts. Feel
free to contribute using the instructions below.

### How to Contribute:

1. Pull/Fork

2. Issue pull requests

3. Make issues

### License:

MIT. Just credit me.


