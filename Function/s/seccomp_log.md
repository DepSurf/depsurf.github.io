# Function: <code>seccomp_log</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void seccomp_log(long unsigned int syscall, long int signr, u32 action, bool requested)
```

```json
{
  "name": "seccomp_log",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580224067,
      "name": "seccomp_log",
      "external": false,
      "loc": "kernel/seccomp.c:543",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": [
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580219728,
      "name": "seccomp_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
  "name": "seccomp_log",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580275257,
      "name": "seccomp_log",
      "external": false,
      "loc": "kernel/seccomp.c:558",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
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
  "name": "seccomp_log",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580336342,
      "name": "seccomp_log",
      "external": false,
      "loc": "kernel/seccomp.c:567",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
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
  "name": "seccomp_log",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580392182,
      "name": "seccomp_log",
      "external": false,
      "loc": "kernel/seccomp.c:629",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
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
  "name": "seccomp_log",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580444903,
      "name": "seccomp_log",
      "external": false,
      "loc": "kernel/seccomp.c:634",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
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
  "name": "seccomp_log",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580493927,
      "name": "seccomp_log",
      "external": false,
      "loc": "kernel/seccomp.c:635",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
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
  "name": "seccomp_log",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580579495,
      "name": "seccomp_log",
      "external": false,
      "loc": "kernel/seccomp.c:645",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
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
  "name": "seccomp_log",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580569176,
      "name": "seccomp_log",
      "external": false,
      "loc": "kernel/seccomp.c:964",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_log",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580572344,
      "name": "seccomp_log",
      "external": false,
      "loc": "kernel/seccomp.c:969",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
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
  "name": "seccomp_log",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580742187,
      "name": "seccomp_log",
      "external": false,
      "loc": "kernel/seccomp.c:948",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
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
  "name": "seccomp_log",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580955554,
      "name": "seccomp_log",
      "external": false,
      "loc": "kernel/seccomp.c:954",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
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
  "name": "seccomp_log",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581250146,
      "name": "seccomp_log",
      "external": false,
      "loc": "kernel/seccomp.c:954",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
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
  "name": "seccomp_log",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581345152,
      "name": "seccomp_log",
      "external": false,
      "loc": "kernel/seccomp.c:954",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
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
  "name": "seccomp_log",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581452224,
      "name": "seccomp_log",
      "external": false,
      "loc": "kernel/seccomp.c:963",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
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
  "name": "seccomp_log",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491770356,
      "name": "seccomp_log",
      "external": false,
      "loc": "kernel/seccomp.c:635",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
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
  "name": "seccomp_log",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225718884,
      "name": "seccomp_log",
      "external": false,
      "loc": "kernel/seccomp.c:635",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
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
  "name": "seccomp_log",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284815460,
      "name": "seccomp_log",
      "external": false,
      "loc": "kernel/seccomp.c:635",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
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
  "name": "seccomp_log",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272089088,
      "name": "seccomp_log",
      "external": false,
      "loc": "kernel/seccomp.c:635",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
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
  "name": "seccomp_log",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580462727,
      "name": "seccomp_log",
      "external": false,
      "loc": "kernel/seccomp.c:635",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
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
  "name": "seccomp_log",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580409767,
      "name": "seccomp_log",
      "external": false,
      "loc": "kernel/seccomp.c:635",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
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
  "name": "seccomp_log",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580453975,
      "name": "seccomp_log",
      "external": false,
      "loc": "kernel/seccomp.c:635",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
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
  "name": "seccomp_log",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580509639,
      "name": "seccomp_log",
      "external": false,
      "loc": "kernel/seccomp.c:635",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void seccomp_log(long unsigned int syscall, long int signr, u32 action, bool requested)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void seccomp_log(long unsigned int syscall, long int signr, u32 action, bool requested)
```
</details>
</li>
</ul>
