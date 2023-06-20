SRE TEST
Please answer in simple, systematic
Share your answer in github/or any repository to dono@onboardcrewapp.com
1. how do you connect domain to kubernetes cluster? please write the process step. can use assumption (mydomain.com as an domain)
2. modify docker-compose.yaml to map given react application to nginx
version: '3.8' services:
web: build:
context: ./
      target: runner
    volumes:
- .:/app
command: npm run dev ports:
- "3000:3000" environment:
      NODE_ENV: development
3. assuming you have wildcard certificate do you insert certificate to that kubernetes cluster. please answer in steps
4. please provide simple grafana installation guide within kubernetes cluster?
5. how do you ensure security in between server?
6. assuming you are running an kubernetes or any orchestration engine, and suddenly the entire system was down, what are thought process and steps you will do and prevent it from happening?
7. how do you ensure security for database? Provide steps and instruction.
