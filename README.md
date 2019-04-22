# cmt-artifacts
## option-market-1.0-SNAPSHOT-distribution.jar  :
  this is market data jar - extract as a zip and find marketdata.sh
  
###run:
  cd option-market-1.0-SNAPSHOT-distribution
  chmod +x marketdata.sh
  ./marketdata.sh   (starts market data and jms borker at tcp://localhost:61616)
  
## options-data-ref-0.0.1-SNAPSHOT.jar
  this is the reference data server - starts rest service 
  also publishes the reference data to a topic - CMT.OPTIONS.REFDATA.TOPIC
 
 ###run:  
  java -jar options-data-ref-0.0.1-SNAPSHOT.jar
  
