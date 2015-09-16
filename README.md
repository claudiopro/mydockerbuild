# mydockerbuild

Repo for the exercise of the [getting started with Docker](https://docs.docker.com/mac/started) tutorial.

```
 ________________________________________ 
/ "Once they go up, who cares where they \
| come down? That's not my department."  |
|                                        |
\ -- Werner von Braun                    /
 ---------------------------------------- 
    \
     \
      \     
                    ##        .            
              ## ## ##       ==            
           ## ## ## ##      ===            
       /""""""""""""""""___/ ===        
  ~~~ {~~ ~~~~ ~~~ ~~~~ ~~ ~ /  ===- ~~~   
       \______ o          __/            
        \    \        __/             
          \____\______/   
```

This repo contains a Dockerfile which performs the following steps:

* Downloads the [whalesay image](https://hub.docker.com/r/docker/whalesay/), a variation of the popular [cowsay](https://github.com/schacon/cowsay) Linux program
* Installs the `fortune` program via `apt-get` (this image is based on Ubuntu)
* Feeds the output of `fortune` to `cowsay`, showing the random quote in the balloon uttered (???) by the whale           

The repo provides scripts to build and run the image

# Build

Execute the following command:

```bash
./build.sh
```

# Run

Execute the following command:

```bash
./run.sh
```

# License

MIT

