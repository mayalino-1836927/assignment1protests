# Assignment 1: Protests
The past few years in the United States, there has been a surge in protests in support of Black Lives Matter, gender equity, and other social issues. In this assignment, you'll work with data from [CountLove](https://countlove.org/) -- the same data often [cited](https://www.nytimes.com/2020/08/28/us/black-lives-matter-protest.html) by the New York Times -- to learn more about demonstrations over the past few years.

By completing the assignment, you will demonstrate the following skills:

- Use of **version control** for managing your code
- Declaring document rendering using **markdown** syntax
- Foundational programming skills in R.


## Background Research
Before diving into this (or any) dataset, it's important to have _domain familiarity_ (i.e., to know something about the topic). As preparation, I'm asking that you read **three articles** about protests in the U.S., and provide a brief 1 - 2 sentence summary or takeaway from each one.

In the section below, create an **unordered list** of the three articles you found. Make sure to provide an appropriate markdown link (_not_ just the URL) to the article in addition to your 1 - 2 sentence summary.

 - [Fighting as One: A Radical Action Plan to Beat Back Racism and Anti-worker Assaults](https://socialism.com/fs-article/fighting-as-one-a-radical-action-plan-to-beat-back-racism-and-anti-worker-assaults/) :
This article begins by remarking on the many crises that are currently and consecutively ocurring, and defines the working class and reminding its reader of the oppression of minorities as part of the working class and outside of it. It maintains that the working class must fight together to unite against oncoming fascism and towards racial justice.

 - [Protests Are About Changing Public Opinion, Not Cowering in Response to Polling Data](https://www.jacobinmag.com/2020/06/black-lives-matter-blm-protests-george-floyd) :
The purpose of the protests for Black lives are explored in this article, which responds to the sentiment of "defund[ing] the police" as being too radical. It asserts that the purpose of the protests are to radicalize people, and that it is not the time to take steps backward toward the goals of the protesters.

 - [Behind Virus and Protests: A Chronic US Economic Racial Gap](https://apnews.com/article/2f549d22162d9d1104c3f402c71e0c44) :
This article goes through the racial gap which are the reasons for the wave of protests. It explores the structural and institutional inequities which further worsen the conditions of working class people of color in the United States

## Accompanying Image
In this section, please **display one image** to accompany your text, and describe _why_ you included it (~2 - 3 sentences). This will require that you download an image into your project folder. In your description, use **bold** and _italics_ (at least once, for practice) to emphasize some of your points.
![Image of a mural for George Floyd, whose death sparked a wave of anti-racist protests across the country and over the globe against police brutality and for civil rights](https://im-media.voltron.voanews.com/Drupal/01live-166/styles/sourced/s3/2020-06/2020-06-05T003435Z_577282461_RC2O2H9P0MJY_RTRMADP_3_MINNEAPOLIS-POLICE-PROTEST.JPG?itok=2-qG-ELB)
A mural for **George Floyd**, whose death sparked a wave of protests all over the United States and across the globe; his name counts as _one of many_ of the lives prematurely taken by police brutality and racist profiling. This picture was included in remembrance of his life, but also to emphasize his impact on others for social justice by the great number of flowers and cards laid to rest by the mural.

## Analysis
At this point, you should open up your `analysis.R` script to begin working with the data. The script will guide you through an initial analysis of the data. Throughout the script, there are prompts labeled **Reflection**. Please write 1 - 2 sentences for each of these reflections below:

- What does the difference between the mean and the median tell you about the *distribution* of the data?

It tells me that the number of people attending these protests vary greatly by each event. There are events that will have greater than a thousand people and some that will have less than 100.
- Does the number of protests in Washington surprise you? Why or why not?

The number of protests do not surprise me in the sense that the timeline being analyzed is an era of political unrest and increased political participation in the US, but I also did not expect for there to be so many more protests from before 2020/at the beginning of the data set. 
- Looking at the `state_table` variable, what data quality issues do you notice, and how would you use that to change your analysis (no need to actually change your analysis)?

I do notice that some locations in the given data set have more detailed information (one plot included specific locations suc as "University of Washington", or "Golden Gate Bridge", while some just stated "Fargo, MN", etc). I think to address these issues I would have to use the String function to detect anomalies.
- Does the change in the number of protests from 2019 to 2020 surprise you? Why or why not?

It does not surprise me, since many events have ocurred in between those dates that have caused people to take to the streets. In between those dates there has been a global pandemic, an increased consciousness for civil rights, and growing tensions in the country in general.
- Do a bit of research. Find at least *two specific policies* that have been changed as a result of protests in 2020. These may be at the city, state, or University level. Please provide a basic summary, as well as a link to each article.

(Breonna's Law)[https://louisvilleky.gov/news/metro-council-passes-breonna%E2%80%99s-law-%E2%80%9Cno-knock%E2%80%9D-warrants-are-banned-lmpd] : this law has put a ban on "no-knock warrants" which is a practice that led to the death of EMT Breonna Taylor (whose death has also inspired a series of protests for police accountability) and has been used as an excuse for many more instances of police malpractice. 

(repeal on part of Civil Rights, Law Section 50-a)[https://nyassembly.gov/leg/?default_fld=&bn=9332&term=2015&Summary=Y&Memo=Y] : this act repeals the "Civil Rights Law" which prohibited the release of the records of police officers, corrections officers, firefighter, and other public service personnel. Previously section 50a of the Civil Rights Law made it so that the public cannot have access to police records.
- Take a look (`View()`) your `high_level_table` variable. What picture does this paint of the U.S.?

I see that there are many more Civil Rights, Racial Injustice, and Gun rights protests than any other purpose. This, when put into context the history of the US, paints a picture of its libertarian ideals and its relationship with race.

## Final Thoughts
When you are finished, with your analysis, please answer the following questions in 1-2 sentences each.

- What about the analysis surprised you?

The analysis is not easy for me to decipher, but it surprises me that the protests in the US can range from issues of a principal getting fired, to criminal justice reforms.
- What parts of this analysis did you find challenging?

I found it challenging to work with the data frames in R, as well as analyzing the plots. 
- What types of analysis do you wish you were able to do with the dataset, but currently don't have the technical skills to do?

I wish I could have made some sort of ranking of the highest number of attendees to each issue, but I found that at a certain point the data will just state "NA". I also would have liked to have done some sort of sentiment analysis with the articles linked in the data, but I do not have either the technical skills nor the planning and timeframe for it.
