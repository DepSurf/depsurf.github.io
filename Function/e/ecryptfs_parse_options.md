# Function: <code>ecryptfs_parse_options</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582003675,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:257",
      "file": "fs/ecryptfs/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582216539,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:256",
      "file": "fs/ecryptfs/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582306091,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:256",
      "file": "fs/ecryptfs/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582390936,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:256",
      "file": "fs/ecryptfs/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582541672,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:256",
      "file": "fs/ecryptfs/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582733698,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:256",
      "file": "fs/ecryptfs/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582837410,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:256",
      "file": "fs/ecryptfs/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int ecryptfs_parse_options(struct ecryptfs_sb_info * sbi, char * options, uid_t * check_ruid)
```

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:242",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583012224,
      "name": "ecryptfs_parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1168
    },
    {
      "addr": 18446744071583014614,
      "name": "ecryptfs_parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int ecryptfs_parse_options(struct ecryptfs_sb_info * sbi, char * options, uid_t * check_ruid)
```

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:242",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583118416,
      "name": "ecryptfs_parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1168
    },
    {
      "addr": 18446744071583120806,
      "name": "ecryptfs_parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int ecryptfs_parse_options(struct ecryptfs_sb_info * sbi, char * options, uid_t * check_ruid)
```

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:242",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583438336,
      "name": "ecryptfs_parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1150
    },
    {
      "addr": 18446744071583440722,
      "name": "ecryptfs_parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int ecryptfs_parse_options(struct ecryptfs_sb_info * sbi, char * options, uid_t * check_ruid)
```

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:242",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583551696,
      "name": "ecryptfs_parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1304
    },
    {
      "addr": 18446744071591354800,
      "name": "ecryptfs_parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int ecryptfs_parse_options(struct ecryptfs_sb_info * sbi, char * options, uid_t * check_ruid)
```

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:242",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583575136,
      "name": "ecryptfs_parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1290
    },
    {
      "addr": 18446744071591297707,
      "name": "ecryptfs_parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
int ecryptfs_parse_options(struct ecryptfs_sb_info * sbi, char * options, uid_t * check_ruid)
```

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:242",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583933408,
      "name": "ecryptfs_parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1290
    },
    {
      "addr": 18446744071592282624,
      "name": "ecryptfs_parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
int ecryptfs_parse_options(struct ecryptfs_sb_info * sbi, char * options, uid_t * check_ruid)
```

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:242",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584513344,
      "name": "ecryptfs_parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1270
    },
    {
      "addr": 18446744071594065027,
      "name": "ecryptfs_parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int ecryptfs_parse_options(struct ecryptfs_sb_info * sbi, char * options, uid_t * check_ruid)
```

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585182960,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:242",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585182960,
      "name": "ecryptfs_parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1459
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
int ecryptfs_parse_options(struct ecryptfs_sb_info * sbi, char * options, uid_t * check_ruid)
```

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585412016,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:242",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585412016,
      "name": "ecryptfs_parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1502
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
int ecryptfs_parse_options(struct ecryptfs_sb_info * sbi, char * options, uid_t * check_ruid)
```

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585646912,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:242",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585646912,
      "name": "ecryptfs_parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1502
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
int ecryptfs_parse_options(struct ecryptfs_sb_info * sbi, char * options, uid_t * check_ruid)
```

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494827520,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:242",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494827520,
      "name": "ecryptfs_parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1484
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
int ecryptfs_parse_options(struct ecryptfs_sb_info * sbi, char * options, uid_t * check_ruid)
```

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228246400,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:242",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228246400,
      "name": "ecryptfs_parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1248
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
int ecryptfs_parse_options(struct ecryptfs_sb_info * sbi, char * options, uid_t * check_ruid)
```

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288672176,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:242",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288672176,
      "name": "ecryptfs_parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1692
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
int ecryptfs_parse_options(struct ecryptfs_sb_info * sbi, char * options, uid_t * check_ruid)
```

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274152076,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:242",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274152076,
      "name": "ecryptfs_parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1060
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
int ecryptfs_parse_options(struct ecryptfs_sb_info * sbi, char * options, uid_t * check_ruid)
```

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:242",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583087152,
      "name": "ecryptfs_parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1168
    },
    {
      "addr": 18446744071583089542,
      "name": "ecryptfs_parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int ecryptfs_parse_options(struct ecryptfs_sb_info * sbi, char * options, uid_t * check_ruid)
```

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:242",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583024304,
      "name": "ecryptfs_parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1168
    },
    {
      "addr": 18446744071583026694,
      "name": "ecryptfs_parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int ecryptfs_parse_options(struct ecryptfs_sb_info * sbi, char * options, uid_t * check_ruid)
```

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:242",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583075760,
      "name": "ecryptfs_parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1168
    },
    {
      "addr": 18446744071583078150,
      "name": "ecryptfs_parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int ecryptfs_parse_options(struct ecryptfs_sb_info * sbi, char * options, uid_t * check_ruid)
```

```json
{
  "name": "ecryptfs_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_parse_options",
      "external": false,
      "loc": "fs/ecryptfs/main.c:242",
      "file": "fs/ecryptfs/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583165040,
      "name": "ecryptfs_parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1168
    },
    {
      "addr": 18446744071583167430,
      "name": "ecryptfs_parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int ecryptfs_parse_options(struct ecryptfs_sb_info * sbi, char * options, uid_t * check_ruid)
```
</details>
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
