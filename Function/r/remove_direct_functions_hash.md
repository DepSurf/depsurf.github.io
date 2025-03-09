# Function: <code>remove_direct_functions_hash</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void remove_direct_functions_hash(struct ftrace_hash * hash, long unsigned int addr)
```

```json
{
  "name": "remove_direct_functions_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remove_direct_functions_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5570",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:unregister_ftrace_direct_multi",
        "kernel/trace/ftrace.c:register_ftrace_direct_multi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580979296,
      "name": "remove_direct_functions_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071593938934,
      "name": "remove_direct_functions_hash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void remove_direct_functions_hash(struct ftrace_hash * hash, long unsigned int addr)
```

```json
{
  "name": "remove_direct_functions_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remove_direct_functions_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5596",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:unregister_ftrace_direct_multi",
        "kernel/trace/ftrace.c:register_ftrace_direct_multi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275792,
      "name": "remove_direct_functions_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071596002025,
      "name": "remove_direct_functions_hash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void remove_direct_functions_hash(struct ftrace_hash * hash, long unsigned int addr)
```

```json
{
  "name": "remove_direct_functions_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remove_direct_functions_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5372",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:unregister_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581371184,
      "name": "remove_direct_functions_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071596520586,
      "name": "remove_direct_functions_hash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "remove_direct_functions_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581502311,
      "name": "remove_direct_functions_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5349",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:unregister_ftrace_direct"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void remove_direct_functions_hash(struct ftrace_hash * hash, long unsigned int addr)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void remove_direct_functions_hash(struct ftrace_hash * hash, long unsigned int addr)
```
</details>
</li>
</ul>
