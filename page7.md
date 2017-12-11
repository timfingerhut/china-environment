<title>Example</title> <style> body { margin:0; padding:0; background-image:url("/china-environment/assets/images/Factory.pdf"); background-repeat: no-repeat; webkit-background-size: cover; moz-background-size: cover; o-background-size: cover; background-size: cover; } </style>


> # <b>VII. Comparison of Newspapers - A Criticality Index</b>

```ruby
> // What do we mean by criticality index?
> We constructed a criticality index to measure the degree to which a publication is critical of government.
```
> ## Methodology
> First, we came up with a list of terms, which are proxies of the willingness of publications to criticize the government in power. Then, we annonate the terms using the Cortext script ["Corpus Term Indexer"](https://docs.cortext.net/corpus-terms-indexer/). In order to operationalize the indicator, we normalized results in a spreadsheet (screenshot below). We then critically evaluate the usefulness of this numerical indicator. For this purpose, we utilize both the temporal indexation option (Cortext's ["Demography"](https://docs.cortext.net/demography/) and also criticize the indicator by case studies. In order to find the cases, we went back to Factiva to search for and randomly select articles mentioning both "corruption" and "environment", which we deemed relevant based on the indicator analysis.


> ## Research
> When thinking about how different Chinese newspapers treat the environment, one question that readily comes to mind is to which degree a source criticizes government. We decided to develop an exemplary indicator, which can serve to compare the criticality of sources. 

> We assume that a proxy to government criticism is the number of times a source mentions issues like smog, death, corruption and censorship. We then normalized the occurrences to calculate how many times these issues are mentioned each 100 articles. 

> ![network map]({{ site.url }}/china-environment/assets/images/criticality.jpeg)

> Corruption and censorship appear to be particularly sensible topics. 

> The table above allows us to draw some tentative conclusions:
> - Censorship appears to be an issue that is "off limits" for the press in mainland China. Only China Daily and the South China Morning > Post consider the topic, but South China Morning Post is 12 times more likely to treat the subject. 
> - Corruption further captured our interest. We see that the index score of the Global Times is actually the highest. South China Morning Post is 50 % more likely to mention the issue than China Daily. 

> But how much do we learn from these index scores? In order to further evaluate the data, we compare how the discussion of corruption evolved over time in the South China Morning Post and in China Daily. We conclude that Xi Jinping's anti-corruption push started to "unleash" the discussion of corruption in China Daily.

> ## South China Morning Post
> ![network map]({{ site.url }}/china-environment/assets/images/censorship-corruption-southchinamorningpost.jpeg)

> ## China Daily
> ![network map]({{ site.url }}/china-environment/assets/images/corruption-china-daily-keycutoff183-march2015.jpeg)

> One can dig even deeper by descending to the level of individual articles. These results actually lead us to re-consider the pertinence of our index scores. A qualitative evaluation of randomly selected articles mentioning both corruption and the environment published in the South China Morning Post and China Daily shows that there are qualitative differences in the news coverage not captured by our numerical index scores. 

> ## South China Morning Post

> ![network map]({{ site.url }}/china-environment/assets/images/south-china-morning-post-example.jpeg)

> ![network map]({{ site.url }}/china-environment/assets/images/south-china-morning-post-example2.jpeg)

> ![network map]({{ site.url }}/china-environment/assets/images/southchina-example3.jpeg)



## China Daily

> ![network map]({{ site.url }}/china-environment/assets/images/chinadaily-example-environment-corruption.jpeg)

> ![network map]({{ site.url }}/china-environment/assets/images/chinadaily-example2.jpeg)

> We welcome any suggestions for the development of further indicators or terms connotating criticality toward government! 
