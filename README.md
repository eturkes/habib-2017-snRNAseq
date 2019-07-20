<!---
    This file is part of habib-2017-snRNAseq.
    Copyright (C) 2019  Emir Turkes

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

    Emir Turkes can be contacted at emir.turkes@eturkes.com
-->

# Habib 2017 snRNAseq Analysis
#### *This analysis is considered complete and should not see major updates*

Analysis of Habib 2017 snRNAseq data

The up-to-date R Markdown HTML report can be found [here](https://drive.google.com/file/d/1pApDFB0KPQeQtdhrEoat58fj1rR_ukbK/view?usp=sharing). 
After downloading, it should be opened in a web browser.

In order to reproduce the report, prerequisite data must be downloaded from my [Google Drive](https://drive.google.com/drive/folders/1nbA_D2RlJqW7g4_0Grl6yVVJkWb5WEw4?usp=sharing).
After downloading and unzipping, move the directory to the project root and rename it as `gdrive`. 

A Docker image for this project is available from [DockerHub](https://cloud.docker.com/repository/docker/eturkes/habib-2017-snrnaseq/general). 
This is the recommended way to reproduce and explore the project. 

To run all scripts and generate an HTML report in the `results` directory, just run:
```
docker-compose run all
```

To open RStudio, run:
```
docker-compose up rstudio
```
It will be available in your web browser at the address [localhost:8790](http://localhost:8790).
