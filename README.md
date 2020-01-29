# LinkedIn Ads Block Configuration Project

This project consists of configuration files for the LinkedIn Ads block project `block-linkedin-ads`
If installed through the marketplace, input the schema and connection values in the install workflow, otherwise edit them in the `manifest.lkml` file.

## To install this block manually, you will need to:

1. Update the constants in the `manifest.lkml` to point to your specific linkedin ads schema and connection name.

2. Enable the Project Import feature currently in /admin/labs on your Looker instance.


Note that the `ref:` should point to the latest commit in thr core block repo [block-linkedin-ads](https://github.com/looker/block-linkedin-ads/commits/master) 

### Block Info

This Block is modeled on the schema from Fivetrans's [LinkedIn Ads ETL](https://fivetran.com/directory/linkedin-ads).

The schema documentation for LinkedIn Ads can be found in [LinkedIn's docs](https://developer.linkedin.com/docs/ref/v2/ads/adcampaigns).
