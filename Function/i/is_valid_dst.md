# Function: <code>is_valid_dst</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool is_valid_dst(struct bpf_dtab_netdev * obj, struct xdp_buff * xdp)
```

```json
{
  "name": "is_valid_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581381088,
      "name": "is_valid_dst",
      "external": false,
      "loc": "kernel/bpf/devmap.c:537",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_enqueue_multi",
        "kernel/bpf/devmap.c:dev_map_enqueue_multi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581381088,
      "name": "is_valid_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_valid_dst",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581709921,
      "name": "is_valid_dst",
      "external": false,
      "loc": "kernel/bpf/devmap.c:533",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_enqueue_multi",
        "kernel/bpf/devmap.c:dev_map_enqueue_multi"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool is_valid_dst(struct bpf_dtab_netdev * obj, struct xdp_frame * xdpf)
```

```json
{
  "name": "is_valid_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582109904,
      "name": "is_valid_dst",
      "external": false,
      "loc": "kernel/bpf/devmap.c:533",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_enqueue_multi",
        "kernel/bpf/devmap.c:dev_map_enqueue_multi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582109904,
      "name": "is_valid_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
bool is_valid_dst(struct bpf_dtab_netdev * obj, struct xdp_frame * xdpf)
```

```json
{
  "name": "is_valid_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582305888,
      "name": "is_valid_dst",
      "external": false,
      "loc": "kernel/bpf/devmap.c:534",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_enqueue_multi",
        "kernel/bpf/devmap.c:dev_map_enqueue_multi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582305888,
      "name": "is_valid_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
bool is_valid_dst(struct bpf_dtab_netdev * obj, struct xdp_frame * xdpf)
```

```json
{
  "name": "is_valid_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582466960,
      "name": "is_valid_dst",
      "external": false,
      "loc": "kernel/bpf/devmap.c:543",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_enqueue_multi",
        "kernel/bpf/devmap.c:dev_map_enqueue_multi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582466960,
      "name": "is_valid_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool is_valid_dst(struct bpf_dtab_netdev * obj, struct xdp_buff * xdp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
bool is_valid_dst(struct bpf_dtab_netdev * obj, struct xdp_buff * xdp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
bool is_valid_dst(struct bpf_dtab_netdev * obj, struct xdp_frame * xdpf)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
