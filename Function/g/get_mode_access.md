# Function: <code>get_mode_access</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_mode_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584320192,
      "name": "get_mode_access",
      "external": false,
      "loc": "security/landlock/fs.c:519",
      "file": "security/landlock/fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/fs.c:hook_path_mknod",
        "security/landlock/fs.c:hook_path_mknod",
        "security/landlock/fs.c:hook_path_rename",
        "security/landlock/fs.c:hook_path_rename",
        "security/landlock/fs.c:hook_path_link",
        "security/landlock/fs.c:hook_path_link"
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
  "name": "get_mode_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584707618,
      "name": "get_mode_access",
      "external": false,
      "loc": "security/landlock/fs.c:519",
      "file": "security/landlock/fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/fs.c:hook_path_mknod",
        "security/landlock/fs.c:hook_path_rename",
        "security/landlock/fs.c:hook_path_link"
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
  "name": "get_mode_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585381879,
      "name": "get_mode_access",
      "external": false,
      "loc": "security/landlock/fs.c:661",
      "file": "security/landlock/fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/fs.c:hook_path_mknod",
        "security/landlock/fs.c:current_check_refer_path",
        "security/landlock/fs.c:current_check_refer_path"
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
  "name": "get_mode_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586128807,
      "name": "get_mode_access",
      "external": false,
      "loc": "security/landlock/fs.c:662",
      "file": "security/landlock/fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/fs.c:hook_path_mknod",
        "security/landlock/fs.c:current_check_refer_path",
        "security/landlock/fs.c:current_check_refer_path"
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
  "name": "get_mode_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586367479,
      "name": "get_mode_access",
      "external": false,
      "loc": "security/landlock/fs.c:662",
      "file": "security/landlock/fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/fs.c:hook_path_mknod",
        "security/landlock/fs.c:current_check_refer_path",
        "security/landlock/fs.c:current_check_refer_path"
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
access_mask_t get_mode_access(const umode_t mode)
```

```json
{
  "name": "get_mode_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586629296,
      "name": "get_mode_access",
      "external": false,
      "loc": "security/landlock/fs.c:578",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/fs.c:hook_path_mknod",
        "security/landlock/fs.c:current_check_refer_path",
        "security/landlock/fs.c:current_check_refer_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586629296,
      "name": "get_mode_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
access_mask_t get_mode_access(const umode_t mode)
```
</details>
</li>
</ul>
