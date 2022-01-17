# Matplotlib Data Visualization on Tumor Analysis 
matplotlib plots

In this project several drug regiments were utilized on a time study of tumor volume size in relation with the treatment drug. To begin we needed to clean and drop duplicate data. There appears to be an entry for the same mouse, however we do not know which is the correct mouse data so we use drop_duplicates to eliminate the mouse all together from the data set. 

Further analysis of the data we can infer that Capomulin and Ramicane are a more effective treatment than Infubinol and Cerftamin by examining the box plot of 'Final Tumor Volume by Drug'

Another interesting find in this data visulization is the correlation between mouse weight and average tumor volume. The heavier the mouse, the larger the volume of the tumor is likely to be. As the treatment progresses for the mouse, and if it responds positively in a reduction of tumor volume, we would expect the weight of the mouse to decrease as well.

Visually inspecting the box plot for regiments of interest we can see there is one significant outlier, this would lead me to conclude our data is reliable for analysis
