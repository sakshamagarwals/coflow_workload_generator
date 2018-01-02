# coflow_workload_generator

##### python trace_producer.py [Number of coflows] [Alpha] [C] [Source_Dist] [Destination_Dist] 

generates traces with required characteristics. Alpha is the maximum number of senders, C is the intra-coflow contention, Source_Dist is the distribution of number os senders, Destination_Dist is the distribution of data among the destinations

##### python distribution_producer.py [Number of coflows] [Alpha] [C] [Source Dist] [Destination Dist]

generates the output files used to generate distributions of size, width, max/min ratio of size, avg max and min loads, inter arrival time and incast ratio for coflow trace generated
