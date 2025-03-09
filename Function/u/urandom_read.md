# Function: <code>urandom_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t urandom_read(struct file * file, char * buf, size_t nbytes, loff_t * ppos)
```

```json
{
  "name": "urandom_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584168128,
      "name": "urandom_read",
      "external": false,
      "loc": "drivers/char/random.c:1458",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:SyS_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584168128,
      "name": "urandom_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
ssize_t urandom_read(struct file * file, char * buf, size_t nbytes, loff_t * ppos)
```

```json
{
  "name": "urandom_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584513680,
      "name": "urandom_read",
      "external": false,
      "loc": "drivers/char/random.c:1739",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:SyS_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584513680,
      "name": "urandom_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
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
ssize_t urandom_read(struct file * file, char * buf, size_t nbytes, loff_t * ppos)
```

```json
{
  "name": "urandom_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584695760,
      "name": "urandom_read",
      "external": false,
      "loc": "drivers/char/random.c:1739",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:SyS_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584695760,
      "name": "urandom_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
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
ssize_t urandom_read(struct file * file, char * buf, size_t nbytes, loff_t * ppos)
```

```json
{
  "name": "urandom_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584777728,
      "name": "urandom_read",
      "external": false,
      "loc": "drivers/char/random.c:1767",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:SyS_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584777728,
      "name": "urandom_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
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
ssize_t urandom_read(struct file * file, char * buf, size_t nbytes, loff_t * ppos)
```

```json
{
  "name": "urandom_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585197840,
      "name": "urandom_read",
      "external": false,
      "loc": "drivers/char/random.c:1766",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:SyS_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585197840,
      "name": "urandom_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
ssize_t urandom_read(struct file * file, char * buf, size_t nbytes, loff_t * ppos)
```

```json
{
  "name": "urandom_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "urandom_read",
      "external": false,
      "loc": "drivers/char/random.c:1857",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:__ia32_sys_getrandom",
        "drivers/char/random.c:__x64_sys_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585434128,
      "name": "urandom_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
    },
    {
      "addr": 18446744071585436225,
      "name": "urandom_read.cold.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t urandom_read(struct file * file, char * buf, size_t nbytes, loff_t * ppos)
```

```json
{
  "name": "urandom_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "urandom_read",
      "external": false,
      "loc": "drivers/char/random.c:1882",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:__ia32_sys_getrandom",
        "drivers/char/random.c:__x64_sys_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585557552,
      "name": "urandom_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
    },
    {
      "addr": 18446744071585559873,
      "name": "urandom_read.cold.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t urandom_read(struct file * file, char * buf, size_t nbytes, loff_t * ppos)
```

```json
{
  "name": "urandom_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "urandom_read",
      "external": false,
      "loc": "drivers/char/random.c:1963",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:__ia32_sys_getrandom",
        "drivers/char/random.c:__x64_sys_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585778064,
      "name": "urandom_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
    },
    {
      "addr": 18446744071585779689,
      "name": "urandom_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t urandom_read(struct file * file, char * buf, size_t nbytes, loff_t * ppos)
```

```json
{
  "name": "urandom_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "urandom_read",
      "external": false,
      "loc": "drivers/char/random.c:2024",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:__ia32_sys_getrandom",
        "drivers/char/random.c:__x64_sys_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585920768,
      "name": "urandom_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
    },
    {
      "addr": 18446744071585922369,
      "name": "urandom_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t urandom_read(struct file * file, char * buf, size_t nbytes, loff_t * ppos)
```

```json
{
  "name": "urandom_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "urandom_read",
      "external": false,
      "loc": "drivers/char/random.c:1842",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586656720,
      "name": "urandom_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071586659322,
      "name": "urandom_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t urandom_read(struct file * file, char * buf, size_t nbytes, loff_t * ppos)
```

```json
{
  "name": "urandom_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "urandom_read",
      "external": false,
      "loc": "drivers/char/random.c:1841",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586767264,
      "name": "urandom_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071591462287,
      "name": "urandom_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t urandom_read(struct file * file, char * buf, size_t nbytes, loff_t * ppos)
```

```json
{
  "name": "urandom_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "urandom_read",
      "external": false,
      "loc": "drivers/char/random.c:1817",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586646704,
      "name": "urandom_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071591403824,
      "name": "urandom_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t urandom_read(struct file * file, char * buf, size_t nbytes, loff_t * ppos)
```

```json
{
  "name": "urandom_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "urandom_read",
      "external": false,
      "loc": "drivers/char/random.c:1839",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587194144,
      "name": "urandom_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071592454694,
      "name": "urandom_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
ssize_t urandom_read(struct file * file, char * buf, size_t nbytes, loff_t * ppos)
```

```json
{
  "name": "urandom_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498743888,
      "name": "urandom_read",
      "external": false,
      "loc": "drivers/char/random.c:2024",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:__arm64_sys_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498743888,
      "name": "urandom_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1048
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
ssize_t urandom_read(struct file * file, char * buf, size_t nbytes, loff_t * ppos)
```

```json
{
  "name": "urandom_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231359968,
      "name": "urandom_read",
      "external": false,
      "loc": "drivers/char/random.c:2024",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:__se_sys_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231359968,
      "name": "urandom_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 856
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
ssize_t urandom_read(struct file * file, char * buf, size_t nbytes, loff_t * ppos)
```

```json
{
  "name": "urandom_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291896672,
      "name": "urandom_read",
      "external": false,
      "loc": "drivers/char/random.c:2024",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:__se_sys_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291896672,
      "name": "urandom_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
ssize_t urandom_read(struct file * file, char * buf, size_t nbytes, loff_t * ppos)
```

```json
{
  "name": "urandom_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276242900,
      "name": "urandom_read",
      "external": false,
      "loc": "drivers/char/random.c:2024",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:__se_sys_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276242900,
      "name": "urandom_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
ssize_t urandom_read(struct file * file, char * buf, size_t nbytes, loff_t * ppos)
```

```json
{
  "name": "urandom_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "urandom_read",
      "external": false,
      "loc": "drivers/char/random.c:2024",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:__ia32_sys_getrandom",
        "drivers/char/random.c:__x64_sys_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585681744,
      "name": "urandom_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
    },
    {
      "addr": 18446744071585683345,
      "name": "urandom_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t urandom_read(struct file * file, char * buf, size_t nbytes, loff_t * ppos)
```

```json
{
  "name": "urandom_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "urandom_read",
      "external": false,
      "loc": "drivers/char/random.c:2024",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:__ia32_sys_getrandom",
        "drivers/char/random.c:__x64_sys_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585541616,
      "name": "urandom_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
    },
    {
      "addr": 18446744071585543217,
      "name": "urandom_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t urandom_read(struct file * file, char * buf, size_t nbytes, loff_t * ppos)
```

```json
{
  "name": "urandom_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "urandom_read",
      "external": false,
      "loc": "drivers/char/random.c:2024",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:__ia32_sys_getrandom",
        "drivers/char/random.c:__x64_sys_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585871168,
      "name": "urandom_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
    },
    {
      "addr": 18446744071585872769,
      "name": "urandom_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t urandom_read(struct file * file, char * buf, size_t nbytes, loff_t * ppos)
```

```json
{
  "name": "urandom_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "urandom_read",
      "external": false,
      "loc": "drivers/char/random.c:2024",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:__ia32_sys_getrandom",
        "drivers/char/random.c:__x64_sys_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585979072,
      "name": "urandom_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 651
    },
    {
      "addr": 18446744071585980641,
      "name": "urandom_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
ssize_t urandom_read(struct file * file, char * buf, size_t nbytes, loff_t * ppos)
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
