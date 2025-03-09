# Function: <code>trace_array_create_dir</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int trace_array_create_dir(struct trace_array * tr)
```

```json
{
  "name": "trace_array_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580666464,
      "name": "trace_array_create_dir",
      "external": false,
      "loc": "kernel/trace/trace.c:8676",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_array_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580666464,
      "name": "trace_array_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trace_array_create_dir(struct trace_array * tr)
```

```json
{
  "name": "trace_array_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580665168,
      "name": "trace_array_create_dir",
      "external": false,
      "loc": "kernel/trace/trace.c:9012",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:trace_array_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580665168,
      "name": "trace_array_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trace_array_create_dir(struct trace_array * tr)
```

```json
{
  "name": "trace_array_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580839856,
      "name": "trace_array_create_dir",
      "external": false,
      "loc": "kernel/trace/trace.c:9176",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracer_init_tracefs",
        "kernel/trace/trace.c:trace_array_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580839856,
      "name": "trace_array_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int trace_array_create_dir(struct trace_array * tr)
```

```json
{
  "name": "trace_array_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581069121,
      "name": "trace_array_create_dir",
      "external": false,
      "loc": "kernel/trace/trace.c:9209",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:trace_array_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069056,
      "name": "trace_array_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071593943693,
      "name": "trace_array_create_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int trace_array_create_dir(struct trace_array * tr)
```

```json
{
  "name": "trace_array_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581374817,
      "name": "trace_array_create_dir",
      "external": false,
      "loc": "kernel/trace/trace.c:9300",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:trace_array_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581374752,
      "name": "trace_array_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071596004641,
      "name": "trace_array_create_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int trace_array_create_dir(struct trace_array * tr)
```

```json
{
  "name": "trace_array_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581469425,
      "name": "trace_array_create_dir",
      "external": false,
      "loc": "kernel/trace/trace.c:9459",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:trace_array_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581469360,
      "name": "trace_array_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071596523226,
      "name": "trace_array_create_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int trace_array_create_dir(struct trace_array * tr)
```

```json
{
  "name": "trace_array_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581576417,
      "name": "trace_array_create_dir",
      "external": false,
      "loc": "kernel/trace/trace.c:9638",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracer_init_tracefs_work_func",
        "kernel/trace/trace.c:trace_array_create_systems"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581576352,
      "name": "trace_array_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071597423908,
      "name": "trace_array_create_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int trace_array_create_dir(struct trace_array * tr)
```
</details>
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
