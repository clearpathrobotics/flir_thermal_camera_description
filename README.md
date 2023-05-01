# flir_thermal_camera_description
URDF files for the Flir A400/A700 camera

## Usage

To add the URDF to your robot, instantiate it as follows, substituting `front_mount` as appropriate for your robot:

```xml
<xacro:include filename="$(find flir_thermal_camera_description)/urdf/flir_thermal_camera.urdf.xacro" />

<xacro:flir_thermal_camera prefix="a400" parent_link="front_mount">
  <origin xyz="0 0 0" rpy="0 0 0" />
</xacro:flir_thermal_camera>
```
