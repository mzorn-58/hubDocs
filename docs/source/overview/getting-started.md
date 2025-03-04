# Getting started  

The following subsections provide pointers to resources developed by the Consortium to make designing, launching, and maintaining hubs easier.  

The simplest way to set up a modeling hub is to directly clone one from the [template hub repositories](https://github.com/Infectious-Disease-Modeling-Hubs?q=&type=template&language=&sort=) or to use one of the [example hub repositories](https://github.com/Infectious-Disease-Modeling-Hubs?q=example&type=all&language=&sort=), which are based on prior use cases. The template hubs provide a skeletal structure of a hub without any data in them, whereas the example hubs provide minimal working examples of hubs and could be used for ideas of how to set up configuration files for new projects.    

## [Template hubs](https://github.com/Infectious-Disease-Modeling-Hubs?q=&type=template&language=&sort=)  

The [`hubTemplate`](https://github.com/Infectious-Disease-Modeling-Hubs/hubTemplate) repository (under development) provides a skeleton structure for groups wishing to build and maintain a new modeling hub. This repository may be cloned to start a new repository for a modeling hub.  

## [Example hubs](https://github.com/Infectious-Disease-Modeling-Hubs?q=example&type=all&language=&sort=)  

The [example Hub repositories](https://github.com/Infectious-Disease-Modeling-Hubs?q=example&type=all&language=&sort=) provide minimal working examples of hubs that can be used for ideas of how to set up configuration files for new projects. They are also used as use-cases for testing the [software for modeling hubs](software.md). 

### 1. [Simple Forecast Hub Example](https://github.com/Infectious-Disease-Modeling-Hubs/example-simple-forecast-hub)  
The [Simple Forecast Hub Example](https://github.com/Infectious-Disease-Modeling-Hubs/example-simple-forecast-hub) is adapted from forecasts submitted to the [US COVID-19 Forecast Hub](https://github.com/reichlab/covid19-forecast-hub), but has been modified to provide examples of nowcasts.  

### 2. [Complex Forecast Hub Example](https://github.com/Infectious-Disease-Modeling-Hubs/example-complex-forecast-hub)  
The [Complex Forecast Hub Example](https://github.com/Infectious-Disease-Modeling-Hubs/example-complex-forecast-hub) is designed to be similar to the [US COVID-19 Forecast Hub](https://github.com/reichlab/covid19-forecast-hub) and the [European COVID-19 Forecast Hub](https://github.com/covid19-forecast-hub-europe/covid19-forecast-hub-europe).  

### 3. [Complex Scenario Hub Example](https://github.com/Infectious-Disease-Modeling-Hubs/example-complex-scenario-hub)  
The [Complex Scenario Hub Example](https://github.com/Infectious-Disease-Modeling-Hubs/example-complex-scenario-hub) is designed to be similar to the [US COVID-19 Scenario Modeling Hub](https://github.com/midas-network/covid19-scenario-modeling-hub)  


## [Schema files](https://github.com/Infectious-Disease-Modeling-Hubs/schemas)  

To take advantage of the infrastructure designed by the Consortium, a hub must contain JSON configuration files in a [specific location and format](hub-config). The schemas that define the structure and formats of the configuration files live in their own [schemas repository](https://github.com/Infectious-Disease-Modeling-Hubs/schemas). The schemas are versioned, and every hub must point to a specific version of the schemas that they are using.  

## [Software for modeling hubs](software.md)  

The main benefit of setting up a hub using the structure outlined in this documentation is that it enables you to use a wide array of tools designed to support common modeling hub tasks, like loading model output data, plotting the model output data, building ensembles using the data, and in some cases evaluating the predictions made by different models.  

