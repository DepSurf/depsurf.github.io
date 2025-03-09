# Function: <code>thermal_zone_device_is_enabled</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int thermal_zone_device_is_enabled(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588651814,
      "name": "thermal_zone_device_is_enabled",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:536",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:handle_thermal_trip"
      ],
      "caller_func": [
        "drivers/thermal/thermal_sysfs.c:mode_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588661056,
      "name": "thermal_zone_device_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int thermal_zone_device_is_enabled(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588543572,
      "name": "thermal_zone_device_is_enabled",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:525",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_mode"
      ],
      "caller_func": [
        "drivers/thermal/thermal_sysfs.c:mode_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588544352,
      "name": "thermal_zone_device_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int thermal_zone_device_is_enabled(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589217684,
      "name": "thermal_zone_device_is_enabled",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:472",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_mode"
      ],
      "caller_func": [
        "drivers/thermal/thermal_sysfs.c:mode_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589218432,
      "name": "thermal_zone_device_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int thermal_zone_device_is_enabled(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590680381,
      "name": "thermal_zone_device_is_enabled",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:474",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_mode",
        "drivers/thermal/thermal_core.c:handle_thermal_trip"
      ],
      "caller_func": [
        "drivers/thermal/thermal_sysfs.c:mode_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590681200,
      "name": "thermal_zone_device_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int thermal_zone_device_is_enabled(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592342265,
      "name": "thermal_zone_device_is_enabled",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:487",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_sysfs.c:mode_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592350176,
      "name": "thermal_zone_device_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int thermal_zone_device_is_enabled(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592768413,
      "name": "thermal_zone_device_is_enabled",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:482",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_sysfs.c:mode_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592776784,
      "name": "thermal_zone_device_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int thermal_zone_device_is_enabled(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593518212,
      "name": "thermal_zone_device_is_enabled",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:526",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_resume",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_mode",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ],
      "caller_func": [
        "drivers/thermal/thermal_sysfs.c:mode_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593525856,
      "name": "thermal_zone_device_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int thermal_zone_device_is_enabled(struct thermal_zone_device * tz)
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
