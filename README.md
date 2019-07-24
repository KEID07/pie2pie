# R-Visuals [pie2pie] Support
| No. | Item | Description |  
| --- | --- | --- |
|  1 | Base Config | General settings for graphics formats, including labels, fonts, etc.
|  1.1 | Set Labels | Set the label content, including the label name, percentage and value, you can select "all" to display all the data, or select "none" to hide the label.
|  1.2 | Labels Position | Set the location of the label, the default is "auto".
|  1.3 | Fonts | Set visual fonts, including label fonts, legend fonts, etc.
|  1.4 | Border Width | Set the border line width, including the border of the pie chart, the connecting line, and the width of the legend border(if enabled).
|  1.5 | Theme | Setting the theme color of pie chart.
|  1.6 | Text Color | Set the visual text color, which applies to label text and legend text.
|  1.7 | Border Color | Sets the visual theme color that applies to the pie border, the legend border, and the connection line (if enabled)
|  1.8 | Merge Smaller Values | If this item is turned on, the parts of the main pie chart that are divided into sub-pie charts will be merged as "Others".
|  1.9 | Pull Others | Pull the "Others" fan from the main pie chart (make sure the "Merge Smaller Values" has been enabled).
|  1.10 | Show Lines | Display the connection lines between the main pie chart and the sub-pie chart, which requires ensuring that the visual aspect ratio is 1:1.
|  2 | Show Legend | Show the legend for this visual.
|  2.1 | Show Legend Border | Shows the outer border of the legend (hidden by default).
|  2.2 | Background Color | Set the background color of the legend area.
|  2.3 | Legend Text Size | Set the legend text size.
|  2.4 | Legend Position | Set the position of the legend, including "top" and "bottom".
|  3 | Shape Config | Change the visual shape setting of the visual, including the inner ring radius and the orientation of the sub-pie chart.
|  3.1 | Direction | Change the orientation of the sub-pie chart, select "reverse" to swap the position of the main pie chart and the sub-pie chart (sub-pie chart on the right by default).
|  3.2 | MainPie Ring Radius | Set the inner ring radius of the main pie chart (if you select "0.0", the chart will become a solid pie chart without inner ring).
|  3.3 | SubPie Ring Radius | Set the inner ring radius of the sub-pie chart (if you select "0.0", the chart will become a solid pie chart without inner ring).
|  4 | Gradient Mode | Turn on the gradient mode. You can set two colors, the color of the sector of pie chart will be transition between the color 1 and color 2 (as below) according to the proportion of different tag values (note that if "Merge Smaller Values" is turned on, the color of "Others" will not affected by their proportion).
|  4.1 | Color 1 | Setting the first color of the gradient mode. The larger the percentage of a sector, the closer the color to "Color 1".
|  4.2 | Color 2 | Setting the second color of the gradient mode. The smaller the percentage of a sector, the closer the color to "Color 2".
|  5 | Other Config | Additional features.
|  5.1 | Display Toolbar | Display the toolbar provided by Plotly.
