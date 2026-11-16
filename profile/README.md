<p align="center">
  <img src="https://vizmini2.github.io/_static/vizmini2.svg" alt="VizMini2" width="120">
</p>

<h1 align="center">VizMini2</h1>
<p align="center"><b>ROS 2 in your pocket, and on your desk.</b></p>

<p align="center">
  <a href="https://vizmini2.github.io/">Documentation</a> ·
  <a href="https://vizmini2.github.io/getting-started/install.html">Install on Android</a> ·
  <a href="https://vizmini2.github.io/getting-started/desktop.html">The PC app</a> ·
  <a href="https://vizmini2.github.io/getting-started/demo.html">Try the demo</a> ·
  <a href="https://vizmini2.github.io/changelog.html">Changelog</a> ·
  <a href="https://github.com/VizMini2/VizMini2">Source code</a> ·
  <a href="https://github.com/sponsors/Juancams">Sponsor</a>
</p>

---

VizMini2 lets you **see, drive and inspect ROS 2 robots from an Android phone or a Linux PC**,
from one code base: both apps have the same tabs and settings, and your tabs, profiles and layouts
move freely between them. It talks to your robots directly over your network (DDS), with no bridge
or server on the robot; Zenoh and foxglove_bridge work too.

- **See**: 3D view with 33 RViz display types, cameras and H.264/H.265 video, the TF tree, the node
  graph, GPS maps and your own dashboards.
- **Drive**: on-screen joysticks, a gamepad or the keyboard, with safety stops; Nav2 goals and
  waypoints from the map.
- **Move arms**: plan and execute with MoveIt, and switch or command ros2_control controllers.
- **Act**: buttons and sliders that publish, call services or send action goals.
- **Maps**: save maps, drive SLAM Toolbox, clear costmaps and draw keepout and speed zones for Nav2.
- **Plot and watch**: plots with formulas and Lua, gauges, and alerts when a value crosses a limit
  or a topic goes silent.
- **Inspect**: nodes and parameters, topics with echo and rate, services, actions and lifecycle nodes.
- **Record**: MCAP bags compatible with `ros2 bag`, and screen videos to show what happened.
- **Share and migrate**: profiles as files or QR codes; tabs to and from RViz 2 files (`.rviz`) and
  layouts of other tools.

No account needed. Not sure yet? The **demo** runs a simulated robot entirely inside your phone,
with everything working and no robot needed.

### Requirements

| | |
|---|---|
| Phone | Android 8.0 (API 26) or newer, OpenGL ES 3 |
| PC | Ubuntu 20.04 or newer, x86-64, with an OpenGL driver: the `.deb` (no ROS 2 needed on the PC) or `ros2 run vizmini2 vizmini2` |
| Robot | ROS 2 Foxy, Humble, Jazzy, Kilted or Lyrical |
| Middleware | Fast DDS or Cyclone DDS (everything: topics, services, actions, parameters, lifecycle), Zenoh through the robot's router, or any other through foxglove_bridge |
| Network | The robot's network, or a VPN / Discovery Server; with Zenoh or foxglove_bridge, any network that reaches the robot's port |

### Help

- Something not working? Start with [Troubleshooting](https://vizmini2.github.io/help/troubleshooting.html)
  and [Known limitations](https://vizmini2.github.io/help/limitations.html).
- Found a bug or have an idea? [Open an issue](https://github.com/VizMini2/VizMini2/issues/new/choose)
  or see [Contact and support](https://vizmini2.github.io/help/contact.html).
- Want to build it or help? See the [developer guide](https://vizmini2.github.io/developers/index.html)
  and [CONTRIBUTING.md](https://github.com/VizMini2/VizMini2/blob/main/CONTRIBUTING.md).

VizMini2 is free software (GPL-3.0) built in spare time. If it helps you with your robots, you can
support it on [GitHub Sponsors](https://github.com/sponsors/Juancams).
