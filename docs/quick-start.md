# Your first ELab experiment

[简体中文](#zh-cn) · [Product overview](../README.md) · [Download status](download.md)

Once ELab is running, open the **Case Library**. Select the three-phase induction motor control and fault diagnosis case (**三相异步电动机智能控制与故障诊断**), then choose **Create project from case** to make an editable copy.

## Try the motor start/stop experiment

1. Open the **Simulation** tab and choose **Live Simulation** (**实时仿真**).
2. In the **Case Console**, choose **Close** on the circuit breaker (**QF1**). The motor should remain stopped.
3. Choose **Press** on the start pushbutton (**SB1**), then **Release**. Observe that the contactor stays engaged and the motor keeps running after the release.
4. Choose **Press** on the stop pushbutton (**SB2**), observe that the contactor releases and the motor stops, then choose **Release**.
5. Start the motor again. Choose **Trip** on the thermal overload relay (**FR1**) and observe the motor stop. Choose **Close session** when finished.

For a classroom exercise, ask learners to predict the motor state before each operation and trace the self-holding path on the schematic.

<a name="zh-cn"></a>

## 开始第一个 ELab 实验

[产品介绍](../README.zh-CN.md) · [下载状态](download.md#zh-cn)

打开 ELab 后，进入**案例库**，选择**三相异步电动机智能控制与故障诊断**，点击**从案例创建工程**，获得可编辑的工程副本。

<a name="motor-startstop-zh"></a>

### 电动机起保停实验

1. 切换到**仿真**页，选择**实时仿真**。
2. 在**操作台**选择断路器（**QF1**）的**合上**。此时电动机应保持停止。
3. 对启动按钮（**SB1**）选择**按下**，再选择**松开**。观察接触器保持吸合、电动机继续运行。
4. 对停止按钮（**SB2**）选择**按下**，观察接触器释放和电动机停止，再选择**松开**。
5. 再次启动电动机，选择热继电器（**FR1**）的**脱扣**，观察电动机停止。完成后点击**结束会话**。

课堂演示时，可让学生先预测每步操作后的电动机状态，再沿原理图查找自保持回路。
