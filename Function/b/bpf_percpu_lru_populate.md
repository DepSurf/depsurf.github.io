# Function: <code>bpf_percpu_lru_populate</code>

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
void bpf_percpu_lru_populate(struct bpf_lru * lru, void * buf, u32 node_offset, u32 elem_size, u32 nr_elems)
```

```json
{
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580511344,
      "name": "bpf_percpu_lru_populate",
      "external": true,
      "loc": "kernel/bpf/bpf_lru_list.c:578",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580511344,
      "name": "bpf_percpu_lru_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580541076,
      "name": "bpf_percpu_lru_populate",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:579",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
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
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580605604,
      "name": "bpf_percpu_lru_populate",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:579",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
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
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580701207,
      "name": "bpf_percpu_lru_populate",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:579",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
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
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580773911,
      "name": "bpf_percpu_lru_populate",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:579",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
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
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580858375,
      "name": "bpf_percpu_lru_populate",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:576",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
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
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580909415,
      "name": "bpf_percpu_lru_populate",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:576",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
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
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581056231,
      "name": "bpf_percpu_lru_populate",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:576",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
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
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581068391,
      "name": "bpf_percpu_lru_populate",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:577",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
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
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581083363,
      "name": "bpf_percpu_lru_populate",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:577",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
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
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581311959,
      "name": "bpf_percpu_lru_populate",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:577",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
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
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581611156,
      "name": "bpf_percpu_lru_populate",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:577",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
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
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581995016,
      "name": "bpf_percpu_lru_populate",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:577",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
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
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582186322,
      "name": "bpf_percpu_lru_populate",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:582",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
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
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582335090,
      "name": "bpf_percpu_lru_populate",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:582",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
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
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492241224,
      "name": "bpf_percpu_lru_populate",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:576",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
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
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226135320,
      "name": "bpf_percpu_lru_populate",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:576",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
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
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285468112,
      "name": "bpf_percpu_lru_populate",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:576",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
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
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272385576,
      "name": "bpf_percpu_lru_populate",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:576",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
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
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580878215,
      "name": "bpf_percpu_lru_populate",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:576",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
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
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580824279,
      "name": "bpf_percpu_lru_populate",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:576",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
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
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580869463,
      "name": "bpf_percpu_lru_populate",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:576",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
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
  "name": "bpf_percpu_lru_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580928039,
      "name": "bpf_percpu_lru_populate",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:576",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
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
void bpf_percpu_lru_populate(struct bpf_lru * lru, void * buf, u32 node_offset, u32 elem_size, u32 nr_elems)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void bpf_percpu_lru_populate(struct bpf_lru * lru, void * buf, u32 node_offset, u32 elem_size, u32 nr_elems)
```
</details>
</li>
</ul>
