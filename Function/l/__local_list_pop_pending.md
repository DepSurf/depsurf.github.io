# Function: <code>__local_list_pop_pending</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_lru_node * __local_list_pop_pending(struct bpf_lru * lru, struct bpf_lru_locallist * loc_l)
```

```json
{
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580509552,
      "name": "__local_list_pop_pending",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:377",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580509552,
      "name": "__local_list_pop_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580540128,
      "name": "__local_list_pop_pending",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:378",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580604584,
      "name": "__local_list_pop_pending",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:378",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__local_list_pop_pending",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:378",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__local_list_pop_pending",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:378",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__local_list_pop_pending",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:375",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__local_list_pop_pending",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:375",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__local_list_pop_pending",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:375",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__local_list_pop_pending",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:375",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__local_list_pop_pending",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:375",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__local_list_pop_pending",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:375",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__local_list_pop_pending",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:375",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__local_list_pop_pending",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:375",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__local_list_pop_pending",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:380",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__local_list_pop_pending",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:380",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__local_list_pop_pending",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:375",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__local_list_pop_pending",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:375",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__local_list_pop_pending",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:375",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272384588,
      "name": "__local_list_pop_pending",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:375",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__local_list_pop_pending",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:375",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__local_list_pop_pending",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:375",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__local_list_pop_pending",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:375",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "__local_list_pop_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__local_list_pop_pending",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:375",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
struct bpf_lru_node * __local_list_pop_pending(struct bpf_lru * lru, struct bpf_lru_locallist * loc_l)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct bpf_lru_node * __local_list_pop_pending(struct bpf_lru * lru, struct bpf_lru_locallist * loc_l)
```
</details>
</li>
</ul>
