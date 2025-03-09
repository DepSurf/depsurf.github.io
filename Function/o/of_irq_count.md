# Function: <code>of_irq_count</code>

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
int of_irq_count(struct device_node * dev)
```

```json
{
  "name": "of_irq_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501646008,
      "name": "of_irq_count",
      "external": true,
      "loc": "drivers/of/irq.c:433",
      "file": "drivers/of/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init",
        "drivers/of/platform.c:of_device_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501646008,
      "name": "of_irq_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int of_irq_count(struct device_node * dev)
```

```json
{
  "name": "of_irq_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234166588,
      "name": "of_irq_count",
      "external": true,
      "loc": "drivers/of/irq.c:433",
      "file": "drivers/of/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe",
        "drivers/clocksource/exynos_mct.c:mct_init_dt",
        "drivers/of/platform.c:of_device_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234166588,
      "name": "of_irq_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int of_irq_count(struct device_node * dev)
```

```json
{
  "name": "of_irq_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295084480,
      "name": "of_irq_count",
      "external": true,
      "loc": "drivers/of/irq.c:433",
      "file": "drivers/of/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_init",
        "drivers/of/platform.c:of_device_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295084480,
      "name": "of_irq_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int of_irq_count(struct device_node * dev)
```

```json
{
  "name": "of_irq_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278104768,
      "name": "of_irq_count",
      "external": true,
      "loc": "drivers/of/irq.c:433",
      "file": "drivers/of/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-sifive-plic.c:plic_init",
        "drivers/of/platform.c:of_device_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278104768,
      "name": "of_irq_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int of_irq_count(struct device_node * dev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_irq_count(struct device_node * dev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int of_irq_count(struct device_node * dev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int of_irq_count(struct device_node * dev)
```
</details>
</li>
</ul>
