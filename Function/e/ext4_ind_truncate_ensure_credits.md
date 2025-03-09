# Function: <code>ext4_ind_truncate_ensure_credits</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int ext4_ind_truncate_ensure_credits(handle_t * handle, struct inode * inode, struct buffer_head * bh, int revoke_creds)
```

```json
{
  "name": "ext4_ind_truncate_ensure_credits",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582972032,
      "name": "ext4_ind_truncate_ensure_credits",
      "external": false,
      "loc": "fs/ext4/indirect.c:713",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582972032,
      "name": "ext4_ind_truncate_ensure_credits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
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
int ext4_ind_truncate_ensure_credits(handle_t * handle, struct inode * inode, struct buffer_head * bh, int revoke_creds)
```

```json
{
  "name": "ext4_ind_truncate_ensure_credits",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583047632,
      "name": "ext4_ind_truncate_ensure_credits",
      "external": false,
      "loc": "fs/ext4/indirect.c:714",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583047632,
      "name": "ext4_ind_truncate_ensure_credits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
int ext4_ind_truncate_ensure_credits(handle_t * handle, struct inode * inode, struct buffer_head * bh, int revoke_creds)
```

```json
{
  "name": "ext4_ind_truncate_ensure_credits",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583073232,
      "name": "ext4_ind_truncate_ensure_credits",
      "external": false,
      "loc": "fs/ext4/indirect.c:714",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583073232,
      "name": "ext4_ind_truncate_ensure_credits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
int ext4_ind_truncate_ensure_credits(handle_t * handle, struct inode * inode, struct buffer_head * bh, int revoke_creds)
```

```json
{
  "name": "ext4_ind_truncate_ensure_credits",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ind_truncate_ensure_credits",
      "external": false,
      "loc": "fs/ext4/indirect.c:716",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583411712,
      "name": "ext4_ind_truncate_ensure_credits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
    },
    {
      "addr": 18446744071592256852,
      "name": "ext4_ind_truncate_ensure_credits.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int ext4_ind_truncate_ensure_credits(handle_t * handle, struct inode * inode, struct buffer_head * bh, int revoke_creds)
```

```json
{
  "name": "ext4_ind_truncate_ensure_credits",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ind_truncate_ensure_credits",
      "external": false,
      "loc": "fs/ext4/indirect.c:716",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583927168,
      "name": "ext4_ind_truncate_ensure_credits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
    },
    {
      "addr": 18446744071594037878,
      "name": "ext4_ind_truncate_ensure_credits.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int ext4_ind_truncate_ensure_credits(handle_t * handle, struct inode * inode, struct buffer_head * bh, int revoke_creds)
```

```json
{
  "name": "ext4_ind_truncate_ensure_credits",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ind_truncate_ensure_credits",
      "external": false,
      "loc": "fs/ext4/indirect.c:723",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584553360,
      "name": "ext4_ind_truncate_ensure_credits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
    },
    {
      "addr": 18446744071596070963,
      "name": "ext4_ind_truncate_ensure_credits.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int ext4_ind_truncate_ensure_credits(handle_t * handle, struct inode * inode, struct buffer_head * bh, int revoke_creds)
```

```json
{
  "name": "ext4_ind_truncate_ensure_credits",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ind_truncate_ensure_credits",
      "external": false,
      "loc": "fs/ext4/indirect.c:731",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584782112,
      "name": "ext4_ind_truncate_ensure_credits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
    },
    {
      "addr": 18446744071596594384,
      "name": "ext4_ind_truncate_ensure_credits.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int ext4_ind_truncate_ensure_credits(handle_t * handle, struct inode * inode, struct buffer_head * bh, int revoke_creds)
```

```json
{
  "name": "ext4_ind_truncate_ensure_credits",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ind_truncate_ensure_credits",
      "external": false,
      "loc": "fs/ext4/indirect.c:731",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585014992,
      "name": "ext4_ind_truncate_ensure_credits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
    },
    {
      "addr": 18446744071597499899,
      "name": "ext4_ind_truncate_ensure_credits.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int ext4_ind_truncate_ensure_credits(handle_t * handle, struct inode * inode, struct buffer_head * bh, int revoke_creds)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
