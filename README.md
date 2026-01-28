# first_e-literature_dataset

Welcome to my third repository!

![repo](https://upload.wikimedia.org/wikipedia/commons/e/e7/Core%2BRepository%2Bcore_samples2.jpg) 

*Core sample labels of a sea floor sample repository, found in [Wikimedia commons](https://commons.wikimedia.org/wiki/File:Core%2BRepository%2Bcore_samples2.jpg)*

This is the last one coming from the **Digital Literary Studies** course, held at the Ca’ Foscari University in the academic year 2025/2026. 

For this work, Professor Emmanuela Carbé, who held the course, gave us a peculiar task. This time, instead of doing a textual analysis of a digitised text (see [first_repository](https://github.com/ClaraPetraMariafrancescaBusdon/first_repository) and [first_textual_analysis](https://github.com/ClaraPetraMariafrancescaBusdon/first_textual_analysis) repositories to see my previous works on the matter), I had to find and investigate at least fifteen pieces of **digital-born literature** and build the relative [**dataset**](https://github.com/ClaraPetraMariafrancescaBusdon/first_e-literature_dataset/blob/main/data/e_lit_dataset%20-%20Foglio1.csv). We’re talking about digital-born texts, where their digital characteristics are deeply intertwined with the structure of the e-literature object itself. Hence, printing them is impossible, because they'd lose an important part of what made them an electronic literature object in the first place.


## SELECTION CRITERIA

During our classes, we analysed some emblematic works, like the ones written by **Michael Joyce** ([*Afternoon: A story*](https://the-next.eliterature.org/works/1040/0/0/), 1987 and [*Twelve Blue*](https://the-next.eliterature.org/works/666/0/0/), 1996) or like the generative digital poetry work by **Nick Montfort**: [*Taroko Gorge*](https://collection.eliterature.org/3/works/taroko-gorge/taroko-gorge.html).

In this repository, I’ll present the examples of digital literature found in the [**Online Journals section**](https://the-next.eliterature.org/categories/online-journals), in the Electronic Literature Archive of the [*Electronic Literature Organization's website*](https://eliterature.org/). 

![electronic literature](https://upload.wikimedia.org/wikipedia/commons/b/b5/Binary_blue.jpg)

*Not its best representation, but good for visualizing the possibilities of Electornic Literature. Found in [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Binary_blue.jpg)*

My first selection criteria is related to the language. Since the Master’s Degree I'm currently attending is in **English**, I wanted to keep the language uniform in this repository as well. This could help with the homogeneity, but could at the same time be a [limitation](#limitations) as well.

I think I started searching from this category because I was influenced by the thoughts of **Serge Noiret** written in his essay [*Digital History 2.0*](https://www.academia.edu/4558748/Digital_History_2_0_in_Clavert_Fr%C3%A9d%C3%A9ric_and_Noiret_Serge_dir_eds_Lhistoire_contemporaine_%C3%A0_l%C3%A8re_num%C3%A9rique_Contemporary_History_in_the_Digital_Age_Bruxelles_Bern_Berlin_Frankfurt_am_Main_New_York_Oxford_Wien_Peter_Lang_2013_pp_155_190) (2010), which I’m currently studying. Here, Noiret highlights that traditional historians have a tendency of searching for a book structure even in web 2.0 products, as well as working individually. I may not be a traditional historian, but I recognise that I too have a tendency of working alone and of searching for a traditional book structure, even in digital works. So I wanted to check the fruits of **collaborative work**, even when done at different levels.

I explored several journals, choosing in the end the works which I found more interesting. They all come from seven out of ten journals currently available online. So in the [dataset](https://github.com/ClaraPetraMariafrancescaBusdon/first_e-literature_dataset/blob/main/data/e_lit_dataset%20-%20Foglio1.csv) you’ll find electronic literature objects coming from [*Cauldron & Net*](https://the-next.eliterature.org/collections/4) (1997-2002), [*frAme*](https://the-next.eliterature.org/collections/15) (1999-2001), [*Poems That GO*](https://the-next.eliterature.org/collections/14) (2000-2004), [*Riding the Meridian*](https://the-next.eliterature.org/collections/13) (1999-2000), [*The New River Journal*](https://the-next.eliterature.org/collections/42) (1996-Present), [*Vectors*](https://the-next.eliterature.org/collections/31) (2005-2013), [*Word Circuits*](https://the-next.eliterature.org/collections/1) (1998-2004).

In the [dataset](https://github.com/ClaraPetraMariafrancescaBusdon/first_e-literature_dataset/blob/main/data/e_lit_dataset%20-%20Foglio1.csv), there are twenty different types of e-literature.Except for three of them ([*Four Guillemets*](https://the-next.eliterature.org/works/2270/0/0/) and [*Blood Sugar*](https://the-next.eliterature.org/works/1593/0/0/), both from 2012 and [*DO IT*](https://the-next.eliterature.org/works/2174/42/0/), 2018), all of the others are dated between the end of the **90s** and the first years of the **2000s**. Not all of them come from a collaborative effort, but they’re in the [dataset](https://github.com/ClaraPetraMariafrancescaBusdon/first_e-literature_dataset/blob/main/data/e_lit_dataset%20-%20Foglio1.csv) anyway because I found them intriguing. So I could say that one of the selection criteria is my **personal taste** as well.

There are some similarities between the choices. Some of the types were completely missing, like generative poetry, whereas others, like **hypertext fiction** and **hypertext poetry**, were chosen more often. 
Then, considering the literary genre, I chose at least half of the time works of **poetry**. 

What isn't poetry is mostly related toward either **epistemological questions** (What is the text? Where does the text begin and end in an e literature object? An example is [*Cruising*](https://the-next.eliterature.org/works/387/0/0/), 2001, which makes the user reflect upon the materiality and the pacing of the text) or **social related issues** (see the essays [*Blood Sugar*](https://the-next.eliterature.org/works/1593/0/0/), 2012 and [*Public Secrets*](https://the-next.eliterature.org/works/703/0/0/), 2007)

## DATA MODEL 

In total there are **fifteen columns**. Except the Item_number, used as a key for eventual future database, the other columns can be grouped in three categories:
1. Basic information related to basic metadata;
2. Data related to hardware, software and/or physical aspects involved, as well as computer language;
3. Data about the type, genre and preservation state of the e-literary object itself
For more details, check [this file](https://github.com/ClaraPetraMariafrancescaBusdon/first_e-literature_dataset/blob/main/data/data_dictionary.md) which explains the dictonary used in more detail.

## LIMITATIONS

![speed limit](https://upload.wikimedia.org/wikipedia/commons/a/ab/2004-05-02_Speed_Limit_3.jpg)

*Speed limit sign found in [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:2004-05-02_Speed_Limit_3.jpg), which suits pretty well this situation*

There are **three** possible limitations to my [dataset](https://github.com/ClaraPetraMariafrancescaBusdon/first_e-literature_dataset/blob/main/data/e_lit_dataset%20-%20Foglio1.csv):
1. Choosing only e-literature coming from Online Journals could have prevented me from exploring in more detail the works made by individual, **independent authors**
2. **Language**
   Even if this is listed as a selection criteria, not choosing works in different languages could have prevented me from making intriguing and promising comparisons.
Maybe in the future I should try exploring only one genre, but in multiple languages
3. **Preservation issues**
   Some of the works were impossible to retrieve and explore, because they were unavailable or going under maintenance. At the same time, a plug-in, called Flash 9, which was necessary in order to access some of the works in the list, was not available on my laptop, making it impossible to explore those projects in more detail.
   I chose to add these in order to highlight the **issue of accessibility**, which is one of the most crucial topics in the Digital and Public Humanities field.
