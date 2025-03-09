# Function: <code>__ext4_unlink</code>

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
int __ext4_unlink(handle_t * handle, struct inode * dir, const struct qstr * d_name, struct inode * inode)
```

```json
{
  "name": "__ext4_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583213216,
      "name": "__ext4_unlink",
      "external": true,
      "loc": "fs/ext4/namei.c:3189",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_unlink",
        "fs/ext4/fast_commit.c:ext4_fc_replay_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583213216,
      "name": "__ext4_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
int __ext4_unlink(handle_t * handle, struct inode * dir, const struct qstr * d_name, struct inode * inode)
```

```json
{
  "name": "__ext4_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583241152,
      "name": "__ext4_unlink",
      "external": true,
      "loc": "fs/ext4/namei.c:3319",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_unlink",
        "fs/ext4/fast_commit.c:ext4_fc_replay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583241152,
      "name": "__ext4_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
int __ext4_unlink(handle_t * handle, struct inode * dir, const struct qstr * d_name, struct inode * inode)
```

```json
{
  "name": "__ext4_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583583184,
      "name": "__ext4_unlink",
      "external": true,
      "loc": "fs/ext4/namei.c:3147",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_unlink",
        "fs/ext4/fast_commit.c:ext4_fc_replay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583583184,
      "name": "__ext4_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
int __ext4_unlink(handle_t * handle, struct inode * dir, const struct qstr * d_name, struct inode * inode)
```

```json
{
  "name": "__ext4_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584120400,
      "name": "__ext4_unlink",
      "external": true,
      "loc": "fs/ext4/namei.c:3194",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_unlink",
        "fs/ext4/fast_commit.c:ext4_fc_replay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584120400,
      "name": "__ext4_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
int __ext4_unlink(struct inode * dir, const struct qstr * d_name, struct inode * inode, struct dentry * dentry)
```

```json
{
  "name": "__ext4_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584753904,
      "name": "__ext4_unlink",
      "external": true,
      "loc": "fs/ext4/namei.c:3207",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_unlink",
        "fs/ext4/fast_commit.c:ext4_fc_replay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584753904,
      "name": "__ext4_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 865
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
int __ext4_unlink(struct inode * dir, const struct qstr * d_name, struct inode * inode, struct dentry * dentry)
```

```json
{
  "name": "__ext4_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584977616,
      "name": "__ext4_unlink",
      "external": true,
      "loc": "fs/ext4/namei.c:3228",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_unlink",
        "fs/ext4/fast_commit.c:ext4_fc_replay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584977616,
      "name": "__ext4_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 865
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
int __ext4_unlink(struct inode * dir, const struct qstr * d_name, struct inode * inode, struct dentry * dentry)
```

```json
{
  "name": "__ext4_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585208736,
      "name": "__ext4_unlink",
      "external": true,
      "loc": "fs/ext4/namei.c:3230",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_unlink",
        "fs/ext4/fast_commit.c:ext4_fc_replay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585208736,
      "name": "__ext4_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 843
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
int __ext4_unlink(handle_t * handle, struct inode * dir, const struct qstr * d_name, struct inode * inode)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dentry * dentry</code>
</li>
<li>
<b>Param removed. </b>
<code>handle_t * handle</code>
</li>
<li>
<b>Param reordered. </b>
<code>handle, dir, d_name, inode</code> ➡️ <code>dir, d_name, inode, dentry</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
