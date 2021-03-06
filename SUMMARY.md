# Summary

* [Introduction](README.md)
* [贡献代码](contribution.md)
* [1 概述](1/1.Overview.md)
* [2 参考标准](2/2.Normative_references.md)
* [3 术语定义](3/3.Definitions.md)
* [4 缩略语](4/4 Acronyms_and_abbreviations.md)
* [5 通用描述](5/5.General_description.md)
   * [5.1 简介](5/5.1.Introduction.md)
   * [5.2  IEEE 802.15.4 WPAN 的组成](5/5.2.omponents_of_the_IEEE_802.15.4_WPAN.md)
   * [5.3 网络拓扑](5/5.3 Network topologies.md)
       * [5.3.1 星型网络](5/5.3.1 Star network formation.md)
       * [5.3.2 对等网络](5/5.3.2 Peer-to-peer network formation.md)
   * [5.4 架构](5/5.4 Architecture.md)
       * [5.4.1 物理层 PHY](5/5.4.1 physical_layer_phy.md)
       * [5.4.2 MAC 子层](5/5.4.2 MAC sublayer.md)
   * [5.5 功能概述](5/5.5 Functional overview.md)
       * [5.5.1 超帧结构](5/5.5.1 Superframe structure.md)
       * [5.5.2 数据传输模型](5/5.5.2 Data transfer model.md)
       * [5.5.3 帧结构](5/5.5.3 Frame structure.md)
       * [5.5.4 提高成功传输的概率](5/5.5.4 Improving probability of successful delivery.md)
       * [5.5.5 电源消耗](5/5.5.5 Power consumption considerations.md)
       * [5.5.6 安全](5/5.5.6 Security.md)
   * [5.6 原语的概念](5/5.6 Concept of primitives.md)
* [6 物理层规范](6/6. PHY specification.md)
   * [6.1 通用需求和定义](6/6.1.General_requirements_and_definitions.md)
   * [6.2 物理层范围规范](6/6.2 PHY service specifications.md)
   * [6.3 PPDU 格式](6/6.3 PPDU format.md)
   * [6.4 PHY 常量 和 PIB 属性](6/6.4 PHY constants and PIB attributes.md)
   * [6.5 2450 MHz 规范](6/6.5 2450 MHz PHY specifications.md)
   * [6.6 868/916 MHz BPSK 规范](6/6.6 mhz_band_binary_phase-shift_keying_bpsk.md)
   * [6.7 868/915 MHz ASK 规范](6/6.7 mhz_band_optional.md)
   * [6.8 868/915 MHz O-QPSK 规范](6/6.8 mhz_band_optional.md)
   * [6.9 通用无线规范](6/6.9 General radio specifications.md)
