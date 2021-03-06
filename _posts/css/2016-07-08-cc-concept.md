---
layout: single
title: "计算传播学的起源、概念和应用"
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/unsplash-image-6.jpg
  cta_label: "Read More"
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "计算传播是指数据驱动的、借助于可计算方法所进行的传播过程，而分析计算传播现象的研究领域就是计算传播学。本文首先分析了计算传播的起源、概念和应用，然后从计算社会科学的角度对计算传播学的理论脉络进行了介绍。"
modified: 2016-07-08T11:55:22-04:00
comments: true
author_profile: true
author: "王成军"
---

{% include toc title="Table" icon="file-text" %}

计算传播是指数据驱动的、借助于可计算方法所进行的传播过程，而分析计算传播现象的研究领域就是计算传播学。本文首先分析了计算传播的起源、概念和应用，然后从计算社会科学的角度对计算传播学的理论脉络进行了介绍。基于以上内容，本文介绍了一个计算传播学研究的例子——“新闻地图”研究项目。新闻地图采用Gdelt新闻数据，以可视化的方式呈现了新闻事件的时空分布，并对新闻人物排名提供了一种可计算的思路，研究发现新闻影响力具有一个放大的机制，这种机制是通过新闻引用来实现的。最后讨论了计算传播学研究中存在的从数据到模式，再从模式到机制的研究思路。

<p>关键词：大数据；计算传播学；数据驱动；计算社会科学；新闻地图</p>
<p>来源：王成军 (2016) 计算传播学的起源、概念与应用. 编辑学刊,3:59-64. <a href="http://www.cnki.net/KCMS/detail/detail.aspx?QueryID=18&amp;CurRec=1&amp;recid=&amp;filename=BJXZ201603016&amp;dbname=CJFDTEMP&amp;dbcode=CJFQ&amp;pr=&amp;urlid=&amp;yx=&amp;v=MTIzODIxTHV4WVM3RGgxVDNxVHJXTTFGckNVUkx5ZllPWm5GQ3ZsVmIzTEp5ZlRkTEc0SDlmTXJJOUVZb1I4ZVg=">CNKI下载</a></p>

## 一、引言：计算传播
<p>计算传播是指数据驱动的、借助于可计算方法所进行的传播过程，而分析计算传播现象的研究领域就是计算传播学(王成军, 2015)。计算传播的应用有很多，例如数据新闻、计算广告、媒体推荐系统等，在过去的几年里，产生了深远的影响。数据新闻风靡全球，重要的国际媒体和国内媒体纷纷采用数据新闻，以开放数据、数据挖掘、可视化的方式提供信息；计算广告备受瞩目，不管是门户网站、搜索引擎，还是社交媒体，纷纷将计算广告当做数据变现的重要渠道，以可计算的方法对广告进行拍卖，实现媒体、内容和用户三方的匹配；媒体推荐系统成为个性化信息获取的重要途径，既包括传统的社交新闻网站，也包括今日头条这种后起之秀，它们纷纷采用协同过滤的方法为用户提供信息，建立了新的信息把关模式。</p>
<p>计算传播作为一种具有重要现实影响的传播行为，它的起源相对较早。例如，网飞公司（Netflix）在九十年代初以邮寄电影光盘作为商业模式，从传播的角度而言，这种商业模式使得用户可以更加自由地选择和观看视频内容，因而具有变革传统媒介消费行为的潜力。对于这个时期的网飞公司而言，很重要的一个问题就是邮寄时间的长短与用户的持续使用行为之间的关系。如果用户对于邮寄时间并不敏感，那么就可以将仓库建在地价低廉的郊区；如果用户对于邮寄时间非常敏感，那么网飞就需要在可承担的范围内将仓库建在距离市区近的地方。而调整仓库的地理位置的决定必须通过计算真实的用户数据才能决定。网飞仅仅是计算传播的一个例子。从更广义的视角来看，搜索引擎的基本社会功能也是计算传播。例如，谷歌的最根本的技术在于其pagerank算法，而这个算法的基本优化目标在于评估每一个网页内容的传播价值，而完成这一目标根本方法就在于计算。反过来经过计算的所得到的搜索结果质量更高，传播效果更好。</p>
<p>驱动计算传播的数据主要来自于人类使用数字媒体时记录下来的数字痕迹（digital traces）。数字媒体使得用户行为可以被详细记载，因而大量地累积了各种用户属性数据和行为数据。例如，当我们通过有线电视观看电视节目的时候、通过手机打电话的时候、通过互联网在网上冲浪的时候、查看微信朋友圈的时候，我们的行为都被电子媒体详细记录下来。数字化的信息不断地改变着传统的传播格局。有线电视服务提供商通过机顶盒获取的用户观看电视的行为对电视节目进行评价，计算不同电视频道在不同时间段的收视率。用户通过网飞网站订观看电影和电视节目的过程中，网飞记录了所有用户的详细数据，除了基本的用户信息、电视剧和电影信息，还包括用户的各种行为数据，例如对视频的订阅、观看、评价、搜索、收藏等。</p>
<p>可计算的方法使得沉睡的数据宝藏开始觉醒。随着计算技术的发展，人类计算能力不断提高，可以分析和挖掘的数据规模不断扩大。统计、机器学习、自然语言处理等数据挖掘技术更广泛地应用到计算传播的过程当中。仍然以网飞为例，基于所积累的丰富数据，网飞建立了高效的推荐系统。为了更有效地提高其推荐系统的推荐效果，网飞举办了两次轰动全球的百万大奖比赛。来自全世界160多个国家的参赛者采用机器学习的方法对网飞的用户数据进行分析，经过三年时间成功地解决了一个巨大挑战：为已有评级的网飞用户预测其对新影片的喜好。计算技术的提高有时候需要深入到模型的高度。例如，谷歌放弃了将一个个网页看作是孤岛的思维方式，转而将这些网页看做网络当中的节点，节点之间由超链接（hyperlink）连接起来。pagerank算法其实质是一个崭新的网络模型。搜索引擎将全世界的网页构成的庞大网络作为数据。毫无疑问这种数据规模是非常大的，对这些数据进行计算所需要的计算量也是非常大的。但是与数据量和计算量相比，谷歌的例子告诉我们建立一个高效的模型更加重要。</p>
<p>计算传播作为一个崭新的研究领域，需要研究者投入更多的注意力。分析计算传播应用、从传播学的角度研究计算传播的实际问题具有不可忽略的意义，反过来讲，分析和总结计算传播学的研究方式，对于传播学自身的发展而言也具有重要意义。本文以上内容对于计算传播的概念、特点和应用进行了简单介绍，在以下内容当中，我们将首先从研究脉络的角度梳理计算传播的起源，然后从一个计算传播的实际项目“新闻地图”出发，进一步介绍计算传播以及计算传播学的研究方法和意义。</p>

