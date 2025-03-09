# Function: <code>stack_trace_consume_entry_nosched</code>

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
bool stack_trace_consume_entry_nosched(void * cookie, long unsigned int addr, bool reliable)
```

```json
{
  "name": "stack_trace_consume_entry_nosched",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580049040,
      "name": "stack_trace_consume_entry_nosched",
      "external": false,
      "loc": "kernel/stacktrace.c:97",
      "file": "kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580049040,
      "name": "stack_trace_consume_entry_nosched",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
bool stack_trace_consume_entry_nosched(void * cookie, long unsigned int addr, bool reliable)
```

```json
{
  "name": "stack_trace_consume_entry_nosched",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580098128,
      "name": "stack_trace_consume_entry_nosched",
      "external": false,
      "loc": "kernel/stacktrace.c:97",
      "file": "kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580098128,
      "name": "stack_trace_consume_entry_nosched",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool stack_trace_consume_entry_nosched(void * cookie, long unsigned int addr, bool reliable)
```

```json
{
  "name": "stack_trace_consume_entry_nosched",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580160640,
      "name": "stack_trace_consume_entry_nosched",
      "external": false,
      "loc": "kernel/stacktrace.c:97",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580160640,
      "name": "stack_trace_consume_entry_nosched",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
bool stack_trace_consume_entry_nosched(void * cookie, long unsigned int addr)
```

```json
{
  "name": "stack_trace_consume_entry_nosched",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580144928,
      "name": "stack_trace_consume_entry_nosched",
      "external": false,
      "loc": "kernel/stacktrace.c:96",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580144928,
      "name": "stack_trace_consume_entry_nosched",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
bool stack_trace_consume_entry_nosched(void * cookie, long unsigned int addr)
```

```json
{
  "name": "stack_trace_consume_entry_nosched",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580149616,
      "name": "stack_trace_consume_entry_nosched",
      "external": false,
      "loc": "kernel/stacktrace.c:96",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149616,
      "name": "stack_trace_consume_entry_nosched",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
bool stack_trace_consume_entry_nosched(void * cookie, long unsigned int addr)
```

```json
{
  "name": "stack_trace_consume_entry_nosched",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580294144,
      "name": "stack_trace_consume_entry_nosched",
      "external": false,
      "loc": "kernel/stacktrace.c:96",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580294144,
      "name": "stack_trace_consume_entry_nosched",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
bool stack_trace_consume_entry_nosched(void * cookie, long unsigned int addr)
```

```json
{
  "name": "stack_trace_consume_entry_nosched",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580502768,
      "name": "stack_trace_consume_entry_nosched",
      "external": false,
      "loc": "kernel/stacktrace.c:97",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580502768,
      "name": "stack_trace_consume_entry_nosched",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
bool stack_trace_consume_entry_nosched(void * cookie, long unsigned int addr)
```

```json
{
  "name": "stack_trace_consume_entry_nosched",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580755904,
      "name": "stack_trace_consume_entry_nosched",
      "external": false,
      "loc": "kernel/stacktrace.c:97",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580755904,
      "name": "stack_trace_consume_entry_nosched",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
bool stack_trace_consume_entry_nosched(void * cookie, long unsigned int addr)
```

```json
{
  "name": "stack_trace_consume_entry_nosched",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580838576,
      "name": "stack_trace_consume_entry_nosched",
      "external": false,
      "loc": "kernel/stacktrace.c:97",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580838576,
      "name": "stack_trace_consume_entry_nosched",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
bool stack_trace_consume_entry_nosched(void * cookie, long unsigned int addr)
```

```json
{
  "name": "stack_trace_consume_entry_nosched",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580928224,
      "name": "stack_trace_consume_entry_nosched",
      "external": false,
      "loc": "kernel/stacktrace.c:97",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928224,
      "name": "stack_trace_consume_entry_nosched",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
bool stack_trace_consume_entry_nosched(void * cookie, long unsigned int addr, bool reliable)
```

```json
{
  "name": "stack_trace_consume_entry_nosched",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580067328,
      "name": "stack_trace_consume_entry_nosched",
      "external": false,
      "loc": "kernel/stacktrace.c:97",
      "file": "kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067328,
      "name": "stack_trace_consume_entry_nosched",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
bool stack_trace_consume_entry_nosched(void * cookie, long unsigned int addr, bool reliable)
```

```json
{
  "name": "stack_trace_consume_entry_nosched",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580012144,
      "name": "stack_trace_consume_entry_nosched",
      "external": false,
      "loc": "kernel/stacktrace.c:97",
      "file": "kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012144,
      "name": "stack_trace_consume_entry_nosched",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
bool stack_trace_consume_entry_nosched(void * cookie, long unsigned int addr, bool reliable)
```

```json
{
  "name": "stack_trace_consume_entry_nosched",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580058400,
      "name": "stack_trace_consume_entry_nosched",
      "external": false,
      "loc": "kernel/stacktrace.c:97",
      "file": "kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580058400,
      "name": "stack_trace_consume_entry_nosched",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
bool stack_trace_consume_entry_nosched(void * cookie, long unsigned int addr, bool reliable)
```

```json
{
  "name": "stack_trace_consume_entry_nosched",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580109232,
      "name": "stack_trace_consume_entry_nosched",
      "external": false,
      "loc": "kernel/stacktrace.c:97",
      "file": "kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580109232,
      "name": "stack_trace_consume_entry_nosched",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
bool stack_trace_consume_entry_nosched(void * cookie, long unsigned int addr, bool reliable)
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
bool stack_trace_consume_entry_nosched(void * cookie, long unsigned int addr, bool reliable)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool stack_trace_consume_entry_nosched(void * cookie, long unsigned int addr, bool reliable)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool stack_trace_consume_entry_nosched(void * cookie, long unsigned int addr, bool reliable)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool stack_trace_consume_entry_nosched(void * cookie, long unsigned int addr, bool reliable)
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
