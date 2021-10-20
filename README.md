## Nonprofit Websites Are Riddled With Ad Trackers

This repository contains the data described in our story, "[Nonprofit Websites Are Riddled With Ad Trackers](https://themarkup.org/)."

### Data

All reports generated for this analysis were done so using the `blacklight-reporter`. Please refer to its [README](https://github.com/the-markup/blacklight-reporter) for more information about the indivudual reports. Summary statistics used in the story were calculated using the [original Blacklight analysis code](https://github.com/the-markup/investigation-blacklight-the-high-cost-of-free/blob/master/0-100k-scan.ipynb), the variant used for this story can be found in [`notebooks/0-100k-scan-nonprofit-version.ipynb`](https://github.com/the-markup/investigation-nonprofit-privacy/blob/main/notebooks/0-100k-scan-nonprofit-version.ipynb).

The data folder is organized as follows:<br>

| Folder                                               | Description                                                                                                                                                                                              |
| :--------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `data/nonprofit-websites.csv`                          | A list of nonprofits along with their websites, as publicly listed on [GuideStar](https://www.guidestar.org/).                                                                                           |
| `data/oct-13-summary.csv`                          | The summary file generated from our bulk Blacklight scan of nonprofit websites on Oct. 13, 2021.                                                                                           |
| `data/story-inspections`                             | The `blacklight-collector` inspections for the websites mentioned in our [story](TK). |

### Which IRS Categories We Looked At

We chose to look at nonprofits labeled with certain IRS Activity Codes in the IRS master file. Below are the codes we looked at, and a description as taken from [a table maintained by the Urban Institute](https://nccs.urban.org/publication/irs-activity-codes).

| NTEE Code | Description |
|----|----|
| **R** | Civil Rights, Social Action & Advocacy | 
| **F** | Mental Health & Crisis Intervention |
| **G** | Voluntary Health Associations & Medical Disciplines |
| **H** | Medical Research |
| **I** |  Crime & Legal-Related |
| **P47** | Pregnancy Centers |
| **P45** | Family Services for Adolescent Parents |
| **E40** | Reproductive Health Care |
| **B83** |  Student Sororities & Fraternities |
| **B94** |  Parent & Teacher Groups |
| **B21** |  Preschools |
| **B24** |  Primary & Elementary Schools  |
| **B25** |  Secondary & High Schools  |
| **B28** |  Special Education |
