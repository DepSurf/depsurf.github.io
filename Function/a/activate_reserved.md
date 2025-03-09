# Function: <code>activate_reserved</code>

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
  "name": "activate_reserved",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579222773,
      "name": "activate_reserved",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:385",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
  "name": "activate_reserved",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579235146,
      "name": "activate_reserved",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:395",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
  "name": "activate_reserved",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579258817,
      "name": "activate_reserved",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:386",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
  "name": "activate_reserved",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579272904,
      "name": "activate_reserved",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:383",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
  "name": "activate_reserved",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579275176,
      "name": "activate_reserved",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:383",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int activate_reserved(struct irq_data * irqd)
```

```json
{
  "name": "activate_reserved",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "activate_reserved",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:384",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579301744,
      "name": "activate_reserved",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071579305138,
      "name": "activate_reserved.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int activate_reserved(struct irq_data * irqd)
```

```json
{
  "name": "activate_reserved",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "activate_reserved",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:388",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579307152,
      "name": "activate_reserved",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071591260304,
      "name": "activate_reserved.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
  "name": "activate_reserved",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579309352,
      "name": "activate_reserved",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:388",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
  "name": "activate_reserved",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579357976,
      "name": "activate_reserved",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:388",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
  "name": "activate_reserved",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579421158,
      "name": "activate_reserved",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:388",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
  "name": "activate_reserved",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579504614,
      "name": "activate_reserved",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:388",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
  "name": "activate_reserved",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579516886,
      "name": "activate_reserved",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:388",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
  "name": "activate_reserved",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579545606,
      "name": "activate_reserved",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:399",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "activate_reserved",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579273880,
      "name": "activate_reserved",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:383",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
  "name": "activate_reserved",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579209224,
      "name": "activate_reserved",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:383",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
  "name": "activate_reserved",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579275080,
      "name": "activate_reserved",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:383",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
  "name": "activate_reserved",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579280972,
      "name": "activate_reserved",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:383",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
int activate_reserved(struct irq_data * irqd)
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
int activate_reserved(struct irq_data * irqd)
```
</details>
</li>
</ul>
