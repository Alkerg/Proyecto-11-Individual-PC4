# Contribuciones de Albert Argumedo en el [Repositorio](https://github.com/Software-Dev-CC3S2-Team-11/PC4)

## Sprint 1
- **Jun 22, 2025**: Modifiqué el `.gitignore` para omotir ciertos archivos generados por python 
  Commit: `feat: add issue template and improve .gitignore`  
  Commit ID: `f3d761ce3a9a8aebf645ad64b49ef196d78e9855`

  - **Jun 24, 2025**: Creé un servicio de autenticación usando FastAPI con JWT 
  Commit: `feat: add basic auth service methods and endpoints`  
  Commit ID: `9a58530c9825eead8aa5a56ea180a9b7cb3c77da`

## Sprint 2

- **Jun 26, 2025**: Añadí los archivos `docker-compose` y programé la lógica básica del orquestrador python
  Commit: `feat: add Dockerfile, docker-compose files for services and env_orchestrator.py`  
  Commit ID: `0fa164adaed4048fe27ce7583fce41523d3c3270`

- **Jun 27, 2025**: Añadí el servicio de autenticación  
  Commit: `feat: add auth service`  
  Commit ID: `2394f102bd04dae742924ce9328cf61eed47d80d`

- **Jun 27, 2025**: Mejoré el orquestrador, separando los comandos para cada servicio
  Commit: `chore: separate services in CLI orchestrator`  
  Commit ID: `748fde5c9eeea595127f0ac51cbefdc281e99844`

- **Jun 27, 2025**: Creé los archivos `.yaml` que sirven como manifiesto para desplegar contenedores en kubernetes 
  Commit: `feat: add kubernetes manifest files`  
  Commit ID: `fc66f102e94bc3dedf5810d68cb989f9fd6658a4`

- **Jun 27, 2025**: feat: Añadí el manifiesto para kubernetes respecto del servicio de autenticación  
  Commit: `feat: add auth_service manifest for minikube`  
  Commit ID: `1917f804677bc4bbc814cf1734496d8f37e5153e`

- **Jun 27, 2025**: Añadí comandos al orquestrador para desplegar servicios de kubernetes
  Commit: `chore: update CLI to manage deplyment using kubernetes`  
  Commit ID: `fd4106a84f4a265e2ae5f9f18a843eb36779962b`

- **Jun 28, 2025**: Hice merge de la rama `feature/secrets-configmaps-env` en la rama `feature/minikube-setup`
  Commit: `Merge branch 'feature/secrets-configmaps-env' into feature/minikube-setup`  
  Commit ID: `7dbe379f97341ba84bb79068eebf4b90f4fa13d2`

- **Jun 29, 2025**: Mejoré el script python que genera los configmaps y secrets adecuandolo a cada entorno 
  Commit: `chore: update env_secrets_configmaps to read environment variables using a dictionary and include db-env`  
  Commit ID: `b8c81d5adc9cf5240b61b36dc75a2e18c14191f2`

- **Jun 29, 2025**: Apliqué los secrets y configmaps generados por un script a los manifiestos de kubernetes 
  Commit: `feat: kubernetes manifests now can read environment variables from configmaps`  
  Commit ID: `15e0f1a18a4c5a2f4dba873e64692d6bcebb1c13`

- **Jun 29, 2025**: Hice una corrección a los manifiestos de kubernetes para leer las variables de entorno  
  Commit: `fix: correction to acces environment variables in kubernetes manifest`  
  Commit ID: `91f7795f613662b58a8f96b42852fc3da92009c9`

## Sprint 3

- Elaboré los gráficos Burn up y Burn down
  
