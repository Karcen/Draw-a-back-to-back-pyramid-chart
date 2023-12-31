This code is for reference only

The appearance of the chart we want to draw is roughly like this: two groups of back-to-back charts sharing a y-axis and a legend.

If we directly use Python to draw, it's not possible to achieve the desired effect. Origin also doesn't provide a satisfactory solution. The strategy I adopted in Python is to draw two separate charts and then combine them back-to-back, manually adding the legend. The specific colors can be obtained using a color picker.

However, since the chart is artificially created, it is evident that the y-axis labels are not centered. We can export the chart as an .svg file and process it further in Adobe AI before exporting it as a .png file. The result is quite good.
![Figure](https://github.com/Karcen/Draw-a-back-to-back-pyramid-chart/assets/96618382/1a6cfab4-60ec-4d7b-8107-3153b137aa5b)
