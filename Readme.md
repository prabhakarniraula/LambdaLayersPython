Lambda Layers compatible with python 3.7 including pandas and cx_Oracle libraries

Upload CX_ORACLE and ORACLE_INSTANT_CLIENT to lambda layers directly to connect to ORACLE DB from lambda function in AWS. Upload pandas to use pandas in lambda functions, numpy is included in the lib itself.

All the packages are compiled in Amazon Linux and are compatible with python3.7.

If these zip files doesn't work, try to install required libraries in EC2 instance and package them to upload to lambda function
