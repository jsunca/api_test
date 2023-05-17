# api_test

Follow the instruction at https://dev.to/myogeshchavan97/how-to-easily-create-and-host-your-own-rest-api-without-writing-a-single-line-of-code-2np4

mkdir c:\api_test
npm init -y
npm install json-server
# create a db.json file with content:
{
  "users": [
    {
      "id": 1,
      "name": "David",
      "age": 30
    },
    {
      "name": "John",
      "id": 2,
      "age": 40
    }
  ]
}

change package.json file and ad scripts section: 
"scripts": {
  "start": "json-server db.json"
}

run and see http://localhost:3000/
git init .
git remote add origin https://github.com/jsunca/api_test.git
git add -all . 
git commit - m "test"
git push origin master

Check api page:
https://my-json-server.typicode.com/jsunca/api_test