* [7 MAC 子层规范](7/7.MAC_sublayer_specification.md)
   * [7.1 MAC 子层服务规范](7/7.1 MAC sublayer service specification.md)
       * [7.1.1 MAC 数据服务](7/7.1.1 MAC data service.md)
       * [7.1.2 MAC 管理服务](7/7.1.2 MAC management service.md)
       * [7.1.3 关联原语](7/7.1.3 Association primitives.md)
       * [7.1.4 解关联原语](7/7.1.4 Disassociation primitives.md)
       * [7.1.5 信标帧通知原语](7/7.1.5 Beacon notification primitive.md)
       * [7.1.6 读取 PIB 属性原语](7/7.1.6 Primitives for reading PIB attributes.md)
       * [7.1.7 GTS  管理原语](7/7.1.7 GTS management primitives.md)
       * [7.1.8 孤立通知原语](7/7.1.8 Primitives for orphan notification.md)
       * [7.1.9 MAC 子层服务原语](7/7.1.9 Primitives for resetting the MAC sublayer.md)
       * [7.1.10 接收器时间使能原语](7/7.1.10 Primitives for specifying the receiver enable time.md)
       * [7.1.11 信道扫描原语](7/7.1.11 Primitives for channel scanning.md)
       * [7.1.12 通信状态原语](7/7.1.12 Communication status primitive.md)
       * [7.1.13 写 PIB 属性原语](7/7.1.13 Primitives for writing PIB attributes.md)
       * [7.1.14 更新超帧结构原语](7/7.1.14 Primitives for updating the superframe configuration.md)
       * [7.1.15 与协调器同步原语](7/7.1.15 Primitives for synchronizing with a coordinator.md)
       * [7.1.16 从协调器请求数据原语](7/7.1.16 Primitives for requesting data from a coordinator.md)
       * [7.1.17 MAC 枚举描述](7/7.1.17 MAC enumeration description.md)
   * [7.2 MAC 帧格式](7/7.2 MAC frame formats.md)
       * [7.2.1 通用 MAC 帧格式](7/7.2.1 General MAC frame format.md)
       * [7.2.2 私有帧格式](7/7.2.2 Format of individual frame types.md)
       * [7.2.3 帧兼容性](7/7.2.3 Frame compatibility.md)
   * [7.3 MAC 命令帧](7/7.3 MAC command frames.md)
       * [7.3.1 关联请求命令](7/7.3.1 Association request command.md)
       * [7.3.2 关联响应命令](7/7.3.2 Association response command.md)
       * [7.3.3 解关联通知命令](7/7.3.3 Disassociation notification command.md)
       * [7.3.4 数据请求命令](7/7.3.4 Data request command.md)
       * [7.3.5 PAN ID 冲突通知命令](7/7.3.5 PAN ID conflict notification command.md)
       * [7.3.6 孤立通知命令](7/7.3.6 Orphan notification command.md)
       * [7.3.7 信标请求命令](7/7.3.7 Beacon request command.md)
       * [7.3.8 协调器重组命令](7/7.3.8 Coordinator realignment command.md)
       * [7.3.9 GTS 请求命令](7/7.3.9 GTS request command.md)
   * [7.4 MAC 常量和 PIB 属性](7/7.4 MAC constants and PIB attributes.md)
       * [7.4.1 MAC 常量](7/7.4.1 MAC constants.md)
       * [7.4.2 MAC PIB 属性](7/7.4.2 MAC PIB attributes.md)
   * [7.5 MAC 功能描述](7/7.5 MAC functional description.md)
       * [7.5.1 信道访问](7/7.5.1 Channel access.md)
           * [7.5.1.1 超帧结构](7/7.5.1.1 Superframe structure.md)
           * [7.5.1.2 超帧收发时序](7/7.5.1.2 Incoming and outgoing superframe timing.md)
           * [7.5.1.3 帧间间隔（IFS）](7/7513_interframe_spacing_ifs.md)
           * [7.5.1.4 CSMA/CA 算法](7/7.5.1.4 CSMA-CA algorithm.md)
       * [7.5.2 启动、维护 PAN](7/7.5.2 Starting and maintaining PANs.md)
           * [7.5.2.1 扫描信道](7/7.5.2.1 Scanning through channels.md)
               * [7.5.2.1.1 ED 信道扫描](7/7.5.2.1.1 ED channel scan.md)
               * [7.5.2.1.2 主动信道扫描](7/7.5.2.1.2 Active channel scan.md)
               * 7.5.2.1.3 被动信道扫描
               * 7.5.2.1.4 孤立信道扫描
           * [7.5.2.2 PAN 标识符冲突检测](7/7.5.2.2 PAN identifier conflict resolution.md)
           * 7.5.2.3 启动网络和重新组网
           * 7.5.2.4 产生信标
           * 7.2.5.5 发现设备
       * [7.5.3 关联和解关联](7/7.5.3 Association and disassociation.md)
       * [7.5.4 同步](7/7.5.4 Synchronization.md)
       * [7.5.5 事务处理](7/7.5.5 Transaction handling.md)
       * [7.5.6 传输、接收和确认](7/7.5.6 Transmission, reception, and acknowledgment.md)
       * [7.5.7 GTS 分配和管理](7/7.5.7 GTS allocation and management.md)
       * [7.5.8 帧安全](7/7.5.8 Frame security.md)
   * [7.6 安全规范](7/7.6 Security suite specifications.md)
       * [7.6.1 PIB 安全材料](7/7.6.1 PIB security material.md)
       * [7.6.2 附加安全头](7/7.6.2 Auxiliary security header.md)
       * [7.6.3 安全操作](7/7.6.3 Security operations.md)
   * [7.7 消息队列图表](7/7.7 Message sequence charts illustrating MAC-PHY interaction.md)
* 附录 A
* 附录 B
* 附录 C
* 附录 D
* 附录 E
* 附录 F
* 附录 G

