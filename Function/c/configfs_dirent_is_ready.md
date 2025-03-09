# Function: <code>configfs_dirent_is_ready</code>

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
int configfs_dirent_is_ready(struct configfs_dirent * sd)
```

```json
{
  "name": "configfs_dirent_is_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581861984,
      "name": "configfs_dirent_is_ready",
      "external": true,
      "loc": "fs/configfs/dir.c:339",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581861984,
      "name": "configfs_dirent_is_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int configfs_dirent_is_ready(struct configfs_dirent * sd)
```

```json
{
  "name": "configfs_dirent_is_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582011872,
      "name": "configfs_dirent_is_ready",
      "external": true,
      "loc": "fs/configfs/dir.c:339",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582011872,
      "name": "configfs_dirent_is_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent * sd)
```

```json
{
  "name": "configfs_dirent_is_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582197005,
      "name": "configfs_dirent_is_ready",
      "external": true,
      "loc": "fs/configfs/dir.c:339",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_mkdir"
      ],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582201920,
      "name": "configfs_dirent_is_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent * sd)
```

```json
{
  "name": "configfs_dirent_is_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582292301,
      "name": "configfs_dirent_is_ready",
      "external": true,
      "loc": "fs/configfs/dir.c:339",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_mkdir"
      ],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582297040,
      "name": "configfs_dirent_is_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent * sd)
```

```json
{
  "name": "configfs_dirent_is_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582455659,
      "name": "configfs_dirent_is_ready",
      "external": true,
      "loc": "fs/configfs/dir.c:354",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_mkdir"
      ],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582463168,
      "name": "configfs_dirent_is_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent * sd)
```

```json
{
  "name": "configfs_dirent_is_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582555051,
      "name": "configfs_dirent_is_ready",
      "external": true,
      "loc": "fs/configfs/dir.c:343",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_mkdir"
      ],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582562464,
      "name": "configfs_dirent_is_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent * sd)
```

```json
{
  "name": "configfs_dirent_is_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582862779,
      "name": "configfs_dirent_is_ready",
      "external": true,
      "loc": "fs/configfs/dir.c:343",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_lookup"
      ],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582870368,
      "name": "configfs_dirent_is_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent * sd)
```

```json
{
  "name": "configfs_dirent_is_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582935771,
      "name": "configfs_dirent_is_ready",
      "external": true,
      "loc": "fs/configfs/dir.c:344",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_lookup"
      ],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582943280,
      "name": "configfs_dirent_is_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent * sd)
```

```json
{
  "name": "configfs_dirent_is_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582963803,
      "name": "configfs_dirent_is_ready",
      "external": true,
      "loc": "fs/configfs/dir.c:342",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_lookup"
      ],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582970864,
      "name": "configfs_dirent_is_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent * sd)
```

```json
{
  "name": "configfs_dirent_is_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583301067,
      "name": "configfs_dirent_is_ready",
      "external": true,
      "loc": "fs/configfs/dir.c:350",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_lookup"
      ],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583306464,
      "name": "configfs_dirent_is_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent * sd)
```

```json
{
  "name": "configfs_dirent_is_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583804699,
      "name": "configfs_dirent_is_ready",
      "external": true,
      "loc": "fs/configfs/dir.c:350",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_lookup"
      ],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583813264,
      "name": "configfs_dirent_is_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent * sd)
```

```json
{
  "name": "configfs_dirent_is_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584425499,
      "name": "configfs_dirent_is_ready",
      "external": true,
      "loc": "fs/configfs/dir.c:351",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_lookup"
      ],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584434736,
      "name": "configfs_dirent_is_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent * sd)
```

```json
{
  "name": "configfs_dirent_is_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584654190,
      "name": "configfs_dirent_is_ready",
      "external": true,
      "loc": "fs/configfs/dir.c:351",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_lookup"
      ],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584663472,
      "name": "configfs_dirent_is_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent * sd)
```

```json
{
  "name": "configfs_dirent_is_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584886849,
      "name": "configfs_dirent_is_ready",
      "external": true,
      "loc": "fs/configfs/dir.c:351",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_lookup"
      ],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584896176,
      "name": "configfs_dirent_is_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent * sd)
```

```json
{
  "name": "configfs_dirent_is_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494196436,
      "name": "configfs_dirent_is_ready",
      "external": true,
      "loc": "fs/configfs/dir.c:343",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_mkdir"
      ],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494205512,
      "name": "configfs_dirent_is_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int configfs_dirent_is_ready(struct configfs_dirent * sd)
```

```json
{
  "name": "configfs_dirent_is_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227637308,
      "name": "configfs_dirent_is_ready",
      "external": true,
      "loc": "fs/configfs/dir.c:343",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227637308,
      "name": "configfs_dirent_is_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int configfs_dirent_is_ready(struct configfs_dirent * sd)
```

```json
{
  "name": "configfs_dirent_is_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287897552,
      "name": "configfs_dirent_is_ready",
      "external": true,
      "loc": "fs/configfs/dir.c:343",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287897552,
      "name": "configfs_dirent_is_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int configfs_dirent_is_ready(struct configfs_dirent * sd)
```

```json
{
  "name": "configfs_dirent_is_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273664244,
      "name": "configfs_dirent_is_ready",
      "external": true,
      "loc": "fs/configfs/dir.c:343",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273664244,
      "name": "configfs_dirent_is_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent * sd)
```

```json
{
  "name": "configfs_dirent_is_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582523787,
      "name": "configfs_dirent_is_ready",
      "external": true,
      "loc": "fs/configfs/dir.c:343",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_mkdir"
      ],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582531200,
      "name": "configfs_dirent_is_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent * sd)
```

```json
{
  "name": "configfs_dirent_is_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582460955,
      "name": "configfs_dirent_is_ready",
      "external": true,
      "loc": "fs/configfs/dir.c:343",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_mkdir"
      ],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582468368,
      "name": "configfs_dirent_is_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent * sd)
```

```json
{
  "name": "configfs_dirent_is_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582514267,
      "name": "configfs_dirent_is_ready",
      "external": true,
      "loc": "fs/configfs/dir.c:343",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_mkdir"
      ],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521680,
      "name": "configfs_dirent_is_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent * sd)
```

```json
{
  "name": "configfs_dirent_is_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582594123,
      "name": "configfs_dirent_is_ready",
      "external": true,
      "loc": "fs/configfs/dir.c:343",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_mkdir"
      ],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582602368,
      "name": "configfs_dirent_is_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int configfs_dirent_is_ready(struct configfs_dirent * sd)
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
