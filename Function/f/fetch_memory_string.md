# Function: <code>fetch_memory_string</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void fetch_memory_string(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_string",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580316688,
      "name": "fetch_memory_string",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:165",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_string"
      ]
    },
    {
      "addr": 18446744071580347888,
      "name": "fetch_memory_string",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:139",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580316688,
      "name": "fetch_memory_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071580347888,
      "name": "fetch_memory_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
void fetch_memory_string(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_string",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580371408,
      "name": "fetch_memory_string",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:165",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_string"
      ]
    },
    {
      "addr": 18446744071580402864,
      "name": "fetch_memory_string",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:139",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580371408,
      "name": "fetch_memory_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071580402864,
      "name": "fetch_memory_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
void fetch_memory_string(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_string",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580419152,
      "name": "fetch_memory_string",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:176",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_string"
      ]
    },
    {
      "addr": 18446744071580451008,
      "name": "fetch_memory_string",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:139",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580419152,
      "name": "fetch_memory_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071580451008,
      "name": "fetch_memory_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
void fetch_memory_string(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_string",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580431216,
      "name": "fetch_memory_string",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:179",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_string"
      ]
    },
    {
      "addr": 18446744071580462400,
      "name": "fetch_memory_string",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:141",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580431216,
      "name": "fetch_memory_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071580462400,
      "name": "fetch_memory_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
void fetch_memory_string(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_string",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580487648,
      "name": "fetch_memory_string",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:179",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_string"
      ]
    },
    {
      "addr": 18446744071580518384,
      "name": "fetch_memory_string",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:141",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580487648,
      "name": "fetch_memory_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071580518384,
      "name": "fetch_memory_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
void fetch_memory_string(struct pt_regs * regs, void * addr, void * dest)
```

```json
{
  "name": "fetch_memory_string",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580575008,
      "name": "fetch_memory_string",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:203",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:fetch_symbol_string"
      ]
    },
    {
      "addr": 18446744071580607104,
      "name": "fetch_memory_string",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:142",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:fetch_file_offset_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580575008,
      "name": "fetch_memory_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071580607104,
      "name": "fetch_memory_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void fetch_memory_string(struct pt_regs * regs, void * addr, void * dest)
```
</details>
</li>
</ul>
