<title>Example</title>
<style>
body {
    margin:0;
    padding:0;
    background-image:url("/china-environment/assets/images/Factory.pdf"); 
    background-repeat: no-repeat;
    webkit-background-size: cover;
    moz-background-size: cover;
    o-background-size: cover;
    background-size: cover;
    }
    
</style>

> # VI. Network Analysis
```ruby
> // What is Network Analysis?
> Network Analysis studies connections and relationships between terms within a dataset. 
```

> Network mapping, or network analysis, is used in this section to compare and understand the discussion of climate change across Chinese media sources. Network mapping is a script that provides analysis and visualization of nodes correlated based on different proximity measures, and produces clusters by identifying dense groups. In 2008, Mathieu Jacomy and others [created](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0098679) network visualization software through Gephi in order to provide social scientists with network analysis tools that would 'not require learning graph theory'. For our research, we used Cortext's [Network Mapping](https://docs.cortext.net/analysis-mapping-heterogeneous-networks/) script in order to compare and understand the discourse of 'climate change' across Chinese media sources, and how it interacts with other terms related to the environment.

> ## A. Methodology 

> The networks below map out the interaction between 150-200 of the most frequent terms within a given corpus. Initially, we extracted a term lists from the corpus combining all sources, and edited it to remove unrelated terms, such as ‘km squared’ and ‘last week'. We left terms related to the research project, including ‘pearl river delta’, ‘pollution’, and ‘climate change’. For comparison purposes, we also extracted similar term lists from South China Daily Post and China Daily, and used them to analyze their respective corpora.

> In order to analyze their interaction, we used the Cortext network mapping tool to produce heterogeneous and homogeneous maps, where the nodes are clustered into groups based on their co-occurrence and proximity. In a heterogeneous map, the program uses two fields to develop ‘communities of nodes’. In this case, the first field included ‘Subject’ and the second field included ‘Terms’. The program calculated the raw co-occurrence of 150 nodes based on a direct chi2 measure with a proximity threshold of 0.1. Producing a homogeneous map involved a similar process, but it used only a single field of 'Terms' in determining clusters. While other parameters were the same, we applied a distributional measure, rather than a chi2 measure, to observe co-occurrence between the terms and analyze the clusters (categories) under which they fall without having 'Subject' as a determining field. 

> ### Term Lists
> <iframe src="https://docs.google.com/spreadsheets/d/1TXG8PqtCQo2e_ukp2gUCatRbDwWqlCKsBRSLHDYEfY0/edit?usp=sharing" frameborder="0" style="overflow:hidden;border:1px solid #DDDDDD;" width="800" height="800" allowfullscreen></iframe>

> ## B. Research 

> In looking at the maps, the structures of the homogeneous and heterogeneous maps seem different. For one, the heterogeneous map seems to be more intertwined, whereas the homogeneous map forms an arc. It is important to note that the heterogeneous map clusters terms around subjects discussed within the sources, whereas in the homogeneous map the clusters emerge out of a distributional co-occurrence between the terms. The results that they produce, however, can be comparable in observing the discussion of environmental issues. For example, in the heterogeneous map, ‘climate change’ can be found under the subject titled ‘Climate Change & Global/World Issues’. Its nearest clusters are ‘Economic News & Trade’, and ‘Regulation/Government Policy & Market’. However, the cluster titled ‘Air/Water/Land Quality & Air Pollution’ is on the other side of the map. The terms ‘air/water/land quality’ are linked with ‘emissions’ under the ‘Climate Change’ category, but otherwise the links between the two clusters seem to be weak.   
  
> ### Heterogeneous Clusters-By Subject
> <iframe src="https://documents.cortext.net/lib/mapexplorer/explorerjs.html?file=https://assets.cortext.net/docs/a5215b796c0714e82b530474fd52c74f" frameborder="0" style="overflow:hidden;border:1px solid #DDDDDD;" width="1100" height="800" allowfullscreen></iframe>

> Similar pattern can be seen in the homogeneous structure below. On the left end of the arc, the ‘Authorities & River’ cluster discusses ‘air pollution’, ‘air quality’, ‘smog’, ‘local governments’, ‘water’, ‘environment’, ‘environmental protection’ and ‘village’. This is closely linked with the cluster titled ‘Species & Nature’, which contains ‘sea’, ‘research’, ‘marine’, ‘trees’ and ‘forest’. While these clusters are closely intertwined, they also appear closely with the terms associated with ‘government’, ‘plan’, and ‘waste’. This could suggest that improving water and pollution levels, along with ensuring conservation can be more associated with the local government efforts in supporting their improvement. 

> ### Homogeneous Clusters-By Words

