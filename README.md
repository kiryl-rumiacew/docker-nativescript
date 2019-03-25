nativescript-cli
This repo includes nativescript running on ubuntu-18.04 LTS.
Its includes android sdk and latest node8.x js.
It allows you with a single command to build your entire nativescript application for android.
Perfect for CI environments like jenkins or bitbucket pipelines.
Just go to the root of your nativescript application and run



running android with version/5.1.1-28.0.3-1.15.2:

docker run --privileged -v /dev/bus/usb:/dev/bus/usb -v $(pwd):/app -it scratchy/nativescript-cli:5.1.1-28.0.3-1.15.2 bash

