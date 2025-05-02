## STEPS TO BUILD THE APPLICATION 

1. cd into the project directory

2. docker compose build

3. docker compose up -d

4. Access the application through: <https://localhost:3000>
***You can check it with this docker command: docker logs docker-container-id***


## STEPS TO RUN THE KUBERNETES NODE-POSTGRES-APP 

a. cd into kubernetes directory

b. Run 'kubectl apply -f postgres.yaml

c. Run 'kubectl apply -f node-app.yaml

***HOW TO ACCESS THE APPLICATION IN THE URL***
i) kubectl port-forward service/node-app 3000:3000
***NB: Keep this command running while accessing the application in the browser URL.

ii) copy 'http://localhost:3000' into the URL
