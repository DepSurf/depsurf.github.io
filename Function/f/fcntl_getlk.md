# Function: <code>fcntl_getlk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * l)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581346288,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2025",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:SyS_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346288,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * l)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581527056,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2051",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:SyS_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581527056,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * l)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581612992,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2089",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:SyS_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581612992,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * flock)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581673552,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2087",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:compat_SyS_fcntl",
        "fs/fcntl.c:compat_SyS_fcntl",
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581673552,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * flock)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581819824,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2121",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:compat_SyS_fcntl",
        "fs/fcntl.c:compat_SyS_fcntl",
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581819824,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * flock)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581994976,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2126",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581994976,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * flock)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582083648,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2240",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582083648,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * flock)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582245552,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2258",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582245552,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * flock)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582345376,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2347",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582345376,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * flock)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582636672,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2350",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582636672,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * flock)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582708784,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2351",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582708784,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * flock)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582738160,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2354",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582738160,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * flock)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583065072,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2257",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583065072,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * flock)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583543008,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2243",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583543008,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * flock)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584143920,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2224",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584143920,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * flock)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584371216,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2201",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584371216,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * flock)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584589568,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2208",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584589568,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * flock)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493929416,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2347",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493929416,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * flock)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227407492,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2347",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227407492,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * flock)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287574176,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2347",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287574176,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * flock)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273480728,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2347",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__se_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273480728,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * flock)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582314112,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2347",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582314112,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * flock)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582251872,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2347",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582251872,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * flock)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582304592,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2347",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582304592,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int fcntl_getlk(struct file * filp, unsigned int cmd, struct flock * flock)
```

```json
{
  "name": "fcntl_getlk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582383760,
      "name": "fcntl_getlk",
      "external": true,
      "loc": "fs/locks.c:2347",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582383760,
      "name": "fcntl_getlk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
<code>struct flock * flock</code>
</li>
<li>
<b>Param removed. </b>
<code>struct flock * l</code>
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
