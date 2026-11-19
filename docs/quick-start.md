# Your first ELab experiment

[简体中文](#zh-cn) · [Product overview](../README.md) · [Download status](download.md)

Once ELab is running, open the **Case Library**. Select the three-phase induction motor control and fault diagnosis case (**三相异步电动机智能控制与故障诊断**), then choose **Create project from case** to make an editable copy.

## Read the circuit

Find the main circuit breaker (**QF1**), Start (**SB1**), Stop (**SB2**), contactor (**KM1**), overload relay (**FR1**), and motor (**M1**). On the control circuit, locate KM1's normally open auxiliary contact **13–14** in the branch parallel to Start. Find the normally closed FR1 contact **91–92** in the control circuit and predict what happens when it opens.

## Try the motor start/stop experiment

1. Open the **Simulation** tab and choose **Live Simulation** (**实时仿真**).
2. In the **Case Console**, choose **Close** on the circuit breaker (**QF1**).
3. On the start pushbutton (**SB1**), choose **Press**, observe the circuit, then choose **Release**.
4. On the stop pushbutton (**SB2**), choose **Press**, observe the circuit, then choose **Release**.
5. Start the motor again and choose **Trip** on the thermal overload relay (**FR1**).

| Action | Expected observation |
| --- | --- |
| Close QF1 | The circuit is ready to start. KM1 is released and M1 is stopped. |
| Press SB1 | KM1 engages and M1 starts. |
| Release SB1 | The auxiliary contact holds KM1 in. M1 keeps running. |
| Press SB2 | The holding circuit opens. KM1 releases and M1 stops. |
| Restart and trip FR1 | The relay opens the control circuit. KM1 releases, M1 stops, and the event timeline records the trip. |

Compare the event timeline for the two stops. Note which device initiated each stop and which contact opened the holding path. If the motor does not restart after the trip, reset FR1 before pressing Start again. To keep a record, save the project and use **Export deliverables** while the session is open. Choose **Close session** when finished.

For a classroom exercise, hide the expected-results table until learners have made a prediction for each row. Ask them to trace the holding path and explain how a stop command and a protection trip open it.

<a name="zh-cn"></a>

## 开始第一个 ELab 实验

[产品介绍](../README.zh-CN.md) · [下载状态](download.md#zh-cn)

打开 ELab 后，进入**案例库**，选择**三相异步电动机智能控制与故障诊断**，点击**从案例创建工程**，获得可编辑的工程副本。

### 先读图

找到断路器（**QF1**）、启动按钮（**SB1**）、停止按钮（**SB2**）、接触器（**KM1**）、热继电器（**FR1**）和电动机（**M1**）。在控制回路里找出与启动按钮并联的 KM1 常开辅助触点 **13–14**，再找到 FR1 的常闭触点 **91–92**，判断它断开时会发生什么。

<a name="motor-startstop-zh"></a>

### 电动机起保停实验

1. 切换到**仿真**页，选择**实时仿真**。
2. 在**操作台**选择断路器（**QF1**）的**合上**。
3. 对启动按钮（**SB1**）选择**按下**，观察回路状态，再选择**松开**。
4. 对停止按钮（**SB2**）选择**按下**，观察回路状态，再选择**松开**。
5. 再次启动电动机，选择热继电器（**FR1**）的**脱扣**。

| 操作 | 预期现象 |
| --- | --- |
| 合上 QF1 | 回路可以接受启动命令，KM1 保持释放，M1 停止。 |
| 按下 SB1 | KM1 吸合，M1 启动。 |
| 松开 SB1 | 辅助触点维持 KM1 吸合，M1 继续运行。 |
| 按下 SB2 | 自保持回路断开，KM1 释放，M1 停止。 |
| 再次启动并脱扣 FR1 | 热继电器断开控制回路，KM1 释放，M1 停止，事件时间线记录脱扣。 |

对照两次停机的事件时间线，记录哪一个器件引发了停机，哪一副触点切断了自保持回路。脱扣后如需再次启动，先复位 FR1，再按启动按钮。如需保留本次记录，请保存工程，并在会话打开时选择**导出成果包**。完成后点击**结束会话**。

课堂演示时，可先遮住结果列，请学生逐项预测，再沿原理图追踪自保持回路，说明停止按钮和保护脱扣分别如何将它断开。
