# Function: <code>convert_offset_index</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
u32 convert_offset_index(struct irq_data * d, u32 offset, u32 * index)
```

```json
{
  "name": "convert_offset_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496372128,
      "name": "convert_offset_index",
      "external": false,
      "loc": "drivers/irqchip/irq-gic-v3.c:243",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3.c:gic_set_affinity",
        "drivers/irqchip/irq-gic-v3.c:gic_set_type",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_set_prio",
        "drivers/irqchip/irq-gic-v3.c:gic_poke_irq",
        "drivers/irqchip/irq-gic-v3.c:gic_peek_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496372128,
      "name": "convert_offset_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
u32 convert_offset_index(struct irq_data * d, u32 offset, u32 * index)
```

```json
{
  "name": "convert_offset_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229707232,
      "name": "convert_offset_index",
      "external": false,
      "loc": "drivers/irqchip/irq-gic-v3.c:243",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3.c:gic_set_affinity",
        "drivers/irqchip/irq-gic-v3.c:gic_set_type",
        "drivers/irqchip/irq-gic-v3.c:gic_poke_irq",
        "drivers/irqchip/irq-gic-v3.c:gic_peek_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229707232,
      "name": "convert_offset_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
u32 convert_offset_index(struct irq_data * d, u32 offset, u32 * index)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
u32 convert_offset_index(struct irq_data * d, u32 offset, u32 * index)
```
</details>
</li>
</ul>
