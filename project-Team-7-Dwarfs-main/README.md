# STA 210 final project

This repo will contain all of your project work. Folders and files for relevant pieces of the project will be added as they're assigned in class.

:link: [Instructions](https://sta210-fa22.netlify.app/project-instructions.html)

:link: [Tips + resources](https://sta210-fa22.netlify.app/project-tips.html)

# Project description

Our group is extremely interested in politics, especially with the primary elections that are coming up right around the corner. We want to investigate why people voted the specific ways they did, focusing on their policy beliefs and non-political identities. One may assume that people vote based on a combination of policy positions and social identities. However, as Jenke and Huettel assert in their article, "Issues or Identity? Cognitive Foundations of Voter Choice," identity and policy positions actually compete to determine voter preference. We either vote based on our identity or policy positions, not both. If we follow their model of voter choice based on cognitive science, the increasing political polarization could be attributed to more people voting based on identity.

Can a statistical analysis of voter data could lead to additional insight into how important policy stances are in voter choice in comparison to identity-based metrics? We hypothesize that identity-based predictors, like whether or not a subject lives in a rural area, maybe better predictors of who someone voted for than policy-based predictors, like if a subject favors or opposes background checks for gun purchases.

# Data

| Variable  | Description               |
|:----------|:--------------------------|
| `president_vote` | The question for this variable was “Who do you think you will vote for?” The options are 1 for Joe Biden and 2 for Donald Trump. This will be the response variable. |
| `abortion` | The question is “There has been some discussion about abortion during recent years. Which one of the opinions on this page best agrees with your view?” Options are 1 for “By law, abortion should never be permitted”, 2 for “The law should permit abortion only in case of rape, incest, or when the woman’s life is in danger”, 3 for “The law should permit abortion other than for rape/incest/danger to woman but only after need clearly established”, 4 for “By law, a woman should always be able to obtain an abortion as a matter of personal choice”, and 0 for other. |
| `gun_backgroundchecks` | The question is “Do you favor, oppose, or neither favor nor oppose requiring background checks for gun purchases at gun shows or other private sales?” Options are 1 for “Favor”, 2 for “Oppose”, 3 for “Neither favor nor oppose”, and 0 for other. |
| `fedbudget` | The question is “Should federal spending on tightening border security to prevent illegal immigration be increased, decreased, or kept the same?” Options are 1 for “Increased”, 2 for “Decreased”, 3 for “Kept the same”, and 0 for other. |
| `rural_urban` | This question asks “Do you currently live in a rural area, small town, suburb, or a city?” Options are 1 for rural area, 2 for small town, 3 for suburb, 4 for city, and 0 for other. |
| `race` | The respondent’s self-identified race or ethnicity. Options are 1 for “White, non-Hispanic”, 2 for “Black, non-Hispanic”, 3 for “Hispanic”, 4 for “Asian or Native Hawaiian/other Pacific Islander, non-Hispanic alone”, 5 for “Native American/Alaska Native or other race, non-Hispanic alone”, 6 for “Multiple races, non-Hispanic”, and 0 for other. |
| `age` | The respondent’s self-identified age. This is a numeric variable with the participant’s stated age, except for -9 for "Refused to answer"" and 80 for age 80 or older. |
|`political_align` | The political alignment of the respondent, ranked on a scale from 1 to 7. This will be the response variable. Options are 1 for “Extremely liberal”, 2 for “Liberal”, 3 for “Slightly liberal”, 4 for “Moderate; middle of the road”, 5 for “Slightly conservative” 6 for “Conservative”, 7 for “Extremely conservative”, and 99 for other response. |

