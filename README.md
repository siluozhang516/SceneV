# SceneV

<p align="center">
  <img src="/assets/logo_bgc.png" alt="SceneV Preview" width="50%">
</p>

**简单高效、精美规范、交互自然的低代码组态数据可视化**

#### 介绍

SceneV（Scene Visual）是一个强大的低代码数据可视化开发平台，专为工业组态和数据可视化大屏设计而打造。它让用户能够通过直观的拖拽操作，零代码或低代码方式快速构建专业级的可视化应用。

- **文档地址:** [https://api.meta2dthingsboard.cn/](https://api.meta2dthingsboard.cn/)
- **预览地址:** [https://meta2dthingsboard.cn/](https://meta2dthingsboard.cn/)

---

#### 项目效果

<div style="margin: 20px 0; border-radius: 8px; overflow: hidden">
  <video autoplay loop muted playsinline>
    <source src="/assets/video/Video_1.mp4" type="video/mp4">
    您的浏览器不支持 HTML5 视频标签。
  </video>
</div>


#### 物联网ThingsBoard数据对接

<div style="margin: 20px 0; border-radius: 8px; overflow: hidden">
  <video autoplay loop muted playsinline>
    <source src="/assets/video/Video_2.mp4" type="video/mp4">
    您的浏览器不支持 HTML5 视频标签。
  </video>
</div>

#### 项目截图
<p align="center">
  <img src="/assets/preview_1.png" alt="SceneV Preview">
</p>

<p align="center">
  <img src="/assets/preview_2.png" alt="SceneV Preview">
</p>
<p align="center">
  <img src="/assets/preview_3.png" alt="SceneV Preview">
</p>
<p align="center">
  <img src="/assets/preview_4.png" alt="SceneV Preview">
</p>
<p align="center">
  <img src="/assets/preview_5.png" alt="SceneV Preview">
</p>
### 核心功能

- **开箱即用**：丰富的组件库和模板，快速搭建专业可视化界面。
- **零代码开发**：无需编写复杂代码，通过配置即可实现复杂交互效果。
- **多数据源支持**：无缝集成 ThingsBoard、HTTP、 MQTT、WebSocket 等多种数据源。
- **实时数据展示**：支持动态数据绑定和实时更新，满足监控大屏需求。
- **响应式设计**：自动适配不同屏幕尺寸，确保在各种设备上完美展示。
- **高性能渲染**：基于 Canvas 的高性能渲染引擎，支持万级数据点流畅展示。
- **无缝对接 ThingsBoard**：通过 websocket 实时接入 ThingsBoard 设备数据。

### 工业级组态图支持

- **专业场景适配**：内置多类型工业组态图形，适配 SCADA、MES、能源监控等典型工业场景。
- **动态效果**：支持在地图上标注设备位置、连线表示通信关系，并可添加动态路径动画，模拟物流或数据流向。

### 多端适配能力

- **跨浏览器支持**：Chrome、Firefox、Edge、Safari 等主流浏览器。
- **移动端适配**：完美支持移动端 webview 方式访问。
- **全平台覆盖**：手机、平板、PC、大屏等多端展示。

### 强大的扩展能力

- **组件库扩展**
  - 控件扩展：支持自定义控件开发。
  - 图表扩展：可集成各类图表库。
  - 图形扩展：支持自定义图形绘制。
  - 图元扩展：可扩展基础图元类型。
  - 模板扩展：支持自定义模板保存与复用。
- **数据显示扩展**
  - 条件显示：根据数据条件动态显示/隐藏元素。
  - 数据格式化：自定义数据显示格式。
  - 自定义函数：支持JavaScript函数扩展数据处理。
- **交互事件扩展**
  - 系统消息：内置消息系统扩展。
  - 自定义消息：支持业务消息定义。
  - 生命周期Hook：提供完整生命周期钩子。
  - 系统接口：开放核心系统接口。
- **智能算法扩展**
  - 自定义拖拽算法：实现特殊拖拽行为。
  - 连线算法：支持自定义连线路径计算。
  - 布局算法：可扩展的自动布局算法。
- **动画扩展**
  - 逐帧动画：支持节点逐帧动画定义。
  - 算法动画：基于数学公式的动画效果。
  - 交互动画：用户交互触发的动画效果。
- **排版扩展**
  - 布局算法：支持自定义排版布局。
  - 响应式布局：自适应不同屏幕尺寸。
  - 栅格系统：灵活的网格布局支持。

### 技术路线

- **前端框架**：采用主流的 Vite + Vue3 + Element Plus。
- **底层技术**：Canvas。
- **消息通信**：支持 WebSocket、MQTT、HTTP、ThingsBoard。
- **浏览器支持**：Chrome、Firefox、Edge 等现代浏览器。
- **API 设计**：遵循 RESTful API 设计规范。
- **多端适配**：支持浏览器和移动端访问。
- **部署方式**：支持离线部署，可在线/离线更新。

### 适用场景

适用于任何需要将实时数据与图形化界面结合的场景。

- **物联网数字可视化**：实时展示物联网设备数据，实现设备状态监控与数据可视化分析。
- **工业智能制造组态**：构建智能工厂的可视化控制系统，实现生产流程的数字化管理。
- **触摸屏端UI**：为工业触摸屏设备定制直观易用的操作界面。
- **工控可视化**：工业控制系统的可视化监控，实现设备状态实时展示与远程控制。
- **零代码Web应用**：无需编程，通过拖拽方式快速构建专业级Web应用。
- **智慧工厂**：监控产线设备状态、能耗、良品率等。
- **城市物联网**：监控摄像头、环境传感器，利用热力图展示空气质量等。
- **能源管理**：显示电网负荷、光伏发电量，并设置报警阈值。
- **教育科研**：帮助学生快速搭建实验数据可视化界面。

## 交流 QQ 群

在这里，你可以与其他用户实时交流，获得帮助，分享你的项目，并参与到最新的功能讨论中。

- **QQ 群号**: `[1023284024]`
- **群二维码**:

  <img src="/assets/qq_group_qr.jpg" alt="QQ Group QR Code" width="250">
