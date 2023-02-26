# Overview

These sources are markdown files that are used to generate a site based on "Transmaxxing". The site (static HTML pages) are generated using Jekyll (a static site generation tool), along with some custom modules available from Github. This site most likely can be generated without the custom Github modules as well - there's nothing specific from the Github API when generating these pages. ***Any changes made to the generated site will be overwritten after the pages are rebuilt using these sources. ***

## Theme, Media

The theme can be changed by editing the [_config.yml](../_config.yml). Sitename, description are all changed there, as well as theme-specific settings like nav bar and external link.

The Media folder relies on relative path resolution. This is normally included in Github Pages and in the non-Pages build instructions config below. If you move the media folder, all media links will break in the referencing pages. Pay attention to relative path levels.

## CNAME

The CNAME file is the resolved domain name this page is hosted at. If it's an A-record pointing here, the CNAME is the info used to verify that route. Change it if the routed domain changes.

## Github Pages

These sources are able to be built using a default Github Pages configuration. They may be placed in a root of a repository, or in a subdirectory. Refer to documentation in Github Pages for more info.

## Generating with Jekyll Standalone

The easiest method is to follow the documentation on Github for the OS you are generating the site for:

[Testing your site locally](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)

You can then copy the generated sources to the appropriate directory on your hosting provider site.