
## Overview

This repository is a companion to the publication
[How COVID-19 is changing the world: a statistical perspective - Volume III][pub-v3]
published by the [Community for the Coordination of Statistical Activities][ccsa] (CCSA) in March, 2021.
The repository contains data files for some of the figures from the publication where contributing
organizations have chosen to make them available as open data. For details please refer to the
[publication][pub-v3] on the [CCSA website][ccsa] and the notes below.

## License ##

The data files in this repository are made available from their respective organizations
under a [Creative Commons Attribution 4.0 International License][cc-by].


## About the Data

Data files are located in the "data" subdirectory of this repository organized by CCSA member.
Unless otherwise indicated files are in [CSV format][csv] with a separate file for each figure.


### ILO ###

Data is current as of 2021-03-16. Latest data are available from ILO's
[COVID topic page](https://ilostat.ilo.org/topics/covid-19/). All ILO data
is updated weekly and can be found at <https://ilostat.ilo.org/data> and
<https://ilostat.ilo.org/data/bulk>.

### OECD ###

OECD data is provided in a [separate GitHub respository][oecd-repo] and
corresponds to the period between January and August 2020; see
[OECD's repository][oecd-repo] for more details on the
[data sources and the OECD Regional Typology][oecd-meta].
Both figures can be recreated from the data in the same file.

### UNSD/WBG ###

The World Bank and the United Nations Statistical Division (UNSD), in coordination with the
five UN Regional Commissions, are conducting a global online survey to assess the impact
of the coronavirus crisis on statistical offices, and to identify needs for financial and technical support.
This archive provides summary data shown in the report; survey data are available at
<https://covid-19-response.unstatshub.org/statistical-programmes/covid19-nso-survey>


### UNEP ###

Data was downloaded on 2021-01-20 from <https://carbonmonitor.org>; see website for latest
available data.

### UN Habitat ###

Data was downloaded on 2021-03-10 from the [COVID-19 tracker](https://unhabitat.citiiq.com) dashboard;
see dashboard for latest available data.

### World Bank ###

Data for computing poverty estimates come from [PovcalNet][povcal] and the latest growth forecasts
from [Global Economic Prospects][gep]. Metadata for the CSV files is provided in JSON format
following the [Frictionless Data Specification][frictionless].


[ccsa]:   https://unstats.un.org/unsd/ccsa/
[pub-v3]: https://unstats.un.org/unsd/ccsa/
[csv]:    http://opendatahandbook.org/guide/en/appendices/file-formats/#comma-separated-files
[cc-by]:  http://creativecommons.org/licenses/by/4.0/

[oecd-repo]: https://github.com/oecd-cfe-eds/ccsa-excess-mortality/
[oecd-meta]: https://github.com/oecd-cfe-eds/ccsa-excess-mortality/blob/master/metadata.md

[povcal]: http://iresearch.worldbank.org/PovcalNet/home.aspx
[gep]:    https://www.worldbank.org/en/publication/global-economic-prospects
[frictionless]: https://specs.frictionlessdata.io/
