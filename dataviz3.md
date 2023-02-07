| [Homepage](https://yeonjin-park.github.io/portfolio/) | [Visualizing debt](/dataviz2.md) | [Critique by design](/dataviz3.md) |

# Critique by Design
In this page, I'll showcase a data visualization about `how I spent my time on the Thesis actually with a compared to my plan over 2 months`.  

## [🔗 A Link to the original data visualization](https://public.timelyapp.com/reports/CzCFGNvbGUuK1BuyejmyR6mJ) 
### **Why I chose this visualization?**
<br /> For this assignment, I used my own datasets, which has recorded for around 2 months(Oct 10th - Dec 16th, 2022). To precisely record all my work processes and boost productivity regarding the thesis, I logged all my digital footprints on the desktop and phone related to the thesis by using `Timely service and their AI software`. Timely support a data visualization feature based on collected datasets, and I chose one of their charts design that shows `planned vs. logged datasets on the thesis project` since I felt there are some points that could be improved on for a better user experience. 

![Timely Screenshot-1](Timely-log.png)
> Timely's timeline page, which is created based on collected user activity data (My personal page recorded on Oct 12th, 2022.)

### **Visualization(GIF)**
<br />Since the design I want to improve is not the public page I shared on the top, I attached the GIF that shows the private user page experience. 

<img src="timely-gif.gif" width="1400"/>  


## ⌛ Progress
### **Step 1. Insights I gained from the critique method**
<br /> 1) Which part stood out to me, and worked well? 
- Overall clear design that shows the trend of each planned and logged dataset. 

<br /> 2) What it led me to think about when considering the redesign? 
- It doesn't present the datasets that can give meaningful insights to users, such as visually highlighting the gap between planned and logged. 
- The design only shows weekly datasets, not considering time granularity which covers detailed, daily information that the AI already tracked. 
- The unit used in the x-axis is not easily read by users (W47 -> Week 47 -> October Week 3).    

---
### **Step 2. Sketch Wireframe**
<br /> While I critiqued the original visualization based on the given criteria(Stephen Few's Data Visualization Effectiveness Profile), I came up with some new ideas and drew the rough structure on my sticky note. The idea mainly focuses on `providing additional tabs(time/tags) to users` so that they can explore more meaningful datasets by themselves, not only `polishing visual details or revising unit issues`. 

<img src="wireframe-1.png" width="800"/>
> My first rough sketch for wireframe ideation

<br />
<br />
  Then I redrew the wireframes by using iPad, also considering the detailed layouts and interactions when user clicks each tab.

![Wireframe 2](wireframe-new1.jpg)
![Wireframe 3](wireframe-new2.jpg)
> My second iPad digital sketch 

---
### **Step 3. User Interview**
<br /> 1) User 1: Student, Late 20's
- Need visual consistency between both line charts (Log/Tag options). I prefer filling out inside of the line chart like the original chart since it clearly shows the differences among different instances. 
- Showing detailed user activities on the right side can bring users information overload. Maybe need additional depth(user action) to get access to this information.
- If possible, providing an insight dashboard would be helpful so that users can easily grasp insights from this dataset. (e.g. You spent 57% of your total working time on the prototyping phase during 2 months.)

<br /> 2) User 2: Student, Late 20's
- Color usage: need to highlight the "logged" dataset more by giving more contrast on two line graphs. (e.g. use grey color for "planned" line graph).

---
### **Step 4. Build it!**
<br /> First of all, I exported all the datasets into `.csv` from Timely so that I can use it for creating a visualization. I deleted some of the columns which will be not used for the design process. 
![Export_1](export-3.png)
> (L)Original .csv file (R)Processed .csv file

<br /> What I changed based on the user feedback: 
- Insights bullet point


## 📊 Final Design
### **How I spent my time on the Thesis actually with a compared to my plan over 2 months**
<br /> I mainly used `Figma` to create a data visualization prototype since it can showcase as many details as possible I planned. You can check the overall user experience from the below Figma prototype. I also implemented `a simpler version of this idea by using Tableau`, with the actual datasets I extracted from Timely. 
- What my data visualization shows 
- Why I selected the visualization 
- What I attempted to show differently 

`Figma Prototype: Please click any spaces so that you can explore the tool experience!`
<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="1200" height="800" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2F3Qlj7vQAxTVcJwJWexFUCq%2FData-Visualization-Class%3Fpage-id%3D1%253A2%26node-id%3D18%253A9%26viewport%3D-1562%252C-95%252C0.5%26scaling%3Dcontain%26starting-point-node-id%3D18%253A9" allowfullscreen></iframe>


<div class='tableauPlaceholder' id='viz1675738595316' style='position: relative'><noscript><a href='#'><img alt='How I spent my time on Thesis project compared to my plan over 2 months ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Th&#47;Thesisworklog-Final&#47;Sheet3&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Thesisworklog-Final&#47;Sheet3' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Th&#47;Thesisworklog-Final&#47;Sheet3&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='ko-KR' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1675738595316');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
