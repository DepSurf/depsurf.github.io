# Function: <code>append_trace_uprobe</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "append_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580784806,
      "name": "append_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:438",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "append_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580900884,
      "name": "append_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:438",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:register_trace_uprobe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "append_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580895140,
      "name": "append_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:438",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:register_trace_uprobe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int append_trace_uprobe(struct trace_uprobe * tu, struct trace_uprobe * to)
```

```json
{
  "name": "append_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580897952,
      "name": "append_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:438",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:register_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580897952,
      "name": "append_trace_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int append_trace_uprobe(struct trace_uprobe * tu, struct trace_uprobe * to)
```

```json
{
  "name": "append_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581102992,
      "name": "append_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:439",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:register_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581102992,
      "name": "append_trace_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
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
int append_trace_uprobe(struct trace_uprobe * tu, struct trace_uprobe * to)
```

```json
{
  "name": "append_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581363680,
      "name": "append_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:438",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:register_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581363680,
      "name": "append_trace_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int append_trace_uprobe(struct trace_uprobe * tu, struct trace_uprobe * to)
```

```json
{
  "name": "append_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581699776,
      "name": "append_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:440",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:register_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581699776,
      "name": "append_trace_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int append_trace_uprobe(struct trace_uprobe * tu, struct trace_uprobe * to)
```

```json
{
  "name": "append_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581844768,
      "name": "append_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:438",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:register_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581844768,
      "name": "append_trace_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
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
int append_trace_uprobe(struct trace_uprobe * tu, struct trace_uprobe * to)
```

```json
{
  "name": "append_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581967872,
      "name": "append_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:433",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:register_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581967872,
      "name": "append_trace_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "append_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492094008,
      "name": "append_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:438",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "append_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225996552,
      "name": "append_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:438",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "append_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285296372,
      "name": "append_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:438",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "append_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580753606,
      "name": "append_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:438",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "append_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580699798,
      "name": "append_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:438",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "append_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580744854,
      "name": "append_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:438",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "append_trace_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580802870,
      "name": "append_trace_uprobe",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:438",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int append_trace_uprobe(struct trace_uprobe * tu, struct trace_uprobe * to)
```
</details>
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
