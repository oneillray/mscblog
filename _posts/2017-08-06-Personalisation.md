---
layout: post
title:  "what is personalisation?"
date:   2017-08-05 22:43:41 +0100
categories: msc
---
# Content Personalisation

### Personalisation is quickly becoming a the norm in content websites theres day. We see tech companies that didn't exist tens years agp, completely disrupt [legacy] industries with personalisation services being a core offering.


{% include image.html
            img="/assets/spotify.png"
            title="spotfiy personalisation"
            caption="Spotify supplies me with brand new music that interests me, based on my previous history." %}

[insert image of airbnb]

{% include image.html
            img="/assets/airbnb.png"
            title="airbnb personalisation"
            caption="Airbnb have completely disrupted the holiday industry by empowering homeowners to become hosts" %}


Jeff Bezos famously stated 'If I have 3 million customers on the Web, I should have 3 million stores on the Web',  Personalisation is the unique a value proposition in eCommerce and publishers on the web. Additionally is helps to solve the increasing problem the information overload that users face particularly when navigating content websites.

{% include image.html
            img="/assets/irishtimes.png"
            title="irishtimes is an example where information overload exists"
            caption="User has to depend on their decision making skills about which article should they invest time to read" %}


In this post, I will give an overview of personalisation, outline the work done in the within the field of UX and explain some of the key terminology used when we talk about personalisation.

> “If I have 3 million customers on the Web, I should have 3 million stores on the Web”
**Jeff Bezos, CEO - Amazon**

Personalisation can be described as:

> A form of user-to-system interactivity that uses a set of technological features to adapt the content, delivery, and arrangement of a communication to individual users’ explicitly registered and / or implicitly determined preferences.

(Thurman & Schifferes, 2012)

> “Personalisation is the understanding of the user, the user’s tasks, and the context in which the user accomplishes tasks and goals”
( J. Karat, C. Marat, and J. Ukelson, 2000)

Personalisation aims to enhance user experience by taking into account that users preferences either implicitly or explicitly and display the most relevant information to that user. Schade (2016) describes personalisation as the as the customisation of a user experience by the system being used.Fan & Poole (2006) suggest that there is three sets of 'perspectives on personalisation' that can guide how personalisation is design. These perspectives are in relation to 1) changing the content, 2) the user interface, and 3) functionality to meet the needs of that user (Fan & Poole, 2006).

An interaction with a personalisation system typically works as follows: user elicits their preferences, the system then collects the preference data and through a compute algorithm it suggest content that it thinks would interest the user based on the preferences given to the system.

{% include image.html
            img="/assets/flipboard.png"
            title="Flipboard with its unique 'magazine type interaction"
            caption="Flipboard is seen as the market leader in giving a personalised 'magazine' type news reading experience." %}


/Screenshot 2017-07-26 13.21.17.png
**Google.com** implicitly personalises your search results but taking into account your location and search history.  


### Personalisation within the news

The goal of news website is to 'appeal to a wide-range of people with different motivations' (Marshall, 2007). However, creating a personalised experience for news content is a huge challenge given news articles generally have such a short shelf life and that interests in different topics can change quickly. Much of the work carried in the area of personalisation has been in measuring the the success of various personalisation algorithms in influencing user engagement (Knijnenburg & Willemsen, 2015). In addition, empirical studies have outlined which types of personalisation systems are most successful across the industry (Thurman & Schifferes, 2012). However very little has been done in the way of measuring the effectiveness of various user interface designs in the 'cold start' of content personalisation.  

#### Related Work

There has been many different takes on personalisation in academia in recent years. Some projects used content filtering whereas others have taken a collaborative filtering approach to personalisation. Researchers' have focused on creating systems that help track users interests' in both the short term and long. In most of these frameworks machine learning techniques have been applied to help with the accuracy of this programs.

- News Dude
- WebMate
- Scene
- Premise


There has also been some strides made in industry on understand content personalisation.

- BBC Labs
- FT labs


## Personalisation for mobile

With more and more content being produced by online publishers daily, the need for personalisation features on mobile since is evident [REF] . Context is increasing important variable when designing personalisation on mobile (De Pessemier, Vanhecke, & Martens, 2016), (Rogowski & Powers, 2013). Mobile users can be in different situation when using their smart phones ie commuting on a train, at home watching tv. This brings a challenge in delivering content to the user to suit these different situations. (Lamche, 2014) explores how different interaction methods can allow more user-friend content recommendations. Similarly, there's been research carried out outline user-needs in location-aware services. Although there's been work carried out in measuring these the user experience of recommendation systems (Nguyen, 2016), little has been done on comparing different user interfaces in the context of mobile.


## Testing Personalisation Methodology

Knijnenburg & Willemsen (2015), have set out a guide for carrying out user experience experience with in the realm of recommendation systems. In their paper, they outline guidelines for carrying out a UX evaluation of a recommender system as well as advice on finding participants for this user experience test and sampling data.



## Key Terminology in Content Personalisation

When we talk about personalisation, there are some key terminology that should be explained since they will be referred to often in this paper.

### Recommender Systems
Recommender systems are often used to address the problem of information overload by delivering content that addresses the interest of that user or group of user of similar interests.  This content can be presented to the user by means of either implicit or explicit personalisation depending on how that information is collected. It is important to explain what both these terms means we they will be referred to through this post.

