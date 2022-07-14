# configuration info for observatory-data package

## Overview

This `/config` folder holds specific information that helps automated processing

| relative path | purpose                                                       |
|---------------|---------------------------------------------------------------|
| `config/google-docs.yml` | id of docs and tabs where data is gathered         |


The contents and formatting of some of these are described with some more detail below

## `config/google-docs.yml`

| key              | usage                                                       | 
|------------------|-------------------------------------------------------------|
| habitat          | groups the information for all the habitats                 |
| habitat.sediment | groups the document info for sediment                       |
| habitat.water    | groups the document info for water                          |
| habitat.hard     | groups the document info for hard substrates                | 
| habitat.\*.docid | the id of the google document                               |
| habitat.\*.tabid.observatory | the gid in the document for the observatory tab |
| habitat.\*.tabid.sampling | the gid in the document for the sampling tab       |
| habitat.\*.tabid.measured | the gid in the document for the measured tab       |
