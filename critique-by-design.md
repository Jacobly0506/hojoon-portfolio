| [home page](https://jacobly0506.github.io/hojoon-portfolio/) | [In-Class-Activities](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique and redesign (MakeoverMonday)

## Step 1: Choose a Data Visualization from MakeoverMonday
For this assignment, I selected the dataset and original visualization from the MakeoverMonday Week 47 (2022) challenge: **Railroad Infrastructure Quality Rankings**, because it presents a globally relevant topic that intersects with transportation, infrastructure investment, and development equity.

- **Dataset Source**: [MakeoverMonday 2022 Week 47 – Railroad Infrastructure Quality Rankings](https://data.world/makeovermonday/2022w47)

## Step 2: Critique the data visualization

<div class='tableauPlaceholder' id='viz1743544016656' style='position: relative'><noscript><a href='#'><img alt='Railroad Infrastructure Quality Rankings (2019) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ra&#47;RailroadInfrastructureQualityRankings2019Original&#47;Original&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='RailroadInfrastructureQualityRankings2019Original&#47;Original' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ra&#47;RailroadInfrastructureQualityRankings2019Original&#47;Original&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div><script type='text/javascript'>                    var divElement = document.getElementById('viz1743544016656');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>

### Rate each specialty in the original data visualization:

| Criteria        | Score (1–10) | Reasons |
|------------------|-------------|-----------|
| **Usefulness**   | 7           | The visualization serves a basic comparative function, ranking countries by railroad quality. However, without context or definition of the metric, its practical value is limited — especially for professional decision-makers. |
| **Completeness** | 5           | The chart lacks critical information such as the year, data source, and methodology. Viewers don’t know what the scores actually mean, reducing its ability to support informed interpretation. |
| **Perceptibility** | 7         | The horizontal bar chart is perceptually effective — bar length is easy to compare, and the descending sort helps with ranking tasks. However, all bars are the same color and not grouped, which reduces clarity of regional patterns. |
| **Truthfulness** | 6           | While the values are likely accurate, the missing context and scale definition undermine validity. The visualization may be unintentionally misleading by omitting key information. |
| **Intuitiveness** | 8          | The design is familiar and easy to understand for most users. No instructions are needed, which supports Few’s principle of intuitive design. |
| **Aesthetics**    | 6          | The design is clean but too minimal. There's little visual hierarchy, no use of color to distinguish insights, and no storytelling element to capture interest. |
| **Engagement**    | 5          | The chart is functional but not memorable. It doesn't encourage further exploration or deeper inquiry. There's no narrative hook or call to action. |

### Describe your overall observations about the data visualization here. What stood out to you? What did you find worked really well? What didn’t work well?
- The original visualization uses a horizontal bar chart to rank countries by railroad infrastructure quality. This approach works well for comparing values and makes use of perceptually effective encoding. However, it lacks key contextual details — it’s unclear what the score represents, there’s no mention of the year, data source, or how the values were calculated. The design is minimal and does not include color or visual cues to guide the viewer. It is functional, but not insightful. The viewer must do all of the interpretive work themselves.

### Who is the primary audience for this tool? Do you think this visualization is effective for reaching that audience? Why or why not?
- The main audience likely includes transportation policy professionals, infrastructure analysts, and people interested in global development. It may also be viewed by general audiences. While the design is simple and easy to understand, it does not provide enough information or context for professional use. It lacks transparency and depth, which limits its effectiveness for those who need to make data-informed decisions.

### Based on your critique, what do you think you’ll try to focus on in your redesign? Any ideas or inspiration for how you can make a better data visualization? What are you excited to try next?
- In my redesign, I will focus on making the score more understandable by clearly labeling what it represents, including the year and data source, and formatting values as percentages to indicate comparability. I will use a choropleth map to show spatial distribution and help the audience identify regional patterns. I’ll also use a diverging color scale with a midpoint at 50% to distinguish higher- and lower-scoring countries. I’m excited to apply what we’ve learned about critique-by-design and Stephen Few’s principles to create a clearer and more engaging final visualization.

## Step 3: Sketch out a solution

<div class='tableauPlaceholder' id='viz1743544864280' style='position: relative'><noscript><a href='#'><img alt='Railroad Infrastructure Quality Rankings (2019) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ra&#47;RailroadInfrastructureQualityRankings2019EarlyDraft&#47;Original&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='RailroadInfrastructureQualityRankings2019EarlyDraft&#47;Original' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ra&#47;RailroadInfrastructureQualityRankings2019EarlyDraft&#47;Original&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div> <script type='text/javascript'>                    var divElement = document.getElementById('viz1743544864280');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>

### Early Draft Solutions
To begin designing a solution, I explored alternatives to the original bar chart. I created a few early drafts in Tableau to test different ways of presenting the railroad infrastructure quality data more clearly.

In the original version, the bar chart showed raw scores ranging from 4.1 to 6.8, but it lacked context, visual hierarchy, and deeper engagement. It also used a single flat color and didn’t indicate how the score related to a broader range.

In my early redesign draft, I made two key changes:

- I normalized the data into percentages to make comparisons more intuitive.
- I applied a color scale based on the quality score, helping viewers quickly identify countries with higher or lower scores.

These changes are an attempt to improve:

- Truthfulness (by showing scale and percent context)
- Aesthetics (with color gradients)
- Completeness (with better labeling and interpretation support)

While this draft is still bar-based, it already provides more context than the original chart and moves toward more engaging storytelling.

## Step 4: Test the solution

<div class='tableauPlaceholder' id='viz1743555182317' style='position: relative'><noscript><a href='#'><img alt='Railroad Infrastructure Quality Rankings (2019)Note: Countries with a railroad infrastructure quality score above 50% are shaded in blue; those below 50% are shaded in green. This midpoint threshold helps distinguish between relatively higher and lower scoring regions for quick interpretation. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ra&#47;RailroadInfrastructureQualityRankings2019EarlyDraftMap&#47;DraftMAP&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='RailroadInfrastructureQualityRankings2019EarlyDraftMap&#47;DraftMAP' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ra&#47;RailroadInfrastructureQualityRankings2019EarlyDraftMap&#47;DraftMAP&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div> <script type='text/javascript'>                    var divElement = document.getElementById('viz1743555182317');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>

### Redesigning Process

After creating an early draft of the redesigned visualization using a choropleth map based on step 3, I presented it to my peers during the in-class critique session. The map shows global railroad infrastructure quality scores, using a midpoint threshold of 50%, with countries shaded accordingly. I did not explain the visualization during the critique. Instead, I observed how my peers interpreted it on their own and collected their feedback.

### Feedback Received

- Student, MEIM degree:
  Suggested I add a clear annotation explaining the midpoint (50%) threshold on the map, so viewers understand what divides the color scale between higher- and lower-performing
  countries.

- Student, MSPPM-DA degree:
  Mentioned that the color scheme could be improved. Instead of using green, blue is usually more positive. They recommended using a single hue
  with a gradient (e.g., light to dark blue) for more intuitive emotional cues.

- Student, ME-CEH degree:
  Suggested including filters (e.g., by global rank or top 10) to make it easier for users to explore the highest-performing countries and interact with the data.

### Insights & Patterns

- My group peers were able to understand the general purpose of the map without needing explanation, which indicates the basic visual layout and labeling were effective.

- Two of my group peers asked about the color logic, which showed that color choice impacts user interpretation and emotional framing.

- One of my group peers wanted interactivity or filtering options.

## Step 5: Build your solution

<div class='tableauPlaceholder' id='viz1743560286780' style='position: relative'><noscript><a href='#'><img alt='Railroad Infrastructure Quality Rankings (2019)Note: Countries with a railroad infrastructure quality score above 50% are shaded in blue; those below 50% are shaded in green. This midpoint threshold helps distinguish between relatively higher and lower scoring regions for quick interpretation. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ra&#47;RailroadInfrastructureQualityRankings2019Redesign&#47;MAP&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='RailroadInfrastructureQualityRankings2019Redesign&#47;MAP' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ra&#47;RailroadInfrastructureQualityRankings2019Redesign&#47;MAP&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div> <script type='text/javascript'>                    var divElement = document.getElementById('viz1743560286780');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>

### Final Visualization
For my final visualization, I used Tableau to create an interactive choropleth map that displays Railroad Infrastructure Quality Rankings (2019) by country. This redesign was built upon feedback from peers and guided by the principles of Stephen Few’s Data Visualization Effectiveness Profile.

### Design Decisions Implementation
- I included a clear annotation below the title explaining the 50% threshold used in the diverging color scale. This helps viewers interpret which countries are scoring above or below average.

- I updated the color palette to use blue for higher scores and green for lower scores, avoiding red-green contrast and aligning with color psychology — where blue often represents stability and quality.

- I added an interactive filter by Global Rank Group (Top 10, 11–30, etc.), allowing users to explore the rankings dynamically.

- Country labels include both the rank and score to improve perceptibility and reduce ambiguity.

**These choices improved several criteria from Few’s profile, especially:**

- Truthfulness: Clarified data range, source, and scale.
  
- Engagement: Enabled user exploration via filtering.
  
- Completeness: Added contextual explanations.
  
- Perceptibility: Used intuitive color contrast and clearer score display.static layout, focusing on clarity and perceptibility, even though filters were suggested. I opted not to include interactivity since this is a static assignment.

### Final Visualization Goal

This redesign aims to move beyond simple rankings to tell a more contextual and spatial story about railroad infrastructure quality worldwide. The map format helps audiences see patterns by geography, while the filter and hover features support more detailed data exploration.

## References
- **Dataset Source**: [MakeoverMonday 2022 Week 47 – Railroad Infrastructure Quality Rankings](https://data.world/makeovermonday/2022w47)
- **Video Referenced**: [Watch Me Viz - #MakeoverMonday 2022 Week 47 - Railroad infrastructure quality rankings](https://www.youtube.com/live/2ZREVC3jayU?feature=shared) by Andy Kriebel

## AI acknowledgements
- **GPT4.0**: Used for grammar checks and writing style
