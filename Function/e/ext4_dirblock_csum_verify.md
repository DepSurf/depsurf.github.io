# Function: <code>ext4_dirblock_csum_verify</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_dirblock_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_dirblock_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582689904,
      "name": "ext4_dirblock_csum_verify",
      "external": true,
      "loc": "fs/ext4/namei.c:361",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582689904,
      "name": "ext4_dirblock_csum_verify",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_dirblock_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_dirblock_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582792096,
      "name": "ext4_dirblock_csum_verify",
      "external": true,
      "loc": "fs/ext4/namei.c:361",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582792096,
      "name": "ext4_dirblock_csum_verify",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_dirblock_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_dirblock_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583105552,
      "name": "ext4_dirblock_csum_verify",
      "external": true,
      "loc": "fs/ext4/namei.c:368",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583105552,
      "name": "ext4_dirblock_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int ext4_dirblock_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_dirblock_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583184608,
      "name": "ext4_dirblock_csum_verify",
      "external": true,
      "loc": "fs/ext4/namei.c:364",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583184608,
      "name": "ext4_dirblock_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int ext4_dirblock_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_dirblock_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583211008,
      "name": "ext4_dirblock_csum_verify",
      "external": true,
      "loc": "fs/ext4/namei.c:366",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583211008,
      "name": "ext4_dirblock_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int ext4_dirblock_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_dirblock_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583555024,
      "name": "ext4_dirblock_csum_verify",
      "external": true,
      "loc": "fs/ext4/namei.c:367",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583555024,
      "name": "ext4_dirblock_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int ext4_dirblock_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_dirblock_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584090528,
      "name": "ext4_dirblock_csum_verify",
      "external": true,
      "loc": "fs/ext4/namei.c:390",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584090528,
      "name": "ext4_dirblock_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int ext4_dirblock_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_dirblock_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584724160,
      "name": "ext4_dirblock_csum_verify",
      "external": true,
      "loc": "fs/ext4/namei.c:395",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584724160,
      "name": "ext4_dirblock_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int ext4_dirblock_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_dirblock_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584947520,
      "name": "ext4_dirblock_csum_verify",
      "external": true,
      "loc": "fs/ext4/namei.c:395",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584947520,
      "name": "ext4_dirblock_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int ext4_dirblock_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_dirblock_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585178832,
      "name": "ext4_dirblock_csum_verify",
      "external": true,
      "loc": "fs/ext4/namei.c:396",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585178832,
      "name": "ext4_dirblock_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
int ext4_dirblock_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_dirblock_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494461840,
      "name": "ext4_dirblock_csum_verify",
      "external": true,
      "loc": "fs/ext4/namei.c:361",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494461840,
      "name": "ext4_dirblock_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int ext4_dirblock_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_dirblock_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227897456,
      "name": "ext4_dirblock_csum_verify",
      "external": true,
      "loc": "fs/ext4/namei.c:361",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227897456,
      "name": "ext4_dirblock_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int ext4_dirblock_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_dirblock_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288217296,
      "name": "ext4_dirblock_csum_verify",
      "external": true,
      "loc": "fs/ext4/namei.c:361",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288217296,
      "name": "ext4_dirblock_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int ext4_dirblock_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_dirblock_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273869060,
      "name": "ext4_dirblock_csum_verify",
      "external": true,
      "loc": "fs/ext4/namei.c:361",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273869060,
      "name": "ext4_dirblock_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int ext4_dirblock_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_dirblock_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582760832,
      "name": "ext4_dirblock_csum_verify",
      "external": true,
      "loc": "fs/ext4/namei.c:361",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582760832,
      "name": "ext4_dirblock_csum_verify",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_dirblock_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_dirblock_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582698000,
      "name": "ext4_dirblock_csum_verify",
      "external": true,
      "loc": "fs/ext4/namei.c:361",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582698000,
      "name": "ext4_dirblock_csum_verify",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_dirblock_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_dirblock_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582751072,
      "name": "ext4_dirblock_csum_verify",
      "external": true,
      "loc": "fs/ext4/namei.c:361",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582751072,
      "name": "ext4_dirblock_csum_verify",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_dirblock_csum_verify(struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "ext4_dirblock_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582835968,
      "name": "ext4_dirblock_csum_verify",
      "external": true,
      "loc": "fs/ext4/namei.c:361",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582835968,
      "name": "ext4_dirblock_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int ext4_dirblock_csum_verify(struct inode * inode, struct buffer_head * bh)
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
