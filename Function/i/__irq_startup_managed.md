# Function: <code>__irq_startup_managed</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__irq_startup_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579802262,
      "name": "__irq_startup_managed",
      "external": false,
      "loc": "kernel/irq/chip.c:196",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_startup"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__irq_startup_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579836278,
      "name": "__irq_startup_managed",
      "external": false,
      "loc": "kernel/irq/chip.c:196",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_startup"
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
  "name": "__irq_startup_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579870126,
      "name": "__irq_startup_managed",
      "external": false,
      "loc": "kernel/irq/chip.c:194",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_startup"
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
  "name": "__irq_startup_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579917166,
      "name": "__irq_startup_managed",
      "external": false,
      "loc": "kernel/irq/chip.c:194",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_startup"
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
  "name": "__irq_startup_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579955244,
      "name": "__irq_startup_managed",
      "external": false,
      "loc": "kernel/irq/chip.c:194",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_startup"
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
  "name": "__irq_startup_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580005100,
      "name": "__irq_startup_managed",
      "external": false,
      "loc": "kernel/irq/chip.c:194",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_startup"
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
int __irq_startup_managed(struct irq_desc * desc, struct cpumask * aff, bool force)
```

```json
{
  "name": "__irq_startup_managed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580051360,
      "name": "__irq_startup_managed",
      "external": false,
      "loc": "kernel/irq/chip.c:194",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580051360,
      "name": "__irq_startup_managed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int __irq_startup_managed(struct irq_desc * desc, struct cpumask * aff, bool force)
```

```json
{
  "name": "__irq_startup_managed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580034000,
      "name": "__irq_startup_managed",
      "external": false,
      "loc": "kernel/irq/chip.c:194",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034000,
      "name": "__irq_startup_managed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
  "name": "__irq_startup_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580038072,
      "name": "__irq_startup_managed",
      "external": false,
      "loc": "kernel/irq/chip.c:194",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_startup"
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
  "name": "__irq_startup_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580170632,
      "name": "__irq_startup_managed",
      "external": false,
      "loc": "kernel/irq/chip.c:194",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_startup"
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
  "name": "__irq_startup_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580317547,
      "name": "__irq_startup_managed",
      "external": false,
      "loc": "kernel/irq/chip.c:191",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_startup"
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
  "name": "__irq_startup_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580531515,
      "name": "__irq_startup_managed",
      "external": false,
      "loc": "kernel/irq/chip.c:191",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_startup"
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
  "name": "__irq_startup_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580604811,
      "name": "__irq_startup_managed",
      "external": false,
      "loc": "kernel/irq/chip.c:191",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_startup"
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
  "name": "__irq_startup_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580669323,
      "name": "__irq_startup_managed",
      "external": false,
      "loc": "kernel/irq/chip.c:191",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_startup"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__irq_startup_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491201184,
      "name": "__irq_startup_managed",
      "external": false,
      "loc": "kernel/irq/chip.c:194",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_startup"
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
  "name": "__irq_startup_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225220240,
      "name": "__irq_startup_managed",
      "external": false,
      "loc": "kernel/irq/chip.c:194",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_startup"
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
  "name": "__irq_startup_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284104240,
      "name": "__irq_startup_managed",
      "external": false,
      "loc": "kernel/irq/chip.c:194",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_startup"
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
  "name": "__irq_startup_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271743014,
      "name": "__irq_startup_managed",
      "external": false,
      "loc": "kernel/irq/chip.c:194",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_startup"
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
  "name": "__irq_startup_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579973836,
      "name": "__irq_startup_managed",
      "external": false,
      "loc": "kernel/irq/chip.c:194",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_startup"
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
  "name": "__irq_startup_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579911644,
      "name": "__irq_startup_managed",
      "external": false,
      "loc": "kernel/irq/chip.c:194",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_startup"
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
  "name": "__irq_startup_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579965372,
      "name": "__irq_startup_managed",
      "external": false,
      "loc": "kernel/irq/chip.c:194",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_startup"
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
  "name": "__irq_startup_managed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580011900,
      "name": "__irq_startup_managed",
      "external": false,
      "loc": "kernel/irq/chip.c:194",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_startup"
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
int __irq_startup_managed(struct irq_desc * desc, struct cpumask * aff, bool force)
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
int __irq_startup_managed(struct irq_desc * desc, struct cpumask * aff, bool force)
```
</details>
</li>
</ul>
