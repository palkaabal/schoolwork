###############################################################
# Program:
#     Lab 05, Threads
#     Brother Ball, CS345
# Author:
#     Lance Bunch
# Summary:
#     This demonstrates the use of threads to multiply matrices
# Time:
#     Estimated: 7.0 Hrs
#		Actual:    0.0 Hrs
###############################################################

##############################################################
# The main rule
##############################################################
a.out: lab05.cpp
	g++ -o a.out -lpthread lab05.cpp 
	tar -czf lab05.tar makefile lab05.cpp

sampleHello.out: sampleHello.cpp
	g++ -o sampleHello.out -lpthread sampleHello.cpp

sampleParam.out: sampleParam.cpp
	g++ -o sampleParam.out -lpthread sampleParam.cpp

sampleGlobal.out: sampleGlobal.cpp
	g++ -o sampleGlobal.out -lpthread sampleGlobal.cpp

sampleSum.out: sampleSum.cpp
	g++ -o sampleSum.out -lpthread sampleSum.cpp

all: a.out sampleHello.out sampleParam.out sampleGlobal.out sampleSum.out
	
