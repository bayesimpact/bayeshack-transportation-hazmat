# Bayes Hack 2016
### Department of Transportation Prompt #1

_How can data stop accidents before they happen?_

## Prompt

The Federal Highway Administration (FHWA) has developed a Freight Analysis Framework that shows historical freight movement estimates.No organization has ever used government permit data or related indicators to develp models that can project future increases in freight traffic.

By creating models from empirical data, we can reduce casualties due to crashes and other safety incidents among all transportation users and minimize risks due to the transportation of hazardous materials. MOdels could predict which areas are likely to see increased transportation of oil and liquid natural gas leverage existing liquid natural gas (LNG) and oil development models to predict future transportation safety risks or anticipate development and transportation of oil and natural gas in a way that hasn't yet been explored.

## In this Repo

* `data/` - Cleaned and prepared data sources. NOTE - Not all data exists here -- see Resources section below.
* `analysis/` - iPyton notebook files (which you can view right here on GitHub) loading the data and exploring a few things. Good to understand the datasets and get ideas for your project.

## Data

`data/hazmat_incidents.csv`
* This is a full dataset pull from The Office of Hazardous Materials Safety's [Incident Reports Database](https://hazmatonline.phmsa.dot.gov/IncidentReportsSearch/IncrSearch.aspx)

`data/freight_data.csv`
* This is the full dataset from the [Freight Analysis Framework](http://www.ops.fhwa.dot.gov/freight/freight_analysis/faf/) of the Federal Highway Administration. It details the mass flow of cargo within the US.</li>
* To understand it, read the [User Guide](http://www.ops.fhwa.dot.gov/freight/freight_analysis/faf/faf3/userguide/index.htm)

<p>More data sources:</p>
<ul>
    <li><a href="http://www.eia.gov/opendata/index.cfm">Energy Information Administration (EIA) open data</a></li>
    <li><a href="http://energy.gov/fe/downloads/electronic-docket-room-e-docket-room">Department of Energy data</a> on the registration of import/export permits for LNG at the Office of Fossil Energy</li>
    <li><a href="http://www.ferc.gov/industries/gas/indus-act/lng.asp">Federal Energy Regulatory Commission (FERC) data</a> on LNG terminals and other facilities</li>
    <li><a href="http://www.blm.gov/wo/st/en/prog/energy/oil_and_gas/statistics.html">Data on public lands where energy development has been authorized</a> from the Bureau of Land Management (BLM)</li>
</ul>
