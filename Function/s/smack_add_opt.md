# Function: <code>smack_add_opt</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smack_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583260353,
      "name": "smack_add_opt",
      "external": false,
      "loc": "security/smack/smack_lsm.c:587",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts"
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
int smack_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "smack_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "smack_add_opt",
      "external": false,
      "loc": "security/smack/smack_lsm.c:587",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583446176,
      "name": "smack_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583461924,
      "name": "smack_add_opt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int smack_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "smack_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "smack_add_opt",
      "external": false,
      "loc": "security/smack/smack_lsm.c:587",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583552112,
      "name": "smack_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583567876,
      "name": "smack_add_opt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int smack_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "smack_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "smack_add_opt",
      "external": false,
      "loc": "security/smack/smack_lsm.c:583",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583905024,
      "name": "smack_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583919953,
      "name": "smack_add_opt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int smack_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "smack_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "smack_add_opt",
      "external": false,
      "loc": "security/smack/smack_lsm.c:583",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584024256,
      "name": "smack_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071591367161,
      "name": "smack_add_opt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int smack_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "smack_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "smack_add_opt",
      "external": false,
      "loc": "security/smack/smack_lsm.c:566",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584052800,
      "name": "smack_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071591310202,
      "name": "smack_add_opt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int smack_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "smack_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "smack_add_opt",
      "external": false,
      "loc": "security/smack/smack_lsm.c:566",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584424416,
      "name": "smack_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071592301744,
      "name": "smack_add_opt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int smack_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "smack_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "smack_add_opt",
      "external": false,
      "loc": "security/smack/smack_lsm.c:569",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585053760,
      "name": "smack_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    },
    {
      "addr": 18446744071594083045,
      "name": "smack_add_opt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int smack_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "smack_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585773696,
      "name": "smack_add_opt",
      "external": false,
      "loc": "security/smack/smack_lsm.c:568",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585773696,
      "name": "smack_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int smack_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "smack_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586005152,
      "name": "smack_add_opt",
      "external": false,
      "loc": "security/smack/smack_lsm.c:566",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586005152,
      "name": "smack_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
int smack_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "smack_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586250864,
      "name": "smack_add_opt",
      "external": false,
      "loc": "security/smack/smack_lsm.c:589",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586250864,
      "name": "smack_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int smack_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "smack_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495324936,
      "name": "smack_add_opt",
      "external": false,
      "loc": "security/smack/smack_lsm.c:587",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495324936,
      "name": "smack_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int smack_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "smack_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228702960,
      "name": "smack_add_opt",
      "external": false,
      "loc": "security/smack/smack_lsm.c:587",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228702960,
      "name": "smack_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int smack_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "smack_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289328128,
      "name": "smack_add_opt",
      "external": false,
      "loc": "security/smack/smack_lsm.c:587",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289328128,
      "name": "smack_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
int smack_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "smack_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274541000,
      "name": "smack_add_opt",
      "external": false,
      "loc": "security/smack/smack_lsm.c:587",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274541000,
      "name": "smack_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int smack_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "smack_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "smack_add_opt",
      "external": false,
      "loc": "security/smack/smack_lsm.c:587",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583520848,
      "name": "smack_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583536612,
      "name": "smack_add_opt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int smack_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "smack_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "smack_add_opt",
      "external": false,
      "loc": "security/smack/smack_lsm.c:587",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583457904,
      "name": "smack_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583473668,
      "name": "smack_add_opt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int smack_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "smack_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "smack_add_opt",
      "external": false,
      "loc": "security/smack/smack_lsm.c:587",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583504624,
      "name": "smack_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583520388,
      "name": "smack_add_opt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int smack_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "smack_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "smack_add_opt",
      "external": false,
      "loc": "security/smack/smack_lsm.c:587",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "security/smack/smack_lsm.c:smack_fs_context_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583601120,
      "name": "smack_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583617154,
      "name": "smack_add_opt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int smack_add_opt(int token, const char * s, void * * mnt_opts)
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
