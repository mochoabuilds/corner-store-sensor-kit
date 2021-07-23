## 1 INTRODUCTION

* I cannot think of a recent period where so much has changed in the way people think about $.  When people look back as this period they will see $ in a period of rapid change. My hope is that new tools emerging from this era could be a force for good for corner stores. 

## 2 THE FUTURE OF CORNER STORES 

* As sensors and processors get better, they are increasingly able to process data themselves at the network edge on palm-sized processors, rather than centrally in the cloud. That in mind, our system drinks up video-stream data and manipulates it according to a series of instructions.  It then spits out results that build structures, translates the built environment and reveals patterns otherwise beyond humans' minds.  Ultimately, the goal is to multiply the efficiency of what humanity has done at the corner store for decades with reliable, small, thoughtfully designed technology.
* Our tools engage shopkeepers a bit differently by showing them their inventory flows in real-time, giving them "eyes in the back of their head" for the identity and location of inventory in real-time.  
* Eventually, we'd like to also normalize the idea of corner stores providing digital money for autonomous checkout directly to regulars - by converting USD into digital money with a simple swipe on a mobile app. _Imagine walking into a retailer, "checking in" with your smartphone, browsing/shopping and then receiving an adjustable receipt upon walking out._ Pre-paying means transactions could be settled instantly on in-house digital ledgers, rather than the pipes of cards networks and banks. By pulling transactions out of the banking system we would also cut operating expenses for retailers, which amount to 1-3% per transaction.
* However, this boost in inventory mgmt and checkout productivity will take time to work out.  New technology is an example of what economists call "general-purpose technology", like electricity a century ago, it has the potential to boost productivity across many industries.  However, making the most of such tech takes time and experimentation. This accumulation of know-how means applied UX Engineers like myself must collect "intangible capital" for reasons we don't yet understand. Until this intangible capital bears fruit, measured by surges in productivity, entrepreneurial types like myself will continue to prototype, test and spec, over and over.

## 3 METHODS

* Our software engages psychology and art history from the beginning with an extensive set of prototypes to test to see what works and how it could work. Before even writing the first line of code I engaged in an ethnographic study of the corner store by working in one myself. By putting the guest and shopkeepers experience in the forefront, I could better design principles from what I saw people doing. This made the job of developing scenarios for uses of the imagined product much easier.  My 1000+ hours of field work helped me better propose tools that move ahead in a human-centered direction to make monitoring inventory and checkout easier.

* This mixed-methods research relies on a mix of methods like:
  * data collection 
  * on-the-ground fieldwork
  * creation of models
  * embedding models to target platform
  * empowering AI applications on edge devices 

## 4 IN-HOUSE REFERENCE LIBRARY

ACTIONS / OBJECTS TRACKED
  * Packaged Goods on 4' x 12' Shelf (Price | Sold By | Vendor | Product Wtg | Unit Cost | Quantity on Floor | Quantity Stored | Pars | Order Y/N)
  * Single Handed Pulls of Packaged Goods From Shelf
  * Double Handed Pulls of Packaged Goods From Shelf
  * Hand Offs of Packaged Goods Between People
  * Non Shelf Pulls of Packaged Goods
  * Tosses of Packaged Goods Between People
  * Misplaced Packaged Goods 
  * Final Packaged Goods Count Near Checkout
  * This dataset and its data pipelines are a growing list. This current dataset has 100 action-object classes, with 100 clips for each action and each clip running approx 10 seconds. In total this dataset has 10,000 videos. It should be noted that all clips collected have variable resolution and frame rates.

## 5 "PRETRAINING"

* We use an offshoot of ImageNet model to pre-train our system. We are immensely grateful for ImageNet and the human labor it took to sort, label and prep the millions of images across thousands of categories. Pre-training helps us avoid representational bottlenecks, boost our activations per tile and better balance the width and depth of the network.  What's more this approach helps us better understand how to model spatio-temporal cues at different scales across multiple cameras.

## 6 ADDRESSING DATA BIAS

## 7 ANALYSIS, DESIGN & IMPLEMENTATION 

## 8 TRAINING DETAILS

* Learning Rates 
* Additional Data Prep
* Testing

## 9 EXPERIMENTS

* In this section we explore the accuracy and generalization of models on different benchmark data sets. 
* Accuracy = Repeatability + Calibration

## 10 RESULTS

## 11 MEASURING ACCURACY ACROSS BENCHMARK DATASETS

* UCF-101 DATASET - 13320 videos across 101 action classes
* Accuracy:
* HMDB-51 DATASET - 6766 videos across 51 action classes
* Accuracy:

## 12 DISCUSSION

## APPENDIX A: "CORNER STORE v-1" EXPANDED

## ACKNOWLEDGEMENTS

* This work was supported by my immediate family, close friends, confidants, my neighborhood grocers/corner stores and the open source community. 

## SANDBOX

* Teaching computer vision systems NOT to use guest biometrics as a condition of accepting payment under the Song Beverley Act of 1971
* Determining the metrics that improve downstream performance
* Better understanding the front-back orientation of human limbs due to clothing, lighting, background, optical interference
* "What You Almost Bought" Merchant Facing Application
* Bridging the edge-cloud barrier to lower server costs?
* Rewriting code and making arrays more ergonomic
* Lowering the costs of switching data across different corner stores
* Better understanding how social, economic and legal systems work together to achieve goals

## REFERENCES

* Writing Ethnographic Field Notes, 2nd Edition (2011)
* The Great Good Place by Roy Oldenburg (1989)
* "Covid-19 and Implications for Automation" (2020)
*
* Building Business Applications Using C++
* Knowledge Representation and Reasoning (2004)
* Learning OpenCV 3: Computer Vision in C++ with the OpenCV Library (2017)
*
* "Quo Vadis, Action Recognition? A New Model and the Kinetics Dataset" (2018)
* "The Kinetics Human Action Video Dataset" (2017)
* "Two Stream Convolutional Networks for Action Recognition in Videos" 
* 
* "Towards Good Practices for Very Deep Two-Stream ConvNets" (2015)
* "FlowNet 2.0: Evolution of Optical Flow Estimation with Deep Networks" (2016)
* 
* "Going Deeper with Convolutions" (2014)
* "Rethinking the Inception Architecture for Computer Vision" (2015)

