# Function: <code>fetch_memory_u8</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void fetch_memory_u8(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_u8",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580315904,
      "name": "fetch_memory_u8",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:160",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_u8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580347536,
      "name": "fetch_memory_u8",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:134",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_u8"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580315904,
      "name": "fetch_memory_u8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071580347536,
      "name": "fetch_memory_u8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void fetch_memory_u8(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_u8",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580370781,
      "name": "fetch_memory_u8",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:160",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_u8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580402232,
      "name": "fetch_memory_u8",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:134",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_u8"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580370624,
      "name": "fetch_memory_u8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071580401840,
      "name": "fetch_memory_u8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void fetch_memory_u8(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_u8",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580418525,
      "name": "fetch_memory_u8",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:171",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_u8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580450376,
      "name": "fetch_memory_u8",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:134",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_u8"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580418368,
      "name": "fetch_memory_u8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071580449984,
      "name": "fetch_memory_u8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void fetch_memory_u8(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_u8",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580430589,
      "name": "fetch_memory_u8",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:174",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_u8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580461768,
      "name": "fetch_memory_u8",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:136",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_u8"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580430432,
      "name": "fetch_memory_u8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071580461376,
      "name": "fetch_memory_u8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void fetch_memory_u8(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_u8",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580487021,
      "name": "fetch_memory_u8",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:174",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_u8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580517752,
      "name": "fetch_memory_u8",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:136",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_u8"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580486864,
      "name": "fetch_memory_u8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071580517360,
      "name": "fetch_memory_u8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void fetch_memory_u8(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_u8",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580574349,
      "name": "fetch_memory_u8",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:198",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_u8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580606552,
      "name": "fetch_memory_u8",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:137",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_u8"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580574192,
      "name": "fetch_memory_u8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071580606128,
      "name": "fetch_memory_u8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void fetch_memory_u8(struct pt_regs * regs, void * addr, void * dest)
```
</details>
</li>
</ul>
