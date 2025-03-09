# Function: <code>fetch_memory_string_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void fetch_memory_string_size(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_string_size",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580316800,
      "name": "fetch_memory_string_size",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:191",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_string_size"
      ]
    },
    {
      "addr": 18446744071580347760,
      "name": "fetch_memory_string_size",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:161",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_string_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580316800,
      "name": "fetch_memory_string_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071580347760,
      "name": "fetch_memory_string_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void fetch_memory_string_size(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_string_size",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580371520,
      "name": "fetch_memory_string_size",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:191",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_string_size"
      ]
    },
    {
      "addr": 18446744071580402826,
      "name": "fetch_memory_string_size",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:161",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_string_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580371520,
      "name": "fetch_memory_string_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071580402736,
      "name": "fetch_memory_string_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void fetch_memory_string_size(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_string_size",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580419264,
      "name": "fetch_memory_string_size",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:202",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_string_size"
      ]
    },
    {
      "addr": 18446744071580450970,
      "name": "fetch_memory_string_size",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:161",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_string_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580419264,
      "name": "fetch_memory_string_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071580450880,
      "name": "fetch_memory_string_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void fetch_memory_string_size(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_string_size",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580430272,
      "name": "fetch_memory_string_size",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:205",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_string_size"
      ]
    },
    {
      "addr": 18446744071580462362,
      "name": "fetch_memory_string_size",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:163",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_string_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580430272,
      "name": "fetch_memory_string_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071580462272,
      "name": "fetch_memory_string_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void fetch_memory_string_size(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_string_size",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580486688,
      "name": "fetch_memory_string_size",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:205",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_string_size"
      ]
    },
    {
      "addr": 18446744071580518346,
      "name": "fetch_memory_string_size",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:163",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_string_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580486688,
      "name": "fetch_memory_string_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071580518256,
      "name": "fetch_memory_string_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void fetch_memory_string_size(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_string_size",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580574016,
      "name": "fetch_memory_string_size",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:229",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_string_size"
      ]
    },
    {
      "addr": 18446744071580607052,
      "name": "fetch_memory_string_size",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:166",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_string_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580574016,
      "name": "fetch_memory_string_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071580606976,
      "name": "fetch_memory_string_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void fetch_memory_string_size(struct pt_regs * regs, void * addr, void * dest)
```
</details>
</li>
</ul>
