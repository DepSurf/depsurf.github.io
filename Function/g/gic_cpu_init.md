# Function: <code>gic_cpu_init</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int gic_cpu_init(struct gic_chip_data * gic)
```

```json
{
  "name": "gic_cpu_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496365824,
      "name": "gic_cpu_init",
      "external": false,
      "loc": "drivers/irqchip/irq-gic.c:514",
      "file": "drivers/irqchip/irq-gic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic.c:gic_init_bases",
        "drivers/irqchip/irq-gic.c:gic_starting_cpu"
      ]
    },
    {
      "addr": 18446603336511074468,
      "name": "gic_cpu_init",
      "external": false,
      "loc": "drivers/irqchip/irq-gic-v3.c:1006",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases",
        "drivers/irqchip/irq-gic-v3.c:gic_starting_cpu"
      ],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases",
        "drivers/irqchip/irq-gic-v3.c:gic_starting_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496365824,
      "name": "gic_cpu_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    },
    {
      "addr": 18446603336496379416,
      "name": "gic_cpu_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int gic_cpu_init(struct gic_chip_data * gic)
```

```json
{
  "name": "gic_cpu_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229700860,
      "name": "gic_cpu_init",
      "external": false,
      "loc": "drivers/irqchip/irq-gic.c:514",
      "file": "drivers/irqchip/irq-gic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic.c:gic_init_bases",
        "drivers/irqchip/irq-gic.c:gic_starting_cpu"
      ]
    },
    {
      "addr": 3243555884,
      "name": "gic_cpu_init",
      "external": false,
      "loc": "drivers/irqchip/irq-gic-v3.c:1006",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases"
      ],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229700860,
      "name": "gic_cpu_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 3229711740,
      "name": "gic_cpu_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int gic_cpu_init(struct gic_chip_data * gic)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int gic_cpu_init(struct gic_chip_data * gic)
```
</details>
</li>
</ul>
