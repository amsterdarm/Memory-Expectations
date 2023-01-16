# Memory & Expectations

In this research project, I investigate whether memories of past inflation experiences can explain inflation expectations individuals report in surveys.

To do so, I build on the recursive learning algorithm approach by [Malmendier & Nagel (2016)](https://academic.oup.com/qje/article-abstract/131/1/53/2461168). The implied weights of past experiences following from MN's gain function capture an important fact, namely that experieces further in the past have decreasing importance for today's expectations. This phenomenon is called the "recency bias".  
I try to capture a second interesting feature of people's memory, namely increased retrieval of memories formed in the years of early adulthood. This phenomenon is dubbed "reminiscence bump" in the psychology literature. From [Berntsen & Rubin (2002)](https://psycnet.apa.org/record/2002-06812-011), I derive an empirical distribution of autobiographical memories.
I repeat MN's analysis, but with a gain sequence calibrated to match said empirical distribution and compare whether this learning sequence can better explain reported expecations.

As a first step, I will implement the main analysis of M&N2016 in python.

## Structure
* `data/` : all the data necessary to recreate my analysis
