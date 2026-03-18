# tb4_sim_jazzy
turtlebot4 simulation repository based on Collaborative Robotics Lab works

## Clone the repo

On the terminal run the following command to clone the repo

```sh
git clone https://github.com/BatCarlos/tb4_sim_jazzy.git
```

## Start the workspace based on Simulation

Enter the folder

```bash
cd tb4_sim_jazzy
```

Pull the latest docker containers
```bash
docker compose pull
```

## Run the containers

Start the docker containers
```bash
xhost +local:root
docker compose up
```
Then you will be able to visualize the simulation and the rviz2 for mapping and navigation.

You can control the turtlebot4 via CLI with teleop_twist_keyboard ou via gazebo GUI.

