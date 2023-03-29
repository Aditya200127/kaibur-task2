# kaibur-task2
FlowMeter is an experimental utility built for analysing and classifing packets by looking at packet headers.
FlowMeter aims to:

 - **Classify packets and flows as benign or malicious with high true positives (TP) and low false positives (FP)**. 
 - **Use the labeled data to reduce amount of traffic requiring deeper analysis**. 

Additionally, Deepfence FlowMeter also categorizes packets into flows and shows a rich ensemble of flow data and statistics
*FlowMeter takes packets and returns file with statistics of flows.* 
*Flowmeter takes packets and returns file with statistics of flows and classifies packets as benign or malicious.*  |

## When to use FLowMeter

Use FlowMeter if you wish to build and operate machine-learning models on network packet data.

## Who uses FlowMeter?

 * We use FlowMeter internally to quickly analyse and label packets. It forms one part of a project to build a fast pre-filter for packets before we conduct deeper layer-7 analysis in [Deepfence ThreatMapper]
