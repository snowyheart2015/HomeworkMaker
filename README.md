# 怼熊孩 ——免费高效的假期作业自动生成器

> 你现在混成这样，就是因为寒假作业做的太少了。 —— 鲁迅

> 鲁迅没有说过上面那句话。 —— 白岩松

![what_is_spoiled_brat](image/spoiled_brat.jpg)

为了伟大的社会主义建设事业，为了短暂假期的平安喜乐，为了您和您私人财产的安全，您有权利与义务和我们一起彻底改造那些三天不打上房揭瓦的熊孩子们。本项目旨在**自动生成初等难度语文、数学、英语寒假作业题（适用于7-12岁熊孩子**，并且提供令家长爱不释手的精美PDF排版。原价二十块、三十块的练习册，现在统统只要几毛钱。

## 1 项目详情

本项目的宗旨是在顷刻之间生成大量寒暑假儿童作业，迅速地将熊孩子淹没在知识的汪洋大海中，从而达到拯救自己、拯救孩子、拯救社会主义接班人的目的。

我们的项目将会有这几个特点：1.**容易取得**；2.**全面覆盖**；3.**高度定制**

**容易取得**，指的是我们的项目成果非常的易于取得。在未来，本项目将会部署到多台服务器上，通过浏览器在线免费下载PDF的方式，造福各位的家长。我们希望有一天，您即使在下楼买彩票的短短几分钟内，也可以轻松地通过彩票站的打印机制作几公斤A4纸的家庭作业。据我们的专家分析，即使熊孩子烧毁了全部的假期作业，您也可以在45分钟内打印出11斤四两重的作业。

（遗憾的是，在短期内家长们只能通过命令行操作生成作业PDF，这需要家长们有一定的计算机基础）

**全面覆盖**，说的是我们的项目要覆盖小学生/初中生作业的方方面面。以目前的技术来看，生成大量的加减乘除和古诗文默写题目是非常容易的。这个技术虽然看上去很粗糙，但是实际上已经能给熊孩子造成大量伤害。未来，我们会应用计算机图形学、计算机视觉、自然语言处理等技术，制造更难更复杂的题目，例如立体几何、圆锥曲线、古文理解、英文翻译、语法练习等。

**高度定制**，意味着我们的项目具备“指哪打哪”的优秀作风。家长可以随意地定制题目的数量和长度，从10个小题到1000个小题，从2位数加减到5次方求根，我们无所不能。除此之外，每生成一份作业文件，我们就会 同步生成一份答案文件，方便家长校对熊孩子的试卷。最后，我们的每一份文件都会明显地打上日期时间戳水印和家长数字签名，从源头上根本性地杜绝了狡诈的熊孩子胡搞瞎搞的可能。


### 习题内容

本项目力求稳扎稳打，由浅入深，从应试教育覆盖到素质教育，让熊孩子不管用什么借口都无法逃离。目前，为止，我们的重点放在了语数英上，日后绝对是要加上政治历史地理生物物理化学的，这点您就放心吧。

数学题目

> 1. 二位数加减乘除
> 2. TODO

语文题目

> 1. 看词写拼音
> 2. 传统诗句填空默写
> 3. TODO

英语题目

> 1. TODO

### 呈现方式

程序在生成某份作业后，自动生成一份便于家长校对的标准答案。
为了防止伪造或其他作假，每份作业/答案上必须打印时间戳。
所有作业题目提供PDF格式的下载，PDF的规格由用户决定（例如A4，B4等）
题目的形式既可以是单项训练，也可以是全套测试考卷。 

## 2 进度规划（Draft）

### 起始（2018年上半年）

0. 收集小学/初中阶段的背诵资料文本文档，例如必备古诗文、各个阶段词汇表，并预处理成方便程序读取的格式；
1. 不考虑排版美观等成分，先实现成熟的自动作业生成算法流程，主要以百位内加减乘除、古诗文填空默写、英语词汇记忆为主；
2. 提供高度自定义的接口，自由配置题目数量、难度等；
3. 提供免安装的命令行脚本，便捷使用，提供PDF输出，实现初步可用；

### 短期（2018年下半年）

1. 提高PDF印刷质量，搭建LaTeX编译系统；
2. 构建快捷的DSL的语言，把作业题目快捷的注入到LaTeX中；
3. 针对学科特点写好PDF模板；

4. 收集小学高年级代数数学模型，例如二元一次方程、一元二次方程、表面积、体积、分数换算等内容；
5. 实现小学高年级代数题；

6. 收集小学高年级几何数学模型，例如三视图等；
6. 搭建绘图工具，攻克小学高年级几何；

### 中短期（2019年上半年）

1. 域名解析绑定，项目迁移到服务器上；
2. 完成网页前端和后端开发，暂时不考虑性能和安全；

3. 探究自然语言处理技术在小学语文期末作业中的应用，特别是阅读理解和命题作文；
4. 试用Image Caption技术完成小学生看图说话（语文或者英语）；
5. 用深度学习+语音技术探索小学英语听力的可行性；

6. 摸底初中物理化学学习资料与题目类型，完成数据预处理；
7. 实现简单的元素周期表和常用化学物质背诵测试；
8. 自动生成物理考试的实验题和简单应用题；
9. 用传统自然语言处理技术实现初级英语语法考试题目；

### 中期（2019年下半年）

1. 服务器多点异地备份，在华北华东华南和洛杉矶东京有云服务器（不知道怎么搞钱）；
2. 小学范围应试教育类题目80%覆盖，初中应试教育题目50%覆盖；

3. 提供免注册下载和注册下载并行的机制，完成注册的家长可以获得学业分析报告和更精准的作业推荐；
4. 实践用户画像和推荐系统，用数据勾勒熊孩子的特点；

5. 建立微信公众号、微信小程序，性感程序，在线发题。


### 中后期（2020年左右）

暂时想不到了

## 3 技术路线（Draft）

1. 建议选用Python生成习题内容，Python做DSL；
2. 为了提供精美的PDF排版效果，建议选择LaTeX作为PDF生成器（TexLive编译器）；
3. 建议等待本地应用开放完毕以后迁移到云服务器上（阿里云或者腾讯云）；
4. 网页后端暂时选择Python Django开发，视情况看是否迁移到Java/Go上；
5. 项目网站的域名是 www.homework-maker.com ，这个域名已经被我买了10年；
6. 目前本项目网站因为没钱没时间解析所以根本无法访问（前两天才买的），咱们下个月再挂Nginx吧；

## 参考资料

1.[how can i use latex from python](https://tex.stackexchange.com/questions/885/how-can-i-use-latex-from-python)

我个人感觉这是个很有意义的全栈训练项目，如果做的足够用心的话，说不定真的能给缺乏教育资源的初等学校提供帮助。

虽然现在一行代码都没加进来，但是我很认真的您知道伐？本人的微信号是vonLynnShawn，有兴趣参加工程的朋友可以加我一起讨论。您如果Pull Request或者Issue了麻烦发微信告诉我一声嗨。

![my_id](image/wechat_id.jpg)

祝您新年快乐。

Draft - Version 01 - 2018.2.14 