## Notes - June 5, 2019 - Roger Schmidt

- Each step edits the image
- FROM: signifies "base image"
- RUN: edits image
- CMD: how to start the image

- A container that is started and then killed, can be restarted with the same state

- For dev mode, you can utilize your pwd to auto refresh the container files (the container is pointed at your pwd).
- You can make an exception that says you want to look for something within the container only (i.e. node_modules in the container, rather than pwd)
