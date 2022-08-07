# MergeShards : External Sort (Part 2) - Preventing Resource Leaks

This is a simple Java program that reads in the sorted shard files 
and combines them into a single large, sorted text file.

## Running the code

To compile and run, do:

    javac -cp . MergeShards.java
    java -cp . MergeShards shards/ sorted.txt