##### *CASA0001 Assignment 2*

*Xianlai Yin 18/12/2022 选题：A*

---

###### *Describe the epistemological orientation of the author(s)? What aspects of the study can you associate with specific epistemological paradigms? 描述作者的认识论取向? 你能将研究的哪些方面与特定的认识论范式联系起来? （第一章）*

`<对文章的整体内容分析，把呈现出明显实证主义特征的部分陈述出来，并辩证地思考是否有符合理想主义或结构主义的内容。>`

`tips: 主要实证主义-使用演绎推理来推断普遍规律；寻求建立客观的证据基础；强调定量分析方法和辅助数据；使用贝叶斯空间结构模型了解密度和公共住房如何影响过早死亡率；假设我们可以解释、预测和改变世界。`

```
1. 作者的认识论取向及研究中与其认识论范式的联系

作者的认识论取向基本符合实证主义范式运用在城市分析中的典型特征，并在研究中多个方面有所体现。首先，本研究对伦敦的士绅化进行了测度与分类，并对其未来趋势进行预测，这与实证主义范式中使用演绎推理来推断普遍规律并认为世界是可以被解释、预测和改变的特征一致。其次，本研究使用主成分分析、聚类分析和机器学习等方法客观地对伦敦的士绅化进行定量分析，与实证主义范式强调定量分析方法的特征相吻合。此外，本研究是基于大量且多种的具有可靠数据源的数据集，这与实证主义范式中寻求建立客观的证据基础的特征相吻合。不过，研究中或许也受到其他认识论的影响，如在文章的讨论和结论部分，作者通过士绅化这一城市现象，追溯和推理空间现象背后更深层次的经济和社会本质，体现了一些结构主义的认识论取向，但是总体上的认识论取向依然是实证主义。


1. the author's epistemological orientation and the links with his epistemological paradigm in the study

The author's epistemological orientation is largely in line with the typical characteristics of the positivist paradigm applied to urban analysis, and is reflected in several aspects of the study. Firstly, the study measures and classifies London's gentrification and predicts its future trends, which is consistent with the positivist paradigm's use of deductive reasoning to infer universal laws and to argue that the world can be explained, predicted and changed. Secondly, this study uses principal component analysis, cluster analysis and machine learning to objectively quantify the gentrification of London, in line with the positivist paradigm's emphasis on quantitative methods of analysis. In addition, the study is based on a large and diverse dataset with reliable data sources, which is in keeping with the positivist paradigm's characteristic of seeking to establish an objective evidence base. However, there may be other epistemological influences in the study, such as the discussion and conclusion sections of the article, where the authors trace and reason about the deeper economic and social nature behind the spatial phenomenon of gentrification through the urban phenomenon, reflecting some structuralist epistemological orientations, but the overall epistemological orientation remains positivist.
```

###### *How do the authors attempt to study neighbourhoods and their characteristics in their study? 作者如何尝试在他们的研究中研究社区及社区的特点?*

`<You should refer to both: the overall research design, specific methods used 你应该参考两者:总体研究设计，使用的具体方法`。`对研究中涉及社区的部分使用到的整体技术方法和具体技术细节进行分析和描述。>`

`tips: 总主题和背景介绍，要解决的前人没有解决的问题（文献综述分析），数据来源分析，分析分区的特征。一般主题，具体的研究问题，从文献综述的研究差距；使用密度、公共住房、潜在因素等与健康结果相关的社区(地区)级数据-过早死亡率；贝叶斯空间结构建模；潜在的生态谬误；什么是版主?接触吗?介质?混杂因素?混合方法:定量和定性方法，进一步调查复杂的关系。`

