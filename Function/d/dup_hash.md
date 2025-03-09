# Function: <code>dup_hash</code>

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
struct ftrace_hash * dup_hash(struct ftrace_hash * src, int size)
```

```json
{
  "name": "dup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580605648,
      "name": "dup_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1361",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580605648,
      "name": "dup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
struct ftrace_hash * dup_hash(struct ftrace_hash * src, int size)
```

```json
{
  "name": "dup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580595680,
      "name": "dup_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1360",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580595680,
      "name": "dup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
struct ftrace_hash * dup_hash(struct ftrace_hash * src, int size)
```

```json
{
  "name": "dup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580598384,
      "name": "dup_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1360",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580598384,
      "name": "dup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
struct ftrace_hash * dup_hash(struct ftrace_hash * src, int size)
```

```json
{
  "name": "dup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dup_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1361",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580769568,
      "name": "dup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    },
    {
      "addr": 18446744071592166129,
      "name": "dup_hash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
struct ftrace_hash * dup_hash(struct ftrace_hash * src, int size)
```

```json
{
  "name": "dup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dup_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1355",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_add_rec_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580987168,
      "name": "dup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071593939650,
      "name": "dup_hash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
struct ftrace_hash * dup_hash(struct ftrace_hash * src, int size)
```

```json
{
  "name": "dup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dup_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1361",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops",
        "kernel/trace/ftrace.c:ftrace_add_rec_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581284448,
      "name": "dup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071596002458,
      "name": "dup_hash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
struct ftrace_hash * dup_hash(struct ftrace_hash * src, int size)
```

```json
{
  "name": "dup_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dup_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1392",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379712,
      "name": "dup_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071596520921,
      "name": "dup_hash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
  "name": "dup_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581487113,
      "name": "dup_hash",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1391",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:__ftrace_hash_move"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct ftrace_hash * dup_hash(struct ftrace_hash * src, int size)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct ftrace_hash * dup_hash(struct ftrace_hash * src, int size)
```
</details>
</li>
</ul>
