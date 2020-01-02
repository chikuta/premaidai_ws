# REAMDE

## How to build

```bash
  $ mkdir -p premaidai_ws/src
  $ cd premaidai_ws
  $ catkin init
  $ wget https://raw.githubusercontent.com/chikuta/premaidai_ws/master/premaidai_ws.rosinstall .rosinstall
  $ rosinstall .
  $ rosdep install --from-paths src --ignore-src
  $ catkin build
```