> <iframe src="https://documents.cortext.net/lib/mapexplorer/explorerjs.html?file=https://assets.cortext.net/docs/a5cccb6d4d494a6092d1cfd53d094e5b" frameborder="0" style="overflow:hidden;border:1px solid #DDDDDD;" width="1100" height="800" allowfullscreen></iframe>

> On the other hand, the discussion of ‘climate change’ occurs at the other right end of the arc. It appears with terms, including ‘agreement’, ‘conference’, ‘emissions’, ‘sustainable development’, and ‘developing countries’. Its closest clusters include ‘Organizations & Program’, and ‘Sector & Market’. As such, the discussion of climate change co-occurs in a broader, and possibly a more international context. Moreover, there are no apparent links with the left side of the arc discussing China’s environmental issues. As such, it is possible that while ‘climate change’ may occur in an environmental context, the chances are very low. Instead, it is possible to suggest that while ongoing environmental problems are seen as a domestic responsibility, the media sources do not link these to climate change, which is discussed in a more global context. 

> ## Newspaper Comparisons-South China Morning Post vs. China Daily

> In addition to analyzing clusters across all sources, we also zoomed in on China Daily and South China Morning Post. South China Morning Post is a Hong Kong newspaper, and China Daily is a mainland, government-controlled newspaper. Similarly to the method discussed above, we extracted 150 of the most frequent terms from these sources, and, after light editing, used them to create heterogeneous clusters. Our aim was to compare how these sources cover environmental issues and climate change, and to analyze differences in their discourse. 

> ### South China Morning Post

> In South China Morning Post, the discussion of  ‘climate change’ is found under the cluster titled ‘China & Nation’. Although the network is homogeneous, it is significantly different from the homogeneous map analyzing all news sources. Rather than having an arc shape, the South China Morning Post map reveals intertwining clusters, particularly those mentioning ‘air pollution’ and ‘climate change’. The discourse of ‘climate change’ is still confined within the limits of discussing global issues, and is tied with terms including ‘Organization’, ‘state’, and ‘Asia’. ‘Air pollution’ is discussed under the cluster titled ‘Air Pollution & Pollution’, which discusses ‘Pearl River Delta’, ‘vehicles’, and ‘health’. The discussion of water and land pollution, and waste appear in separate clusters that are spread out, although the links remain. Most importantly, despite having no direct links between the terms ‘climate change’ and ‘air pollution’, the clusters in which they are being discussed show connections, which is different from the arc shape of the homogeneous network analyzing all sources. As such, it is possible to suggest that the likelihood of covering climate change as part of air pollution in South China Morning Post is higher than across overall media sources. 

> <iframe src="https://documents.cortext.net/lib/mapexplorer/explorerjs.html?file=https://assets.cortext.net/docs/01d81e616ae3ae7748315bf795fc1f9c" frameborder="0" style="overflow:hidden;border:1px solid #DDDDDD;" width="1100" height="800" allowfullscreen></iframe>

> ### China Daily 
> In contrast to South China Morning Post, China Daily map is shaped like an arc, similar to the heterogeneous network analyzing all sources. The term ‘climate change’ appears under ‘Climate Change and Nation’ cluster, which is intertwined with issues regarding market and economy. The terms identified with ‘climate change’ include ‘organizations’, ‘United States’, ‘leaders’ and the ‘UN’. Interestingly, while ‘China’ appears under the similar cluster as ‘climate change’ in the South China Morning Post, in China Daily it appears under the cluster discussing economic growth. On the left side of the map, the China Daily articles have three closely intertwined clusters regarding ‘Mountains & Park’, ‘Cars & Vehicle’, and ‘Province & Bureau’. These all contain issues linked to environmental problems in China. For instance, ‘Mountains & Park’ contains: ‘conservation’, ‘natural reserves’, ‘birds’, and ‘nature’; ‘Province and Bureau’ contains ‘city’, ‘waste’, ‘environment’, ‘air pollution’, along with ‘bureau’ and ‘province’. ‘Cars & Vehicles’ is a small section that is linked with ‘air pollution’ and ‘air quality’.

> <iframe src="https://documents.cortext.net/lib/mapexplorer/explorerjs.html?file=https://assets.cortext.net/docs/1bb440e79273433fb81261974c2cc851" frameborder="0" style="overflow:hidden;border:1px solid #DDDDDD;" width="1100" height="800" allowfullscreen></iframe>

>  However, as in the homogeneous network, there are no direct links between general environmental issues that China faces and the discussion of climate change, suggesting that it is less likely for China Daily to cover these issues together. Moreover, as overall environmental issues appear in the context of ‘bureau’ and ‘province’, it is possible to assume that local governments are seen as being responsible for tackling China’s domestic environmental problems. Climate change, on the other hand, is seen as a global issue in which local efforts are not necessarily considered. 
