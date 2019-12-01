# Folder structure

Firstly you want to set up the folder structure. Like most projects this will use two-top-level directories. This will help maintaining the application easier as it develops.

```
mkdir CLI
cd CLI/
mkdir cmd
mkdir pkg
```

Now the folder structure is in place, you will need to make a `main.go` file inside `CLI/cmd`. This will be where the main function lives and where the binary will be built from.

```
cd cmd
touch main.go
```
