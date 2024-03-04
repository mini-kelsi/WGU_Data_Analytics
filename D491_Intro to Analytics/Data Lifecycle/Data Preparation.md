### Data Preparation Phase
    ## Phase 2

* Involves **data preparation**
  > includes the steps to explore, preprocess, and condition data prior to modeling and analysis.
* The team needs to create a robust enviroment in which it can explore the data that is separate form a production environment.
* Prepare an **analytics sandbox**
* Perform **ETLT**
  >*a combination of extracting, transforming, and loading data into the sandbox.*

  # Data Preparation tends to be the most labor-intensive step.

  * Learn about the data and familiar themselves with the data.
  * *Important to catalog the data sources that the team has access to and identify additional data sources that the team can leverage but perhaps does not have access to today*
* Learning about the data accomplishes several goals:
    * Clarifies sthe data the team has access to
    * Highlights gaps by identifying datasets that the team may find usedful but may not be accessible to the team that day
    * Identifies datasets outside the organization that may be useful to obtain, through open APIs, data sharing, or purchasing data to supplement already existing datasets
* *Data conditioning* refers to the process of cleaning data, normalizing datasets, and performing transformations on the data.
    - **Critical step**
    -  Data conditioning is performed *only by* **IT, the data owners, a DBA, or a data engineer.**
    -  Can involve many complex steps to join or merge datasets or otherwise get datasets into a state that enables analysis in further phases.
* Teams begin forming ideas in this phase about which data to keep and which data to transform or discard, it is important to involve mu
