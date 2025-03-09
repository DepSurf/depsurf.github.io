# Function: <code>pps_cdev_ioctl</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int pps_cdev_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "pps_cdev_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587094032,
      "name": "pps_cdev_ioctl",
      "external": false,
      "loc": "drivers/pps/pps.c:104",
      "file": "drivers/pps/pps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pps/pps.c:pps_cdev_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587094032,
      "name": "pps_cdev_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1111
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
long int pps_cdev_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "pps_cdev_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587271216,
      "name": "pps_cdev_ioctl",
      "external": false,
      "loc": "drivers/pps/pps.c:104",
      "file": "drivers/pps/pps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pps/pps.c:pps_cdev_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587271216,
      "name": "pps_cdev_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1111
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
long int pps_cdev_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "pps_cdev_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pps_cdev_ioctl",
      "external": false,
      "loc": "drivers/pps/pps.c:90",
      "file": "drivers/pps/pps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pps/pps.c:pps_cdev_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587540688,
      "name": "pps_cdev_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1085
    },
    {
      "addr": 18446744071587542628,
      "name": "pps_cdev_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
long int pps_cdev_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "pps_cdev_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pps_cdev_ioctl",
      "external": false,
      "loc": "drivers/pps/pps.c:90",
      "file": "drivers/pps/pps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pps/pps.c:pps_cdev_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587743456,
      "name": "pps_cdev_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1085
    },
    {
      "addr": 18446744071587745396,
      "name": "pps_cdev_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
long int pps_cdev_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "pps_cdev_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pps_cdev_ioctl",
      "external": false,
      "loc": "drivers/pps/pps.c:90",
      "file": "drivers/pps/pps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pps/pps.c:pps_cdev_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588588192,
      "name": "pps_cdev_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1085
    },
    {
      "addr": 18446744071588590135,
      "name": "pps_cdev_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
long int pps_cdev_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "pps_cdev_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pps_cdev_ioctl",
      "external": false,
      "loc": "drivers/pps/pps.c:90",
      "file": "drivers/pps/pps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pps/pps.c:pps_cdev_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588611584,
      "name": "pps_cdev_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1085
    },
    {
      "addr": 18446744071591580013,
      "name": "pps_cdev_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
long int pps_cdev_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "pps_cdev_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pps_cdev_ioctl",
      "external": false,
      "loc": "drivers/pps/pps.c:90",
      "file": "drivers/pps/pps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pps/pps.c:pps_cdev_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588496512,
      "name": "pps_cdev_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1085
    },
    {
      "addr": 18446744071591522831,
      "name": "pps_cdev_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
long int pps_cdev_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "pps_cdev_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pps_cdev_ioctl",
      "external": false,
      "loc": "drivers/pps/pps.c:90",
      "file": "drivers/pps/pps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pps/pps.c:pps_cdev_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589165216,
      "name": "pps_cdev_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1076
    },
    {
      "addr": 18446744071592632097,
      "name": "pps_cdev_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
long int pps_cdev_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "pps_cdev_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pps_cdev_ioctl",
      "external": false,
      "loc": "drivers/pps/pps.c:90",
      "file": "drivers/pps/pps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pps/pps.c:pps_cdev_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590619952,
      "name": "pps_cdev_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1150
    },
    {
      "addr": 18446744071594515788,
      "name": "pps_cdev_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
long int pps_cdev_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "pps_cdev_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592281984,
      "name": "pps_cdev_ioctl",
      "external": false,
      "loc": "drivers/pps/pps.c:90",
      "file": "drivers/pps/pps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pps/pps.c:pps_cdev_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592281984,
      "name": "pps_cdev_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1210
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
long int pps_cdev_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "pps_cdev_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592706496,
      "name": "pps_cdev_ioctl",
      "external": false,
      "loc": "drivers/pps/pps.c:90",
      "file": "drivers/pps/pps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pps/pps.c:pps_cdev_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592706496,
      "name": "pps_cdev_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1199
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
long int pps_cdev_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "pps_cdev_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593452608,
      "name": "pps_cdev_ioctl",
      "external": false,
      "loc": "drivers/pps/pps.c:90",
      "file": "drivers/pps/pps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pps/pps.c:pps_cdev_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593452608,
      "name": "pps_cdev_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1199
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
long int pps_cdev_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "pps_cdev_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500927392,
      "name": "pps_cdev_ioctl",
      "external": false,
      "loc": "drivers/pps/pps.c:90",
      "file": "drivers/pps/pps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pps/pps.c:pps_cdev_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500927392,
      "name": "pps_cdev_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1600
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
long int pps_cdev_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "pps_cdev_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233437660,
      "name": "pps_cdev_ioctl",
      "external": false,
      "loc": "drivers/pps/pps.c:90",
      "file": "drivers/pps/pps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233437660,
      "name": "pps_cdev_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2036
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
long int pps_cdev_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "pps_cdev_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294381968,
      "name": "pps_cdev_ioctl",
      "external": false,
      "loc": "drivers/pps/pps.c:90",
      "file": "drivers/pps/pps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pps/pps.c:pps_cdev_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294381968,
      "name": "pps_cdev_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1712
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
long int pps_cdev_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "pps_cdev_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277695162,
      "name": "pps_cdev_ioctl",
      "external": false,
      "loc": "drivers/pps/pps.c:90",
      "file": "drivers/pps/pps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277695162,
      "name": "pps_cdev_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1254
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
long int pps_cdev_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "pps_cdev_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pps_cdev_ioctl",
      "external": false,
      "loc": "drivers/pps/pps.c:90",
      "file": "drivers/pps/pps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pps/pps.c:pps_cdev_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587384400,
      "name": "pps_cdev_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1085
    },
    {
      "addr": 18446744071587386340,
      "name": "pps_cdev_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
long int pps_cdev_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "pps_cdev_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pps_cdev_ioctl",
      "external": false,
      "loc": "drivers/pps/pps.c:90",
      "file": "drivers/pps/pps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pps/pps.c:pps_cdev_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587152624,
      "name": "pps_cdev_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1067
    },
    {
      "addr": 18446744071587154548,
      "name": "pps_cdev_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
long int pps_cdev_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "pps_cdev_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pps_cdev_ioctl",
      "external": false,
      "loc": "drivers/pps/pps.c:90",
      "file": "drivers/pps/pps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pps/pps.c:pps_cdev_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587699600,
      "name": "pps_cdev_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1085
    },
    {
      "addr": 18446744071587701540,
      "name": "pps_cdev_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
long int pps_cdev_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "pps_cdev_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pps_cdev_ioctl",
      "external": false,
      "loc": "drivers/pps/pps.c:90",
      "file": "drivers/pps/pps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pps/pps.c:pps_cdev_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587812560,
      "name": "pps_cdev_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1058
    },
    {
      "addr": 18446744071587814612,
      "name": "pps_cdev_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
long int pps_cdev_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```
</details>
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
