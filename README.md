Amazon Mexa
Install MongoDB Compass
Create new txt file on main folder
Add this to the file you just created ¨MONGODB_URL=mongodb://localhost/amazonmexa¨
Change file name to .env
On main folder :
npm install
npm start
On frontend Folder:
npm install
npm start

Once you open the site for the first time, you´ll need to load items and saved users from the backend so go to
http://localhost:5000/api/users/seed
http://localhost:5000/api/products/seed

Reload the website and products and default users should be working.

admin user:
admin@example.com
1234

Regular user:
roberto@example.com
1234
