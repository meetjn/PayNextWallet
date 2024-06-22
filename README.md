# Turborepo starter

This is an official starter Turborepo.

## Architecture

![alt text](archtitecture.png)


# Starting the project locally localhost 3001 only

Run the following command in the packages/DB folder 

start the postgres db locally using the docker by running command 


sudo docker run -e POSTGRES_PASSWORD=mysecret -d -p 5433:5432 postgres


npx prisma migrate dev

npx prisma generate

npx prisma db seed

npx prisma studio


NOTE: Make sure you copy over all the .env.example file to .env right next to it in the same repo 