# Function: <code>cgroup_pressure_write</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file * of, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "cgroup_pressure_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580257968,
      "name": "cgroup_pressure_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3623",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580257968,
      "name": "cgroup_pressure_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file * of, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "cgroup_pressure_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580306192,
      "name": "cgroup_pressure_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3625",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580306192,
      "name": "cgroup_pressure_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file * of, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "cgroup_pressure_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580375984,
      "name": "cgroup_pressure_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3566",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580375984,
      "name": "cgroup_pressure_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
ssize_t cgroup_pressure_write(struct kernfs_open_file * of, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "cgroup_pressure_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580362848,
      "name": "cgroup_pressure_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3562",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580362848,
      "name": "cgroup_pressure_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
ssize_t cgroup_pressure_write(struct kernfs_open_file * of, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "cgroup_pressure_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580365904,
      "name": "cgroup_pressure_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3575",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580365904,
      "name": "cgroup_pressure_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
ssize_t cgroup_pressure_write(struct kernfs_open_file * of, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "cgroup_pressure_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580525552,
      "name": "cgroup_pressure_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3630",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580525552,
      "name": "cgroup_pressure_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
ssize_t cgroup_pressure_write(struct kernfs_open_file * of, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "cgroup_pressure_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580722432,
      "name": "cgroup_pressure_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3641",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580722432,
      "name": "cgroup_pressure_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
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
ssize_t cgroup_pressure_write(struct kernfs_open_file * of, char * buf, size_t nbytes, loff_t off)
```

```json
{
  "name": "cgroup_pressure_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_pressure_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3824",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580997312,
      "name": "cgroup_pressure_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071595999871,
      "name": "cgroup_pressure_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
ssize_t cgroup_pressure_write(struct kernfs_open_file * of, char * buf, size_t nbytes, loff_t off)
```

```json
{
  "name": "cgroup_pressure_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_pressure_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3793",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581085872,
      "name": "cgroup_pressure_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071596518041,
      "name": "cgroup_pressure_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
ssize_t cgroup_pressure_write(struct kernfs_open_file * of, char * buf, size_t nbytes, loff_t off)
```

```json
{
  "name": "cgroup_pressure_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_pressure_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3855",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581183392,
      "name": "cgroup_pressure_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071597418263,
      "name": "cgroup_pressure_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file * of, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "cgroup_pressure_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491558088,
      "name": "cgroup_pressure_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3625",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491558088,
      "name": "cgroup_pressure_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
ssize_t cgroup_pressure_write(struct kernfs_open_file * of, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "cgroup_pressure_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225522520,
      "name": "cgroup_pressure_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3625",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225522520,
      "name": "cgroup_pressure_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
ssize_t cgroup_pressure_write(struct kernfs_open_file * of, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "cgroup_pressure_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284531536,
      "name": "cgroup_pressure_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3625",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284531536,
      "name": "cgroup_pressure_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file * of, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "cgroup_pressure_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271972046,
      "name": "cgroup_pressure_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3625",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271972046,
      "name": "cgroup_pressure_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file * of, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "cgroup_pressure_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580274992,
      "name": "cgroup_pressure_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3625",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580274992,
      "name": "cgroup_pressure_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file * of, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "cgroup_pressure_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580222496,
      "name": "cgroup_pressure_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3625",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580222496,
      "name": "cgroup_pressure_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file * of, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "cgroup_pressure_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580266240,
      "name": "cgroup_pressure_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3625",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580266240,
      "name": "cgroup_pressure_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file * of, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "cgroup_pressure_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580319648,
      "name": "cgroup_pressure_write",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3625",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580319648,
      "name": "cgroup_pressure_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file * of, char * buf, size_t nbytes, enum psi_res res)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>loff_t off</code>
</li>
<li>
<b>Param removed. </b>
<code>enum psi_res res</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
