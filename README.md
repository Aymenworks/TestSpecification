# Odigo - Home screen iOS

|         	      |  	                                                  |
|-----------------|----------------------------------------------------	|
| **Title**       | As an user, I want to see the sightseeing articles 	|
| **Trello cards**| [N°2](http:google.fr)                              	|
| **Developers**  | Aymen Rebouh                                       	|

## Design

### iPhone
[Sketch link]()

### iPad
[Sketch link]()

## Navigation rules

|       Area  	  |  	              Interactions                        |
|-----------------|----------------------------------------------------	|
| **A1**          | As an user, I want to see the sightseeing articles 	|
| **A2**          | As an user, I want to see the sightseeing articles 	|
| **A3**          | As an user, I want to see the sightseeing articles 	|
| **A3**          | As an user, I want to see the sightseeing articles 	|

## Core rules

|         	      |  	                                                  |
|-----------------|----------------------------------------------------	|
| **Title**       | As an user, I want to see the sightseeing articles 	|
| **Trello cards**| [N°2](http:google.fr)                              	|
| **Developers**  | Aymen Rebouh                                       	|

## Data source

### In

The final URL will be the **base url** indicated somewhere else **+** the service 

For example : `https://odigo.api.production/topArticlesOfTheDay`


| Feature                       | Service             | HTTP Method | Parameters                                | Content-type      |
|-------------------------------|---------------------|-------------|-------------------------------------------|-------------------|
| **Top 5 articles of the day** | topArticlesOfTheDay | GET         | category=all/sightseeing/food/shopping/...| applications/json |
| **Last 20 articles**          | lastArticles        | GET         | category=all/sightseeing/food/shopping/...| applications/json |

### Out

| Feature                       | JSON                                        |
|-------------------------------|---------------------------------------------|
| **Top 5 articles of the day** | [Top5Articles](https://link.to.jsonFile.com |
| **Last 20 articles**          | [LastArticles](https://link.to.jsonFile.com |
