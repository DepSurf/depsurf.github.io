# Function: <code>pstore_get_backend_records</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```

```json
{
  "name": "pstore_get_backend_records",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582517792,
      "name": "pstore_get_backend_records",
      "external": true,
      "loc": "fs/pstore/platform.c:831",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_get_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582517792,
      "name": "pstore_get_backend_records",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 611
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
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```

```json
{
  "name": "pstore_get_backend_records",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582669360,
      "name": "pstore_get_backend_records",
      "external": true,
      "loc": "fs/pstore/platform.c:828",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_get_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582669360,
      "name": "pstore_get_backend_records",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```

```json
{
  "name": "pstore_get_backend_records",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pstore_get_backend_records",
      "external": true,
      "loc": "fs/pstore/platform.c:674",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_get_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582863048,
      "name": "pstore_get_backend_records.cold.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    },
    {
      "addr": 18446744071582862256,
      "name": "pstore_get_backend_records",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 562
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
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```

```json
{
  "name": "pstore_get_backend_records",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pstore_get_backend_records",
      "external": true,
      "loc": "fs/pstore/platform.c:725",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_get_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582971168,
      "name": "pstore_get_backend_records.cold.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071582970304,
      "name": "pstore_get_backend_records",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
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
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```

```json
{
  "name": "pstore_get_backend_records",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pstore_get_backend_records",
      "external": true,
      "loc": "fs/pstore/platform.c:719",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_get_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583152128,
      "name": "pstore_get_backend_records.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071583151168,
      "name": "pstore_get_backend_records",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```

```json
{
  "name": "pstore_get_backend_records",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pstore_get_backend_records",
      "external": true,
      "loc": "fs/pstore/platform.c:719",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_get_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583258192,
      "name": "pstore_get_backend_records.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071583257232,
      "name": "pstore_get_backend_records",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```

```json
{
  "name": "pstore_get_backend_records",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pstore_get_backend_records",
      "external": true,
      "loc": "fs/pstore/platform.c:729",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_get_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583585176,
      "name": "pstore_get_backend_records.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071583584528,
      "name": "pstore_get_backend_records",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```

```json
{
  "name": "pstore_get_backend_records",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pstore_get_backend_records",
      "external": true,
      "loc": "fs/pstore/platform.c:729",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_get_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591361123,
      "name": "pstore_get_backend_records.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071583705264,
      "name": "pstore_get_backend_records",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```

```json
{
  "name": "pstore_get_backend_records",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pstore_get_backend_records",
      "external": true,
      "loc": "fs/pstore/platform.c:732",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_get_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591303946,
      "name": "pstore_get_backend_records.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071583730176,
      "name": "pstore_get_backend_records",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```

```json
{
  "name": "pstore_get_backend_records",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pstore_get_backend_records",
      "external": true,
      "loc": "fs/pstore/platform.c:732",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_get_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592290234,
      "name": "pstore_get_backend_records.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071584091440,
      "name": "pstore_get_backend_records",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```

```json
{
  "name": "pstore_get_backend_records",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pstore_get_backend_records",
      "external": true,
      "loc": "fs/pstore/platform.c:730",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_get_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594072307,
      "name": "pstore_get_backend_records.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071584686128,
      "name": "pstore_get_backend_records",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```

```json
{
  "name": "pstore_get_backend_records",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585372384,
      "name": "pstore_get_backend_records",
      "external": true,
      "loc": "fs/pstore/platform.c:745",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_get_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585372384,
      "name": "pstore_get_backend_records",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```

```json
{
  "name": "pstore_get_backend_records",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585602880,
      "name": "pstore_get_backend_records",
      "external": true,
      "loc": "fs/pstore/platform.c:745",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_get_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585602880,
      "name": "pstore_get_backend_records",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```

```json
{
  "name": "pstore_get_backend_records",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585848320,
      "name": "pstore_get_backend_records",
      "external": true,
      "loc": "fs/pstore/platform.c:656",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_get_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585848320,
      "name": "pstore_get_backend_records",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 726
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
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```

```json
{
  "name": "pstore_get_backend_records",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494985976,
      "name": "pstore_get_backend_records",
      "external": true,
      "loc": "fs/pstore/platform.c:719",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_get_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494985976,
      "name": "pstore_get_backend_records",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 684
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
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```

```json
{
  "name": "pstore_get_backend_records",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228391356,
      "name": "pstore_get_backend_records",
      "external": true,
      "loc": "fs/pstore/platform.c:719",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_get_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228391356,
      "name": "pstore_get_backend_records",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 760
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
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```

```json
{
  "name": "pstore_get_backend_records",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288869696,
      "name": "pstore_get_backend_records",
      "external": true,
      "loc": "fs/pstore/platform.c:719",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_get_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288869696,
      "name": "pstore_get_backend_records",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1052
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
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```

```json
{
  "name": "pstore_get_backend_records",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274285236,
      "name": "pstore_get_backend_records",
      "external": true,
      "loc": "fs/pstore/platform.c:719",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_get_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274285236,
      "name": "pstore_get_backend_records",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```

```json
{
  "name": "pstore_get_backend_records",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pstore_get_backend_records",
      "external": true,
      "loc": "fs/pstore/platform.c:719",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_get_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583226928,
      "name": "pstore_get_backend_records.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071583225968,
      "name": "pstore_get_backend_records",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```

```json
{
  "name": "pstore_get_backend_records",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pstore_get_backend_records",
      "external": true,
      "loc": "fs/pstore/platform.c:719",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_get_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583164080,
      "name": "pstore_get_backend_records.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071583163120,
      "name": "pstore_get_backend_records",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```

```json
{
  "name": "pstore_get_backend_records",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pstore_get_backend_records",
      "external": true,
      "loc": "fs/pstore/platform.c:719",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_get_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583210960,
      "name": "pstore_get_backend_records.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071583210000,
      "name": "pstore_get_backend_records",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```

```json
{
  "name": "pstore_get_backend_records",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pstore_get_backend_records",
      "external": true,
      "loc": "fs/pstore/platform.c:719",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_get_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583304850,
      "name": "pstore_get_backend_records.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071583303888,
      "name": "pstore_get_backend_records",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void pstore_get_backend_records(struct pstore_info * psi, struct dentry * root, int quiet)
```
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
