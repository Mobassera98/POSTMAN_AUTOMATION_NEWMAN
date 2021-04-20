# POSTMAN_AUTOMATION_NEWMAN
Write API Tests with Postman and Newman

## Postman

•	A postman is a good tool that we mostly use to quickly test APIs to see the result returned by them, but it's way more powerful than that.

•	Making API is hard but Postman makes it simpler, easier.

•	You can simply test any API and see the response immediately.

•	You can create a collection of API endpoints and call them whenever you want to see the responses.

## Newman

•	We Write Tests in Postman, then export the collection and use Newman to run them directly from the command line.

## Working procedure

1.	First, we need to be Download & install Postman.
2.	After that, Download & install Nodejs.
3.	Clone or Download POSTMAN_AUTOMATION_NEWMAN Repository & import that collection file into our Postman.
4.	Open Powershell window here (POSTMAN_AUTOMATION_NEWMAN Folder) using shift + right-click.
5.	Check prerequisite install node version using ( node --version )
6.	Now need to install Newman using ( npm i newman )
7.	Run report using Newman:
npx newman run ./collection/customer_api_collection.json -e ./collection/customer_api_env.json -n 1 [Here -e = Environment, -n = Iteration Number]
8.	Now, if you want to generate an HTML report:
( npm i newman-reporter-htmlextra )
( npm test )


