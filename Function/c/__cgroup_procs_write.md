# Function: <code>__cgroup_procs_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t __cgroup_procs_write(struct kernfs_open_file * of, char * buf, size_t nbytes, loff_t off, bool threadgroup)
```

```json
{
  "name": "__cgroup_procs_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579987728,
      "name": "__cgroup_procs_write",
      "external": false,
      "loc": "kernel/cgroup.c:2824",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_tasks_write",
        "kernel/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579987728,
      "name": "__cgroup_procs_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cgroup_procs_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580017296,
      "name": "__cgroup_procs_write",
      "external": false,
      "loc": "kernel/cgroup.c:2882",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_procs_write",
        "kernel/cgroup.c:cgroup_tasks_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580017296,
      "name": "__cgroup_procs_write.constprop.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cgroup_procs_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580050976,
      "name": "__cgroup_procs_write",
      "external": false,
      "loc": "kernel/cgroup.c:2891",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_procs_write",
        "kernel/cgroup.c:cgroup_tasks_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050976,
      "name": "__cgroup_procs_write.constprop.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t __cgroup_procs_write(struct kernfs_open_file * of, char * buf, size_t nbytes, loff_t off, bool threadgroup)
```

```json
{
  "name": "__cgroup_procs_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580054256,
      "name": "__cgroup_procs_write",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2485",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_tasks_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054256,
      "name": "__cgroup_procs_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 898
    }
  ]
}
```
</details>
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
ssize_t __cgroup_procs_write(struct kernfs_open_file * of, char * buf, bool threadgroup)
```

```json
{
  "name": "__cgroup_procs_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580367952,
      "name": "__cgroup_procs_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4744",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580367952,
      "name": "__cgroup_procs_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t __cgroup_procs_write(struct kernfs_open_file * of, char * buf, bool threadgroup)
```

```json
{
  "name": "__cgroup_procs_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_procs_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4917",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580527776,
      "name": "__cgroup_procs_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071592161385,
      "name": "__cgroup_procs_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
ssize_t __cgroup_procs_write(struct kernfs_open_file * of, char * buf, bool threadgroup)
```

```json
{
  "name": "__cgroup_procs_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_procs_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4928",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580724800,
      "name": "__cgroup_procs_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
    },
    {
      "addr": 18446744071593934423,
      "name": "__cgroup_procs_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
ssize_t __cgroup_procs_write(struct kernfs_open_file * of, char * buf, bool threadgroup)
```

```json
{
  "name": "__cgroup_procs_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_procs_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5125",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581000256,
      "name": "__cgroup_procs_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
    },
    {
      "addr": 18446744071595999989,
      "name": "__cgroup_procs_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
ssize_t __cgroup_procs_write(struct kernfs_open_file * of, char * buf, bool threadgroup)
```

```json
{
  "name": "__cgroup_procs_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_procs_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5102",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581088848,
      "name": "__cgroup_procs_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    },
    {
      "addr": 18446744071596518159,
      "name": "__cgroup_procs_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t __cgroup_procs_write(struct kernfs_open_file * of, char * buf, bool threadgroup)
```

```json
{
  "name": "__cgroup_procs_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_procs_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5138",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581186368,
      "name": "__cgroup_procs_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    },
    {
      "addr": 18446744071597418381,
      "name": "__cgroup_procs_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
ssize_t __cgroup_procs_write(struct kernfs_open_file * of, char * buf, size_t nbytes, loff_t off, bool threadgroup)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
ssize_t __cgroup_procs_write(struct kernfs_open_file * of, char * buf, size_t nbytes, loff_t off, bool threadgroup)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
ssize_t __cgroup_procs_write(struct kernfs_open_file * of, char * buf, size_t nbytes, loff_t off, bool threadgroup)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
ssize_t __cgroup_procs_write(struct kernfs_open_file * of, char * buf, bool threadgroup)
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
