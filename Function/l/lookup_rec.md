# Function: <code>lookup_rec</code>

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
struct dyn_ftrace * lookup_rec(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "lookup_rec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580599600,
      "name": "lookup_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1530",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:find_direct_entry",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:ftrace_text_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580599600,
      "name": "lookup_rec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct dyn_ftrace * lookup_rec(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "lookup_rec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580589632,
      "name": "lookup_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1529",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:find_direct_entry",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:ftrace_text_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580589632,
      "name": "lookup_rec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct dyn_ftrace * lookup_rec(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "lookup_rec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580592640,
      "name": "lookup_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1529",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:find_direct_entry",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:ftrace_text_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580592640,
      "name": "lookup_rec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct dyn_ftrace * lookup_rec(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "lookup_rec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580763760,
      "name": "lookup_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1530",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:find_direct_entry",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_set_hash",
        "kernel/trace/ftrace.c:ftrace_text_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580763760,
      "name": "lookup_rec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct dyn_ftrace * lookup_rec(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "lookup_rec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580980304,
      "name": "lookup_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1524",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:find_direct_entry",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_text_reserved",
        "kernel/trace/ftrace.c:ftrace_location",
        "kernel/trace/ftrace.c:ftrace_location"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980304,
      "name": "lookup_rec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
struct dyn_ftrace * lookup_rec(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "lookup_rec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581276896,
      "name": "lookup_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1530",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:find_direct_entry",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_text_reserved",
        "kernel/trace/ftrace.c:ftrace_location",
        "kernel/trace/ftrace.c:ftrace_location"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581276896,
      "name": "lookup_rec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
struct dyn_ftrace * lookup_rec(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "lookup_rec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581372160,
      "name": "lookup_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1561",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_text_reserved",
        "kernel/trace/ftrace.c:ftrace_location",
        "kernel/trace/ftrace.c:ftrace_location"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581372160,
      "name": "lookup_rec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
struct dyn_ftrace * lookup_rec(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "lookup_rec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581478960,
      "name": "lookup_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1560",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_text_reserved",
        "kernel/trace/ftrace.c:ftrace_location",
        "kernel/trace/ftrace.c:ftrace_location"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581478960,
      "name": "lookup_rec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
struct dyn_ftrace * lookup_rec(long unsigned int start, long unsigned int end)
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
