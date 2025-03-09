# Function: <code>__dquot_free_space</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581412928,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1800",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581412928,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581588096,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1808",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581588096,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581676480,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1805",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581676480,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581741392,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1831",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_free_quota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581741392,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 645
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581887792,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1843",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581887792,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 699
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582061472,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1840",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_free_quota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582061472,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 663
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582155568,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1840",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_free_quota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582155568,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 663
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582318240,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1848",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_free_quota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582318240,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582417328,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1850",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_free_quota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582417328,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582712912,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1848",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582712912,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 762
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582784080,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1849",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582784080,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 762
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582811184,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1847",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_release_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582811184,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 762
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583140576,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1852",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_free_quota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583140576,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 897
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583639712,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1862",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_free_quota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583639712,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 981
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584245152,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1862",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_free_quota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584245152,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 878
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584475760,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1920",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_free_quota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584475760,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 878
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584698720,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1874",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_inode_unacct_blocks",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_free_quota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584698720,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 878
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494029040,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1850",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_free_quota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494029040,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 860
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227499936,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1850",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_free_quota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227499936,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1000
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287692544,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1850",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_free_quota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287692544,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1056
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273531984,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1850",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_free_quota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273531984,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 702
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582386064,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1850",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_free_quota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582386064,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582323760,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1850",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_free_quota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582323760,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582376544,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1850",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_free_quota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582376544,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
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
void __dquot_free_space(struct inode * inode, qsize_t number, int flags)
```

```json
{
  "name": "__dquot_free_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582465824,
      "name": "__dquot_free_space",
      "external": true,
      "loc": "fs/quota/dquot.c:1850",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_free_quota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582465824,
      "name": "__dquot_free_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 679
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
