# Function: <code>__handle_domain_irq</code>

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
int __handle_domain_irq(struct irq_domain * domain, unsigned int hwirq, bool lookup, struct pt_regs * regs)
```

```json
{
  "name": "__handle_domain_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491170768,
      "name": "__handle_domain_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:659",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-bcm2835.c:bcm2835_handle_irq",
        "drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_handle_irq",
        "drivers/irqchip/irq-sun4i.c:sun4i_handle_irq",
        "drivers/irqchip/irq-gic.c:gic_handle_irq",
        "drivers/irqchip/irq-gic-v3.c:gic_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491170768,
      "name": "__handle_domain_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int __handle_domain_irq(struct irq_domain * domain, unsigned int hwirq, bool lookup, struct pt_regs * regs)
```

```json
{
  "name": "__handle_domain_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225195936,
      "name": "__handle_domain_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:659",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/irq.c:asm_do_IRQ",
        "arch/arm/mach-imx/tzic.c:tzic_handle_irq",
        "drivers/irqchip/irq-hip04.c:hip04_handle_irq",
        "drivers/irqchip/irq-orion.c:orion_handle_irq",
        "drivers/irqchip/irq-omap-intc.c:omap_intc_handle_irq",
        "drivers/irqchip/irq-gic.c:gic_handle_irq",
        "drivers/irqchip/irq-gic-v3.c:gic_handle_irq",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_handle_irq",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_handle_msi_irq",
        "drivers/irqchip/irq-rda-intc.c:rda_handle_irq",
        "drivers/irqchip/irq-aspeed-vic.c:avic_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225195936,
      "name": "__handle_domain_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int __handle_domain_irq(struct irq_domain * domain, unsigned int hwirq, bool lookup, struct pt_regs * regs)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int __handle_domain_irq(struct irq_domain * domain, unsigned int hwirq, bool lookup, struct pt_regs * regs)
```
</details>
</li>
</ul>
