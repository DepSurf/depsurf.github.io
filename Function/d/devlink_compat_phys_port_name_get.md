# Function: <code>devlink_compat_phys_port_name_get</code>

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
int devlink_compat_phys_port_name_get(struct net_device * dev, char * name, size_t len)
```

```json
{
  "name": "devlink_compat_phys_port_name_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_compat_phys_port_name_get",
      "external": true,
      "loc": "net/core/devlink.c:6921",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_phys_port_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588619926,
      "name": "devlink_compat_phys_port_name_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588617648,
      "name": "devlink_compat_phys_port_name_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
int devlink_compat_phys_port_name_get(struct net_device * dev, char * name, size_t len)
```

```json
{
  "name": "devlink_compat_phys_port_name_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588841456,
      "name": "devlink_compat_phys_port_name_get",
      "external": true,
      "loc": "net/core/devlink.c:8085",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_phys_port_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588841456,
      "name": "devlink_compat_phys_port_name_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int devlink_compat_phys_port_name_get(struct net_device * dev, char * name, size_t len)
```

```json
{
  "name": "devlink_compat_phys_port_name_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589725424,
      "name": "devlink_compat_phys_port_name_get",
      "external": true,
      "loc": "net/core/devlink.c:9316",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_phys_port_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589725424,
      "name": "devlink_compat_phys_port_name_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int devlink_compat_phys_port_name_get(struct net_device * dev, char * name, size_t len)
```

```json
{
  "name": "devlink_compat_phys_port_name_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589760464,
      "name": "devlink_compat_phys_port_name_get",
      "external": true,
      "loc": "net/core/devlink.c:10279",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_phys_port_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589760464,
      "name": "devlink_compat_phys_port_name_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int devlink_compat_phys_port_name_get(struct net_device * dev, char * name, size_t len)
```

```json
{
  "name": "devlink_compat_phys_port_name_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589642640,
      "name": "devlink_compat_phys_port_name_get",
      "external": true,
      "loc": "net/core/devlink.c:10543",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_phys_port_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589642640,
      "name": "devlink_compat_phys_port_name_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int devlink_compat_phys_port_name_get(struct net_device * dev, char * name, size_t len)
```

```json
{
  "name": "devlink_compat_phys_port_name_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_compat_phys_port_name_get",
      "external": true,
      "loc": "net/core/devlink.c:11485",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_phys_port_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592708831,
      "name": "devlink_compat_phys_port_name_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071590397504,
      "name": "devlink_compat_phys_port_name_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int devlink_compat_phys_port_name_get(struct net_device * dev, char * name, size_t len)
```

```json
{
  "name": "devlink_compat_phys_port_name_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_compat_phys_port_name_get",
      "external": true,
      "loc": "net/core/devlink.c:12070",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_phys_port_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594595128,
      "name": "devlink_compat_phys_port_name_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591992992,
      "name": "devlink_compat_phys_port_name_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int devlink_compat_phys_port_name_get(struct net_device * dev, char * name, size_t len)
```

```json
{
  "name": "devlink_compat_phys_port_name_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_compat_phys_port_name_get",
      "external": true,
      "loc": "net/core/devlink.c:12951",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_phys_port_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596331825,
      "name": "devlink_compat_phys_port_name_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593806496,
      "name": "devlink_compat_phys_port_name_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int devlink_compat_phys_port_name_get(struct net_device * dev, char * name, size_t len)
```

```json
{
  "name": "devlink_compat_phys_port_name_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_compat_phys_port_name_get",
      "external": true,
      "loc": "net/devlink/leftover.c:9476",
      "file": "net/devlink/leftover.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_phys_port_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596893771,
      "name": "devlink_compat_phys_port_name_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071595891568,
      "name": "devlink_compat_phys_port_name_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int devlink_compat_phys_port_name_get(struct net_device * dev, char * name, size_t len)
```

```json
{
  "name": "devlink_compat_phys_port_name_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_compat_phys_port_name_get",
      "external": true,
      "loc": "net/devlink/port.c:1533",
      "file": "net/devlink/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_phys_port_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597818033,
      "name": "devlink_compat_phys_port_name_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071596704464,
      "name": "devlink_compat_phys_port_name_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int devlink_compat_phys_port_name_get(struct net_device * dev, char * name, size_t len)
```

```json
{
  "name": "devlink_compat_phys_port_name_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502413176,
      "name": "devlink_compat_phys_port_name_get",
      "external": true,
      "loc": "net/core/devlink.c:8085",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_phys_port_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502413176,
      "name": "devlink_compat_phys_port_name_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
int devlink_compat_phys_port_name_get(struct net_device * dev, char * name, size_t len)
```

```json
{
  "name": "devlink_compat_phys_port_name_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235149676,
      "name": "devlink_compat_phys_port_name_get",
      "external": true,
      "loc": "net/core/devlink.c:8085",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_phys_port_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235149676,
      "name": "devlink_compat_phys_port_name_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int devlink_compat_phys_port_name_get(struct net_device * dev, char * name, size_t len)
```

```json
{
  "name": "devlink_compat_phys_port_name_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295964720,
      "name": "devlink_compat_phys_port_name_get",
      "external": true,
      "loc": "net/core/devlink.c:8085",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_phys_port_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295964720,
      "name": "devlink_compat_phys_port_name_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
int devlink_compat_phys_port_name_get(struct net_device * dev, char * name, size_t len)
```

```json
{
  "name": "devlink_compat_phys_port_name_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278620434,
      "name": "devlink_compat_phys_port_name_get",
      "external": true,
      "loc": "net/core/devlink.c:8085",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_phys_port_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278620434,
      "name": "devlink_compat_phys_port_name_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int devlink_compat_phys_port_name_get(struct net_device * dev, char * name, size_t len)
```

```json
{
  "name": "devlink_compat_phys_port_name_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588447840,
      "name": "devlink_compat_phys_port_name_get",
      "external": true,
      "loc": "net/core/devlink.c:8085",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_phys_port_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588447840,
      "name": "devlink_compat_phys_port_name_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int devlink_compat_phys_port_name_get(struct net_device * dev, char * name, size_t len)
```

```json
{
  "name": "devlink_compat_phys_port_name_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588160528,
      "name": "devlink_compat_phys_port_name_get",
      "external": true,
      "loc": "net/core/devlink.c:8085",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_phys_port_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588160528,
      "name": "devlink_compat_phys_port_name_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int devlink_compat_phys_port_name_get(struct net_device * dev, char * name, size_t len)
```

```json
{
  "name": "devlink_compat_phys_port_name_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588780016,
      "name": "devlink_compat_phys_port_name_get",
      "external": true,
      "loc": "net/core/devlink.c:8085",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_phys_port_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588780016,
      "name": "devlink_compat_phys_port_name_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int devlink_compat_phys_port_name_get(struct net_device * dev, char * name, size_t len)
```

```json
{
  "name": "devlink_compat_phys_port_name_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588920544,
      "name": "devlink_compat_phys_port_name_get",
      "external": true,
      "loc": "net/core/devlink.c:8085",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_phys_port_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588920544,
      "name": "devlink_compat_phys_port_name_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int devlink_compat_phys_port_name_get(struct net_device * dev, char * name, size_t len)
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
