# Function: <code>jbd2_handle_buffer_credits</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int jbd2_handle_buffer_credits(handle_t * handle)
```

```json
{
  "name": "jbd2_handle_buffer_credits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582895057,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1633",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved"
      ],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata"
      ]
    },
    {
      "addr": 18446744071583277503,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1633",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583296860,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1633",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582892448,
      "name": "jbd2_handle_buffer_credits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int jbd2_handle_buffer_credits(handle_t * handle)
```

```json
{
  "name": "jbd2_handle_buffer_credits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582967313,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1768",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved"
      ],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata"
      ]
    },
    {
      "addr": 18446744071583378650,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1768",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583412156,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1768",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582964784,
      "name": "jbd2_handle_buffer_credits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int jbd2_handle_buffer_credits(handle_t * handle)
```

```json
{
  "name": "jbd2_handle_buffer_credits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582993365,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1777",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved"
      ],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata"
      ]
    },
    {
      "addr": 18446744071583401226,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1777",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583435004,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1777",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591289665,
      "name": "jbd2_handle_buffer_credits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int jbd2_handle_buffer_credits(handle_t * handle)
```

```json
{
  "name": "jbd2_handle_buffer_credits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583329829,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1816",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved"
      ],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata"
      ]
    },
    {
      "addr": 18446744071583745546,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1816",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583784332,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1816",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592250889,
      "name": "jbd2_handle_buffer_credits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int jbd2_handle_buffer_credits(handle_t * handle)
```

```json
{
  "name": "jbd2_handle_buffer_credits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583838492,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1808",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved"
      ],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata"
      ]
    },
    {
      "addr": 18446744071584302535,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1808",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584347746,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1808",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583835296,
      "name": "jbd2_handle_buffer_credits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_handle_buffer_credits",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584462125,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1806",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584951015,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1806",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584997506,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1806",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_handle_buffer_credits",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584691016,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1807",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585179130,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1807",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585225474,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1807",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_handle_buffer_credits",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584923704,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1820",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585412027,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1820",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585458482,
      "name": "jbd2_handle_buffer_credits",
      "external": false,
      "loc": "include/linux/jbd2.h:1820",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata"
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
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int jbd2_handle_buffer_credits(handle_t * handle)
```
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int jbd2_handle_buffer_credits(handle_t * handle)
```
</details>
</li>
</ul>
