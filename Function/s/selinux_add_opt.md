# Function: <code>selinux_add_opt</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int selinux_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "selinux_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_add_opt",
      "external": false,
      "loc": "security/selinux/hooks.c:968",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583130144,
      "name": "selinux_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
    },
    {
      "addr": 18446744071583163968,
      "name": "selinux_add_opt.cold.71",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int selinux_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "selinux_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_add_opt",
      "external": false,
      "loc": "security/selinux/hooks.c:993",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583317120,
      "name": "selinux_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 18446744071583351344,
      "name": "selinux_add_opt.cold",
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
int selinux_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "selinux_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_add_opt",
      "external": false,
      "loc": "security/selinux/hooks.c:995",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583422448,
      "name": "selinux_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 18446744071583457312,
      "name": "selinux_add_opt.cold",
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
int selinux_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "selinux_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_add_opt",
      "external": false,
      "loc": "security/selinux/hooks.c:946",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583768288,
      "name": "selinux_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 18446744071583800688,
      "name": "selinux_add_opt.cold",
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
int selinux_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "selinux_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_add_opt",
      "external": false,
      "loc": "security/selinux/hooks.c:947",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583887968,
      "name": "selinux_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 18446744071591363098,
      "name": "selinux_add_opt.cold",
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
int selinux_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "selinux_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_add_opt",
      "external": false,
      "loc": "security/selinux/hooks.c:1005",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583914400,
      "name": "selinux_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 18446744071591305881,
      "name": "selinux_add_opt.cold",
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
int selinux_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "selinux_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_add_opt",
      "external": false,
      "loc": "security/selinux/hooks.c:987",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584277696,
      "name": "selinux_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071592294004,
      "name": "selinux_add_opt.cold",
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
int selinux_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "selinux_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_add_opt",
      "external": false,
      "loc": "security/selinux/hooks.c:948",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584904672,
      "name": "selinux_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
    },
    {
      "addr": 18446744071594076331,
      "name": "selinux_add_opt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int selinux_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "selinux_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_add_opt",
      "external": false,
      "loc": "security/selinux/hooks.c:953",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585612944,
      "name": "selinux_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    },
    {
      "addr": 18446744071596094412,
      "name": "selinux_add_opt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int selinux_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "selinux_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_add_opt",
      "external": false,
      "loc": "security/selinux/hooks.c:965",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585844016,
      "name": "selinux_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
    },
    {
      "addr": 18446744071596617721,
      "name": "selinux_add_opt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int selinux_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "selinux_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_add_opt",
      "external": false,
      "loc": "security/selinux/hooks.c:1006",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586094880,
      "name": "selinux_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
    },
    {
      "addr": 18446744071597523725,
      "name": "selinux_add_opt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int selinux_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "selinux_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495179544,
      "name": "selinux_add_opt",
      "external": false,
      "loc": "security/selinux/hooks.c:995",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495179544,
      "name": "selinux_add_opt",
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
int selinux_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "selinux_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228566928,
      "name": "selinux_add_opt",
      "external": false,
      "loc": "security/selinux/hooks.c:995",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228566928,
      "name": "selinux_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int selinux_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "selinux_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289164928,
      "name": "selinux_add_opt",
      "external": false,
      "loc": "security/selinux/hooks.c:995",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289164928,
      "name": "selinux_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
int selinux_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "selinux_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274420312,
      "name": "selinux_add_opt",
      "external": false,
      "loc": "security/selinux/hooks.c:995",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274420312,
      "name": "selinux_add_opt",
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
int selinux_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "selinux_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_add_opt",
      "external": false,
      "loc": "security/selinux/hooks.c:995",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583391184,
      "name": "selinux_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 18446744071583426048,
      "name": "selinux_add_opt.cold",
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
int selinux_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "selinux_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_add_opt",
      "external": false,
      "loc": "security/selinux/hooks.c:995",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583328272,
      "name": "selinux_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 18446744071583363120,
      "name": "selinux_add_opt.cold",
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
int selinux_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "selinux_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_add_opt",
      "external": false,
      "loc": "security/selinux/hooks.c:995",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583374960,
      "name": "selinux_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 18446744071583409824,
      "name": "selinux_add_opt.cold",
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
int selinux_add_opt(int token, const char * s, void * * mnt_opts)
```

```json
{
  "name": "selinux_add_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_add_opt",
      "external": false,
      "loc": "security/selinux/hooks.c:995",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_fs_context_parse_param",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583468544,
      "name": "selinux_add_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 18446744071583505984,
      "name": "selinux_add_opt.cold",
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int selinux_add_opt(int token, const char * s, void * * mnt_opts)
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
