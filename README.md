# Turborepo starter

This is an official starter Turborepo.

## Architecture

![alt text](archtitecture.png)


# Starting the project locally localhost 3001 only

Run the following command in the packages/DB folder 

start the postgres db locally using the docker by running command 

"sudo is for mac os"

sudo docker run -e POSTGRES_PASSWORD=mysecret -d -p 5433:5432 postgres

## Head over to packages/db and then run the following command


npx prisma migrate dev

npx prisma generate

npx prisma db seed

npx prisma studio

Last step:
go to the src repo and run

    npm run dev

this will start the project:

Login in using 1111111111 in the number section

and enter password 'alice'

do the same login in other tab using 2222222222 in the number account

and password 'bob' 
NOTE: Make sure you copy over all the .env.example file to .env right next to it in the same repo 
