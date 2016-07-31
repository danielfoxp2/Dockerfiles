#Exercism in Docker

Feel confortable to use if you think it can help you somehow.

##Suggestion on How to build it
Inside the directory with this Dockerfile run it:

```bash
sudo docker build -t exercism .
```
##Suggestion on How to run it
To create the container just use:

```bash
sudo docker run -it --name exercism --volumes-from data-volume-container exercism ash
```
##Additional infos
In order to proper use of the exercism app it is needed to configure the API key of your exercism account.
So inside the container just execute:

```bash
exercism configure --key=YOUR-API-KEY-RIGHT-HERE
```
