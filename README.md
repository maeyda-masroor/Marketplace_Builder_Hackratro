
[
](https://github.com/maeyda-masroor/my-appv1)

this is github where all work is done related to coding

Starting from day 1 we have provide business model and schema 
in day 2 we provide technical information related to functional requirement
In day 3 -- Api integration was done using Mock Api by using customerize Api 
1-STEP FOR MAKING CUSTOMIZE API 
1-GO TO CHATGPT give prompt to make 20 dataset if u dont have any dummy data accroding to schema provide 
2-And go to application where you will create API->prodcut->route.ts file
#note if u have more than one dataset u need to make another route like Api-> category ->routes
file folder strcutrue 

API
-- PRODUCT 
------ route.ts
-- CATEGORY 
------ route.ts

Now make json file in public folder 

App
--public
----category.json
----product.json

now use route handling in this 

deployed this code into vercel and obtain vercel link to put in folder

script
---importProduct.mjs
Remember to use exact feild in json and schema so to link each other 
Remmeber its not easy to delete data from sanity so import it wisely 
insert command in package.json 
"import-data":"node script/import-data"

fetch whole data from sanity using GQPL queries 

in day4 
we make dynamic routing 
a link in category was made and for linking url with data we use _id of category and since category was reference in product we destructured the of category and link product with it
a add to cart was added using context API and localstorage
a search bar was also used by extracting product and filtering on input bases

In day 5 
testing was use in cypress and performnce testing

In day 6 
staging vercel link was created 
step to note
1-use vercel link in cors in sanity ->project->api -> 
2- staging link checkout 
vercel setting 
adding enviournment variable





