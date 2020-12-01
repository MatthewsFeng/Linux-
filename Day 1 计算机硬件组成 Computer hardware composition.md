# Day 1 计算机硬件组成 Computer hardware composition

## 一 PC与服务器 PC and servers

A desktop computer system typically runs a user-friendly operating system and desktop applications to facilitate desktop-oriented tasks. In contrast, a server manages all network resources. Servers are often dedicated (meaning it performs no other task besides server tasks)

个人计算机系统通常运行简便的操作系统和桌面应用程序。相反，服务器管理所有的网络资源。服务器通常是专用的(这意味着它不执行服务器任务之外的其他任务)



### 服务器的特点 Features of servers

- The ability to update hardware and software without a restart or reboot.

- Advanced backup capability for frequent backup of critical data.

- Advanced networking performance.

- Automatic (invisible to the user) data transfer between devices.

- High security for resources, data and memory protection.

  

- 不需要重新启动或重新启动就可以更新硬件和软件。

- 先进的备份能力，频繁备份的关键数据。

- 先进的网络性能。

- 设备之间自动(对用户不可见)数据传输。

- 资源、数据和内存保护的高安全性。

## 二 服务器分类 Server classification

### 按尺寸 By size

可分为1u , 2u, 4u

The classification by size can be divided into 1u , 2u, 4u

1u = 1.75 inches = 4.45 cm

### 按外形 By shape

可分为塔式服务器和机架式服务器和刀片服务器

it can be divided into tower server, rack server and blade server

![Difference-between-Rack-servers-and-Blade-Servers](C:\Users\Administrator\Desktop\Difference-between-Rack-servers-and-Blade-Servers.png)

The main difference between rack server & blade server is A Rack Server is an independent server installed in the case, while Blade Servers need to work with each other in one chassis.

机架服务器和刀片服务器的主要区别是机架服务器是安装在案例中的独立服务器，而刀片服务器需要在一个机箱中相互协作。

#### 机架式服务器 Rack Server

- Rack server acts as the **lone rider** of all the needed components as a **single powerful system**. Rack servers could perform powerfully to run **high-end applications**.
- Rack servers are convenient to **fit** as it **consumes less** amount of physical space.
- Rack servers are usually equipped with **internal fans**, increasing airflows which makes it’s **cooling more easier**.
- Rack servers can be **highly efficient** when you require more than one server as they don’t require a **huge chassis**.

机架服务器作为一个强大的系统，作为所有需要的组件的独行侠。机架服务器可以强大地运行高端应用程序。

机架服务器非常方便，因为它消耗较少的物理空间。

机架服务器通常配备内部风扇，增加空气流量，使其更容易冷却。

机架服务器在需要多个服务器时可以非常高效，因为它们不需要巨大的机箱。

#### 刀片服务器 Blade Server

- Blade servers can enable their massive chassis to **supply power** to multiple servers which **reduces** total power consumption for each blade server.

- Blade servers promote **Hot-swappable** features which could provide you **redundancy** when one blade faces a problem making it to be pulled and replaced much more **easily**.

- Blade servers require **only one cable** (often fiber) for running to the chassis which **reduces** the use of individual cables running for each **blade server**.

- Blade servers require **minimal space** and at the same time provide **high processing power**.

  刀片服务器可以使其庞大的机箱为多个服务器提供电源，从而减少每个刀片服务器的总电源消耗。

  刀片服务器提倡热插拔功能，当一个刀片服务器遇到问题时，可以提供冗余，使其更容易提取和替换。

  刀片服务器只需要一条电缆(通常是光纤)就可以运行到机箱，这减少了为每个刀片服务器运行单独电缆的使用。

  刀片服务器需要最少的空间，同时提供高处理能力。

#### 塔式服务器 Tower Server

A tower server is a computer intended for use as a server and built in an upright cabinet that stands alone. The cabinet, called a tower, is similar in size and shape to the cabinet for a tower-style personal computer. This is in contrast to rack server s or blade server s, which are designed to be rack-mounted 

在大小和形状上与塔式个人电脑机柜相似

## 三 服务器品牌 Server brand

#### DELL  戴尔

#### HP 惠普

## 四 去IOE 运动 Take off IOE

### I=IBM (minicomputer)

### O=Oracle  (datebase)

### E=EMC (memory device)

第一个是指IT架构的更新换代，具体说就是以IBM为代表的主机、以ORACLE为代表的关系型数据库，以及以EMC为代表的高端存储设备，被新型的云计算技术所替换，也就是我们常说的“云化”。

