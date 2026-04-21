this was a project made from a tutorial on Youtube from Techworld with Nana.

In this project we dockerised a nodejs application serving a static webite logging the name of the application passed as an environment variable. All those weren't difficult as i already knew how to do all that, i've already dockerise some applications 

My learning was really in running 'kindof' different version of the application using docker compose or multiple instances of the application still with docker compose using the --scale parameter of the compose command, i didn't know it was possible
```bash
docker compose up --build --scale app1=5
```
Though in the first version it wasn't like that, we were building 3 starting 3 different containers from the same image and passed different variables for the application name 

Nginx was used to loadbalance and serve the application, I also learned how to load balance an application running multiple instances, it was great 