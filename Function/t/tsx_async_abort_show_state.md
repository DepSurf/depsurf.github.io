# Function: <code>tsx_async_abort_show_state</code>

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
  "name": "tsx_async_abort_show_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579139630,
      "name": "tsx_async_abort_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1477",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
ssize_t tsx_async_abort_show_state(char * buf)
```

```json
{
  "name": "tsx_async_abort_show_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579154880,
      "name": "tsx_async_abort_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1599",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579154880,
      "name": "tsx_async_abort_show_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
ssize_t tsx_async_abort_show_state(char * buf)
```

```json
{
  "name": "tsx_async_abort_show_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579152128,
      "name": "tsx_async_abort_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1607",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579152128,
      "name": "tsx_async_abort_show_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
ssize_t tsx_async_abort_show_state(char * buf)
```

```json
{
  "name": "tsx_async_abort_show_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579158496,
      "name": "tsx_async_abort_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1607",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579158496,
      "name": "tsx_async_abort_show_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
ssize_t tsx_async_abort_show_state(char * buf)
```

```json
{
  "name": "tsx_async_abort_show_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579188160,
      "name": "tsx_async_abort_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1762",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579188160,
      "name": "tsx_async_abort_show_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
ssize_t tsx_async_abort_show_state(char * buf)
```

```json
{
  "name": "tsx_async_abort_show_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579236064,
      "name": "tsx_async_abort_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:2264",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236064,
      "name": "tsx_async_abort_show_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
ssize_t tsx_async_abort_show_state(char * buf)
```

```json
{
  "name": "tsx_async_abort_show_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579295344,
      "name": "tsx_async_abort_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:2315",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579295344,
      "name": "tsx_async_abort_show_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
ssize_t tsx_async_abort_show_state(char * buf)
```

```json
{
  "name": "tsx_async_abort_show_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579301776,
      "name": "tsx_async_abort_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:2590",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579301776,
      "name": "tsx_async_abort_show_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
ssize_t tsx_async_abort_show_state(char * buf)
```

```json
{
  "name": "tsx_async_abort_show_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579331408,
      "name": "tsx_async_abort_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:2728",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579331408,
      "name": "tsx_async_abort_show_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tsx_async_abort_show_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579139998,
      "name": "tsx_async_abort_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1477",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "tsx_async_abort_show_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579071150,
      "name": "tsx_async_abort_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1477",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "tsx_async_abort_show_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579139550,
      "name": "tsx_async_abort_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1477",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "tsx_async_abort_show_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579144686,
      "name": "tsx_async_abort_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1477",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
ssize_t tsx_async_abort_show_state(char * buf)
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
