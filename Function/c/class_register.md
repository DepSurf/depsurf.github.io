# Function: <code>class_register</code>

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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int class_register(const struct class * cls)
```

```json
{
  "name": "class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590621120,
      "name": "class_register",
      "external": true,
      "loc": "drivers/base/class.c:178",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_class_init",
        "block/genhd.c:genhd_device_init",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtio_console_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/core.c:devlink_class_init",
        "drivers/base/class.c:class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_loader/sysfs.c:register_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/spi/spi.c:spi_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/roles/class.c:usb_roles_init",
        "drivers/input/input.c:input_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_init",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_init_sysfs",
        "drivers/powercap/powercap_sys.c:powercap_init",
        "net/core/net-sysfs.c:netdev_kobject_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590621120,
      "name": "class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
int class_register(const struct class * cls)
```

```json
{
  "name": "class_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590980272,
      "name": "class_register",
      "external": true,
      "loc": "drivers/base/class.c:178",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "mm/backing-dev.c:bdi_class_init",
        "block/genhd.c:genhd_device_init",
        "block/bsg.c:bsg_init",
        "drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init",
        "drivers/pwm/sysfs.c:pwm_sysfs_init",
        "drivers/pci/probe.c:pcibus_class_init",
        "drivers/rapidio/rio-driver.c:rio_bus_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/regulator/core.c:regulator_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtio_console_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/iommu/iommu-sysfs.c:iommu_dev_init",
        "drivers/base/core.c:devlink_class_init",
        "drivers/base/class.c:class_create",
        "drivers/base/transport_class.c:transport_class_register",
        "drivers/base/firmware_loader/sysfs.c:register_sysfs_loader",
        "drivers/base/devcoredump.c:devcoredump_init",
        "drivers/scsi/hosts.c:scsi_init_hosts",
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_register",
        "drivers/scsi/sd.c:init_sd",
        "drivers/accel/drm_accel.c:accel_core_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/spi/spi.c:spi_init",
        "drivers/net/phy/mdio_bus.c:mdio_bus_init",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/roles/class.c:usb_roles_init",
        "drivers/input/input.c:input_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/hwmon/hwmon.c:hwmon_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_init",
        "drivers/mmc/core/host.c:mmc_register_host_class",
        "drivers/leds/led-class.c:leds_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_init",
        "drivers/remoteproc/remoteproc_sysfs.c:rproc_init_sysfs",
        "drivers/powercap/powercap_sys.c:powercap_init",
        "net/core/net-sysfs.c:netdev_kobject_init",
        "net/rfkill/core.c:rfkill_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590980272,
      "name": "class_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int class_register(const struct class * cls)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
