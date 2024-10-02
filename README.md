# Problem C Planting Strategies

## Problem Background
In a village located in the mountainous area of North China, the temperature is generally low, and most arable land can only support one season of crops each year. The village has a total arable land area of 1201 mu, divided into 34 different types of plots, including flat dry land, terraced fields, hillside land, and irrigated land. Additionally, the village has 16 ordinary greenhouses and 4 smart greenhouses, each with an area of 0.6 mu.

Different types of plots and greenhouses are suitable for planting different crops:
- **Flat dry land, terraced fields, hillside land**: Suitable for planting one season of grain crops.
- **Irrigated land**: Suitable for planting one season of rice or two seasons of vegetables.
- **Ordinary greenhouses**: Suitable for planting one season of vegetables and one season of edible fungi.
- **Smart greenhouses**: Suitable for planting two seasons of vegetables.

In the same plot, different crops can be mixed in each season, and continuous monoculture should be avoided. Additionally, to promote soil fertility, each plot must plant leguminous crops at least once every three years.

## Problem 1
Assuming that the expected sales volume, planting costs, yield per mu, and sales prices of crops remain stable relative to 2023, and the crops planted each season are sold in that season, provide the optimal planting plan for crops from 2024 to 2030 for the following two scenarios:

1. **Scenario 1**: Excess production above the expected sales volume leads to wastage.
2. **Scenario 2**: Excess production above the expected sales volume is sold at 50% of the 2023 sales price.

The results should be filled into `result1_1.xlsx` and `result1_2.xlsx` respectively (see attachment 3 for template files).

## Problem 2
Considering the following uncertainties, provide the optimal planting plan for 2024 to 2030 and fill in the results in `result2.xlsx` (see attachment 3 for template files):
- The annual growth rate of expected sales volume for wheat and corn is 5%-10%;
- The expected sales volume of other crops varies by ±5% each year;
- The annual yield per mu of crops fluctuates by ±10%;
- Planting costs increase by 5% each year;
- Grain crop prices remain stable;
- Vegetable prices increase by 5% each year;
- Edible fungi prices decrease by 1%-5% each year, especially the price of morels, which decreases by 5% each year.

## Problem 3
Based on Problem 2, comprehensively consider the substitutability and complementarity among crops, as well as the correlations between sales volume, sales prices, and planting costs, to provide the optimal planting strategy for 2024 to 2030 and perform a comparative analysis with the results from Problem 2.

## Attachments
- **Attachment 1**: Basic information on existing arable land and crops in the village
- **Attachment 2**: 2023 planting and related statistical data for village crops
- **Attachment 3**: Template files for submission results (`result1_1.xlsx`, `result1_2.xlsx`, `result2.xlsx`)
