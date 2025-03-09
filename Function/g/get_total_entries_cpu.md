# Function: <code>get_total_entries_cpu</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_total_entries_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580522624,
      "name": "get_total_entries_cpu",
      "external": false,
      "loc": "kernel/trace/trace.c:3494",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_total_entries_cpu",
        "kernel/trace/trace.c:get_total_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580522624,
      "name": "get_total_entries_cpu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_total_entries_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580569984,
      "name": "get_total_entries_cpu",
      "external": false,
      "loc": "kernel/trace/trace.c:3520",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_total_entries_cpu",
        "kernel/trace/trace.c:get_total_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580569984,
      "name": "get_total_entries_cpu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void get_total_entries_cpu(struct array_buffer * buf, long unsigned int * total, long unsigned int * entries, int cpu)
```

```json
{
  "name": "get_total_entries_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580689917,
      "name": "get_total_entries_cpu",
      "external": false,
      "loc": "kernel/trace/trace.c:3684",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_total_entries_cpu"
      ],
      "caller_func": [
        "kernel/trace/trace.c:get_total_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580655408,
      "name": "get_total_entries_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void get_total_entries_cpu(struct array_buffer * buf, long unsigned int * total, long unsigned int * entries, int cpu)
```

```json
{
  "name": "get_total_entries_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580680717,
      "name": "get_total_entries_cpu",
      "external": false,
      "loc": "kernel/trace/trace.c:3752",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_total_entries_cpu"
      ],
      "caller_func": [
        "kernel/trace/trace.c:get_total_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580646144,
      "name": "get_total_entries_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void get_total_entries_cpu(struct array_buffer * buf, long unsigned int * total, long unsigned int * entries, int cpu)
```

```json
{
  "name": "get_total_entries_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580684045,
      "name": "get_total_entries_cpu",
      "external": false,
      "loc": "kernel/trace/trace.c:4079",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_total_entries_cpu"
      ],
      "caller_func": [
        "kernel/trace/trace.c:get_total_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580649040,
      "name": "get_total_entries_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void get_total_entries_cpu(struct array_buffer * buf, long unsigned int * total, long unsigned int * entries, int cpu)
```

```json
{
  "name": "get_total_entries_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580858853,
      "name": "get_total_entries_cpu",
      "external": false,
      "loc": "kernel/trace/trace.c:4151",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_total_entries_cpu"
      ],
      "caller_func": [
        "kernel/trace/trace.c:get_total_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580822304,
      "name": "get_total_entries_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void get_total_entries_cpu(struct array_buffer * buf, long unsigned int * total, long unsigned int * entries, int cpu)
```

```json
{
  "name": "get_total_entries_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581088389,
      "name": "get_total_entries_cpu",
      "external": false,
      "loc": "kernel/trace/trace.c:4154",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_total_entries_cpu"
      ],
      "caller_func": [
        "kernel/trace/trace.c:get_total_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581047392,
      "name": "get_total_entries_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void get_total_entries_cpu(struct array_buffer * buf, long unsigned int * total, long unsigned int * entries, int cpu)
```

```json
{
  "name": "get_total_entries_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581395829,
      "name": "get_total_entries_cpu",
      "external": false,
      "loc": "kernel/trace/trace.c:4178",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_total_entries_cpu"
      ],
      "caller_func": [
        "kernel/trace/trace.c:get_total_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581349808,
      "name": "get_total_entries_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void get_total_entries_cpu(struct array_buffer * buf, long unsigned int * total, long unsigned int * entries, int cpu)
```

```json
{
  "name": "get_total_entries_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581490645,
      "name": "get_total_entries_cpu",
      "external": false,
      "loc": "kernel/trace/trace.c:4279",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_total_entries_cpu"
      ],
      "caller_func": [
        "kernel/trace/trace.c:get_total_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581444368,
      "name": "get_total_entries_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void get_total_entries_cpu(struct array_buffer * buf, long unsigned int * total, long unsigned int * entries, int cpu)
```

```json
{
  "name": "get_total_entries_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581601509,
      "name": "get_total_entries_cpu",
      "external": false,
      "loc": "kernel/trace/trace.c:4241",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_total_entries_cpu"
      ],
      "caller_func": [
        "kernel/trace/trace.c:get_total_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581553824,
      "name": "get_total_entries_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
  "name": "get_total_entries_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491860680,
      "name": "get_total_entries_cpu",
      "external": false,
      "loc": "kernel/trace/trace.c:3520",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_total_entries_cpu",
        "kernel/trace/trace.c:get_total_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491860680,
      "name": "get_total_entries_cpu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void get_total_entries_cpu(struct trace_buffer * buf, long unsigned int * total, long unsigned int * entries, int cpu)
```

```json
{
  "name": "get_total_entries_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225799464,
      "name": "get_total_entries_cpu",
      "external": false,
      "loc": "kernel/trace/trace.c:3520",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_total_entries_cpu",
        "kernel/trace/trace.c:get_total_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225799464,
      "name": "get_total_entries_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "get_total_entries_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284932928,
      "name": "get_total_entries_cpu",
      "external": false,
      "loc": "kernel/trace/trace.c:3520",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_total_entries_cpu",
        "kernel/trace/trace.c:get_total_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284932928,
      "name": "get_total_entries_cpu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "get_total_entries_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272157870,
      "name": "get_total_entries_cpu",
      "external": false,
      "loc": "kernel/trace/trace.c:3520",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_total_entries_cpu",
        "kernel/trace/trace.c:get_total_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272157870,
      "name": "get_total_entries_cpu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_total_entries_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580538784,
      "name": "get_total_entries_cpu",
      "external": false,
      "loc": "kernel/trace/trace.c:3520",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_total_entries_cpu",
        "kernel/trace/trace.c:get_total_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580538784,
      "name": "get_total_entries_cpu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_total_entries_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580485632,
      "name": "get_total_entries_cpu",
      "external": false,
      "loc": "kernel/trace/trace.c:3520",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_total_entries_cpu",
        "kernel/trace/trace.c:get_total_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580485632,
      "name": "get_total_entries_cpu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_total_entries_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580530032,
      "name": "get_total_entries_cpu",
      "external": false,
      "loc": "kernel/trace/trace.c:3520",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_total_entries_cpu",
        "kernel/trace/trace.c:get_total_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580530032,
      "name": "get_total_entries_cpu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_total_entries_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580586512,
      "name": "get_total_entries_cpu",
      "external": false,
      "loc": "kernel/trace/trace.c:3520",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_total_entries_cpu",
        "kernel/trace/trace.c:get_total_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580586512,
      "name": "get_total_entries_cpu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void get_total_entries_cpu(struct array_buffer * buf, long unsigned int * total, long unsigned int * entries, int cpu)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void get_total_entries_cpu(struct trace_buffer * buf, long unsigned int * total, long unsigned int * entries, int cpu)
```
</details>
</li>
</ul>
