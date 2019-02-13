Instruction:

run ’npm install‘ to install all libraries.

run 'npm run seed', and it will automatically creat 5 categories for used goods and also a user account. The username is 'test' and password is '123'. Additionally, it uploads a used switch game named 'zelda legend' in the name of this test account.

run 'npm start'. The url is 'localhost:3000/hannibal'. It's our homepage. You can see all goods listed by categories and you also can search any goods you want.

Click login button. You can either use test account showed above or create a new account to login. After login, click 'Account info' button, where you can edit your account or check/upload/edit/delete any goods that you uploaded before. By the way, If you want to upload a product, you need to prepare a picture. That's necessary. Additionally, login/signup/edit pass takes some time, since we use 'bcrypt' to encode the plain password.

Click logout button to clean the session. Otherwise, it will be cleaned after one hour.
