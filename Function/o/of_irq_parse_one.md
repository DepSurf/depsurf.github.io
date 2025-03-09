# Function: <code>of_irq_parse_one</code>

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
int of_irq_parse_one(struct device_node * device, int index, struct of_phandle_args * out_irq)
```

```json
{
  "name": "of_irq_parse_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501644776,
      "name": "of_irq_parse_one",
      "external": true,
      "loc": "drivers/of/irq.c:286",
      "file": "drivers/of/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:of_irq_parse_and_map_pci",
        "drivers/of/irq.c:of_irq_count",
        "drivers/of/irq.c:of_irq_get",
        "drivers/of/irq.c:irq_of_parse_and_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501644776,
      "name": "of_irq_parse_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
int of_irq_parse_one(struct device_node * device, int index, struct of_phandle_args * out_irq)
```

```json
{
  "name": "of_irq_parse_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234165396,
      "name": "of_irq_parse_one",
      "external": true,
      "loc": "drivers/of/irq.c:286",
      "file": "drivers/of/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c:rcar_gen2_regulator_quirk",
        "drivers/pci/of.c:of_irq_parse_and_map_pci",
        "drivers/of/irq.c:of_irq_count",
        "drivers/of/irq.c:of_irq_get",
        "drivers/of/irq.c:irq_of_parse_and_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234165396,
      "name": "of_irq_parse_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int of_irq_parse_one(struct device_node * device, int index, struct of_phandle_args * out_irq)
```

```json
{
  "name": "of_irq_parse_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295082832,
      "name": "of_irq_parse_one",
      "external": true,
      "loc": "drivers/of/irq.c:286",
      "file": "drivers/of/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:of_irq_parse_and_map_pci",
        "drivers/of/irq.c:of_irq_count",
        "drivers/of/irq.c:of_irq_get",
        "drivers/of/irq.c:irq_of_parse_and_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295082832,
      "name": "of_irq_parse_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int of_irq_parse_one(struct device_node * device, int index, struct of_phandle_args * out_irq)
```

```json
{
  "name": "of_irq_parse_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278103792,
      "name": "of_irq_parse_one",
      "external": true,
      "loc": "drivers/of/irq.c:286",
      "file": "drivers/of/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-sifive-plic.c:plic_init",
        "drivers/pci/of.c:of_irq_parse_and_map_pci",
        "drivers/of/irq.c:of_irq_count",
        "drivers/of/irq.c:of_irq_get",
        "drivers/of/irq.c:irq_of_parse_and_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278103792,
      "name": "of_irq_parse_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int of_irq_parse_one(struct device_node * device, int index, struct of_phandle_args * out_irq)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_irq_parse_one(struct device_node * device, int index, struct of_phandle_args * out_irq)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int of_irq_parse_one(struct device_node * device, int index, struct of_phandle_args * out_irq)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int of_irq_parse_one(struct device_node * device, int index, struct of_phandle_args * out_irq)
```
</details>
</li>
</ul>
