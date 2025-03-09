# Function: <code>thermal_zone_device_set_mode</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int thermal_zone_device_set_mode(struct thermal_zone_device * tz, enum thermal_device_mode mode)
```

```json
{
  "name": "thermal_zone_device_set_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588652288,
      "name": "thermal_zone_device_set_mode",
      "external": false,
      "loc": "drivers/thermal/thermal_core.c:492",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_disable",
        "drivers/thermal/thermal_core.c:thermal_zone_device_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588652288,
      "name": "thermal_zone_device_set_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int thermal_zone_device_set_mode(struct thermal_zone_device * tz, enum thermal_device_mode mode)
```

```json
{
  "name": "thermal_zone_device_set_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588538928,
      "name": "thermal_zone_device_set_mode",
      "external": false,
      "loc": "drivers/thermal/thermal_core.c:481",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_disable",
        "drivers/thermal/thermal_core.c:thermal_zone_device_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588538928,
      "name": "thermal_zone_device_set_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int thermal_zone_device_set_mode(struct thermal_zone_device * tz, enum thermal_device_mode mode)
```

```json
{
  "name": "thermal_zone_device_set_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589212944,
      "name": "thermal_zone_device_set_mode",
      "external": false,
      "loc": "drivers/thermal/thermal_core.c:428",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_disable",
        "drivers/thermal/thermal_core.c:thermal_zone_device_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589212944,
      "name": "thermal_zone_device_set_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int thermal_zone_device_set_mode(struct thermal_zone_device * tz, enum thermal_device_mode mode)
```

```json
{
  "name": "thermal_zone_device_set_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590677008,
      "name": "thermal_zone_device_set_mode",
      "external": false,
      "loc": "drivers/thermal/thermal_core.c:430",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_disable",
        "drivers/thermal/thermal_core.c:thermal_zone_device_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590677008,
      "name": "thermal_zone_device_set_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int thermal_zone_device_set_mode(struct thermal_zone_device * tz, enum thermal_device_mode mode)
```

```json
{
  "name": "thermal_zone_device_set_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592342704,
      "name": "thermal_zone_device_set_mode",
      "external": false,
      "loc": "drivers/thermal/thermal_core.c:437",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_disable",
        "drivers/thermal/thermal_core.c:thermal_zone_device_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592342704,
      "name": "thermal_zone_device_set_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int thermal_zone_device_set_mode(struct thermal_zone_device * tz, enum thermal_device_mode mode)
```

```json
{
  "name": "thermal_zone_device_set_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592769216,
      "name": "thermal_zone_device_set_mode",
      "external": false,
      "loc": "drivers/thermal/thermal_core.c:432",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_disable",
        "drivers/thermal/thermal_core.c:thermal_zone_device_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592769216,
      "name": "thermal_zone_device_set_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
int thermal_zone_device_set_mode(struct thermal_zone_device * tz, enum thermal_device_mode mode)
```

```json
{
  "name": "thermal_zone_device_set_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thermal_zone_device_set_mode",
      "external": false,
      "loc": "drivers/thermal/thermal_core.c:482",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_disable",
        "drivers/thermal/thermal_core.c:thermal_zone_device_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593520496,
      "name": "thermal_zone_device_set_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    },
    {
      "addr": 18446744071597762599,
      "name": "thermal_zone_device_set_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int thermal_zone_device_set_mode(struct thermal_zone_device * tz, enum thermal_device_mode mode)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
