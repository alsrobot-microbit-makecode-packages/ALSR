# Keyboard
The github address of the package is https://github.com/alsrobot-microbit-makecode-packages/ALSRobotKeyboard
The maintenance staff of the package is https://github.com/bobolx

The button module (for details, please visit: http://www.alsrobot.cn/goods-873.html) needs to be equipped with our company's micro:bit motor driver expansion board (for details, please visit: http://www.alsrobot.cn/goods-846.html) Use the 3P line (see http://www.alsrobot.cn/goods-786.html) and connect it to any of P0, P1 or P2.

## Button
//Connect to the p1 pin. If the S1 button is pressed, the following method returns true, otherwise it returns false.
KeyBoard.btnPressed(AnalogPin.P1, btnList.S1)

//Connect to the p1 pin. If any button is raised, the following method returns true, otherwise it returns false.
KeyBoard.btnreleased(AnalogPin.P1)

## Support

* for PXT/microbit

## License

MIT


# 模拟五大按键模块
软件包github地址为：https://github.com/alsrobot-microbit-makecode-packages/ALSRobotKeyboard
软件包修改维护人员：https://github.com/bobolx

该按键模块（详情请访问：http://www.alsrobot.cn/goods-873.html）需要与我们公司的micro:bit 电机驱动扩展板（详情请访问：http://www.alsrobot.cn/goods-846.html）使用3P线（详情请见：http://www.alsrobot.cn/goods-786.html）连接使用，可以接在P0、P1或者P2的任意一个

## 按钮
//连接p1引脚，如果S1按钮被按下则下面的方法返回true，否则返回false
KeyBoard.btnPressed(AnalogPin.P1, btnList.S1)

//连接p1引脚，如果任意按钮抬起则下面的方法返回true，否则返回false
KeyBoard.btnreleased(AnalogPin.P1)

## 支持

* for PXT/microbit

## License

MIT
