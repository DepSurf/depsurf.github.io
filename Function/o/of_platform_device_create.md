# Function: <code>of_platform_device_create</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct platform_device * of_platform_device_create(struct device_node * np, const char * bus_id, struct device * parent)
```

```json
{
  "name": "of_platform_device_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336511300520,
      "name": "of_platform_device_create",
      "external": true,
      "loc": "drivers/of/platform.c:210",
      "file": "drivers/of/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/of/platform.c:of_platform_default_populate_init"
      ],
      "caller_func": [
        "drivers/irqchip/irq-mbigen.c:mbigen_device_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_init",
        "drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_init",
        "drivers/ata/libahci_platform.c:ahci_platform_get_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501614416,
      "name": "of_platform_device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct platform_device * of_platform_device_create(struct device_node * np, const char * bus_id, struct device * parent)
```

```json
{
  "name": "of_platform_device_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243960512,
      "name": "of_platform_device_create",
      "external": true,
      "loc": "drivers/of/platform.c:210",
      "file": "drivers/of/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/of/platform.c:of_platform_default_populate_init"
      ],
      "caller_func": [
        "drivers/video/fbdev/simplefb.c:simplefb_init",
        "drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_init",
        "drivers/ata/libahci_platform.c:ahci_platform_get_resources",
        "drivers/memory/omap-gpmc.c:gpmc_probe_generic_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234137560,
      "name": "of_platform_device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct platform_device * of_platform_device_create(struct device_node * np, const char * bus_id, struct device * parent)
```

```json
{
  "name": "of_platform_device_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295041440,
      "name": "of_platform_device_create",
      "external": true,
      "loc": "drivers/of/platform.c:210",
      "file": "drivers/of/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/opal.c:opal_init",
        "arch/powerpc/platforms/powernv/opal.c:opal_init",
        "arch/powerpc/platforms/powernv/opal.c:opal_init",
        "arch/powerpc/platforms/powernv/opal.c:opal_pdev_init",
        "arch/powerpc/platforms/powernv/opal-rtc.c:__machine_initcall_powernv_opal_time_init",
        "arch/powerpc/platforms/powernv/rng.c:__machine_initcall_powernv_rng_init",
        "arch/powerpc/platforms/powernv/opal-sensor.c:opal_sensor_init",
        "arch/powerpc/platforms/powernv/vas.c:vas_init",
        "drivers/video/fbdev/simplefb.c:simplefb_init",
        "drivers/misc/cxl/base.c:cxl_base_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295041440,
      "name": "of_platform_device_create",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct platform_device * of_platform_device_create(struct device_node * np, const char * bus_id, struct device * parent)
```

```json
{
  "name": "of_platform_device_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270837642,
      "name": "of_platform_device_create",
      "external": true,
      "loc": "drivers/of/platform.c:210",
      "file": "drivers/of/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/of/platform.c:of_platform_default_populate_init"
      ],
      "caller_func": [
        "drivers/video/fbdev/simplefb.c:simplefb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278078322,
      "name": "of_platform_device_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct platform_device * of_platform_device_create(struct device_node * np, const char * bus_id, struct device * parent)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct platform_device * of_platform_device_create(struct device_node * np, const char * bus_id, struct device * parent)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct platform_device * of_platform_device_create(struct device_node * np, const char * bus_id, struct device * parent)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct platform_device * of_platform_device_create(struct device_node * np, const char * bus_id, struct device * parent)
```
</details>
</li>
</ul>
