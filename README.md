# 21-days-of-dev

Reading and Writing JSON (sync and async)

https://stackabuse.com/reading-and-writing-json-files-with-node-js/

Converting TypeScript to JavaScript

https://www.tutorialsteacher.com/typescript/converting-javascript-to-typescript

Playing with and scaling the pizza-portal application

https://github.com/abhishekr7/pizza-portal

Converting pizza-portal into inventro

Understanding the SQL part 

Comparison of NoSQL options in the market
https://www.trustradius.com/nosql-databases


Redis => Mid Size companies
https://www.trustradius.com/products/redis/reviews

MongoDB => Trusted by everyone
**general** 

CouchBase => Enterprises Mid Size companies
https://www.trustradius.com/products/couchbase-data-platform/reviews

DynamoDB => Very few users in all sizes
https://www.trustradius.com/products/amazon-dynamodb/reviews

IBM Cloudant => Very few
https://www.trustradius.com/products/cloudant/reviews

**Chart.js**
> *Pros*

 1. lightweight

 2. responsive charts

 3. clear documentation

 4. NPM plugin support

> *Cons*

 1. Limited features

What is express ?
> *Web application framework* - 
> Helps to organize your web application into an MVC architecture on the server side

Frames should be avoided at all costs. There are outdated and can cause problems. Use server side scripting instead.

# SQL

**Connect to the SQL server**
```
mysql -u root -p
password: (root)
```
**Select Database**
```
use inventro
```
**Create Table**
```
create table orders (id INT, name VARCHAR(10), quantity INT, purchase_date DATE);
```
**Insert a row**
```
insert into orders values(1, 'test', 0, '2019-11-02');
```
**View table**
```
select * from orders;
```
# Chart Library

**Chart.js** 
> The library contains a set of 6 charts and is 11Kb gzipped, this makes its loading time and page impact low.


Terminate command

1. Ctrl + C

2. lsof -i tcp:<port>

3. kill -9 <PID>

## Async - Await

https://stackoverflow.com/questions/12030248/what-is-the-right-way-to-make-a-synchronous-mongodb-query-in-node-js
