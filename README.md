**DevLoc**

DevLoc provides an interactive visualization and an aggregate dataset for exploring the global distribution of open-source developers.

**Contents**

* developer_counts_by_country_region.csv
    Aggregate predicted developer counts for 242 countries and regions.
* docs/index.html
    Interactive 3D globe visualization of the country- and region-level distribution.

**Dataset**

The CSV file contains two columns:

Country/Region,Developer Count
United States,4331264
Brazil,2593480
India,2319526
...

The released file contains aggregate country- and region-level estimates only. It does not include developer identifiers or individual-level location records.

The current dataset covers 23,956,097 developers across 242 countries and regions.

**Visualization**

<img width="5120" height="2638" alt="image" src="https://github.com/user-attachments/assets/4b0f1a04-1ddd-44c6-922e-caf34526e400" />


The interactive 3D globe supports:

* rotating and zooming the Earth;
* searching for a country or region;
* viewing estimated developer counts and global rankings;
* comparing distributions across continents.

The visualization is available through GitHub Pages:

https://peng99999.github.io/DevLoc/

**Intended Use**

This repository is released to support research on open-source ecosystems, developer geography, regional participation, and related empirical software engineering studies.

When using the dataset, please treat the values as model-based aggregate estimates rather than official population statistics.

**License**

This project is released under the MIT License.