```
2. 研究社区及社区特点的方法

总体上说，本研究在系统分析伦敦邻里变化的基础上，使用多种数据集对其士绅化现象进行量化，通过多次对数据进行降维和分类提取士绅化的特征与空间模式，之后使用机器学习的方法对其趋势进行预测。文章背景是士绅化这一发生在例如伦敦这类的后工业化城市的一种复杂的社会空间现象，它往往是与种族、阶级等相关的广泛的社会分化问题的具体体现 (Perera, 2019; Snoussi & Mompelat, 2019)，也对城市政策制定提出了难题。

以往对士绅化的研究，一方面由于士绅化所涉及的社会空间的复杂性和缺乏证据或手段收集、处理和分析数据 (Almeida's, 2021)，很难对士绅化进行定量分析，因此无法精准地进行研究，也缺乏可复制性。另一方面，此前的士绅化研究大多只是基于人口变化的整体趋势，并没有精准地划分以找到真正意义上的士绅化现象。同时，对于士绅化的预测对政策的制定有着重要的指导意义，而此前的研究受限于技术方法很难对趋势进行判断。如今，随着技术发展和数据量的爆发性增长，本文得以利用更先进的技术方法弥补这些方面的空缺。

本研究首先收集了大量数据，包括ONS提供的人口普查与房价相关数据，GLA提供的建成环境相关数据，和CDRC提供的人口波动数据，并以最为接近社区规模和划分的人口普查的Lower-Layer Super Output Areas (LSOA)作为分析单元。研究分为了具体的四个阶段：第一阶段，通过主成分分析识别每一个LSOA的历史变化；第二阶段，通过K-means聚类识别呈增长趋势的LSOA是否为士绅化社区；第三阶段，通过再一次的K-means聚类识别士绅化的LSOA的类型 （super gentrification, marginal gentrification, mainstream  gentrification），并通过Global Moran's I和Getis-Ord Gi判断士绅化的空间自相关程度；第四阶段，通过基于多元随机森林模型的机器学习预测伦敦各LSOA的未来发展趋势。此外，本文使用了交互式的空间数据可视化方法，使得判断空间模式和趋势更加便利。


2. Methods for studying neighbourhoods and their characteristics

Overall, this study uses multiple datasets to quantify the phenomenon of gentrification based on a systematic analysis of neighbourhood change in London, extracting characteristics and spatial patterns of gentrification by downscaling and classifying the data several times, and then using machine learning methods to predict its trends. The context of the article is that gentrification, a complex socio-spatial phenomenon occurring in post-industrial cities such as London, is often a concrete manifestation of broader social divisions related to race, class, etc. (Perera, 2019; Snoussi & Mompelat, 2019) and poses a challenge for urban policy making.

Previous studies of gentrification have, on the one hand, been difficult to quantify due to the complexity of the social spaces involved in gentrification and the lack of evidence or means to collect, process and analyse data (Almeida's, 2021), making it impossible to study gentrification with precision and lacking replicability. On the other hand, most previous studies of gentrification have been based on overall trends in population change and have not been precisely delineated to find the true meaning of the phenomenon of gentrification. At the same time, the prediction of gentrification is an important guide to policy making, and previous studies have been limited by technical methods to determine trends. Now, with technological developments and the explosive growth of data, this paper is able to fill these gaps with more advanced technical methods.

The study began by collecting a large amount of data, including census and house price related data from the ONS, built environment related data from the GLA, and population fluctuation data from the CDRC, and used the Lower-Layer Super Output Areas (LSOA), which most closely approximates the census of community sizes and divisions, as the unit of analysis. The study was divided into four specific stages: in the first stage, each LSOA was identified by principal component analysis for historical change; in the second stage, K-means clustering was used to identify LSOAs with a growing trend as gentrification communities; in the third stage, further K-means clustering was used to identify types of gentrification LSOAs (super gentrification, marginal gentrification, mainstream gentrification In the fourth stage, machine learning based on a multivariate random forest model was used to predict the future trend of each LSOA in London. In addition, this paper uses an interactive spatial data visualisation method, which makes it easier to determine spatial patterns and trends.
```

###### *Given your answers above, reflect on the strengths and limitations of the study. What spatial and social processes are considered or not considered? 根据你上面的答案，思考一下这项研究的优势和局限性。哪些空间和社会过程被考虑或不被考虑?（第三章，第六章，第七章）*

`<社会领域包括社会、文化、社会结构、社区、规范、社会实践，空间领域包括距离、位置、规模、面积、运动和网络，跨社会和空间的领域包括地方、领土、城市。社会对空间的过程包括社会分化、沿着经济轴的住宅分化、沿着文化轴的居住分化。其实证研究包括地理人口学和隔离研究。空间对社会的过程包括邻域效应、生活机会差异。其实证研究包括横断面研究、邻里效应研究分析研究的优势与劣势，并分析以上这些因素在文中的情况。>`

`tips: 优势-测试不同模型及其组合的定量方法，使用因素分析链接到社会变量；劣势-不考虑主观经验、密度和公众实际上是如何被体验的(理想主义者)或结构过程(它们是如何产生的)；横断面研究；自我选择的考虑:人们如何选择进入某些社区。`

