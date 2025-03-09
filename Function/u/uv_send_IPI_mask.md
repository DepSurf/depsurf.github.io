# Function: <code>uv_send_IPI_mask</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void uv_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "uv_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579292640,
      "name": "uv_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:552",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579292640,
      "name": "uv_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void uv_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "uv_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579322981,
      "name": "uv_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:586",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322896,
      "name": "uv_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void uv_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "uv_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579325380,
      "name": "uv_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:743",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579325280,
      "name": "uv_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void uv_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "uv_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579328100,
      "name": "uv_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:739",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579328000,
      "name": "uv_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void uv_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "uv_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579382836,
      "name": "uv_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:739",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579382736,
      "name": "uv_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void uv_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "uv_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579448014,
      "name": "uv_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:745",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579447920,
      "name": "uv_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void uv_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "uv_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579534896,
      "name": "uv_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:745",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579534896,
      "name": "uv_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void uv_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "uv_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579547808,
      "name": "uv_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:746",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547808,
      "name": "uv_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void uv_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "uv_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579576080,
      "name": "uv_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:747",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579576080,
      "name": "uv_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void uv_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "uv_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579298480,
      "name": "uv_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:552",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579298480,
      "name": "uv_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void uv_send_IPI_mask(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void uv_send_IPI_mask(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void uv_send_IPI_mask(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void uv_send_IPI_mask(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void uv_send_IPI_mask(const struct cpumask * mask, int vector)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void uv_send_IPI_mask(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void uv_send_IPI_mask(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
void uv_send_IPI_mask(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
