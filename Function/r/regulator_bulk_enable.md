# Function: <code>regulator_bulk_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583933056,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:3494",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583933056,
      "name": "regulator_bulk_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584270688,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:3528",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584270688,
      "name": "regulator_bulk_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584452560,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:3592",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584452560,
      "name": "regulator_bulk_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584536864,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:3615",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536864,
      "name": "regulator_bulk_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584947104,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:3623",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584947104,
      "name": "regulator_bulk_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:3797",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585188868,
      "name": "regulator_bulk_enable.cold.62",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071585177120,
      "name": "regulator_bulk_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585295906,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:4422",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585305090,
      "name": "regulator_bulk_enable.cold.67",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071585295760,
      "name": "regulator_bulk_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:4447",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585517307,
      "name": "regulator_bulk_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585506304,
      "name": "regulator_bulk_enable",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:4457",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585658658,
      "name": "regulator_bulk_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585648960,
      "name": "regulator_bulk_enable",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:4506",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586383686,
      "name": "regulator_bulk_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586374896,
      "name": "regulator_bulk_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:4644",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591455816,
      "name": "regulator_bulk_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071586492608,
      "name": "regulator_bulk_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:4646",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591397603,
      "name": "regulator_bulk_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071586375632,
      "name": "regulator_bulk_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:4783",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592442605,
      "name": "regulator_bulk_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071586898864,
      "name": "regulator_bulk_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:4828",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594310847,
      "name": "regulator_bulk_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588189072,
      "name": "regulator_bulk_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589590736,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:4868",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589590736,
      "name": "regulator_bulk_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589892768,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:4934",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589892768,
      "name": "regulator_bulk_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590230400,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:4956",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590230400,
      "name": "regulator_bulk_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498310416,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:4457",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498310416,
      "name": "regulator_bulk_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230991532,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:4457",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230991532,
      "name": "regulator_bulk_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291481680,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:4457",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291481680,
      "name": "regulator_bulk_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276001218,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:4457",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276001218,
      "name": "regulator_bulk_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:4457",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585419579,
      "name": "regulator_bulk_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585409568,
      "name": "regulator_bulk_enable",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:4457",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585289730,
      "name": "regulator_bulk_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585280032,
      "name": "regulator_bulk_enable",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:4457",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585609058,
      "name": "regulator_bulk_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585599360,
      "name": "regulator_bulk_enable",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:4457",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585717186,
      "name": "regulator_bulk_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585707488,
      "name": "regulator_bulk_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
