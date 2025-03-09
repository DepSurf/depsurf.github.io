# Function: <code>class_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584402480,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:212",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_class.c:firmware_class_exit",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/input/input.c:input_exit",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/thermal/thermal_core.c:thermal_exit",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "net/rfkill/core.c:rfkill_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584402480,
      "name": "class_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584737840,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:212",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_class.c:firmware_class_exit",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_exit",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/thermal/thermal_core.c:thermal_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "net/rfkill/core.c:rfkill_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584737840,
      "name": "class_unregister",
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
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584927712,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:226",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_class.c:firmware_class_exit",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_exit",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/thermal/thermal_core.c:thermal_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "net/rfkill/core.c:rfkill_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584927712,
      "name": "class_unregister",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585012480,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:194",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_class.c:firmware_class_exit",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/input/input.c:input_exit",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/thermal/thermal_core.c:thermal_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "net/rfkill/core.c:rfkill_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585012480,
      "name": "class_unregister",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585434736,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:194",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_class.c:firmware_class_exit",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/input/input.c:input_exit",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/thermal/thermal_core.c:thermal_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "net/rfkill/core.c:rfkill_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585434736,
      "name": "class_unregister",
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
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585677904,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:192",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/thermal/thermal_core.c:thermal_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585677904,
      "name": "class_unregister",
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
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585808160,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:192",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/thermal/thermal_core.c:thermal_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585808160,
      "name": "class_unregister",
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
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586041424,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:198",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586041424,
      "name": "class_unregister",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586189056,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:198",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586189056,
      "name": "class_unregister",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586950768,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:199",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_exit",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586950768,
      "name": "class_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587035760,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:199",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/base/core.c:devlink_class_init",
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_exit",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587035760,
      "name": "class_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586919552,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:199",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/base/core.c:devlink_class_init",
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_exit",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586919552,
      "name": "class_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587481952,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:199",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/base/core.c:devlink_class_init",
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_exit",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587481952,
      "name": "class_unregister",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588803584,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:199",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/base/core.c:devlink_class_init",
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_loader/sysfs.c:unregister_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_exit",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588803584,
      "name": "class_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590300752,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:204",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/base/core.c:devlink_class_init",
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_loader/sysfs.c:unregister_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_exit",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590300752,
      "name": "class_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void class_unregister(const struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590621984,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:223",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtio_console_fini",
        "drivers/char/virtio_console.c:virtio_console_init",
        "drivers/base/core.c:devlink_class_init",
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_loader/sysfs.c:unregister_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/roles/class.c:usb_roles_exit",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_exit",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590621984,
      "name": "class_unregister",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void class_unregister(const struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590981232,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:222",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "block/bsg.c:bsg_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtio_console_fini",
        "drivers/char/virtio_console.c:virtio_console_init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/base/core.c:devlink_class_init",
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_loader/sysfs.c:unregister_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/accel/drm_accel.c:accel_core_exit",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/roles/class.c:usb_roles_exit",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_exit",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590981232,
      "name": "class_unregister",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498988760,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:198",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498988760,
      "name": "class_unregister",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231557024,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:198",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/mtd/mtdcore.c:cleanup_mtd",
        "drivers/mtd/mtdcore.c:init_mtd",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231557024,
      "name": "class_unregister",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292141488,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:198",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292141488,
      "name": "class_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276363796,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:198",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276363796,
      "name": "class_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585949424,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:198",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585949424,
      "name": "class_unregister",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585798480,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:198",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585798480,
      "name": "class_unregister",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586139072,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:198",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586139072,
      "name": "class_unregister",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void class_unregister(struct class * cls)
```

```json
{
  "name": "class_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586247760,
      "name": "class_unregister",
      "external": true,
      "loc": "drivers/base/class.c:198",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/base/class.c:class_destroy",
        "drivers/base/transport_class.c:transport_class_unregister",
        "drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/scsi/hosts.c:scsi_exit_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_exit",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/input/input.c:input_exit",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_exit",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_exit",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_unregister_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586247760,
      "name": "class_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct class * cls</code> ➡️ <code>const struct class * cls</code>
</li>
</ul>
</details>
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
