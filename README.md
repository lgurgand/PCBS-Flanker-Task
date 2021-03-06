# PCBS : Flanker Task

## The Flanker Task

The Flanker Task is a task that measures cognitive control (which is the ability to ignore irrelevant thoughts or stimuli in order to do a task correctly), that was first published by Eriksen and Eriksen in 1974. The goal of the study is to understand the effect of noise on the identification of a target.

In the Flanker task, the subjects sees a line of arrows pointing to the left or to the right, and has to press a button indicating the direction of the middle arrow. The middle arrow is flanked by other arrows which point in the same or opposite direction as the middle arrow.
The task is easier if the central arrow points in the same direction as the other ones (congruent condition <<<<<<), more difficult otherwise because we have to make an effort to ignore the flanking arrows (incongruent condition <<<><<<).
Subjects are often slower and less accurate in the incongruent condition.

## Running the code 

Please download the main experiment PCBS_FlankerTask.py, and the images (left_congruent.png, left_incongruent.png, right_congruent.png, right_incongruent.png) and run the code on Python. This will create an xpd file listing the subject ID, the kind of stimulus (which image was presented), the response key and the reaction time.
Be careful when running the code, make sure that your working directory is where the pictures are.

## Results

You can find a report of the analysis of the results (https://github.com/lgurgand/PCBS-Flanker-Task/blob/a867806e6ce80580d3b727652c902f746fb92606/PCBS_Flanker_task_ANALYSIS.pdf). The analysis were done using the software R. The experiment was done on 6 subjects, and 5 out of the 6 did show a significantely higher reaction time in the incongruent trials than in the congruent trials, as expected. 

This means that it requires more time to respond when you have to have some cognitive control involved and have to ignore the irrelevant informations (the arrows pointing in opposite directions as the target arrow).

![Graph of the results](https://github.com/lgurgand/PCBS-Flanker-Task/blob/main/PCBS_results_R.png)

## Previous coding experience, PCBS experience

I have mostly used R in the past and I had never used Python (or R) to run experiments, only to analyze data. Thanks to this course, I have learned how to create experiments which can be very useful when working in cognitive science. I feel like this course was very complete but it was also a lot of work, 3 hours per week is a lot for so few ECTS. 
