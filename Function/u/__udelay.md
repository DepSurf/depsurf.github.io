# Function: <code>__udelay</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs)
```

```json
{
  "name": "__udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582999808,
      "name": "__udelay",
      "external": true,
      "loc": "arch/x86/lib/delay.c:171",
      "file": "arch/x86/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/apei/erst.c:erst_exec_stall",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/cpufreq/powernow-k8.c:write_new_fid",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582999808,
      "name": "__udelay",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs)
```

```json
{
  "name": "__udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583289552,
      "name": "__udelay",
      "external": true,
      "loc": "arch/x86/lib/delay.c:171",
      "file": "arch/x86/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/apei/erst.c:erst_exec_stall",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/cpufreq/powernow-k8.c:write_new_fid",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583289552,
      "name": "__udelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void __udelay(long unsigned int usecs)
```

```json
{
  "name": "__udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583408208,
      "name": "__udelay",
      "external": true,
      "loc": "arch/x86/lib/delay.c:171",
      "file": "arch/x86/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/apei/erst.c:erst_exec_stall",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/cpufreq/powernow-k8.c:write_new_fid",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583408208,
      "name": "__udelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void __udelay(long unsigned int usecs)
```

```json
{
  "name": "__udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588265328,
      "name": "__udelay",
      "external": true,
      "loc": "arch/x86/lib/delay.c:178",
      "file": "arch/x86/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/apei/erst.c:erst_exec_stall",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588265328,
      "name": "__udelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void __udelay(long unsigned int usecs)
```

```json
{
  "name": "__udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588817872,
      "name": "__udelay",
      "external": true,
      "loc": "arch/x86/lib/delay.c:179",
      "file": "arch/x86/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/apei/erst.c:erst_exec_stall",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588817872,
      "name": "__udelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void __udelay(long unsigned int usecs)
```

```json
{
  "name": "__udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589196096,
      "name": "__udelay",
      "external": true,
      "loc": "arch/x86/lib/delay.c:179",
      "file": "arch/x86/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/apei/erst.c:erst_exec_stall",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/cpufreq/powernow-k8.c:write_new_fid",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589196096,
      "name": "__udelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void __udelay(long unsigned int usecs)
```

```json
{
  "name": "__udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589437552,
      "name": "__udelay",
      "external": true,
      "loc": "arch/x86/lib/delay.c:179",
      "file": "arch/x86/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/apei/erst.c:erst_exec_stall",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/cpufreq/powernow-k8.c:write_new_fid",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589437552,
      "name": "__udelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void __udelay(long unsigned int usecs)
```

```json
{
  "name": "__udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589895488,
      "name": "__udelay",
      "external": true,
      "loc": "arch/x86/lib/delay.c:179",
      "file": "arch/x86/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/apei/erst.c:erst_exec_stall",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/cpufreq/powernow-k8.c:write_new_fid",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589895488,
      "name": "__udelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __udelay(long unsigned int usecs)
```

```json
{
  "name": "__udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590121472,
      "name": "__udelay",
      "external": true,
      "loc": "arch/x86/lib/delay.c:179",
      "file": "arch/x86/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/apei/erst.c:erst_exec_stall",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/cpufreq/powernow-k8.c:write_new_fid",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590121472,
      "name": "__udelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __udelay(long unsigned int usecs)
```

```json
{
  "name": "__udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585125520,
      "name": "__udelay",
      "external": true,
      "loc": "arch/x86/lib/delay.c:221",
      "file": "arch/x86/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/apei/erst.c:erst_exec_stall",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/base/regmap/regmap.c:_regmap_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition",
        "drivers/cpufreq/powernow-k8.c:write_new_fid",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585125520,
      "name": "__udelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __udelay(long unsigned int usecs)
```

```json
{
  "name": "__udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585276352,
      "name": "__udelay",
      "external": true,
      "loc": "arch/x86/lib/delay.c:221",
      "file": "arch/x86/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/apei/erst.c:erst_exec_stall",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/base/regmap/regmap.c:_regmap_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/early/xhci-dbc.c:handshake",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition",
        "drivers/cpufreq/powernow-k8.c:write_new_fid",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585276352,
      "name": "__udelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __udelay(long unsigned int usecs)
```

```json
{
  "name": "__udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585159840,
      "name": "__udelay",
      "external": true,
      "loc": "arch/x86/lib/delay.c:221",
      "file": "arch/x86/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/apei/erst.c:erst_exec_stall",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/base/regmap/regmap.c:_regmap_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition",
        "drivers/cpufreq/powernow-k8.c:write_new_fid",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585159840,
      "name": "__udelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __udelay(long unsigned int usecs)
```

```json
{
  "name": "__udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585612688,
      "name": "__udelay",
      "external": true,
      "loc": "arch/x86/lib/delay.c:221",
      "file": "arch/x86/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/apei/erst.c:erst_exec_stall",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/base/regmap/regmap.c:_regmap_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition",
        "drivers/cpufreq/powernow-k8.c:write_new_fid",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585612688,
      "name": "__udelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __udelay(long unsigned int usecs)
```

```json
{
  "name": "__udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586769536,
      "name": "__udelay",
      "external": true,
      "loc": "arch/x86/lib/delay.c:221",
      "file": "arch/x86/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "kernel/rcu/srcutree.c:try_check_zero",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/apei/erst.c:erst_exec_stall",
        "drivers/regulator/core.c:_regulator_delay_helper",
        "drivers/base/regmap/regmap.c:_regmap_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition",
        "drivers/cpufreq/powernow-k8.c:write_new_fid",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586769536,
      "name": "__udelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __udelay(long unsigned int usecs)
```

```json
{
  "name": "__udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595934736,
      "name": "__udelay",
      "external": true,
      "loc": "arch/x86/lib/delay.c:221",
      "file": "arch/x86/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "kernel/rcu/srcutree.c:try_check_zero",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/apei/erst.c:erst_exec_stall",
        "drivers/regulator/core.c:_regulator_delay_helper",
        "drivers/base/regmap/regmap.c:_regmap_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition",
        "drivers/cpufreq/powernow-k8.c:write_new_fid",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595934736,
      "name": "__udelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __udelay(long unsigned int usecs)
```

```json
{
  "name": "__udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596453152,
      "name": "__udelay",
      "external": true,
      "loc": "arch/x86/lib/delay.c:221",
      "file": "arch/x86/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:send_init_sequence",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "kernel/rcu/srcutree.c:try_check_zero",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/apei/erst.c:erst_exec_stall",
        "drivers/regulator/core.c:_regulator_delay_helper",
        "drivers/base/regmap/regmap.c:_regmap_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition",
        "drivers/cpufreq/powernow-k8.c:write_new_fid",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596453152,
      "name": "__udelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __udelay(long unsigned int usecs)
```

```json
{
  "name": "__udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597348176,
      "name": "__udelay",
      "external": true,
      "loc": "arch/x86/lib/delay.c:221",
      "file": "arch/x86/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "kernel/rcu/srcutree.c:try_check_zero",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/apei/erst.c:erst_exec_stall",
        "drivers/regulator/core.c:_regulator_delay_helper",
        "drivers/base/regmap/regmap.c:_regmap_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition",
        "drivers/cpufreq/powernow-k8.c:write_new_fid",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597348176,
      "name": "__udelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __udelay(long unsigned int usecs)
```

```json
{
  "name": "__udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503797872,
      "name": "__udelay",
      "external": true,
      "loc": "arch/arm64/lib/delay.c:49",
      "file": "arch/arm64/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/apei/erst.c:erst_exec_stall",
        "drivers/clk/actions/owl-pll.c:owl_pll_set_rate",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_set_params",
        "drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_notifier_cb",
        "drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_notifier_cb",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/iommu/arm-smmu.c:__arm_smmu_tlb_sync",
        "drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503797872,
      "name": "__udelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void __udelay(long unsigned int usecs)
```

```json
{
  "name": "__udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589723728,
      "name": "__udelay",
      "external": true,
      "loc": "arch/x86/lib/delay.c:179",
      "file": "arch/x86/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/cpufreq/powernow-k8.c:write_new_fid",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589723728,
      "name": "__udelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __udelay(long unsigned int usecs)
```

```json
{
  "name": "__udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589449504,
      "name": "__udelay",
      "external": true,
      "loc": "arch/x86/lib/delay.c:179",
      "file": "arch/x86/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/apei/erst.c:erst_exec_stall",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/cpufreq/powernow-k8.c:write_new_fid",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource",
        "drivers/hv/connection.c:vmbus_post_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589449504,
      "name": "__udelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __udelay(long unsigned int usecs)
```

```json
{
  "name": "__udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590167104,
      "name": "__udelay",
      "external": true,
      "loc": "arch/x86/lib/delay.c:179",
      "file": "arch/x86/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/apei/erst.c:erst_exec_stall",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/cpufreq/powernow-k8.c:write_new_fid",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590167104,
      "name": "__udelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __udelay(long unsigned int usecs)
```

```json
{
  "name": "__udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590217504,
      "name": "__udelay",
      "external": true,
      "loc": "arch/x86/lib/delay.c:179",
      "file": "arch/x86/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/cppc_acpi.c:send_pcc_cmd",
        "drivers/acpi/apei/erst.c:erst_exec_stall",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/cpufreq/powernow-k8.c:write_new_fid",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590217504,
      "name": "__udelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __udelay(long unsigned int usecs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __udelay(long unsigned int usecs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __udelay(long unsigned int usecs)
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
