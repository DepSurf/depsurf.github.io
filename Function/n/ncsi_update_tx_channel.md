# Function: <code>ncsi_update_tx_channel</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int ncsi_update_tx_channel(struct ncsi_dev_priv * ndp, struct ncsi_package * package, struct ncsi_channel * disable, struct ncsi_channel * enable)
```

```json
{
  "name": "ncsi_update_tx_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589334912,
      "name": "ncsi_update_tx_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:824",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589334912,
      "name": "ncsi_update_tx_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 697
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
int ncsi_update_tx_channel(struct ncsi_dev_priv * ndp, struct ncsi_package * package, struct ncsi_channel * disable, struct ncsi_channel * enable)
```

```json
{
  "name": "ncsi_update_tx_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ncsi_update_tx_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:820",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589797456,
      "name": "ncsi_update_tx_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071589790016,
      "name": "ncsi_update_tx_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 571
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
int ncsi_update_tx_channel(struct ncsi_dev_priv * ndp, struct ncsi_package * package, struct ncsi_channel * disable, struct ncsi_channel * enable)
```

```json
{
  "name": "ncsi_update_tx_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ncsi_update_tx_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:819",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590020628,
      "name": "ncsi_update_tx_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071590013296,
      "name": "ncsi_update_tx_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 571
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
int ncsi_update_tx_channel(struct ncsi_dev_priv * ndp, struct ncsi_package * package, struct ncsi_channel * disable, struct ncsi_channel * enable)
```

```json
{
  "name": "ncsi_update_tx_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ncsi_update_tx_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:846",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591052570,
      "name": "ncsi_update_tx_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071591045104,
      "name": "ncsi_update_tx_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 571
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
int ncsi_update_tx_channel(struct ncsi_dev_priv * ndp, struct ncsi_package * package, struct ncsi_channel * disable, struct ncsi_channel * enable)
```

```json
{
  "name": "ncsi_update_tx_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ncsi_update_tx_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:846",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591639432,
      "name": "ncsi_update_tx_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071591108720,
      "name": "ncsi_update_tx_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 571
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
int ncsi_update_tx_channel(struct ncsi_dev_priv * ndp, struct ncsi_package * package, struct ncsi_channel * disable, struct ncsi_channel * enable)
```

```json
{
  "name": "ncsi_update_tx_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ncsi_update_tx_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:852",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591582887,
      "name": "ncsi_update_tx_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    },
    {
      "addr": 18446744071591039120,
      "name": "ncsi_update_tx_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
int ncsi_update_tx_channel(struct ncsi_dev_priv * ndp, struct ncsi_package * package, struct ncsi_channel * disable, struct ncsi_channel * enable)
```

```json
{
  "name": "ncsi_update_tx_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ncsi_update_tx_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:904",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592748857,
      "name": "ncsi_update_tx_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
    },
    {
      "addr": 18446744071591881360,
      "name": "ncsi_update_tx_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
int ncsi_update_tx_channel(struct ncsi_dev_priv * ndp, struct ncsi_package * package, struct ncsi_channel * disable, struct ncsi_channel * enable)
```

```json
{
  "name": "ncsi_update_tx_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ncsi_update_tx_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:904",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594635486,
      "name": "ncsi_update_tx_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
    },
    {
      "addr": 18446744071593600576,
      "name": "ncsi_update_tx_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 658
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
int ncsi_update_tx_channel(struct ncsi_dev_priv * ndp, struct ncsi_package * package, struct ncsi_channel * disable, struct ncsi_channel * enable)
```

```json
{
  "name": "ncsi_update_tx_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ncsi_update_tx_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:904",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596366376,
      "name": "ncsi_update_tx_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071595528400,
      "name": "ncsi_update_tx_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 790
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
int ncsi_update_tx_channel(struct ncsi_dev_priv * ndp, struct ncsi_package * package, struct ncsi_channel * disable, struct ncsi_channel * enable)
```

```json
{
  "name": "ncsi_update_tx_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ncsi_update_tx_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:904",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596896171,
      "name": "ncsi_update_tx_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071596036944,
      "name": "ncsi_update_tx_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 790
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
int ncsi_update_tx_channel(struct ncsi_dev_priv * ndp, struct ncsi_package * package, struct ncsi_channel * disable, struct ncsi_channel * enable)
```

```json
{
  "name": "ncsi_update_tx_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ncsi_update_tx_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:896",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597821453,
      "name": "ncsi_update_tx_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071596901616,
      "name": "ncsi_update_tx_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 790
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
int ncsi_update_tx_channel(struct ncsi_dev_priv * ndp, struct ncsi_package * package, struct ncsi_channel * disable, struct ncsi_channel * enable)
```

```json
{
  "name": "ncsi_update_tx_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503761024,
      "name": "ncsi_update_tx_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:819",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503761024,
      "name": "ncsi_update_tx_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
int ncsi_update_tx_channel(struct ncsi_dev_priv * ndp, struct ncsi_package * package, struct ncsi_channel * disable, struct ncsi_channel * enable)
```

```json
{
  "name": "ncsi_update_tx_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236385388,
      "name": "ncsi_update_tx_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:819",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236385388,
      "name": "ncsi_update_tx_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 772
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
int ncsi_update_tx_channel(struct ncsi_dev_priv * ndp, struct ncsi_package * package, struct ncsi_channel * disable, struct ncsi_channel * enable)
```

```json
{
  "name": "ncsi_update_tx_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297601728,
      "name": "ncsi_update_tx_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:819",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297601728,
      "name": "ncsi_update_tx_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 896
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
int ncsi_update_tx_channel(struct ncsi_dev_priv * ndp, struct ncsi_package * package, struct ncsi_channel * disable, struct ncsi_channel * enable)
```

```json
{
  "name": "ncsi_update_tx_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279676686,
      "name": "ncsi_update_tx_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:819",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279676686,
      "name": "ncsi_update_tx_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
int ncsi_update_tx_channel(struct ncsi_dev_priv * ndp, struct ncsi_package * package, struct ncsi_channel * disable, struct ncsi_channel * enable)
```

```json
{
  "name": "ncsi_update_tx_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ncsi_update_tx_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:819",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589624228,
      "name": "ncsi_update_tx_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071589616896,
      "name": "ncsi_update_tx_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 571
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
int ncsi_update_tx_channel(struct ncsi_dev_priv * ndp, struct ncsi_package * package, struct ncsi_channel * disable, struct ncsi_channel * enable)
```

```json
{
  "name": "ncsi_update_tx_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ncsi_update_tx_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:819",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589348756,
      "name": "ncsi_update_tx_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071589341424,
      "name": "ncsi_update_tx_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 571
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
int ncsi_update_tx_channel(struct ncsi_dev_priv * ndp, struct ncsi_package * package, struct ncsi_channel * disable, struct ncsi_channel * enable)
```

```json
{
  "name": "ncsi_update_tx_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ncsi_update_tx_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:819",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590066260,
      "name": "ncsi_update_tx_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071590058928,
      "name": "ncsi_update_tx_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 571
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
int ncsi_update_tx_channel(struct ncsi_dev_priv * ndp, struct ncsi_package * package, struct ncsi_channel * disable, struct ncsi_channel * enable)
```

```json
{
  "name": "ncsi_update_tx_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ncsi_update_tx_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:819",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590116340,
      "name": "ncsi_update_tx_channel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071590109024,
      "name": "ncsi_update_tx_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 571
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int ncsi_update_tx_channel(struct ncsi_dev_priv * ndp, struct ncsi_package * package, struct ncsi_channel * disable, struct ncsi_channel * enable)
```
</details>
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
