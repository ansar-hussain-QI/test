* Environment variable : User need to configure a few environment variables as mention below table 

| Variable Name			 | Required/Optional| Description           		           														  				| Example												 |
|:----------------------:|:----------------:|:-------------------------------------------------------------------------------------------------------------:|:---------------------------------:|
|DB_HOST_NAME	 		 |  Required  		| Database host name			  			  																	|	hkfsdtestdb.cfpk60t8fa9t.ap-southeast-1.rds.amazonaws.com	|
|DB_PORT_NO  	 		 |  Required  		| Database port no						     						 					      					| 	1521	  						|
|DB_SERVICE_NAME  	 	 |  Required  		| Database service name						     					 					      					| 	orcl	  							|
|DB_USER_NAME  	 		 |  Required  		| Database username						     						 					      					|Contact Admin		  							|
|DB_PASSWORD	 	 	 |  Required  		| Database password								 					 						  					|Contact Admin 		  							|
|GRPC_SERVER_URL	 	 |  Required  		| Full gRPC's url with http server and port number											  					| http://grpc_server:5000 			|
|GRPC_RECONNECTION_TIME	 |  Optional		| Waiting time (in seconds) before reconnecting to gRPC server if there is a lost connection, default value 10	| 10 		 
