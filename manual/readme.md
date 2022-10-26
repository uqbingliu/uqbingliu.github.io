# Website Management

## Organization of files
```
|- _config.yml: for `site` variable.
|- _includes/: configure components like header, footer, analytics, etc. (html)
|- _pages/: configure pages (bound to each tab)
```

## Instructions

### Add one paper
* add one md file under `_publications/` directory.

### Add analytics (google-universal)
* Create Google Analytics account. ([reference](https://support.google.com/analytics/answer/10269537?hl=en#zippy=%2Cadd-the-google-tag-to-a-website-builder-or-cms-hosted-website-for-example-wordpress-shopify-etc))
* Configuration. `_config.yml` -> `analytics:`.

## Modify the templates
### Layout of the website
#### Tabs
### paper entry
`_publications/archive-single.html`

## Grammar
Global variables: 
* site: `_config.yml`
* page: the meta data of each md file.

## TODOs
* [ ] add visit stat function 




