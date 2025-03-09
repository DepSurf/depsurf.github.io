# Function: <code>__thermal_zone_device_update</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "__thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592349139,
      "name": "__thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:409",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_mode"
      ],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_mode",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592342208,
      "name": "__thermal_zone_device_update.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
    },
    {
      "addr": 18446744071596309070,
      "name": "__thermal_zone_device_update.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071592350112,
      "name": "__thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "__thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592775777,
      "name": "__thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:404",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_mode"
      ],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_mode",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_trip.c:thermal_zone_set_trip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592768352,
      "name": "__thermal_zone_device_update.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 834
    },
    {
      "addr": 18446744071596838465,
      "name": "__thermal_zone_device_update.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071592776720,
      "name": "__thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "__thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593518191,
      "name": "__thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:459",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_resume",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_mode",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_resume",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_mode",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store",
        "drivers/thermal/thermal_trip.c:thermal_zone_trip_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593515408,
      "name": "__thermal_zone_device_update.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
    },
    {
      "addr": 18446744071597762641,
      "name": "__thermal_zone_device_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593525744,
      "name": "__thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void __thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
