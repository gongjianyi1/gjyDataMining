# gjyDataMining
# 步骤一：建立一个GitHub仓库

首先在github中注册并登录自己的github账号：
![1](https://github.com/gongjianyi1/gjyDataMining/assets/167768150/69b2051e-85ac-434f-b0a9-313aba63cbee)
随后登录后直接进入GitHub主页右上角点击加号新建一个仓库：
![2](https://github.com/gongjianyi1/gjyDataMining/assets/167768150/100c47c7-aa8a-404d-843a-9db2e04eb219)
填入仓库名，其余选项的说明如图所示，这样我们便建立好了属于自己的一个仓库。
![3](https://github.com/gongjianyi1/gjyDataMining/assets/167768150/5a40cd1b-c60d-4819-83c0-d827c0882a9b)
![4](https://github.com/gongjianyi1/gjyDataMining/assets/167768150/0fb94243-fdca-4965-9d55-3f1bb4ecfe05)
我们创建好之后，这是你可以看到一个README.md的文件，这个文件中是你的仓库的概要、使用流程、许可协议等信息。

https://github.com/gongjianyi1/gjyDataMining.git

OK啦，GitHub创建自己的仓库就已经完成了。

# 步骤二：ppt等文件的传入

我们点击“add file”在本地上传所需的ppt导入到自己的github仓库中，上传 PowerPoint 到 GitHub 仓库可以通过以下步骤完成：

1. **将 PowerPoint 文件保存在本地**

   将你的 PowerPoint 文件保存在你的计算机上一个方便的位置，以便稍后上传到 GitHub。

2. **打开 GitHub 仓库**

   在浏览器中登录 GitHub，并打开你的目标仓库（即你创建的名为 xxDataMining 的仓库）。

3. **点击 "Upload files"**

   在仓库页面的右侧，你会看到一个绿色按钮 "Add file"，点击它并选择 "Upload files"。

4. **选择文件并上传**

   点击 "Choose your files" 或者直接将 PowerPoint 文件拖拽到浏览器中。

   选择你想要上传的 PowerPoint 文件，然后点击 "Open"。

5. **提交更改**

   文件上传完成后，你会在页面底部看到一个绿色按钮，上面写着 "Commit changes"。点击这个按钮。

6. **填写提交信息**

   在弹出的对话框中，输入一个简短但描述性的提交信息，描述你上传的文件，然后点击 "Commit changes"。

7. **等待上传完成**

   GitHub 将会自动上传你的文件，并将其保存到你的仓库中。

现在，你的 PowerPoint 文件已经成功上传到你的 GitHub 仓库中了。其他人可以在你的仓库中找到并查看它。
![5](https://github.com/gongjianyi1/gjyDataMining/assets/167768150/b9d53178-248a-4b2d-91d0-90e4cc73296b)
![6](https://github.com/gongjianyi1/gjyDataMining/assets/167768150/0c427c96-6355-491c-adab-892b7399d994)
# 步骤三：记录想学习或获得的计算机技能

因为我的个人研究方向是生化反应网络与控制中混沌系统相结合的方向，所以在平时的仿真实验会经常用到matlab，所以在理论推导的基础上我更想学习一下关于matlab仿真有关知识。具体是指，比如我们定义好一个混沌系统的参数以及ode后，接下来我们会分析它接下来表现出怎样的动力学特性，所以研究混沌系统初始的相图、分岔图以及李亚普诺夫指数谱对于我们接下来分析混沌系统同步以及多级通信是十分重要的一环，所以我比较想学习的是有关混沌系统的动力学分析。

接下来是我已经完成的工作，我在这个过程中收获到了许多的知识：

首先我想具体介绍一下我所做的研究方向是基于DNA链位移的超混沌系统耦合投影同步及其加密通信，具体工作如下：

## 1.基于DNA化学反应网络(DNA CRNs)的两个混沌系统的完全同步及其安全通信问题。单级混沌保密通信系统的安全性引起了人们的关注。提出了一种基于DNA crn的多级安全通信方案。首先，利用DNA CRNs构建了一个由催化、双元、凝聚和湮灭模块组成的三变量混沌系统。

## 2.其次，根据非线性系统的稳定性原理，采用DNA crn实现了三个混沌系统的耦合投影同步，并对同步结果进行了讨论。最后，利用DNA CRNs设计正弦和余弦信号。将这些信号叠加到三个系统中，实现多级加解密。

## 3.此外，还考虑了干扰项，对系统的鲁棒性进行了检验。结果表明，该方案具有较高的安全性，能够在存在干扰的情况下通过多级传输对生物信号进行有效的加解密。

我们首先利用DSD建立了一个新的三变量混沌系统，然后来分析它的动力学特性。
![7](https://github.com/gongjianyi1/gjyDataMining/assets/167768150/ec14c27d-fe5e-4323-952c-d4032bad1d3b)
通过观察 Lyapunov 指数谱的轨迹分布，可以确定非线性系统在特定参数区间是否为混沌。对于非线性系统来说，若该系统的运动状态为稳定运动或周期运动，其不可能存在大于零的 Lyapunov 指数。若该系统为周期运动，则其 Lyapunov 指数全为负；若为周期或拟周期运动，则其最大 Lyapunov 指数为 0，其余 Lyapunov 指数为0 或负数。若该系统至少存在一个正的 Lyapunov 指数，则可确定该系统做混沌运动。

随后利用耦合投影同步来使得我们的系统进行同步。
![8](https://github.com/gongjianyi1/gjyDataMining/assets/167768150/3fd3eac5-4477-4c4b-a303-17eee5b68ba1)
通过visualdsd软件验证了耦合投影同步的正确性。三个系统的的浓度值具有一定的比例关系。将系统的混沌信号放大两次，并与系统的混沌信号同步。添加合适的耦合项对其进行同步，分别两两计算出两个系统之间的误差后，我们发现将系统的混沌信号放大一次，并与系统的混沌信号同步。三个系统的相图如图所示。也可以看出，这三个系统之间存在比例关系，同时误差归0完成同步。
![9](https://github.com/gongjianyi1/gjyDataMining/assets/167768150/45fd1c0d-c1c3-4d5b-95c4-5ccff821b677)
最后完成多级通信方案，在该方案中，混沌掩蔽用于安全通信。它的思想是传输信号被调制用一个混沌信号组成一个混合信号，将其送入信道。接收系统在接收到混合信号后，由于发送系统与接收系统是同步的，因此接收系统可以从混合信号中解密发送信号。安全方案图如图7所示，其中ml(l = 1,2，…)， 6)为传输信号;Sl是混合信号;M * l是一个解密信号。由发送信号ml与混沌信号x2、y3叠加形成的混合信号sl由发送系统i送入信道，混合信号sl经α倍放大后由发送系统II接收。接收到αsl后，发送系统II可与发送系统i实现投影同步，αsl连续发送至信道，经β倍放大后得到αβsl。当αβsl被接收系统接收时，发送系统I、发送系统II和接收系统可以实现投影同步。因此，可以从接收机的混合信号中消除混沌信号，恢复发射信号。当发送系统、发送系统和接收系统同步时，得到x2 = z2αβ和y3 = z3β。发射信号可以从接收系统解密:m * l = sl−z2αβ−z3β。
![10](https://github.com/gongjianyi1/gjyDataMining/assets/167768150/3dae5271-cd88-4fc6-962a-91ea118d49b3)
在后续的仿真实验中，我们引入了一组余弦函数来验证加密通信的可行性，实验结果如图所示，其中第一张图表示初始信号。第二张表示初始信号和混沌信号组成的混合信号，最后一张图发现我们可以几乎不失真的恢复进入系统的初始信号。
![11](https://github.com/gongjianyi1/gjyDataMining/assets/167768150/d3734db5-ee2f-4cec-817b-3423ca66e503)
![12](https://github.com/gongjianyi1/gjyDataMining/assets/167768150/77f118f0-c0e6-4a98-82f9-cbb6e49a47e7)
![13](https://github.com/gongjianyi1/gjyDataMining/assets/167768150/1b478d0a-4b35-4233-99ce-bb021bd965f2)






