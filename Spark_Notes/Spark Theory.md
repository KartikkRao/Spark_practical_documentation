
# What is Apache Spark :

Apache spark is a unified computing engine and set of libraries for parallel data processing on computer cluster

# What is unified: 

All in one is unified all in one platform for data processing and transformation,
spark is designed to support wide range of task over the same computing engine

# Where does the data get stored in spark:

-> spark is limited to the computer resource you provide to it. It does not have its own storage rather uses your cpu rams. That means if you write your logic and then not storing it anywhere then when you shut down your pc ram is volatile all intermediate data will be erased 

-> But its can connect with your various data sources like databses, cloud storages etc and use those as storing the data that is transformed



# What is a computing Engine:

-> when we provide a certain task to our computers it uses its ram and cpu to proces the command convert it to binary and then achieve the results that is a compute engine

-> Spark uses this compute engine to process data   

# What is parallel data processing:

divide the task into different computers in the same cluster achieving faster result.

# Spark architecture is a master-slave architecture 

-> There is one main computer called master 

-> there are several other called slaves 

-> Master control and orchestrate what work a slave has to do and the slave does that work and sends it to the master 


# 3 V's of Big data:

Velocity, variety and volume

# Hadoop vs Spark

	performace:
		Hadoop: Hadoop is slower then spark because it writes the data in disk and 
			reads again from disk to in memory(RAM)
		Spark: Does all computation in memory 
	




