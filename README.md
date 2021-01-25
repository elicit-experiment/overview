# overview

Elicit is an online platform for researchers to carry out online human subject experiments in the web browser. The platform is comprised of three parts, 

1. An experiment [frontend](https://github.com/elicit-experiment/frontend "Frontend") that visualize stimuli, capture user responses and interaction using scales and webcam eye tracking. 
2. An [API](https://github.com/elicit-experiment/api "API") that allows access to a database where user responses, behavioral data and interactions are stored for easy retrieval 
3. A [client-API](https://github.com/elicit-experiment/client-api "Client API") written in python, that allows researchers to both create and extract results from experiments and the API from (2) 

The experiment platform is currently hosted on [Elicit](http://elicit-experiment.com/ "Elicit") and investigators can contact Jens Madsen if they want to be added as an investigator and try the platform out. The client side API is written in Python, so you do not need to know any HTML or Javascript to create experiments or retrieve results. 

The platform interfaces with AMT and Prolific, where the two services are used to direct user to Elicit and random comletion codes are generated at the completion of an experiment which can be used for payment on AMT/Prolific. Over 1000 users have been through the platform and counting, where webcam eye tracking has been collected for the paper *Synchronized eye movements predict test scores in online video education* published in PNAS. 


At current state the following items have been implementes

**Scales**
- Likert scales
- Continuous one dimensional scale. (w/o time resolved ratings)
- Categorical scale (w/o multiple selection)
- List select.
- Text box

**User behavior**
- Eye movements (using WebGazer)
- Mouse movements (coming soon)
- Keyboard events (coming soon)

**Stimuli**
- Images
- Video (using YouTube)
- Audio (web player)

**Interface**
- Amazon Mechanical Turk
- Prolific
- Automatically generates completion codes. 


The platform was initially started at the Technical University of Denmark under the CoSound project. The focus was to carry out listening experiments, but the platform has since been expanded greatly using various funding sources and is now continued at the City College of New York. 
