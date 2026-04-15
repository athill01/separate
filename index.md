---
# Do not edit the text between these lines!
layout: default
---

# EX09 Website

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->

## Summary

I analyzed the survey data to decipher whether or not COMP110 should be split into separate section for majors and non-majors. This analysis was conducted based on the following: the distribution of hours spent working outside of class and the students' perceived difficulty of the course. I used Jupyter Notebooks, and the library seaborn, as well as other self-created functions to normalize the data and visualize it based on Major Status (BS, BA, Minor, or Non-CS)

## Visualization 1
<img src="static/imgs/stats.png" alt="Image of visualization 1" width="400">
<br>
This graph shows the percentage of students in each major category and how many hours they spent working online. Non-CS students skew toward the 5-10 and 10+ hour marks.

## Visualization 2
<img src="static/imgs/stats1.png" alt="Image of visualization 2" width="400">
<br>
This distribution plot shows the students' perceived difficulty. Non-CS majors have a light spike at the higher difficulty ratings compared to the CS tracks.

## Visualization 3
<img src="static/imgs/stats2.png" alt="Image of visualization 3" width="400">
<br>
Using a custom helper function, I calculated the average difficulty rating for every CS track and for non-CS majors. This shows that Non-CS and CS-BS students face the most difficulties, while BAs and Minors find the course noticeably easier.


## Part 1.5: Conclusion
<br>
The analysis prior weakly supports the recommendation to split up COMP110 into distinct sections for CS and non-CS majors. 

Hourly commitment:
Based on the table above, non-CS students spend more time on classwork on average. They have the greatest ratio of students who spend 5-10 hours on work, as well a large portion in 3-5 hours. Besides CS-BA students, they are the only students who spend 10+ hours a week on the class, which is significant due to the large sample size. Those on the CS track peak in 3-5 hours, but have solid representation in 0-2 hours.

Perceived Difficulty
Non-CS students reported the highest perceived difficulty, but CS-BS students reported the second highest, nearly the same as Non-CS. This could be attributed to the demanding curriculum for CS-BS students where they are allocating more hours to their other classes, especially since they appear to spend the least amount of time on the course. CS-Minors and CS-BAs reported significantly lower difficulties, about 3.5 and 3.8 respectively.

However this idea doesn't seem practical. The amount of non-CS majors significantly overwhelm the concentration of CS major/minor students. This also could have caused errors as the sample size for CS students was not great enough. More sampling could be done in the future to validate these findings.