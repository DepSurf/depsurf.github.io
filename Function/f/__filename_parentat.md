# Function: <code>__filename_parentat</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int __filename_parentat(int dfd, struct filename * name, unsigned int flags, struct path * parent, struct qstr * last, int * type, const struct path * root)
```

```json
{
  "name": "__filename_parentat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583848352,
      "name": "__filename_parentat",
      "external": false,
      "loc": "fs/namei.c:2539",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:vfs_path_parent_lookup",
        "fs/namei.c:kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583848352,
      "name": "__filename_parentat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
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
int __filename_parentat(int dfd, struct filename * name, unsigned int flags, struct path * parent, struct qstr * last, int * type, const struct path * root)
```

```json
{
  "name": "__filename_parentat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584055168,
      "name": "__filename_parentat",
      "external": false,
      "loc": "fs/namei.c:2546",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:vfs_path_parent_lookup",
        "fs/namei.c:__kern_path_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584055168,
      "name": "__filename_parentat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int __filename_parentat(int dfd, struct filename * name, unsigned int flags, struct path * parent, struct qstr * last, int * type, const struct path * root)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