第二个是指针对外国IT设备，特别是美国产品的“严打”，减少甚至不再购买IBM、ORACLE、EMC等企业的产品。

第三，是建立与支撑系统云化配套的运行维护管理体系。

## 五 电脑和服务器的主要构成

### 主机 host machine

#### 内存 Internal storage

#### 中央处理器 CPU Central Processing Unit

#### 主板 Main board

### 外设 device

#### 存储 storage

##### 磁盘 disk

##### 光盘 optical disk

##### 闪存 flash memory

#### 输入设备 Input device

##### 键盘 keyboard

鼠标 mouse

扫描仪 scanister

摄像头 webcam

#### 输出设备 Output device

##### 显示卡 display card

显示器 display

音箱 loudspeaker box

打印机 printer

### 服务器组成  Server composition

#### 机箱 Case

#### 电源 Power supply - the heart 

##### 不间断电源 UPS uninterruptible power system

#### 中央处理器 CPU - the brain

##### 风扇 fan

A fan on top of a computer processor. It helps pull and blow hot air off the processor, helping keep it cooler.

#### 硬盘 Hard disk

机械硬盘 HDD hard disk drive

固态硬盘 SSD solid state drive

硬盘接口 hard disk interface

##### SAS

SATA

#### 磁盘阵列 Raid  Redundant Arrays of Independent disks

##### Raid 0

It's also known as "disk striping." With **RAID 0**, data is written across multiple disks. This **means** the work that the computer is doing is handled by multiple disks rather than just one, increasing performance because multiple drives are reading and writing data, improving disk I/O. A minimum of two disks is required.

在raid0中，数据是跨多个磁盘写入的。这意味着计算机所做的工作是由多个磁盘而不是一个磁盘来处理的，由于多个驱动器正在读取和写入数据，从而提高了性能，提高了磁盘I/O。至少需要两个磁盘。

##### Raid 1

A popular disk or solid state drive (SSD) subsystem that increases safety by writing the same data on two drives. Called "mirroring," **RAID 1** does not increase performance. However, if one drive fails, the second drive is used, and the failed drive is manually replaced.

通过在两个驱动器上写入相同的数据来提高安全性。被称为“镜像”的 raid1 不会提高性能。但是，如果一个驱动器出现故障，则使用第二个驱动器，并手动替换出现故障的驱动器。

##### Raid 5

**RAID 5** is a unique version of **RAID** that uses something called **RAID** parity. This technique uses parity information or bonus data to calculate any lost information. Parity is distributed among all drives in the **RAID**. **RAID 5** requires roughly one free drive worth of space to store the parity

raid5是使用RAID奇偶校验的独特版本。这种技术使用奇偶校验信息或奖励数据来计算任何丢失的信息。奇偶校验分布在RAID中的所有驱动器中。RAID 5需要大约一个自由驱动器的空间来存储奇偶校验

##### Raid 10

**RAID 10**, also known as **RAID** 1+0, is a **RAID** configuration that combines disk mirroring and disk striping to protect data. It requires a minimum of four disks and stripes data across mirrored pairs. As long as one disk in each mirrored pair is functional, data can be retrieved

raid10，也称为raid1+0，是一种结合磁盘镜像和磁盘条带保护数据的RAID配置。它需要至少四个磁盘和横跨镜像对的条纹数据。只要每个镜像对中有一个磁盘是有效的，就可以检索数据

### 六 计算机体系三层结构与优化

##### The three-layer structure and optimization of computer system

应用程序 application program

操作系统 operating system

计算机硬件 computer hardware

### 运维的职责 duty of operation and maintenance

##### 监控 monitor

备份 backups

优化 optimize



# Day 1 exercise

##### 1.你用过的服务器型号有哪些？配置如何？

What server models have you used?How is the configuration?

Dell r720 2u 双路，4个SAS硬盘 32G

1个CPU 4核 16G



##### 2.程序、进程和守护进程的区别

The difference between programs, processes and daemon processes



##### 3.提升用户体验的网站解决方案

Web solutions that enhance the user experience



##### 4. buffer与cache区别

The difference between buffer and cache



##### 5.描述Raid 0 1的特点

Describe the characteristics of Raid 0 1

###### Raid 0- disk striping 条带化

速度快，无冗余，容量无损失

Fast speed, no redundancy, no loss of capacity

###### Raid 1 mirroring  镜像

100%冗余，容量损失半，最安全

100% redundancy, half capacity loss，the most secure



