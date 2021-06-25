## WHY? (SHOPKEEPERS)

* New kinds of technologies are being used to monitor the essential retailer. As cameras/processors get smarter, they are increasingly able to process data themselves - at the network edge (on hand-sized $400 processors linked to off-the-shelf cameras), rather than centrally in the cloud - simplifying computational loads and the need to transmit data unnecessairly.  Our AI application engages essential retailer shopkeepers differently by showing item flows in real-time, a super important and overlooked aspect of the human-computer interface.

* This research relies on a mix of methods to accomplish this:
  * video data collection
  * on-the-ground-fieldwork
  * numerical modeling 
  * embedding AI applications on edge devices 
* Video data collection and on-the-ground field work help us collect data.  Numerical modeling and embedding AI applications on edge devices helps us log the identity and location of every item on a 4' x 12' shelf.  Next, we generate detailed maps of items distribution, abundance, migrations and patterns.  Ultinately, these methods are used to build an AI that identifies "whose hands are doing what, with what object" at the essential retailer.

## WHY? (GUESTS & SHOPKEEPERS)

* As the lines between banks, tech and retail blur we must ask how technology is changing the checkout experience.  Guests may need to prepare for a long-term shift in how money and checkout works. _Our code runs on the idea that "people don't want to make payments, they want to do what a payment facilitates"._ Our proof of concept automates the dull and repetitive tasks of scanning goods by having a camera, processor and many lines of code run autonomous checkout software.  We believe shoppers want choice.  Sometimes they will want autonomous-checkout and sometimes they will want to checkout with a cashier. Thisalso gives shopkeepers some freedom from the register so they can focus on those things that make their space feel more like a "third place".  
* Our moonshot is to normalize the idea of retailers selling gift cards redeemable for autonomous checkout credits directly to guests. Imagine walking into a retailer, "checking in" with your smartphone, browsing/shopping and then walking out. Pre-paying means transactions could also be settled instantly on in-house digital ledgers, rather than the pipes of cards networks and banks. Additionally, by pulling transactions out of the banking system we would also cut operating expenses for retailers, which amount to 1-3% per transaction.

## RESEARCH GOALS

* As with any AI / machine learning, the syllabus determines the outcome.  Our AI's syllabus is focused on the political value of time we may have not considered ourselves.  We build the system to think like an differently, sensitive to the members meaning filling each respective space.  The subroutines are written to make sure the biases of the analog world regarding the political value of time are not repeated in the AI world.  Questions such as -- who benefits and who is harmed by this application?  And does it put power into the hands of the already powerful? -- are asked repeatedly at every step in the software development process.  This approach to development ensures diversity and sustainability is actively built in at every step of the system.
* Additionally, this project was created to showcase my ability to write software that generates revenue again, but this time at the graduate studies level.

## HOW? (PROBLEM SOLVING PROCESS)

* 1 - ASK "WHAT SYSTEM MUST DO" by analyzing problem with shoppers and experts in the field to determine what is required of solution
* 2 - MODEL REQUIREMENT for OBJECTS using bottom-up approach that looks for objects that closely model the real world
* 3 - NAME the CLASSES and METHODS that carry out these RESPONSIBILITIES from step 2 
* 4 - REFINE the CLASS INTERFACE and DETERMINE: CLASSNAME, RESPONSIBILITIES and COLLABORATOR CLASSES to build cohesion
* 5 - DEVELOP the MESSAGE SENDING PROTOCOLS using step 4 as starting point and determine what types of arguments need to be sent with a message and what type of object a method can return.  Here is where we also document preconditions and postconditions, that solidify are the responsibilities of the class. 
* 6 - SETUP the CLASS FRAMEWORKS for testing newly identified classes to make sure components integrate and fulfill our goals
* 7 - TEST CLASS INTERFACE and "add some flesh" to step 6 by sending message sending protocol to class interface before developing the methods
* 8 - FILL in the METHODS and CLASS ATTRIBUTES for each class to make sure object's methods work 
* 9 - TEST, DEBUG AND INTEGRATE all the parts :)

##  IN-HOUSE REFERENCE LIBRARY

ACTIONS / OBJECTS TRACKED
  * Items in Store (~80)
  * Single Handed Pulls of Items From Shelf
  * Double Handed Pulls of Items From Shelf
  * Hand Offs of Items Between People
  * Non Shelf Pulls of Items
  * Tosses of Items Between People
  * Misplaced Items 
  * Final Item Inventory and Checkout
  * This dataset is a growing list.  It is mainly focused on scenarios that require long range temporal reasoning for differentiation.  Other scenarios focus more on the object-action relationship, such as people pulling itmes from a shelf. This current dataset has 100 action-object classes, with 100 clips for each action and each clip running approx 10 seconds. In total the v1 dataset has 10,000 videos. It should be noted that all clips collected have variable resolution and frame rates.

## "PRETRAINING"

* We use an offshoot of ImageNet model to pre-train our system. We are immensely grateful for ImageNet and the human labor it took to sort, label and prep the millions of images across thousands of categories. Pre-training helps us avoid representational bottlenecks, boost our activations per tile and better balance the width and depth of the network.  What's more this approach helps us better understand how to model spatio-temporal cues at different scales across multiple cameras.

## ADDRESSING DATA BIAS

## ANALYSIS, DESIGN & IMPLEMENTATION 

## TRAINING DETAILS

* Learning Rates 
* Additional Data Prep
* Testing

## EXPERIMENTS

* In this section we explore the accuracy and generalization of models on different benchmark data sets. 
* Accuracy = Repeatability + Calibration

## RESULTS

## MEASURING ACCURACY ACROSS BENCHMARK DATASETS

* UCF-101 DATASET - 13320 videos across 101 action classes
* Accuracy:
* HMDB-51 DATASET - 6766 videos across 51 action classes
* Accuracy:

## DISCUSSION

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
* The Poltical Value of Time by Elizabeth F. Cohen (2018)
* 
* Building Business Applications Using C++
* Hands On Machine Learning with C++ (2020)
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

