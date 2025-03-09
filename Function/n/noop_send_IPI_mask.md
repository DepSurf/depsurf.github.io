# Function: <code>noop_send_IPI_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```

```json
{
  "name": "noop_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "noop_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_noop.c:33",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579192464,
      "name": "noop_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```

```json
{
  "name": "noop_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "noop_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_noop.c:33",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579204176,
      "name": "noop_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```

```json
{
  "name": "noop_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579201504,
      "name": "noop_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_noop.c:33",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579201504,
      "name": "noop_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```

```json
{
  "name": "noop_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579217168,
      "name": "noop_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_noop.c:34",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579217168,
      "name": "noop_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```

```json
{
  "name": "noop_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579229456,
      "name": "noop_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_noop.c:34",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229456,
      "name": "noop_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```

```json
{
  "name": "noop_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579253152,
      "name": "noop_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_noop.c:34",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579253152,
      "name": "noop_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```

```json
{
  "name": "noop_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579267168,
      "name": "noop_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_noop.c:34",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579267168,
      "name": "noop_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```

```json
{
  "name": "noop_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579268816,
      "name": "noop_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_noop.c:18",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268816,
      "name": "noop_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```

```json
{
  "name": "noop_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579296800,
      "name": "noop_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_noop.c:18",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579296800,
      "name": "noop_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```

```json
{
  "name": "noop_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579302048,
      "name": "noop_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_noop.c:19",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579302048,
      "name": "noop_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```

```json
{
  "name": "noop_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579304912,
      "name": "noop_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_noop.c:19",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304912,
      "name": "noop_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```

```json
{
  "name": "noop_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579352944,
      "name": "noop_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_noop.c:19",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579352944,
      "name": "noop_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```

```json
{
  "name": "noop_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579415056,
      "name": "noop_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_noop.c:19",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579415056,
      "name": "noop_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```

```json
{
  "name": "noop_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579497632,
      "name": "noop_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_noop.c:19",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579497632,
      "name": "noop_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```

```json
{
  "name": "noop_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579509808,
      "name": "noop_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_noop.c:19",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509808,
      "name": "noop_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```

```json
{
  "name": "noop_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579537872,
      "name": "noop_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_noop.c:24",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579537872,
      "name": "noop_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```

```json
{
  "name": "noop_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579267520,
      "name": "noop_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_noop.c:18",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579267520,
      "name": "noop_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```

```json
{
  "name": "noop_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579202944,
      "name": "noop_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_noop.c:18",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579202944,
      "name": "noop_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```

```json
{
  "name": "noop_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579268720,
      "name": "noop_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_noop.c:18",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268720,
      "name": "noop_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```

```json
{
  "name": "noop_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274320,
      "name": "noop_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_noop.c:18",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274320,
      "name": "noop_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
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
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void noop_send_IPI_mask(const struct cpumask * cpumask, int vector)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
