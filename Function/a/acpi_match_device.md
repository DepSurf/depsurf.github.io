# Function: <code>acpi_match_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```

```json
{
  "name": "acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583558590,
      "name": "acpi_match_device",
      "external": true,
      "loc": "drivers/acpi/bus.c:667",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/mfd/axp20x.c:axp20x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583558590,
      "name": "acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```

```json
{
  "name": "acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583880213,
      "name": "acpi_match_device",
      "external": true,
      "loc": "drivers/acpi/bus.c:743",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583880213,
      "name": "acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```

```json
{
  "name": "acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584019267,
      "name": "acpi_match_device",
      "external": true,
      "loc": "drivers/acpi/bus.c:753",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584019267,
      "name": "acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```

```json
{
  "name": "acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584072464,
      "name": "acpi_match_device",
      "external": true,
      "loc": "drivers/acpi/bus.c:781",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/char/tpm/tpm_tis.c:check_acpi_tpm2",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_match_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584072464,
      "name": "acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```

```json
{
  "name": "acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584342320,
      "name": "acpi_match_device",
      "external": true,
      "loc": "drivers/acpi/bus.c:808",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cannonlake.c:cnl_pinctrl_probe",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/char/tpm/tpm_tis.c:check_acpi_tpm2",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_match_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584342320,
      "name": "acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```

```json
{
  "name": "acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584563088,
      "name": "acpi_match_device",
      "external": true,
      "loc": "drivers/acpi/bus.c:823",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/acpi/bus.c:acpi_device_get_match_data",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/char/tpm/tpm_tis.c:check_acpi_tpm2",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_match_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584563088,
      "name": "acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```

```json
{
  "name": "acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584660400,
      "name": "acpi_match_device",
      "external": true,
      "loc": "drivers/acpi/bus.c:792",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/acpi/bus.c:acpi_device_get_match_data",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/char/tpm/tpm_tis.c:check_acpi_tpm2",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_match_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584660400,
      "name": "acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```

```json
{
  "name": "acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584860448,
      "name": "acpi_match_device",
      "external": true,
      "loc": "drivers/acpi/bus.c:779",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/char/tpm/tpm_tis.c:check_acpi_tpm2",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_match_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584860448,
      "name": "acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```

```json
{
  "name": "acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584996320,
      "name": "acpi_match_device",
      "external": true,
      "loc": "drivers/acpi/bus.c:779",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/char/tpm/tpm_tis.c:check_acpi_tpm2",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_match_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584996320,
      "name": "acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```

```json
{
  "name": "acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585694959,
      "name": "acpi_match_device",
      "external": true,
      "loc": "drivers/acpi/bus.c:779",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_device_get_match_data"
      ],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/char/tpm/tpm_tis.c:check_acpi_tpm2",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_match_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585694672,
      "name": "acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```

```json
{
  "name": "acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585817103,
      "name": "acpi_match_device",
      "external": true,
      "loc": "drivers/acpi/bus.c:784",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_device_get_match_data"
      ],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/char/tpm/tpm_tis.c:check_acpi_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585816816,
      "name": "acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```

```json
{
  "name": "acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585697423,
      "name": "acpi_match_device",
      "external": true,
      "loc": "drivers/acpi/bus.c:863",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_device_get_match_data"
      ],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/char/tpm/tpm_tis.c:check_acpi_tpm2",
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585697120,
      "name": "acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```

```json
{
  "name": "acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586177743,
      "name": "acpi_match_device",
      "external": true,
      "loc": "drivers/acpi/bus.c:865",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_device_get_match_data"
      ],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/char/tpm/tpm_tis.c:check_acpi_tpm2",
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586177440,
      "name": "acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```

```json
{
  "name": "acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587413087,
      "name": "acpi_match_device",
      "external": true,
      "loc": "drivers/acpi/bus.c:902",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_device_get_match_data"
      ],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/char/tpm/tpm_tis.c:check_acpi_tpm2",
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587412800,
      "name": "acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```

```json
{
  "name": "acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588668991,
      "name": "acpi_match_device",
      "external": true,
      "loc": "drivers/acpi/bus.c:908",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_device_get_match_data"
      ],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/char/tpm/tpm_tis.c:check_acpi_tpm2",
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588668672,
      "name": "acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```

```json
{
  "name": "acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588956719,
      "name": "acpi_match_device",
      "external": true,
      "loc": "drivers/acpi/bus.c:884",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_device_get_match_data"
      ],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/char/tpm/tpm_tis.c:check_acpi_tpm2",
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588956400,
      "name": "acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```

```json
{
  "name": "acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589254015,
      "name": "acpi_match_device",
      "external": true,
      "loc": "drivers/acpi/bus.c:934",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_device_get_match_data"
      ],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/char/tpm/tpm_tis.c:check_acpi_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589253696,
      "name": "acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```

```json
{
  "name": "acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497405688,
      "name": "acpi_match_device",
      "external": true,
      "loc": "drivers/acpi/bus.c:779",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:check_acpi_tpm2",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_match_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497405688,
      "name": "acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```

```json
{
  "name": "acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584940224,
      "name": "acpi_match_device",
      "external": true,
      "loc": "drivers/acpi/bus.c:779",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:check_acpi_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584940224,
      "name": "acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```

```json
{
  "name": "acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584849024,
      "name": "acpi_match_device",
      "external": true,
      "loc": "drivers/acpi/bus.c:779",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/char/tpm/tpm_tis.c:check_acpi_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584849024,
      "name": "acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```

```json
{
  "name": "acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584947904,
      "name": "acpi_match_device",
      "external": true,
      "loc": "drivers/acpi/bus.c:779",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/char/tpm/tpm_tis.c:check_acpi_tpm2",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_match_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584947904,
      "name": "acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```

```json
{
  "name": "acpi_match_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585054080,
      "name": "acpi_match_device",
      "external": true,
      "loc": "drivers/acpi/bus.c:779",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/char/tpm/tpm_tis.c:check_acpi_tpm2",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_match_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585054080,
      "name": "acpi_match_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
const struct acpi_device_id * acpi_match_device(const struct acpi_device_id * ids, const struct device * dev)
```
</details>
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
