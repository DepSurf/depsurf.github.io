# Function: <code>__cgroup_procs_start</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cgroup_procs_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580108336,
      "name": "__cgroup_procs_start",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4267",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580108336,
      "name": "__cgroup_procs_start.isra.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cgroup_procs_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580167504,
      "name": "__cgroup_procs_start",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4304",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580167504,
      "name": "__cgroup_procs_start.isra.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cgroup_procs_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580215424,
      "name": "__cgroup_procs_start",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4373",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580215424,
      "name": "__cgroup_procs_start.isra.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cgroup_procs_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580263392,
      "name": "__cgroup_procs_start",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4663",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580263392,
      "name": "__cgroup_procs_start.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
  "name": "__cgroup_procs_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580311696,
      "name": "__cgroup_procs_start",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4677",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580311696,
      "name": "__cgroup_procs_start.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
void * __cgroup_procs_start(struct seq_file * s, loff_t * pos, unsigned int iter_flags)
```

```json
{
  "name": "__cgroup_procs_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580381728,
      "name": "__cgroup_procs_start",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4611",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580381728,
      "name": "__cgroup_procs_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
void * __cgroup_procs_start(struct seq_file * s, loff_t * pos, unsigned int iter_flags)
```

```json
{
  "name": "__cgroup_procs_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580368640,
      "name": "__cgroup_procs_start",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4612",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580368640,
      "name": "__cgroup_procs_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void * __cgroup_procs_start(struct seq_file * s, loff_t * pos, unsigned int iter_flags)
```

```json
{
  "name": "__cgroup_procs_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580371664,
      "name": "__cgroup_procs_start",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4625",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580371664,
      "name": "__cgroup_procs_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
void * __cgroup_procs_start(struct seq_file * s, loff_t * pos, unsigned int iter_flags)
```

```json
{
  "name": "__cgroup_procs_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_procs_start",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4800",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580532064,
      "name": "__cgroup_procs_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446744071592161406,
      "name": "__cgroup_procs_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void * __cgroup_procs_start(struct seq_file * s, loff_t * pos, unsigned int iter_flags)
```

```json
{
  "name": "__cgroup_procs_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_procs_start",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4811",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580729328,
      "name": "__cgroup_procs_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
    },
    {
      "addr": 18446744071593934444,
      "name": "__cgroup_procs_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void * __cgroup_procs_start(struct seq_file * s, loff_t * pos, unsigned int iter_flags)
```

```json
{
  "name": "__cgroup_procs_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_procs_start",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5008",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581005040,
      "name": "__cgroup_procs_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    },
    {
      "addr": 18446744071596000010,
      "name": "__cgroup_procs_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void * __cgroup_procs_start(struct seq_file * s, loff_t * pos, unsigned int iter_flags)
```

```json
{
  "name": "__cgroup_procs_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_procs_start",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4985",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581093632,
      "name": "__cgroup_procs_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    },
    {
      "addr": 18446744071596518180,
      "name": "__cgroup_procs_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void * __cgroup_procs_start(struct seq_file * s, loff_t * pos, unsigned int iter_flags)
```

```json
{
  "name": "__cgroup_procs_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_procs_start",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5021",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581191152,
      "name": "__cgroup_procs_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    },
    {
      "addr": 18446744071597418423,
      "name": "__cgroup_procs_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
  "name": "__cgroup_procs_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491564328,
      "name": "__cgroup_procs_start",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4677",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491564328,
      "name": "__cgroup_procs_start.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void * __cgroup_procs_start(struct seq_file * s, loff_t * pos, unsigned int iter_flags)
```

```json
{
  "name": "__cgroup_procs_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225528684,
      "name": "__cgroup_procs_start",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4677",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225528684,
      "name": "__cgroup_procs_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__cgroup_procs_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284542256,
      "name": "__cgroup_procs_start",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4677",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284542256,
      "name": "__cgroup_procs_start.isra.0",
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
  "name": "__cgroup_procs_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271977902,
      "name": "__cgroup_procs_start",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4677",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271977902,
      "name": "__cgroup_procs_start.isra.0",
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
  "name": "__cgroup_procs_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580280496,
      "name": "__cgroup_procs_start",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4677",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580280496,
      "name": "__cgroup_procs_start.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
  "name": "__cgroup_procs_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580227936,
      "name": "__cgroup_procs_start",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4677",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580227936,
      "name": "__cgroup_procs_start.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
  "name": "__cgroup_procs_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580271744,
      "name": "__cgroup_procs_start",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4677",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580271744,
      "name": "__cgroup_procs_start.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
  "name": "__cgroup_procs_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580325280,
      "name": "__cgroup_procs_start",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4677",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580325280,
      "name": "__cgroup_procs_start.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
void * __cgroup_procs_start(struct seq_file * s, loff_t * pos, unsigned int iter_flags)
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void * __cgroup_procs_start(struct seq_file * s, loff_t * pos, unsigned int iter_flags)
```
</details>
</li>
</ul>
