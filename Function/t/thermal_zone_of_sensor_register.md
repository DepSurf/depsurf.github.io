# Function: <code>thermal_zone_of_sensor_register</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct thermal_zone_device * thermal_zone_of_sensor_register(struct device * dev, int sensor_id, void * data, const struct thermal_zone_of_device_ops * ops)
```

```json
{
  "name": "thermal_zone_of_sensor_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501008592,
      "name": "thermal_zone_of_sensor_register",
      "external": true,
      "loc": "drivers/thermal/of-thermal.c:484",
      "file": "drivers/thermal/of-thermal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501008592,
      "name": "thermal_zone_of_sensor_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct thermal_zone_device * thermal_zone_of_sensor_register(struct device * dev, int sensor_id, void * data, const struct thermal_zone_of_device_ops * ops)
```

```json
{
  "name": "thermal_zone_of_sensor_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233520444,
      "name": "thermal_zone_of_sensor_register",
      "external": true,
      "loc": "drivers/thermal/of-thermal.c:484",
      "file": "drivers/thermal/of-thermal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_register",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233520444,
      "name": "thermal_zone_of_sensor_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct thermal_zone_device * thermal_zone_of_sensor_register(struct device * dev, int sensor_id, void * data, const struct thermal_zone_of_device_ops * ops)
```

```json
{
  "name": "thermal_zone_of_sensor_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294488160,
      "name": "thermal_zone_of_sensor_register",
      "external": true,
      "loc": "drivers/thermal/of-thermal.c:484",
      "file": "drivers/thermal/of-thermal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294488160,
      "name": "thermal_zone_of_sensor_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct thermal_zone_device * thermal_zone_of_sensor_register(struct device * dev, int sensor_id, void * data, const struct thermal_zone_of_device_ops * ops)
```

```json
{
  "name": "thermal_zone_of_sensor_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277757798,
      "name": "thermal_zone_of_sensor_register",
      "external": true,
      "loc": "drivers/thermal/of-thermal.c:484",
      "file": "drivers/thermal/of-thermal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277757798,
      "name": "thermal_zone_of_sensor_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct thermal_zone_device * thermal_zone_of_sensor_register(struct device * dev, int sensor_id, void * data, const struct thermal_zone_of_device_ops * ops)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct thermal_zone_device * thermal_zone_of_sensor_register(struct device * dev, int sensor_id, void * data, const struct thermal_zone_of_device_ops * ops)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct thermal_zone_device * thermal_zone_of_sensor_register(struct device * dev, int sensor_id, void * data, const struct thermal_zone_of_device_ops * ops)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct thermal_zone_device * thermal_zone_of_sensor_register(struct device * dev, int sensor_id, void * data, const struct thermal_zone_of_device_ops * ops)
```
</details>
</li>
</ul>
