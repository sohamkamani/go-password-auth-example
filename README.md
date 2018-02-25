# Password authentication in Go

Read the blog post [here](https://www.sohamkamani.com/blog/2018/02/25/golang-password-authentication-and-storage/).

This repository is an implementation of simple password based authentication and storage in Go.
Passwords are stored in a Postgres DB instance.

To run the application:
- Create a postgres DB and a `users` table using the [users.sql](/sohamkamani/go-password-auth-example/blob/master/users.sql).
- Start the application with the commands: `go build` and `./go-password-auth-example`
- Test the application with the requests in the [test.http](/sohamkamani/go-password-auth-example/blob/master/test.http) file

