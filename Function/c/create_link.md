# Function: <code>create_link</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581865183,
      "name": "create_link",
      "external": false,
      "loc": "fs/configfs/symlink.c:72",
      "file": "fs/configfs/symlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:configfs_symlink"
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
  "name": "create_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582015001,
      "name": "create_link",
      "external": false,
      "loc": "fs/configfs/symlink.c:72",
      "file": "fs/configfs/symlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:configfs_symlink"
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
  "name": "create_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582203429,
      "name": "create_link",
      "external": false,
      "loc": "fs/configfs/symlink.c:72",
      "file": "fs/configfs/symlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:configfs_symlink"
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
  "name": "create_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582298513,
      "name": "create_link",
      "external": false,
      "loc": "fs/configfs/symlink.c:72",
      "file": "fs/configfs/symlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:configfs_symlink"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582464798,
      "name": "create_link",
      "external": false,
      "loc": "fs/configfs/symlink.c:58",
      "file": "fs/configfs/symlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:configfs_symlink"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int create_link(struct config_item * parent_item, struct config_item * item, struct dentry * dentry)
```

```json
{
  "name": "create_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582562752,
      "name": "create_link",
      "external": false,
      "loc": "fs/configfs/symlink.c:79",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582562752,
      "name": "create_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
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
int create_link(struct config_item * parent_item, struct config_item * item, struct dentry * dentry)
```

```json
{
  "name": "create_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582871104,
      "name": "create_link",
      "external": false,
      "loc": "fs/configfs/symlink.c:79",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582871104,
      "name": "create_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
int create_link(struct config_item * parent_item, struct config_item * item, struct dentry * dentry)
```

```json
{
  "name": "create_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582943968,
      "name": "create_link",
      "external": false,
      "loc": "fs/configfs/symlink.c:79",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582943968,
      "name": "create_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
int create_link(struct config_item * parent_item, struct config_item * item, struct dentry * dentry)
```

```json
{
  "name": "create_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582971472,
      "name": "create_link",
      "external": false,
      "loc": "fs/configfs/symlink.c:77",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582971472,
      "name": "create_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
int create_link(struct config_item * parent_item, struct config_item * item, struct dentry * dentry)
```

```json
{
  "name": "create_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583307072,
      "name": "create_link",
      "external": false,
      "loc": "fs/configfs/symlink.c:77",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583307072,
      "name": "create_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
int create_link(struct config_item * parent_item, struct config_item * item, struct dentry * dentry)
```

```json
{
  "name": "create_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583813936,
      "name": "create_link",
      "external": false,
      "loc": "fs/configfs/symlink.c:77",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583813936,
      "name": "create_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 443
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
int create_link(struct config_item * parent_item, struct config_item * item, struct dentry * dentry)
```

```json
{
  "name": "create_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584435600,
      "name": "create_link",
      "external": false,
      "loc": "fs/configfs/symlink.c:77",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584435600,
      "name": "create_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 443
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
int create_link(struct config_item * parent_item, struct config_item * item, struct dentry * dentry)
```

```json
{
  "name": "create_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584664368,
      "name": "create_link",
      "external": false,
      "loc": "fs/configfs/symlink.c:77",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584664368,
      "name": "create_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 443
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
int create_link(struct config_item * parent_item, struct config_item * item, struct dentry * dentry)
```

```json
{
  "name": "create_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584897088,
      "name": "create_link",
      "external": false,
      "loc": "fs/configfs/symlink.c:77",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584897088,
      "name": "create_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
int create_link(struct config_item * parent_item, struct config_item * item, struct dentry * dentry)
```

```json
{
  "name": "create_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494206984,
      "name": "create_link",
      "external": false,
      "loc": "fs/configfs/symlink.c:79",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494206984,
      "name": "create_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
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
int create_link(struct config_item * parent_item, struct config_item * item, struct dentry * dentry)
```

```json
{
  "name": "create_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227639308,
      "name": "create_link",
      "external": false,
      "loc": "fs/configfs/symlink.c:79",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227639308,
      "name": "create_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1012
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
int create_link(struct config_item * parent_item, struct config_item * item, struct dentry * dentry)
```

```json
{
  "name": "create_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287900880,
      "name": "create_link",
      "external": false,
      "loc": "fs/configfs/symlink.c:79",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287900880,
      "name": "create_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1312
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "create_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273666776,
      "name": "create_link",
      "external": false,
      "loc": "fs/configfs/symlink.c:79",
      "file": "fs/configfs/symlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:configfs_symlink"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int create_link(struct config_item * parent_item, struct config_item * item, struct dentry * dentry)
```

```json
{
  "name": "create_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582531488,
      "name": "create_link",
      "external": false,
      "loc": "fs/configfs/symlink.c:79",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582531488,
      "name": "create_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
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
int create_link(struct config_item * parent_item, struct config_item * item, struct dentry * dentry)
```

```json
{
  "name": "create_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582468656,
      "name": "create_link",
      "external": false,
      "loc": "fs/configfs/symlink.c:79",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582468656,
      "name": "create_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
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
int create_link(struct config_item * parent_item, struct config_item * item, struct dentry * dentry)
```

```json
{
  "name": "create_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582521968,
      "name": "create_link",
      "external": false,
      "loc": "fs/configfs/symlink.c:79",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521968,
      "name": "create_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
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
int create_link(struct config_item * parent_item, struct config_item * item, struct dentry * dentry)
```

```json
{
  "name": "create_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582602656,
      "name": "create_link",
      "external": false,
      "loc": "fs/configfs/symlink.c:79",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582602656,
      "name": "create_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 760
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int create_link(struct config_item * parent_item, struct config_item * item, struct dentry * dentry)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int create_link(struct config_item * parent_item, struct config_item * item, struct dentry * dentry)
```
</details>
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
