
#### Git Server build command

```
docker build -t developerhelperhub/my-cloud-git-server .
```

#### Docker Information

volumn : /var/www/git
port : 80
name : developerhelperhub/my-cloud-git-server


#### Docker run command 

```
docker-compose up -d
```

#### Creating New Git Repository on the Server:

To create a new Git repository test (let’s say) on the Git HTTP server container, run the following command:

```
docker-compose exec my-cloud-git-server mkrepo my-cloud-config-repo
```

#### Git clone example 

git clone http://localhost:8087/my-cloud-config-repo.git

### Reference 

https://linuxhint.com/setup_git_http_server_docker/

