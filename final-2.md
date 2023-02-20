| [Homepage](https://yeonjin-park.github.io/portfolio/) | [Visualizing debt](/dataviz2.md) | [Critique by design](/dataviz3.md) | [Final Project 1](/final-1.md) | [Final Project 2](/final-2.md) | [Final Project 3](/final-3.md) |

# Wireframe and Storyboard

## Wireframe draft in Figma 
I initially started with a more product promotion-style website for the presentation but decided to move to the `cartoon style with a user scenario` since using the story would be more compelling for people and easy to follow. I tried to put some `feature-focused parts` (features: Overview timeline&Comparison) while people scroll down the user scenario so that they can easily grasp what features the users can use in the scenario. After finishing drawing the user scenario, I am planning to spend more time on exploring visualization types on the service I suggest. 

![sketches-final](Sketches-final2.png)
> My Initial wireframes for presentation.

`⬇ Please scroll down to see the overall flow of the wireframe.`
<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="1200" height="800" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2F3Qlj7vQAxTVcJwJWexFUCq%2FData-Visualization-Class%3Fpage-id%3D176%253A6%26node-id%3D182%253A1108%26viewport%3D832%252C461%252C0.5%26scaling%3Dscale-down-width" allowfullscreen></iframe>

## Storyboard
Before I started creating the wireframe, I came up with the story arc regarding the service for figuring out `what will be the entire user's career life along with the suggested features`. While I ideated the storyboard, I also put additional features(Trends, Network maps) on it as a future consideration. The storyboard mainly now focuses on the `entire career path of a tech worker with the service`, but I'll soon cover specific roles with different career levels like junior product designer, senior PM or lead engineer, etc. 
- `Yellow tag` refers to user actions with the service
- `Orange tag` refers to user situations(context) 

![storyboard](User-Scenario.png)
> Rough sketch of the user scenario 

# User research 

## Target audience
The target audience of my project is `all types of workers in the tech industry ranging from junior to lead level` since those workers' most work progress can be tracked in the digital environments. (FYI: I also interviewed non-tech workers like artists before, but they also agreed it would be hard to track all their work progress since most of their work will be progressed in a non-digital environment.) This can lead to precise results of the data visualization, which will help them to check all the details of the work progress with higher accuracy. But for this project, I narrowed down my interviewees to `product designers` working in tech companies because the datasets I used are from a product designer. 

### Approach to choosing Interviewees
To get the most varied feedback from the user group, I created a user group division like below: 
1) Based on their role: Junior / Mid-level / Senior 
2) Whether they habitually have written down work log: Yes / No 

I interviewed 3 people in total and mainly looked into people who regularly do self-reflection on their careers. When considering their background, I thought they'll also give more detailed feedback on the design of charts. 


## Interview script
Following chart includes goals and questions for my user interview. 

| Goal | Questions to Ask |
|------|------------------|
|   Aesthetics and Layout   |        What do you think about the overall layout and aesthetics of the wireframe?          |
|      |        Do you think the illustration style matches well with the overall wireframe design?          |
|   Logical Coherence   |        Is the story seems clear for you?          |
|     |        Which parts can I cut out for the 60 secs elevator pitch?          |
|   Prototype   |        What do you think about the chart designs? Are they seems the best chart type for this feature?           |
|      |       How's the design(color/layout) of the prototype?          |
|   Overall   |      What was the most compelling, and consufing parts of the overall flow?           |

Prior to asking all detailed questions, I shared some basic context of this project(60secs elevator pitching, need to address problems and actions, etc).

## Interview findings

All three people mentioned that my user scenario is compelling and helps them easily follow the overall structure of the service I suggest. The only problem was the presentation time limit, so they provided some feedback regarding `creating a more simplified flow and prioritizing the contents.`  

| Questions               | Junior Designer, UK | Mid-level Designer, US | Senior Designer, KR |
|-------------------------|--------------------------------|-------------|-------------|
| **What do you think about the overall layout and aesthetics of the wireframe?** |     I love the style of the illustration, which only highlights important parts by using limited colors.      |      Simple illustration with the mid-fi prototype seems harmonious. Those helped me to understand the user flow easily.       |     The use of a grey color background and a blue highlight color was a great choice.        |
|             **Do you think the illustration style matches well with the overall wireframe design?**            |         Yes, black lines with greyish-blue aesthetics are all applied in both wireframe and illustration, which makes the visual consistancy.                         |        Definitely, if the dashboard design is polished more, then it would be the best.      |       Yes. The only thing I want to mention is considering the size of the text. Some text boxes seem too small compared to other overall designs.      |
|          **Is the story seems clear to you?**               |             Flow is easy to understand, and the user story is clear.                   |         Yes, I can easily imagine how users can use this service in their career life.    |      Yes, but it'd be great if you could also cover lead or manager-level use cases in the scenario.       |
|          **Which parts can I cut out for the 60 secs elevator pitch?**                |            Maybe you can focus more on the features of each dashboard and reduce using the time for the intro and outro parts                     |      It'd be great to reduce some details of the problem statement parts. It seems to be taking over 20 secs.         |        How about cutting some of the feature explanation parts? You're now showing each of 4 features for two dashboards, and it seems too much for 60-second pitching. You can put it on another page to show it later if anyone asks about the details.     |
|         **What do you think about the chart designs? Are they seem to be the best chart type for this feature?**              |          It seems clear for me! If you put GIF for explaining the flow, then that would be great.                      |        If you have more time to consider time granularity(monthly), I would suggest presenting more high-level information on this time setting since it would be easier for users to read and also more playful.     |      Putting their achievement on the top of the comparison feature would be useful.(e.g. Apple Fitness: you achieved your goal 23 days in this month!)       |
|        **How's the design(color/layout) of the prototype?**               |               Need to use same typeface in the design. It seems you used two different typefaces for this design.                 |      Looks nice. Just need more polishing on layouts.        |       Overally good for mid-fi prototype. You can check Rawgraphs.com for creating a more high-quality data visualization.     |      
|         **What were the most compelling and confusing parts of the overall flow?**               |              The illustration is the big plus point of this presentation! But I guess you'll have to spend more time polishing the dashboard itself to create the GIF.                    |       Not the confusing part, but I would suggest you put some resources on the problem statement part since you did lots of interviews and surveys before.        |       Your presentation contents are all combined with the user scenario, which is a good strategy for short pitching. The only concern is time, so make sure you can highlight only important parts in a minute.       |


# Identified changes for Part III


| Research synthesis                       | Anticipated changes for Part III                                                |
|------------------------------------------|---------------------------------------------------------------------------------|
| Cut out parts for the presentation |Cut out some explanations of the dashboard, just highlight 1 or 2 important features. Also, problem statement can be more shorten.|
|                      Create a sticky navigation bar to add more detailed info for Q&A sesssion                    |          Rather than cut out contents in your main presentation, move them into another page and create a navigation bar so that you can show them in the Q&A session.                                                                       |
|                     Illustration as a introduction                     |                   Put an illustration that explains person using the service on the top of the page.                                                              |
|                    Put research resources in the problem statement part                      |                    Since I previously conducted some 1:1 interviews and online surveys to support the problem statement, I should put resources in the presentation.                                                             |
|                    How to integrate Tableau prototype into Figma?                     |                    Need time to process Timely datasets, and put GIF and Tableau link at the bottom of the Figma file.                                                             |




