# Function: <code>arch_send_wakeup_ipi_mask</code>

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
void arch_send_wakeup_ipi_mask(const struct cpumask * mask)
```

```json
{
  "name": "arch_send_wakeup_ipi_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490272992,
      "name": "arch_send_wakeup_ipi_mask",
      "external": true,
      "loc": "arch/arm64/kernel/smp.c:816",
      "file": "arch/arm64/kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/acpi_parking_protocol.c:acpi_parking_protocol_cpu_boot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490272992,
      "name": "arch_send_wakeup_ipi_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void arch_send_wakeup_ipi_mask(const struct cpumask * mask)
```

```json
{
  "name": "arch_send_wakeup_ipi_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224448648,
      "name": "arch_send_wakeup_ipi_mask",
      "external": true,
      "loc": "arch/arm/kernel/smp.c:561",
      "file": "arch/arm/kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/common/mcpm_platsmp.c:mcpm_boot_secondary",
        "arch/arm/mach-exynos/platsmp.c:exynos_boot_secondary",
        "arch/arm/mach-hisi/platmcpm.c:hip04_boot_secondary",
        "arch/arm/mach-hisi/platsmp.c:hix5hd2_boot_secondary",
        "arch/arm/mach-hisi/platsmp.c:hi3xxx_boot_secondary",
        "arch/arm/mach-mvebu/platsmp.c:mv98dx3236_boot_secondary",
        "arch/arm/mach-mvebu/platsmp.c:armada_xp_boot_secondary",
        "arch/arm/mach-mvebu/platsmp-a9.c:mvebu_cortex_a9_boot_secondary",
        "arch/arm/mach-imx/platsmp.c:ls1021a_boot_secondary",
        "arch/arm/mach-mediatek/platsmp.c:mtk_boot_secondary",
        "arch/arm/mach-milbeaut/platsmp.c:m10v_boot_secondary",
        "arch/arm/mach-omap2/omap-smp.c:omap4_boot_secondary",
        "arch/arm/mach-qcom/platsmp.c:qcom_boot_secondary",
        "arch/arm/mach-shmobile/smp-emev2.c:emev2_boot_secondary",
        "arch/arm/plat-versatile/platsmp.c:versatile_boot_secondary",
        "drivers/soc/renesas/r9a06g032-smp.c:r9a06g032_smp_boot_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224448648,
      "name": "arch_send_wakeup_ipi_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void arch_send_wakeup_ipi_mask(const struct cpumask * mask)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void arch_send_wakeup_ipi_mask(const struct cpumask * mask)
```
</details>
</li>
</ul>
