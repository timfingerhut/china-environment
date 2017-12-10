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

># Network Analysis
 
> ## Overview
> This section uses network mapping to compare and understand the discussion of climate change across Chinese media sources. Network mapping is a script that provides analysis and visualization of nodes correlated based on different proximity measures. It identifies dense groups and produces clusters. In this case, it can be used to determine under which sub-group the discussion of climate change appears. 

> Network Mapping is a Cortext script that analyzes the dynamics of a textual corpus by visualizing how terms interact with one-another, and whether they co-occur. At first it is necessary to produce a list of terms either by term extraction from the corpus, or by using a custom list. In this case, 200 of the most frequent terms from all media sources were extracted and edited to remove unrelated terms, such as ‘km squared’ and ‘last week. Terms related to the research project, including ‘pearl river delta’, ‘pollution’, and ‘climate change’ were kept. Similarly, such term lists were extracted from China Daily and South China Morning Post corpora individually for comparison purposes, which will be further discussed below. 
<b>

> ### Term Lists
> <iframe src="https://docs.google.com/spreadsheets/d/1TXG8PqtCQo2e_ukp2gUCatRbDwWqlCKsBRSLHDYEfY0/edit?usp=sharing" frameborder="0" style="overflow:hidden;border:1px solid #DDDDDD;" width="800" height="800" allowfullscreen></iframe>

> After their extraction, the list was applied to the main corpus containing all Chinese media sources to see how the terms interacted with one-another. This can be observed through a map of heterogeneous or homogeneous nodes that are associated based on their proximity measures. In a heterogeneous map, the program uses two fields to develop ‘communities of nodes’. In this case, the first field included ‘Subject’ and the second field included ‘Terms’, and the number of nodes was limited to 150. The nodes are selected based on the frequency of their co-occurrence at a given time period. The co-occurrences were based on a direct chi2 measure, with a proximity threshold of 0.1. This takes into account the raw co-occurrence between the terms. The homogeneous network, on the other hand, only how the terms alone interact with one another within the corpora, and therefore uses a single field. The other parameters are similar to the ones used for the heterogeneous map. However, the homogeneous map uses an indirect, or a distributional measure to determine co-occurrence of the terms, and combines them into separate clusters, or subjects. 

> ## Homogeneous and Heterogeneous Clusters  
  
> In looking at the maps, the structures of the homogeneous and heterogeneous maps seem different. For one, the heterogeneous map seems to be more intertwined, whereas the homogeneous map forms an arc. It is important to note that the heterogeneous map clusters terms around subjects discussed within the sources, whereas in the homogeneous map the clusters emerge out of a distributional co-occurrence between the terms. The results that they produce, however, can be comparable in observing the discussion of environmental issues. For example, in the heterogeneous map, ‘climate change’ can be found under the subject titled ‘Climate Change & Global/World Issues’. Its nearest clusters are ‘Economic News & Trade’, and ‘Regulation/Government Policy & Market’. However, the cluster titled ‘Air/Water/Land Quality & Air Pollution’ is on the other side of the map. The terms ‘air/water/land quality’ are linked with ‘emissions’ under the ‘Climate Change’ category, but otherwise the links between the two clusters seem to be weak.   
  
> ### Heterogeneous Clusters-By Subject
> <iframe src="https://documents.cortext.net/lib/mapexplorer/explorerjs.html?file=https://assets.cortext.net/docs/a5215b796c0714e82b530474fd52c74f" frameborder="0" style="overflow:hidden;border:1px solid #DDDDDD;" width="1100" height="800" allowfullscreen></iframe>
<b>
> Similar pattern can be seen in the homogeneous structure below. On the left end of the arc, the ‘Authorities & River’ cluster discusses ‘air pollution’, ‘air quality’, ‘smog’, ‘local governments’, ‘water’, ‘environment’, ‘environmental protection’ and ‘village’. This is closely linked with the cluster titled ‘Species & Nature’, which contains ‘sea’, ‘research’, ‘marine’, ‘trees’ and ‘forest’. While these clusters are closely intertwined, they also appear closely with the terms associated with ‘government’, ‘plan’, and ‘waste’. This could suggest that improving water and pollution levels, along with ensuring conservation can be more associated with the local government efforts in supporting their improvement. 

> ### Homogeneous Clusters-By Words

> <iframe src="https://documents.cortext.net/lib/mapexplorer/explorerjs.html?file=https://assets.cortext.net/docs/a5cccb6d4d494a6092d1cfd53d094e5b" frameborder="0" style="overflow:hidden;border:1px solid #DDDDDD;" width="1100" height="800" allowfullscreen></iframe>

> On the other hand, the discussion of ‘climate change’ occurs at the other right end of the arc. It appears with terms, including ‘agreement’, ‘conference’, ‘emissions’, ‘sustainable development’, and ‘developing countries’. Its closest clusters include ‘Organizations & Program’, and ‘Sector & Market’. As such, the discussion of climate change co-occurs in a broader, and possibly a more international context. Moreover, there are no apparent links with the left side of the arc discussing China’s environmental issues. As such, it is possible that while ‘climate change’ may occur in an environmental context, the chances are very low. Instead, it is possible to suggest that while ongoing environmental problems are seen as a domestic responsibility, the media sources do not link these to climate change, which is discussed in a more global context. 

> ## Newspaper Comparisons-South China Morning Post vs. China Daily

> ### South China Morning Post

> <iframe src="https://documents.cortext.net/lib/mapexplorer/explorerjs.html?file=https://assets.cortext.net/docs/01d81e616ae3ae7748315bf795fc1f9c" frameborder="0" style="overflow:hidden;border:1px solid #DDDDDD;" width="1100" height="800" allowfullscreen></iframe>

> ### China Daily 

> <iframe src="https://documents.cortext.net/lib/mapexplorer/explorerjs.html?file=https://assets.cortext.net/docs/1bb440e79273433fb81261974c2cc851" frameborder="0" style="overflow:hidden;border:1px solid #DDDDDD;" width="1100" height="800" allowfullscreen></iframe>
