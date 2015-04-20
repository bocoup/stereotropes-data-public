# Stereotropes Data

This is the collection of data that powers the [Stereotropes](http://stereotropes.bocoup.com)
interactive visualization.

It is build with the code found in [Stereotropes-analysis](http://github.com/bocoup/stereotropes-analysis).

## What data is in here

This repository contains the following data:

- individual trope information
- individual film information
- adjective network of related adjectives (through co-occurance in trope descriptions)
- adjective gender-association map
- genre film lists (genres + decades)
- dictionaries for tropes and films

## How do I use it?

If you've found yourself here, it is likely you're trying to get [stereotropes](http://github.com/bocoup/stereotropes-client) running. That repository relies on a submodule that is not public because it contains data we cannot distribute. This repo contains all the data that we can distribute (minus film posters) so that you can get a local copy of stereotropes running.

Clone this repo into your `stereotropes-client/assets/data` folder.

## Where does this data come from

This data is collected from three different sources:

* [tvtropes.org](http://tvtropes.org) - A collection of community curated tropes, films and film roles.
* [omdb](http://www.omdbapi.com/) - The OMDb API is a free web service to obtain movie information, all content and images on the site are contributed and maintained by our users.
* [Rotten Tomatoes](rottentomatoes.com) - The Rotten Tomatoes API provides access to Rotten Tomatoes' film metadata.

## License

This data is distributed under the licenses specified by the original data
distributors. The licenses include:

#### TV Tropes

All data from TV Tropes is distributed under the

[Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported](https://creativecommons.org/licenses/by-nc-sa/3.0/legalcode) license.

#### OMDB

All content licensed under [CC-BY 4.0 Attirbution International](http://creativecommons.org/licenses/by/4.0/).

#### Rotten Tomatoes

All data obtained from Rotten Tomatoes follows the [Rotten Tomoatoes(tm) XML and API Data Feeds Terms of Service](http://developer.rottentomatoes.com/API_Terms_of_Use).

Any subsequent use of this data must abide by the original distribution guidelines.

## Contact

For any questions, please email stereotropes@bocoup.com.
