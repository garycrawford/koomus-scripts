# Koomus Scripts

This repo contains scripts which will help to manage the koomus runtime containerised environment.

Clone the repo, symlink into a `bin` directory and ensure the bin is on the PATH.

Assuming that Graphite is running (and listening for metrics on 2003) you will be able to execture:

    `conrun {docker_image} {command}`

CPU and memory stats will be sent to Graphite and the container will be cleaned and removed on exit.
