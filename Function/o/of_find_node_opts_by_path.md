# Function: <code>of_find_node_opts_by_path</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct device_node * of_find_node_opts_by_path(const char * path, const char * * opts)
```

```json
{
  "name": "of_find_node_opts_by_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501603728,
      "name": "of_find_node_opts_by_path",
      "external": true,
      "loc": "drivers/of/base.c:939",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/imx/clk.c:imx_obtain_fixed_clock_from_dt",
        "drivers/soc/bcm/brcmstb/common.c:soc_is_brcmstb",
        "drivers/soc/fsl/guts.c:fsl_guts_probe",
        "drivers/soc/amlogic/meson-gx-socinfo.c:meson_gx_socinfo_init",
        "drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init",
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init",
        "drivers/tty/sysrq.c:sysrq_toggle_support",
        "drivers/base/arch_topology.c:init_cpu_topology",
        "drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/base.c:of_find_node_opts_by_path",
        "drivers/of/base.c:of_get_next_cpu_node",
        "drivers/of/base.c:of_machine_is_compatible",
        "drivers/of/platform.c:of_platform_default_populate_init",
        "drivers/of/platform.c:of_platform_populate",
        "drivers/of/platform.c:of_platform_bus_probe",
        "drivers/of/resolver.c:of_resolve_phandles",
        "drivers/of/resolver.c:of_resolve_phandles",
        "drivers/of/overlay.c:init_overlay_changeset",
        "drivers/of/overlay.c:init_overlay_changeset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501603728,
      "name": "of_find_node_opts_by_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
struct device_node * of_find_node_opts_by_path(const char * path, const char * * opts)
```

```json
{
  "name": "of_find_node_opts_by_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234128544,
      "name": "of_find_node_opts_by_path",
      "external": true,
      "loc": "drivers/of/base.c:939",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/setup.c:init_machine_late",
        "arch/arm/kernel/devtree.c:arm_dt_init_cpu_maps",
        "arch/arm/mach-imx/cpu.c:imx_soc_device_init",
        "arch/arm/mach-omap2/omap_hwmod.c:__omap_hwmod_setup_all",
        "arch/arm/mach-omap2/omap_hwmod.c:__omap_hwmod_setup_all",
        "arch/arm/mach-rockchip/platsmp.c:rockchip_smp_prepare_cpus",
        "drivers/bus/ti-sysc.c:sysc_map_and_check_registers",
        "drivers/bus/ti-sysc.c:sysc_map_and_check_registers",
        "drivers/clk/imx/clk.c:imx_obtain_fixed_clock_from_dt",
        "drivers/soc/fsl/guts.c:fsl_guts_probe",
        "drivers/soc/amlogic/meson-gx-socinfo.c:meson_gx_socinfo_init",
        "drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init",
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init",
        "drivers/soc/samsung/exynos-chipid.c:exynos_chipid_early_init",
        "drivers/soc/tegra/common.c:soc_is_tegra",
        "drivers/tty/sysrq.c:sysrq_toggle_support",
        "drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init",
        "drivers/cpufreq/ti-cpufreq.c:ti_cpufreq_init",
        "drivers/cpuidle/cpuidle-big_little.c:bl_idle_init",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/base.c:of_find_node_opts_by_path",
        "drivers/of/base.c:of_get_next_cpu_node",
        "drivers/of/base.c:of_machine_is_compatible",
        "drivers/of/platform.c:of_platform_default_populate_init",
        "drivers/of/platform.c:of_platform_populate",
        "drivers/of/platform.c:of_platform_bus_probe",
        "drivers/of/resolver.c:of_resolve_phandles",
        "drivers/of/resolver.c:of_resolve_phandles",
        "drivers/of/overlay.c:init_overlay_changeset",
        "drivers/of/overlay.c:init_overlay_changeset",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234128544,
      "name": "of_find_node_opts_by_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
struct device_node * of_find_node_opts_by_path(const char * path, const char * * opts)
```

```json
{
  "name": "of_find_node_opts_by_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295027232,
      "name": "of_find_node_opts_by_path",
      "external": true,
      "loc": "drivers/of/base.c:939",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps",
        "arch/powerpc/kernel/setup-common.c:show_cpuinfo",
        "arch/powerpc/kernel/setup_64.c:check_smt_enabled",
        "arch/powerpc/kernel/proc_powerpc.c:proc_ppc64_create",
        "arch/powerpc/kernel/legacy_serial.c:check_legacy_serial_console",
        "arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports",
        "arch/powerpc/kernel/machine_kexec.c:kexec_setup",
        "arch/powerpc/kernel/machine_kexec_64.c:export_htab_values",
        "arch/powerpc/kernel/ima_kexec.c:get_addr_size_cells",
        "arch/powerpc/kernel/kvm.c:kvm_para_available",
        "arch/powerpc/mm/drmem.c:drmem_init",
        "arch/powerpc/mm/drmem.c:drmem_update_dt",
        "arch/powerpc/mm/numa.c:memory_hotplug_max",
        "arch/powerpc/mm/numa.c:memory_hotplug_max",
        "arch/powerpc/mm/numa.c:hot_add_scn_to_nid",
        "arch/powerpc/mm/numa.c:mem_topology_setup",
        "arch/powerpc/mm/numa.c:parse_numa_properties",
        "arch/powerpc/mm/numa.c:parse_numa_properties",
        "arch/powerpc/mm/numa.c:parse_numa_properties",
        "arch/powerpc/mm/numa.c:parse_numa_properties",
        "arch/powerpc/sysdev/xive/spapr.c:xive_spapr_init",
        "arch/powerpc/platforms/powernv/setup.c:pnv_show_cpuinfo",
        "arch/powerpc/platforms/powernv/opal.c:opal_init",
        "arch/powerpc/platforms/powernv/opal.c:opal_init",
        "arch/powerpc/platforms/powernv/opal.c:opal_init",
        "arch/powerpc/platforms/powernv/opal.c:opal_init",
        "arch/powerpc/platforms/powernv/opal.c:opal_init",
        "arch/powerpc/platforms/powernv/opal-async.c:opal_async_comp_init",
        "arch/powerpc/platforms/powernv/idle.c:pnv_parse_cpuidle_dt",
        "arch/powerpc/platforms/powernv/opal-rtc.c:__machine_initcall_powernv_opal_time_init",
        "arch/powerpc/platforms/powernv/opal-sysparam.c:opal_sys_param_init",
        "arch/powerpc/platforms/powernv/opal-sensor.c:opal_sensor_init",
        "arch/powerpc/platforms/powernv/opal-power.c:opal_power_control_init",
        "arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_init",
        "arch/powerpc/platforms/pseries/reconfig.c:ofdt_write",
        "arch/powerpc/platforms/pseries/reconfig.c:ofdt_write",
        "arch/powerpc/platforms/pseries/of_helpers.c:pseries_of_derive_parent",
        "arch/powerpc/platforms/pseries/of_helpers.c:pseries_of_derive_parent",
        "arch/powerpc/platforms/pseries/setup.c:pSeries_setup_arch",
        "arch/powerpc/platforms/pseries/setup.c:pSeries_show_cpuinfo",
        "arch/powerpc/platforms/pseries/ras.c:__machine_initcall_pseries_init_ras_IRQ",
        "arch/powerpc/platforms/pseries/ras.c:__machine_initcall_pseries_init_ras_IRQ",
        "arch/powerpc/platforms/pseries/ras.c:init_ras_hotplug_IRQ",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_release",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_add",
        "arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_memory_block_size",
        "arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_memory_block_size",
        "arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_memory_block_size",
        "arch/powerpc/platforms/pseries/io_event_irq.c:__machine_initcall_pseries_ioei_init",
        "arch/powerpc/platforms/pseries/lparcfg.c:lparcfg_data",
        "drivers/soc/fsl/guts.c:fsl_guts_probe",
        "drivers/tty/sysrq.c:sysrq_toggle_support",
        "drivers/tty/hvc/hvc_opal.c:hvc_opal_init_early",
        "drivers/tty/hvc/hvc_opal.c:hvc_opal_init_early",
        "drivers/cpufreq/powernv-cpufreq.c:init_powernv_pstates",
        "drivers/cpuidle/governors/haltpoll.c:init_haltpoll",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/base.c:of_find_node_opts_by_path",
        "drivers/of/base.c:of_get_next_cpu_node",
        "drivers/of/base.c:of_machine_is_compatible",
        "drivers/of/platform.c:of_platform_populate",
        "drivers/of/platform.c:of_platform_bus_probe",
        "drivers/of/resolver.c:of_resolve_phandles",
        "drivers/of/resolver.c:of_resolve_phandles",
        "drivers/of/overlay.c:init_overlay_changeset",
        "drivers/of/overlay.c:init_overlay_changeset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295027232,
      "name": "of_find_node_opts_by_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
struct device_node * of_find_node_opts_by_path(const char * path, const char * * opts)
```

```json
{
  "name": "of_find_node_opts_by_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278070344,
      "name": "of_find_node_opts_by_path",
      "external": true,
      "loc": "drivers/of/base.c:939",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/time.c:time_init",
        "drivers/tty/sysrq.c:sysrq_toggle_support",
        "drivers/base/arch_topology.c:init_cpu_topology",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/base.c:of_find_node_opts_by_path",
        "drivers/of/base.c:of_get_next_cpu_node",
        "drivers/of/base.c:of_machine_is_compatible",
        "drivers/of/platform.c:of_platform_default_populate_init",
        "drivers/of/platform.c:of_platform_populate",
        "drivers/of/platform.c:of_platform_bus_probe",
        "drivers/of/resolver.c:of_resolve_phandles",
        "drivers/of/resolver.c:of_resolve_phandles",
        "drivers/of/overlay.c:init_overlay_changeset",
        "drivers/of/overlay.c:init_overlay_changeset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278070344,
      "name": "of_find_node_opts_by_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
struct device_node * of_find_node_opts_by_path(const char * path, const char * * opts)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct device_node * of_find_node_opts_by_path(const char * path, const char * * opts)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct device_node * of_find_node_opts_by_path(const char * path, const char * * opts)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct device_node * of_find_node_opts_by_path(const char * path, const char * * opts)
```
</details>
</li>
</ul>
