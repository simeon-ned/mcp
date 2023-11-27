# Practices

## Setup

For the sake of easier setup, we have introduced a `devcontainer` configuration for VSCode. This allows you to run the code in a containerized environment, without having to install anything on your local machine.

If it is not a option for you, there is an option running docker from command line:

```bash
docker run -it \
    --net host \
    -e PYOPENGL_PLATFORM=osmesa \
    -e MUJOCO_GL=osmesa \
    -e LOCAL_USER_ID=$(id -u) \
    -e DISPLAY=$DISPLAY \
    -e QT_X11_NO_MITSHM=1 \
    -v /tmp/.X11-unix:/tmp/.X11-unix \
    robotlev/mcp:latest \
    /bin/bash
```
