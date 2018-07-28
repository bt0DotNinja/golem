# golem
Web server built from scratch, for use with OpenShift &amp; other tools that include automatic certificates

## Quickstart
front-end: HTML5, CSS

back-end: Go

### How To Run
From your terminal, navigate to the repository and type the following commands for a local server.

```
cd src
go run main.go
```

Go to [localhost:8080](http://localhost:8080) in your browser and you will see the website.

For production use, for example as your blog engine, it's recommended to use `go install` and then run the built executable that is located in the `bin`
folder of the repository.
