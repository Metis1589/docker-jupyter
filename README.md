Dockerfile for Jupyter 
=============================
There are many libs of python, such as anaconda、scikit-learn、elasticsearch、pyes

### To build image by Dockerfile
	docker build -t jupyter:latest .
	
### To run the container
	docker run -p 8888:8888 -d -it  jupyter:latest  /bin/bash  -c "/opt/conda/bin/jupyter notebook --notebook-dir=/opt/notebooks --ip='*' --port=8888" 

 

