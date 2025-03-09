# Function: <code>make_bad_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581112880,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:170",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581112880,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581278592,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:170",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581278592,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581357008,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:197",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:ext4_iget",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581357008,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581412320,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:197",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:ext4_iget",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581412320,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581553936,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:198",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:ext4_iget",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581553936,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581710112,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:198",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:ext4_iget",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581710112,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581796624,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:198",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796624,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581915568,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:198",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581915568,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581987952,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:198",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581987952,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582221552,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:199",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/super.c:ext4_get_journal_inode",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup_interpose",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582221552,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582269056,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:199",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/super.c:ext4_get_journal_inode",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup_interpose"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269056,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582294576,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:207",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/super.c:ext4_get_journal_inode",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582294576,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582613392,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:207",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/super.c:ext4_get_journal_inode",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582613392,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583147312,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:207",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/super.c:ext4_get_journal_inode",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583147312,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583720352,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:207",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/super.c:ext4_get_journal_inode",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583720352,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583937376,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:207",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/super.c:ext4_get_journal_inode",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583937376,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584144069,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:206",
      "file": "fs/bad_inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/bad_inode.c:iget_failed"
      ],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/super.c:ext4_get_journal_inode",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_do_statx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584143696,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493500648,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:198",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493500648,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227058640,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:198",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227058640,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287063168,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:198",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287063168,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273173570,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:198",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273173570,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581956688,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:198",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581956688,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581894256,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:198",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581894256,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581948000,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:198",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581948000,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void make_bad_inode(struct inode * inode)
```

```json
{
  "name": "make_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582018032,
      "name": "make_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:198",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582018032,
      "name": "make_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
