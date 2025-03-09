# Function: <code>___pcpu_freelist_pop_nmi</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pcpu_freelist_node * ___pcpu_freelist_pop_nmi(struct pcpu_freelist * s)
```

```json
{
  "name": "___pcpu_freelist_pop_nmi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581064432,
      "name": "___pcpu_freelist_pop_nmi",
      "external": false,
      "loc": "kernel/bpf/percpu_freelist.c:158",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581064432,
      "name": "___pcpu_freelist_pop_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
  "name": "___pcpu_freelist_pop_nmi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581080199,
      "name": "___pcpu_freelist_pop_nmi",
      "external": false,
      "loc": "kernel/bpf/percpu_freelist.c:158",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop"
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
  "name": "___pcpu_freelist_pop_nmi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581308209,
      "name": "___pcpu_freelist_pop_nmi",
      "external": false,
      "loc": "kernel/bpf/percpu_freelist.c:158",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop"
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
  "name": "___pcpu_freelist_pop_nmi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581607092,
      "name": "___pcpu_freelist_pop_nmi",
      "external": false,
      "loc": "kernel/bpf/percpu_freelist.c:158",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop"
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
struct pcpu_freelist_node * ___pcpu_freelist_pop_nmi(struct pcpu_freelist * s)
```

```json
{
  "name": "___pcpu_freelist_pop_nmi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989184,
      "name": "___pcpu_freelist_pop_nmi",
      "external": false,
      "loc": "kernel/bpf/percpu_freelist.c:153",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989184,
      "name": "___pcpu_freelist_pop_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
struct pcpu_freelist_node * ___pcpu_freelist_pop_nmi(struct pcpu_freelist * s)
```

```json
{
  "name": "___pcpu_freelist_pop_nmi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582180512,
      "name": "___pcpu_freelist_pop_nmi",
      "external": false,
      "loc": "kernel/bpf/percpu_freelist.c:153",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582180512,
      "name": "___pcpu_freelist_pop_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
struct pcpu_freelist_node * ___pcpu_freelist_pop_nmi(struct pcpu_freelist * s)
```

```json
{
  "name": "___pcpu_freelist_pop_nmi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582329280,
      "name": "___pcpu_freelist_pop_nmi",
      "external": false,
      "loc": "kernel/bpf/percpu_freelist.c:153",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582329280,
      "name": "___pcpu_freelist_pop_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct pcpu_freelist_node * ___pcpu_freelist_pop_nmi(struct pcpu_freelist * s)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct pcpu_freelist_node * ___pcpu_freelist_pop_nmi(struct pcpu_freelist * s)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct pcpu_freelist_node * ___pcpu_freelist_pop_nmi(struct pcpu_freelist * s)
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
