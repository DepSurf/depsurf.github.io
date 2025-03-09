# Function: <code>aafs_create</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dentry * aafs_create(const char * name, umode_t mode, struct dentry * parent, void * data, void * link, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "aafs_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582878496,
      "name": "aafs_create",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:229",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582878496,
      "name": "aafs_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aafs_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583036240,
      "name": "aafs_create",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:229",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583036240,
      "name": "aafs_create.constprop.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aafs_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583236832,
      "name": "aafs_create",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:226",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583236832,
      "name": "aafs_create.constprop.39",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aafs_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583354416,
      "name": "aafs_create",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:226",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583354416,
      "name": "aafs_create.constprop.39",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aafs_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583542208,
      "name": "aafs_create",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:231",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583542208,
      "name": "aafs_create.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aafs_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583648080,
      "name": "aafs_create",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:231",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583648080,
      "name": "aafs_create.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aafs_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584005568,
      "name": "aafs_create",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:261",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584005568,
      "name": "aafs_create.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aafs_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584125344,
      "name": "aafs_create",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:261",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584125344,
      "name": "aafs_create.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
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
  "name": "aafs_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584152528,
      "name": "aafs_create",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:261",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584152528,
      "name": "aafs_create.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aafs_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584536672,
      "name": "aafs_create",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:261",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536672,
      "name": "aafs_create.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aafs_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585177344,
      "name": "aafs_create",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:264",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585177344,
      "name": "aafs_create.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aafs_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585905552,
      "name": "aafs_create",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:265",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585905552,
      "name": "aafs_create.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aafs_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586136784,
      "name": "aafs_create",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:266",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586136784,
      "name": "aafs_create.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aafs_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586386000,
      "name": "aafs_create",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:266",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586386000,
      "name": "aafs_create.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "aafs_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495440136,
      "name": "aafs_create",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:231",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495440136,
      "name": "aafs_create.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "aafs_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228807916,
      "name": "aafs_create",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:231",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228807916,
      "name": "aafs_create.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "aafs_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289484672,
      "name": "aafs_create",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:231",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289484672,
      "name": "aafs_create.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "aafs_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274634140,
      "name": "aafs_create",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:231",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274634140,
      "name": "aafs_create.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aafs_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583616816,
      "name": "aafs_create",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:231",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583616816,
      "name": "aafs_create.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aafs_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583553872,
      "name": "aafs_create",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:231",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583553872,
      "name": "aafs_create.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aafs_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583600592,
      "name": "aafs_create",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:231",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583600592,
      "name": "aafs_create.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aafs_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583697680,
      "name": "aafs_create",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:231",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583697680,
      "name": "aafs_create.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct dentry * aafs_create(const char * name, umode_t mode, struct dentry * parent, void * data, void * link, const struct file_operations * fops, const struct inode_operations * iops)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
struct dentry * aafs_create(const char * name, umode_t mode, struct dentry * parent, void * data, void * link, const struct file_operations * fops, const struct inode_operations * iops)
```
</details>
</li>
</ul>
