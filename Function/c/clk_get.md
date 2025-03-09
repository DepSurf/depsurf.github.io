# Function: <code>clk_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586070048,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:197",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_add_alias"
      ],
      "caller_func": [
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/clk/clk-devres.c:devm_clk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586070048,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586480982,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:197",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_add_alias"
      ],
      "caller_func": [
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/clk/clk-devres.c:devm_clk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586480464,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584287686,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:197",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_add_alias"
      ],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/mfd/twl-core.c:twl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584287168,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584366784,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:197",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_add_alias"
      ],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk-bulk.c:clk_bulk_get",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/mfd/twl-core.c:twl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584366256,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584772560,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:197",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_add_alias"
      ],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk-bulk.c:clk_bulk_get",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_get_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584772032,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585000773,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:197",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_add_alias"
      ],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_get_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585000256,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585105429,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:194",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_add_alias"
      ],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/opp/core.c:dev_pm_opp_set_clkname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585105008,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585311397,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:100",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_add_alias"
      ],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk-bulk.c:__clk_bulk_get",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/opp/core.c:dev_pm_opp_set_clkname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585311344,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585449333,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:100",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_add_alias"
      ],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk-bulk.c:__clk_bulk_get",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/opp/core.c:dev_pm_opp_set_clkname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585449280,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586165968,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:100",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk-bulk.c:__clk_bulk_get",
        "drivers/clk/clkdev.c:clk_add_alias",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/mfd/twl-core.c:clocks_init",
        "drivers/opp/core.c:dev_pm_opp_set_clkname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586165968,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586283040,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:100",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk-bulk.c:__clk_bulk_get",
        "drivers/clk/clkdev.c:clk_add_alias",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/mfd/twl-core.c:clocks_init",
        "drivers/opp/core.c:dev_pm_opp_set_clkname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586283040,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586156816,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:100",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk-bulk.c:__clk_bulk_get",
        "drivers/clk/clkdev.c:clk_add_alias",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:_add_opp_table_indexed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586156816,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586658416,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:100",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk-bulk.c:__clk_bulk_get",
        "drivers/clk/clkdev.c:clk_add_alias",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:_add_opp_table_indexed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586658416,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587926480,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:100",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk-bulk.c:__clk_bulk_get",
        "drivers/clk/clkdev.c:clk_add_alias",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:_add_opp_table_indexed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587926480,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589281480,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:100",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_add_alias"
      ],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get_optional_enabled",
        "drivers/clk/clk-devres.c:devm_clk_get_optional_prepared",
        "drivers/clk/clk-devres.c:devm_clk_get_optional",
        "drivers/clk/clk-devres.c:devm_clk_get_enabled",
        "drivers/clk/clk-bulk.c:__clk_bulk_get",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_gen_context",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/opp/core.c:dev_pm_opp_set_config",
        "drivers/opp/core.c:_add_opp_table_indexed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589281264,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589578120,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:100",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_add_alias"
      ],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get_optional_enabled",
        "drivers/clk/clk-devres.c:devm_clk_get_optional_prepared",
        "drivers/clk/clk-devres.c:devm_clk_get_optional",
        "drivers/clk/clk-devres.c:devm_clk_get_enabled",
        "drivers/clk/clk-bulk.c:__clk_bulk_get",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_gen_context",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/opp/core.c:dev_pm_opp_set_config",
        "drivers/opp/core.c:_add_opp_table_indexed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589577904,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589887560,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:100",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_add_alias"
      ],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get_optional_enabled",
        "drivers/clk/clk-devres.c:devm_clk_get_optional_prepared",
        "drivers/clk/clk-devres.c:devm_clk_get_optional",
        "drivers/clk/clk-devres.c:devm_clk_get_enabled",
        "drivers/clk/clk-bulk.c:__clk_bulk_get",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_gen_context",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/opp/core.c:dev_pm_opp_set_config",
        "drivers/opp/core.c:_add_opp_table_indexed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589887344,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497738360,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:100",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-xgene.c:xgene_phy_probe",
        "drivers/pci/controller/pci-xgene.c:xgene_pcie_probe",
        "drivers/video/fbdev/amba-clcd.c:clcdfb_register",
        "drivers/video/fbdev/mx3fb.c:sdc_init_panel",
        "drivers/amba/bus.c:amba_get_enable_pclk",
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk-bulk.c:__clk_bulk_get",
        "drivers/clk/clkdev.c:clk_add_alias",
        "drivers/clk/mvebu/armada-37xx-tbg.c:armada_3700_tbg_clock_probe",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/ata/libahci_platform.c:ahci_platform_get_resources",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:_opp_get_opp_table",
        "drivers/cpufreq/cpufreq-dt.c:cpufreq_init",
        "drivers/clocksource/sh_cmt.c:sh_cmt_setup",
        "drivers/clocksource/sh_tmu.c:sh_tmu_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497738360,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230560556,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:100",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-omap2/io.c:omap_sdrc_init",
        "arch/arm/mach-omap2/timer.c:realtime_counter_init",
        "arch/arm/mach-omap2/timer.c:omap_dm_timer_init_one",
        "arch/arm/mach-omap2/timer.c:omap_dm_timer_init_one",
        "arch/arm/mach-omap2/voltage.c:omap_voltage_late_init",
        "drivers/bus/ti-sysc.c:sysc_notifier_call",
        "drivers/bus/ti-sysc.c:sysc_notifier_call",
        "drivers/video/fbdev/amba-clcd.c:clcdfb_probe",
        "drivers/video/fbdev/mx3fb.c:__set_par",
        "drivers/amba/bus.c:amba_get_enable_pclk",
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk-bulk.c:__clk_bulk_get",
        "drivers/clk/clkdev.c:clk_add_alias",
        "drivers/clk/ti/clk.c:omap2_clk_enable_init_clocks",
        "drivers/clk/ti/clk-814x.c:dm814x_adpll_enable_init_clocks",
        "drivers/clk/ti/clk-3xxx.c:omap3_clk_lock_dpll5",
        "drivers/clk/ti/clk-3xxx.c:omap3_clk_lock_dpll5",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/mfd/t7l66xb.c:t7l66xb_probe",
        "drivers/mfd/t7l66xb.c:t7l66xb_probe",
        "drivers/mfd/tc6387xb.c:tc6387xb_probe",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/omap-usb-tll.c:usbtll_omap_probe",
        "drivers/ata/libahci_platform.c:ahci_platform_get_resources",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/power/avs/smartreflex.c:sr_set_clk_length",
        "drivers/power/avs/smartreflex.c:sr_set_clk_length",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:_opp_get_opp_table",
        "drivers/cpufreq/cpufreq-dt.c:cpufreq_init",
        "drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init",
        "drivers/cpufreq/omap-cpufreq.c:omap_cpu_init",
        "drivers/clocksource/sh_cmt.c:sh_cmt_setup",
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_setup",
        "drivers/clocksource/sh_tmu.c:sh_tmu_setup",
        "drivers/clocksource/timer-ti-dm.c:_omap_dm_timer_request",
        "drivers/clocksource/timer-ti-dm.c:_omap_dm_timer_request",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_source",
        "sound/soc/fsl/imx-sgtl5000.c:imx_sgtl5000_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230560556,
      "name": "clk_get",
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "clk_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_get",
      "external": false,
      "loc": "include/linux/clk.h:745",
      "file": "drivers/base/regmap/regmap-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clk_get",
      "external": false,
      "loc": "include/linux/clk.h:745",
      "file": "drivers/mfd/twl-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clk_get",
      "external": false,
      "loc": "include/linux/clk.h:745",
      "file": "drivers/opp/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275882272,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:100",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk-bulk.c:__clk_bulk_get",
        "drivers/clk/clkdev.c:clk_add_alias",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:_opp_get_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275882272,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585211861,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:100",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_add_alias"
      ],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk-bulk.c:__clk_bulk_get",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/opp/core.c:dev_pm_opp_set_clkname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585211808,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585164069,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:100",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_add_alias"
      ],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk-bulk.c:__clk_bulk_get",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/opp/core.c:dev_pm_opp_set_clkname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585164016,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585399733,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:100",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_add_alias"
      ],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk-bulk.c:__clk_bulk_get",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/opp/core.c:dev_pm_opp_set_clkname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585399680,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct clk * clk_get(struct device * dev, const char * con_id)
```

```json
{
  "name": "clk_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585507077,
      "name": "clk_get",
      "external": true,
      "loc": "drivers/clk/clkdev.c:100",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_add_alias"
      ],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk-bulk.c:__clk_bulk_get",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/opp/core.c:dev_pm_opp_set_clkname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585507024,
      "name": "clk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct clk * clk_get(struct device * dev, const char * con_id)
```
</details>
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
