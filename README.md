# overview

Elicit is an online platform designed to allow researchers to let people carry out experiments in the web browser. The platform is comprised of three parts, 

1. An experiment frontend that visualize stimuli, capture user responses and interaction using scales and webcam eye tracking. [link](https://github.com/elicit-experiment/frontend "Frontend")
2. An API that allows access to a database where user responses, behavioral data and interactions are stored for easy retrieval [link](https://github.com/elicit-experiment/api "API")
3. A client-API written in python, that allows researchers to both create and extract results from experiments and the API from (2) 
[link](https://github.com/elicit-experiment/client-api "Client API")

The experiment platform is currently hosted on www.elicit-experiment.com and investigators can contact Jens Madsen if they want to be added as an investigator and try the platform out. The client side API is written in Python, so you do not need to know any HTML or Javascript to create experiments or retrieve results.

At current state the following items have been implementes

**Scales**
-Likert scales
-Continuous one dimensional scale. (w/o time resolved ratings)
-Categorical scale (w/o multiple selection)
-List select.
-Text box

**User behavior**
-Eye movements (using WebGazer)
-Mouse movements (coming soon)
-Keyboard events (coming soon)

**Stimuli**
-Images
-Video (using YouTube)
-Audio (web player)

**Interface**
-Amazon Mechanical Turk
-Prolific
-Automatically generates completion codes. 
