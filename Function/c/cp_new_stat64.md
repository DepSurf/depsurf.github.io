# Function: <code>cp_new_stat64</code>

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
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
long int cp_new_stat64(struct kstat * stat, struct stat64 * statbuf)
```

```json
{
  "name": "cp_new_stat64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493347992,
      "name": "cp_new_stat64",
      "external": false,
      "loc": "fs/stat.c:443",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_sys_fstatat64",
        "fs/stat.c:__do_sys_fstat64",
        "fs/stat.c:__do_sys_lstat64",
        "fs/stat.c:__do_sys_stat64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493347992,
      "name": "cp_new_stat64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
long int cp_new_stat64(struct kstat * stat, struct stat64 * statbuf)
```

```json
{
  "name": "cp_new_stat64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226938904,
      "name": "cp_new_stat64",
      "external": false,
      "loc": "fs/stat.c:443",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_sys_fstatat64",
        "fs/stat.c:__do_sys_fstat64",
        "fs/stat.c:__do_sys_lstat64",
        "fs/stat.c:__do_sys_stat64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226938904,
      "name": "cp_new_stat64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int cp_new_stat64(struct kstat * stat, struct stat64 * statbuf)
```

```json
{
  "name": "cp_new_stat64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286890448,
      "name": "cp_new_stat64",
      "external": false,
      "loc": "fs/stat.c:443",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_sys_fstatat64",
        "fs/stat.c:__do_sys_fstat64",
        "fs/stat.c:__do_sys_lstat64",
        "fs/stat.c:__do_sys_stat64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286890448,
      "name": "cp_new_stat64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
long int cp_new_stat64(struct kstat * stat, struct stat64 * statbuf)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
long int cp_new_stat64(struct kstat * stat, struct stat64 * statbuf)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
long int cp_new_stat64(struct kstat * stat, struct stat64 * statbuf)
```
</details>
</li>
</ul>
