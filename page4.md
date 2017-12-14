

> <title>Example</title>
> <style>
> body {
    margin:0;
    padding:0;
    background-image:url("/china-environment/assets/images/Factory.pdf"); 
    background-repeat: no-repeat;
    webkit-background-size: cover;
    moz-background-size: cover;
    o-background-size: cover;
    background-size: cover;
    }

> # V. Contingency Matrix

> ## A. Methodology 
```ruby
> // What is a contingency matrix?
> Contingency matrix can be used for various analytical purposes. We visualize and compare the strength 
> of correlations between two fields across our selected sources. 
```
 
> The contingency matrix below visualizes the joint distributions of the most common of the 200 terms (extracted after parsing all the data from the Chinese news outlets) for each studied news source (2000-2017). Since the country has been experiencing recurring environmental crises, including air and water pollution, the matrix offers an insight on how often Chinese news outlets choose to cover  environmental issues based on the term frequency. 

> <iframe src="https://documents.cortext.net/cb43/cb43640a4e569e043ea59e6a5a13e567/52171/contingency_matrix-all-china-news-sources-logFalse-ISItermsAll_Articles_Top_200_T-SourceName-y1_214-reordered-nFchi2.pdf" frameborder="0" style="overflow:hidden;border:1px solid #DDDDDD;" width="1000" height="670" allowfullscreen></iframe>


> Before developing the matrix, we extracted 200 frequent terms from the combined Chinese news articles (all-China-news-sources) corpus. We divided the corpus according to the source type. After indexing the all-China-news-sources corpus with both term and source lists, we used the contingency matrix on Cortext. In selecting the nodes, we chose the term list as the First Field of the matrix, and the source name as the Second Field, so the matrix analyzed co-occurrence of a pair of items drawn from  each list within the reports. 

> In following the null that their distributions are independent, the matrix calculates whether joint appearances of terms in newspapers is higher or lower than the average. If a cell is red, such as the one for ‘air pollution’ and ‘South China Morning Post’, the number of joint mentions of the term in the news paper is higher than expected. However, if a cell is blue, such as the one for ‘air pollution’ and ‘China Daily’, the level of co-occurrence between the two is lower than expected, meaning that there are fewer mentions of air pollution in the newspaper China Daily. The deviation marked by the strength of the color reveals the degree of their co-occurrence. While strong colors suggest either high or low co-occurrence of a pair in the articles, white cells do not feature correlation, meaning that their joint mentions revolve around the average. 

> ## B. Interpretation 

> The matrix offers an insight regarding the news outlets differing reporting on the environmental crisis in China. It reveals interesting correlations between terms and news sources. For instance, China Daily displays lighter shades for the same terms that display darker shades for South China Morning Post. A good example on that is the term ‘air pollution’, which has a light blue color when correlated with China Daily, but a dark red colour when correlated with South China Morning Post. This suggests that a topic, like air pollution, is rarely discussed in China Daily, while discussed more frequently in the South China Morning Post. Knowing that air pollution is a severe environmental issue in China, it is surprising to see that the main news outlet, China Daily, does not discuss it more frequently. On the contrary, there is a higher correlation of the term ‘climate change’ with China Daily than the term with South China Morning Post. This is possibly because China Daily reports on more international topics, while South China Morning Post reports on more national topics. Climate change in China, as discussing in earlier sections, is addressed as a global/international issue. Hence, reporting on it does not necessarily have to do with what is going on nationally in China. This could suggest that China Daily is willing to report on environmental issues that are international rather than voicing national environmental concerns. The matrix highlights the importance of taking into account the contextual meanings behind topics/terms.

> [Home](index.md) - [Previous Page](page3.md) - [Next Page](page5.md)