### Cold Start
The 'Cold Start' problem is constantly referred when personalisation is being discuss. Cold Start is the challenge that a new user faces when they have first sign up to a service.  How system's help overcome the issue guessing what a user may be interested in without any information about that user to work with. The Cold start problem is still very much an unsolved issue, however companies such as [Netflix](https://en.wikipedia.org/wiki/Netflix_Prize) have seemed to make strides investing heavily into collaborative filtering technology to help make the on boarding process less frictionless.


/netflix-1.png

[Further reading on cold start](https://en.wikipedia.org/wiki/Cold_start)
. Further reading in around of items that should be presented in this cold start process can be read [here](https://ux.stackexchange.com/questions/81494/whats-the-best-way-to-show-too-many-options-with-checkboxes-to-user)

### Content Filtering

### Collaborative filtering

### Explicit vs Implicit Personalisation



### Explicit Personalisation

(Thurman & Schifferes, 2012) describe **Explicit personalisation** as the means of a user directly inter their user preferences to customise their reading experience. Explicit personalisation can be seen in various flavours within online new publishing, the most of which is the presentation of a 'My News' view is apparent in the BBCs mobile applications.  

*Direct user inputs*

/Image uploaded from iOS (3).jpg

#### Implicit Personalisation

**Implicit Personalisation** on the contrary requires no user interaction and content is often presented without the user being aware of the profiling and how the content is being personalised to their interests. There are many examples of this, the most obvious example is google search. When you type 'news' in google the results returned will be relevant to your geolocation.  [Ref needed]

*User preferences by using collected data eg. Via subscriber info or geolocation*

/Screenshot 2017-07-26 13.21.17.png


## Why is it important ? (100)

- It brings value to the end user.
- Analytics - business intelligence

Personalisation brings value to user but providing them with a customised experience that caters to their needs and goals. The main benefit of personalisation to the user is it that it can deliver content to users that interest them.

## The Value proposition of Personalisation

Personalisation is a strategy that is being adopted by news organisations to ensure that their content is remains relevant to individual users and to help keep their readers engaged by offering they an aggregated news feed which is [relevant] to their interests.

Another huge benefit of personalisation is that it allows for companies gain deep knowledge of their users behaviour patterns, and interests which has huge financial opportunities for publishers to become 'behavioural data companies'. Eli Pariser (2011) states unless newspapers...think of themselves as behavioural data companies with a mission [to produce] information about their readers’ preferences” they will be “sunk”.

/Screenshot 2017-07-31 14.56.04.png

After just a couple of search queries amazon provides suggestions of similar products that user might be interested in purchasing.

### What has been done in personalisation in the context of new websites?
# What do we know? What is there a gap / opportunity in?
- Evaluation User interfaces for preference selection in cold start to personalisation systems
-  
## How is it done? (100)
## Who's doing it? (100)



## Notable Papers

### What is personalisation?
- What to personalise and whom to personalise to

Fan, H., & Poole, M. S. (2006). What Is Personalization? Perspectives on the Design and Implementation of Personalization in Information Systems. Journal of Organizational Computing and Electronic Commerce, 16(3–4), 179–202. https://doi.org/10.1080/10919392.2006.9681199


### 'The Personalisation at News Websites'
A review of how new organisation have adopted personalisation features and the reliance of this technology to drive reader engagement.

- some context to mobile devices

*Thurman, N. & Schifferes, S. (2012). The Future of Personalisation at News Websites: Lessons from a Longitudinal Study. Journalism Studies, 13(5-6), doi: 10.1080/1461670X.2012.664341*


### Towards Conversational Recommender Systems.

*Christakopoulou, K., Radlinski, F., & Hofmann, K. (2016). Towards Conversational Recommender Systems. In Proceedings of the 22Nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (pp. 815–824). New York, NY, USA: ACM. https://doi.org/10.1145/2939672.2939746*


### Preface to the special issue on personalization and behavior change
- A study of how persuasive technologies are used to change users belabour through personalisation technologies

### Implicit User Profiling in News Recommender Systems

- This paper looks at that change of personalisation in the context of news articles and how user profiles could be built up for long-term interests and running contexts

Lamche, B. (2014). Improving Mobile Recommendations through Context-Aware User Interaction. In User Modeling, Adaptation, and Personalization (pp. 490–495). Springer, Cham. https://doi.org/10.1007/978-3-319-08786-3_45


###  Improving Mobile Recommendations through Context-Aware User Interaction

The usability, accuracy and interaction of personalisation on mobile application using Fashion as the case study.


### A personalised and context-aware news offer for mobile devices
- The increasing importance of considering context the designing for personalisation on mobile

De Pessemier, T., Vanhecke, K., & Martens, L. (2016). A personalized and context-aware news offer for mobile devices. In Lecture Notes in Business Information Processing (Vol. 246, pp. 147–168). Springer International Publishing Switzerland. https://doi.org/http://dx.doi.org/10.1007/978-3-319-30996-5_8


## References

1. Thurman, N., & Schifferes, S. (2012). The Future of Personalisation at News Websites: Lessons from a Longitudinal Study. Journalism Studies, 13(5–6). https://doi.org/10.1080/1461670X.2012.664341
