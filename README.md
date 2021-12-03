# publisher-subscriber
The ROS publisher/subscriber example packaged as a snap, based on ROS Noetic and Ubuntu Core 20. Strictly confined.
This example is available on ROS wiki, [here](http://wiki.ros.org/ROS/Tutorials/WritingPublisherSubscriber%28python%29).

## build
Just launch ```snapcraft``` from top dir, it will create the snap ```publisher-subscriber_0.1_xxxx.snap```

## install
```
snap install publisher-subscriber_0.1_xxxx.snap --dangerous
```

## run
Open a shell then launch roscore
```
publisher-subscriber.roscore
```
Open a shell then launch the talker
```
publisher-subscriber.talker
```
Open a shell then launch the listener
```
publisher-subscriber.listener
```
