# Function: <code>ethtool_set_settings</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586319948,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/core/ethtool.c:383",
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586741920,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/core/ethtool.c:820",
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
      "addr": 18446744071586741920,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586927712,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/core/ethtool.c:831",
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
      "addr": 18446744071586927712,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587053968,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/core/ethtool.c:834",
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
      "addr": 18446744071587053968,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587554960,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/core/ethtool.c:837",
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
      "addr": 18446744071587554960,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587862544,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/core/ethtool.c:810",
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
      "addr": 18446744071587862544,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588006080,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/core/ethtool.c:741",
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
      "addr": 18446744071588006080,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588319776,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/core/ethtool.c:740",
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
      "addr": 18446744071588319776,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588526432,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/core/ethtool.c:741",
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
      "addr": 18446744071588526432,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589854176,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:669",
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
      "addr": 18446744071589854176,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589894640,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:673",
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
      "addr": 18446744071589894640,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589801808,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:673",
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
      "addr": 18446744071589801808,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:675",
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
      "addr": 18446744071590567056,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    },
    {
      "addr": 18446744071592711670,
      "name": "ethtool_set_settings.cold",
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:699",
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
      "addr": 18446744071592183264,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
    },
    {
      "addr": 18446744071594597724,
      "name": "ethtool_set_settings.cold",
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:680",
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
      "addr": 18446744071594010288,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
    },
    {
      "addr": 18446744071596333687,
      "name": "ethtool_set_settings.cold",
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:681",
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
      "addr": 18446744071594388016,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
    },
    {
      "addr": 18446744071596862653,
      "name": "ethtool_set_settings.cold",
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:684",
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
      "addr": 18446744071595189056,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
    },
    {
      "addr": 18446744071597787702,
      "name": "ethtool_set_settings.cold",
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502057912,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/core/ethtool.c:741",
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
      "addr": 18446603336502057912,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234810812,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/core/ethtool.c:741",
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
      "addr": 3234810812,
      "name": "ethtool_set_settings",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295508560,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/core/ethtool.c:741",
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
      "addr": 13835058055295508560,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278337976,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/core/ethtool.c:741",
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
      "addr": 18446743936278337976,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588133168,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/core/ethtool.c:741",
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
      "addr": 18446744071588133168,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587846000,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/core/ethtool.c:741",
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
      "addr": 18446744071587846000,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588464992,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/core/ethtool.c:741",
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
      "addr": 18446744071588464992,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_settings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588601904,
      "name": "ethtool_set_settings",
      "external": false,
      "loc": "net/core/ethtool.c:741",
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
      "addr": 18446744071588601904,
      "name": "ethtool_set_settings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int ethtool_set_settings(struct net_device * dev, void * useraddr)
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
