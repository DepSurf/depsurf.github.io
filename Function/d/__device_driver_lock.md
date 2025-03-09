# Function: <code>__device_driver_lock</code>

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
void __device_driver_lock(struct device * dev, struct device * parent)
```

```json
{
  "name": "__device_driver_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586032592,
      "name": "__device_driver_lock",
      "external": false,
      "loc": "drivers/base/dd.c:941",
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
      "addr": 18446744071586032592,
      "name": "__device_driver_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void __device_driver_lock(struct device * dev, struct device * parent)
```

```json
{
  "name": "__device_driver_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586179984,
      "name": "__device_driver_lock",
      "external": false,
      "loc": "drivers/base/dd.c:956",
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
      "addr": 18446744071586179984,
      "name": "__device_driver_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
  "name": "__device_driver_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586947575,
      "name": "__device_driver_lock",
      "external": false,
      "loc": "drivers/base/dd.c:930",
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
  "name": "__device_driver_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587033159,
      "name": "__device_driver_lock",
      "external": false,
      "loc": "drivers/base/dd.c:976",
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
  "name": "__device_driver_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586916951,
      "name": "__device_driver_lock",
      "external": false,
      "loc": "drivers/base/dd.c:997",
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
  "name": "__device_driver_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587479270,
      "name": "__device_driver_lock",
      "external": false,
      "loc": "drivers/base/dd.c:1031",
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
  "name": "__device_driver_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588799381,
      "name": "__device_driver_lock",
      "external": false,
      "loc": "drivers/base/dd.c:1050",
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
  "name": "__device_driver_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590295813,
      "name": "__device_driver_lock",
      "external": false,
      "loc": "drivers/base/dd.c:1069",
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
  "name": "__device_driver_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590615925,
      "name": "__device_driver_lock",
      "external": false,
      "loc": "drivers/base/dd.c:1091",
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
  "name": "__device_driver_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590975029,
      "name": "__device_driver_lock",
      "external": false,
      "loc": "drivers/base/dd.c:1091",
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
void __device_driver_lock(struct device * dev, struct device * parent)
```

```json
{
  "name": "__device_driver_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498977536,
      "name": "__device_driver_lock",
      "external": false,
      "loc": "drivers/base/dd.c:956",
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
      "addr": 18446603336498977536,
      "name": "__device_driver_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void __device_driver_lock(struct device * dev, struct device * parent)
```

```json
{
  "name": "__device_driver_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231546312,
      "name": "__device_driver_lock",
      "external": false,
      "loc": "drivers/base/dd.c:956",
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
      "addr": 3231546312,
      "name": "__device_driver_lock",
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
void __device_driver_lock(struct device * dev, struct device * parent)
```

```json
{
  "name": "__device_driver_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292127264,
      "name": "__device_driver_lock",
      "external": false,
      "loc": "drivers/base/dd.c:956",
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
      "addr": 13835058055292127264,
      "name": "__device_driver_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void __device_driver_lock(struct device * dev, struct device * parent)
```

```json
{
  "name": "__device_driver_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276355648,
      "name": "__device_driver_lock",
      "external": false,
      "loc": "drivers/base/dd.c:956",
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
      "addr": 18446743936276355648,
      "name": "__device_driver_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void __device_driver_lock(struct device * dev, struct device * parent)
```

```json
{
  "name": "__device_driver_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585940352,
      "name": "__device_driver_lock",
      "external": false,
      "loc": "drivers/base/dd.c:956",
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
      "addr": 18446744071585940352,
      "name": "__device_driver_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void __device_driver_lock(struct device * dev, struct device * parent)
```

```json
{
  "name": "__device_driver_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585789488,
      "name": "__device_driver_lock",
      "external": false,
      "loc": "drivers/base/dd.c:956",
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
      "addr": 18446744071585789488,
      "name": "__device_driver_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void __device_driver_lock(struct device * dev, struct device * parent)
```

```json
{
  "name": "__device_driver_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586130000,
      "name": "__device_driver_lock",
      "external": false,
      "loc": "drivers/base/dd.c:956",
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
      "addr": 18446744071586130000,
      "name": "__device_driver_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void __device_driver_lock(struct device * dev, struct device * parent)
```

```json
{
  "name": "__device_driver_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586238608,
      "name": "__device_driver_lock",
      "external": false,
      "loc": "drivers/base/dd.c:956",
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
      "addr": 18446744071586238608,
      "name": "__device_driver_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void __device_driver_lock(struct device * dev, struct device * parent)
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
void __device_driver_lock(struct device * dev, struct device * parent)
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
