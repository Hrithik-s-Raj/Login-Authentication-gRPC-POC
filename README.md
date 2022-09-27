# Login-Authentication-gRPC-POC
Microservice for registering a new user,getting the user,verifying the JWT token of the user,Login  into the app 

Step 1:

go to userService and run => npm install - which will install all the dependencies required

Step 2: 
       run npm start 
       
step 3:
   As like normal apis we cant test the apis in Postman,insomnia etc here iam using a RPC testing tool which is "BLOOM RPC"
   
   "https://github.com/bloomrpc/bloomrpc/releases" - download the bloom rpc tool from this link
   
   
step 4:
  Open BloomRPC and import the protobuf which is in the protos/user/user.proto
  
  <img src="https://i.ibb.co/TK1gg32/Screenshot-2022-09-27-101828.png"/>
  
Step 5: the rpc calls will be listed and we can test each by passing the params
   
   