```
3. 研究的优势和局限性与涉及的空间和社会过程

本研究的优势主要体现在，利用可靠的社会与空间数据和多种定量分析方法，精准地在伦敦量化了复杂的士绅化并进行分类，也对其未来趋势进行预测，很好地弥补了前文所提到的士绅化研究领域的空缺。同时，优秀的交互式可视化方法及清晰的分析解读，为规划机构制定决策提供了可靠的依据。此外，作者基于本研究分享的代码也为研究相似主题的学者提供了一条可重复的研究方法。

但是，本文也存在一定的局限性。首先，士绅化背后的原因复杂，本文虽然相对以往的研究量化了更多的社会因素，但是诸多偶发事件（如疫情或战争）和上位规划（如重要基础设施的规划）带来的影响难以被量化和评估，这也对预测带来了极大的干扰。同时，士绅化在后工业化的城市有着稳定的发展趋势，但是如今信息化冲击着城市的社会结构，空间距离的影响被互联网的广泛普及所冲淡，或许不久的未来，当城市进入一个信息化占主导的阶段，城市原有的地价分布特征将被重构，基于本文模型的十年期预测的准确度或将比预期更低。此外，本文仅在伦敦对2001-2011年的数据进行分析，一方面，或许基于多个不同城市或区域的数据进行分析或许会更有普适性；另一方面，对多个年份的数据进行分析和预测，可以更好地调整模型，如利用1991-2001年的数据预测2011年的数据，并用参考实际的2011年数据进行调整。当然，这些局限性中的部分或许过于严苛，多年期的数据采集和历史数据统计口径的统一有着较高难度，预测中的偶然性因素也难以避免。

本研究中的士绅化涉及到社会空间的分化，包括沿着经济轴的住宅分化和沿着文化轴的居住分化，本研究利用地理人口统计的现代化技术，对区域人口和地理数据进行模拟，判断社会过程对空间过程的影响。此外，作者也在时间序列上进行横断面研究（尽管只有两个年份），在空间上进行了邻域效应的分析，以判断空间过程对社会过程的影响。而分离研究可以进一步分析伦敦士绅化的社会空间划分模式，更深入地了解士绅化背后的深层次原因，但很可惜其似乎并没有体现在文章中。


3. Strengths and limitations of the study and the spatial and social processes involved

The strengths of this study are mainly in the use of reliable social and spatial data and multiple quantitative analysis methods to accurately quantify and classify the complex gentrification in London and also to forecast its future trends, well filling the gap in the field of gentrification research mentioned earlier. At the same time, the excellent interactive visualisation methods and clear interpretation of the analysis provide a reliable basis for decision-making by planning agencies. In addition, the code shared by the authors based on this study provides a repeatable research method for scholars studying similar topics.

However, there are some limitations to this paper. Firstly, the causes behind gentrification are complex, and although this paper quantifies more social factors than previous studies, the impact of many episodic events (such as epidemics or wars) and superordinate planning (such as planning for critical infrastructure) is difficult to quantify and assess, which also poses a significant interference in prediction. At the same time, gentrification has been a stable trend in post-industrial cities, but nowadays information technology is impacting on the social structure of cities, and the influence of spatial distance is being diluted by the widespread availability of the Internet. Perhaps in the near future, when cities enter a phase dominated by information technology, the original characteristics of land price distribution in cities will be reconstructed, and the accuracy of ten-year forecasts based on this paper's model may be lower than expected. In addition, this paper only analyses data from 2001-2011 in London. On the one hand, it may be more generalisable to base the analysis on data from several different cities or regions; on the other hand, analysing and forecasting data from multiple years allows for better adjustment of the model, for example, using data from 1991-2001 to forecast data for 2011 and using reference to the actual 2011 year data to make adjustments. Of course, some of these limitations are perhaps too stringent, with a high degree of difficulty in collecting data over multiple years and harmonising the statistical calibre of historical data, and the element of chance in forecasting is difficult to avoid.

The gentrification in this study involves socio-spatial differentiation, including residential differentiation along the economic axis and residential differentiation along the cultural axis, and this study uses modern techniques of geo-demography to simulate regional demographic and geographical data to determine the impact of social processes on spatial processes. In addition, the authors have also conducted cross-sectional studies on time series (albeit for only two years) and neighbourhood effects on space to determine the impact of spatial processes on social processes. Whereas the separation study could have further analysed the socio-spatial division patterns of gentrification in London and provided more insight into the deeper reasons behind gentrification, unfortunately its does not seem to be reflected in the article.
```

