# Function: <code>cpu_pm_register_notifier</code>

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
int cpu_pm_register_notifier(struct notifier_block * nb)
```

```json
{
  "name": "cpu_pm_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492102584,
      "name": "cpu_pm_register_notifier",
      "external": true,
      "loc": "kernel/cpu_pm.c:45",
      "file": "kernel/cpu_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/fpsimd.c:fpsimd_init",
        "virt/kvm/arm/arm.c:kvm_arch_init",
        "virt/kvm/arm/arm.c:kvm_arch_init",
        "drivers/irqchip/irq-gic.c:gic_init_bases",
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases",
        "drivers/firmware/arm_sdei.c:sdei_probe",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_register",
        "drivers/perf/arm_pmu.c:armpmu_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492102584,
      "name": "cpu_pm_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int cpu_pm_register_notifier(struct notifier_block * nb)
```

```json
{
  "name": "cpu_pm_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226002744,
      "name": "cpu_pm_register_notifier",
      "external": true,
      "loc": "kernel/cpu_pm.c:45",
      "file": "kernel/cpu_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/vfp/vfpmodule.c:vfp_init",
        "arch/arm/kernel/hw_breakpoint.c:arch_hw_breakpoint_init",
        "arch/arm/mach-mvebu/pmsu.c:mvebu_v7_cpu_pm_init",
        "arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init",
        "arch/arm/mach-tegra/irq.c:tegra_init_irq",
        "drivers/irqchip/irq-gic.c:gic_init_bases",
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases",
        "drivers/irqchip/irq-vf610-mscm-ir.c:vf610_mscm_ir_of_init",
        "drivers/gpio/gpio-omap.c:omap_gpio_probe",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_of_init",
        "drivers/perf/arm_pmu.c:armpmu_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226002744,
      "name": "cpu_pm_register_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int cpu_pm_register_notifier(struct notifier_block * nb)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int cpu_pm_register_notifier(struct notifier_block * nb)
```
</details>
</li>
</ul>
