# BoilerPlate Code

- Graphql Yoga Server
- Prisma
- Prisma-client-lib
- Postgress
- Docker 

# Run required services

Copy the `.env.example` and rename it to `.env`.

```sh
 # first  run this
 ENV_FILE=.env docker-compose -f docker-compose.prisma.yml  up --build -d
 
 # then run this. 
 ENV_FILE=.env docker-compose -f docker-compose.prisma.yml -f docker-compose.yml up --build

```
