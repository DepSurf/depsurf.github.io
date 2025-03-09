# Function: <code>dev_pm_domain_set</code>

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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584770528,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:144",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/base/power/domain.c:__pm_genpd_add_device",
        "drivers/base/power/domain.c:genpd_free_dev_data",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_optimus_hdmi_audio",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_optimus_hdmi_audio",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584770528,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584960928,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:144",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/base/power/domain.c:__pm_genpd_add_device",
        "drivers/base/power/domain.c:genpd_free_dev_data",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_optimus_hdmi_audio",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_optimus_hdmi_audio",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584960928,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585045600,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:144",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/base/power/domain.c:pm_genpd_remove_device",
        "drivers/base/power/domain.c:__pm_genpd_add_device",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_optimus_hdmi_audio",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_optimus_hdmi_audio",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585045600,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585468416,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:144",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/base/power/domain.c:pm_genpd_remove_device",
        "drivers/base/power/domain.c:__pm_genpd_add_device",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_optimus_hdmi_audio",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_optimus_hdmi_audio",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585468416,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585712272,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:185",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/base/power/domain.c:pm_genpd_remove_device",
        "drivers/base/power/domain.c:pm_genpd_add_device",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585712272,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585844096,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:202",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/base/power/domain.c:pm_genpd_remove_device",
        "drivers/base/power/domain.c:pm_genpd_add_device",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585844096,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586080304,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:200",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/base/power/domain.c:pm_genpd_remove_device",
        "drivers/base/power/domain.c:pm_genpd_add_device",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586080304,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586228736,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:200",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/base/power/domain.c:pm_genpd_remove_device",
        "drivers/base/power/domain.c:pm_genpd_add_device",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586228736,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586994544,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:220",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/base/power/domain.c:genpd_remove_device",
        "drivers/base/power/domain.c:genpd_add_device",
        "drivers/base/power/clock_ops.c:pm_clk_notify",
        "drivers/base/power/clock_ops.c:pm_clk_notify",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586994544,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587079296,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:220",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/base/power/domain.c:genpd_remove_device",
        "drivers/base/power/domain.c:genpd_add_device",
        "drivers/base/power/clock_ops.c:pm_clk_notify",
        "drivers/base/power/clock_ops.c:pm_clk_notify",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587079296,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586965568,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:220",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/base/power/domain.c:genpd_remove_device",
        "drivers/base/power/domain.c:genpd_add_device",
        "drivers/base/power/clock_ops.c:pm_clk_notify",
        "drivers/base/power/clock_ops.c:pm_clk_notify",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586965568,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587531712,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:220",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/base/power/domain.c:genpd_remove_device",
        "drivers/base/power/domain.c:genpd_add_device",
        "drivers/base/power/clock_ops.c:pm_clk_notify",
        "drivers/base/power/clock_ops.c:pm_clk_notify",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587531712,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588862736,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:220",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/base/power/domain.c:genpd_remove_device",
        "drivers/base/power/domain.c:genpd_add_device",
        "drivers/base/power/clock_ops.c:pm_clk_notify",
        "drivers/base/power/clock_ops.c:pm_clk_notify",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588862736,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590369824,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:220",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/base/power/domain.c:genpd_remove_device",
        "drivers/base/power/domain.c:genpd_add_device",
        "drivers/base/power/clock_ops.c:pm_clk_notify",
        "drivers/base/power/clock_ops.c:pm_clk_notify",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590369824,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590690320,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:220",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/base/power/domain.c:genpd_remove_device",
        "drivers/base/power/domain.c:genpd_add_device",
        "drivers/base/power/clock_ops.c:pm_clk_notify",
        "drivers/base/power/clock_ops.c:pm_clk_notify",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590690320,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591051856,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:220",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/pmdomain/core.c:genpd_remove_device",
        "drivers/pmdomain/core.c:genpd_add_device",
        "drivers/base/power/clock_ops.c:pm_clk_notify",
        "drivers/base/power/clock_ops.c:pm_clk_notify",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591051856,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499040808,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:200",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/base/power/domain.c:genpd_remove_device",
        "drivers/base/power/domain.c:genpd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499040808,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231599548,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:200",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-omap2/omap_device.c:omap_device_register",
        "arch/arm/mach-omap2/omap_device.c:omap_device_build_from_dt",
        "arch/arm/mach-omap2/omap_device.c:omap_device_build_from_dt",
        "drivers/bus/ti-sysc.c:sysc_notifier_call",
        "drivers/base/power/domain.c:genpd_remove_device",
        "drivers/base/power/domain.c:genpd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231599548,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292212160,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:200",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_remove_device",
        "drivers/base/power/domain.c:genpd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292212160,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276401578,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:200",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_remove_device",
        "drivers/base/power/domain.c:genpd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276401578,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585988944,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:200",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/base/power/domain.c:pm_genpd_remove_device",
        "drivers/base/power/domain.c:pm_genpd_add_device",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585988944,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585838208,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:200",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/base/power/domain.c:pm_genpd_remove_device",
        "drivers/base/power/domain.c:pm_genpd_add_device",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585838208,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586178752,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:200",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/base/power/domain.c:pm_genpd_remove_device",
        "drivers/base/power/domain.c:pm_genpd_add_device",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586178752,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
```

```json
{
  "name": "dev_pm_domain_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586287472,
      "name": "dev_pm_domain_set",
      "external": true,
      "loc": "drivers/base/power/common.c:200",
      "file": "drivers/base/power/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/base/power/domain.c:pm_genpd_remove_device",
        "drivers/base/power/domain.c:pm_genpd_add_device",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_fini_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_init_domain_pm_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586287472,
      "name": "dev_pm_domain_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void dev_pm_domain_set(struct device * dev, struct dev_pm_domain * pd)
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
