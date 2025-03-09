# Function: <code>dev_change_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586304976,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1141",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586304976,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 729
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586733216,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1145",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586733216,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586919008,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1144",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586919008,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587044288,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1176",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587044288,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 756
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
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587544608,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1173",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587544608,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 765
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1173",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587860741,
      "name": "dev_change_name.cold.166",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587848576,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1175",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588001191,
      "name": "dev_change_name.cold.173",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587988464,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1171",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588312234,
      "name": "dev_change_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071588300192,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1089",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588518545,
      "name": "dev_change_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071588506640,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1281",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589392445,
      "name": "dev_change_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071589377808,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1283",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591629704,
      "name": "dev_change_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071589383600,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1331",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591573101,
      "name": "dev_change_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071589280352,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 724
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
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1206",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592699104,
      "name": "dev_change_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071590007552,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 739
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
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1153",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594585259,
      "name": "dev_change_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071591546096,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 844
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
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1153",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596324577,
      "name": "dev_change_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593319840,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 871
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
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1178",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596854877,
      "name": "dev_change_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593781680,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 860
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
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1182",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597779885,
      "name": "dev_change_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071594562256,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 919
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
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502039392,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1089",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502039392,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 956
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
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234791432,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1089",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234791432,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 860
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
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295485888,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1089",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295485888,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1188
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
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278326818,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1089",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278326818,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1089",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588125281,
      "name": "dev_change_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071588113376,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1089",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587838113,
      "name": "dev_change_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071587826208,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1089",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588457105,
      "name": "dev_change_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071588445200,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int dev_change_name(struct net_device * dev, const char * newname)
```

```json
{
  "name": "dev_change_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_name",
      "external": true,
      "loc": "net/core/dev.c:1089",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588594017,
      "name": "dev_change_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071588582112,
      "name": "dev_change_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
