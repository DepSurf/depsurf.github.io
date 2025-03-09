# Function: <code>generic_handle_domain_irq</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int generic_handle_domain_irq(struct irq_domain * domain, unsigned int hwirq)
```

```json
{
  "name": "generic_handle_domain_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580147072,
      "name": "generic_handle_domain_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:673",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:do_amd_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147072,
      "name": "generic_handle_domain_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int generic_handle_domain_irq(struct irq_domain * domain, unsigned int hwirq)
```

```json
{
  "name": "generic_handle_domain_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580293888,
      "name": "generic_handle_domain_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:702",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:do_amd_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293888,
      "name": "generic_handle_domain_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int generic_handle_domain_irq(struct irq_domain * domain, unsigned int hwirq)
```

```json
{
  "name": "generic_handle_domain_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580504640,
      "name": "generic_handle_domain_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:705",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580504640,
      "name": "generic_handle_domain_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int generic_handle_domain_irq(struct irq_domain * domain, unsigned int hwirq)
```

```json
{
  "name": "generic_handle_domain_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580576720,
      "name": "generic_handle_domain_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:726",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580576720,
      "name": "generic_handle_domain_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int generic_handle_domain_irq(struct irq_domain * domain, unsigned int hwirq)
```

```json
{
  "name": "generic_handle_domain_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580641008,
      "name": "generic_handle_domain_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:726",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580641008,
      "name": "generic_handle_domain_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int generic_handle_domain_irq(struct irq_domain * domain, unsigned int hwirq)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
