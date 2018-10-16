# Keyboard
软件包github地址为：https://github.com/alsrobot-microbit-makecode-packages/ALSRobotKeyboard
软件包修改维护人员：https://github.com/bobolx

该按键模块（详情请访问：http://www.alsrobot.cn/goods-873.html）需要与我们公司的micro:bit 电机驱动扩展板（详情请访问：http://www.alsrobot.cn/goods-846.html）连接microbit使用，可以接在P0、P1或者P2的任意一个

## 按钮
//连接p1引脚，S1按钮被按下，如果按钮被按下则下面的方法返回true，否则返回false
KeyBoard.btnPressed(AnalogPin.P1, btnList.S1)

//连接p1引脚，如果任意按钮抬起则下面的方法返回true，否则返回false
KeyBoard.btnreleased(AnalogPin.P1)

## 支持

* for PXT/microbit

## License

MIT