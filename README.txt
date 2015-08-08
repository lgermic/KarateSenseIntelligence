----------------------------------------------------------------------
----------------------------------------------------------------------
----------------------------------------------------------------------
----------------------------------------------------------------------
README.txt		KarateSenseIntelligence
----------------------------------------------------------------------
----------------------------------------------------------------------
----------------------------------------------------------------------
----------------------------------------------------------------------

This is the README.txt of the KarateSenseIntelligence (KarateSenseI) project. The KarateSenseI projects aims
to provide a environment for Karate athlets to study and quantify their performances. The environment provides 
hardware and software based blocks.

Specification:
 - Perception Neuron System by NOITOM (c) for motion capturing - up to 120 fps
 - Surface reconstruction using Microsofts Kinect (c)
 - real time motion capturing and surface reconstruction
 - real time analysis (time series, key value extraction)
(- real time motion recognition update)


Top abstraction Layer of the environment:

					|--------------------|	
					|		     |
					|   KarateSenseI     |
					|                    |
					|--------------------|
					/		     \
			      	       /		      \
			    	      /			       \
		|--------------------|				|--------------------|					
		|		     |				|		     |				
		|      Hardware      |				|      Software      |
		|                    |				|                    |
		|--------------------|				|--------------------|-----------------------------
		/		     \				/		     \                             \   
	       /                      \			       /		      \                             \
              /                        \		      /			       \                             \
|--------------------| 		|--------------------|       |--------------------|     |--------------------|     |--------------------|
|   PN by NOITOM (c) |		|  Kinect for XboX   |       |   Axis Neuron (c)  |     |   Kinect SDK v1.8  |     |Point Cloud Library |
|(Perception Neuron) |		|     or Windows     |       |     by NOITOM      |     |     by Mircosoft   |     |        v1.6        |
| 		     |		|   by Microsoft (c) |       |                    |     |                    |     |                    |
|--------------------|		|--------------------|       |--------------------|     |--------------------|     |--------------------| 


