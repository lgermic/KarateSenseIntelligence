----------------------------------------------------------------------
----------------------------------------------------------------------
----------------------------------------------------------------------
----------------------------------------------------------------------
README.txt		KarateSenseIntelligence
----------------------------------------------------------------------
----------------------------------------------------------------------
----------------------------------------------------------------------
----------------------------------------------------------------------

The KarateSenseI projects aims to provide an environment for Karate athlets to study and quantify their performances. 
The environment provides hardware and software based blocks.

Specification:
 - Perception Neuron System by NOITOM (c) for motion capturing - up to 120 fps
 - Surface reconstruction using Microsofts Kinect (c)
 - real time motion capturing and surface reconstruction
 - real time analysis (time series, key value extraction)
(- real time motion recognition update)


Top abstraction Layer of the environment:

KarateSenseI    
	|--->	Hardware
	|	|--->	PN by NOITOM (c) (Perception Neuron) 
	|	|--->	Kinect for XboX or Windows by Microsoft (c)  
	|
	|
	|--->	Software
	|	|--->	Axis Neuron (c) by NOITOM      
	|	|---> 	Kinect SDK v1.8 by Mircosoft   
	|	|--->	Point Cloud Library v1.6 


contact: Leonard Germic (germic@physik.uni-bonn.de)