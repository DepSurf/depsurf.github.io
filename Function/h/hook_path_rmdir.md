# Function: <code>hook_path_rmdir</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int hook_path_rmdir(const const struct path * dir, const struct dentry * dentry)
```

```json
{
  "name": "hook_path_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584320816,
      "name": "hook_path_rmdir",
      "external": false,
      "loc": "security/landlock/fs.c:631",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584320816,
      "name": "hook_path_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int hook_path_rmdir(const const struct path * dir, const struct dentry * dentry)
```

```json
{
  "name": "hook_path_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584707312,
      "name": "hook_path_rmdir",
      "external": false,
      "loc": "security/landlock/fs.c:631",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584707312,
      "name": "hook_path_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int hook_path_rmdir(const const struct path * dir, const struct dentry * dentry)
```

```json
{
  "name": "hook_path_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hook_path_rmdir",
      "external": false,
      "loc": "security/landlock/fs.c:1137",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585380928,
      "name": "hook_path_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071594089835,
      "name": "hook_path_rmdir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int hook_path_rmdir(const const struct path * dir, const struct dentry * dentry)
```

```json
{
  "name": "hook_path_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hook_path_rmdir",
      "external": false,
      "loc": "security/landlock/fs.c:1152",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586133536,
      "name": "hook_path_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
    },
    {
      "addr": 18446744071596102234,
      "name": "hook_path_rmdir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int hook_path_rmdir(const const struct path * dir, const struct dentry * dentry)
```

```json
{
  "name": "hook_path_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hook_path_rmdir",
      "external": false,
      "loc": "security/landlock/fs.c:1152",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586371344,
      "name": "hook_path_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071596625352,
      "name": "hook_path_rmdir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int hook_path_rmdir(const const struct path * dir, const struct dentry * dentry)
```

```json
{
  "name": "hook_path_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586635680,
      "name": "hook_path_rmdir",
      "external": false,
      "loc": "security/landlock/fs.c:1068",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586635680,
      "name": "hook_path_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int hook_path_rmdir(const const struct path * dir, const struct dentry * dentry)
```
</details>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
