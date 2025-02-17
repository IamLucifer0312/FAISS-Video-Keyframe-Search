# Prerequisites

Before you run the project, please make sure you have set up all the following:

1.  This project uses Docker to run. If you have not installed Docker Desktop, please install from [here](https://www.docker.com/products/docker-desktop/).

2.  At the root directory, create a `data` and `out` folder. Put all relevant data in the `data` folder. The `out` folder should be kept empty.

3.  Make sure to open Docker Desktop before running. Otherwise, you will get an error saying Docker engine hasn't started yet.

# Running the Project

```bash
# Run the services
docker-compose up --build

# Stop the services
docker-compose stop

# Remove the services
docker-compose down
```

# Project Description:  
- This project builds an Machine Learning System for video similarity search.  
- The FAISS library pre-trained model is employed and tuned to handle clip embeddings created from video keyframes. The system can recognize patterns in these keyframes and search for similar videos from the data source.  
- Technology and Skills used: FAISS, Torch, CUDA, Tensorflow, Frontend and Backend Development, etc.  
