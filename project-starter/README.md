Comparing Earthworm Biomass and Invasive Species Density Across Soil Types
================
by Rachel Krick

## Presentation

My presentation can be found [here](presentation/presentation.html).

## Introduction & Research Questions

The data comes from a study that looked at how invasive plant species influence ecological properties. 
They also aimed to "highlight ways of improving the design and interpretation of observational studies that assess the impacts of invasive plants.
The data contains 12 observations and 51  variables. 

The  collection of this data combines two different methods of sampling:  

  * (1) large-scale stratified sampling of vegetation  across multiple sites where researchers recorded species composition, abundance, and environmental variables in areas with and without invasive plants
  * (2) finer-scale paired-plot studies, where invaded plots were directly matched with nearby uninvaded plots under similar conditions to better isolate invasion effects. 
  
My project looks at the impact of the invasive species (*Rhamnus cathartica* or buck thorn) on earth worm biomass. It also looks at how soil type
impacts earthworm biomass and the invasive species. 

The first variable I chose to work with was buckthorn_stems_per_m2_subplot which measures the number of buckthorn stems in each 3 m diameter subplot.
I chose this buckthorn variable in particular because it is a good measure of the actual density of buckthorn plants in each plot.
The second variable I chose to work with was earthworm_biomass_g_per_m2 which measures the biomass of earthworms in each subplot.
The final variable I chose was soil_type which is an indicator of the soil type in each plot (in this case either silty or sandy).

My analysis of the data answers the following questions:

  1. Is there a statistically significant relationship between the invasive species and the earth worm biomass? What does this mean for how the invasive species impacts earthworm biomass? 
  
  2. Does the mean earthworm biomass vary by soil type? Is there a statistically significant difference in the means? 
  
  3. Does the mean number of buckthorn stems vary by soil type? Is there a statistically significant difference in the means? 

**Overall:**  
 What does this mean for how soil type might play a role in the relationship between invasive species and earthworm biomass? 


## Methodology

In order to use the data, I first had to


## Results

There is a positive correlation between buckthorn stems and earth worm biomass. For every additional buckthorn stem present per m² in a subplot, the earthworm biomass increases by approximately 0.300 g/m².
The statistical analysis for earth worm biomass by soil type revealed that the mean earthworm biomass was higher in silty soil than in sandy soil (x̄₁ − x̄₂= 1.50571).
Moreover, because 0 is included in the interval (CI= -1.587664 to 4.599092), there is not strong evidence of a significant difference between the two soil types.
Finally, the test result was not statistically significant. Because the p-value is greater than 0.05 (p-value= 0.3005), we fail to reject the null hypothesis.
This indicates there is insufficient evidence to conclude that earthworm biomass differs significantly between silty and sandy soils.

The statistical analysis for buckthorn stem density by soil type revealed that the mean number of buckthorn stems was higher in silty soil than in sandy soil (ȳ₁ − ȳ₂ = 6.025714).
Moreover, because 0 is included in the interval (CI= -1.266736 to 13.318164), there is not strong evidence of a significant difference between the two soil types.
Finally, the test result was also not statistically significant. Because the p-value is greater than 0.05 (p-value= 0.08557), we fail to reject the null hypothesis.
This indicates there is insufficient evidence to conclude that buckthorn stem density differs significantly between the two soil types.

## Conclusion 

From my statistical analysis of the data I found that soil type alone may not be a strong predictor 
of the relationship between invasive buckthorn and earthworm biomass in this study. However, both variables 
were higher in silty soil. This may indicate that silty soils provide more favorable conditions for both earthworms 
and buckthorn growth. This could be due to the fact that silty soils might retain more moisture and nutrients than 
sandy soils. The results of the analysis could also be a result of the relatively small number of plots surveyed. 
Future work with this data might analyze relationships between earthworm biomass and buckthorn density
with various nutrients found in the different soils. 

## Data

Mueller, Kevin E.; Lodge, Alexandra G.; Roth, Alexander M. et al. (2018). Data from: A tale of two studies: 
  detection and attribution of the impacts of invasive plants in observational surveys [Dataset]. 
  Dryad. https://doi.org/10.5061/dryad.h3h1n

## References

Mueller, Kevin E.; Lodge, Alexandra G.; Roth, Alexander M. et al. (2018). Data from: A tale of two studies: 
  detection and attribution of the impacts of invasive plants in observational surveys [Dataset]. 
  Dryad. https://doi.org/10.5061/dryad.h3h1n

