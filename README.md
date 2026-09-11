# Computing Education Around the World: Dataset
An international dataset of school-level computing curricula.

This dataset is frequently updated using curricular sources gathered from our [update pipeline](https://github.com/rpcerc/ceatw-update-pipeline) which are verified by researchers at RPCERC. The latest version is always stored at the root of the repository with the title `curricular_dataset_<date>.csv`.

You can see previous versions of the dataset in the `previous/` directory. Over time, we hope that this enables research into the development of school-level computing curricula.

## The Structure of the Dataset
Each version of the dataset has the following fields:

| Field | Type | Description |
| --- | --- | --- |
| `country` | String | Country name. |
| `countryCode` | String | Country code. |
| `lastUpdated` | Date | When the country's curricula data was updated in the dataset (not when the curricula was last updated). |
| `summary` | String | A <50-word overview of how computing is taught. |
| `reason` | String | Potential justification. |
| `primary` | Curricular category | Computing curriculum for primary school. |
| `lowerSecondary` | Curricular category | Computing curriculum for lower-secondary school. |
| `upperSecondary` | Curricular category | Computing curriculum for upper-secondary school. |
| `sources` | Object | Online sources that contain evidence of a country's computing curricula. Contains the following fields: `{title, url}`|

## Contributing to the Dataset
If you notice incorrect or missing data about a country's school computing curricula, fill in [this form](https://forms.gle/5qxrFpS2GN5MBcdv7). Add your name if you wanted to be credited!