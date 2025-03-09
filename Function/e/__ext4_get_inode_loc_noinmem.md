# Function: <code>__ext4_get_inode_loc_noinmem</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ext4_get_inode_loc_noinmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583096002,
      "name": "__ext4_get_inode_loc_noinmem",
      "external": false,
      "loc": "fs/ext4/inode.c:4435",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ext4_get_inode_loc_noinmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583121030,
      "name": "__ext4_get_inode_loc_noinmem",
      "external": false,
      "loc": "fs/ext4/inode.c:4434",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __ext4_get_inode_loc_noinmem(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "__ext4_get_inode_loc_noinmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583445216,
      "name": "__ext4_get_inode_loc_noinmem",
      "external": false,
      "loc": "fs/ext4/inode.c:4355",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583445216,
      "name": "__ext4_get_inode_loc_noinmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int __ext4_get_inode_loc_noinmem(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "__ext4_get_inode_loc_noinmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583968304,
      "name": "__ext4_get_inode_loc_noinmem",
      "external": false,
      "loc": "fs/ext4/inode.c:4577",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583968304,
      "name": "__ext4_get_inode_loc_noinmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int __ext4_get_inode_loc_noinmem(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "__ext4_get_inode_loc_noinmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584596144,
      "name": "__ext4_get_inode_loc_noinmem",
      "external": false,
      "loc": "fs/ext4/inode.c:4672",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584596144,
      "name": "__ext4_get_inode_loc_noinmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int __ext4_get_inode_loc_noinmem(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "__ext4_get_inode_loc_noinmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584822464,
      "name": "__ext4_get_inode_loc_noinmem",
      "external": false,
      "loc": "fs/ext4/inode.c:4457",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584822464,
      "name": "__ext4_get_inode_loc_noinmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int __ext4_get_inode_loc_noinmem(struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "__ext4_get_inode_loc_noinmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585055440,
      "name": "__ext4_get_inode_loc_noinmem",
      "external": false,
      "loc": "fs/ext4/inode.c:4476",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/inode.c:__ext4_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585055440,
      "name": "__ext4_get_inode_loc_noinmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int __ext4_get_inode_loc_noinmem(struct inode * inode, struct ext4_iloc * iloc)
```
</details>
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
