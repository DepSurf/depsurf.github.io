# Function: <code>set_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581039287,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:808",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:follow_dotdot",
        "fs/namei.c:path_init",
        "fs/namei.c:link_path_walk"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581192800,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:813",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:path_init",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581192800,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581270016,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:813",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:path_init",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581270016,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581318976,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:825",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:path_init",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581318976,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581459200,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:826",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:path_init",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459200,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581625120,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:810",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:path_init",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581625120,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
void set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581711696,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:810",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:path_init",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581711696,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
void set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581829376,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:808",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:path_init",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581829376,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581901824,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:801",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:path_init",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901824,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
int set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582130272,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:836",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:nd_jump_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582130272,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
int set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582177232,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:836",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:nd_jump_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582177232,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582201120,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:896",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:nd_jump_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582201120,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582518864,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:924",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:nd_jump_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582518864,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583043984,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:918",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:handle_dots",
        "fs/namei.c:nd_jump_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583043984,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583609024,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:926",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:handle_dots",
        "fs/namei.c:nd_jump_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583609024,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583833344,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:929",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:handle_dots",
        "fs/namei.c:nd_jump_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583833344,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584039360,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:932",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:handle_dots",
        "fs/namei.c:nd_jump_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584039360,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493382328,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:801",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:path_init",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493382328,
      "name": "set_root",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226961108,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:801",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:path_init",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226961108,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286922704,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:801",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:path_init",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286922704,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
void set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273098496,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:801",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:path_init",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273098496,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581870560,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:801",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:path_init",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581870560,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581808160,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:801",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:path_init",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581808160,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581861872,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:801",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:path_init",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581861872,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void set_root(struct nameidata * nd)
```

```json
{
  "name": "set_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581924752,
      "name": "set_root",
      "external": false,
      "loc": "fs/namei.c:801",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:path_init",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581924752,
      "name": "set_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void set_root(struct nameidata * nd)
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
