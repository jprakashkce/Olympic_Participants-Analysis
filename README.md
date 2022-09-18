# Olympic_Participants-Analysis
Analysis of Olympic Participants dataset using Hadoop Map Reduce.

Commands to Execute:


Copy the file from local file system to HDFS:

  >>>hadoop fs -copyFromLocal inputFile /InputFileLocation
  
Run job ( wordcount ):

  >>>hadoop jar jarFile.jar /inputFile /OutputFile

GET command:

  >>>hadoop fs -get /OutputFile
  
