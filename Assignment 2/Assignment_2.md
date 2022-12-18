##### *CASA0001 Assignment 2*

*Xianlai Yin 18/12/2022 选题：A*

---

###### *Describe the epistemological orientation of the author(s)? What aspects of the study can you associate with specific epistemological paradigms? 描述作者的认识论取向? 你能将研究的哪些方面与特定的认识论范式联系起来? （第一章）*

`<对文章的整体内容分析，把呈现出明显实证主义特征的部分陈述出来，并辩证地思考是否有符合理想主义或结构主义的内容。>`

`tips: 主要实证主义-使用演绎推理来推断普遍规律；寻求建立客观的证据基础；强调定量分析方法和辅助数据；使用贝叶斯空间结构模型了解密度和公共住房如何影响过早死亡率；假设我们可以解释、预测和改变世界。`

```
作者的认识论取向基本符合实证主义范式在城市分析中的典型特征，并在研究中多个方面有所体现。首先，本文对伦敦的士绅化进程进行了测度与分类，并对其未来趋势进行预测，这与实证主义范式中使用演绎推理来推断普遍规律并认为世界是可以被解释、预测和改变的特征一致。其次，本研究使用主成分分析、聚类分析和机器学习等方法客观地对伦敦的士绅化进程进行定量分析，与实证主义范式强调定量分析方法的特征相吻合。此外，研究是基于大量且多种的具有可靠数据源的数据集，对；伦敦的士绅化过程和模式进行量化研究，这与实证主义范式中寻求建立客观的证据基础的特征相吻合。不过，文章中或许也有一些其他认识论如结构主义的影响，在文章的实证分析部分，作者通过士绅化这一城市现象，追溯和推理空间现象背后更深层次的的经济和社会本质。

The author's epistemological orientation is largely in line with the positivist paradigm typical of urban analysis, and is reflected in several aspects of the study. Firstly, the paper measures and classifies the process of gentrification in London and predicts its future trends, which is consistent with the positivist paradigm's use of deductive reasoning to infer universal laws and to argue that the world is open to interpretation, prediction and change. Secondly, the study uses principal component analysis, cluster analysis and machine learning to objectively quantify the process of gentrification in London, in line with the positivist paradigm's emphasis on quantitative methods of analysis. Furthermore, the research is based on a large and diverse dataset with reliable data sources to quantify; the processes and patterns of gentrification in London, which is in line with the positivist paradigm's characteristic of seeking to establish an objective evidence base. However, there may be some other epistemological influences such as structuralism in the article, and in the empirical analysis section of the article, the authors trace and reason about the deeper economic and social essence behind the spatial phenomenon of gentrification as an urban phenomenon.
```

###### *How do the authors attempt to study neighbourhoods and their characteristics in their study? 作者如何尝试在他们的研究中研究社区及社区的特点?*

`<You should refer to both: the overall research design, specific methods used 你应该参考两者:总体研究设计，使用的具体方法`。`对研究中涉及社区的部分使用到的整体技术方法和具体技术细节进行分析和描述。>`

`tips: 总主题和背景介绍，要解决的前人没有解决的问题（文献综述分析），数据来源分析，分析分区的特征。一般主题，具体的研究问题，从文献综述的研究差距；使用密度、公共住房、潜在因素等与健康结果相关的社区(地区)级数据-过早死亡率；贝叶斯空间结构建模；潜在的生态谬误；什么是版主?接触吗?介质?混杂因素?混合方法:定量和定性方法，进一步调查复杂的关系。`

```
总体上说，本文在系统研究伦敦的邻里变化的基础上，使用多种数据集对其士绅化进程进行量化，通过多次对数据进行降维和分类提取士绅化的特征与空间模式，之后使用机器学习的方法对士绅化趋势进行预测。文章的背景是士绅化这一发生在例如伦敦这类的后工业化城市的一种复杂的社会空间现象，它往往是与种族、阶级等相关的广泛的社会分化问题的具体体现(Perera, 2019; Snoussi & Mompelat, 2019)，也对城市政策制定提出了难题。

而以往对士绅化的研究，一方面，由于士绅化所涉及的社会空间的复杂性和缺乏证据或手段收集、处理和分析数据(Almeida's, 2021)，很难对士绅化进行定量分析，因此无法精准地进行研究，也缺乏可复制性。另一方面，此前的士绅化研究大多只是基于人口变化的整体趋势，并没有精准地划分趋势以找到真正意义上的士绅化现象。同时，对于士绅化的预测对政策的制定有着重要的指导意义，而此前的研究受限于技术方法很难对趋势进行判断。如今，随着技术发展和数据量的爆发性增长，本文得以利用更先进的技术方法弥补这些方面的空缺。

本研究首先收集了大量数据，包括ONS提供的人口普查与房价相关数据，GLA提供的建成环境相关数据，和CDRC提供的人口波动数据，并以最为接近社区规模和划分的人口普查的Lower-Layer Super Output Areas (LSOA)作为分析单元。研究分为了具体的四个阶段：第一阶段，通过主成分分析识别每一个LSOA的历史变化；第二阶段，通过K-means聚类识别呈增长趋势的LSOA是否为士绅化社区；第三阶段，通过再一次的K-means聚类识别士绅化的LSOA的类型（super gentrification, marginal gentrification, mainstream  gentrification），并通过Global Moran's I和Getis-Ord Gi判断士绅化的空间自相关程度；第四阶段，通过基于多元随机森林模型的机器学习预测伦敦各LSOA的未来发展趋势。此外，本文使用了交互式的空间数据可视化方法，使判断空间模式和趋势更加便利。

In general, this paper uses multiple datasets to quantify the process of gentrification based on a systematic study of neighbourhood change in London, extracting features and spatial patterns of gentrification through multiple downscaling and classification of the data, and then using machine learning methods to predict gentrification trends. The context of the article is that gentrification, a complex socio-spatial phenomenon occurring in post-industrial cities such as London, is often a concrete manifestation of broader social divisions related to race, class, etc. (Perera, 2019; Snoussi & Mompelat, 2019) and poses a challenge for urban policy making.

Previous studies of gentrification, on the other hand, have been difficult to quantify due to the complexity of the social spaces involved in gentrification and the lack of evidence or means to collect, process and analyse data (Almeida's, 2021), making it impossible to study gentrification with precision and lacking replicability. On the other hand, most previous studies of gentrification have been based only on overall trends in population change, and have not precisely delineated trends to find the true meaning of the phenomenon of gentrification. At the same time, the prediction of gentrification is an important guide to policy making, and previous studies have been limited by technical methods to determine trends. Now, with technological developments and the explosive growth of data, this paper is able to fill these gaps with more advanced technical methods.

The study began by collecting a large amount of data, including census and house price related data from the ONS, built environment related data from the GLA, and population fluctuation data from the CDRC, and used the Lower-Layer Super Output Areas (LSOA), which most closely approximates the census of community sizes and divisions, as the unit of analysis. The study was divided into four specific phases: in the first phase, each LSOA was identified by principal component analysis for historical change; in the second phase, K-means clustering was used to identify LSOAs with a growing trend as gentrification communities; in the third phase, further K-means clustering was used to identify the types of gentrification LSOAs (super gentrification, marginal gentrification, mainstream gentrification ) and determining the spatial autocorrelation of gentrification by Global Moran's I and Getis-Ord Gi. In the fourth stage, the future trends of each LSOA in London are predicted by machine learning based on multivariate random forest models. The complete study is constructed.
```

