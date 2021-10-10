# Course - Visualizations and Communication

##### NOTE: 
1. Your code MUST execute without any errors. 
2. You can add more lines in your code as required.

## Section 1: rCharts

### Question 1 
**The dataset is loaded for you. Perform the following tasks:**  
Using rCharts, visualize the dataset for HairEyeColor as an interactive bar chart. Use hair color on the x-axis and bars must correspond to the eye color. 
1. The data visualized must be for Female.  
2. The graph must have option to switch between stacked and group bar-charts.  


Hint: use nPlot


```R
require(devtools)
install_github('rCharts', 'ramnathv')
library("rCharts")
library(datasets)
```


```R
HairEyeColor
```


    , , Sex = Male
    
           Eye
    Hair    Brown Blue Hazel Green
      Black    32   11    10     3
      Brown    53   50    25    15
      Red      10   10     7     7
      Blond     3   30     5     8
    
    , , Sex = Female
    
           Eye
    Hair    Brown Blue Hazel Green
      Black    36    9     5     2
      Brown    66   34    29    14
      Red      16    7     7     7
      Blond     4   64     5     8
    



```R

```


```R

```


```R

```

### Good Job! You are done with the section!

## Section 2: Leaflet

### Question 1 
**Perform the following tasks:**  
Using leaflet, create the map and drop a pin-point to your current location! Use google maps to find out the longitude and lattitude. In a pop-up write, "I am here!"


```R

```


```R

```


```R

```


```R

```

### Good Job! You are done with the section!

## Section 3: Plotly

### Question 1 
**The dataset is loaded for you. Perform the following tasks:**  
Using the diamonds dataset, plot box plots for each of the cuts.  
1. Put price in the y axis.  
2. Create two different sets of Boxplots. One with color mapped to the clarity variable and another with color mapped to color variable.  


```R
library(datasets)
library(plotly)

head(diamonds)
```


<table>
<thead><tr><th scope=col>carat</th><th scope=col>cut</th><th scope=col>color</th><th scope=col>clarity</th><th scope=col>depth</th><th scope=col>table</th><th scope=col>price</th><th scope=col>x</th><th scope=col>y</th><th scope=col>z</th></tr></thead>
<tbody>
	<tr><td>0.23     </td><td>Ideal    </td><td>E        </td><td>SI2      </td><td>61.5     </td><td>55       </td><td>326      </td><td>3.95     </td><td>3.98     </td><td>2.43     </td></tr>
	<tr><td>0.21     </td><td>Premium  </td><td>E        </td><td>SI1      </td><td>59.8     </td><td>61       </td><td>326      </td><td>3.89     </td><td>3.84     </td><td>2.31     </td></tr>
	<tr><td>0.23     </td><td>Good     </td><td>E        </td><td>VS1      </td><td>56.9     </td><td>65       </td><td>327      </td><td>4.05     </td><td>4.07     </td><td>2.31     </td></tr>
	<tr><td>0.29     </td><td>Premium  </td><td>I        </td><td>VS2      </td><td>62.4     </td><td>58       </td><td>334      </td><td>4.20     </td><td>4.23     </td><td>2.63     </td></tr>
	<tr><td>0.31     </td><td>Good     </td><td>J        </td><td>SI2      </td><td>63.3     </td><td>58       </td><td>335      </td><td>4.34     </td><td>4.35     </td><td>2.75     </td></tr>
	<tr><td>0.24     </td><td>Very Good</td><td>J        </td><td>VVS2     </td><td>62.8     </td><td>57       </td><td>336      </td><td>3.94     </td><td>3.96     </td><td>2.48     </td></tr>
</tbody>
</table>




```R

```


```R

```


```R

```

## Good Job! You are done with the course!
