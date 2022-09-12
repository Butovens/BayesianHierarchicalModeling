# Multilevel Bayesian analysis

This data set comes from a neuroscience singing experiment. The experiment was to determine which (selected) brain region contributed to one's ability to sing accurately.

The task from the **SSAP_Vocal_Imitation.csv** data set had participants sing back a single vocal target pitch in 10 trials. This task included 5 different pitches presented twice in a randomized fashion. 

The task from the **SSAP_Piano_Imitation.csv** data set had participants had sing back a single piano tone target pitch in 10 trials. This task also included 5 different pitches presented twice in a randomized fashion. 


Those singing tasks gave a score for each pitch sung. These scores are signed pitch-deviation scores that are computed by subtracting the value of the sung pitch from the value of the imitated target pitch  (i.e. score = sung pitch – target pitch). The closer to zero the value is, the more accurate the pitch sung is (relative to the target pitch). The unit of the score is CENT which is a logarithmic unit of measure used for musical interval. It measures the ratio between two frequencies.

The design of this experiment was a pretest-posttest within subject design with four different conditions (i.e. sham/placebo brain simulation, visual cortex brain simulation , left cerebellum brain simulation , right cerebellum brain simulation). Participants did the singing tasks once before brain stimulation and once after brain stimulation.

The variables are:

* **Imitation 3**: Participant ID
* **PRE_S**: Sham pretest stimulation condition
* **POST_S**: Sham posttest stimulation condition
* **PRE_RC**: Right Cerebellum pretest stimulation condition
* **POST_RC**: Right Cerebellum posttest stimulation condition
* **PRE_V**: Visual cortex pretest stimulation condition
* **POST_V**: Visual cortex posttest stimulation condition
* **PRE_LC**: Left Cerebellum pretest stimulation condition
* **POST_LC**: Left Cerebellum posttest stimulation condition
* **Interval**: Musical interval to be sung relative to participants' comfort pitch

The **Equation.Rmd** file contains the final model's equation in Latex format. 

