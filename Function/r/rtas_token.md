# Function: <code>rtas_token</code>

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
int rtas_token(const char * service)
```

```json
{
  "name": "rtas_token",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282412288,
      "name": "rtas_token",
      "external": true,
      "loc": "arch/powerpc/kernel/rtas.c:316",
      "file": "arch/powerpc/kernel/rtas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/rtas.c:rtas_give_timebase",
        "arch/powerpc/kernel/rtas.c:rtas_give_timebase",
        "arch/powerpc/kernel/rtas.c:rtas_initialize",
        "arch/powerpc/kernel/rtas.c:rtas_initialize",
        "arch/powerpc/kernel/rtas.c:rtas_ibm_suspend_me",
        "arch/powerpc/kernel/rtas.c:rtas_ibm_suspend_me",
        "arch/powerpc/kernel/rtas.c:rtas_os_term",
        "arch/powerpc/kernel/rtas.c:rtas_os_term",
        "arch/powerpc/kernel/rtas.c:rtas_os_term",
        "arch/powerpc/kernel/rtas.c:rtas_halt",
        "arch/powerpc/kernel/rtas.c:rtas_power_off",
        "arch/powerpc/kernel/rtas.c:rtas_restart",
        "arch/powerpc/kernel/rtas.c:rtas_set_indicator_fast",
        "arch/powerpc/kernel/rtas.c:rtas_set_indicator",
        "arch/powerpc/kernel/rtas.c:rtas_get_sensor_fast",
        "arch/powerpc/kernel/rtas.c:rtas_get_sensor",
        "arch/powerpc/kernel/rtas.c:rtas_set_power_level",
        "arch/powerpc/kernel/rtas.c:rtas_get_power_level",
        "arch/powerpc/kernel/rtas-rtc.c:rtas_set_rtc_time",
        "arch/powerpc/kernel/rtas-rtc.c:rtas_get_rtc_time",
        "arch/powerpc/kernel/rtas-rtc.c:rtas_get_boot_time",
        "arch/powerpc/kernel/rtas_pci.c:init_pci_config_tokens",
        "arch/powerpc/kernel/rtas_pci.c:init_pci_config_tokens",
        "arch/powerpc/kernel/rtas_pci.c:init_pci_config_tokens",
        "arch/powerpc/kernel/rtas_pci.c:init_pci_config_tokens",
        "arch/powerpc/kernel/rtasd.c:rtas_event_scan_init",
        "arch/powerpc/kernel/rtasd.c:rtas_event_scan_init",
        "arch/powerpc/kernel/rtas-proc.c:ppc_rtas_tone_volume_write",
        "arch/powerpc/kernel/rtas-proc.c:ppc_rtas_tone_freq_write",
        "arch/powerpc/kernel/rtas-proc.c:ppc_rtas_sensors_show",
        "arch/powerpc/kernel/rtas-proc.c:ppc_rtas_clock_show",
        "arch/powerpc/kernel/rtas-proc.c:ppc_rtas_clock_write",
        "arch/powerpc/kernel/rtas-proc.c:ppc_rtas_poweron_write",
        "arch/powerpc/sysdev/xics/ics-rtas.c:ics_rtas_init",
        "arch/powerpc/sysdev/xics/ics-rtas.c:ics_rtas_init",
        "arch/powerpc/sysdev/xics/ics-rtas.c:ics_rtas_init",
        "arch/powerpc/sysdev/xics/ics-rtas.c:ics_rtas_init",
        "arch/powerpc/platforms/pseries/lpar.c:pseries_lpar_read_hblkrm_characteristics",
        "arch/powerpc/platforms/pseries/nvram.c:pSeries_nvram_init",
        "arch/powerpc/platforms/pseries/nvram.c:pSeries_nvram_init",
        "arch/powerpc/platforms/pseries/setup.c:pseries_power_off",
        "arch/powerpc/platforms/pseries/setup.c:pseries_power_off",
        "arch/powerpc/platforms/pseries/setup.c:pSeries_cmo_feature_init",
        "arch/powerpc/platforms/pseries/setup.c:pSeries_setup_arch",
        "arch/powerpc/platforms/pseries/ras.c:fwnmi_release_errinfo",
        "arch/powerpc/platforms/pseries/ras.c:__machine_initcall_pseries_init_ras_IRQ",
        "arch/powerpc/platforms/pseries/dlpar.c:dlpar_release_drc",
        "arch/powerpc/platforms/pseries/dlpar.c:dlpar_acquire_drc",
        "arch/powerpc/platforms/pseries/dlpar.c:dlpar_configure_connector",
        "arch/powerpc/platforms/pseries/mobility.c:post_mobility_fixup",
        "arch/powerpc/platforms/pseries/mobility.c:pseries_devicetree_update",
        "arch/powerpc/platforms/pseries/mobility.c:pseries_devicetree_update",
        "arch/powerpc/platforms/pseries/pci.c:pseries_send_map_pe",
        "arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_notify_resume",
        "arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_send_allow_unfreeze",
        "arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_init",
        "arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_init",
        "arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_init",
        "arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_init",
        "arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_init",
        "arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_init",
        "arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_init",
        "arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_init",
        "arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_init",
        "arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_init",
        "arch/powerpc/platforms/pseries/msi.c:__machine_initcall_pseries_rtas_msi_init",
        "arch/powerpc/platforms/pseries/msi.c:__machine_initcall_pseries_rtas_msi_init",
        "arch/powerpc/platforms/pseries/smp.c:smp_init_pseries",
        "arch/powerpc/platforms/pseries/smp.c:smp_init_pseries",
        "arch/powerpc/platforms/pseries/smp.c:smp_pSeries_kick_cpu",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:__machine_initcall_pseries_pseries_cpu_hotplug_init",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:__machine_initcall_pseries_pseries_cpu_hotplug_init",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:__machine_initcall_pseries_pseries_cpu_hotplug_init",
        "arch/powerpc/platforms/pseries/io_event_irq.c:__machine_initcall_pseries_ioei_init",
        "arch/powerpc/platforms/pseries/lparcfg.c:parse_system_parameter_string",
        "arch/powerpc/platforms/pseries/suspend.c:__machine_initcall_pseries_pseries_suspend_init",
        "drivers/tty/hvc/hvc_rtas.c:hvc_rtas_console_init",
        "drivers/tty/hvc/hvc_rtas.c:hvc_rtas_console_init",
        "drivers/tty/hvc/hvc_rtas.c:hvc_rtas_init",
        "drivers/tty/hvc/hvc_rtas.c:hvc_rtas_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282412288,
      "name": "rtas_token",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int rtas_token(const char * service)
```
</details>
</li>
</ul>
