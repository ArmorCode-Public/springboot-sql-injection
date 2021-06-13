# springboot-sql-injection


Building app
> ./build

Running app
> ./run


After application starts, run below from cmd-line for sql-injection

curl "http://localhost:8080/test?name=TestUser1'%20or%20'1'='1"