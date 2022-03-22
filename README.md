# foodcoach-ontology

This is a repo for storing the ontology for the graph database that is used in the FoodCoach project.
The ontology contains three main parts:
1. Digital receipts exported from [BitsAboutMe](https://bitsabout.me/en/)
2. Product information from relational database [EatFit](https://eatfit-service.foodcoa.ch/)
3. Aggregated basket information 

Changed has been made so that the ontology is different from EatFit. 
The following properties have been deleted while they were barely used in the past.
1. Product: serving_size, comment, health_percentage
4. Minor category: nwd_subcategory_id
