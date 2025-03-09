# Function: <code>__fget_files</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct file * __fget_files(struct files_struct * files, unsigned int fd, fmode_t mask, unsigned int refs)
```

```json
{
  "name": "__fget_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582222320,
      "name": "__fget_files",
      "external": false,
      "loc": "fs/file.c:717",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup",
        "fs/file.c:fget_task",
        "fs/file.c:fget",
        "fs/file.c:fget_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582222320,
      "name": "__fget_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct file * __fget_files(struct files_struct * files, unsigned int fd, fmode_t mask, unsigned int refs)
```

```json
{
  "name": "__fget_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582269824,
      "name": "__fget_files",
      "external": false,
      "loc": "fs/file.c:817",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/file.c:fget_task",
        "fs/file.c:fget",
        "fs/file.c:fget_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269824,
      "name": "__fget_files",
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
struct file * __fget_files(struct files_struct * files, unsigned int fd, fmode_t mask, unsigned int refs)
```

```json
{
  "name": "__fget_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582295328,
      "name": "__fget_files",
      "external": false,
      "loc": "fs/file.c:829",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/file.c:fget_task",
        "fs/file.c:fget",
        "fs/file.c:fget_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582295328,
      "name": "__fget_files",
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
struct file * __fget_files(struct files_struct * files, unsigned int fd, fmode_t mask, unsigned int refs)
```

```json
{
  "name": "__fget_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582614160,
      "name": "__fget_files",
      "external": false,
      "loc": "fs/file.c:900",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/file.c:fget_task",
        "fs/file.c:fget",
        "fs/file.c:fget_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582614160,
      "name": "__fget_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
  "name": "__fget_files",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583149844,
      "name": "__fget_files",
      "external": false,
      "loc": "fs/file.c:908",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fget_light",
        "fs/file.c:fget_task",
        "fs/file.c:fget_raw",
        "fs/file.c:fget"
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
  "name": "__fget_files",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583723162,
      "name": "__fget_files",
      "external": false,
      "loc": "fs/file.c:908",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fget_light",
        "fs/file.c:fget_task",
        "fs/file.c:fget_raw",
        "fs/file.c:fget"
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
  "name": "__fget_files",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583940218,
      "name": "__fget_files",
      "external": false,
      "loc": "fs/file.c:909",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fget_light",
        "fs/file.c:fget_task",
        "fs/file.c:fget_raw",
        "fs/file.c:fget"
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
  "name": "__fget_files",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584148914,
      "name": "__fget_files",
      "external": false,
      "loc": "fs/file.c:1031",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/file.c:__fdget_pos",
        "fs/file.c:__fdget_raw",
        "fs/file.c:fget_task",
        "fs/file.c:fget"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct file * __fget_files(struct files_struct * files, unsigned int fd, fmode_t mask, unsigned int refs)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct file * __fget_files(struct files_struct * files, unsigned int fd, fmode_t mask, unsigned int refs)
```
</details>
</li>
</ul>
