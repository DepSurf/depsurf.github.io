# Function: <code>stack_trace_consume_entry</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool stack_trace_consume_entry(void * cookie, long unsigned int addr, bool reliable)
```

```json
{
  "name": "stack_trace_consume_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580048624,
      "name": "stack_trace_consume_entry",
      "external": false,
      "loc": "kernel/stacktrace.c:81",
      "file": "kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048624,
      "name": "stack_trace_consume_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool stack_trace_consume_entry(void * cookie, long unsigned int addr, bool reliable)
```

```json
{
  "name": "stack_trace_consume_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580097728,
      "name": "stack_trace_consume_entry",
      "external": false,
      "loc": "kernel/stacktrace.c:81",
      "file": "kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097728,
      "name": "stack_trace_consume_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
bool stack_trace_consume_entry(void * cookie, long unsigned int addr, bool reliable)
```

```json
{
  "name": "stack_trace_consume_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580160684,
      "name": "stack_trace_consume_entry",
      "external": false,
      "loc": "kernel/stacktrace.c:81",
      "file": "kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/stacktrace.c:stack_trace_consume_entry_nosched"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580160224,
      "name": "stack_trace_consume_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
bool stack_trace_consume_entry(void * cookie, long unsigned int addr)
```

```json
{
  "name": "stack_trace_consume_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580144972,
      "name": "stack_trace_consume_entry",
      "external": false,
      "loc": "kernel/stacktrace.c:81",
      "file": "kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/stacktrace.c:stack_trace_consume_entry_nosched"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580144512,
      "name": "stack_trace_consume_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
bool stack_trace_consume_entry(void * cookie, long unsigned int addr)
```

```json
{
  "name": "stack_trace_consume_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580149660,
      "name": "stack_trace_consume_entry",
      "external": false,
      "loc": "kernel/stacktrace.c:81",
      "file": "kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/stacktrace.c:stack_trace_consume_entry_nosched"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149200,
      "name": "stack_trace_consume_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
bool stack_trace_consume_entry(void * cookie, long unsigned int addr)
```

```json
{
  "name": "stack_trace_consume_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580294188,
      "name": "stack_trace_consume_entry",
      "external": false,
      "loc": "kernel/stacktrace.c:81",
      "file": "kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/stacktrace.c:stack_trace_consume_entry_nosched"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293728,
      "name": "stack_trace_consume_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
bool stack_trace_consume_entry(void * cookie, long unsigned int addr)
```

```json
{
  "name": "stack_trace_consume_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580502820,
      "name": "stack_trace_consume_entry",
      "external": false,
      "loc": "kernel/stacktrace.c:82",
      "file": "kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/stacktrace.c:stack_trace_consume_entry_nosched"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580502160,
      "name": "stack_trace_consume_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
bool stack_trace_consume_entry(void * cookie, long unsigned int addr)
```

```json
{
  "name": "stack_trace_consume_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580755956,
      "name": "stack_trace_consume_entry",
      "external": false,
      "loc": "kernel/stacktrace.c:82",
      "file": "kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/stacktrace.c:stack_trace_consume_entry_nosched"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580755152,
      "name": "stack_trace_consume_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
bool stack_trace_consume_entry(void * cookie, long unsigned int addr)
```

```json
{
  "name": "stack_trace_consume_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580838628,
      "name": "stack_trace_consume_entry",
      "external": false,
      "loc": "kernel/stacktrace.c:82",
      "file": "kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/stacktrace.c:stack_trace_consume_entry_nosched"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580837824,
      "name": "stack_trace_consume_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
bool stack_trace_consume_entry(void * cookie, long unsigned int addr)
```

```json
{
  "name": "stack_trace_consume_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580928276,
      "name": "stack_trace_consume_entry",
      "external": false,
      "loc": "kernel/stacktrace.c:82",
      "file": "kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/stacktrace.c:stack_trace_consume_entry_nosched"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580927248,
      "name": "stack_trace_consume_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool stack_trace_consume_entry(void * cookie, long unsigned int addr, bool reliable)
```

```json
{
  "name": "stack_trace_consume_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580066928,
      "name": "stack_trace_consume_entry",
      "external": false,
      "loc": "kernel/stacktrace.c:81",
      "file": "kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580066928,
      "name": "stack_trace_consume_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool stack_trace_consume_entry(void * cookie, long unsigned int addr, bool reliable)
```

```json
{
  "name": "stack_trace_consume_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580011744,
      "name": "stack_trace_consume_entry",
      "external": false,
      "loc": "kernel/stacktrace.c:81",
      "file": "kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580011744,
      "name": "stack_trace_consume_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool stack_trace_consume_entry(void * cookie, long unsigned int addr, bool reliable)
```

```json
{
  "name": "stack_trace_consume_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580058000,
      "name": "stack_trace_consume_entry",
      "external": false,
      "loc": "kernel/stacktrace.c:81",
      "file": "kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580058000,
      "name": "stack_trace_consume_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool stack_trace_consume_entry(void * cookie, long unsigned int addr, bool reliable)
```

```json
{
  "name": "stack_trace_consume_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580108832,
      "name": "stack_trace_consume_entry",
      "external": false,
      "loc": "kernel/stacktrace.c:81",
      "file": "kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580108832,
      "name": "stack_trace_consume_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
bool stack_trace_consume_entry(void * cookie, long unsigned int addr, bool reliable)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool reliable</code>
</li>
</ul>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
bool stack_trace_consume_entry(void * cookie, long unsigned int addr, bool reliable)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool stack_trace_consume_entry(void * cookie, long unsigned int addr, bool reliable)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool stack_trace_consume_entry(void * cookie, long unsigned int addr, bool reliable)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool stack_trace_consume_entry(void * cookie, long unsigned int addr, bool reliable)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
