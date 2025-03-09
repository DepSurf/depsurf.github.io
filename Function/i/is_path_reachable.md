# Function: <code>is_path_reachable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581138336,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:2937",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:path_is_under",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:SyS_pivot_root",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581138336,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581303872,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:2924",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:path_is_under",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581303872,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581382864,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:3068",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:path_is_under",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581382864,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581438112,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:3010",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:path_is_under",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581438112,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581580000,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:3083",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:path_is_under",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581580000,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581735968,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:3120",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:path_is_under",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581735968,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581822656,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:3092",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:path_is_under",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581822656,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581946656,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:3549",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:path_is_under",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581946656,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582019232,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:3580",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:path_is_under",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582019232,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582232833,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:3633",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:path_is_under"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582254800,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582281393,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:3655",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:path_is_under"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582304096,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582308049,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:3701",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:path_is_under"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582331696,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582627377,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:3780",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:path_is_under"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582652288,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583163865,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:3823",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:path_is_under"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583191328,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583739257,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:3929",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:path_is_under"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583766672,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583955833,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:4121",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:path_is_under"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583983840,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584171856,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:4134",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_listmount",
        "fs/namespace.c:__ia32_sys_listmount",
        "fs/namespace.c:__x64_sys_listmount",
        "fs/namespace.c:__x64_sys_listmount",
        "fs/namespace.c:do_statmount",
        "fs/namespace.c:path_is_under"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584196384,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493540816,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:3580",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__arm64_sys_pivot_root",
        "fs/namespace.c:__arm64_sys_pivot_root",
        "fs/namespace.c:path_is_under",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493540816,
      "name": "is_path_reachable",
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227091972,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:3580",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:path_is_under",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227091972,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287111120,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:3580",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:path_is_under",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287111120,
      "name": "is_path_reachable",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273206012,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:3580",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:path_is_under",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273206012,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581987968,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:3580",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:path_is_under",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581987968,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581925536,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:3580",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:path_is_under",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581925536,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581979248,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:3580",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:path_is_under",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581979248,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool is_path_reachable(struct mount * mnt, struct dentry * dentry, const struct path * root)
```

```json
{
  "name": "is_path_reachable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582049744,
      "name": "is_path_reachable",
      "external": true,
      "loc": "fs/namespace.c:3580",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:path_is_under",
        "fs/pnode.c:get_dominating_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582049744,
      "name": "is_path_reachable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
