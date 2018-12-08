# Ad-Click-Prediction
Given some information about the user, webpage and ads, determine which ad is more likely to be clicked by the user on the given webpage and improve the user experience.
 
1	Naive Bayes ->	Campaign_id, Advertisor_id, Platform_id =>	0.77(Training Accuracy)

2	Random Forest - 1	->Campaign_id, Advertisor_id =>	0.54

3	Random Forest - 2->	topic_id, source_id, publisher_id, category_id =>	0.48

4	SGD	-> Campaign_id, Advertisor_id, Platform_id	=> 0.64
