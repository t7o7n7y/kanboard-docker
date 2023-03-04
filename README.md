# kanboard-docker
# This will install kanboard and nginx containers
# 1.Create in yuor directory, directory "public_html":
```
mkdir public_html
```

# 2.Then create a file "index.html":

```
echo "<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Docker Nginx</title>
</head>
<body>
  <h2>Hello Erinin!</h2>
  <h2>This is a test!</h2>
  <h2>Look's like it's work!</h2>

</body>
</html>
> ./index.html
```
# 3.Run docker-compose.yml file from repository:
```
sudo docker compose up -d
```

# or:
```
sudo docker-compose up -d
```

# 4.Now run in your browser:
```
localhost:8080
```

# 5.For Kanboard app run in your browser:
```
localhost:8888/login
```

