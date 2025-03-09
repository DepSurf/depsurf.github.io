# Function: <code>save_stack_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void save_stack_address(void * data, long unsigned int addr, int reliable)
```

```json
{
  "name": "save_stack_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579100656,
      "name": "save_stack_address",
      "external": false,
      "loc": "arch/x86/kernel/stacktrace.c:35",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100656,
      "name": "save_stack_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int save_stack_address(void * data, long unsigned int addr, int reliable)
```

```json
{
  "name": "save_stack_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579100224,
      "name": "save_stack_address",
      "external": false,
      "loc": "arch/x86/kernel/stacktrace.c:39",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100224,
      "name": "save_stack_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int save_stack_address(struct stack_trace * trace, long unsigned int addr, bool nosched)
```

```json
{
  "name": "save_stack_address",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579098096,
      "name": "save_stack_address",
      "external": false,
      "loc": "arch/x86/kernel/stacktrace.c:13",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/stacktrace.c:__save_stack_trace",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579098096,
      "name": "save_stack_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int save_stack_address(struct stack_trace * trace, long unsigned int addr, bool nosched)
```

```json
{
  "name": "save_stack_address",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579090048,
      "name": "save_stack_address",
      "external": false,
      "loc": "arch/x86/kernel/stacktrace.c:15",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/stacktrace.c:__save_stack_trace",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579090048,
      "name": "save_stack_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int save_stack_address(struct stack_trace * trace, long unsigned int addr, bool nosched)
```

```json
{
  "name": "save_stack_address",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579100832,
      "name": "save_stack_address",
      "external": false,
      "loc": "arch/x86/kernel/stacktrace.c:15",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100832,
      "name": "save_stack_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int save_stack_address(struct stack_trace * trace, long unsigned int addr, bool nosched)
```

```json
{
  "name": "save_stack_address",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579106400,
      "name": "save_stack_address",
      "external": false,
      "loc": "arch/x86/kernel/stacktrace.c:15",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579106400,
      "name": "save_stack_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int save_stack_address(struct stack_trace * trace, long unsigned int addr, bool nosched)
```

```json
{
  "name": "save_stack_address",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579112064,
      "name": "save_stack_address",
      "external": false,
      "loc": "arch/x86/kernel/stacktrace.c:15",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579112064,
      "name": "save_stack_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct stack_trace * trace</code>
</li>
<li>
<b>Param added. </b>
<code>bool nosched</code>
</li>
<li>
<b>Param removed. </b>
<code>void * data</code>
</li>
<li>
<b>Param removed. </b>
<code>int reliable</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int save_stack_address(struct stack_trace * trace, long unsigned int addr, bool nosched)
```
</details>
</li>
</ul>
