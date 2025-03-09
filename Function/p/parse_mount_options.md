# Function: <code>parse_mount_options</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581522608,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:162",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_remount",
        "fs/devpts/inode.c:devpts_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581522608,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581708512,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:190",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mount",
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581708512,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 511
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581796592,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:190",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796592,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 511
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581867648,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:223",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581867648,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582017632,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:251",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582017632,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:251",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582206064,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    },
    {
      "addr": 18446744071582208611,
      "name": "parse_mount_options.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582301072,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:249",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582301072,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:246",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582467408,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
    },
    {
      "addr": 18446744071582469882,
      "name": "parse_mount_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:246",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582566352,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
    },
    {
      "addr": 18446744071582568826,
      "name": "parse_mount_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:246",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582874608,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
    },
    {
      "addr": 18446744071582877201,
      "name": "parse_mount_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:246",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582947472,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
    },
    {
      "addr": 18446744071591346613,
      "name": "parse_mount_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:246",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582974960,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
    },
    {
      "addr": 18446744071591289363,
      "name": "parse_mount_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:246",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583310560,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
    },
    {
      "addr": 18446744071592249322,
      "name": "parse_mount_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:246",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583817760,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
    },
    {
      "addr": 18446744071594030389,
      "name": "parse_mount_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584439792,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:246",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584439792,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584668560,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:228",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668560,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584901328,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:227",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584901328,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494211936,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:246",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494211936,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227643308,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:246",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227643308,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287906928,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:246",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287906928,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 688
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273670296,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:246",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273670296,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:246",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582535088,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
    },
    {
      "addr": 18446744071582537562,
      "name": "parse_mount_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:246",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582472256,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
    },
    {
      "addr": 18446744071582474730,
      "name": "parse_mount_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:246",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582525568,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
    },
    {
      "addr": 18446744071582528042,
      "name": "parse_mount_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int parse_mount_options(char * data, int op, struct pts_mount_opts * opts)
```

```json
{
  "name": "parse_mount_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_mount_options",
      "external": false,
      "loc": "fs/devpts/inode.c:246",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582606240,
      "name": "parse_mount_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
    },
    {
      "addr": 18446744071582608714,
      "name": "parse_mount_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
