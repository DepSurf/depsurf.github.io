# Function: <code>find_direct_entry</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ftrace_func_entry * find_direct_entry(long unsigned int * ip, struct dyn_ftrace * * recp)
```

```json
{
  "name": "find_direct_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580599760,
      "name": "find_direct_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5097",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:modify_ftrace_direct",
        "kernel/trace/ftrace.c:unregister_ftrace_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580599760,
      "name": "find_direct_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
struct ftrace_func_entry * find_direct_entry(long unsigned int * ip, struct dyn_ftrace * * recp)
```

```json
{
  "name": "find_direct_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580589792,
      "name": "find_direct_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5184",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:modify_ftrace_direct",
        "kernel/trace/ftrace.c:unregister_ftrace_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580589792,
      "name": "find_direct_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
struct ftrace_func_entry * find_direct_entry(long unsigned int * ip, struct dyn_ftrace * * recp)
```

```json
{
  "name": "find_direct_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580592800,
      "name": "find_direct_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5184",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:modify_ftrace_direct",
        "kernel/trace/ftrace.c:unregister_ftrace_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580592800,
      "name": "find_direct_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
struct ftrace_func_entry * find_direct_entry(long unsigned int * ip, struct dyn_ftrace * * recp)
```

```json
{
  "name": "find_direct_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_direct_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5184",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:modify_ftrace_direct",
        "kernel/trace/ftrace.c:unregister_ftrace_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580763920,
      "name": "find_direct_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071592165549,
      "name": "find_direct_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
struct ftrace_func_entry * find_direct_entry(long unsigned int * ip, struct dyn_ftrace * * recp)
```

```json
{
  "name": "find_direct_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_direct_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5331",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:modify_ftrace_direct",
        "kernel/trace/ftrace.c:unregister_ftrace_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980480,
      "name": "find_direct_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071593939008,
      "name": "find_direct_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
struct ftrace_func_entry * find_direct_entry(long unsigned int * ip, struct dyn_ftrace * * recp)
```

```json
{
  "name": "find_direct_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_direct_entry",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5354",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:modify_ftrace_direct",
        "kernel/trace/ftrace.c:unregister_ftrace_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581277088,
      "name": "find_direct_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071596002099,
      "name": "find_direct_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct ftrace_func_entry * find_direct_entry(long unsigned int * ip, struct dyn_ftrace * * recp)
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
struct ftrace_func_entry * find_direct_entry(long unsigned int * ip, struct dyn_ftrace * * recp)
```
</details>
</li>
</ul>
