# Function: <code>follow_up</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581036752,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1055",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_dotdot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581036752,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581196976,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1071",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581196976,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581274256,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1071",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581274256,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581323216,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1083",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323216,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581459824,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1084",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component",
        "fs/devpts/inode.c:devpts_mntget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459824,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581625936,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1071",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component",
        "fs/devpts/inode.c:devpts_mntget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581625936,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581712496,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1112",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component",
        "fs/devpts/inode.c:devpts_mntget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581712496,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581830192,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1110",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component",
        "fs/devpts/inode.c:devpts_mntget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581830192,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581902656,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1105",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component",
        "fs/devpts/inode.c:devpts_mntget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902656,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582131168,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1102",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mntget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582131168,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582177712,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1102",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mntget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582177712,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582203520,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1187",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mntget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582203520,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582521296,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1215",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mntget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521296,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583038240,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1259",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mntget",
        "security/landlock/fs.c:check_access_path_dual"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583038240,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583603472,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1267",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mntget",
        "security/landlock/fs.c:is_access_to_paths_allowed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583603472,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583820544,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1270",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mntget",
        "security/landlock/fs.c:is_access_to_paths_allowed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583820544,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584026496,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1273",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mntget",
        "security/landlock/fs.c:is_access_to_paths_allowed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584026496,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493381752,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1105",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component",
        "fs/devpts/inode.c:devpts_mntget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493381752,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226968216,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1105",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component",
        "fs/devpts/inode.c:devpts_mntget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226968216,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286936752,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1105",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component",
        "fs/devpts/inode.c:devpts_mntget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286936752,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273098740,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1105",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component",
        "fs/devpts/inode.c:devpts_mntget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273098740,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581871392,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1105",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component",
        "fs/devpts/inode.c:devpts_mntget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581871392,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581808992,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1105",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component",
        "fs/devpts/inode.c:devpts_mntget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581808992,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581862704,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1105",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component",
        "fs/devpts/inode.c:devpts_mntget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581862704,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int follow_up(struct path * path)
```

```json
{
  "name": "follow_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581925120,
      "name": "follow_up",
      "external": true,
      "loc": "fs/namei.c:1105",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component",
        "fs/devpts/inode.c:devpts_mntget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581925120,
      "name": "follow_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
