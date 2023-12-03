# Tabular Data Generation

Pre-requisite: should have python libraries used in code installed in the system's python environment

Note: Model used is a test model similar to actual one used in research by me but not the same

## How to Run:

Clone the project

```bash
  git clone https://github.com/tanav2202/Tabular-Data-Generation
```

Go to the project directory

```bash
  cd Tabular-Data-Generation
```

Run the container and build command.

```bash
  docker compose up --build
```

## Local Demo (of Backend System) : 

1. Visit http://127.0.0.1:5000/docs to see all the CRUD operations inside the API
3. Screen should look like this:
![image](https://user-images.githubusercontent.com/78900552/182476735-f190571b-8d0e-4762-8998-55f7d310ac89.png)

4. Execute the DELETE operation to remove pre-existing files (if present)
5. Execute the PUT (/load data) opertation to add .csv file then execute

Dataset used for this model: https://www.kaggle.com/datasets/brunogrisci/breast-cancer-gene-expression-cumida

![image](https://user-images.githubusercontent.com/78900552/182476975-3102256b-f4be-442f-9987-1ed2f72160b3.png)

6. Then use GET (/train) to run the model
7. output.csv file is generated after the model is run. 
8. To download use the last GET (/output) operation
![image](https://user-images.githubusercontent.com/78900552/182477518-dd586e27-8de8-4f1a-bf41-91bd6c838ee2.png)

