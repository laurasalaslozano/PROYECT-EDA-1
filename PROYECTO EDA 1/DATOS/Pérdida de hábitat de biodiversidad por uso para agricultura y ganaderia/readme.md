# Number of animal species losing habitat due to cropland expansion by 2050 - Data package

This data package contains the data that powers the chart ["Number of animal species losing habitat due to cropland expansion by 2050"](https://ourworldindata.org/grapher/projected-habitat-loss-extent-bau?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website.

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The remaining columns are the data columns, each of which is a time series. If the CSV data is downloaded using the "full data" option, then each column corresponds to one time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data columns are transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

### How we process data at Our World In Data
All data and visualizations on Our World in Data rely on data sourced from one or several original data providers. Preparing this original data involves several processing steps. Depending on the data, this can include standardizing country names and world region definitions, converting units, calculating derived indicators such as per capita measures, as well as adding or adapting metadata such as the name or the description given to an indicator.
[Read about our data pipeline](https://docs.owid.io/projects/etl/)

## Detailed information about each time series


## Losing more than 25%
Last updated: January 1, 2021  
Date range: 2050–2050  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Williams, Clark, Buchanan, Ficetola, Rondinini, & Tilman (2021). Proactive conservation to prevent habitat losses to agricultural expansion. Nature Sustainability. – processed by Our World in Data

#### Full citation
Williams, Clark, Buchanan, Ficetola, Rondinini, & Tilman (2021). Proactive conservation to prevent habitat losses to agricultural expansion. Nature Sustainability. – processed by Our World in Data. “Losing more than 25%” [dataset]. Williams, Clark, Buchanan, Ficetola, Rondinini, & Tilman (2021). Proactive conservation to prevent habitat losses to agricultural expansion. Nature Sustainability. [original data].
Source: Williams, Clark, Buchanan, Ficetola, Rondinini, & Tilman (2021). Proactive conservation to prevent habitat losses to agricultural expansion. Nature Sustainability. – processed by Our World In Data

### Additional information about this data
Projected species' habitat loss is projected to 2050 under a business-as-usual, plus five intervention scenarios with changes to diets or agricultural production.

Business-as-usual: This assumes population growth from UN medium projections; crop yield increases in line with historical rates of improvement; and dietary changes in line with projected rises in income.

Closing yield gaps: Yields increase linearly from current yields to 80% of the estimated maximum potential by 2050. Increasing yields above 80% is rarely achieved over large areas.

Halve food waste: consumer food waste and food losses in supply chains are reduced by 25% by 2030 and 50% by 2050.

Healthier diets: Diets transition to the EAT-Lancet diet which is in line with healthy calorie and nutritional requirements. For richer countries this would mean a reduction (but not elimination) of meat consumption. For poorer countries, this would mean an increase.

Optimize trade: agricultural production and trade is optimized to produce food in the locations with the least risk of habitat loss. Agricultural production shifts from the 25 countries projected to have the greatest mean losses of suitable habitat across all species to countries where less than 10% of species are threatened with extinction.

Combined: all four interventions are combined.


## Losing more than 50%
Last updated: January 1, 2021  
Date range: 2050–2050  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Williams, Clark, Buchanan, Ficetola, Rondinini, & Tilman (2021). Proactive conservation to prevent habitat losses to agricultural expansion. Nature Sustainability. – processed by Our World in Data

#### Full citation
Williams, Clark, Buchanan, Ficetola, Rondinini, & Tilman (2021). Proactive conservation to prevent habitat losses to agricultural expansion. Nature Sustainability. – processed by Our World in Data. “Losing more than 50%” [dataset]. Williams, Clark, Buchanan, Ficetola, Rondinini, & Tilman (2021). Proactive conservation to prevent habitat losses to agricultural expansion. Nature Sustainability. [original data].
Source: Williams, Clark, Buchanan, Ficetola, Rondinini, & Tilman (2021). Proactive conservation to prevent habitat losses to agricultural expansion. Nature Sustainability. – processed by Our World In Data

### Additional information about this data
Projected species' habitat loss is projected to 2050 under a business-as-usual, plus five intervention scenarios with changes to diets or agricultural production.

Business-as-usual: This assumes population growth from UN medium projections; crop yield increases in line with historical rates of improvement; and dietary changes in line with projected rises in income.

Closing yield gaps: Yields increase linearly from current yields to 80% of the estimated maximum potential by 2050. Increasing yields above 80% is rarely achieved over large areas.

Halve food waste: consumer food waste and food losses in supply chains are reduced by 25% by 2030 and 50% by 2050.

Healthier diets: Diets transition to the EAT-Lancet diet which is in line with healthy calorie and nutritional requirements. For richer countries this would mean a reduction (but not elimination) of meat consumption. For poorer countries, this would mean an increase.

Optimize trade: agricultural production and trade is optimized to produce food in the locations with the least risk of habitat loss. Agricultural production shifts from the 25 countries projected to have the greatest mean losses of suitable habitat across all species to countries where less than 10% of species are threatened with extinction.

Combined: all four interventions are combined.


## Losing more than 90%
Last updated: January 1, 2021  
Date range: 2050–2050  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Williams, Clark, Buchanan, Ficetola, Rondinini, & Tilman (2021). Proactive conservation to prevent habitat losses to agricultural expansion. Nature Sustainability. – processed by Our World in Data

#### Full citation
Williams, Clark, Buchanan, Ficetola, Rondinini, & Tilman (2021). Proactive conservation to prevent habitat losses to agricultural expansion. Nature Sustainability. – processed by Our World in Data. “Losing more than 90%” [dataset]. Williams, Clark, Buchanan, Ficetola, Rondinini, & Tilman (2021). Proactive conservation to prevent habitat losses to agricultural expansion. Nature Sustainability. [original data].
Source: Williams, Clark, Buchanan, Ficetola, Rondinini, & Tilman (2021). Proactive conservation to prevent habitat losses to agricultural expansion. Nature Sustainability. – processed by Our World In Data

### Additional information about this data
Projected species' habitat loss is projected to 2050 under a business-as-usual, plus five intervention scenarios with changes to diets or agricultural production.

Business-as-usual: This assumes population growth from UN medium projections; crop yield increases in line with historical rates of improvement; and dietary changes in line with projected rises in income.

Closing yield gaps: Yields increase linearly from current yields to 80% of the estimated maximum potential by 2050. Increasing yields above 80% is rarely achieved over large areas.

Halve food waste: consumer food waste and food losses in supply chains are reduced by 25% by 2030 and 50% by 2050.

Healthier diets: Diets transition to the EAT-Lancet diet which is in line with healthy calorie and nutritional requirements. For richer countries this would mean a reduction (but not elimination) of meat consumption. For poorer countries, this would mean an increase.

Optimize trade: agricultural production and trade is optimized to produce food in the locations with the least risk of habitat loss. Agricultural production shifts from the 25 countries projected to have the greatest mean losses of suitable habitat across all species to countries where less than 10% of species are threatened with extinction.

Combined: all four interventions are combined.


## Losing more than 75%
Last updated: January 1, 2021  
Date range: 2050–2050  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Williams, Clark, Buchanan, Ficetola, Rondinini, & Tilman (2021). Proactive conservation to prevent habitat losses to agricultural expansion. Nature Sustainability. – processed by Our World in Data

#### Full citation
Williams, Clark, Buchanan, Ficetola, Rondinini, & Tilman (2021). Proactive conservation to prevent habitat losses to agricultural expansion. Nature Sustainability. – processed by Our World in Data. “Losing more than 75%” [dataset]. Williams, Clark, Buchanan, Ficetola, Rondinini, & Tilman (2021). Proactive conservation to prevent habitat losses to agricultural expansion. Nature Sustainability. [original data].
Source: Williams, Clark, Buchanan, Ficetola, Rondinini, & Tilman (2021). Proactive conservation to prevent habitat losses to agricultural expansion. Nature Sustainability. – processed by Our World In Data

### Additional information about this data
Projected species' habitat loss is projected to 2050 under a business-as-usual, plus five intervention scenarios with changes to diets or agricultural production.

Business-as-usual: This assumes population growth from UN medium projections; crop yield increases in line with historical rates of improvement; and dietary changes in line with projected rises in income.

Closing yield gaps: Yields increase linearly from current yields to 80% of the estimated maximum potential by 2050. Increasing yields above 80% is rarely achieved over large areas.

Halve food waste: consumer food waste and food losses in supply chains are reduced by 25% by 2030 and 50% by 2050.

Healthier diets: Diets transition to the EAT-Lancet diet which is in line with healthy calorie and nutritional requirements. For richer countries this would mean a reduction (but not elimination) of meat consumption. For poorer countries, this would mean an increase.

Optimize trade: agricultural production and trade is optimized to produce food in the locations with the least risk of habitat loss. Agricultural production shifts from the 25 countries projected to have the greatest mean losses of suitable habitat across all species to countries where less than 10% of species are threatened with extinction.

Combined: all four interventions are combined.


    