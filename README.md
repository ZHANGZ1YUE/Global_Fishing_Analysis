# Global_Fishing_Analysis

Use Global Fishing Watch API to collect and use fishing data.

Steps to run:

-   Install the package

``` r
devtools::install_github("GlobalFishingWatch/gfwr")
```

-   Authorization: The use of `gfwr` requires a GFW API token, which users can request from the [GFW API Portal](https://globalfishingwatch.org/our-apis/tokens). Save this token to your `.Renviron` file (using `usethis::edit_r_environ()`) by adding a string named `"GFW_TOKEN"` to the file (`"GFW_TOKEN" = "PASTE_YOUR_TOKEN_HERE"`). Save the `.Renviron` file and restart the R session to make the edit effective.
