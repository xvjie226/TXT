<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <title>测试页面</title>
    <!--
        用'display'给盒子定义'flex'
        'border'是边界标签
        用 'flex-direction'给'flex”定义'column（竖向）'属性
        'flex: 1;'使盒子占满全屏
        'background-image: linear-gradient'渐变色
    -->
    <style>
        body {
            display: flex;
            /*设置为弹性盒子属性*/
            flex-direction: column;
            /*盒子内排列方向*/
            /*'column'为竖向排列*/
            background-color: aqua;
            /*盒子背景颜色*/
        }

        a {
            color: white;
            /*内容颜色*/
            text-decoration: none;
            /*去除'a'标签内容的下划线*/
            font-size: 30px;
            /*设置字体*/
        }

        .d1 {
            background-image: linear-gradient(to right, rgb(0, 162, 255), rgb(0, 255, 60));
            /*背景颜色渐变*/
            /*格式|background-image: linear-gradient(to 终点方向，颜色1，颜色2)*/
            height: 120px;
            /*高度*/
            text-align: center;
            /*内容水平居中*/
            line-height: 112px;
            /*行高*/
            font-size: 60px;
            /*字体大小*/
            color: azure;
            /*内容颜色*/
            font-style: italic;
            /*字体样式*/
            /*'italic'为斜体*/
            margin-bottom: 10px;
            /*下边距*/
            /*'margin'为边距，'bottom'为方向*/
        }

        .d2 {
            background-color: aqua;
            /*背景颜色*/
            display: flex;
            /*设置为弹性盒子属性*/
            flex-direction: row;
            /*盒子内排列方向*/
            /*'row'为横向*/
            height: 1000px;
            /*盒子高度*/
            margin-bottom: 10px;
            /*下边距*/
        }

        .d21 {
            background-image: linear-gradient(to bottom, rgb(0, 162, 255), rgb(0, 255, 60));
            /*背景颜色渐变*/
            width: 120px;
            /*盒子宽度*/
            display: flex;
            /*设置为弹性盒子属性*/
            flex-direction: column;
            /*盒子内排列方向*/
            /*'column'为竖向排列*/
            text-align: center;
            /*内容水平居中*/
        }

        .d211,
        .d212,
        .d213 {
            margin-top: 10px;
            /*设置字体大小*/
        }


        .d22 {
            background-image: linear-gradient(to bottom, rgb(0, 162, 255), rgb(0, 255, 60));
            /*背景颜色渐变*/
            flex: 1;
            /*使盒子铺满剩余位置*/
            margin-left: 10px;
            /*左边距*/
            margin-right: 10px;
            /*右边距*/
        }

        .d23 {
            background-image: linear-gradient(to bottom, rgb(0, 162, 255), rgb(0, 255, 60));
            /*背景颜色渐变*/
            width: 120px;
            /*盒子宽度*/
            display: flex;
            /*设置为弹性盒子属性*/
            flex-direction: column;
            /*盒子内排列方向*/
            /*'column'为竖向排列*/
            text-align: center;
            /*内容水平居中*/
        }
        .d231,.d232,.d233{
            margin-top: 10px;
            /*设置字体大小*/
        }

        .d3 {
            background-color: white;
            /*背景颜色*/
            height: 100px;
            /*盒子高度*/
        }
    </style>
</head>

<body>
    <!--上栏-->
    <div class="d1">
        TXT
    </div>
    <!--主页面-->
    <div class="d2">
        <!--左侧边栏-->
        <div class="d21">
            <div class="d211">
                <a href="../TXT/笔记">笔记</a>
            </div>
            <div class="d212">
                <a href="/图">图库</a>
            </div>
            <div class="d213">
                <a href=""></a>
            </div>
        </div>
        <!--主页面-->
        <div class="d22">
            <div class="221">
            </div>
        </div>
        <!--右侧边栏-->
        <div class="d23">
            <div class="231">
                <a href="https://www.runoob.com/">菜鸟教程</a>
            </div>
            <div class="232">
                <a href="https://developer.mozilla.org/zh-CN/docs/Learn/Getting_started_with_the_web">MDN</a>
            </div>
            <div class="233">
                <a href=""></a>
            </div>
        </div>
    </div>
    <!--下栏-->
    <div class="d3"></div>
</body>

</html>