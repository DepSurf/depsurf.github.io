# Function: <code>vfs_remove_acl</code>

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
int vfs_remove_acl(struct user_namespace * mnt_userns, struct dentry * dentry, const char * acl_name)
```

```json
{
  "name": "vfs_remove_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584177872,
      "name": "vfs_remove_acl",
      "external": true,
      "loc": "fs/posix_acl.c:1177",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584177872,
      "name": "vfs_remove_acl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
int vfs_remove_acl(struct mnt_idmap * idmap, struct dentry * dentry, const char * acl_name)
```

```json
{
  "name": "vfs_remove_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584405568,
      "name": "vfs_remove_acl",
      "external": true,
      "loc": "fs/posix_acl.c:1211",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584405568,
      "name": "vfs_remove_acl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 630
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
int vfs_remove_acl(struct mnt_idmap * idmap, struct dentry * dentry, const char * acl_name)
```

```json
{
  "name": "vfs_remove_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584626288,
      "name": "vfs_remove_acl",
      "external": true,
      "loc": "fs/posix_acl.c:1211",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:removexattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584626288,
      "name": "vfs_remove_acl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 630
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
int vfs_remove_acl(struct user_namespace * mnt_userns, struct dentry * dentry, const char * acl_name)
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
