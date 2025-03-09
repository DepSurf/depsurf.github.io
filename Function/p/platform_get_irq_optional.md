# Function: <code>platform_get_irq_optional</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq_optional",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586192288,
      "name": "platform_get_irq_optional",
      "external": true,
      "loc": "drivers/base/platform.c:194",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586192288,
      "name": "platform_get_irq_optional",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq_optional",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586957344,
      "name": "platform_get_irq_optional",
      "external": true,
      "loc": "drivers/base/platform.c:158",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/base/platform.c:platform_irq_count",
        "drivers/base/platform.c:platform_get_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586957344,
      "name": "platform_get_irq_optional",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
int platform_get_irq_optional(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq_optional",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587043104,
      "name": "platform_get_irq_optional",
      "external": true,
      "loc": "drivers/base/platform.c:189",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587043104,
      "name": "platform_get_irq_optional",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq_optional",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586926928,
      "name": "platform_get_irq_optional",
      "external": true,
      "loc": "drivers/base/platform.c:189",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586926928,
      "name": "platform_get_irq_optional",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq_optional",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587488832,
      "name": "platform_get_irq_optional",
      "external": true,
      "loc": "drivers/base/platform.c:169",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587488832,
      "name": "platform_get_irq_optional",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
int platform_get_irq_optional(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq_optional",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588811408,
      "name": "platform_get_irq_optional",
      "external": true,
      "loc": "drivers/base/platform.c:171",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588811408,
      "name": "platform_get_irq_optional",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
int platform_get_irq_optional(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq_optional",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590309344,
      "name": "platform_get_irq_optional",
      "external": true,
      "loc": "drivers/base/platform.c:171",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590309344,
      "name": "platform_get_irq_optional",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
int platform_get_irq_optional(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq_optional",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590629840,
      "name": "platform_get_irq_optional",
      "external": true,
      "loc": "drivers/base/platform.c:171",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590629840,
      "name": "platform_get_irq_optional",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
int platform_get_irq_optional(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq_optional",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590989072,
      "name": "platform_get_irq_optional",
      "external": true,
      "loc": "drivers/base/platform.c:171",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590989072,
      "name": "platform_get_irq_optional",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq_optional",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498994584,
      "name": "platform_get_irq_optional",
      "external": true,
      "loc": "drivers/base/platform.c:194",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498994584,
      "name": "platform_get_irq_optional",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int platform_get_irq_optional(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq_optional",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231562812,
      "name": "platform_get_irq_optional",
      "external": true,
      "loc": "drivers/base/platform.c:194",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231562812,
      "name": "platform_get_irq_optional",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq_optional",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292150544,
      "name": "platform_get_irq_optional",
      "external": true,
      "loc": "drivers/base/platform.c:194",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292150544,
      "name": "platform_get_irq_optional",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int platform_get_irq_optional(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq_optional",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276369166,
      "name": "platform_get_irq_optional",
      "external": true,
      "loc": "drivers/base/platform.c:194",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276369166,
      "name": "platform_get_irq_optional",
      "section": ".text",
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq_optional",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585952496,
      "name": "platform_get_irq_optional",
      "external": true,
      "loc": "drivers/base/platform.c:194",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585952496,
      "name": "platform_get_irq_optional",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq_optional",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585801712,
      "name": "platform_get_irq_optional",
      "external": true,
      "loc": "drivers/base/platform.c:194",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585801712,
      "name": "platform_get_irq_optional",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq_optional",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586142304,
      "name": "platform_get_irq_optional",
      "external": true,
      "loc": "drivers/base/platform.c:194",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586142304,
      "name": "platform_get_irq_optional",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device * dev, unsigned int num)
```

```json
{
  "name": "platform_get_irq_optional",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586250992,
      "name": "platform_get_irq_optional",
      "external": true,
      "loc": "drivers/base/platform.c:194",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586250992,
      "name": "platform_get_irq_optional",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int platform_get_irq_optional(struct platform_device * dev, unsigned int num)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