###### *Do you think the authors achieve their research objective? What additional work may be done to contribute to the research field of this study? 你认为作者达到了他们的研究目的吗?为了对本研究的研究领域做出贡献，还需要做哪些额外的工作?*

`<对本文的总结研判，并提出未来展望，并进行一定的批判性思考。>`

`tips: 实现了绘制不平等地图的目标；公共住房供应和健康差距之间的相关性，在考虑其他地区特征后，扭转影响的方向；未来工作：附加变量?混杂变量和/或控制变量?；纵向研究，公共住房前后?；补充定性分析，以提供所选社区的更多细节；城市政策分析，以研究集中卫生脆弱性的产生。（后续分析定量部分）使用定量结果来决定要访问的社区:三个死亡率不同但城市密度相似的社区，围绕城市密度、日常活动、健康和福祉邀请当地居民参与的焦点小组；（后续分析定性部分）揭示社会实践、社会经济环境的重要性。即城市密度影响个人健康和福祉的偶然机制。`

```
4. 研究目的达成度分析与未来工作展望

首先，文章详细地对伦敦各社区2001-2011年的士绅化进行了量化分析，并精准地找到了真正经历士绅化的社区并划分了他们士绅化的类别，在此基础上对2021年的士绅化区域进行了预测，同时，本文的分析过程也被作为可复制的方法被分享，研究结果也被交互式的地理数据可视化方法进行清晰呈现。此外，后续的其他研究也在陆续证明本研究的有效性 (本文)。因此可以认为，本文的既定研究目标都被很好地完成了。

为了进一步对相关研究领域做出贡献，未来的工作可以从以下几个方面展开。第一，前文所提到的一些问题可以进行进一步完善，随着数据源的增加和收集方法的多样化，可以收集多年期数据进行更长期的分析研究，同时，也可以对包括伦敦在内的不同地区各有特征的城市同步进行研究，这二者可以使得研究更具有普适性和可重复性，创造出一套普遍可行的士绅化分析方法。第二，将政策、规划等人为干预因素作为分析数据加入到研究中，一方面可以提高预测的准确性，另一方面也可以判断不同政策对士绅化的影响，辅助相关机构制定政策。此外，对于士绅化的研究的来源及目的是提高城市居民的生活环境质量，人的感知和观点也应该是研究中的重要一环，通过问卷或访谈等方式将人的想法引入，并与数据分析进行对比研究或许可以提高研究最终的社会公正性。


4. Analysis of the achievement of the research objectives and future work

Firstly, the paper provides a detailed quantitative analysis of gentrification in London communities from 2001-2011 and pinpoints the communities that are actually experiencing gentrification and classifies them into gentrification categories, based on which the gentrification areas in 2021 are projected. The results of the study were also clearly presented by an interactive geographical data visualisation method. In addition, other subsequent studies are proving the validity of this paper (this paper). It can therefore be considered that the stated research objectives of this paper have been well achieved.

In order to further contribute to the relevant research field, future work can be carried out in the following ways. Firstly, some of the issues mentioned in the previous section could be further refined, with the addition of data sources and the diversification of collection methods, multi-year data could be collected for longer-term analysis, while simultaneous studies could be conducted on cities with different characteristics in different regions, including London, both of which could make the research more generalisable and repeatable, creating a set of generally feasible gentrification analysis. Secondly, the inclusion of human interventions such as policy and planning as part of the data analysed will improve the accuracy of predictions on the one hand, and determine the impact of different policies on gentrification on the other, assisting the relevant agencies in formulating policies. In addition, the source and purpose of the study of gentrification is to improve the quality of the living environment of urban residents, and human perceptions and opinions should also be an important part of the study, and the introduction of human thoughts through questionnaires or interviews and comparative studies with data analysis may improve the ultimate social justice of the study.
```

###### *To support your arguments, you should cite relevant literature. 为了支持你的观点，你应该引用参考文献。*

`<找两三篇关于实证主义的论文，再找两三片分析文章相关的论文。>`

```

```

时间安排：早上10：00-12：00（两篇论文精读与选择）；下午13：00-19：00（每题一个半小时，500中文字）；晚上20：00-22：00（翻译优化与排版）；晚上22：00-24：00（参考文献与查重）
