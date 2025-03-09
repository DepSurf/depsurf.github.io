# Function: <code>select_target_cpu</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int select_target_cpu(const struct cpumask * dest)
```

```json
{
  "name": "select_target_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586398507,
      "name": "select_target_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1780",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:set_affinity_irq"
      ],
      "caller_func": [
        "drivers/xen/events/events_base.c:set_affinity_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586395856,
      "name": "select_target_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int select_target_cpu(const struct cpumask * dest)
```

```json
{
  "name": "select_target_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586282562,
      "name": "select_target_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1822",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:set_affinity_irq"
      ],
      "caller_func": [
        "drivers/xen/events/events_base.c:set_affinity_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586279808,
      "name": "select_target_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int select_target_cpu(const struct cpumask * dest)
```

```json
{
  "name": "select_target_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586796755,
      "name": "select_target_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1828",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:set_affinity_irq"
      ],
      "caller_func": [
        "drivers/xen/events/events_base.c:set_affinity_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586792528,
      "name": "select_target_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int select_target_cpu(const struct cpumask * dest)
```

```json
{
  "name": "select_target_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588078077,
      "name": "select_target_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1828",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:set_affinity_irq"
      ],
      "caller_func": [
        "drivers/xen/events/events_base.c:set_affinity_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588073600,
      "name": "select_target_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
unsigned int select_target_cpu(const struct cpumask * dest)
```

```json
{
  "name": "select_target_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589451584,
      "name": "select_target_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1830",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:select_target_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589451584,
      "name": "select_target_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
unsigned int select_target_cpu(const struct cpumask * dest)
```

```json
{
  "name": "select_target_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589751120,
      "name": "select_target_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1827",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:select_target_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589751120,
      "name": "select_target_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
unsigned int select_target_cpu(const struct cpumask * dest)
```

```json
{
  "name": "select_target_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590090144,
      "name": "select_target_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1805",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:select_target_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590090144,
      "name": "select_target_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
unsigned int select_target_cpu(const struct cpumask * dest)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
