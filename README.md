# Title

# Abstract
The dataset is provided by Open Food Facts which is an open platform to collect varieties of data on food across the world. From this, one can extract appropriate information in order to answer some problem statements. For instance, in a framework of social good, one can analyze the ingredients of given products in order to warn customers about the (health and environmental) implications of what they are buying. It is also possible to track the food to learn the flux and the carbon footprint of different products. An analysis regarding packaging would be interesting as well; we could mesure the amount of plastic waste produced by the food industry.

# Research questions

### Global Food Industry Overview:

- Is there a correlation between the price and the healthiness of the food. Can anyone afford to eat healthy? What are the (micro/macro) nutrients that will lack the most in low-budget households? How does this change from country to country?

# Dataset
(todo)

# A list of internal milestones up until project milestone 2
- Get used to the data.
- Preprocess/Clean the data.
- Do some statistics in relation to the research questions
- Select a final interesting problem statement that could meaningfully take in account a maximum number of aforementionned features and related trend analysis.

# Questions for TA


Open Food Facts - Milestone 2

The dataset is obtained through an open source platform where information about food products are available and updatable by users.

ABSTRACT:

This step consisted in exploring and assess a first analysis of available data and their consistency to obtain a study scope. By exploring the dataset, fields have been removed because being either irrelevant or presenting to high number of missing values. A reduced-field data set is obtained to study the healthiness and the eco-friendliness of products. The previous characteristics will be used to establish a ranking of brands, stores and countries.

Analysis Strategy:

After exploring the dataset, some questions that were previously considered can’t be covered. For instance, the establishment of a relation between the healthiness food and revenues, will not be assessed as the information about prices is not available. Although, it is possible to study interesting facts. The exploration lead to a final study subject: The healthiness and Eco-Friendliness of brands and countries regarding food.

	▪	Healthiness:

The healthiness is measured with the « Nutrition Score ». This data is available for many products and its calculation method is available. Although, that the number of missing values is high, these can be obtained through calculation based on the nutriments which are much largely available. The score is given through an alphabetical ranking that are derived based on numerical values. One will restaure the numerical values to make a more stringent ranking.

	▪	Eco-Friendliness:

This information is not directly available in the dataset. It will be calculated based on 2 criterion: the packaging material and the distance between the origin of the product and its final purchasing country. For the packaging, one will consider if either it is recyclable or not. It is well known that the plastic used in the food industry is in general not recyclable except when it’s bottles form which are generally built in PET. Glass bottles are also recyclable and will be considered this way. The carbon footprint is not available in the data, therefore, this will be replace by the impact of distance travelled by the products. The calculation will be done with an average carbon emission per mass and kilometer.


Expected Outcome:

The goal will be to rank brands, stores and countries based on the aforementioned criterion. It will even be possible to create an arbitrary label to do so. In addition, different links could be found. For example, it will possible to say if, generally the food of low-quality has a high carbon footprint. It will be also possible to expose the countries that are more importer than exporter and assess their part of responsibility in making food travel so the responsibility of ecological impact.

 

