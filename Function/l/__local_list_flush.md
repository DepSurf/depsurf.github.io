# Function: <code>__local_list_flush</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580510146,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:294",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580539513,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:293",
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
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580604092,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:293",
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
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580699889,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:293",
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
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580772577,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:293",
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
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580856872,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:290",
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
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580907912,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:290",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __local_list_flush(struct bpf_lru_list * l, struct bpf_lru_locallist * loc_l)
```

```json
{
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581054672,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:290",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581054672,
      "name": "__local_list_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
void __local_list_flush(struct bpf_lru_list * l, struct bpf_lru_locallist * loc_l)
```

```json
{
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581066832,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:290",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581066832,
      "name": "__local_list_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581081457,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:290",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
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
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581309772,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:290",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
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
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581608796,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:290",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
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
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581992556,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:290",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
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
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582183900,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:295",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
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
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582332668,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:295",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
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
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492239980,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:290",
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
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226133636,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:290",
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
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285465936,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:290",
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
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272384234,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:290",
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
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580876712,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:290",
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
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580822776,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:290",
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
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580867960,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:290",
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
  "name": "__local_list_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580926536,
      "name": "__local_list_flush",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:290",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __local_list_flush(struct bpf_lru_list * l, struct bpf_lru_locallist * loc_l)
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
void __local_list_flush(struct bpf_lru_list * l, struct bpf_lru_locallist * loc_l)
```
</details>
</li>
</ul>
