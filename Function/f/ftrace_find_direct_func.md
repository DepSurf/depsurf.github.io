# Function: <code>ftrace_find_direct_func</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ftrace_direct_func * ftrace_find_direct_func(long unsigned int addr)
```

```json
{
  "name": "ftrace_find_direct_func",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580621356,
      "name": "ftrace_find_direct_func",
      "external": true,
      "loc": "kernel/trace/ftrace.c:4953",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:unregister_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580624928,
      "name": "ftrace_find_direct_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct ftrace_direct_func * ftrace_find_direct_func(long unsigned int addr)
```

```json
{
  "name": "ftrace_find_direct_func",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580620037,
      "name": "ftrace_find_direct_func",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5030",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:modify_ftrace_direct",
        "kernel/trace/ftrace.c:unregister_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580615312,
      "name": "ftrace_find_direct_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct ftrace_direct_func * ftrace_find_direct_func(long unsigned int addr)
```

```json
{
  "name": "ftrace_find_direct_func",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580622917,
      "name": "ftrace_find_direct_func",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5030",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:modify_ftrace_direct",
        "kernel/trace/ftrace.c:unregister_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580617632,
      "name": "ftrace_find_direct_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct ftrace_direct_func * ftrace_find_direct_func(long unsigned int addr)
```

```json
{
  "name": "ftrace_find_direct_func",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580794741,
      "name": "ftrace_find_direct_func",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5030",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:modify_ftrace_direct",
        "kernel/trace/ftrace.c:unregister_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580789280,
      "name": "ftrace_find_direct_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct ftrace_direct_func * ftrace_find_direct_func(long unsigned int addr)
```

```json
{
  "name": "ftrace_find_direct_func",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581015843,
      "name": "ftrace_find_direct_func",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5196",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:modify_ftrace_direct",
        "kernel/trace/ftrace.c:unregister_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581010208,
      "name": "ftrace_find_direct_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct ftrace_direct_func * ftrace_find_direct_func(long unsigned int addr)
```

```json
{
  "name": "ftrace_find_direct_func",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581316659,
      "name": "ftrace_find_direct_func",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5217",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:modify_ftrace_direct",
        "kernel/trace/ftrace.c:unregister_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581310336,
      "name": "ftrace_find_direct_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct ftrace_direct_func * ftrace_find_direct_func(long unsigned int addr)
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
struct ftrace_direct_func * ftrace_find_direct_func(long unsigned int addr)
```
</details>
</li>
</ul>
