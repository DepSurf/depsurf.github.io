# Function: <code>lookup_positive_unlocked</code>

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
struct dentry * lookup_positive_unlocked(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_positive_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582138544,
      "name": "lookup_positive_unlocked",
      "external": true,
      "loc": "fs/namei.c:2604",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_on_mount",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/debugfs/inode.c:debugfs_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582138544,
      "name": "lookup_positive_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct dentry * lookup_positive_unlocked(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_positive_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582185136,
      "name": "lookup_positive_unlocked",
      "external": true,
      "loc": "fs/namei.c:2602",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_on_mount",
        "fs/kernfs/mount.c:kernfs_node_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582185136,
      "name": "lookup_positive_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct dentry * lookup_positive_unlocked(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_positive_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582207344,
      "name": "lookup_positive_unlocked",
      "external": true,
      "loc": "fs/namei.c:2692",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_on_mount",
        "fs/kernfs/mount.c:kernfs_node_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582207344,
      "name": "lookup_positive_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct dentry * lookup_positive_unlocked(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_positive_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582525312,
      "name": "lookup_positive_unlocked",
      "external": true,
      "loc": "fs/namei.c:2758",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_on_mount",
        "fs/kernfs/mount.c:kernfs_node_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582525312,
      "name": "lookup_positive_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct dentry * lookup_positive_unlocked(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_positive_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583046992,
      "name": "lookup_positive_unlocked",
      "external": true,
      "loc": "fs/namei.c:2859",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_on_mount",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/debugfs/inode.c:debugfs_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583046992,
      "name": "lookup_positive_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct dentry * lookup_positive_unlocked(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_positive_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583612608,
      "name": "lookup_positive_unlocked",
      "external": true,
      "loc": "fs/namei.c:2838",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_on_mount",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/debugfs/inode.c:debugfs_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583612608,
      "name": "lookup_positive_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
struct dentry * lookup_positive_unlocked(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_positive_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583828416,
      "name": "lookup_positive_unlocked",
      "external": true,
      "loc": "fs/namei.c:2869",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_on_mount",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/debugfs/inode.c:debugfs_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583828416,
      "name": "lookup_positive_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct dentry * lookup_positive_unlocked(const char * name, struct dentry * base, int len)
```

```json
{
  "name": "lookup_positive_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584034464,
      "name": "lookup_positive_unlocked",
      "external": true,
      "loc": "fs/namei.c:2886",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_on_mount",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/debugfs/inode.c:debugfs_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584034464,
      "name": "lookup_positive_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct dentry * lookup_positive_unlocked(const char * name, struct dentry * base, int len)
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
