# Function: <code>check_access_path</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int check_access_path(const const struct landlock_ruleset * domain, const const struct path * path, u32 access_request)
```

```json
{
  "name": "check_access_path",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584320862,
      "name": "check_access_path",
      "external": false,
      "loc": "security/landlock/fs.c:230",
      "file": "security/landlock/fs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/landlock/fs.c:hook_path_rmdir",
        "security/landlock/fs.c:hook_path_unlink",
        "security/landlock/fs.c:hook_path_symlink",
        "security/landlock/fs.c:hook_path_mkdir"
      ],
      "caller_func": [
        "security/landlock/fs.c:hook_file_open",
        "security/landlock/fs.c:hook_path_rmdir",
        "security/landlock/fs.c:hook_path_unlink",
        "security/landlock/fs.c:hook_path_symlink",
        "security/landlock/fs.c:hook_path_mknod",
        "security/landlock/fs.c:hook_path_mknod",
        "security/landlock/fs.c:hook_path_mkdir",
        "security/landlock/fs.c:hook_path_rename",
        "security/landlock/fs.c:hook_path_link",
        "security/landlock/fs.c:hook_path_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584319104,
      "name": "check_access_path.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
    },
    {
      "addr": 18446744071584319584,
      "name": "check_access_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
  "name": "check_access_path",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584707553,
      "name": "check_access_path",
      "external": false,
      "loc": "security/landlock/fs.c:230",
      "file": "security/landlock/fs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/landlock/fs.c:hook_file_open",
        "security/landlock/fs.c:hook_path_rmdir",
        "security/landlock/fs.c:hook_path_unlink",
        "security/landlock/fs.c:hook_path_symlink",
        "security/landlock/fs.c:hook_path_mknod",
        "security/landlock/fs.c:hook_path_mkdir",
        "security/landlock/fs.c:hook_path_rename",
        "security/landlock/fs.c:hook_path_link"
      ],
      "caller_func": [
        "security/landlock/fs.c:hook_file_open",
        "security/landlock/fs.c:hook_path_rmdir",
        "security/landlock/fs.c:hook_path_unlink",
        "security/landlock/fs.c:hook_path_symlink",
        "security/landlock/fs.c:hook_path_mknod",
        "security/landlock/fs.c:hook_path_mkdir",
        "security/landlock/fs.c:hook_path_rename",
        "security/landlock/fs.c:hook_path_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584706160,
      "name": "check_access_path.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 519
    },
    {
      "addr": 18446744071592307576,
      "name": "check_access_path.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
  "name": "check_access_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585378029,
      "name": "check_access_path",
      "external": false,
      "loc": "security/landlock/fs.c:639",
      "file": "security/landlock/fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/fs.c:hook_file_open",
        "security/landlock/fs.c:hook_path_rmdir",
        "security/landlock/fs.c:hook_path_unlink",
        "security/landlock/fs.c:hook_path_symlink",
        "security/landlock/fs.c:hook_path_mknod",
        "security/landlock/fs.c:hook_path_mkdir"
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
  "name": "check_access_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586132357,
      "name": "check_access_path",
      "external": false,
      "loc": "security/landlock/fs.c:638",
      "file": "security/landlock/fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/fs.c:hook_path_truncate",
        "security/landlock/fs.c:hook_path_rmdir",
        "security/landlock/fs.c:hook_path_unlink",
        "security/landlock/fs.c:hook_path_symlink",
        "security/landlock/fs.c:hook_path_mknod",
        "security/landlock/fs.c:hook_path_mkdir"
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
  "name": "check_access_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586370581,
      "name": "check_access_path",
      "external": false,
      "loc": "security/landlock/fs.c:638",
      "file": "security/landlock/fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/fs.c:hook_path_truncate",
        "security/landlock/fs.c:hook_path_rmdir",
        "security/landlock/fs.c:hook_path_unlink",
        "security/landlock/fs.c:hook_path_symlink",
        "security/landlock/fs.c:hook_path_mknod",
        "security/landlock/fs.c:hook_path_mkdir"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int check_access_path(const const struct landlock_ruleset * domain, const const struct path * path, access_mask_t access_request)
```

```json
{
  "name": "check_access_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586632928,
      "name": "check_access_path",
      "external": false,
      "loc": "security/landlock/fs.c:554",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/fs.c:hook_path_truncate",
        "security/landlock/fs.c:hook_path_rmdir",
        "security/landlock/fs.c:hook_path_unlink",
        "security/landlock/fs.c:hook_path_symlink",
        "security/landlock/fs.c:hook_path_mknod",
        "security/landlock/fs.c:hook_path_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586632928,
      "name": "check_access_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int check_access_path(const const struct landlock_ruleset * domain, const const struct path * path, u32 access_request)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int check_access_path(const const struct landlock_ruleset * domain, const const struct path * path, u32 access_request)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int check_access_path(const const struct landlock_ruleset * domain, const const struct path * path, access_mask_t access_request)
```
</details>
</li>
</ul>
