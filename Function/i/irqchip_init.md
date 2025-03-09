# Function: <code>irqchip_init</code>

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
void irqchip_init()
```

```json
{
  "name": "irqchip_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511063400,
      "name": "irqchip_init",
      "external": true,
      "loc": "drivers/irqchip/irqchip.c:27",
      "file": "drivers/irqchip/irqchip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/irq.c:init_IRQ"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511063400,
      "name": "irqchip_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void irqchip_init()
```

```json
{
  "name": "irqchip_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243546236,
      "name": "irqchip_init",
      "external": true,
      "loc": "drivers/irqchip/irqchip.c:27",
      "file": "drivers/irqchip/irqchip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/irq.c:init_IRQ",
        "arch/arm/mach-exynos/exynos.c:exynos_init_irq",
        "arch/arm/mach-highbank/highbank.c:highbank_init_irq",
        "arch/arm/mach-mvebu/board-v7.c:mvebu_init_irq",
        "arch/arm/mach-imx/mach-imx6q.c:imx6q_init_irq",
        "arch/arm/mach-imx/mach-imx6sl.c:imx6sl_init_irq",
        "arch/arm/mach-imx/mach-imx6sx.c:imx6sx_init_irq",
        "arch/arm/mach-imx/mach-imx6ul.c:imx6ul_init_irq",
        "arch/arm/mach-imx/mach-imx7d.c:imx7d_init_irq",
        "arch/arm/mach-omap2/omap4-common.c:omap_gic_of_init",
        "arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of",
        "arch/arm/mach-shmobile/setup-r8a7778.c:r8a7778_init_irq_dt",
        "arch/arm/mach-shmobile/setup-r8a7779.c:r8a7779_init_irq_dt",
        "arch/arm/mach-tegra/tegra.c:tegra_dt_init_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243546236,
      "name": "irqchip_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void irqchip_init()
```

```json
{
  "name": "irqchip_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302745036,
      "name": "irqchip_init",
      "external": true,
      "loc": "drivers/irqchip/irqchip.c:27",
      "file": "drivers/irqchip/irqchip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302745036,
      "name": "irqchip_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void irqchip_init()
```

```json
{
  "name": "irqchip_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270772412,
      "name": "irqchip_init",
      "external": true,
      "loc": "drivers/irqchip/irqchip.c:27",
      "file": "drivers/irqchip/irqchip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/irq.c:init_IRQ"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270772412,
      "name": "irqchip_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void irqchip_init()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void irqchip_init()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void irqchip_init()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void irqchip_init()
```
</details>
</li>
</ul>
