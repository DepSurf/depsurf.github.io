# Function: <code>__local_list_pop_free</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_lru_node * __local_list_pop_free(struct bpf_lru_locallist * loc_l)
```

```json
{
  "name": "__local_list_pop_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580509812,
      "name": "__local_list_pop_free",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:364",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580509472,
      "name": "__local_list_pop_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__local_list_pop_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580539480,
      "name": "__local_list_pop_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:364",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free"
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
  "name": "__local_list_pop_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580603928,
      "name": "__local_list_pop_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:364",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free"
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
  "name": "__local_list_pop_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580699732,
      "name": "__local_list_pop_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:364",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free"
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
  "name": "__local_list_pop_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580772420,
      "name": "__local_list_pop_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:364",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free"
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
  "name": "__local_list_pop_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580856704,
      "name": "__local_list_pop_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:361",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
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
  "name": "__local_list_pop_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580907744,
      "name": "__local_list_pop_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:361",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
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
  "name": "__local_list_pop_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581055237,
      "name": "__local_list_pop_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:361",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
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
  "name": "__local_list_pop_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581067397,
      "name": "__local_list_pop_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:361",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
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
  "name": "__local_list_pop_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581081989,
      "name": "__local_list_pop_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:361",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
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
  "name": "__local_list_pop_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581310367,
      "name": "__local_list_pop_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:361",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
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
  "name": "__local_list_pop_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581609433,
      "name": "__local_list_pop_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:361",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
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
  "name": "__local_list_pop_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581993209,
      "name": "__local_list_pop_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:361",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
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
  "name": "__local_list_pop_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582184537,
      "name": "__local_list_pop_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:366",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
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
  "name": "__local_list_pop_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582333305,
      "name": "__local_list_pop_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:366",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
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
  "name": "__local_list_pop_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492239144,
      "name": "__local_list_pop_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:361",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free"
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
  "name": "__local_list_pop_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226133500,
      "name": "__local_list_pop_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:361",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
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
  "name": "__local_list_pop_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285465672,
      "name": "__local_list_pop_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:361",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
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
  "name": "__local_list_pop_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272384076,
      "name": "__local_list_pop_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:361",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
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
  "name": "__local_list_pop_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580876544,
      "name": "__local_list_pop_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:361",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
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
  "name": "__local_list_pop_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580822608,
      "name": "__local_list_pop_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:361",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
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
  "name": "__local_list_pop_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580867792,
      "name": "__local_list_pop_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:361",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
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
  "name": "__local_list_pop_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580926368,
      "name": "__local_list_pop_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:361",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct bpf_lru_node * __local_list_pop_free(struct bpf_lru_locallist * loc_l)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct bpf_lru_node * __local_list_pop_free(struct bpf_lru_locallist * loc_l)
```
</details>
</li>
</ul>
