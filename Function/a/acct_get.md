# Function: <code>acct_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579943775,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:141",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579974591,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:141",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580005071,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:141",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580012271,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:143",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580059126,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:144",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:144",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:144",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:144",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:144",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
struct bsd_acct_struct * acct_get(struct pid_namespace * ns)
```

```json
{
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580324096,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:144",
      "file": "kernel/acct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580324096,
      "name": "acct_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
struct bsd_acct_struct * acct_get(struct pid_namespace * ns)
```

```json
{
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580309392,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:144",
      "file": "kernel/acct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580309392,
      "name": "acct_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:144",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:144",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:163",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:163",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:163",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:163",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:144",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:144",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:144",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271942096,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:144",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:144",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:144",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:144",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
  "name": "acct_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acct_get",
      "external": false,
      "loc": "kernel/acct.c:144",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process"
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
struct bsd_acct_struct * acct_get(struct pid_namespace * ns)
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
struct bsd_acct_struct * acct_get(struct pid_namespace * ns)
```
</details>
</li>
</ul>
