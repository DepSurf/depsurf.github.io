# Function: <code>put_fragment</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void put_fragment(struct configfs_fragment * frag)
```

```json
{
  "name": "put_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582456608,
      "name": "put_fragment",
      "external": true,
      "loc": "fs/configfs/dir.c:167",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/inode.c:configfs_hash_and_remove",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_dir_close",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:configfs_d_iput",
        "fs/configfs/symlink.c:configfs_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582456608,
      "name": "put_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void put_fragment(struct configfs_fragment * frag)
```

```json
{
  "name": "put_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582556000,
      "name": "put_fragment",
      "external": true,
      "loc": "fs/configfs/dir.c:166",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/inode.c:configfs_hash_and_remove",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_dir_close",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_d_iput",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:create_link",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582556000,
      "name": "put_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void put_fragment(struct configfs_fragment * frag)
```

```json
{
  "name": "put_fragment",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582870136,
      "name": "put_fragment",
      "external": true,
      "loc": "fs/configfs/dir.c:166",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_dir_close",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_lookup",
        "fs/configfs/dir.c:configfs_d_iput"
      ],
      "caller_func": [
        "fs/configfs/inode.c:configfs_hash_and_remove",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:create_link",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582866896,
      "name": "put_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void put_fragment(struct configfs_fragment * frag)
```

```json
{
  "name": "put_fragment",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582943048,
      "name": "put_fragment",
      "external": true,
      "loc": "fs/configfs/dir.c:166",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_dir_close",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_lookup",
        "fs/configfs/dir.c:configfs_d_iput"
      ],
      "caller_func": [
        "fs/configfs/inode.c:configfs_hash_and_remove",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:create_link",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582939808,
      "name": "put_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void put_fragment(struct configfs_fragment * frag)
```

```json
{
  "name": "put_fragment",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582969944,
      "name": "put_fragment",
      "external": true,
      "loc": "fs/configfs/dir.c:164",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_dir_close",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_lookup",
        "fs/configfs/dir.c:configfs_d_iput"
      ],
      "caller_func": [
        "fs/configfs/inode.c:configfs_hash_and_remove",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:create_link",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582967488,
      "name": "put_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void put_fragment(struct configfs_fragment * frag)
```

```json
{
  "name": "put_fragment",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583305544,
      "name": "put_fragment",
      "external": true,
      "loc": "fs/configfs/dir.c:172",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_dir_close",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_lookup",
        "fs/configfs/dir.c:configfs_d_iput"
      ],
      "caller_func": [
        "fs/configfs/inode.c:configfs_hash_and_remove",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:create_link",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583303152,
      "name": "put_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void put_fragment(struct configfs_fragment * frag)
```

```json
{
  "name": "put_fragment",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583812281,
      "name": "put_fragment",
      "external": true,
      "loc": "fs/configfs/dir.c:172",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_dir_close",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_lookup",
        "fs/configfs/dir.c:configfs_d_iput"
      ],
      "caller_func": [
        "fs/configfs/inode.c:configfs_hash_and_remove",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:create_link",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583809808,
      "name": "put_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void put_fragment(struct configfs_fragment * frag)
```

```json
{
  "name": "put_fragment",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584433689,
      "name": "put_fragment",
      "external": true,
      "loc": "fs/configfs/dir.c:172",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_dir_close",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_lookup",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:configfs_d_iput"
      ],
      "caller_func": [
        "fs/configfs/inode.c:configfs_hash_and_remove",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:create_link",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584431040,
      "name": "put_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void put_fragment(struct configfs_fragment * frag)
```

```json
{
  "name": "put_fragment",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584662425,
      "name": "put_fragment",
      "external": true,
      "loc": "fs/configfs/dir.c:172",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_dir_close",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_lookup",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:configfs_d_iput"
      ],
      "caller_func": [
        "fs/configfs/inode.c:configfs_hash_and_remove",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:create_link",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584659792,
      "name": "put_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void put_fragment(struct configfs_fragment * frag)
```

```json
{
  "name": "put_fragment",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584895098,
      "name": "put_fragment",
      "external": true,
      "loc": "fs/configfs/dir.c:172",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_dir_close",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_lookup",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:configfs_d_iput"
      ],
      "caller_func": [
        "fs/configfs/inode.c:configfs_hash_and_remove",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:create_link",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584892544,
      "name": "put_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void put_fragment(struct configfs_fragment * frag)
```

```json
{
  "name": "put_fragment",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494203940,
      "name": "put_fragment",
      "external": true,
      "loc": "fs/configfs/dir.c:166",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_dir_close",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_d_iput"
      ],
      "caller_func": [
        "fs/configfs/inode.c:configfs_hash_and_remove",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_dir_close",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_d_iput",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:create_link",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494194408,
      "name": "put_fragment.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446603336494201952,
      "name": "put_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void put_fragment(struct configfs_fragment * frag)
```

```json
{
  "name": "put_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227632048,
      "name": "put_fragment",
      "external": true,
      "loc": "fs/configfs/dir.c:166",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/inode.c:configfs_hash_and_remove",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_dir_close",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:detach_attrs",
        "fs/configfs/dir.c:configfs_remove_dirent",
        "fs/configfs/dir.c:configfs_d_iput",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:create_link",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227632048,
      "name": "put_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void put_fragment(struct configfs_fragment * frag)
```

```json
{
  "name": "put_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287889136,
      "name": "put_fragment",
      "external": true,
      "loc": "fs/configfs/dir.c:166",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/inode.c:configfs_hash_and_remove",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_dir_close",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_remove_dirent",
        "fs/configfs/dir.c:configfs_d_iput",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:create_link",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287889136,
      "name": "put_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void put_fragment(struct configfs_fragment * frag)
```

```json
{
  "name": "put_fragment",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273664000,
      "name": "put_fragment",
      "external": true,
      "loc": "fs/configfs/dir.c:166",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_dir_close",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_remove_dirent",
        "fs/configfs/dir.c:configfs_d_iput"
      ],
      "caller_func": [
        "fs/configfs/inode.c:configfs_hash_and_remove",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273662296,
      "name": "put_fragment",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void put_fragment(struct configfs_fragment * frag)
```

```json
{
  "name": "put_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582524736,
      "name": "put_fragment",
      "external": true,
      "loc": "fs/configfs/dir.c:166",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/inode.c:configfs_hash_and_remove",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_dir_close",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_d_iput",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:create_link",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582524736,
      "name": "put_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void put_fragment(struct configfs_fragment * frag)
```

```json
{
  "name": "put_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582461904,
      "name": "put_fragment",
      "external": true,
      "loc": "fs/configfs/dir.c:166",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/inode.c:configfs_hash_and_remove",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_dir_close",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_d_iput",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:create_link",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582461904,
      "name": "put_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void put_fragment(struct configfs_fragment * frag)
```

```json
{
  "name": "put_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582515216,
      "name": "put_fragment",
      "external": true,
      "loc": "fs/configfs/dir.c:166",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/inode.c:configfs_hash_and_remove",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_dir_close",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_d_iput",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:create_link",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582515216,
      "name": "put_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void put_fragment(struct configfs_fragment * frag)
```

```json
{
  "name": "put_fragment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582595840,
      "name": "put_fragment",
      "external": true,
      "loc": "fs/configfs/dir.c:166",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/inode.c:configfs_hash_and_remove",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_dir_close",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_d_iput",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:create_link",
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582595840,
      "name": "put_fragment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void put_fragment(struct configfs_fragment * frag)
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
