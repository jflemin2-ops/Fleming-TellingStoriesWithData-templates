| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Title
Text here...

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._

## Step one: the visualization

_Include link to the original data visualization (or screenshot - make sure to correctly cite your sources, etc.).  Include paragraph or two on why you selected this particular data visualization.  For obvious reasons, the data visualization you select should come from a publicly accessible source._

https://lazy-cats.netlify.app/ 

## Step two: the critique
_Don't forget to complete the Google Form found on the assignment page.  You can summarize your thoughts here._
While the data is presented in a fun way and the topic itself is quirky enough to retain reader interest, some of the visualizations make no sense at a first glance. Especially the Top three activities of cats by time spent section.
The common trend in all of these maps is a lack of numbers which makes it harder to contextualize what exactly is being measured. I'd also work to simplify the data while working to keep the intentional creativity in the graphs by putting combing everything relevant
## Step three: Sketch a solution

<div class='tableauPlaceholder' id='viz1775047275062' style='position: relative'><noscript><a href='#'><img alt='Average time cats spend by activity ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Av&#47;AveragetimecatsspendbyactivityDRAFT&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='AveragetimecatsspendbyactivityDRAFT&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Av&#47;AveragetimecatsspendbyactivityDRAFT&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1775047275062');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

## Step four: Test the solution

_Before you conduct your interviews, prepare a simple script.  Use this as a guide and as a way to take notes as you go forward. Come up with your own list of questions you want to ask for the selected visualization. Keep the questions broad so you can get the most value out of your feedback. Then, document answers to your questions here._

Questions to ask (modify these for your own interviews): 

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

Results: 

_Don't identify or share personally identifiable information (PII) about the people you spoke to._

Question 1 w/ responses:
"What do you think this visualization is showing about cats exactly?"
* “It looks like it’s showing how much time cats spend on different activities in summer versus winter.”
* “I think it breaks down cat behavior into categories and compares them by season.”
* “It seems like a summary of daily activity for cats depending on the time of year. Hard to tell at first glance”

Question 2 w/ responses:
"What does this chart tell you about differences (or similarities) in cat behavior between summer and winter?"
* “It’s hard to tell patterns because there are so many bars.”
* “I’m not sure if there’s a seasonal difference since everything looks crowded.”
* “Maybe cats are slightly more active in the summer, but overall they’re mostly inactive.”

Question 3 w/ responses:
"Is anything about this visualization surprising or confusing to you?"
*“I find it overwhelming trying to compare all the individual cats. Too many bars.”
*“The colors make sense, but it’s hard to track one cat across the chart.”
*“The chart is unclear, I had to double-check what each color represented.”

Question 4 w/ responses:
"Who do you think this visualization is designed for?"
*“Maybe researchers who want detailed data on each cat.”
*“It seems more technical, like for someone analyzing the dataset closely.”
*“I don’t think it’s meant for a general audience it feels way too detailed.”

Question 5 w/ responses:
"What, if anything, would you change or improve about this visualization?"
*“I would reduce the number of cats shown or group them together.”
*“It would help to simplify it to show overall trends instead of individuals.”
*“Maybe separate it into smaller charts or remove some categories to make it clearer.”
Synthesis: 

_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._

Feedback consistently showed that while the detailed chart with Cat ID allowed for individual comparisons, it was overwhelming and made it difficult to identify clear patterns or seasonal differences. Moving forward, the simplified version should be easier to interpret, with readers being better able to quickly recognize that cats spend most of their time inactive and that behavior is relatively consistent across seasons. I learned that prioritizing clarity over granularity is more effective for communicating key insights. Based on this feedback, I'll choose to remove Cat ID (was a nice touch in the original, but kinda useless here) from the final design, categorize the data by season, and use a 100% stacked bar chart to highlight overall behavioral patterns more clearly.

## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

This was a hard one to try and simplify. The original visualization contained multiple graphs that, while quirky and interactable didn't explain much. The most creative visualization was the part at the end showing cats by name. This is what made me include Cat ID in the original visualization. While it added a lot of personality, it overall takes away from what should be taken away from the graph. Because of this, I chose to aggregate by season in the final design to prioritize clarity and highlight the dominant behavioral patterns across the dataset. The following is my result:

<img width="796" height="635" alt="Screenshot 2026-04-01 at 9 18 11 AM" src="https://github.com/user-attachments/assets/a13020ed-afc6-4751-ae13-98ca1cb1be62" />

The simplified version of the dataset is much more effective because it focuses on the big picture instead of getting lost in individual variation. By aggregating the data by season, the chart becomes immediately readable and you can quickly see that cats spend the majority of their time lying and sitting without having to scan through dozens of individual bars. This makes the main takeaway clear within seconds, which wasn’t possible in the more detailed version. It also improves comparison, since placing Summer and Winter side by side makes it easy to spot that behavior is fairly consistent across seasons.

## References
_List any references you used here._
https://lazy-cats.netlify.app/
https://github.com/Lisa-Ho/lazy-cats
## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._

