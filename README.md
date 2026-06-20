# HelloWorld (.NET)

Simple .NET console application that prints "Hello, world!." 

## Prerequisites

- .NET SDK (recommended: .NET 8.0 or newer). Download from https://dotnet.microsoft.com/.

## Project structure

- HelloWorld/HelloWorld.csproj — project file
- HelloWorld/Program.cs — application entrypoint
- .gitignore

## Build and run

From the repository root:

```bash
# Build
dotnet build HelloWorld

# Run
dotnet run --project HelloWorld
```

You should see:

```
Hello, world!
```

## Create a Git repository and push to GitHub

If you want to push this to a new GitHub repository:

```bash
# Initialize git, add files, commit
git init
git add .
git commit -m "Initial commit: HelloWorld .NET project"

# Create a repo on GitHub (option A: use gh CLI)
gh repo create my-helloworld --public --source=. --remote=origin --push

# OR create the repo on github.com, then:
git remote add origin https://github.com/<your-username>/<repo>.git
git branch -M main
git push -u origin main
```

Replace `<your-username>/<repo>` with your GitHub repo path.
