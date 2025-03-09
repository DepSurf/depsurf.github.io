# Function: <code>hk_should_isolate</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool hk_should_isolate(struct irq_data * data, unsigned int cpu)
```

```json
{
  "name": "hk_should_isolate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580076992,
      "name": "hk_should_isolate",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:175",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076992,
      "name": "hk_should_isolate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
bool hk_should_isolate(struct irq_data * data, unsigned int cpu)
```

```json
{
  "name": "hk_should_isolate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580059120,
      "name": "hk_should_isolate",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:175",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580059120,
      "name": "hk_should_isolate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
  "name": "hk_should_isolate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580060129,
      "name": "hk_should_isolate",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:175",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
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
  "name": "hk_should_isolate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580192705,
      "name": "hk_should_isolate",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:175",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
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
  "name": "hk_should_isolate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580343105,
      "name": "hk_should_isolate",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:175",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
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
  "name": "hk_should_isolate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580560753,
      "name": "hk_should_isolate",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:175",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
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
  "name": "hk_should_isolate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580634225,
      "name": "hk_should_isolate",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:175",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
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
  "name": "hk_should_isolate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580699377,
      "name": "hk_should_isolate",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:175",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool hk_should_isolate(struct irq_data * data, unsigned int cpu)
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
bool hk_should_isolate(struct irq_data * data, unsigned int cpu)
```
</details>
</li>
</ul>
