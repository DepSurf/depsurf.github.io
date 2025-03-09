# Function: <code>pick_file</code>

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
struct file * pick_file(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "pick_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582270384,
      "name": "pick_file",
      "external": false,
      "loc": "fs/file.c:599",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:replace_fd",
        "fs/file.c:__close_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582270384,
      "name": "pick_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct file * pick_file(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "pick_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582295888,
      "name": "pick_file",
      "external": false,
      "loc": "fs/file.c:599",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:replace_fd",
        "fs/file.c:__close_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582295888,
      "name": "pick_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct file * pick_file(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "pick_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582614768,
      "name": "pick_file",
      "external": false,
      "loc": "fs/file.c:609",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:replace_fd",
        "fs/file.c:__close_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582614768,
      "name": "pick_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
struct file * pick_file(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "pick_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583153910,
      "name": "pick_file",
      "external": false,
      "loc": "fs/file.c:637",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__close_fd_get_file"
      ],
      "caller_func": [
        "fs/file.c:replace_fd",
        "fs/file.c:close_fd_get_file",
        "fs/file.c:__close_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583147808,
      "name": "pick_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct file * pick_file(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "pick_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583722464,
      "name": "pick_file",
      "external": false,
      "loc": "fs/file.c:637",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:replace_fd",
        "fs/file.c:close_fd_get_file",
        "fs/file.c:__close_fd_get_file",
        "fs/file.c:__close_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583722464,
      "name": "pick_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
struct file * pick_file(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "pick_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583939504,
      "name": "pick_file",
      "external": false,
      "loc": "fs/file.c:637",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:replace_fd",
        "fs/file.c:close_fd_get_file",
        "fs/file.c:__close_fd_get_file",
        "fs/file.c:__close_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583939504,
      "name": "pick_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
struct file * pick_file(struct files_struct * files, unsigned int fd)
```
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct file * pick_file(struct files_struct * files, unsigned int fd)
```
</details>
</li>
</ul>
