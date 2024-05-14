---
    bibliography: custom.bib
---

## Abstract

Music Information Retrieval (MIR) is a field focused on extracting information from music, which takes the form of audio data in its rawest form. MIR has been developed over the past decades to allow modern music platforms like Spotify to provide in-depth musical analyses and personalized recommendations to each of its users, describing the emotions of a user's music preferences, clustering a user's liked songs into mood-based groups, and offering personal analyses at the end of each year based on the patterns of a user's listening history. These algorithms were my motivation for my project; I wanted to know, how can such a subjective art form as music be quantified as data for these tasks, and how can Machine Learning algorithms use this musical data to extract specific and subjective musical features? Through my research, I found that spectrograms can be effectively used in ML algorithms such as Convolutional Neural Networks and Support Vector Machines for emotion and genre classification, though more subjective tasks like timbre classification are still in rudimentary condition, with much room for future improvement. 

My full paper, bibliography, and code for generating example spectrograms lie in my project's [GitHub Repository](https://github.com/britt-lange/451-final-project).

## Introduction

My goal for this project was to analyze the current state of Music Information Retrieval and effectiveness of Machine Learning tasks on musical data. Throughout my research, I explored user-feedback-based algorithms such as Collaborative Filtering [@sanchez2016] as well as content-based algorithms for musical analysis. Many algorithms utilize visual representations of music known as spectrograms, to which more high-level algorithms can be applied for feature extraction [@costa2011; @costa2017; @pons2017]. I explore and analyze these algorithms thoroughly in my paper.



## Values Statement

People who might benefit from my project might be researchers interested in the state of Music Information Retrieval and the effectiveness of quantifying music for Machine Learning tasks. My project provides a synthesis of several Machine Learning experiments that have been performed on musical data, classifying the types of experiments based on the content they use and the tasks they attempt to perform. The organization of my project can provide guidance for anyone looking to perform experiments on musical data, allowing them to compare the effectiveness of different Machine Learning algoritms and data collection methods.

I have properly cited and credited all the researchers whose work I examined, though there could be potential harm in misquoting or misunderstanding their methods or intentions, mistakes that I tried my hardest to avoid.

I was motivated to embark on this project because I love music and am fascinated by all the mainstream technologies available for music analysis and classification. I wanted to learn how these tasks could be performed and how music could be analyzed by a computer as quantitative data, since music provokes such a personal, emotional experience in me. 

Overall, I think my project provides a useful synthesis of music-related data and algorithms, and I hope that others who are interested in the intersection of music and computer science may find it beneficial.

## Materials, Methods, and Results

My bibliography file includes all the works I examined, even if I did not utilize them directly in my paper. My methods involved organizing my paper into sections and subsections based on different types of algorithms and data collection methods as a means to make my paper readable and accessible. 

The most advanced and effective techniques employed spectrograms with various means of feature extraction, including convolutional kernels and Robust Local Binary Pattern (RLBP). While genre and emotion classification have become quite common and successful, more subjective musical elements such as timbre still evade machines' abilities to fully capture audio features. While there has been much development in MIR since its inception, there is plenty of improvement to be made in the future.

## Conclusion

My goal at the start of the project was to thoroughly examine the different ways music could be represented as data. Many of the content-based algorithms I explored employed music spectrograms, visual representations of musical data, which I briefly experimented with through Python's librosa library in [spectro.ipynb](https://github.com/britt-lange/451-final-project/blob/main/spectro.ipynb) [@librosa].

I conducted thorough research of many different types of algorithms and data representations and am quite satisfied with my findings. I believe I met my goals of comparing different ML algorithms performed on music and analyzing the effectiveness of different methods of quantifying musical data.

If I had more time or resources, I might attempt to reproduce some of the findings, specifically of the experimentation involving CNNs and RLBP, and fusing together the most effective algorithms. I would attempt to improve upon the findings of [@pons2017] in the task of timbre classification by incorporating other effective models like RLBP into the CNN structure.


## Personal Reflection

I learned a great deal about modern methods of music information retrieval. In my research, I was able to solidify my understanding of different algorithms we have studied, including CNNs, SVMs, and clustering, conducting extra research if I was unclear about a particular method of any study. Reporting in-depth on these algorithms helped me thoroughly learn the data collection and feature extraction methods necessary for complex data representations like spectrograms.

I am very proud of the work that I did. I was extremely thorough in my research, reading through plenty of different articles to find relevant ones to report on and taking into account the credibility of each before utilizing their documentation. I spent many hours researching and writing notes on my research, then organizing my research into different sections of my paper. 

Researching and writing a formal report allowed me to practice professional skills that I will use later in my career, as well as organizing and formatting a research paper. As I do not plan to pursue a career in Computer Science, I wanted to find a project that motivated me and combined CS methods with my own personal interests so that I could produce a final product that I was proud of and that I felt would help me learn something useful. I did find much of my research very interesting, and I know whenever I use Spotify's music analysis techniques I will think about the deeper mechanisms behind such algorithms. I worked very hard on my project despite the knowledge that I will likely not utilize Machine Learning knowledge in my postgraduate career, and I feel very proud of the work that I accomplished.