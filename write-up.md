## First Version

[https://public.tableau.com/views/Udacity-BaseballData/5?:embed=y&:display_count=yes&publish=yes](https://public.tableau.com/views/Udacity-BaseballData/5?:embed=y&:display_count=yes&publish=yes)

## Final Version

[https://public.tableau.com/views/Udacity-BaseballData/1_1?:embed=y&:display_count=yes](https://public.tableau.com/views/Udacity-BaseballData/1_1?:embed=y&:display_count=yes) 

## Summary

The batter's body condition seems to have related to the batting average and the number of home runs. The batter's height and weight with over 300 home runs is generally higher than the batter's height and weight with a batting average of over 0.3. When we look at the weight-to-height ratio, we can see that the best home run hitter groups have 3.0 and good contact batters have 2.1.

## Design

### Sheet 1

A scatter plot is chosen to visualize the relation between hitting average and home run count. The color and filter on handedness were used to show any dependence of data on handedness. To prevent the confusion caused by the scale changes, to the scale of the axis is fixed.


### Sheet 2, 4

Scatter plots are used to show the distribution of batters on weight and height. To concentrate on the qualified batters the size of the point encoded to show home run count or hitting average. Also, to investigate any difference depending on the handedness, the handedness is encoded in color. To prevent the confusion caused by the scale changes, to the scale of the axis is fixed.

### Sheet 5

A histogram was chosen to show the distribution of heating average and home run count depending on weight-height ratio. The double axis is chosen to show the two values in one graph. To prevent the confusion caused by the scale changes, to the scale of the axis is fixed.

### Sheet 11

A harmonic average of HR and avg is shown using histograms. Besides high HR and avg range of weight-height ratio, I want to know the range of weight-height ratio for balanced ability between HR and avg. There are two new ranges of well-balanced ability, around 2.7 and 2.8. To show the distribution of HR and avg, each feature is shown using color.

## Feedback

### Review 1

She does not like the color used in the plots. The taste of the color palette is different from person to person. So, I did not change the color palette. Also, to help her understanding, I changed to abbreviated plot title and axis labels, to full feature names.

### Review 2

He asked whether I can extract other feature related to the batter. For example, slugging average, RBI. Though it is impossible to get those feature from data, I added a harmonic average of normalized avg and HR to show the balanced ability between contact ability and batting power. 
