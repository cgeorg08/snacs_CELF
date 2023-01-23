# snacs_CELF
More and more insights have been acquired by studying the problem of finding outbreaks in networks. In turn, we investigate it through a series of experiments trying to obtain as much novel information as possible. To begin with, we try to solve the problem based on the following notion; given a dynamic network in which the edges represent the spread in our network, our target is to find the appropriate set of nodes so as to discover the spread in the most successful way. The most successful way is considered to be something really objective and it depends on the application we want to explore. This is because, in different applications, success is sometimes measured in regards to either the speed or the efficiency of finding a near-optimal solution. Therefore, this problem is important to be explored and analyzed since there is high interest to uncover any kind of spread (for example spread of information, fake news or a disease) in any given graph as soon as possible without knowing the source of it. 

Our goal in this paper is to investigate the propagation of a disease. Furthermore, after the retrieval of five realistic datasets, we build graphs and simulate real-life scenarios of virus spread. Thus, the main contributions can be listed with the following order:
+ We implement the CELF algorithm as described in the paper "Cost-effective Outbreak Detection in Networks", which is an efficient approximation algorithm that achieves near-optimal solutions.
+ We implement a different method to simulate the propagation of the virus which is called independent cascades (IC). An independent cascade demonstrates the spread from a source node with the help of a given probability distribution.
+ We perform experiments by changing the construction of the graph and our objective (which is represented by the objective functions). To make it more clear, we construct graphs which have nodes with costs, edges with weights and we, also, introduce timestamps. In that way, we are able to model the spread in our graph as it can be seen in a small community of the real world. Experiments include he change of the objective which means that our goal can change from trying to detect the number of people affected from the disease to the time passed until the disease has been discovered.

The datasets used are the following:
+ "Adolescent health": http://konect.cc/networks/moreno_health/
+ "Infectious": http://konect.cc/networks/sociopatterns-infectious/
+ "Haggle": http://konect.cc/networks/contact/
+ "Malawi": http://www.sociopatterns.org/datasets/contact-patterns-in-a-village-in-rural-malawi/
+ "Hospital": http://www.sociopatterns.org/datasets/hospital-ward-dynamic-contact-network/
