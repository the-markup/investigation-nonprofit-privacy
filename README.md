## Nonprofit Websites Are Riddled With Ad Trackers

This repository contains the data described in our story, "[Nonprofit Websites Are Riddled With Ad Trackers](https://themarkup.org/)."

### Data

All reports generated for this analysis were done so using the `blacklight-reporter`. Please refer to its [README](https://github.com/the-markup/blacklight-reporter) for more information about the indivudual reports. Summary statistics used in the story were calculated using the [original Blacklight analysis code](https://github.com/the-markup/investigation-blacklight-the-high-cost-of-free/blob/master/0-100k-scan.ipynb).

The data folder is organzied as follows:<br>

| Folder                                               | Description                                                                                                                                                                                              |
| :--------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `data/nonprofit-websites.csv`                          | A list of nonprofits along with their websites, as publicly listed on [Charity Navigator](https://www.charitynavigator.org/).                                                                                           |
| `data/oct-13-summary.csv`                          | The summary file generated from our bulk Blacklight scan of nonprofit websites on October 13, 2021.                                                                                           |
| `data/story-inspections`                             | The `blacklight-collector` inspections for the websites mentioned in our [story](TK). |
