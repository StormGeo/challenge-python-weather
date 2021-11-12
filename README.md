<p align="center">
  <a href="https://www.stormgeo.com/">
      <img src="https://imgur.com/iPIZTeG.png" alt="StormGeo" width="300px"/>
  </a>
</p>

___


## Recruitment process

Hello Python developer, ready to join our recruiting process?

### Requirements

Good knowledge in:

- Python
- Object Oriented Programming
- Design Patterns
- Automated tests
- Task automation
- Web scraping
- SQL
- NoSQL

### The challenge

- Read two HDF5 files with temperature data: one with *predicted data* and the
  other with *observed data*. Note: observation station locations can be found
  in the JSON metadata file.
- Calculate the RMSE index for each 6-hour interval in the time-series at all
  points in the matrix.

<img src="https://imgur.com/WfCrfQX.png" alt="RMSE - Root Mean Square Error" />

- Plot two-dimensional maps of the index for each period and a graph of the
  time-series of the same index for Bergen (Latitude **60.39299** and Longitude
  **5.32415**).
- Create a `PROJECT.md` file with descriptions of all the steps to install and
  use your software.
- Write the index calculation result in a NetCDF file (**Optional**).

**Description of datasets:**

Forecast Data

| Property | Description |
| :-------------------------------- |:-------------|
| Archive | forecast.hdf5 |
| Number of timesteps | 73 |
| Reference date | 2021-11-01 |
| Timestep Frequency | Hour |
| Temperature Variable Name | temperature |
| Temperature unit | Celsius degree |

Observed Data

| Property | Description |
| :-------------------------------- |:---------------|
| Archive | observations.hdf5 |
| Number of timesteps | 73 |
| Reference date | 2021-11-01 |
| Timestep Frequency | Hour |
| Temperature Variable Name | temperature |
| Temperature unit | Celsius degree |

Observation Metadata

```json
{"<station id>": {"lon": "<station lon>", "lat": "<station lat>", "station_name": "<station name>"}}
```

### Evaluation

What we will evaluate:

- Performance
- Maintainability
- Organization
- Best practices


### Steps

To complete the challenge, follow the following steps:

1. Create a new, private repository using this repository as a reference.
    * Go to the following link: https://github.com/new/import
    * Enter the following repository URL in the "Your old repository clone URL"
      field: https://github.com/StormGeo/challenge-python-weather
    * Name the repository `challenge-python-weather`.
    * Set the repository privacy to "Private".

<img src="https://imgur.com/d9hBflb.png" alt="Import private repository" />

2. Create a branch where you implement your solution. Include a `PROJECT.md`
   with an explanation of how we should run the project and with as much detail
   as possible about what was done.

3. Make a pull request of your solution to your own private repository.

4. Invite your StormGeo contact, or person specified by your contact, as a
   contributor to your repository.

___


Any questions, please contact our team.

