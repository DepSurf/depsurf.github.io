# Function: <code>__dax_driver_register</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int __dax_driver_register(struct dax_device_driver * dax_drv, struct module * module, const char * mod_name)
```

```json
{
  "name": "__dax_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dax_driver_register",
      "external": true,
      "loc": "drivers/dax/bus.c:459",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586448723,
      "name": "__dax_driver_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071586447440,
      "name": "__dax_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int __dax_driver_register(struct dax_device_driver * dax_drv, struct module * module, const char * mod_name)
```

```json
{
  "name": "__dax_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586595376,
      "name": "__dax_driver_register",
      "external": true,
      "loc": "drivers/dax/bus.c:459",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586595376,
      "name": "__dax_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int __dax_driver_register(struct dax_device_driver * dax_drv, struct module * module, const char * mod_name)
```

```json
{
  "name": "__dax_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587380512,
      "name": "__dax_driver_register",
      "external": true,
      "loc": "drivers/dax/bus.c:473",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587380512,
      "name": "__dax_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int __dax_driver_register(struct dax_device_driver * dax_drv, struct module * module, const char * mod_name)
```

```json
{
  "name": "__dax_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587443200,
      "name": "__dax_driver_register",
      "external": true,
      "loc": "drivers/dax/bus.c:1389",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587443200,
      "name": "__dax_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int __dax_driver_register(struct dax_device_driver * dax_drv, struct module * module, const char * mod_name)
```

```json
{
  "name": "__dax_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587324912,
      "name": "__dax_driver_register",
      "external": true,
      "loc": "drivers/dax/bus.c:1390",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587324912,
      "name": "__dax_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int __dax_driver_register(struct dax_device_driver * dax_drv, struct module * module, const char * mod_name)
```

```json
{
  "name": "__dax_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587891472,
      "name": "__dax_driver_register",
      "external": true,
      "loc": "drivers/dax/bus.c:1388",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587891472,
      "name": "__dax_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int __dax_driver_register(struct dax_device_driver * dax_drv, struct module * module, const char * mod_name)
```

```json
{
  "name": "__dax_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589240656,
      "name": "__dax_driver_register",
      "external": true,
      "loc": "drivers/dax/bus.c:1418",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589240656,
      "name": "__dax_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
int __dax_driver_register(struct dax_device_driver * dax_drv, struct module * module, const char * mod_name)
```

```json
{
  "name": "__dax_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590799744,
      "name": "__dax_driver_register",
      "external": true,
      "loc": "drivers/dax/bus.c:1418",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590799744,
      "name": "__dax_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
int __dax_driver_register(struct dax_device_driver * dax_drv, struct module * module, const char * mod_name)
```

```json
{
  "name": "__dax_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591140864,
      "name": "__dax_driver_register",
      "external": true,
      "loc": "drivers/dax/bus.c:1442",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591140864,
      "name": "__dax_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int __dax_driver_register(struct dax_device_driver * dax_drv, struct module * module, const char * mod_name)
```

```json
{
  "name": "__dax_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591486560,
      "name": "__dax_driver_register",
      "external": true,
      "loc": "drivers/dax/bus.c:1445",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591486560,
      "name": "__dax_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __dax_driver_register(struct dax_device_driver * dax_drv, struct module * module, const char * mod_name)
```

```json
{
  "name": "__dax_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499480456,
      "name": "__dax_driver_register",
      "external": true,
      "loc": "drivers/dax/bus.c:459",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499480456,
      "name": "__dax_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int __dax_driver_register(struct dax_device_driver * dax_drv, struct module * module, const char * mod_name)
```

```json
{
  "name": "__dax_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231953100,
      "name": "__dax_driver_register",
      "external": true,
      "loc": "drivers/dax/bus.c:459",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231953100,
      "name": "__dax_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int __dax_driver_register(struct dax_device_driver * dax_drv, struct module * module, const char * mod_name)
```

```json
{
  "name": "__dax_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292758736,
      "name": "__dax_driver_register",
      "external": true,
      "loc": "drivers/dax/bus.c:459",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292758736,
      "name": "__dax_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int __dax_driver_register(struct dax_device_driver * dax_drv, struct module * module, const char * mod_name)
```

```json
{
  "name": "__dax_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276698178,
      "name": "__dax_driver_register",
      "external": true,
      "loc": "drivers/dax/bus.c:459",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276698178,
      "name": "__dax_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int __dax_driver_register(struct dax_device_driver * dax_drv, struct module * module, const char * mod_name)
```

```json
{
  "name": "__dax_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586285856,
      "name": "__dax_driver_register",
      "external": true,
      "loc": "drivers/dax/bus.c:459",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586285856,
      "name": "__dax_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int __dax_driver_register(struct dax_device_driver * dax_drv, struct module * module, const char * mod_name)
```

```json
{
  "name": "__dax_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586123344,
      "name": "__dax_driver_register",
      "external": true,
      "loc": "drivers/dax/bus.c:459",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/device.c:dax_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586123344,
      "name": "__dax_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int __dax_driver_register(struct dax_device_driver * dax_drv, struct module * module, const char * mod_name)
```

```json
{
  "name": "__dax_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586543344,
      "name": "__dax_driver_register",
      "external": true,
      "loc": "drivers/dax/bus.c:459",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586543344,
      "name": "__dax_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int __dax_driver_register(struct dax_device_driver * dax_drv, struct module * module, const char * mod_name)
```

```json
{
  "name": "__dax_driver_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586655120,
      "name": "__dax_driver_register",
      "external": true,
      "loc": "drivers/dax/bus.c:459",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586655120,
      "name": "__dax_driver_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int __dax_driver_register(struct dax_device_driver * dax_drv, struct module * module, const char * mod_name)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
