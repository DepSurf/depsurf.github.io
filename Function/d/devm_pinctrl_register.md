# Function: <code>devm_pinctrl_register</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583462512,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1904",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583462512,
      "name": "devm_pinctrl_register",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583590240,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1904",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583590240,
      "name": "devm_pinctrl_register",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583629376,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2202",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583629376,
      "name": "devm_pinctrl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583875584,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2211",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583875584,
      "name": "devm_pinctrl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584076208,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2160",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584076208,
      "name": "devm_pinctrl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584160784,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2188",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584160784,
      "name": "devm_pinctrl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584350672,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2177",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584350672,
      "name": "devm_pinctrl_register",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584485520,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2204",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584485520,
      "name": "devm_pinctrl_register",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585151200,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2201",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585151200,
      "name": "devm_pinctrl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585302512,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2224",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585302512,
      "name": "devm_pinctrl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585186512,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2248",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585186512,
      "name": "devm_pinctrl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585640400,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2250",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585640400,
      "name": "devm_pinctrl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586801360,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2250",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586801360,
      "name": "devm_pinctrl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587937968,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2249",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587937968,
      "name": "devm_pinctrl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588212208,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2258",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588212208,
      "name": "devm_pinctrl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588505008,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2272",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588505008,
      "name": "devm_pinctrl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496503920,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2204",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinctrl_probe",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pinctrl_probe",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_register",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe",
        "drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe_regmap",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496503920,
      "name": "devm_pinctrl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229809852,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2204",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pinctrl_probe",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_probe",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_legacy_probe",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe",
        "drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe_regmap",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_pinctrl_probe",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_probe",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_pinctrl_probe",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229809852,
      "name": "devm_pinctrl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290715984,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2204",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290715984,
      "name": "devm_pinctrl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275422658,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2204",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275422658,
      "name": "devm_pinctrl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584454272,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2204",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584454272,
      "name": "devm_pinctrl_register",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584389952,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2204",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584389952,
      "name": "devm_pinctrl_register",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584437184,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2204",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584437184,
      "name": "devm_pinctrl_register",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```

```json
{
  "name": "devm_pinctrl_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584543312,
      "name": "devm_pinctrl_register",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2204",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584543312,
      "name": "devm_pinctrl_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct pinctrl_dev * devm_pinctrl_register(struct device * dev, struct pinctrl_desc * pctldesc, void * driver_data)
```
</details>
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
