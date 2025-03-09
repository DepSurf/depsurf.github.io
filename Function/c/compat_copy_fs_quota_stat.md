# Function: <code>compat_copy_fs_quota_stat</code>

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
int compat_copy_fs_quota_stat(struct compat_fs_quota_stat * to, struct fs_quota_stat * from)
```

```json
{
  "name": "compat_copy_fs_quota_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582797776,
      "name": "compat_copy_fs_quota_stat",
      "external": false,
      "loc": "fs/quota/quota.c:414",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:do_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582797776,
      "name": "compat_copy_fs_quota_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
  "name": "compat_copy_fs_quota_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582828187,
      "name": "compat_copy_fs_quota_stat",
      "external": false,
      "loc": "fs/quota/quota.c:415",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:quota_getxstate"
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
  "name": "compat_copy_fs_quota_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583160667,
      "name": "compat_copy_fs_quota_stat",
      "external": false,
      "loc": "fs/quota/quota.c:415",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:quota_getxstate"
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
  "name": "compat_copy_fs_quota_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583650911,
      "name": "compat_copy_fs_quota_stat",
      "external": false,
      "loc": "fs/quota/quota.c:416",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:quota_getxstate"
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
  "name": "compat_copy_fs_quota_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584256863,
      "name": "compat_copy_fs_quota_stat",
      "external": false,
      "loc": "fs/quota/quota.c:416",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:quota_getxstate"
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
  "name": "compat_copy_fs_quota_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584487455,
      "name": "compat_copy_fs_quota_stat",
      "external": false,
      "loc": "fs/quota/quota.c:416",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:quota_getxstate"
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
  "name": "compat_copy_fs_quota_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584710415,
      "name": "compat_copy_fs_quota_stat",
      "external": false,
      "loc": "fs/quota/quota.c:416",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:quota_getxstate"
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
int compat_copy_fs_quota_stat(struct compat_fs_quota_stat * to, struct fs_quota_stat * from)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int compat_copy_fs_quota_stat(struct compat_fs_quota_stat * to, struct fs_quota_stat * from)
```
</details>
</li>
</ul>
