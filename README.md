

## For Running `RestAPI-SpringBoot-BoilerPlate` project, certain things needs to be available

### Setting up Couchbase
- Make sure couchbase is running in your system. 
- If you are using couchbase software then
  - Go to url http://localhost:8091, and create new cluster and name it as `Eagle`. Provide username as `Administrator`and password as `password`.
  - If cluster already created then continue to next step.
  - Login to the cluster using credentials username: `Administrator`, password: `password`
  - Create a new user with username same as bucket name mentioned `application.properties` file(`spring.couchbase.bucket.name`) and password as `jigsaw` and provide Full admin access.
  - Logout from Admin account and login to `travel-sample` user account.
  - Create a new bucket and name it as `travel-sample`.
 - Thats it for setting up Couchbase.