## 二、作为计算社会科学的计算传播学
<p>虽然计算传播应用早已存在，但是作为一个概念，计算传播和计算传播学的提出主要源于计算社会科学的发展。直到计算社会科学成为研究热点之后，计算传播作为一个概念才正式被提出(王成军, 2015; 祝建华 et al., 2014)。2009年，社会科学研究者David Lazer、Alex Pentland、Sinan Aral、Nicholas Christakis、Noshir Contractor、James Fowler、Myron Gutmann、Devon Brewer等人与作为计算机科学家的Lada Adamic以及作为网络科学研究者的Albert Barabasi在《科学》杂志上发表了一篇题为“计算社会科学”的论文，开启了计算社会科学的研究热潮(Lazer, Pentland, Adamic, &amp; Aral, 2009)。Lazer等人指出随着用于研究的数据不断增多以及人类的计算能力不断增强，采用计算作为研究手段的社会科学已经形成，尤其需要强调的是这个研究领域的一个主要特点是采用网络科学的研究方法分析社会科学的研究问题。</p>
<p>无独有偶，在Lazer等人2009年发表这篇文章之前，网络科学的另外一个主要研究者Duncan Watts于2007年就在《自然》杂志上发表题为“二十一世纪的科学”一文(Watts, 2007)。Watts认为社会科学是二十一世纪最重要的科学。我们现代社会所面临的绝大多数问题是社会科学问题。社会科学研究者之所以没有发展出类似物理学和生命科学一样完善的理论框架是因为社会科学研究是最难的。社会现象卷入了海量的异质性的个体的相互互动，以致于变得非常复杂。幸运的是网络科学的研究开启了一个新的研究方向，但是网络科学需要大量的实证数据，而基于互联网的传播恰好提供了新的两种新的研究方式：一是各种各样的“数字足迹”（网络聊天、发博客、发微博、加标签、发邮件等），另外一个是互联网实验。基于以上理由，Watts提出“如果处理得当，基于互联网传播产生的数据和互动性将会变革我们对于人类集体行为的认识”(Watts, 2007)。</p>
<p>根据对于计算社会科学一词的引文网络分析，研究者发现计算社会科学方兴未艾、处于指数增长的阶段(王成军, 2015)。自从Lazer等人2009年发表其重要论文之后，计算社会科学类的论文数量和应用数量不断增长，且大多数论文发表在《科学》、《自然》等综合性期刊以及各个学科最好的期刊上。从引文网络的结构而言，计算社会科学研究已经形成了一个紧密的研究领域。一直以来，计算方法同社会科学的结合是通过计算机模拟（多主体建模）进行的(Axelrod, 1997; Gilbert, 2008; Gilbert &amp; Troitzsch, 2005)，网络科学出现之后，因其与真实的人类行为数据的紧密结合而成为更为重要的研究范式。社会系统如同生物系统、金融系统等一样是一个复杂系统，社会现象充满了复杂性，因而需要采用复杂性科学的研究视角进行分析(Mitchell, 2011)。正因为人们总是生活在各种网络当中，而且网络恰好为各种复杂的社会现象的结构提供了一个数学表达，因而采用网络科学的视角对于分析社会现象具有重要意义，也是基于这个原因，计算社会科学现阶段最主要的研究主要是基于网络科学展开的(王成军, 2015)。</p>
<p>社会科学家开始大量地使用社会网络数据进行科学研究(Miller, 2011)，例如Bollen等人采用推特的数据进行情感分析，发现“冷静”这一种情绪可以较好地预测股票的涨落(Bollen, Mao, &amp; Zeng, 2011)。Ginsberg等人采用谷歌的搜索数据分析了人们检索与流感相关的词语的时间序列，通过机器学习的方式预测人类大规模流感的爆发，可以使人们提前两周预知流感的爆发(Ginsberg et al., 2009)。</p>
<p>Eagle等人采用英国的手机数据构建的传播网络，研究发现城市节点在传播网络的多样性与城市社会经济发展指数之间具有非常好的正相关的函数关系，由此可能证明传播行为对于经济发展的重要性(Eagle, Macy, &amp; Claxton, 2010)。 Bond等人使用Facebook作为网络实验平台研究美国大选，liu&#8217;bai&#8217;wan六百多万人参与了实验，结果证明社交网路传递的信息的影响力远大于信息的直接传播，强关系对于人类社会网络里的行为传播具有重要意义(Bond et al., 2012)。 当人类传播行为的数据构成了计算社会科学的重要基础的时候，深入认识计算传播学的时机终于到来。祝建华等人总结了计算社会科学在传播学的各种应用(祝建华 et al., 2014)，沈浩等分析了复杂网络和社会计算对于传播学研究的意义(沈浩, 杨璇, &amp; 杨一冰., 2014)，王成军(2015)系统回顾了计算社会科学发展，并给出了计算传播学的定义：“计算传播学是计算社会科学的重要分支。它主要关注人类传播行为的可计算性基础,以传播网络分析、传播文本挖掘、数据科学等为主要分析工具,(以非介入的方式)大规模地收集并分析人类传播行为数据,挖掘人类传播行为背后的模式和法则,分析模式背后的生成机制与基本原理,可以被广泛地应用于数据新闻和计算广告等场景”。在此基础上2015年，第一本计算传播学相关的图书《社交网络上的计算传播学》出版(许小可, 胡海波, 张伦, &amp; 王成军, 2015)。</p>

