# Function: <code>ethtool_get_settings</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586320026,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/core/ethtool.c:369",
      "file": "net/core/ethtool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586745168,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/core/ethtool.c:764",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586745168,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586931712,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/core/ethtool.c:775",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586931712,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587057760,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/core/ethtool.c:778",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587057760,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 601
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587558880,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/core/ethtool.c:783",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587558880,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587863584,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/core/ethtool.c:756",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587863584,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588005664,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/core/ethtool.c:708",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588005664,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588319344,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/core/ethtool.c:707",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588319344,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588526000,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/core/ethtool.c:708",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588526000,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589861136,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:636",
      "file": "net/ethtool/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589861136,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589901056,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:640",
      "file": "net/ethtool/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589901056,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589808032,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:640",
      "file": "net/ethtool/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589808032,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:642",
      "file": "net/ethtool/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590570480,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071592711751,
      "name": "ethtool_get_settings.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:666",
      "file": "net/ethtool/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:__dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592187904,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 534
    },
    {
      "addr": 18446744071594597808,
      "name": "ethtool_get_settings.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:647",
      "file": "net/ethtool/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:__dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594013984,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
    },
    {
      "addr": 18446744071596333750,
      "name": "ethtool_get_settings.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:648",
      "file": "net/ethtool/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:__dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594391216,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
    },
    {
      "addr": 18446744071596862716,
      "name": "ethtool_get_settings.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:651",
      "file": "net/ethtool/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:__dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595192256,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
    },
    {
      "addr": 18446744071597787765,
      "name": "ethtool_get_settings.cold",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502060368,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/core/ethtool.c:708",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502060368,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234810060,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/core/ethtool.c:708",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234810060,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295508112,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/core/ethtool.c:708",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295508112,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278338812,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/core/ethtool.c:708",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278338812,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588132736,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/core/ethtool.c:708",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588132736,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587845568,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/core/ethtool.c:708",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587845568,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588464560,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/core/ethtool.c:708",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588464560,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588601472,
      "name": "ethtool_get_settings",
      "external": false,
      "loc": "net/core/ethtool.c:708",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588601472,
      "name": "ethtool_get_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int ethtool_get_settings(struct net_device * dev, void * useraddr)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
