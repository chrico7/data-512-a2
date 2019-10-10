DATA 512 - A2
Corey Christopherson
10-10-2019


The purpose of this project is to explore the concept of bias through data on Wikipedia articles - specifically, articles on political figures from a variety of countries

###
## Source Data ##
###

Source data is licensed under the CC-BY-SA 3.0 and GFDL licenses
 - CC-BY-SA 3.0: https://creativecommons.org/licenses/by-sa/3.0/
 - GFDL: https://www.gnu.org/licenses/fdl-1.3.html

###
## API Documentation ##
###

Wikimedia Foundation REST API terms of use: https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions

ORES API: https://ores.wikimedia.org/v3/#!/scoring/get_v3_scores_context_revid_model

###
## Final Data Fields ##
###

wp_wpds_politicians_by_country.csv

country         | Name of country
article_name    | Name of politician
revision_id     | article ID
article_quality | ores score
population      | Population of Country

###
## Special Considerations ##
###

 - There are several articles and nations that did not have data in both files. These records have been retained in the wp_wpds_countries-no_match.csv file