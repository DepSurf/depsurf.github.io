# Function: <code>debugfs_rename</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582112384,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:667",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582112384,
      "name": "debugfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 529
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
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582328096,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:728",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582328096,
      "name": "debugfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 529
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
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582418896,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:728",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582418896,
      "name": "debugfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582502240,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:762",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582502240,
      "name": "debugfs_rename",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582653552,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:786",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582653552,
      "name": "debugfs_rename",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582846880,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:809",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582846880,
      "name": "debugfs_rename",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582955056,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:812",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582955056,
      "name": "debugfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 683
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
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583135504,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:832",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583135504,
      "name": "debugfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583241680,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:834",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583241680,
      "name": "debugfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583569696,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:727",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_migrate_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583569696,
      "name": "debugfs_rename.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 705
    },
    {
      "addr": 18446744071583570416,
      "name": "debugfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583688656,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:752",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_migrate_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583688656,
      "name": "debugfs_rename.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
    },
    {
      "addr": 18446744071583689296,
      "name": "debugfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583713168,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:756",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583713168,
      "name": "debugfs_rename.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 667
    },
    {
      "addr": 18446744071583713840,
      "name": "debugfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584073984,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:756",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584073984,
      "name": "debugfs_rename.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 712
    },
    {
      "addr": 18446744071584074704,
      "name": "debugfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584665712,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:766",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584665712,
      "name": "debugfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 929
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
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585348464,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:811",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585348464,
      "name": "debugfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 929
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
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585578608,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:811",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585578608,
      "name": "debugfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 959
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
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585817360,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:858",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585817360,
      "name": "debugfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 959
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
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494965496,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:834",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494965496,
      "name": "debugfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228373596,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:834",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228373596,
      "name": "debugfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 724
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288844688,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:834",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288844688,
      "name": "debugfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1008
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274266690,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:834",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274266690,
      "name": "debugfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583210416,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:834",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583210416,
      "name": "debugfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583147568,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:834",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583147568,
      "name": "debugfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583194448,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:834",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583194448,
      "name": "debugfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
struct dentry * debugfs_rename(struct dentry * old_dir, struct dentry * old_dentry, struct dentry * new_dir, const char * new_name)
```

```json
{
  "name": "debugfs_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583288736,
      "name": "debugfs_rename",
      "external": true,
      "loc": "fs/debugfs/inode.c:834",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583288736,
      "name": "debugfs_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