## 三、新闻地图

<p>新闻是传播学研究的一个重点，也是记录人类行为的重要方式。在本部分，本文试图给出一个计算传播学研究的实例—“新闻地图”。新闻地图研究所使用的数据主要来源于Gdelt新闻数据库（http://gdeltproject.org/）。Gdelt是由谷歌资助的一个新闻数据项目，它监测全球100多种语言的广播新闻、报纸新闻和网络新闻，从中提取其中的地点、组织、人物、时间，并将所有这些数据开放。目前开放的数据主要分为事件数据库和全球知识图谱数据库两类，使得新闻变成研究各种人类社会的重要资源。新闻地图(http://ccc.nju.edu.cn/newsmap)是一个以可视化的方式反映中国新闻在时间与空间分布的差异性的网页应用，利用Gdelt已有历史数据作为数据源，通过多样化的统计图表对中国新闻进行展示。</p>
<p>我们知道新闻的生产本身就具有很强的空间异质性。有些地方虽然空间面积很小，但是新闻就很多，例如国家的首都；有些地方虽然面积很大，但是新闻却相对较少。采用可视化的方式展现这种空间差异性可以给人们带来更多启发。为此，我们采用扭曲地图（cartogram，或译为“变形地图”）的形式展现，如下图1展示了2015年中国各省市的新闻事件数量。在在这个扭曲地图里面积大小表示新闻事件的数量，我们可以很明显地观察到北京、上海、香港三个大都市生产了大量的新闻事件，而山东、河北等省份的新闻事件则相对较少，更多年份的扭曲地图见(http://ccc.nju.edu.cn/newsmap)。</p>

![newsmap](http://oaf2qt3yk.bkt.clouddn.com/7f9b5d2c496199c1ed82617979b336e1.png)

<p>图1. 扭曲地图展现的中国各省份的新闻空间分布</p>

<p>除了采用空间的描述之外，我们还可以从时间的角度看世界新闻对于中国的报道。图2展现了中国和香港的新闻事件数量随时间变化。为了便于可视化，本文将中国的新闻时间总数量除以十。世界新闻对中国的报道从1979年中美建交时最高，之后逐渐下降并保持了相对的平稳，其间在1997年之后略有增加。与之相比，关于香港的新闻事件则处于首先逐渐增加，到1997年香港回归时迅速增加达到顶峰，之后又逐渐下降的过程，其间2013年和2014年因为“占领中环”而产生了两次“爆发”。</p>

![newsmap2](http://oaf2qt3yk.bkt.clouddn.com/fed9f8bc3d926152a502c18db46b9533.png)

图2. 中国和香港的新闻事件数量随时间变化（每月）

<p>Gdelt全球知识图谱数据是基于对新闻内容的挖掘提供了所提供的关系数据。例如识别出新闻事件的所有人名、地名等。这样我们就可以得到两个人名在一个新闻里同时出现的数据。基于这种数据可以构建节点是人名，链接是两个人名在新闻里一起出现的次数的网络。图3展现了2015年全球新闻人物网络的一部分数据(王成军, 2016)。在图3当中，本文使用节点的pagerank数值来表示节点的大小，我们很明显地发现美国总统奥巴马是2015年全球新闻人物的第一名（0.039）， 其他前十名人物分别是美国国务卿John Kerry（0.0072）、俄罗斯总统Vladimir Putin （0.0056）、法国总统Francois Hollande（0.0052）、天主教第266任教皇Pope Francis（0.0051）、德国总理Angela Merkel（0.0037）、以色列总理Benjamin Netanyahu（0.0036）、美众议院议长John Boehner（0.0035）、美国枪击案受害者或NBA教练Michael Brown（0.0034）、美国南卡罗来纳州印度裔州长Nikki Haley（0.0033）。</p>

![newsmap3](http://oaf2qt3yk.bkt.clouddn.com/6ea9db00797598761ec7d7cc50fae5fc.png)

图3. 2015年全球新闻人物网络


<p>研究者总是试图定量地分析新闻影响力。为此，本文分析了中国各省份从1979年到2015年的新闻影响力，具体包括各个省份的新闻数量、新闻被引用数量以及新闻时间的戈德斯坦得分（Goldstein scale）(Goldstein, 1992)。戈德斯坦得分为每个事件分配一个在-10到+10之间的数值，用以衡量理论上该事件对国家产生的潜在影响。分析结果如图4所示（双对数坐标系）。显然，新闻数量和戈德斯坦得分之间存在完美的线性关系，这表明当我们从一个地区的角度分析新闻影响力的时候，戈德斯坦得分并未给我们更多洞见。这或许是因为戈德斯坦得分是基于事件类型而非事件的细节，因此一个10人参与的暴乱与一个1000人参与的暴乱都将获得同样的分数。更为重要的是，不管是新闻数量还是戈德斯坦得分与新闻被引用次数之间都存在超线性的幂律关系，幂指数是1.11，这表明了新闻影响力具有一个放大的机制，这种机制是通过新闻引用来实现的。</p>

![newsmap4](http://oaf2qt3yk.bkt.clouddn.com/37f57c916894d0cd1ff9de0fbdab1248.png)

图4. 三种新闻影响力之间的关系（双对数坐标系）(刘磊, 朱静怡, 王成军, &amp; 陈志聪, 2015)</p>

## 四、结论和讨论
<p>综上，本文对计算传播学的概念、理论脉络、实际应用进行了综合介绍。计算传播学作为一个研究领域，更加重视对于数据本身的使用，但是需要强调的是数据只是起点。通过数据挖掘，发现人类传播行为的模式才更有意义。从数据到模式的跨越，衡量了计算传播学研究的发展阶段。在缺乏数据的时候，研究者无法证明模式的存在。开普勒只有在第谷收集的大量的天文数据的基础上才能做出天体运行模式的三大发现。网络科学家也只有在掌握了大规模的网络数据的时候才能发现并证明幂律在网络中的普遍存在(Barabási &amp; Albert, 1999)。在新闻地图项目研究当中，只有当我们系统的分析了各个省市新闻影响力的不同计算指标之后，才能发现它们之间的幂律关系，尤其是新闻数量与新闻引用之间所存在的超线性增长模式。</p>
<p>但是，需要警惕的是仅仅停留在模式层面上是不足的，只有能够在机制上对模式的出现提供有效的解释才能将研究变得更加有价值。同样以网络科学分析网络中的无标度现象作为例子，研究者在电力输运网络、演员网络、互联网三个数据当中均发现了度分布的无标度模式，这表明在这种模式背后必然隐藏着更为深刻的机制。Barabási &amp; Albert(1999)认为网络增长和优先链接两种机制是构成无标度模式普遍存在的关键原因。基于这两种机制，他们构造了BA网络，并采用平均场的方法证明了其有效性。通过机制，我们可以得到现实数据中所隐藏的模式。在新闻地图研究项目中，我们得到了三种新闻影响力的幂律模式，也推理得到了一个可能的机制，即新闻影响力的扩大是通过新闻引用来实现的，但还没有提供一个有效性的证明，这成为下一步研究的重点。当计算传播学研究从发现模式的阶段上升到提出机制的阶段，标志着这个研究领域的开始走向成熟。</p>

## 参考文献

<ul>
<li>Axelrod, R. M. (1997). The complexity of cooperation: Agent-based models of competition and collaboration: Princeton University Press.</li>
<li>Barabási, A.-L., &amp; Albert, R. (1999). Emergence of scaling in random networks. Science, 286(5439), 509-512. </li>
<li>Bollen, J., Mao, H., &amp; Zeng, X. (2011). Twitter mood predicts the stock market. Journal of Computational Science, 2(1), 1-8. </li>
<li>Bond, R. M., Fariss, C. J., Jones, J. J., Kramer, A. D., Marlow, C., Settle, J. E., &amp; Fowler, J. H. (2012). A 61-million-person experiment in social influence and political mobilization. nature, 489(7415), 295-298. </li>
<li>Eagle, N., Macy, M., &amp; Claxton, R. (2010). Network Diversity and Economic Development. Science, 328, 1029–1031. </li>
<li>Gilbert, N. (2008). Agent-based models: Sage.</li>
<li>Gilbert, N., &amp; Troitzsch, K. (2005). Simulation for the social scientist: McGraw-Hill International.</li>
<li>Ginsberg, J., Mohebbi, M. H., Patel, R. S., Brammer, L., Smolinski, M. S., &amp; Brilliant, L. (2009). Detecting influenza epidemics using search engine query data. nature, 457(7232), 1012-1014. </li>
<li>Goldstein, J. S. (1992). A Conflict-Cooperation Scale for WEIS Events Data. Journal of Conflict Resolution, 36(2), 369-385. </li>
<li>Lazer, D., Pentland, A. S., Adamic, L., &amp; Aral, S. B., Albert Laszlo; Brewer, Devon; Christakis, Nicholas; Contractor, Noshir; * Fowler, James; Gutmann, Myron. (2009). Life in the network: The coming age of computational social science. Science, 323(5915), 721. </li>
<li>Miller, G. (2011). Social scientists wade into the tweet stream. Science, 333(6051), 1814-1815. </li>
<li>Mitchell, M. (2011). Complexity: A Guided Tour. New York: Oxford University Press. Watts, D. J. (2007). A twenty-first century science. nature, 445(7127), 489-489. </li>
<li>刘磊, 朱静怡, 王成军, &amp; 陈志聪 (Producer). (2015). 读者可以浏览《各省市新闻动态变化图》的在线互动版本. Retrieved from http://ccc.nju.edu.cn/newsmap/link3.html</li>
<li>沈浩, 杨璇, &amp; 杨一冰. (2014). 传播学研究新思路：复杂网络与社会计算. 科研信息化技术与应用, 5(2), 27-33. </li>
<li>王成军. (2015). 计算传播学:作为计算社会科学的传播学. 中国网络传播研究, 8, 193-208. </li>
<li>王成军 (Producer). (2016). 读者可以浏览《2015年全球新闻人物网络》的互动版本. Retrieved from http://data-science-lab.github.io/gdelt/index.html</li>
<li>祝建华, 彭泰权, 梁海, 王成军, 秦洁, &amp; 陈鹤鑫. (2014). 计算社会科学在新闻传播研究中的应用. 科研信息化技术与应用, 5(2), 3-13. </li>
<li>许小可, 胡海波, 张伦, &amp; 王成军. (2015). 社交网络上的计算传播学. 北京: 中国科学出版社.</li>
</ul>
