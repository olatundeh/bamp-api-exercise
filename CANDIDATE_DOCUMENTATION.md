
Use this file to include any notes you make about the exercise.
Ensure to commit this file as you work through the exercise.
1.Install Dependencies
npm install -g @nestjs/cli

2.Create new nest app
nest new bamg-app
cd bamg-app

3.Set up main nestjs 
Install the prisma cli as a development dependency
npm add prisma @prisma/client

start the dev server
npm run start:dev

install/add prettier to avoid code formatting errors

4.Create model database
Invoke the prisma cli locally: craete the initial prisma setup 
npx prisma init

run migrate command to apply changes to the database
npx prisma migrate dev --name init

5.Create Prisma service
create prisma.service.ts

6.Create service

create files
team.sevice.ts

Add methods for create, read, update and delete.

7.Create controller
create team.controller.ts which defines all the API route for the team entity

8.Create module
