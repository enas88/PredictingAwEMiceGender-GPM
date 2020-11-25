# PredictingAwEMiceGender-GPM


In order to analyse the recent test held for the AwE mice,
Combining the old mice (24, 25 months) with the young mice tests (3 months).
The main idea here is to focus on the Controlled diet treatment (C), in order to figure out the female and male behaviour.
 
As a baseline Alessandra suggested to find the analysis for the main differences between the physical and mental tests, the second step is to find the power difference between the males and females, as she mentioned Berry et al. (2019), that even for some of the female mice which are suffering from a bad body shape they could pass the big pole test, even better than well-shaped males. 
 
According to Berry et al. (2019) which shows the tests and treatments held for mice in the intellicages as statistical analysis, in my turn now, I need to set the best algorithm for analyzing those measurements. 
 
My goal is to learn the machine to get the best out of those reports.


Gender as a target

The first assumption will be is by building a model that test the differences between males and females according to their mental and physical abilities. We have 128 male and 145 female:

I started the test, first by making the mice gender as a target, I did 5 different experiments by using different Features-Engineering algorithms: 
First: Taking the features (39) feature for the test measurements and one for the treatment (C, Trehalose, Ampel, RA_D1, RA_D2, RA_RA_D1, RA_RA_D2).



Features as they are 
As feature_distribution plot function used here to show the significant relationships, as I’ve chosen the highest rank (most important features), where Random Forest algorithm used to show the most important features which affect the prediction model, defining the Gender as the class label:
The strongest relationship between:
MWM (target time), and the Insulin Sensitivity test. (memory)
MWM (LatencyDay2) and the Insulin Sensitivity test.\\ different major (learning), 
//Elevated plus maze (Sniffing_D) and elevated plus maze (wall rearing_F). (exploration)
//BASAL grip strength score (s) and the Treatment.
POST-BIGp_TTT and the Bodyweight.
Rotarod score 3 (s) and the Glucose tolerance test (AUC).

I’d like to show you the relationship between each attribute and its target (male-female):

Treatments (refer above) male:0 Female:1
