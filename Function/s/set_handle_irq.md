# Function: <code>set_handle_irq</code>

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
int set_handle_irq(void (*)(struct pt_regs *) handle_irq)
```

```json
{
  "name": "set_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510891732,
      "name": "set_handle_irq",
      "external": true,
      "loc": "kernel/irq/handle.c:214",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_l1_intc_of_init",
        "drivers/irqchip/irq-gic.c:__gic_init_bases",
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336510891732,
      "name": "set_handle_irq",
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
int set_handle_irq(void (*)(struct pt_regs *) handle_irq)
```

```json
{
  "name": "set_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243380032,
      "name": "set_handle_irq",
      "external": true,
      "loc": "kernel/irq/handle.c:214",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-imx/tzic.c:tzic_init_dt",
        "drivers/irqchip/irq-hip04.c:hip04_of_init",
        "drivers/irqchip/irq-orion.c:orion_irq_init",
        "drivers/irqchip/irq-omap-intc.c:intc_of_init",
        "drivers/irqchip/irq-gic.c:__gic_init_bases",
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init",
        "drivers/irqchip/irq-rda-intc.c:rda8810_intc_init",
        "drivers/irqchip/irq-aspeed-vic.c:avic_of_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243380032,
      "name": "set_handle_irq",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int set_handle_irq(void (*)(struct pt_regs *) handle_irq)
```

```json
{
  "name": "set_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270631424,
      "name": "set_handle_irq",
      "external": true,
      "loc": "kernel/irq/handle.c:214",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-sifive-plic.c:plic_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270631424,
      "name": "set_handle_irq",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int set_handle_irq(void (*)(struct pt_regs *) handle_irq)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int set_handle_irq(void (*)(struct pt_regs *) handle_irq)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int set_handle_irq(void (*)(struct pt_regs *) handle_irq)
```
</details>
</li>
</ul>
