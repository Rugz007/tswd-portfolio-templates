| [home page](https://rugz007.github.io/tswd-portfolio-templates/)

# Makeover Monday Redesign - US Weapon exports

## Step one: the visualization

I chose to critique the following data visualization: 



![Source](https://www.bloomberg.com/graphics/2023-us-made-gun-exports-shootings-violence-sig-sauer/)

The data visualization shows the US semiautomatic firearm exports from 2005-2022 to various countries using a radial graph. The radial graph seems to give the idea of how US exports have led to violence in different parts of the world.

## Step two: the critique
The graph has both strengths and weaknesses in its design. The use of red effectively conveys a sense of urgency, while the varying thickness of lines cleverly represents the volume of gun exports to each country. A notable positive element is the inclusion of the total number of gun exports from the US.
However, the graph's readability could be improved. It's not immediately clear that the length of each bar indicates distance from the US, which took some time to decipher. 

The varying thickness of the lines which indicate the volume of gun exports make it difficult to compare the number of weapons exported to different countries.

The crowded layout makes it challenging to grasp the main message at first glance. Additionally, the lack of proportionality in the graph's elements may confuse readers.
Overall, while the graph presents important information, its complex design requires careful study to fully understand its content.

## Step three: Sketch a solution

### First graph: Bar chart
- My initial thoughts led to me to draw out a bar chat. The bar chart would show the total number of weapons exported to each country. The reason I chose a bar chart because it is simple to to read and understand, allowing readers to quickly grasp the main message. 
- To ensure the countries are easier to compare, I chose a bar chart is because it is easier to compare the number of weapons exported to different countries. 
- I chose to use the color red to maintain the sense of urgency conveyed in the original visualization.
- I chose to included the top 20 countries which are the largest importers of US weapons to ensure the graph is not too crowded.
- The x-axis is sorted in descending order to show the countries with the highest number of weapons imported first. I had considered to sort them by distance from the US but decided against it as it would not be as intuitive as sorting by the number of weapons imported.

Here is the sketch of the solution:

### Second graph: Map
Based on the initial feedback I got, I found out that having another type of graph to show the geographical context of the data would be helpful.
- I chose to make a map to show the countries which are the largest importers of US weapons. This will give a geographical context to the data and show that US is affecting the countries far and wide.
- I used the color red to maintain the sense of urgency conveyed in the original visualization.
- I chose to label the countries with more than 10K weapons imported to ensure the map is not too crowded.
- I chose to use the light map to ensure the countries are easily visible.

This does not have a sketch and was directly implemented in the final solution.



## Step four: Test the solution

Questions to ask (modify these for your own interviews): 

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

- How does this compare to the original visualization?

- Do you prefer the bar chart, the map or the radial graph?

### Results: 

| Question | Data Engineer, 27 | Housewife, 58 |
|----------|-------------|-------------|
| Can you tell me what you think this is? | This looks like a chart showing the number of weapons exported by the US to different countries. | It appears to be a visualization of US weapon exports to various nations. |
| Can you describe to me what this is telling you? | It shows which countries are the largest importers of US weapons. | It indicates the volume of weapon exports from the US to different countries. |
| Is there anything you find surprising or confusing? | The fact that thailand is the biggest importer of US weapons is surprising. | The layout is clear, but the sheer number of exports is surprising. |
| Who do you think is the intended audience for this? | Policy makers and researchers interested in arms trade. | People studying international relations or organizations like united nations. |
| Is there anything you would change or do differently? | Being surprised about the fact that a country so far away from Thailand imports so much, I would have liked to see some geographical context in this graph to show that US is affecting the countries far and wide. | Including a timeline might help show trends over time. |
| How does this compare to the original visualization? | It's easier to understand than the radial graph. | This bar chart is more straightforward and less cluttered. |
| Do you prefer the bar chart, the map or the radial graph? | It depends on the context the data is being talked about, but I would have liked to see more of the bar and map because they are more clear. | I prefer the bar chart. |


### Synthesis: 

The feedback suggests that the bar chart is easier to understand than the radial graph. The interviewees found the bar chart more straightforward and less cluttered. The feedback overall for the barchart was good. 
I tried to sort the bar graph by distance from the US but the interviewees found it more intuitive to sort by the number of weapons imported as I had hypothesized during the sketching phase.
They also suggested including geographical context and hence I also made a map to show the countries which are the largest importers of US weapons. These two graphs can be used based on the context of the data being talked about.

Another feedback was that the total count of weapons was not included in the bar chart. I decided to include the total count of weapons exported in the subtitle of the bar chart and the map to ensure the reader knows the total number of weapons exported.
## Step five: build the solution

Here is the final solution:

Bar chart:


The bar chart should be used when comparision between the countries is needed. But it cannot communicate how far the countries are from the US.

Map:

The map should be used when geographical context is needed. The map is not good at helping the reader know exactly how much is the difference between the countries.
