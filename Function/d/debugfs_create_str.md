# Function: <code>debugfs_create_str</code>

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
void debugfs_create_str(const char * name, umode_t mode, struct dentry * parent, char * * value)
```

```json
{
  "name": "debugfs_create_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583722368,
      "name": "debugfs_create_str",
      "external": true,
      "loc": "fs/debugfs/file.c:951",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:update_sched_domain_debugfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583722368,
      "name": "debugfs_create_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void debugfs_create_str(const char * name, umode_t mode, struct dentry * parent, char * * value)
```

```json
{
  "name": "debugfs_create_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584083168,
      "name": "debugfs_create_str",
      "external": true,
      "loc": "fs/debugfs/file.c:936",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:update_sched_domain_debugfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584083168,
      "name": "debugfs_create_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void debugfs_create_str(const char * name, umode_t mode, struct dentry * parent, char * * value)
```

```json
{
  "name": "debugfs_create_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584676928,
      "name": "debugfs_create_str",
      "external": true,
      "loc": "fs/debugfs/file.c:936",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:update_sched_domain_debugfs",
        "drivers/opp/debugfs.c:opp_debug_create_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584676928,
      "name": "debugfs_create_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void debugfs_create_str(const char * name, umode_t mode, struct dentry * parent, char * * value)
```

```json
{
  "name": "debugfs_create_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585361744,
      "name": "debugfs_create_str",
      "external": true,
      "loc": "fs/debugfs/file.c:952",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:update_sched_domain_debugfs",
        "drivers/opp/debugfs.c:opp_debug_create_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585361744,
      "name": "debugfs_create_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void debugfs_create_str(const char * name, umode_t mode, struct dentry * parent, char * * value)
```

```json
{
  "name": "debugfs_create_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585590960,
      "name": "debugfs_create_str",
      "external": true,
      "loc": "fs/debugfs/file.c:944",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585590960,
      "name": "debugfs_create_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void debugfs_create_str(const char * name, umode_t mode, struct dentry * parent, char * * value)
```

```json
{
  "name": "debugfs_create_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585831344,
      "name": "debugfs_create_str",
      "external": true,
      "loc": "fs/debugfs/file.c:1080",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_create_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585831344,
      "name": "debugfs_create_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void debugfs_create_str(const char * name, umode_t mode, struct dentry * parent, char * * value)
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
