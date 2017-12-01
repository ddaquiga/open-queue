# Open Queue Server Model

compile openQueueing.cpp:

	g++ -c openQueueing.cpp

	g++ -o openQueueing openQueueing.o

run openQueueing.exe

	./openQueueing

In this project, I developed a simulator to model an open single server system. The simulator provides options to choose the random distributions of interarrival time and service time; which can be constant, exponential, or uniform. For each of the nine combinations of interarrival and service times distributions, I compute the average value and standard deviation of these parameters: interarrival time, <service time, wait time, response time, queue length, and utilization.