# Function: <code>__platform_driver_probe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584407568,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:636",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/rtc/rtc-cmos.c:cmos_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584407568,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584742880,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:656",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/rtc/rtc-cmos.c:cmos_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584742880,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584932896,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:670",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/rtc/rtc-cmos.c:cmos_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584932896,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585017248,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:670",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/rtc/rtc-cmos.c:cmos_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585017248,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585439568,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:670",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/rtc/rtc-cmos.c:cmos_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585439568,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:668",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/rtc/rtc-cmos.c:cmos_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585684922,
      "name": "__platform_driver_probe.cold.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071585683344,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585815130,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:670",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/rtc/rtc-cmos.c:cmos_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585815130,
      "name": "__platform_driver_probe.cold.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071585813488,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586048582,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:710",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/rtc/rtc-cmos.c:cmos_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586048582,
      "name": "__platform_driver_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071586046848,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586196532,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:775",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/rtc/rtc-cmos.c:cmos_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586196532,
      "name": "__platform_driver_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071586194928,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:836",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/rtc/rtc-cmos.c:cmos_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586959086,
      "name": "__platform_driver_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071586954832,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:934",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/rtc/rtc-cmos.c:cmos_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591486713,
      "name": "__platform_driver_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071587039664,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:933",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/rtc/rtc-cmos.c:cmos_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591430393,
      "name": "__platform_driver_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071586923472,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:897",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/rtc/rtc-cmos.c:cmos_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592489505,
      "name": "__platform_driver_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071587485120,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:906",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/rtc/rtc-cmos.c:cmos_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594359158,
      "name": "__platform_driver_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071588807264,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590304896,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:906",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/rtc/rtc-cmos.c:cmos_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590304896,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590625616,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:913",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/rtc/rtc-cmos.c:cmos_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590625616,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590984864,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:913",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/rtc/rtc-cmos.c:cmos_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590984864,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498996352,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:775",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/brcmstb_gisb.c:brcm_gisb_driver_init",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_driver_init",
        "drivers/pwm/pwm-stmpe.c:stmpe_pwm_driver_init",
        "drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_driver_init",
        "drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_driver_init",
        "drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_init",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_init",
        "drivers/dma/mxs-dma.c:mxs_dma_module_init",
        "drivers/dma/ipu/ipu_idmac.c:ipu_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/rtc/rtc-efi.c:efi_rtc_driver_init",
        "drivers/rtc/rtc-mv.c:mv_rtc_driver_init",
        "drivers/firmware/meson/meson_sm.c:meson_sm_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498996352,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231561504,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:775",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/brcmstb_gisb.c:brcm_gisb_driver_init",
        "drivers/gpio/gpio-htc-egpio.c:egpio_init",
        "drivers/pwm/pwm-stmpe.c:stmpe_pwm_driver_init",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_driver_init",
        "drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_driver_init",
        "drivers/video/fbdev/omap2/omapfb/vrfb.c:vrfb_driver_init",
        "drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_init",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_init",
        "drivers/dma/mxs-dma.c:mxs_dma_module_init",
        "drivers/dma/ipu/ipu_idmac.c:ipu_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/mfd/asic3.c:asic3_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/auxdisplay/arm-charlcd.c:charlcd_driver_init",
        "drivers/rtc/rtc-efi.c:efi_rtc_driver_init",
        "drivers/rtc/rtc-mv.c:mv_rtc_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231561504,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292148480,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:775",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/opal-secvar.c:opal_secvar_init",
        "drivers/pwm/pwm-stmpe.c:stmpe_pwm_driver_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/rtc/rtc-generic.c:generic_rtc_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292148480,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276367856,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:775",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-stmpe.c:stmpe_pwm_driver_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276367856,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585956740,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:775",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/rtc/rtc-cmos.c:cmos_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585956740,
      "name": "__platform_driver_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071585955136,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585805956,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:775",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/rtc/rtc-cmos.c:cmos_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585805956,
      "name": "__platform_driver_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071585804352,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586146548,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:775",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/rtc/rtc-cmos.c:cmos_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586146548,
      "name": "__platform_driver_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071586144944,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __platform_driver_probe(struct platform_driver * drv, int (*)(struct platform_device *) probe, struct module * module)
```

```json
{
  "name": "__platform_driver_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586255252,
      "name": "__platform_driver_probe",
      "external": true,
      "loc": "drivers/base/platform.c:775",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/rtc/rtc-cmos.c:cmos_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586255252,
      "name": "__platform_driver_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071586253632,
      "name": "__platform_driver_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
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
