## End to End ML-modular project with deployment on Azure cloud with Github Actions


docker build -t testmlproject.azurecr.io/mltest:latest .

docker login testmlproject.azurecr.io

docker push testmlproject.azurecr.io/mltest:latest