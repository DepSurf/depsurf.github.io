# Function: <code>setattr_should_drop_suidgid</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int setattr_should_drop_suidgid(struct user_namespace * mnt_userns, struct inode * inode)
```

```json
{
  "name": "setattr_should_drop_suidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583716256,
      "name": "setattr_should_drop_suidgid",
      "external": true,
      "loc": "fs/attr.c:66",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:__file_remove_privs",
        "fs/fuse/file.c:fuse_cache_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583716256,
      "name": "setattr_should_drop_suidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
int setattr_should_drop_suidgid(struct mnt_idmap * idmap, struct inode * inode)
```

```json
{
  "name": "setattr_should_drop_suidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583936352,
      "name": "setattr_should_drop_suidgid",
      "external": true,
      "loc": "fs/attr.c:67",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:__file_remove_privs",
        "fs/fuse/file.c:fuse_cache_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583936352,
      "name": "setattr_should_drop_suidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int setattr_should_drop_suidgid(struct mnt_idmap * idmap, struct inode * inode)
```

```json
{
  "name": "setattr_should_drop_suidgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584142624,
      "name": "setattr_should_drop_suidgid",
      "external": true,
      "loc": "fs/attr.c:67",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:__file_remove_privs",
        "fs/fuse/file.c:fuse_cache_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584142624,
      "name": "setattr_should_drop_suidgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int setattr_should_drop_suidgid(struct user_namespace * mnt_userns, struct inode * inode)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap * idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
