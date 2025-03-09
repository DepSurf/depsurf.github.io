# Function: <code>__device_driver_unlock</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __device_driver_unlock(struct device * dev, struct device * parent)
```

```json
{
  "name": "__device_driver_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586032752,
      "name": "__device_driver_unlock",
      "external": false,
      "loc": "drivers/base/dd.c:957",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__driver_attach_async_helper",
        "drivers/base/dd.c:device_driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586032752,
      "name": "__device_driver_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __device_driver_unlock(struct device * dev, struct device * parent)
```

```json
{
  "name": "__device_driver_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586180144,
      "name": "__device_driver_unlock",
      "external": false,
      "loc": "drivers/base/dd.c:972",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__driver_attach_async_helper",
        "drivers/base/dd.c:device_driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586180144,
      "name": "__device_driver_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__device_driver_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586947457,
      "name": "__device_driver_unlock",
      "external": false,
      "loc": "drivers/base/dd.c:946",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:device_driver_detach",
        "drivers/base/dd.c:device_release_driver",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:__driver_attach_async_helper",
        "drivers/base/dd.c:device_driver_attach"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__device_driver_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587033041,
      "name": "__device_driver_unlock",
      "external": false,
      "loc": "drivers/base/dd.c:992",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:device_driver_detach",
        "drivers/base/dd.c:device_release_driver",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:__driver_attach_async_helper",
        "drivers/base/dd.c:device_driver_attach"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__device_driver_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586916833,
      "name": "__device_driver_unlock",
      "external": false,
      "loc": "drivers/base/dd.c:1013",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:device_driver_detach",
        "drivers/base/dd.c:device_release_driver",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:__driver_attach_async_helper",
        "drivers/base/dd.c:device_driver_attach"
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
  "name": "__device_driver_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587479137,
      "name": "__device_driver_unlock",
      "external": false,
      "loc": "drivers/base/dd.c:1047",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:driver_detach",
        "drivers/base/dd.c:device_driver_detach",
        "drivers/base/dd.c:device_release_driver",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__driver_attach_async_helper",
        "drivers/base/dd.c:device_driver_attach"
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
  "name": "__device_driver_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588799478,
      "name": "__device_driver_unlock",
      "external": false,
      "loc": "drivers/base/dd.c:1066",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__driver_attach_async_helper",
        "drivers/base/dd.c:device_driver_attach"
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
  "name": "__device_driver_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590295910,
      "name": "__device_driver_unlock",
      "external": false,
      "loc": "drivers/base/dd.c:1085",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__driver_attach_async_helper",
        "drivers/base/dd.c:device_driver_attach"
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
  "name": "__device_driver_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590616022,
      "name": "__device_driver_unlock",
      "external": false,
      "loc": "drivers/base/dd.c:1107",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__driver_attach_async_helper",
        "drivers/base/dd.c:device_driver_attach"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__device_driver_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590975126,
      "name": "__device_driver_unlock",
      "external": false,
      "loc": "drivers/base/dd.c:1107",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__driver_attach",
        "drivers/base/dd.c:__driver_attach_async_helper",
        "drivers/base/dd.c:device_driver_attach"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __device_driver_unlock(struct device * dev, struct device * parent)
```

```json
{
  "name": "__device_driver_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498977720,
      "name": "__device_driver_unlock",
      "external": false,
      "loc": "drivers/base/dd.c:972",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__driver_attach_async_helper",
        "drivers/base/dd.c:device_driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498977720,
      "name": "__device_driver_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void __device_driver_unlock(struct device * dev, struct device * parent)
```

```json
{
  "name": "__device_driver_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231546456,
      "name": "__device_driver_unlock",
      "external": false,
      "loc": "drivers/base/dd.c:972",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__driver_attach_async_helper",
        "drivers/base/dd.c:device_driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231546456,
      "name": "__device_driver_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void __device_driver_unlock(struct device * dev, struct device * parent)
```

```json
{
  "name": "__device_driver_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292127552,
      "name": "__device_driver_unlock",
      "external": false,
      "loc": "drivers/base/dd.c:972",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__driver_attach_async_helper",
        "drivers/base/dd.c:device_driver_attach",
        "drivers/base/dd.c:device_driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292127552,
      "name": "__device_driver_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void __device_driver_unlock(struct device * dev, struct device * parent)
```

```json
{
  "name": "__device_driver_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276355800,
      "name": "__device_driver_unlock",
      "external": false,
      "loc": "drivers/base/dd.c:972",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__driver_attach_async_helper",
        "drivers/base/dd.c:device_driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276355800,
      "name": "__device_driver_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __device_driver_unlock(struct device * dev, struct device * parent)
```

```json
{
  "name": "__device_driver_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585940512,
      "name": "__device_driver_unlock",
      "external": false,
      "loc": "drivers/base/dd.c:972",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__driver_attach_async_helper",
        "drivers/base/dd.c:device_driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585940512,
      "name": "__device_driver_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void __device_driver_unlock(struct device * dev, struct device * parent)
```

```json
{
  "name": "__device_driver_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585789648,
      "name": "__device_driver_unlock",
      "external": false,
      "loc": "drivers/base/dd.c:972",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__driver_attach_async_helper",
        "drivers/base/dd.c:device_driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585789648,
      "name": "__device_driver_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void __device_driver_unlock(struct device * dev, struct device * parent)
```

```json
{
  "name": "__device_driver_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586130160,
      "name": "__device_driver_unlock",
      "external": false,
      "loc": "drivers/base/dd.c:972",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__driver_attach_async_helper",
        "drivers/base/dd.c:device_driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586130160,
      "name": "__device_driver_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void __device_driver_unlock(struct device * dev, struct device * parent)
```

```json
{
  "name": "__device_driver_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586238768,
      "name": "__device_driver_unlock",
      "external": false,
      "loc": "drivers/base/dd.c:972",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/base/dd.c:__driver_attach_async_helper",
        "drivers/base/dd.c:device_driver_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586238768,
      "name": "__device_driver_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void __device_driver_unlock(struct device * dev, struct device * parent)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void __device_driver_unlock(struct device * dev, struct device * parent)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
