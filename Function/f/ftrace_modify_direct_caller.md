# Function: <code>ftrace_modify_direct_caller</code>

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
int ftrace_modify_direct_caller(struct ftrace_func_entry * entry, struct dyn_ftrace * rec, long unsigned int old_addr, long unsigned int new_addr)
```

```json
{
  "name": "ftrace_modify_direct_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580628848,
      "name": "ftrace_modify_direct_caller",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5187",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:modify_ftrace_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580628848,
      "name": "ftrace_modify_direct_caller",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 340
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
int ftrace_modify_direct_caller(struct ftrace_func_entry * entry, struct dyn_ftrace * rec, long unsigned int old_addr, long unsigned int new_addr)
```

```json
{
  "name": "ftrace_modify_direct_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580619584,
      "name": "ftrace_modify_direct_caller",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5274",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:modify_ftrace_direct",
        "kernel/trace/ftrace.c:modify_ftrace_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580619584,
      "name": "ftrace_modify_direct_caller",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 340
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
int ftrace_modify_direct_caller(struct ftrace_func_entry * entry, struct dyn_ftrace * rec, long unsigned int old_addr, long unsigned int new_addr)
```

```json
{
  "name": "ftrace_modify_direct_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580622464,
      "name": "ftrace_modify_direct_caller",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5274",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:modify_ftrace_direct",
        "kernel/trace/ftrace.c:modify_ftrace_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580622464,
      "name": "ftrace_modify_direct_caller",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 340
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
int ftrace_modify_direct_caller(struct ftrace_func_entry * entry, struct dyn_ftrace * rec, long unsigned int old_addr, long unsigned int new_addr)
```

```json
{
  "name": "ftrace_modify_direct_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580794288,
      "name": "ftrace_modify_direct_caller",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5274",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:modify_ftrace_direct",
        "kernel/trace/ftrace.c:modify_ftrace_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580794288,
      "name": "ftrace_modify_direct_caller",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 340
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
int ftrace_modify_direct_caller(struct ftrace_func_entry * entry, struct dyn_ftrace * rec, long unsigned int old_addr, long unsigned int new_addr)
```

```json
{
  "name": "ftrace_modify_direct_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581015360,
      "name": "ftrace_modify_direct_caller",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5427",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:modify_ftrace_direct",
        "kernel/trace/ftrace.c:modify_ftrace_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581015360,
      "name": "ftrace_modify_direct_caller",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 342
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
int ftrace_modify_direct_caller(struct ftrace_func_entry * entry, struct dyn_ftrace * rec, long unsigned int old_addr, long unsigned int new_addr)
```

```json
{
  "name": "ftrace_modify_direct_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581316224,
      "name": "ftrace_modify_direct_caller",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5452",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:modify_ftrace_direct",
        "kernel/trace/ftrace.c:modify_ftrace_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581316224,
      "name": "ftrace_modify_direct_caller",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 287
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
int ftrace_modify_direct_caller(struct ftrace_func_entry * entry, struct dyn_ftrace * rec, long unsigned int old_addr, long unsigned int new_addr)
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
int ftrace_modify_direct_caller(struct ftrace_func_entry * entry, struct dyn_ftrace * rec, long unsigned int old_addr, long unsigned int new_addr)
```
</details>
</li>
</ul>
