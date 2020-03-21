# Ultimate post on Coronavirus for @opendatascience telegram channel 

Dear readers and subscribers, we would have ignored coronavirus theme completely, wasn't it for 64% of you who asked for at least some information to be posted.

So we came up with rather big and thorouful post, available as a GitHub page, so you can submit your pull requests with updates / additions to the information provided.

We followed some rules, which we find adequate and which are based on the common sense and hope that all the contributors will comply with them:

1. Provided information should be correct, better if it is verifiable.
2. Source should be provided not to spread fake news data.
3. Biases and distributions should be taken into account: raw information is not that representative and can misguide opinions.
4. If appliable, information should be actionable — readers should get a clear picture of what they can do after reading it, not just get upset or worried.

## Learning and enlightning others

Briefing:

* Coronavirus is somehow similar to common cold: spreads throw air or surfaces, causes dry caugh and pneumonia on late stages.
* Despite being similar, it is much more contagious, because people are not even partially immune (yet).
* Danger comes from late stages and overloaded healthcare system.
* Diagnostics is hard, requires special tests.
* Most threatening is exponential (or viral) growth. Each carrier is able to infect ~2.5 ([source](https://twitter.com/AdamJKucharski/status/1239146318301483009)) people.
* More dangerous to elderly people.
* There are 2 strategies exploited by governments: letting build 'herd immunity' by quarantining older people and restraining all population, to flatten the curve to fight healthcare system overload.
* Other danger comes from panic and spread of misinformation (or censorship of that information by government): check for the fake news and trustworthness of the source.
* There is probability that the humanity will be infected and build immunity.
* Maps and sources of spread often do not take into account availability of tests ([why it matters](https://twitter.com/Bershidsky/status/1239488197719199744)) thus richer countries tend to have more diagnosed cases, thus, GDP correlation to cases per capita matters with 0.6 for Kendall and 0.8 for Spearman ([Post in russian](https://vk.com/wall66559_77852), [data](https://www.who.int/docs/default-source/coronaviruse/situation-reports/20200311-sitrep-51-covid-19.pdf) [sources](https://docs.google.com/spreadsheets/d/1nUny3LRZKxxaC0Q8XGIAaBlgd8kZAQysvLX0E93-Ens/edit#gid=0)).
 

### <a name="whoadvice"></a>WHO's advice for the public

WHO stands for World Health Organization and that's one organization you can trust in terms of health recommendations (it's like Open Data Science, but about Health 😉).

* Wash your hands better: use alcohol-based liqud or soap, wash your hands deliberately, like surgeons in the movies do. 
* Wash your hands more frequently: adopt a habit of washing hands before having a meal and after coming home / to work.
* Maintain social distancing: stay away from people sneezing or coughing. 
* Avoid touching your face, nose, mouth  and eyes. 
* Practise respiratory hygiene: cover your mouth and nose with your bent elbow or tissue when you cough or sneeze. [WHO Source](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/advice-for-public)
* Common thin face masks are not effective to protect from getting infected ([WHO](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/advice-for-public/when-and-how-to-use-masks)). 

#### Vox's article covering basics on coronavirus

Link: [Vox](https://www.vox.com/science-and-health/2020/3/6/21161234/coronavirus-covid-19-science-outbreak-ends-endemic-vaccine)

### Why exponential growth is so dangerous

##### Interactive article on how virus spreads

Kevin Simler's outbreak interactive demo shows and teaches from the case of single person how virus spreads.

[Project website](https://www.meltingasphalt.com/interactive/outbreak/) 
Link: [Github](https://github.com/kevinsimler/outbreak), Node JS 

##### Washington Post's article with demo

Link: [Washington Post](https://www.washingtonpost.com/graphics/2020/world/corona-simulator/)

##### Korean cluster's Reuter's inforgrafics

Link: [Reuter's  site](https://graphics.reuters.com/CHINA-HEALTH-SOUTHKOREA-CLUSTERS/0100B5G33SB/index.html)

##### DmitrySerg's spread simulation project

Link: [Project Github](https://github.com/DmitrySerg/COVID-19)

##### 📹  Videos

* [The Coronavirus Explained & What You Should Do](https://youtu.be/BtN-goy9VOY) by Kurzgesagt
* [Exponential growth and epidemics](https://youtu.be/Kas0tIxDvrg) by 3Blue1Brown

##### Pornhub's insights on traffic

Link: [Page](https://www.pornhub.com/insights/corona-virus)

## What you can do about it

1. Follow [WHO's advice](#whoadvice) to lower your chances of getting infecting.
2. Stay inside, switch to remote work if possible.
3 . Spread the word about the pandemia, share trustworthy information

## What you can do (as data scientists and active community members):

Most of the information about COVID-2019 causes panic and just leaves you with anxiety. But there are some projects, in which any dear data scientist reader can take part and *actually do something* about the virus (and that's worth repeating), apart from following advices to lower spread of virus and informing others with reliable sources. 


### Flatternthecurve

This website is also community-driven, you can help in any way: verifiyng information or translating the content.

Website: [Link](https://www.flattenthecurve.com).
Contribution guidelines: [github](https://github.com/flattenthecurve/guide/blob/master/CONTRIBUTING.md).

### folding@home coronavirus-specific projects

What: Donate your GPU power to help researchers develop drug against COVID-2019

Link: [Discussion on Reddit](https://www.reddit.com/r/pcmasterrace/comments/fhb5e4/coronavirus_specific_gpu_projects_are_now/)

## CLI-tool for COVID related data retrieving

Unified transcoding tool and cli for covid-19 related national and international datasets. You can help with the development or use it for you research.

Link: [Github](https://github.com/ggbaro/covid-health-ita)

### Building CT scan pneumonia detector

What: CT scan / Xray pneumonia detector.

Note: CT scan detection might be ineffective for COVID detection, because pneumonia is rather late stage on which intensive care is already required.

Project 1: [Github](https://github.com/JordanMicahBennett/SMART-CT-SCAN_BASED-COVID19_VIRUS_DETECTOR)
Project 2: [Github](https://github.com/ieee8023/covid-chestxray-dataset)


## Remote work

Some of us will spend more time working remotely. We all have different backgrounds and trivial information might be valuable for people just starting to work remotely.
Remote work due to the quarantine or self-isolation may seem challenging at first, but there is nothing to be afraid of. We collected some articles and FAQs which will help to transit to remote mode.

Links:
* Bloomberg's [article](https://www.bloomberg.com/news/articles/2020-03-15/how-to-work-from-home-tips-on-staying-healthy-sane-productive) on remote work.
* Great [guide](https://about.gitlab.com/company/culture/all-remote/guide/) from gitlab team.
* Now classic 37signal's book [Remote](https://basecamp.com/books/remote) about remote work culture and how to build it.
* Very practical guide about [Work/Life balance](https://wemake.services/meta/rsdp/work-life-balance) in remote work.
* [Tips](https://www.cnbc.com/2020/03/20/coronavirus-tips-for-protecting-your-mental-health-during-quarantine.html) for safeguarding your mental health during quarantine

Vitamin D and daily sports are also recommended during quarantine.


## Dashboards, Maps, Aggregations, Noteworthy articles

* The popular [medium article](https://medium.com/@tomaspueyo/coronavirus-act-today-or-people-will-die-f4d3d9cd99ca) with 40M views.
* https://www.worldometers.info/coronavirus/#countries
* John Hopkin's University interactive map on virus: https://coronavirus.jhu.edu/map.html
* Daily updated page with statistics (and references!) and other advices: https://ourworldindata.org/coronavirus

### More links 

* https://www.erasmusmagazine.nl/en/2020/03/14/unique-discovery-in-erasmus-mc-antibody-against-corona/
* https://www.biorxiv.org/content/10.1101/2020.03.11.987958v1
* https://www.reddit.com/r/datascience/comments/fieuqo/open_covid19_dataset/
* https://www.nationalgeographic.com/science/2020/02/here-is-what-coronavirus-does-to-the-body/
* https://jamanetwork.com/journals/jama/fullarticle/2762130
* https://www.thelancet.com/journals/lancet/article/PIIS0140-6736(20)30211-7/fulltext
* https://www.livescience.com/new-coronavirus-compare-with-flu.html
* https://www.theatlantic.com/health/archive/2020/02/covid-vaccine/607000/
