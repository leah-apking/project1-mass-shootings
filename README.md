# Project 1: Mass Shootings Investigation

### Students
 - Leah Apking
 - Julie Eremeeva
 - Nancy Gomez
 - Isidore Lozano 
      
### Background 

Gun violence has been a constant in American life for generations, but mass shootings seem to have become prevalent than ever before. Though they make up only one percent of gun violence nationwide, mass shootings are in the news nearly every week. In 2023 there have been more mass shootings in the United States than days on the calendar, but the topic of gun control remains highly politicized with little being done on a national level.

Everytown for Gun Safety and the Gun Violence Archive define mass shooting as any incident in which four or more people are shot and wounded or killed, excluding the shooter. This is the definition we will use to define a mass shooting incident.

We are taking a closer look at mass shootings in the United States over the last 8 years (2015-2022). We are about to find out if it has really become a more frequent issue. Do community factors such as poverty rate or population density impact the frequency of mass shootings? Are restrictive guns laws in blue states effective in limiting mass shootings? Are mass shootings more common in red or blue states? Are mass shootings more common to occur in a certain season? Let's see what story data will tell us this time. 

### Data Sources

#### Mass Shootings Data and Crime Data: 
   - https://www.gunviolencearchive.org 
   - https://www.theviolenceproject.org/mass-shooter-database/

#### Census Data: 
   - https://www.census.gov/data/developers/data-sets.html

#### Gun Policy:
   - https://everytownresearch.org/ 
   - https://giffords.org/lawcenter/gun-laws/


### Research questions
  1. Have the rates of mass shootings increased in the last 8 years?
  2. Does local poverty rate/ lower median family income contribute to greater prevalence of mass shootings in the US?
  3. Do gun laws impact the prevalence of mass shootings?
  4. What percentage of gun violence is related to mass shootings?

### Have the rates of mass shootings increased in the last 8 years?

We have seen a significant increase in the number of mass shooting incidents in recent years. In 2022 the United States experienced 641 mass shooting incidents, just down from a high of 688 in 2021; compared to 335 incidents just a few years earlier in 2018. We found that more mass shootings occur during the summer months, with July having the highest number of incidents, followed by June and August.

![total_per_year](https://github.com/leah-apking/project1-mass-shootings/assets/119013360/1bba3772-52cb-4f08-be73-88eff730fed0)

Between 2015 and 2022 Illinois experienced the highest number of mass shooting incidents followed by California and Texas. However, these figures are not adjusted for each state’s population. Among major cities Chicago had the highest number of mass shootings during this period.

### Does local poverty rate/ lower median family income contribute to greater prevalence of mass shootings in the US?

After reviewing census data from 2015 and 2020, we were unable to find a correlation between poverty level and instances of mass shootings. Further investigation including all forms of gun violence would likely find a relationship between poverty levels and gun violence, but our research was limited to mass shooting incidents. We suspect that other factors, such access to firearms, strength of gun control legislation, and availability of mental health care, may be more significant than poverty levels when seeking to understand the increasing rates of mass shootings in the United States.

### Do gun laws impact the prevalence of mass shootings?

Everytown for Gun Safety Research and Policy conducts rigorous, independent research related to gun violence in the United States. Everytown scores every state on the strength of its gun laws by analyzing the 50 most important policies for each state, the laws with more substantial impact are worth more points, with a total of 100 possible points. Laws with the most significant impact and point value include background check requirement, extreme risk laws, and the elimination of the “Stand Your Ground” law.

#### Everytown for Gun Safety Rankings:
* #1.     California (86.5 points)
* #2.     New York (81.5 points)
* #50.   Mississippi (3 points)

When evaluating the effectiveness of stricter gun laws on mass shooting incidents and deaths all figures will be shown in frequency, the number of mass shooting incidents/deaths per million people, to prevent the skew caused by varying state populations. Linear regression shows an overall decrease in the frequency of mass shooting death as gun law strength increases.

![fig_laws1](https://github.com/leah-apking/project1-mass-shootings/assets/119013360/d76eec9f-bd72-4711-bf7c-b1bca7a6a37a)

Comparing mass shooting incidents and deaths between historically red, blue, and swing (purple) states with a set of ANOVA tests showed the variation between groups was not statistically significant. (p<sup>deaths</sup>= 0.385; p<sup>incidents</sup>= 0.641).

![fig_laws5](https://github.com/leah-apking/project1-mass-shootings/assets/119013360/f520c449-6465-439b-a324-d8eb1c590fe6)

To evaluate how indiciual gun policies effect mass shooting deaths we chose five laws that are commonly discussed following mass shooting incidents. We included background check requirements and the elimination of the “Stand Your Ground” law, two of the laws included in Everytown’s level 1 grouping of the most impactful gun laws, well as laws required waiting periods for firearm purchases, assault weapons bans, and high-capacity magazine bans.

In all five cases states with the restrictive gun policy had less frequent mass shooting death than those without the restriction. Although, independent t-tests determined that the only policy showing a statistical difference was legislation removing “Stand Your Ground” or “Shoot First” laws (p = 0.047). 

![fig_laws4](https://github.com/leah-apking/project1-mass-shootings/assets/119013360/2fd59928-e64c-4f26-b1c1-dabfa7217629)

While restrictive gun legislation is one of the few current defenses against mass shooting incidents and the deaths and injuries they cause, the analysis conducted shows their effect is limited. When controlling for size of population, states with more strict gun regulations experience fewer mass shooting incidents and deaths. The one case that showed a statistical significance, ending “Stand Your Ground” laws may help disprove the idea that arming more citizens will help protect the public in the event of a mass shooting and indicate that the culture surrounding guns in each state may play a role in preventing mass shootings.

### What percentage of gun violence is related to mass shootings?

Although mass shootings are the most talked about and broadcasted, they are just a tiny percentage of the total gun violence in states. Mass shooting incidents made up less than two percent of all gun violence incidents in 44 states, Illinois experienced the highest percentage at 2.23 percent.

<img width="272" alt="image" src="https://github.com/leah-apking/project1-mass-shootings/assets/119013360/96ad1b30-c857-431f-80ac-2f2825de18b4">
 
States with higher gun violence did have more mass shootings than states with less gun violence.

More restrictive gun laws and positive actions to strengthen communities and available resources can help save lives and prevent all gun violence including mass shootings.


