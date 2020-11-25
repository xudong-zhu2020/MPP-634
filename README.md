Hi everyone, here is my project of advanced econometircs! It is about left-children's education in China.

# Background
China's urbanization resulted in an enormous labor transfer from to the countryside to cities, creating a large number of left-behind children. The number of left-behind children in rural areas has reached 61.03 million in 2010, accounting for 37.7% of rural children and about 21.88% of all children. Among them, half of them parents of left-behind children go out to work at the same time, which has a significant impact on the welfare and education of left- behind children.
![image](https://github.com/xudong-zhu2020/MPP-634/blob/MPP-634/截屏2020-11-25%20上午1.36.44.png) 

# Problem Statement
Parental labor transfer affects left-behind children’s education significantly: 1) long-term separation from parents will lead to decreasing parents' care for children’s education inevitably, negatively affecting student’s academic performance. 2) parental labor transfer has increased family income and then strengthen the ability to invest in children's education, positively affecting children's academic performance. 

The paper is to research how parental transfer affect children’s academic performance overall and to qualify the two disparate influence.

# Literature Review
Many scholars believe that, parental labor labor will have an impact on the welfare and education of their children. The research on the quantitative relationship between labor transfer and education investment is relatively rich. In contrast, quantitative research on the impact of the parents' concern for their children's learning is not as rich.

Scholars differ on the definition of left-behind children in China. The article considers children aged 6 to 16 who have not lived together with their father or mother for more than ten months in the previous year as left-behind children.

# Methodology
## Data Sources
The dataset comes from the China Family Panel Studies (CFPS) in 2016, including 8427 observations, and 25 variables.

## Variables
![image](https://github.com/xudong-zhu2020/MPP-634/blob/MPP-634/截屏2020-11-25%20上午12.28.02.png)

## Descriptive Statistics
![image](https://github.com/xudong-zhu2020/MPP-634/blob/MPP-634/截屏2020-11-25%20上午12.32.29.png)


## Empirical Analysis
### (1) Grades = α + β1 Left + β2 Fedu + β3 Medu + β4 Selfept + β5 Parept + β6 Gender + β7 Age + εi                       
### (2) Eduexp = α + β1 Left + β2 Fedu + β3 Medu + β4 Edustage + β5 Parept + β6 Gender + β7 Finc + εi                     
### (3) Parcare = α + β1 Left + β2 Fedu + β3 Medu + β4 Edustage+ β5 Parept + β6 Gender + εi  
![image](https://github.com/xudong-zhu2020/MPP-634/blob/MPP-634/截屏2020-11-25%20上午12.41.13.png)


### Yi = β0 + β1 X1i + … + βk Xki + βk+1 W1i + … + βk+r Wri + εi
### Xki =α0 + α1 Z1i + … + α1+m Zmi + αm+1 W1i + … + αm+r Wri + εi
### Grades = α + β1 Parcare + β2 Eduexp + β3 Selfept + β4 Gender + β5 Age + εi
![image](https://github.com/xudong-zhu2020/MPP-634/blob/MPP-634/截屏2020-11-25%20上午10.10.43.png)

# Policy Recommendations
## Family
### Avoid long-time separation from children
### More communication and pay enough attention to children's education.
### Increase education expenditures, especially the investment in extracurricular tutoring.


## Governments 
### Make adjustments in education expenditures
### Increase education expenditures for left-behind children and meaningful assistance programs
### Relax restrictions to allow children to receive education in cities and provide affordable education


## The whole society, especially NGOs. 
### Organize targeted and meaningful programs, such as homework tutoring

[Link](https://public.tableau.com/views/Book1_16051173926370/Dashboard2?:language=zh-Hans&:display_count=y&:origin=viz_share_link)

<div class='tableauPlaceholder' id='viz1606308197054' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_16051173926370&#47;Dashboard2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Book1_16051173926370&#47;Dashboard2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_16051173926370&#47;Dashboard2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-Hans' /></object></div>               

<div class='tableauPlaceholder' id='viz1606308197054' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_16051173926370&#47;Dashboard2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Book1_16051173926370&#47;Dashboard2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_16051173926370&#47;Dashboard2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-Hans' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1606308197054');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.minWidth='420px';vizElement.style.maxWidth='650px';vizElement.style.width='100%';vizElement.style.minHeight='587px';vizElement.style.maxHeight='887px';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.minWidth='420px';vizElement.style.maxWidth='650px';vizElement.style.width='100%';vizElement.style.minHeight='587px';vizElement.style.maxHeight='887px';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='727px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

