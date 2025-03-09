# Function: <code>thermal_zone_device_register_with_trips</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct thermal_zone_device * thermal_zone_device_register_with_trips(const char * type, struct thermal_trip * trips, int num_trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register_with_trips",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thermal_zone_device_register_with_trips",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1195",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596309131,
      "name": "thermal_zone_device_register_with_trips.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071592347808,
      "name": "thermal_zone_device_register_with_trips",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct thermal_zone_device * thermal_zone_device_register_with_trips(const char * type, struct thermal_trip * trips, int num_trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, const struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register_with_trips",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thermal_zone_device_register_with_trips",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1204",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596838485,
      "name": "thermal_zone_device_register_with_trips.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071592774208,
      "name": "thermal_zone_device_register_with_trips",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1641
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct thermal_zone_device * thermal_zone_device_register_with_trips(const char * type, struct thermal_trip * trips, int num_trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, const struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register_with_trips",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thermal_zone_device_register_with_trips",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1275",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/thermal/thermal_core.c:thermal_tripless_zone_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597762620,
      "name": "thermal_zone_device_register_with_trips.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593520864,
      "name": "thermal_zone_device_register_with_trips",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1585
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct thermal_zone_device * thermal_zone_device_register_with_trips(const char * type, struct thermal_trip * trips, int num_trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct thermal_zone_params * tzp</code> ➡️ <code>const struct thermal_zone_params * tzp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
