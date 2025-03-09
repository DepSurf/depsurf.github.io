# Function: <code>fetch_memory_u64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void fetch_memory_u64(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_u64",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580316480,
      "name": "fetch_memory_u64",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:160",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_u64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580346480,
      "name": "fetch_memory_u64",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:134",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_u64"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580316480,
      "name": "fetch_memory_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071580346480,
      "name": "fetch_memory_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void fetch_memory_u64(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_u64",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580371361,
      "name": "fetch_memory_u64",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:160",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_u64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580402616,
      "name": "fetch_memory_u64",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:134",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_u64"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580371200,
      "name": "fetch_memory_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071580402128,
      "name": "fetch_memory_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void fetch_memory_u64(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_u64",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580419105,
      "name": "fetch_memory_u64",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:171",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_u64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580450760,
      "name": "fetch_memory_u64",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:134",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_u64"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580418944,
      "name": "fetch_memory_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071580450272,
      "name": "fetch_memory_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void fetch_memory_u64(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_u64",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580431169,
      "name": "fetch_memory_u64",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:174",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_u64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580462152,
      "name": "fetch_memory_u64",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:136",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_u64"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580431008,
      "name": "fetch_memory_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071580461664,
      "name": "fetch_memory_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void fetch_memory_u64(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_u64",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580487601,
      "name": "fetch_memory_u64",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:174",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_u64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580518136,
      "name": "fetch_memory_u64",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:136",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_u64"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580487440,
      "name": "fetch_memory_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071580517648,
      "name": "fetch_memory_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void fetch_memory_u64(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_u64",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580574961,
      "name": "fetch_memory_u64",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:198",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_u64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580606904,
      "name": "fetch_memory_u64",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:137",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_u64"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580574800,
      "name": "fetch_memory_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071580606400,
      "name": "fetch_memory_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void fetch_memory_u64(struct pt_regs * regs, void * addr, void * dest)
```
</details>
</li>
</ul>
