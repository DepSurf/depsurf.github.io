# Function: <code>cpu_map_build_skb</code>

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
struct sk_buff * cpu_map_build_skb(struct bpf_cpu_map_entry * rcpu, struct xdp_pkt * xdp_pkt)
```

```json
{
  "name": "cpu_map_build_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580613552,
      "name": "cpu_map_build_skb",
      "external": true,
      "loc": "kernel/bpf/cpumap.c:225",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580613552,
      "name": "cpu_map_build_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_map_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580724099,
      "name": "cpu_map_build_skb",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:162",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
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
  "name": "cpu_map_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580804227,
      "name": "cpu_map_build_skb",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:162",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
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
  "name": "cpu_map_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580892428,
      "name": "cpu_map_build_skb",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:163",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
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
  "name": "cpu_map_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580945068,
      "name": "cpu_map_build_skb",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:163",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
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
  "name": "cpu_map_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581105440,
      "name": "cpu_map_build_skb",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:154",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581105440,
      "name": "cpu_map_build_skb.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct sk_buff * cpu_map_build_skb(struct xdp_frame * xdpf, struct sk_buff * skb)
```

```json
{
  "name": "cpu_map_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581133440,
      "name": "cpu_map_build_skb",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:144",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581133440,
      "name": "cpu_map_build_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    }
  ]
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
  "name": "cpu_map_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492286376,
      "name": "cpu_map_build_skb",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:163",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
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
  "name": "cpu_map_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226174568,
      "name": "cpu_map_build_skb",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:163",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
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
  "name": "cpu_map_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285520432,
      "name": "cpu_map_build_skb",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:163",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
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
  "name": "cpu_map_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272420408,
      "name": "cpu_map_build_skb",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:163",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
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
  "name": "cpu_map_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580913868,
      "name": "cpu_map_build_skb",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:163",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
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
  "name": "cpu_map_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580859932,
      "name": "cpu_map_build_skb",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:163",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
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
  "name": "cpu_map_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580905116,
      "name": "cpu_map_build_skb",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:163",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
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
  "name": "cpu_map_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580963216,
      "name": "cpu_map_build_skb",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:163",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
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
struct sk_buff * cpu_map_build_skb(struct bpf_cpu_map_entry * rcpu, struct xdp_pkt * xdp_pkt)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
struct sk_buff * cpu_map_build_skb(struct bpf_cpu_map_entry * rcpu, struct xdp_pkt * xdp_pkt)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct sk_buff * cpu_map_build_skb(struct xdp_frame * xdpf, struct sk_buff * skb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct sk_buff * cpu_map_build_skb(struct xdp_frame * xdpf, struct sk_buff * skb)
```
</details>
</li>
</ul>
