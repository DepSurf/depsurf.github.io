# Function: <code>ext4_xattr_credits_for_new_inode</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int ext4_xattr_credits_for_new_inode(struct inode * dir, mode_t mode, bool encrypt)
```

```json
{
  "name": "ext4_xattr_credits_for_new_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583032272,
      "name": "ext4_xattr_credits_for_new_inode",
      "external": false,
      "loc": "fs/ext4/ialloc.c:865",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583032272,
      "name": "ext4_xattr_credits_for_new_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_xattr_credits_for_new_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583065475,
      "name": "ext4_xattr_credits_for_new_inode",
      "external": false,
      "loc": "fs/ext4/ialloc.c:866",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_xattr_credits_for_new_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583403508,
      "name": "ext4_xattr_credits_for_new_inode",
      "external": false,
      "loc": "fs/ext4/ialloc.c:868",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_xattr_credits_for_new_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583918595,
      "name": "ext4_xattr_credits_for_new_inode",
      "external": false,
      "loc": "fs/ext4/ialloc.c:868",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_xattr_credits_for_new_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584544694,
      "name": "ext4_xattr_credits_for_new_inode",
      "external": false,
      "loc": "fs/ext4/ialloc.c:867",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
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
  "name": "ext4_xattr_credits_for_new_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584773633,
      "name": "ext4_xattr_credits_for_new_inode",
      "external": false,
      "loc": "fs/ext4/ialloc.c:866",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
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
  "name": "ext4_xattr_credits_for_new_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585006644,
      "name": "ext4_xattr_credits_for_new_inode",
      "external": false,
      "loc": "fs/ext4/ialloc.c:866",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int ext4_xattr_credits_for_new_inode(struct inode * dir, mode_t mode, bool encrypt)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int ext4_xattr_credits_for_new_inode(struct inode * dir, mode_t mode, bool encrypt)
```
</details>
</li>
</ul>
