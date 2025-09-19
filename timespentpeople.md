# Visualization of how poeple spend their time throughout their lives

<div class='tableauPlaceholder' id='viz1758252187371' style='position: relative'><noscript><a href='#'><img alt='Who Americans spend their time with, by ageBased on averages from surveys from 2010-2023 for Americans aged 15 to 80. Time spent with multiple people counts towards all. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ti&#47;TimeSpentPeople&#47;Sheet12&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TimeSpentPeople&#47;Sheet12' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ti&#47;TimeSpentPeople&#47;Sheet12&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1758252187371');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


## Source
U.S. Bureau of Labor Statistics (2023) – with major processing by Our World in Data https://ourworldindata.org/time-use#who-do-we-spend-time-with-across-our-lifetime


## Critique
I selected this data because I found it legitimately interesting. I was surprised at how prevalent each group was at different points in time and wanted to pick apart the data more. My main issue was that the only insight is seeing that “Alone” is most popular, followed by “Partner,” followed by everything else at the bottom. It is hard to look at individual trends for each line because even with distinct colors they all heavily overlap. I wanted to find a way to convey the same information but allowing for observation of individual categories.
Sketch
I thought that an area chart would be a good way to convey the specific information that I wanted: the individual times of each category. To this end, I created a pair of prototype charts in Tableau. They had the same information, but one stacked the areas together and the other separated them into six separate graphs.
### Stacked chart:
- Easy to see all data at once
- Compare categories quickly
### Six separate graphs:
- Tell individual stories
- All in one row: still good for comparison
- Moving average used to smooth out individual lines


## Test
For my testing, I shared my pair of initial charts with users to receive feedback on what story they thought was being told and which chart they preferred. The following set of questions was asked:
1. What are these charts telling you?
2. What confuses/surprises you?
3. Who might be the audience for these charts?
4. Which chart do you like more? Why?

### User 1 - ECE student
1. The charts are showing how much time americans spend with people based on relationship and age.
2. I'm not sure what moving average means (on the right graph)
3. i like the left one (with all of them on the same axes) since you can see all of it at once and it's easier to compare. it's kind of harder to see the time at different ages for the different relationships with the other one (idk if that makes sense at all)
4. alone seems like strange wording as a relationship but i guess it makes sense?

### User 2 - Pharmacy student
1. The average amount of time spent with different relationship types over a lifetime and how they compare to each other?
2. Having a hard time conceptualizing how much time the Y axis is representing. Also I'm assuming the year on the X axis is referring to age? Does the second figure not include 15 and 85 just because of space reasons?
3. The general public? Maybe some advertising people to market their product better somehow
4. There are things I like/dislike about both, the first one has everything all in one place but it can be a bit confusing because I only realized later that the values for the category are the area that its color takes up, not its height--I think I still like the first one better though

### User 3 - Music Composition student
1. Not sure what time spent means but it’s like who you spend your time with and how that changes
2. Don’t understand the units for time spent, and that children spike at like age 18 is concerning
3. Regular people who understand charts
4. My first instinct was #1 cause it feels a little cleaner but I’m now leaning towards #2 because it shows the proportions changing better

### User 4 - Biotech student
1. These charts are telling me who people (sampling Americans) spent their time with across their life. It shows that younger people tend to spend time with friends and family, adults spend most of their time with co-workers and children, and older people spend most of their time with their partner. It also shows that people generally spend more time alone as they get older.
2. The main thing that confuses me about this figure is what the units for time is (I am assuming hours per week). Something that surprises me is how much less time people spend with their friends in their early 20s.
3. The audience for these charts may be young adults and people studying societal trends.
4. I like the right one more because it is more clear that they are independent stats from each other and it is easier to observe trends in comparison to one another.

### User 5 - Architecture student
1. ok they are telling me who people spend their time with over the course of their lives
2. I am confused by the scale on the left like I want to assume it's % of time like 15 year old spend 30% of their time alone? or is it 10 bc the blue is visible from the 20 to the 30 mark? Unclear
3. audience might be ppl doing studies correlating things to the circles we spend time with- like development of social skills for young children or like happiness
4. I think the second chart is clearer more quickly

### Copilot
1. Both visualizations explore how Americans spend time with different social groups—partner, children, friends, family, co-workers, and alone—across their lifespan. They reveal a shifting social landscape:
- Time with friends and family is abundant in youth but fades with age.
- Time with children and co-workers peaks in midlife.
- Time spent alone increases steadily, especially after age 40.
- Partner time remains relatively stable through adulthood, peaking in later middle age.
2.
- The steep rise in time spent alone after midlife is striking. It’s not just a gradual increase—it becomes dominant.
- Friend time drops off dramatically after early adulthood, which feels emotionally significant.
- Partner time peaking around age 60 is unexpected—I’d have guessed earlier.
3. 
- Social scientists or psychologists studying relationship dynamics
- Designers or educators crafting narratives about aging and social connection
- Anyone reflecting on life stages—this could resonate with people making career or family decisions
- Policy makers or nonprofits focused on loneliness, elder care, or youth development
4. I lean toward the multi-panel line chart. It offers clarity by isolating each relationship type, making it easier to compare trajectories without visual clutter. The moving average smooths out noise, and the separation into panels invites deeper reflection on each relationship.

The general feedback was as follows:

### What are these charts telling you?
- Everyone clearly understood what the charts were trying to convey
- Users were able to reach simple conclusions about the data.

### What confuses/surprises you?
- Many users found the axes confusing. Either the axis titles need to be changed or a subtitle should be added that clarifies exactly what is being measured.
- Some users were surprised by the data itself. Humans seem to spend a lot of time alone as adults.

### Who might be the audience for these charts?
- Most users felt it was simply the general public.
- Others suggested that it was for social scientists and people researching human development.
- Another proposal was that it was targeting young adults who would have time to plan their futures with this in mind

### Which chart do you like more? Why?
- Votes for stacked: 2 
- Votes for individual: 4
- This was a close race, with multiple users saying they liked both.
- The second option seemed to minimize confusion.


## Build
With all of the feedback I collected, I was able to proceed with constructing my final graphic. As stated previously, the goal was to present the data in a way that allowed users to see the trends of each of the categories on their own. In my critique I identified this as my largest issue with the existing line chart, so I wanted to select a chart type that would mitigate the issue. To this end the second sketch option was chosen. This was the more popular choice, and the feedback specifically stated that it was better for reading individual categories.
The feedback given was also used to revise the names of the axes and title for the charts. This was done to dispel any confusion over what was being shown. A specific issue was that users were unsure about the vertical axis and whether it represented hours per day or week or something else. Overall it was very clear how to change the labels to communicate more effectively with the audience.


## AI Acknowledgement
Microsoft Copilot was used in the feedback process as part of user testing.

