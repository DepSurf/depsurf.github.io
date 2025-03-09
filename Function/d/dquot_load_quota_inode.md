# Function: <code>dquot_load_quota_inode</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dquot_load_quota_inode(struct inode * inode, int type, int format_id, unsigned int flags)
```

```json
{
  "name": "dquot_load_quota_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582724912,
      "name": "dquot_load_quota_inode",
      "external": true,
      "loc": "fs/quota/dquot.c:2414",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_on_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582724912,
      "name": "dquot_load_quota_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
int dquot_load_quota_inode(struct inode * inode, int type, int format_id, unsigned int flags)
```

```json
{
  "name": "dquot_load_quota_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582796064,
      "name": "dquot_load_quota_inode",
      "external": true,
      "loc": "fs/quota/dquot.c:2415",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_on_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582796064,
      "name": "dquot_load_quota_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dquot_load_quota_inode(struct inode * inode, int type, int format_id, unsigned int flags)
```

```json
{
  "name": "dquot_load_quota_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582824144,
      "name": "dquot_load_quota_inode",
      "external": true,
      "loc": "fs/quota/dquot.c:2413",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_on_mount",
        "fs/ext4/super.c:ext4_enable_quotas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582824144,
      "name": "dquot_load_quota_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int dquot_load_quota_inode(struct inode * inode, int type, int format_id, unsigned int flags)
```

```json
{
  "name": "dquot_load_quota_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583156254,
      "name": "dquot_load_quota_inode",
      "external": true,
      "loc": "fs/quota/dquot.c:2418",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_on_mount",
        "fs/ext4/super.c:ext4_enable_quotas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592246911,
      "name": "dquot_load_quota_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071583156096,
      "name": "dquot_load_quota_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int dquot_load_quota_inode(struct inode * inode, int type, int format_id, unsigned int flags)
```

```json
{
  "name": "dquot_load_quota_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583637798,
      "name": "dquot_load_quota_inode",
      "external": true,
      "loc": "fs/quota/dquot.c:2428",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_on_mount",
        "fs/ext4/super.c:ext4_enable_quotas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594027583,
      "name": "dquot_load_quota_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071583637648,
      "name": "dquot_load_quota_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int dquot_load_quota_inode(struct inode * inode, int type, int format_id, unsigned int flags)
```

```json
{
  "name": "dquot_load_quota_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584243127,
      "name": "dquot_load_quota_inode",
      "external": true,
      "loc": "fs/quota/dquot.c:2437",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_on_mount",
        "fs/ext4/super.c:ext4_enable_quotas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596063059,
      "name": "dquot_load_quota_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071584242960,
      "name": "dquot_load_quota_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int dquot_load_quota_inode(struct inode * inode, int type, int format_id, unsigned int flags)
```

```json
{
  "name": "dquot_load_quota_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584473735,
      "name": "dquot_load_quota_inode",
      "external": true,
      "loc": "fs/quota/dquot.c:2496",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_on_mount",
        "fs/ext4/super.c:ext4_enable_quotas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596587015,
      "name": "dquot_load_quota_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071584473568,
      "name": "dquot_load_quota_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int dquot_load_quota_inode(struct inode * inode, int type, int format_id, unsigned int flags)
```

```json
{
  "name": "dquot_load_quota_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584696657,
      "name": "dquot_load_quota_inode",
      "external": true,
      "loc": "fs/quota/dquot.c:2463",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_on_mount",
        "fs/ext4/super.c:ext4_enable_quotas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597492785,
      "name": "dquot_load_quota_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071584696480,
      "name": "dquot_load_quota_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
int dquot_load_quota_inode(struct inode * inode, int type, int format_id, unsigned int flags)
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
