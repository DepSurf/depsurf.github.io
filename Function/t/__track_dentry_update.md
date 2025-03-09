# Function: <code>__track_dentry_update</code>

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
int __track_dentry_update(struct inode * inode, void * arg, bool update)
```

```json
{
  "name": "__track_dentry_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583394080,
      "name": "__track_dentry_update",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:428",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:__ext4_fc_track_create",
        "fs/ext4/fast_commit.c:__ext4_fc_track_link",
        "fs/ext4/fast_commit.c:__ext4_fc_track_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583394080,
      "name": "__track_dentry_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
int __track_dentry_update(struct inode * inode, void * arg, bool update)
```

```json
{
  "name": "__track_dentry_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583417040,
      "name": "__track_dentry_update",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:428",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:__ext4_fc_track_create",
        "fs/ext4/fast_commit.c:__ext4_fc_track_link",
        "fs/ext4/fast_commit.c:__ext4_fc_track_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583417040,
      "name": "__track_dentry_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
int __track_dentry_update(struct inode * inode, void * arg, bool update)
```

```json
{
  "name": "__track_dentry_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583759312,
      "name": "__track_dentry_update",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:395",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:__ext4_fc_track_create",
        "fs/ext4/fast_commit.c:__ext4_fc_track_link",
        "fs/ext4/fast_commit.c:__ext4_fc_track_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583759312,
      "name": "__track_dentry_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 515
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
int __track_dentry_update(struct inode * inode, void * arg, bool update)
```

```json
{
  "name": "__track_dentry_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584317824,
      "name": "__track_dentry_update",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:414",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:__ext4_fc_track_create",
        "fs/ext4/fast_commit.c:__ext4_fc_track_link",
        "fs/ext4/fast_commit.c:__ext4_fc_track_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584317824,
      "name": "__track_dentry_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
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
int __track_dentry_update(struct inode * inode, void * arg, bool update)
```

```json
{
  "name": "__track_dentry_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584965552,
      "name": "__track_dentry_update",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:416",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:__ext4_fc_track_create",
        "fs/ext4/fast_commit.c:__ext4_fc_track_link",
        "fs/ext4/fast_commit.c:__ext4_fc_track_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584965552,
      "name": "__track_dentry_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
int __track_dentry_update(struct inode * inode, void * arg, bool update)
```

```json
{
  "name": "__track_dentry_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585193824,
      "name": "__track_dentry_update",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:416",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:__ext4_fc_track_create",
        "fs/ext4/fast_commit.c:__ext4_fc_track_link",
        "fs/ext4/fast_commit.c:__ext4_fc_track_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585193824,
      "name": "__track_dentry_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
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
int __track_dentry_update(struct inode * inode, void * arg, bool update)
```

```json
{
  "name": "__track_dentry_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585426720,
      "name": "__track_dentry_update",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:416",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:__ext4_fc_track_create",
        "fs/ext4/fast_commit.c:__ext4_fc_track_link",
        "fs/ext4/fast_commit.c:__ext4_fc_track_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585426720,
      "name": "__track_dentry_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int __track_dentry_update(struct inode * inode, void * arg, bool update)
```
</details>
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
