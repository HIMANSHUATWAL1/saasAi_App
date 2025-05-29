# <------------------- PROJECT INITIALIZATION ------------------>



#  01_setup ----------->

1. install nextjs --> npx create-next-app@latest 

with typescript + reactjs + tailwind 

2. install shadcn for UI component 

using command--> npx shadcn@latest init 

3. for adding component we have to run command-->

npx shadcn@version add --all

4. @ sign mean (..) mean root directory 

5. then push the changes  in new git repo.



# 02_Database----------------->
Add-->install 

1. Add a postgreSQL database (Neon)

2. Add DrizzelORM (version 0.43.1)

3. Add drizzle-kit (version 0.31.1) 

4. Add tsx (version 4.19.4)

5. follow all the directions given by drizzle orm 

6. for continious updates checking we use command--->

          npx drizzle-kit studio 

7. for pushing and watching changes we create commands on package.json using npn run we can use them -->

 "db:push": "drizzle-kit push",
 "db:studio": "drizzle-kit studio"



