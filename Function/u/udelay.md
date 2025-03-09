# Function: <code>udelay</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void udelay(long unsigned int usecs)
```

```json
{
  "name": "udelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282341152,
      "name": "udelay",
      "external": true,
      "loc": "arch/powerpc/kernel/time.c:476",
      "file": "arch/powerpc/kernel/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/traps.c:system_reset_exception",
        "arch/powerpc/kernel/setup-common.c:machine_restart",
        "arch/powerpc/kernel/setup_64.c:smp_release_cpus",
        "arch/powerpc/kernel/rtas.c:rtas_get_power_level",
        "arch/powerpc/kernel/rtas-rtc.c:rtas_get_boot_time",
        "arch/powerpc/kernel/smp.c:__cpu_up",
        "arch/powerpc/kernel/smp.c:generic_cpu_disable",
        "arch/powerpc/kernel/smp.c:__smp_send_nmi_ipi",
        "arch/powerpc/kernel/crash.c:default_machine_crash_shutdown",
        "arch/powerpc/kernel/crash.c:default_machine_crash_shutdown",
        "arch/powerpc/kernel/crash.c:crash_kexec_secondary",
        "arch/powerpc/sysdev/i8259.c:i8259_init",
        "arch/powerpc/sysdev/i8259.c:i8259_init",
        "arch/powerpc/sysdev/xics/xics-common.c:xics_migrate_irqs_away",
        "arch/powerpc/sysdev/xive/spapr.c:plpar_busy_delay",
        "arch/powerpc/platforms/powernv/setup.c:pnv_power_off",
        "arch/powerpc/platforms/powernv/setup.c:pnv_restart",
        "arch/powerpc/platforms/powernv/setup.c:pnv_restart",
        "arch/powerpc/platforms/powernv/opal.c:opal_shutdown",
        "arch/powerpc/platforms/powernv/opal.c:opal_flush_console",
        "arch/powerpc/platforms/powernv/opal-rtc.c:opal_get_boot_time",
        "arch/powerpc/platforms/powernv/opal-rtc.c:opal_get_boot_time",
        "arch/powerpc/platforms/powernv/opal-nvram.c:opal_nvram_write",
        "arch/powerpc/platforms/powernv/opal-nvram.c:opal_nvram_write",
        "arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_phb_reset",
        "arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_phb_reset",
        "arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_poll",
        "arch/powerpc/platforms/pseries/setup.c:pseries_little_endian_exceptions",
        "arch/powerpc/platforms/pseries/setup.c:pseries_big_endian_exceptions",
        "arch/powerpc/platforms/pseries/setup.c:pseries_disable_reloc_on_exc",
        "arch/powerpc/platforms/pseries/setup.c:pseries_enable_reloc_on_exc",
        "arch/powerpc/platforms/pseries/rtas-fadump.c:rtas_fadump_invalidate",
        "arch/powerpc/platforms/pseries/rtas-fadump.c:rtas_fadump_unregister",
        "arch/powerpc/platforms/pseries/rtas-fadump.c:rtas_fadump_register",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:wait_for_other_cpus",
        "arch/powerpc/xmon/xmon.c:get_output_lock",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/smpboot.c:cpu_wait_death",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/srcutree.c:try_check_zero",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "drivers/pci/pci.c:pci_restore_config_dword",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_mport_chk_dev_access",
        "drivers/video/console/vgacon.c:vga_set_palette",
        "drivers/video/console/vgacon.c:vga_set_palette",
        "drivers/video/console/vgacon.c:vga_set_palette",
        "drivers/video/console/vgacon.c:vga_set_palette",
        "drivers/video/console/vgacon.c:vga_set_palette",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_doresize",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/fbdev/gxt4500.c:gxt4500_set_par",
        "drivers/video/fbdev/gxt4500.c:gxt4500_set_par",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/tty/hvc/hvsi.c:poll_for_state",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:size_fifo",
        "drivers/tty/serial/8250/8250_pci.c:sbs_init",
        "drivers/tty/serial/sccnxp.c:sccnxp_write",
        "drivers/tty/serial/sccnxp.c:sccnxp_read",
        "drivers/base/power/domain.c:genpd_dev_pm_detach",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear",
        "drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set",
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down",
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down",
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_handshake",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:_ohci_shutdown",
        "drivers/usb/host/ohci-hcd.c:_ohci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/uhci-hcd.c:wakeup_rh",
        "drivers/usb/host/uhci-hcd.c:suspend_rh",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_finish_suspend",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_handshake",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_panic_blink",
        "drivers/input/serio/i8042.c:i8042_toggle_aux",
        "drivers/input/serio/i8042.c:i8042_port_close",
        "drivers/input/serio/i8042.c:i8042_flush",
        "drivers/input/serio/i8042.c:i8042_wait_write",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff",
        "drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff",
        "drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff",
        "drivers/power/reset/gpio-restart.c:gpio_restart_notify",
        "drivers/power/reset/gpio-restart.c:gpio_restart_notify",
        "drivers/power/reset/gpio-restart.c:gpio_restart_notify",
        "drivers/power/reset/syscon-reboot.c:syscon_restart_handle",
        "drivers/power/reset/syscon-poweroff.c:syscon_poweroff",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282341152,
      "name": "udelay",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void udelay(long unsigned int usecs)
```

```json
{
  "name": "udelay",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279788672,
      "name": "udelay",
      "external": true,
      "loc": "arch/riscv/lib/delay.c:81",
      "file": "arch/riscv/lib/delay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/smp.c:smp_send_stop",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/srcutree.c:try_check_zero",
        "drivers/pci/pci.c:pci_restore_config_dword",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/pci/quirks.c:quirk_via_vlink",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu",
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_lock_device",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_clr_err_stopped",
        "drivers/rapidio/rio.c:rio_mport_chk_dev_access",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate",
        "drivers/clk/sifive/fu540-prci.c:sifive_fu540_prci_wrpll_set_rate",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_enable_delay",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:size_fifo",
        "drivers/tty/serial/8250/8250_pci.c:sbs_init",
        "drivers/tty/serial/sifive.c:sifive_serial_console_putchar",
        "drivers/base/power/domain.c:genpd_dev_pm_detach",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_tf_load",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear",
        "drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set",
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common",
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:_ohci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/uhci-hcd.c:wakeup_rh",
        "drivers/usb/host/uhci-hcd.c:suspend_rh",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_finish_suspend",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_handshake",
        "drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff",
        "drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff",
        "drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff",
        "drivers/power/reset/gpio-restart.c:gpio_restart_notify",
        "drivers/power/reset/gpio-restart.c:gpio_restart_notify",
        "drivers/power/reset/gpio-restart.c:gpio_restart_notify",
        "drivers/power/reset/syscon-reboot.c:syscon_restart_handle",
        "drivers/power/reset/syscon-poweroff.c:syscon_poweroff",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout",
        "net/core/netpoll.c:netpoll_send_skb_on_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279788672,
      "name": "udelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void udelay(long unsigned int usecs)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void udelay(long unsigned int usecs)
```
</details>
</li>
</ul>
