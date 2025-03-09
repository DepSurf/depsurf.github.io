# Function: <code>current_check_refer_path</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int current_check_refer_path(const struct dentry * old_dentry, const const struct path * new_dir, const struct dentry * new_dentry, const bool removable, const bool exchange)
```

```json
{
  "name": "current_check_refer_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "current_check_refer_path",
      "external": false,
      "loc": "security/landlock/fs.c:811",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/fs.c:hook_path_rename",
        "security/landlock/fs.c:hook_path_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585378560,
      "name": "current_check_refer_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1383
    },
    {
      "addr": 18446744071594089658,
      "name": "current_check_refer_path.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int current_check_refer_path(const struct dentry * old_dentry, const const struct path * new_dir, const struct dentry * new_dentry, const bool removable, const bool exchange)
```

```json
{
  "name": "current_check_refer_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "current_check_refer_path",
      "external": false,
      "loc": "security/landlock/fs.c:813",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/fs.c:hook_path_rename",
        "security/landlock/fs.c:hook_path_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586130160,
      "name": "current_check_refer_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1465
    },
    {
      "addr": 18446744071596101963,
      "name": "current_check_refer_path.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int current_check_refer_path(const struct dentry * old_dentry, const const struct path * new_dir, const struct dentry * new_dentry, const bool removable, const bool exchange)
```

```json
{
  "name": "current_check_refer_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "current_check_refer_path",
      "external": false,
      "loc": "security/landlock/fs.c:813",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/fs.c:hook_path_rename",
        "security/landlock/fs.c:hook_path_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586368848,
      "name": "current_check_refer_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1486
    },
    {
      "addr": 18446744071596625165,
      "name": "current_check_refer_path.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int current_check_refer_path(const struct dentry * old_dentry, const const struct path * new_dir, const struct dentry * new_dentry, const bool removable, const bool exchange)
```

```json
{
  "name": "current_check_refer_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586634544,
      "name": "current_check_refer_path",
      "external": false,
      "loc": "security/landlock/fs.c:731",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/fs.c:hook_path_rename",
        "security/landlock/fs.c:hook_path_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586634544,
      "name": "current_check_refer_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 721
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int current_check_refer_path(const struct dentry * old_dentry, const const struct path * new_dir, const struct dentry * new_dentry, const bool removable, const bool exchange)
```
</details>
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
