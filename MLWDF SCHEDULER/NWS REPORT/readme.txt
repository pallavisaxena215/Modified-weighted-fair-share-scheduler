Add the following files in ns-3-dev/src/nr/model
1. nr-mac-scheduler-tdma-m_lwdf.cc
2. nr-mac-scheduler-tdma-m_lwdf.h
3. nr-mac-scheduler-ue-info-m_lwdf.cc
4. nr-mac-scheduler-ue-info-m_lwdf.h

Replace the following files in ns-3-dev/src/nr/model with the one provided by us.
1. nr-mac-scheduler-ns3.cc
2. nr-mac-scheduler-ns3.h

Replace the following files in ns-3-dev/src/traffic-control/model 
1. pie-queue-disc.cc
2. pie-queue-disc.h

Replace the original wscript file in ns-3-dev/src/nr 

Command to run the test file 
./waf --run "scratch/Topology.cc --RngRun=val_of_choice"

To obtain instantaneous throughput graph 
Command to run the test file 
./waf --run "scratch/Throughput.cc --RngRun=val_of_choice"