###### *Given your answers above, reflect on the strengths and limitations of the study. What spatial and social processes are considered or not considered? 根据你上面的答案，思考一下这项研究的优势和局限性。哪些空间和社会过程被考虑或不被考虑?（第三章，第六章，第七章）*

`<社会领域包括社会、文化、社会结构、社区、规范、社会实践，空间领域包括距离、位置、规模、面积、运动和网络，跨社会和空间的领域包括地方、领土、城市。社会对空间的过程包括社会分化、沿着经济轴的住宅分化、沿着文化轴的居住分化。其实证研究包括地理人口学和隔离研究。空间对社会的过程包括领域效应、生活机会差异。其实证研究包括横断面研究、邻里效应研究分析研究的优势与劣势，并分析以上这些因素在文中的情况。>`

`tips: 优势-测试不同模型及其组合的定量方法，使用因素分析链接到社会变量；劣势-不考虑主观经验、密度和公众实际上是如何被体验的(理想主义者)或结构过程(它们是如何产生的)；横断面研究；自我选择的考虑:人们如何选择进入某些社区。`

```
本研究的优势主要体现在，利用可靠的社会与空间数据和多种定量分析方法，精准地在伦敦量化了复杂的士绅化，并对其未来趋势进行预测，很好地弥补了前文所提到的士绅化研究领域的空缺。同时，优秀的交互式可视化方法及清晰的分析解读，为规划机构制定决策提供了可靠的依据。此外，本文与作者提供的代码也为研究相似主题的学者提供了一条可复制的研究方法。

但是，本文也存在一定的局限性。首先，

重点仅仅是英格兰伦敦的士绅化，这可能并不代表其他城市或地区的士绅化。此外，该研究可能没有考虑到士绅化所涉及的所有空间和社会过程，因为它主要依赖于与人口、房价和建筑环境相关的数据。其他因素，如社会和文化动态，也可能在士绅化中发挥作用，在分析中可能无法完全捕捉到。另一个局限性是，该研究将士绅化作为邻里变化的过程，可能没有充分考虑士绅化对城市和社区的更广泛影响。士绅化往往与种族、阶级和排斥等问题有关，社会经济地位较低的居民被从士绅化社区中驱逐出来，可能会对这些个人和社区产生负面影响。作者确实认识到士绅化的争议性及其可能产生的潜在负面影响，但他们在分析中并没有充分探讨这些问题。可以进行进一步的研究，以更全面地了解士绅化的社会和文化层面及其对城市和社区的更广泛影响。


```

###### *Do you think the authors achieve their research objective? What additional work may be done to contribute to the research field of this study? 你认为作者达到了他们的研究目的吗?为了对本研究的研究领域做出贡献，还需要做哪些额外的工作?*

`<对本文的总结研判，并提出未来展望，并进行一定的批判性思考。>`

`tips: 实现了绘制不平等地图的目标；公共住房供应和健康差距之间的相关性，在考虑其他地区特征后，扭转影响的方向；未来工作：附加变量?混杂变量和/或控制变量?；纵向研究，公共住房前后?；补充定性分析，以提供所选社区的更多细节；城市政策分析，以研究集中卫生脆弱性的产生。（后续分析定量部分）使用定量结果来决定要访问的社区:三个死亡率不同但城市密度相似的社区，围绕城市密度、日常活动、健康和福祉邀请当地居民参与的焦点小组；（后续分析定性部分）揭示社会实践、社会经济环境的重要性。即城市密度影响个人健康和福祉的偶然机制。`

```

```

###### *To support your arguments, you should cite relevant literature. 为了支持你的观点，你应该引用参考文献。*

`<找两三篇关于实证主义的论文，再找两三片分析文章相关的论文。>`

```

```

时间安排：早上10：00-12：00（两篇论文精读与选择）；下午13：00-19：00（每题一个半小时，500中文字）；晚上20：00-22：00（翻译优化与排版）；晚上22：00-24：00（参考文献与查重）
