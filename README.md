This code is for reference only

The desired appearance of the chart is as follows: two groups of back-to-back charts sharing a y-axis and a legend.

It may be not possible to achieve this desired effect directly using Python for drawing. Origin also does not provide a satisfactory solution. In Python, the approach I adopted was to draw two separate charts and then combine them back-to-back, manually adding the legend. Specific colors can be obtained using a color picker.

However, since the chart is manually created, it is evident that the y-axis labels are not centered. To address this, we can export the chart as an .svg file and further process it in Adobe AI before exporting it as a .png file. The resulting chart is of high quality.
![Figure](https://github.com/Karcen/Draw-a-back-to-back-pyramid-chart/assets/96618382/1a6cfab4-60ec-4d7b-8107-3153b137aa5b)
