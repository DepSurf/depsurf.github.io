# Function: <code>process_cached_mods</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "process_cached_mods",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580264609,
      "name": "process_cached_mods",
      "external": false,
      "loc": "kernel/trace/ftrace.c:4070",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_module_enable"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "process_cached_mods",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580316714,
      "name": "process_cached_mods",
      "external": false,
      "loc": "kernel/trace/ftrace.c:4038",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_module_enable"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "process_cached_mods",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580377388,
      "name": "process_cached_mods",
      "external": false,
      "loc": "kernel/trace/ftrace.c:4026",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_module_enable"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "process_cached_mods",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580433772,
      "name": "process_cached_mods",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3985",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_module_enable"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "process_cached_mods",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580486353,
      "name": "process_cached_mods",
      "external": false,
      "loc": "kernel/trace/ftrace.c:4021",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_module_enable"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "process_cached_mods",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580535505,
      "name": "process_cached_mods",
      "external": false,
      "loc": "kernel/trace/ftrace.c:4045",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_module_enable"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void process_cached_mods(const char * mod_name)
```

```json
{
  "name": "process_cached_mods",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580622304,
      "name": "process_cached_mods",
      "external": false,
      "loc": "kernel/trace/ftrace.c:4172",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_module_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580622304,
      "name": "process_cached_mods",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
void process_cached_mods(const char * mod_name)
```

```json
{
  "name": "process_cached_mods",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580612688,
      "name": "process_cached_mods",
      "external": false,
      "loc": "kernel/trace/ftrace.c:4249",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_module_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580612688,
      "name": "process_cached_mods",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "process_cached_mods",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580618795,
      "name": "process_cached_mods",
      "external": false,
      "loc": "kernel/trace/ftrace.c:4249",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_module_enable"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "process_cached_mods",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580790459,
      "name": "process_cached_mods",
      "external": false,
      "loc": "kernel/trace/ftrace.c:4249",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_module_enable"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "process_cached_mods",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581011537,
      "name": "process_cached_mods",
      "external": false,
      "loc": "kernel/trace/ftrace.c:4389",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_module_enable"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "process_cached_mods",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581311737,
      "name": "process_cached_mods",
      "external": false,
      "loc": "kernel/trace/ftrace.c:4410",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_module_enable"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "process_cached_mods",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581407075,
      "name": "process_cached_mods",
      "external": false,
      "loc": "kernel/trace/ftrace.c:4565",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_module_enable"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "process_cached_mods",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581514687,
      "name": "process_cached_mods",
      "external": false,
      "loc": "kernel/trace/ftrace.c:4531",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_module_enable"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "process_cached_mods",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491817244,
      "name": "process_cached_mods",
      "external": false,
      "loc": "kernel/trace/ftrace.c:4045",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_module_enable"
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
  "name": "process_cached_mods",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225765500,
      "name": "process_cached_mods",
      "external": false,
      "loc": "kernel/trace/ftrace.c:4045",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_module_enable"
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
  "name": "process_cached_mods",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284880148,
      "name": "process_cached_mods",
      "external": false,
      "loc": "kernel/trace/ftrace.c:4045",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_module_enable"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "process_cached_mods",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272127530,
      "name": "process_cached_mods",
      "external": false,
      "loc": "kernel/trace/ftrace.c:4045",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_module_enable"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "process_cached_mods",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580504305,
      "name": "process_cached_mods",
      "external": false,
      "loc": "kernel/trace/ftrace.c:4045",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_module_enable"
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
  "name": "process_cached_mods",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580451329,
      "name": "process_cached_mods",
      "external": false,
      "loc": "kernel/trace/ftrace.c:4045",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_module_enable"
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
  "name": "process_cached_mods",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580495553,
      "name": "process_cached_mods",
      "external": false,
      "loc": "kernel/trace/ftrace.c:4045",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_module_enable"
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
  "name": "process_cached_mods",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580551761,
      "name": "process_cached_mods",
      "external": false,
      "loc": "kernel/trace/ftrace.c:4045",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_module_enable"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void process_cached_mods(const char * mod_name)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void process_cached_mods(const char * mod_name)
```
</details>
</li>
</ul>
