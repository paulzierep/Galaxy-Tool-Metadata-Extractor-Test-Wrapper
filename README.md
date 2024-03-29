# Purpose
This repository contains a collection of galaxy wrappers to test the functionality of the Galaxy Tool Metadata Extractor. 
See [Galaxy Tool Metadata Extractor](https://github.com/galaxyproject/galaxy_tool_metadata_extractor)

This repository should contain all wrapper use cases that could be parsed by the Galaxy Tool Metadata Extractor.

Use cases:

Path  | Source | Use case description
------------- | ------------- | -------------
tools/aldex2  | [IUC](https://github.com/galaxyproject/tools-iuc)  | Normal wrapper (with macros)
tools/abritamr  | [IUC](https://github.com/galaxyproject/tools-iuc)  | Normal wrapper (no macros)
data_managers/data_manager_cat  | [IUC](https://github.com/galaxyproject/tools-iuc)  | Data Manager (not parsed !)
tools/2d_auto_threshold  | [BMCV](https://github.com/BMCV/galaxy-image-analysis)  | wrapper with biii xref in wrapper.xml
tools/fastp  | [IUC](https://github.com/galaxyproject/tools-iuc) | line break `\n` in ID in wrapper macro (https://github.com/galaxyproject/galaxy_tool_metadata_extractor/pull/69)
tools/spades  | [IUC](https://github.com/galaxyproject/tools-iuc) | multiple bio.tool IDs
