# Function: <code>cooling_device_stats_setup</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cooling_device_stats_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587146070,
      "name": "cooling_device_stats_setup",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:904",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cooling_device_stats_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587326006,
      "name": "cooling_device_stats_setup",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:907",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cooling_device_stats_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587596934,
      "name": "cooling_device_stats_setup",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:907",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cooling_device_stats_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587800374,
      "name": "cooling_device_stats_setup",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:907",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void cooling_device_stats_setup(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "cooling_device_stats_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588644704,
      "name": "cooling_device_stats_setup",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:907",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588644704,
      "name": "cooling_device_stats_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void cooling_device_stats_setup(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "cooling_device_stats_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588666880,
      "name": "cooling_device_stats_setup",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:894",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588666880,
      "name": "cooling_device_stats_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void cooling_device_stats_setup(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "cooling_device_stats_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588549408,
      "name": "cooling_device_stats_setup",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:814",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588549408,
      "name": "cooling_device_stats_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void cooling_device_stats_setup(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "cooling_device_stats_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589223488,
      "name": "cooling_device_stats_setup",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:814",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589223488,
      "name": "cooling_device_stats_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void cooling_device_stats_setup(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "cooling_device_stats_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590687056,
      "name": "cooling_device_stats_setup",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:814",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590687056,
      "name": "cooling_device_stats_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cooling_device_stats_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592358965,
      "name": "cooling_device_stats_setup",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:872",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void cooling_device_stats_setup(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "cooling_device_stats_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592783472,
      "name": "cooling_device_stats_setup",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:871",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_reinit",
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592783472,
      "name": "cooling_device_stats_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void cooling_device_stats_setup(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "cooling_device_stats_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593532304,
      "name": "cooling_device_stats_setup",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:840",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_reinit",
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593532304,
      "name": "cooling_device_stats_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "cooling_device_stats_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501002192,
      "name": "cooling_device_stats_setup",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:907",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "cooling_device_stats_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233514776,
      "name": "cooling_device_stats_setup",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:907",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "cooling_device_stats_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294479452,
      "name": "cooling_device_stats_setup",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:907",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "cooling_device_stats_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277752772,
      "name": "cooling_device_stats_setup",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:907",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cooling_device_stats_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587431350,
      "name": "cooling_device_stats_setup",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:907",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cooling_device_stats_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587199558,
      "name": "cooling_device_stats_setup",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:907",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cooling_device_stats_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587756518,
      "name": "cooling_device_stats_setup",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:907",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cooling_device_stats_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587869718,
      "name": "cooling_device_stats_setup",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:907",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void cooling_device_stats_setup(struct thermal_cooling_device * cdev)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void cooling_device_stats_setup(struct thermal_cooling_device * cdev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void cooling_device_stats_setup(struct thermal_cooling_device * cdev)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
