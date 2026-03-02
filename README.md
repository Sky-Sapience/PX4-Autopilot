# PX4 Drone Autopilot (Workspace README)

**Important:** Before using this project, please follow all setup steps in the [OFFICIAL_README.md](OFFICIAL_README.md). The official readme contains essential instructions for environment setup, dependencies, and initial configuration.

Note: This README assumes you are running this on WSL Ubuntu 22.04, as this is where everything here was tested, might work on native Ubuntu 22.04 as well.

---

## Quick Start: Compile Gazebo with Custom Model

After completing the setup from the official readme, you can compile PX4 SITL with your new Gazebo model using the following command:

```
make px4_sitl gazebo-classic_typhoon_h480_aruco__sks_aruco
```

This will build and launch the simulator with the `typhoon_h480_aruco` model in the `sks_aruco` world in Gazebo Classic.

---

For more details, advanced usage, and troubleshooting, refer to [OFFICIAL_README.md](OFFICIAL_README.md).
