<p align="center">
  <img src="https://vizmini2.github.io/_static/vizmini2.svg" alt="VizMini2" width="120">
</p>

<h1 align="center">VizMini2</h1>
<p align="center"><b>ROS 2 in your pocket.</b></p>

<p align="center">
  <a href="https://vizmini2.github.io/">Documentation</a> ·
  <a href="https://vizmini2.github.io/getting-started/install.html">Install</a> ·
  <a href="https://vizmini2.github.io/getting-started/demo.html">Try the demo</a> ·
  <a href="https://vizmini2.github.io/changelog.html">Changelog</a> ·
  <a href="https://github.com/sponsors/Juancams">Sponsor</a>
</p>

---

VizMini2 is an Android app to **see, drive and inspect ROS 2 robots from your phone**.
It talks to your robots directly over your network (DDS), with no bridge or server on
the robot.

- **See**: 3D view with 18 RViz displays, cameras, the TF tree, the node graph and your own dashboards.
- **Drive**: on-screen joysticks or a gamepad, with safety stops.
- **Act**: buttons that publish, call services or send action goals; Nav2 goals from the map.
- **Inspect**: nodes and parameters, topics with echo and rate, services, actions and lifecycle nodes.
- **Record**: MCAP bags compatible with `ros2 bag` and Foxglove, and play them back.
- **Share**: robot profiles synced to your account, as files or as QR codes.

Not sure yet? The **demo** runs a simulated robot entirely inside your phone, no account
and no robot needed.

### Requirements

| | |
|---|---|
| Phone | Android 8.0 (API 26) or newer, OpenGL ES 3 |
| Robot | ROS 2 (tested with Jazzy; Humble and newer should work). Fast DDS (`rmw_fastrtps_cpp`) for services, actions, parameters and lifecycle |
| Network | Same Wi-Fi as the robot, or a VPN / Discovery Server |

### Help

- Something not working? Start with [Troubleshooting](https://vizmini2.github.io/help/troubleshooting.html)
  and [Known limitations](https://vizmini2.github.io/help/limitations.html).
- Found a bug or have an idea? [Open an issue](https://github.com/VizMini2/VizMini2.github.io/issues/new/choose)
  or see [Contact and support](https://vizmini2.github.io/help/contact.html).

VizMini2 is free and built in spare time. If it helps you with your robots, you can
support it on [GitHub Sponsors](https://github.com/sponsors/Juancams).
