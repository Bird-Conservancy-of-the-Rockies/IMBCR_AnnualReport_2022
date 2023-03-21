# IMBCR_AnnualReport_2022
Code to produce the IMBCR Annual Report as a Quarto Book in html and pdf formats.


## About Quarto Books

## Useful reference links

- Open hyperlink in new tab by default `quarto-dev/quartocli` issue [#3169](https://github.com/quarto-dev/quarto-cli/discussions/3169#discussion-4538526)  
  - Add a `.lua` filter to `_quart.yml`, which appends code to each link within the doc  
  - See also [Quarto Filters](https://quarto.org/docs/extensions/filters.html) and [Lua](https://quarto.org/docs/extensions/lua.html)  

## Current items updated by hand (not programmatically)

## A note about table captions

Current RMarkdown and Quarto do not support cross references for interactive HTML tables (e.g. DT:::datatable). They can be cross referenced as figures but this doesn't make sense. For 2022, I am putting the table captions in manually. See [Github issue #628](https://github.com/quarto-dev/quarto-cli/discussions/628)
