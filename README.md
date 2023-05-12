# Factors for Pet Dog Aggression towards Humans

The increasing popularity of dog ownership in tandem with emerging conflicts poses a noteworthy concern in contemporary society. For instance, within our group, one member is a dog owner while another exhibits an intense fear of dogs. The fear of dog bites predominantly drives individuals' apprehension towards dogs, thus sparking our interest in exploring the factors influencing canine aggression towards humans. This study aims to delve into the multifaceted aspects surrounding this issue and shed light on the underlying factors contributing to dog bites.
 
Driving by the interest, we found a dataset namned [DOHMH Dog Bite Data](https://data.cityofnewyork.us/Health/DOHMH-Dog-Bite-Data)
which contents dog bite incidents from 2015 to 2021. The data is collected from reports received online, mail, fax or by phone to 311 or NYC DOHMH Animal Bite Unit. The information of date and loccation of the incident, dog breeds, gender, age, and neutering status are included in this dataset.

## The unneutered male pit bull tends to exhibit a higher incidence of dog-inflicted injuries on humans.

In our study, we aimed to investigate whether certain dog breeds exhibit higher aggression towards humans. We analyzed the DOHMH Dog Bite Data to examine the frequency of bite incidents categorized by breed. Interestingly, upon excluding dogs of uncertain breed types, we observed that approximately half of the reported bite incidents were attributed to pit bulls.

<iframe src="fig/breed_pie_chart.html"
    sandbox="allow-same-origin allow-scripts"
    width="800"
    height="500"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

In our investigation, we sought to examine the potential relationship between dog bite behavior and the age of dogs. We created a line graph based on the age data and observed a clear trend. Specifically, as the age of dogs surpasses 2 years, there is a gradual decrease in the occurrence of dog bites.

<iframe src="fig/figure3.png"
    sandbox="allow-same-origin allow-scripts"
    width="800"
    height="500"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

In our study, we aimed to explore the potential influence of gender and neutering status on dog bite behavior.
The interactive pie chart indicated that unneutered males exhibited a significantly higher level of aggressiveness.

<iframe src="fig/gender.html"
    sandbox="allow-same-origin allow-scripts"
    width="800"
    height="500"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

All the evidence suggests that unneutered male pit bulls pose a significant risk and should be approached with caution. However, it is important to acknowledge that the conclusions drawn from the data, which solely includes information on dog bite incidents involving humans, may not provide a comprehensive and convincing representation.

## Incorporated the NYC Dog Licensing Dataset to delve deeper 

To delve deeper into the matter, it should be noted that the previous data from the DOHMH Dog Bite Dataset only reflects incidents involving dogs that have already bitten humans. 
Therefore, a conclusive analysis cannot be made without considering the distribution ratios of specific factors among the entire population of pet dogs in New York City.
To address this, we have incorporated the [NYC Dog Licensing Dataset](https://data.cityofnewyork.us/Health/NYC-Dog-Licensing-Dataset/nu7n-tubp) to examine the distribution of these factors that influence dog aggression within the broader population of pet dogs.

By combining two datasets, the ratio of bites incidents according to the breed clearly showed
pit bull and rottweiler have much more possiblities to bite human.

<iframe src="fig/ratio_breed.html"
    sandbox="allow-same-origin allow-scripts"
    width="800"
    height="500"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>