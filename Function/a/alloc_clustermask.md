# Function: <code>alloc_clustermask</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_clustermask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579239965,
      "name": "alloc_clustermask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:125",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
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
  "name": "alloc_clustermask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579252468,
      "name": "alloc_clustermask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:126",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
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
  "name": "alloc_clustermask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579276276,
      "name": "alloc_clustermask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:126",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
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
  "name": "alloc_clustermask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579290692,
      "name": "alloc_clustermask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:126",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
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
  "name": "alloc_clustermask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579296676,
      "name": "alloc_clustermask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:124",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
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
int alloc_clustermask(unsigned int cpu, int node)
```

```json
{
  "name": "alloc_clustermask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579326048,
      "name": "alloc_clustermask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:124",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326048,
      "name": "alloc_clustermask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int alloc_clustermask(unsigned int cpu, int node)
```

```json
{
  "name": "alloc_clustermask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579327648,
      "name": "alloc_clustermask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:126",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579327648,
      "name": "alloc_clustermask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
  "name": "alloc_clustermask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579330420,
      "name": "alloc_clustermask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:126",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
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
  "name": "alloc_clustermask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579385481,
      "name": "alloc_clustermask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:126",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
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
  "name": "alloc_clustermask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579451081,
      "name": "alloc_clustermask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:132",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
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
  "name": "alloc_clustermask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579538809,
      "name": "alloc_clustermask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:132",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int alloc_clustermask(unsigned int cpu, u32 cluster, int node)
```

```json
{
  "name": "alloc_clustermask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579552752,
      "name": "alloc_clustermask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:134",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552752,
      "name": "alloc_clustermask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
int alloc_clustermask(unsigned int cpu, u32 cluster, int node)
```

```json
{
  "name": "alloc_clustermask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579580384,
      "name": "alloc_clustermask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:124",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579580384,
      "name": "alloc_clustermask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 651
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_clustermask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579292484,
      "name": "alloc_clustermask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:124",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
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
  "name": "alloc_clustermask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579227844,
      "name": "alloc_clustermask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:124",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
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
  "name": "alloc_clustermask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579293684,
      "name": "alloc_clustermask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:124",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
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
  "name": "alloc_clustermask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579302516,
      "name": "alloc_clustermask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:124",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
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
int alloc_clustermask(unsigned int cpu, int node)
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
int alloc_clustermask(unsigned int cpu, int node)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int alloc_clustermask(unsigned int cpu, u32 cluster, int node)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
