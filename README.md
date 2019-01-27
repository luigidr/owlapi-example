# Sample usage of the OWL API Library

A simple example of how to use the [OWL API](http://owlcs.github.io/owlapi/) library and the HermiT reasoner.

In particular, the project will:
* load the ontology present in the `resources` folder (`university.owl`)
* compute logical inferences
* ask for
  * university individuals
  * which degrees each university offers
  * which courses each degree offers
  * who is enrolled in those courses
  
It uses OWL API (version 4.5.4) and the [HermiT](http://www.hermit-reasoner.com) reasoner (version 1.3.8.413). Dependencies are handled by Gradle.
