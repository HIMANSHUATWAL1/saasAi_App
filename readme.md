![CodeRabbit Pull Request Reviews](https://img.shields.io/coderabbit/prs/github/HIMANSHUATWAL1/saasAi_App?utm_source=oss&utm_medium=github&utm_campaign=HIMANSHUATWAL1%2FsaasAi_App&labelColor=171717&color=FF570A&link=https%3A%2F%2Fcoderabbit.ai&label=CodeRabbit+Reviews)

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

7. for pushing and watching changes we create commands on package.json using npn run we can use them ---->

 "db:push": "drizzle-kit push",
 "db:studio": "drizzle-kit studio"




# 03_Authentication setup-------------->

1. Integrate better auth. By using better.auth.com website.
(npm install better-auth@1.2.8)

2. follow given steps for installation to setup.

3. create better auth instance.

4. configure auth schema (-push changes)

here app/api/auth/[...all]/route.ts  

here [...all] mean all type of route (universal)

5. create basic UI   (-- create new user)

about all better-auth working exprience (signUp,signOut)





