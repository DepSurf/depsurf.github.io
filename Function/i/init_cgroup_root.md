# Function: <code>init_cgroup_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void init_cgroup_root(struct cgroup_root * root, struct cgroup_sb_opts * opts)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579973648,
      "name": "init_cgroup_root",
      "external": false,
      "loc": "kernel/cgroup.c:1938",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_mount",
        "kernel/cgroup.c:cgroup_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973648,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void init_cgroup_root(struct cgroup_root * root, struct cgroup_sb_opts * opts)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580003312,
      "name": "init_cgroup_root",
      "external": false,
      "loc": "kernel/cgroup.c:1962",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_init_early",
        "kernel/cgroup.c:cgroup_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580003312,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void init_cgroup_root(struct cgroup_root * root, struct cgroup_sb_opts * opts)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580034896,
      "name": "init_cgroup_root",
      "external": false,
      "loc": "kernel/cgroup.c:1970",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_init_early",
        "kernel/cgroup.c:cgroup_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034896,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void init_cgroup_root(struct cgroup_root * root, struct cgroup_sb_opts * opts)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580042352,
      "name": "init_cgroup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1681",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init_early",
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580042352,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void init_cgroup_root(struct cgroup_root * root, struct cgroup_sb_opts * opts)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580091856,
      "name": "init_cgroup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1855",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init_early",
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580091856,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void init_cgroup_root(struct cgroup_root * root, struct cgroup_sb_opts * opts)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580150944,
      "name": "init_cgroup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1873",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init_early",
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150944,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void init_cgroup_root(struct cgroup_root * root, struct cgroup_sb_opts * opts)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580198576,
      "name": "init_cgroup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1911",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init_early",
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580198576,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void init_cgroup_root(struct cgroup_fs_context * ctx)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580245456,
      "name": "init_cgroup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1970",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init_early",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580245456,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void init_cgroup_root(struct cgroup_fs_context * ctx)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580293680,
      "name": "init_cgroup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1970",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init_early",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293680,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void init_cgroup_root(struct cgroup_fs_context * ctx)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580364784,
      "name": "init_cgroup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1908",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init_early",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580364784,
      "name": "init_cgroup_root",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void init_cgroup_root(struct cgroup_fs_context * ctx)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_cgroup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1905",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init_early",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591315217,
      "name": "init_cgroup_root.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580351664,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void init_cgroup_root(struct cgroup_fs_context * ctx)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_cgroup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1912",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init_early",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591257403,
      "name": "init_cgroup_root.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580354784,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void init_cgroup_root(struct cgroup_fs_context * ctx)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_cgroup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1966",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init_early",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592160974,
      "name": "init_cgroup_root.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071580511840,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
void init_cgroup_root(struct cgroup_fs_context * ctx)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_cgroup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1970",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init_early",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593934002,
      "name": "init_cgroup_root.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071580708448,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
void init_cgroup_root(struct cgroup_fs_context * ctx)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_cgroup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2026",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init_early",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595999584,
      "name": "init_cgroup_root.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580981808,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void init_cgroup_root(struct cgroup_fs_context * ctx)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_cgroup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2034",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init_early",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596517718,
      "name": "init_cgroup_root.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581069696,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void init_cgroup_root(struct cgroup_fs_context * ctx)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_cgroup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2043",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init_early",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597417940,
      "name": "init_cgroup_root.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581167168,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
void init_cgroup_root(struct cgroup_fs_context * ctx)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491543832,
      "name": "init_cgroup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1970",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init_early",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491543832,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void init_cgroup_root(struct cgroup_fs_context * ctx)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225508728,
      "name": "init_cgroup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1970",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init_early",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225508728,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void init_cgroup_root(struct cgroup_fs_context * ctx)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284513984,
      "name": "init_cgroup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1970",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init_early",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284513984,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void init_cgroup_root(struct cgroup_fs_context * ctx)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271959446,
      "name": "init_cgroup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1970",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init_early",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271959446,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void init_cgroup_root(struct cgroup_fs_context * ctx)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580262480,
      "name": "init_cgroup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1970",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init_early",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580262480,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void init_cgroup_root(struct cgroup_fs_context * ctx)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580209984,
      "name": "init_cgroup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1970",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init_early",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580209984,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void init_cgroup_root(struct cgroup_fs_context * ctx)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580253728,
      "name": "init_cgroup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1970",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init_early",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580253728,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void init_cgroup_root(struct cgroup_fs_context * ctx)
```

```json
{
  "name": "init_cgroup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580307072,
      "name": "init_cgroup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1970",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init_early",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580307072,
      "name": "init_cgroup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct cgroup_fs_context * ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct cgroup_root * root</code>
</li>
<li>
<b>Param removed. </b>
<code>struct cgroup_sb_opts * opts</code>
</li>
</ul>
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
