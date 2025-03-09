# Function: <code>__compat_get_timespec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __compat_get_timespec(struct timespec * ts, const struct compat_timespec * cts)
```

```json
{
  "name": "__compat_get_timespec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579957136,
      "name": "__compat_get_timespec",
      "external": false,
      "loc": "kernel/compat.c:143",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:get_compat_itimerspec",
        "kernel/compat.c:get_compat_itimerspec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579957136,
      "name": "__compat_get_timespec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
int __compat_get_timespec(struct timespec * ts, const struct compat_timespec * cts)
```

```json
{
  "name": "__compat_get_timespec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579987728,
      "name": "__compat_get_timespec",
      "external": false,
      "loc": "kernel/compat.c:143",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:get_compat_itimerspec",
        "kernel/compat.c:get_compat_itimerspec",
        "kernel/compat.c:compat_get_timespec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579987728,
      "name": "__compat_get_timespec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __compat_get_timespec(struct timespec * ts, const struct compat_timespec * cts)
```

```json
{
  "name": "__compat_get_timespec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580018256,
      "name": "__compat_get_timespec",
      "external": false,
      "loc": "kernel/compat.c:143",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:get_compat_itimerspec",
        "kernel/compat.c:get_compat_itimerspec",
        "kernel/compat.c:compat_get_timespec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580018256,
      "name": "__compat_get_timespec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __compat_get_timespec(struct timespec * ts, const struct compat_timespec * cts)
```

```json
{
  "name": "__compat_get_timespec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580025536,
      "name": "__compat_get_timespec",
      "external": false,
      "loc": "kernel/compat.c:109",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:get_compat_itimerspec",
        "kernel/compat.c:get_compat_itimerspec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580025536,
      "name": "__compat_get_timespec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__compat_get_timespec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580073506,
      "name": "__compat_get_timespec",
      "external": false,
      "loc": "kernel/compat.c:109",
      "file": "kernel/compat.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__compat_get_timespec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580132837,
      "name": "__compat_get_timespec",
      "external": false,
      "loc": "kernel/compat.c:110",
      "file": "kernel/compat.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__compat_get_timespec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580180037,
      "name": "__compat_get_timespec",
      "external": false,
      "loc": "kernel/compat.c:110",
      "file": "kernel/compat.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__compat_get_timespec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580225929,
      "name": "__compat_get_timespec",
      "external": false,
      "loc": "kernel/compat.c:43",
      "file": "kernel/compat.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__compat_get_timespec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580274169,
      "name": "__compat_get_timespec",
      "external": false,
      "loc": "kernel/compat.c:43",
      "file": "kernel/compat.c",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__compat_get_timespec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491515444,
      "name": "__compat_get_timespec",
      "external": false,
      "loc": "kernel/compat.c:43",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/compat.c:compat_get_timespec"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__compat_get_timespec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284484496,
      "name": "__compat_get_timespec",
      "external": false,
      "loc": "kernel/compat.c:43",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/compat.c:compat_get_timespec"
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
  "name": "__compat_get_timespec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580242969,
      "name": "__compat_get_timespec",
      "external": false,
      "loc": "kernel/compat.c:43",
      "file": "kernel/compat.c",
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
  "name": "__compat_get_timespec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580190521,
      "name": "__compat_get_timespec",
      "external": false,
      "loc": "kernel/compat.c:43",
      "file": "kernel/compat.c",
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
  "name": "__compat_get_timespec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580234217,
      "name": "__compat_get_timespec",
      "external": false,
      "loc": "kernel/compat.c:43",
      "file": "kernel/compat.c",
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
  "name": "__compat_get_timespec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580287209,
      "name": "__compat_get_timespec",
      "external": false,
      "loc": "kernel/compat.c:43",
      "file": "kernel/compat.c",
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
int __compat_get_timespec(struct timespec * ts, const struct compat_timespec * cts)
```
</details>
</li>
</ul>
