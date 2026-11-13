# Makeover Monday: GDP per Capita vs. Life Satisfaction

## Introduction

For this assignment, I selected a visualization from Makeover Monday that explores the relationship between GDP per capita and life satisfaction across countries in 2017.

The original visualization shows a positive relationship between GDP per capita and life satisfaction. However, some country labels overlap, and the different circle sizes are not clearly explained. The logarithmic scale on the x-axis may also be difficult for readers to understand.

My goal is to redesign the visualization to make it easier to compare countries, identify regional patterns, and understand the relationship between GDP per capita and life satisfaction.


## Original Visualization and Data Source

The original visualization, *Self-reported Life Satisfaction vs. GDP per Capita (2017)*, was published by Our World in Data and featured in Makeover Monday.

The chart compares GDP per capita and self-reported life satisfaction across countries in 2017.

**Original Visualization**: [Our World in Data – Self-reported life satisfaction vs. GDP per capita](https://ourworldindata.org/happiness-and-life-satisfaction)

**Data Source**: Our World in Data, using GDP per capita and life satisfaction data.


## Critique of the Original Visualization

### Strengths

The original visualization clearly shows a positive relationship between GDP per capita and life satisfaction. The axis labels help readers understand what is being compared, while the different colors make it easier to identify regional patterns.

### Weaknesses

One issue is that many country labels overlap, making it difficult to identify individual countries. The circles also have different sizes, but their meaning is not clearly explained. In addition, the logarithmic scale on the x-axis may be confusing for readers who are unfamiliar with this type of scale.

### Redesign Goals

My goal is to make the visualization easier to read and compare. I plan to use circles of the same size, label only selected countries, and provide additional information through tooltips. I also want to make the logarithmic scale clearer and use consistent regional categories to help readers compare countries.


## Wireframe and Initial Redesign

Before creating the visualization in Tableau, I sketched a wireframe to plan how I wanted to improve the original chart.

In my redesign, I decided to use circles of the same size and label only a few selected countries to reduce clutter. I also planned to include tooltips so readers could explore individual countries without displaying too much information on the chart.

I kept the logarithmic scale for GDP per capita but wanted to make it clearer through the axis label. I also planned to use six continent categories to help readers compare regional patterns.

### Initial Wireframe

The sketch below shows my initial plan for the redesigned visualization.
![Initial Wireframe](wireframe.png)


## Peer Testing and Feedback

I shared my initial visualization design with two participants to understand whether they could identify the main message and what improvements they would suggest.

**Participant 1**: A MAM student with experience in arts education and fundraising.

My first participant thought the chart was clean and easy to read. She could immediately recognize the positive relationship between GDP per capita and life satisfaction, and she felt that both axes were clearly labeled. However, she was unsure why I had highlighted specific countries or what I wanted readers to learn from them. She also thought there were too many colors and felt that regional differences did not need to be the main focus of the visualization.

**Participant 2**: A MISM-BIDA student with previous experience as a business analyst.

My second participant first noticed Europe because of its bright color. He observed that European countries generally had higher GDP per capita and life satisfaction, while many African countries were concentrated in the lower-left area of the chart. He also recognized the overall positive relationship between the two variables.

He suggested narrowing the focus and using the title to communicate a more specific takeaway. He also felt that the colors were distracting. Instead of highlighting countries without explaining their significance, he recommended focusing on a few interesting outliers and connecting them to a clear story.

### What I Learned

Both participants could understand the positive relationship between GDP per capita and life satisfaction, which showed me that the basic scatterplot was effective. However, they both felt that the colors and highlighted countries made the main message less clear. The first participant focused more on readability and simplicity, while the second emphasized the importance of a specific takeaway and a stronger story. Their feedback helped me realize that I needed to be more intentional about which countries I highlighted and why.

### Planned Improvements

Based on their feedback, I decided to revise the title to communicate the main takeaway more clearly and simplify the colors by using gray for most countries. Instead of highlighting several countries without a clear purpose, I planned to focus on Costa Rica and Botswana because they have similar GDP per capita but very different life satisfaction scores. I also planned to use orange to highlight these two countries and add an annotation explaining their differences. This would allow readers to see the overall positive relationship while also understanding why these two countries are worth comparing.


## Final Redesign in Tableau
After receiving feedback from my two peers, I revised my visualization to make the main message clearer and reduce unnecessary distractions. I changed the title to highlight the positive relationship between GDP per capita and life satisfaction. Instead of using different colors to represent continents, I changed most data points to gray and used orange to highlight only the countries relevant to my story. I also adjusted the y-axis range from 0–8 to 2–8 to reduce empty space while keeping the scale visible.

I decided to focus on Costa Rica and Botswana because they have nearly identical GDP per capita ($15,525 and $15,807), but very different life satisfaction scores (7.23 and 3.50). I added an annotation to highlight this 3.73-point difference and explain why these two countries are worth comparing. These changes help readers see the overall positive relationship while also recognizing that GDP per capita alone does not fully explain differences in life satisfaction.

Compared with my initial wireframe, my final visualization uses a simpler color scheme and focuses on two specific countries instead of regional differences. Although I originally planned to use different colors for continents, the peer feedback helped me realize that this was not necessary for the story I wanted to tell. I kept the equal-sized circles, limited country labels, and tooltips from my original plan, but shifted the focus to comparing Costa Rica and Botswana.

### Final Visualization

[View my final visualization on Tableau Public](https://public.tableau.com/app/profile/joy.kuo6896/viz/1_17945133428230/GDPperCapitavs_LifeSatisfaction2017?publish=yes)

![Final Tableau Redesign](GDP%20per%20Capita%20vs.%20Life%20Satisfaction%20%282017%29.png)


## References

Our World in Data — *Self-reported Life Satisfaction vs. GDP per Capita (2017)*. [Original Visualization](https://ourworldindata.org/happiness-and-life-satisfaction)

Makeover Monday. [Makeover Monday](https://makeovermonday.vercel.app/dataset/2020w11-self-reported-life-satisfaction-vs-gdp-per-capita)


## AI Acknowledgements

I used ChatGPT to help improve the wording, grammar, and organization of my written explanations. I also used it for technical guidance while working in Tableau, including creating calculated fields and adjusting chart formatting. The critique, wireframe, peer feedback, and final design decisions were based on my own observations and work.
