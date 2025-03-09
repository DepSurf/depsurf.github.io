# Function: <code>__hwmon_create_attrs</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586267130,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:511",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586366626,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:511",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586831471,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:518",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:518",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
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
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:536",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
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
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587572528,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:536",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587572528,
      "name": "__hwmon_create_attrs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 945
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587776272,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:551",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587776272,
      "name": "__hwmon_create_attrs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 909
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct attribute * * __hwmon_create_attrs(const void * drvdata, const struct hwmon_chip_info * chip)
```

```json
{
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588624608,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:656",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588624608,
      "name": "__hwmon_create_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
struct attribute * * __hwmon_create_attrs(const void * drvdata, const struct hwmon_chip_info * chip)
```

```json
{
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588644608,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:666",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588644608,
      "name": "__hwmon_create_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:666",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:704",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:723",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:724",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:728",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct attribute * * __hwmon_create_attrs(const void * drvdata, const struct hwmon_chip_info * chip)
```

```json
{
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:728",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593505712,
      "name": "__hwmon_create_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1141
    },
    {
      "addr": 18446744071597762445,
      "name": "__hwmon_create_attrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500974568,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:551",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500974568,
      "name": "__hwmon_create_attrs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
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
struct attribute * * __hwmon_create_attrs(const void * drvdata, const struct hwmon_chip_info * chip)
```

```json
{
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233489212,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:551",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233489212,
      "name": "__hwmon_create_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294443072,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:551",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294443072,
      "name": "__hwmon_create_attrs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277732846,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:551",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277732846,
      "name": "__hwmon_create_attrs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 840
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587407248,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:551",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587407248,
      "name": "__hwmon_create_attrs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 909
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587175456,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:551",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587175456,
      "name": "__hwmon_create_attrs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 909
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587732416,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:551",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587732416,
      "name": "__hwmon_create_attrs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 909
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hwmon_create_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587845568,
      "name": "__hwmon_create_attrs",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:551",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:__hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587845568,
      "name": "__hwmon_create_attrs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 909
    }
  ]
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
struct attribute * * __hwmon_create_attrs(const void * drvdata, const struct hwmon_chip_info * chip)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct attribute * * __hwmon_create_attrs(const void * drvdata, const struct hwmon_chip_info * chip)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct attribute * * __hwmon_create_attrs(const void * drvdata, const struct hwmon_chip_info * chip)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct attribute * * __hwmon_create_attrs(const void * drvdata, const struct hwmon_chip_info * chip)
```
</details>
</li>
</ul>
