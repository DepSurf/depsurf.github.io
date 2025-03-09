# Function: <code>psi_write</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "psi_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579857952,
      "name": "psi_write",
      "external": false,
      "loc": "kernel/sched/psi.c:1190",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_write",
        "kernel/sched/psi.c:psi_memory_write",
        "kernel/sched/psi.c:psi_io_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857952,
      "name": "psi_write.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "psi_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579906480,
      "name": "psi_write",
      "external": false,
      "loc": "kernel/sched/psi.c:1191",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_write",
        "kernel/sched/psi.c:psi_memory_write",
        "kernel/sched/psi.c:psi_io_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579906480,
      "name": "psi_write.isra.0",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t psi_write(struct file * file, const char * user_buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579950544,
      "name": "psi_write",
      "external": false,
      "loc": "kernel/sched/psi.c:1240",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_write",
        "kernel/sched/psi.c:psi_memory_write",
        "kernel/sched/psi.c:psi_io_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579950544,
      "name": "psi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t psi_write(struct file * file, const char * user_buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579939104,
      "name": "psi_write",
      "external": false,
      "loc": "kernel/sched/psi.c:1252",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_write",
        "kernel/sched/psi.c:psi_memory_write",
        "kernel/sched/psi.c:psi_io_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939104,
      "name": "psi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t psi_write(struct file * file, const char * user_buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579946656,
      "name": "psi_write",
      "external": false,
      "loc": "kernel/sched/psi.c:1284",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_write",
        "kernel/sched/psi.c:psi_memory_write",
        "kernel/sched/psi.c:psi_io_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579946656,
      "name": "psi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t psi_write(struct file * file, const char * user_buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580070928,
      "name": "psi_write",
      "external": false,
      "loc": "kernel/sched/psi.c:1282",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_write",
        "kernel/sched/psi.c:psi_memory_write",
        "kernel/sched/psi.c:psi_io_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070928,
      "name": "psi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
ssize_t psi_write(struct file * file, const char * user_buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580207648,
      "name": "psi_write",
      "external": false,
      "loc": "kernel/sched/psi.c:1285",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_cpu_write",
        "kernel/sched/build_utility.c:psi_memory_write",
        "kernel/sched/build_utility.c:psi_io_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580207648,
      "name": "psi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
ssize_t psi_write(struct file * file, const char * user_buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580399472,
      "name": "psi_write",
      "external": false,
      "loc": "kernel/sched/psi.c:1461",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_cpu_write",
        "kernel/sched/build_utility.c:psi_memory_write",
        "kernel/sched/build_utility.c:psi_io_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580399472,
      "name": "psi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
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
ssize_t psi_write(struct file * file, const char * user_buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580468096,
      "name": "psi_write",
      "external": false,
      "loc": "kernel/sched/psi.c:1520",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_cpu_write",
        "kernel/sched/build_utility.c:psi_memory_write",
        "kernel/sched/build_utility.c:psi_io_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580468096,
      "name": "psi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
ssize_t psi_write(struct file * file, const char * user_buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580527888,
      "name": "psi_write",
      "external": false,
      "loc": "kernel/sched/psi.c:1512",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_cpu_write",
        "kernel/sched/build_utility.c:psi_memory_write",
        "kernel/sched/build_utility.c:psi_io_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580527888,
      "name": "psi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "psi_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491106448,
      "name": "psi_write",
      "external": false,
      "loc": "kernel/sched/psi.c:1191",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_write",
        "kernel/sched/psi.c:psi_memory_write",
        "kernel/sched/psi.c:psi_io_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491106448,
      "name": "psi_write.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
    },
    {
      "addr": 18446603336491107008,
      "name": "psi_write.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "psi_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225111124,
      "name": "psi_write",
      "external": false,
      "loc": "kernel/sched/psi.c:1191",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225111124,
      "name": "psi_write.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
ssize_t psi_write(struct file * file, const char * user_buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283998736,
      "name": "psi_write",
      "external": false,
      "loc": "kernel/sched/psi.c:1191",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_write",
        "kernel/sched/psi.c:psi_memory_write",
        "kernel/sched/psi.c:psi_io_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283998736,
      "name": "psi_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "psi_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271688140,
      "name": "psi_write",
      "external": false,
      "loc": "kernel/sched/psi.c:1191",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271688140,
      "name": "psi_write.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "psi_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579878592,
      "name": "psi_write",
      "external": false,
      "loc": "kernel/sched/psi.c:1191",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_write",
        "kernel/sched/psi.c:psi_memory_write",
        "kernel/sched/psi.c:psi_io_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579878592,
      "name": "psi_write.isra.0",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "psi_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579813584,
      "name": "psi_write",
      "external": false,
      "loc": "kernel/sched/psi.c:1191",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_write",
        "kernel/sched/psi.c:psi_memory_write",
        "kernel/sched/psi.c:psi_io_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579813584,
      "name": "psi_write.isra.0",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "psi_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579866752,
      "name": "psi_write",
      "external": false,
      "loc": "kernel/sched/psi.c:1191",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_write",
        "kernel/sched/psi.c:psi_memory_write",
        "kernel/sched/psi.c:psi_io_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866752,
      "name": "psi_write.isra.0",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "psi_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579912128,
      "name": "psi_write",
      "external": false,
      "loc": "kernel/sched/psi.c:1191",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_write",
        "kernel/sched/psi.c:psi_memory_write",
        "kernel/sched/psi.c:psi_io_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579912128,
      "name": "psi_write.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
ssize_t psi_write(struct file * file, const char * user_buf, size_t nbytes, enum psi_res res)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
ssize_t psi_write(struct file * file, const char * user_buf, size_t nbytes, enum psi_res res)
```
</details>
</li>
</ul>
