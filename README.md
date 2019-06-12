# Bank Model

### This project is aimed at the classroom of Artificial Intelligence ministered by Lucas Baggio at FATEC Ribeirao Preto.

***
![alt text](http://www.fatecrp.edu.br/wp-content/themes/fatecrp/dist/img/logo.png)
***

### Requirements
    . Docker
    . python3

### To execute this project, follow the next steps:
    git clone https://github.com/kenjihiraoka/bank_model.git
  
    cd bank_model
  
    docker build -t bank_model .
  
    docker run -v $(pwd):/bank_model -ti -p 8888:8888 --name bank_model bank_model:latest /bin/bash
  
    jupyter notebook --allow-root --ip=0.0.0.0
 
### Copy the output snippet of the above command that has the token:
    Example:
    
    :8888/?token=8819a93d0e0edf8a800589e8f94ddf054be5919f0866cdc5

### And copy in your browser:
    localhost:8888/?token=8819a93d0e0edf8a800589e8f94ddf054be5919f0866cdc5
