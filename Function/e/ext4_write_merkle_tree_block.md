# Function: <code>ext4_write_merkle_tree_block</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int ext4_write_merkle_tree_block(struct inode * inode, const void * buf, u64 index, int log_blocksize)
```

```json
{
  "name": "ext4_write_merkle_tree_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582969488,
      "name": "ext4_write_merkle_tree_block",
      "external": false,
      "loc": "fs/ext4/verity.c:353",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582969488,
      "name": "ext4_write_merkle_tree_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
int ext4_write_merkle_tree_block(struct inode * inode, const void * buf, u64 index, int log_blocksize)
```

```json
{
  "name": "ext4_write_merkle_tree_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583285344,
      "name": "ext4_write_merkle_tree_block",
      "external": false,
      "loc": "fs/ext4/verity.c:368",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583285344,
      "name": "ext4_write_merkle_tree_block",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int ext4_write_merkle_tree_block(struct inode * inode, const void * buf, u64 index, int log_blocksize)
```

```json
{
  "name": "ext4_write_merkle_tree_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583400896,
      "name": "ext4_write_merkle_tree_block",
      "external": false,
      "loc": "fs/ext4/verity.c:389",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583400896,
      "name": "ext4_write_merkle_tree_block",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int ext4_write_merkle_tree_block(struct inode * inode, const void * buf, u64 index, int log_blocksize)
```

```json
{
  "name": "ext4_write_merkle_tree_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583423840,
      "name": "ext4_write_merkle_tree_block",
      "external": false,
      "loc": "fs/ext4/verity.c:383",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583423840,
      "name": "ext4_write_merkle_tree_block",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_write_merkle_tree_block(struct inode * inode, const void * buf, u64 index, int log_blocksize)
```

```json
{
  "name": "ext4_write_merkle_tree_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_write_merkle_tree_block",
      "external": false,
      "loc": "fs/ext4/verity.c:383",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583773216,
      "name": "ext4_write_merkle_tree_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071592272690,
      "name": "ext4_write_merkle_tree_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int ext4_write_merkle_tree_block(struct inode * inode, const void * buf, u64 index, int log_blocksize)
```

```json
{
  "name": "ext4_write_merkle_tree_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_write_merkle_tree_block",
      "external": false,
      "loc": "fs/ext4/verity.c:384",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333328,
      "name": "ext4_write_merkle_tree_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071594054543,
      "name": "ext4_write_merkle_tree_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
int ext4_write_merkle_tree_block(struct inode * inode, const void * buf, u64 index, int log_blocksize)
```

```json
{
  "name": "ext4_write_merkle_tree_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_write_merkle_tree_block",
      "external": false,
      "loc": "fs/ext4/verity.c:383",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584982192,
      "name": "ext4_write_merkle_tree_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071596085811,
      "name": "ext4_write_merkle_tree_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
int ext4_write_merkle_tree_block(struct inode * inode, const void * buf, u64 pos, unsigned int size)
```

```json
{
  "name": "ext4_write_merkle_tree_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585210848,
      "name": "ext4_write_merkle_tree_block",
      "external": false,
      "loc": "fs/ext4/verity.c:383",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585210848,
      "name": "ext4_write_merkle_tree_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int ext4_write_merkle_tree_block(struct inode * inode, const void * buf, u64 pos, unsigned int size)
```

```json
{
  "name": "ext4_write_merkle_tree_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585443712,
      "name": "ext4_write_merkle_tree_block",
      "external": false,
      "loc": "fs/ext4/verity.c:383",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585443712,
      "name": "ext4_write_merkle_tree_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int ext4_write_merkle_tree_block(struct inode * inode, const void * buf, u64 index, int log_blocksize)
```

```json
{
  "name": "ext4_write_merkle_tree_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494645744,
      "name": "ext4_write_merkle_tree_block",
      "external": false,
      "loc": "fs/ext4/verity.c:353",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494645744,
      "name": "ext4_write_merkle_tree_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
int ext4_write_merkle_tree_block(struct inode * inode, const void * buf, u64 index, int log_blocksize)
```

```json
{
  "name": "ext4_write_merkle_tree_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228090400,
      "name": "ext4_write_merkle_tree_block",
      "external": false,
      "loc": "fs/ext4/verity.c:353",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228090400,
      "name": "ext4_write_merkle_tree_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int ext4_write_merkle_tree_block(struct inode * inode, const void * buf, u64 index, int log_blocksize)
```

```json
{
  "name": "ext4_write_merkle_tree_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288458704,
      "name": "ext4_write_merkle_tree_block",
      "external": false,
      "loc": "fs/ext4/verity.c:353",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288458704,
      "name": "ext4_write_merkle_tree_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int ext4_write_merkle_tree_block(struct inode * inode, const void * buf, u64 index, int log_blocksize)
```

```json
{
  "name": "ext4_write_merkle_tree_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274014340,
      "name": "ext4_write_merkle_tree_block",
      "external": false,
      "loc": "fs/ext4/verity.c:353",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274014340,
      "name": "ext4_write_merkle_tree_block",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int ext4_write_merkle_tree_block(struct inode * inode, const void * buf, u64 index, int log_blocksize)
```

```json
{
  "name": "ext4_write_merkle_tree_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582938224,
      "name": "ext4_write_merkle_tree_block",
      "external": false,
      "loc": "fs/ext4/verity.c:353",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582938224,
      "name": "ext4_write_merkle_tree_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
int ext4_write_merkle_tree_block(struct inode * inode, const void * buf, u64 index, int log_blocksize)
```

```json
{
  "name": "ext4_write_merkle_tree_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582875376,
      "name": "ext4_write_merkle_tree_block",
      "external": false,
      "loc": "fs/ext4/verity.c:353",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582875376,
      "name": "ext4_write_merkle_tree_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
int ext4_write_merkle_tree_block(struct inode * inode, const void * buf, u64 index, int log_blocksize)
```

```json
{
  "name": "ext4_write_merkle_tree_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582926832,
      "name": "ext4_write_merkle_tree_block",
      "external": false,
      "loc": "fs/ext4/verity.c:353",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582926832,
      "name": "ext4_write_merkle_tree_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
int ext4_write_merkle_tree_block(struct inode * inode, const void * buf, u64 index, int log_blocksize)
```

```json
{
  "name": "ext4_write_merkle_tree_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583013920,
      "name": "ext4_write_merkle_tree_block",
      "external": false,
      "loc": "fs/ext4/verity.c:353",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583013920,
      "name": "ext4_write_merkle_tree_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
int ext4_write_merkle_tree_block(struct inode * inode, const void * buf, u64 index, int log_blocksize)
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 pos</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int size</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 index</code>
</li>
<li>
<b>Param removed. </b>
<code>int log_blocksize</code>
</li>
</ul>
</details>
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
