# learn-cicd-starter (Notely)

This repo contains the starter code for the "Notely" application for the "Learn CICD" course on [Boot.dev](https://boot.dev).

## Add a new branch

```bash
git checkout -b BRANCH_NAME
```

To push the new branch to GitHub, run:

```bash
git push origin BRANCH_NAME
```

## Local Development

Make sure you're on Go version 1.20+.

Create a `.env` file in the root of the project with the following contents:

```bash
PORT="8080"
```

Run the server:

```bash
go build -o notely && ./notely
```

*This starts the server in non-database mode.* It will serve a simple webpage at `http://localhost:8080`.

You do *not* need to set up a database or any interactivity on the webpage yet. Instructions for that will come later in the course!
