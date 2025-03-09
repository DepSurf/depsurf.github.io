# Function: <code>__xdp_map_lookup_elem</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void * __xdp_map_lookup_elem(struct bpf_map * map, u32 index)
```

```json
{
  "name": "__xdp_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587645616,
      "name": "__xdp_map_lookup_elem",
      "external": false,
      "loc": "net/core/filter.c:2587",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_generic_redirect_map",
        "net/core/filter.c:xdp_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587645616,
      "name": "__xdp_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void * __xdp_map_lookup_elem(struct bpf_map * map, u32 index)
```

```json
{
  "name": "__xdp_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587961440,
      "name": "__xdp_map_lookup_elem",
      "external": false,
      "loc": "net/core/filter.c:3225",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587961440,
      "name": "__xdp_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xdp_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588125811,
      "name": "__xdp_map_lookup_elem",
      "external": false,
      "loc": "net/core/filter.c:3439",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect"
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
  "name": "__xdp_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588428961,
      "name": "__xdp_map_lookup_elem",
      "external": false,
      "loc": "net/core/filter.c:3572",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_xdp_redirect_map"
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
  "name": "__xdp_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588634529,
      "name": "__xdp_map_lookup_elem",
      "external": false,
      "loc": "net/core/filter.c:3576",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_xdp_redirect_map"
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
  "name": "__xdp_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589501397,
      "name": "__xdp_map_lookup_elem",
      "external": false,
      "loc": "net/core/filter.c:3540",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_xdp_redirect_map"
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
  "name": "__xdp_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589503797,
      "name": "__xdp_map_lookup_elem",
      "external": false,
      "loc": "net/core/filter.c:3947",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_xdp_redirect_map"
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
  "name": "__xdp_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502212888,
      "name": "__xdp_map_lookup_elem",
      "external": false,
      "loc": "net/core/filter.c:3576",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_xdp_redirect_map"
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
  "name": "__xdp_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234927864,
      "name": "__xdp_map_lookup_elem",
      "external": false,
      "loc": "net/core/filter.c:3576",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_xdp_redirect_map"
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
  "name": "__xdp_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295655392,
      "name": "__xdp_map_lookup_elem",
      "external": false,
      "loc": "net/core/filter.c:3576",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_xdp_redirect_map"
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
  "name": "__xdp_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278435566,
      "name": "__xdp_map_lookup_elem",
      "external": false,
      "loc": "net/core/filter.c:3576",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_xdp_redirect_map"
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
  "name": "__xdp_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588241265,
      "name": "__xdp_map_lookup_elem",
      "external": false,
      "loc": "net/core/filter.c:3576",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_xdp_redirect_map"
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
  "name": "__xdp_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587954081,
      "name": "__xdp_map_lookup_elem",
      "external": false,
      "loc": "net/core/filter.c:3576",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_xdp_redirect_map"
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
  "name": "__xdp_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588573089,
      "name": "__xdp_map_lookup_elem",
      "external": false,
      "loc": "net/core/filter.c:3576",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_xdp_redirect_map"
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
  "name": "__xdp_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588710577,
      "name": "__xdp_map_lookup_elem",
      "external": false,
      "loc": "net/core/filter.c:3576",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_xdp_redirect_map"
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void * __xdp_map_lookup_elem(struct bpf_map * map, u32 index)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void * __xdp_map_lookup_elem(struct bpf_map * map, u32 index)
```
</details>
</li>
</ul>
