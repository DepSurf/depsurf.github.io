# Function: <code>inode_update_time</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int inode_update_time(struct inode * inode, struct timespec64 * time, int flags)
```

```json
{
  "name": "inode_update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582601609,
      "name": "inode_update_time",
      "external": true,
      "loc": "fs/inode.c:1785",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582599856,
      "name": "inode_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int inode_update_time(struct inode * inode, struct timespec64 * time, int flags)
```

```json
{
  "name": "inode_update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583137758,
      "name": "inode_update_time",
      "external": true,
      "loc": "fs/inode.c:1866",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583133040,
      "name": "inode_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int inode_update_time(struct inode * inode, struct timespec64 * time, int flags)
```

```json
{
  "name": "inode_update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583709280,
      "name": "inode_update_time",
      "external": true,
      "loc": "fs/inode.c:1868",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_modified_flags",
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583702480,
      "name": "inode_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int inode_update_time(struct inode * inode, struct timespec64 * time, int flags)
```

```json
{
  "name": "inode_update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583926748,
      "name": "inode_update_time",
      "external": true,
      "loc": "fs/inode.c:1912",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_modified_flags",
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583919888,
      "name": "inode_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int inode_update_time(struct inode * inode, int flags)
```

```json
{
  "name": "inode_update_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584133449,
      "name": "inode_update_time",
      "external": true,
      "loc": "fs/inode.c:1914",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:kiocb_modified",
        "fs/inode.c:file_modified",
        "fs/inode.c:file_update_time",
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584128992,
      "name": "inode_update_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int inode_update_time(struct inode * inode, struct timespec64 * time, int flags)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct timespec64 * time</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, time, flags</code> ➡️ <code>inode, flags</code>
</li>
</ul>
</details>
</li>
</ul>
