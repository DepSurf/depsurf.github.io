# Function: <code>ctl_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ctl_ioctl(uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585832352,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1793",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585832352,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1231
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
int ctl_ioctl(uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586226672,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1797",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586226672,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1258
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
int ctl_ioctl(uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586431168,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1797",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586431168,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1258
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
int ctl_ioctl(struct file * file, uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586535808,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1812",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586535808,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1330
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
int ctl_ioctl(struct file * file, uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587003424,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1820",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587003424,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1383
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
int ctl_ioctl(struct file * file, uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1821",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587297232,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1043
    },
    {
      "addr": 18446744071587305318,
      "name": "ctl_ioctl.cold.12",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int ctl_ioctl(struct file * file, uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1815",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587477424,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1085
    },
    {
      "addr": 18446744071587485542,
      "name": "ctl_ioctl.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
int ctl_ioctl(struct file * file, uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1815",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587754880,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1162
    },
    {
      "addr": 18446744071587759601,
      "name": "ctl_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int ctl_ioctl(struct file * file, uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1841",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587959296,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1223
    },
    {
      "addr": 18446744071587964081,
      "name": "ctl_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int ctl_ioctl(struct file * file, uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1841",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588811488,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 678
    },
    {
      "addr": 18446744071588817612,
      "name": "ctl_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int ctl_ioctl(struct file * file, uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1842",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588829440,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 678
    },
    {
      "addr": 18446744071591592970,
      "name": "ctl_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int ctl_ioctl(struct file * file, uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1919",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588713024,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 686
    },
    {
      "addr": 18446744071591535698,
      "name": "ctl_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int ctl_ioctl(struct file * file, uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1934",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589401696,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 767
    },
    {
      "addr": 18446744071592649215,
      "name": "ctl_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int ctl_ioctl(struct file * file, uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1945",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590878048,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 862
    },
    {
      "addr": 18446744071594533967,
      "name": "ctl_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
int ctl_ioctl(struct file * file, uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592574960,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1952",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592574960,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1052
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
int ctl_ioctl(struct file * file, uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593005776,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:2022",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593005776,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1033
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
int ctl_ioctl(struct file * file, uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593756992,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:2028",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593756992,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1033
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
int ctl_ioctl(struct file * file, uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501203256,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1841",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501203256,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2220
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
int ctl_ioctl(struct file * file, uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233708368,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1841",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233708368,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1704
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
int ctl_ioctl(struct file * file, uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294725232,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1841",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294725232,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1688
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
int ctl_ioctl(struct file * file, uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277903382,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1841",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277903382,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 918
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
int ctl_ioctl(struct file * file, uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1841",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587590272,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1223
    },
    {
      "addr": 18446744071587595057,
      "name": "ctl_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int ctl_ioctl(struct file * file, uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1841",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587358352,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1223
    },
    {
      "addr": 18446744071587363137,
      "name": "ctl_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int ctl_ioctl(struct file * file, uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1841",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587915440,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1223
    },
    {
      "addr": 18446744071587920225,
      "name": "ctl_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int ctl_ioctl(struct file * file, uint command, struct dm_ioctl * user)
```

```json
{
  "name": "ctl_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ctl_ioctl",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:1841",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588030704,
      "name": "ctl_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1223
    },
    {
      "addr": 18446744071588035489,
      "name": "ctl_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file * file</code>
</li>
<li>
<b>Param reordered. </b>
<code>command, user</code> ➡️ <code>file, command, user</code>
</li>
</ul>
</details>
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
