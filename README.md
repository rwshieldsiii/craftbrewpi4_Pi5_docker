# craftbeerpi4_Pi5_docker
Docker configuration for Craftbeerpi4 + Pi5. There is complexity to getting the GPIO pins to work correctly within docker on the Pi5 due to a kernel change. I published this to save others a lot of headaches.

## Running and Configuration

fork the project
```gh repo fork OWNER/REPO```

Bring up the docker container

```docker-compose up```

Navigate to ``<PI_IP_ADDRESS>:8000`` and configure your server

commit your changes to your forked project to preserve them in the event of system failure.

```git add --all```
   ```git commit -m "initial configuration"```


