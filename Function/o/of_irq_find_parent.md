# Function: <code>of_irq_find_parent</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct device_node * of_irq_find_parent(struct device_node * child)
```

```json
{
  "name": "of_irq_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501642784,
      "name": "of_irq_find_parent",
      "external": true,
      "loc": "drivers/of/irq.c:54",
      "file": "drivers/of/irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-mvebu-gicp.c:mvebu_gicp_probe",
        "drivers/irqchip/irq-ti-sci-intr.c:ti_sci_intr_irq_domain_probe",
        "drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_domain_probe",
        "drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_request_resources",
        "drivers/of/irq.c:of_irq_init",
        "drivers/of/irq.c:of_irq_parse_one",
        "drivers/of/irq.c:of_irq_parse_raw",
        "drivers/of/irq.c:of_irq_parse_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501642784,
      "name": "of_irq_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct device_node * of_irq_find_parent(struct device_node * child)
```

```json
{
  "name": "of_irq_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234163264,
      "name": "of_irq_find_parent",
      "external": true,
      "loc": "drivers/of/irq.c:54",
      "file": "drivers/of/irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-alpine-msi.c:alpine_msix_init",
        "drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_probe",
        "drivers/irqchip/irq-uniphier-aidet.c:uniphier_aidet_probe",
        "drivers/of/irq.c:of_irq_init",
        "drivers/of/irq.c:of_irq_parse_one",
        "drivers/of/irq.c:of_irq_parse_raw",
        "drivers/of/irq.c:of_irq_parse_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234163264,
      "name": "of_irq_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct device_node * of_irq_find_parent(struct device_node * child)
```

```json
{
  "name": "of_irq_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295080160,
      "name": "of_irq_find_parent",
      "external": true,
      "loc": "drivers/of/irq.c:54",
      "file": "drivers/of/irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/irq.c:of_irq_init",
        "drivers/of/irq.c:of_irq_parse_one",
        "drivers/of/irq.c:of_irq_parse_raw",
        "drivers/of/irq.c:of_irq_parse_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295080160,
      "name": "of_irq_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct device_node * of_irq_find_parent(struct device_node * child)
```

```json
{
  "name": "of_irq_find_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278101866,
      "name": "of_irq_find_parent",
      "external": true,
      "loc": "drivers/of/irq.c:54",
      "file": "drivers/of/irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/irq.c:of_irq_init",
        "drivers/of/irq.c:of_irq_parse_one",
        "drivers/of/irq.c:of_irq_parse_raw",
        "drivers/of/irq.c:of_irq_parse_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278101866,
      "name": "of_irq_find_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
    }
  ]
}
```
</details>
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
struct device_node * of_irq_find_parent(struct device_node * child)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct device_node * of_irq_find_parent(struct device_node * child)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct device_node * of_irq_find_parent(struct device_node * child)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct device_node * of_irq_find_parent(struct device_node * child)
```
</details>
</li>
</ul>
