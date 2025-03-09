# Function: <code>regulator_set_voltage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583938096,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:2951",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr",
        "drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583938096,
      "name": "regulator_set_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584268048,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:2967",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584268048,
      "name": "regulator_set_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584449872,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:3003",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584449872,
      "name": "regulator_set_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584533504,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:3026",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584533504,
      "name": "regulator_set_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584943728,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:3034",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584943728,
      "name": "regulator_set_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585173616,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:3123",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585173616,
      "name": "regulator_set_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585294720,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:3729",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585294720,
      "name": "regulator_set_voltage",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585503968,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:3749",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585503968,
      "name": "regulator_set_voltage",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585655488,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:3758",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585655488,
      "name": "regulator_set_voltage",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586381248,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:3798",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586381248,
      "name": "regulator_set_voltage",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586499216,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:3928",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586499216,
      "name": "regulator_set_voltage",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586382640,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:3926",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586382640,
      "name": "regulator_set_voltage",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586906448,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:4026",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586906448,
      "name": "regulator_set_voltage",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588197776,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:4068",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588197776,
      "name": "regulator_set_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589602192,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:4098",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_config_regulator_single",
        "drivers/opp/core.c:_opp_config_regulator_single",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589602192,
      "name": "regulator_set_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589905536,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:4164",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_config_regulator_single",
        "drivers/opp/core.c:_opp_config_regulator_single",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589905536,
      "name": "regulator_set_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590243456,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:4170",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_config_regulator_single",
        "drivers/opp/core.c:_opp_config_regulator_single",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590243456,
      "name": "regulator_set_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498317648,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:3758",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/soc/imx/gpcv2.c:imx_pgc_domain_probe",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr",
        "drivers/mmc/host/mmci.c:mmci_sig_volt_switch",
        "drivers/mmc/host/mmci.c:mmci_sig_volt_switch",
        "drivers/mmc/host/mmci.c:mmci_sig_volt_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498317648,
      "name": "regulator_set_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230998876,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:3758",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/soc/imx/gpcv2.c:imx_pgc_domain_probe",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/opp/ti-opp-supply.c:_opp_set_voltage",
        "drivers/opp/ti-opp-supply.c:_opp_set_voltage",
        "drivers/cpufreq/omap-cpufreq.c:omap_target",
        "drivers/cpufreq/omap-cpufreq.c:omap_target",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr",
        "drivers/mmc/host/mmci.c:mmci_sig_volt_switch",
        "drivers/mmc/host/mmci.c:mmci_sig_volt_switch",
        "drivers/mmc/host/mmci.c:mmci_sig_volt_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230998876,
      "name": "regulator_set_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291492384,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:3758",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291492384,
      "name": "regulator_set_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276007834,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:3758",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276007834,
      "name": "regulator_set_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585416480,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:3758",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585416480,
      "name": "regulator_set_voltage",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585286560,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:3758",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/opp/core.c:_set_opp_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585286560,
      "name": "regulator_set_voltage",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585605888,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:3758",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585605888,
      "name": "regulator_set_voltage",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator * regulator, int min_uV, int max_uV)
```

```json
{
  "name": "regulator_set_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585714016,
      "name": "regulator_set_voltage",
      "external": true,
      "loc": "drivers/regulator/core.c:3758",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/opp/core.c:_set_opp_voltage",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585714016,
      "name": "regulator_set_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
