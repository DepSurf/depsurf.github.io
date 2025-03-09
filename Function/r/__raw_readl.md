# Function: <code>__raw_readl</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 __raw_readl(volatile const void * addr)
```

```json
{
  "name": "__raw_readl",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490325696,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "arch/arm64/kernel/acpi_parking_protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/acpi_parking_protocol.c:acpi_parking_protocol_cpu_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490546020,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "virt/kvm/arm/vgic/vgic-v2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_put",
        "virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_put",
        "virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_save_state",
        "virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_save_state",
        "virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_save_state",
        "virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503972264,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "arch/arm64/kvm/hyp/vgic-v2-cpuif-proxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/hyp/vgic-v2-cpuif-proxy.c:__vgic_v2_perform_cpuif_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491207940,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "kernel/irq/generic-chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:irq_gc_init_mask_cache",
        "kernel/irq/generic-chip.c:irq_readl_be"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494974044,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "fs/debugfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:debugfs_print_regs32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496175088,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "lib/iomap_copy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iomap_copy.c:__ioread32_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496178952,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "lib/logic_pio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496347676,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "lib/stmp_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/stmp_device.c:stmp_reset_block",
        "lib/stmp_device.c:stmp_clear_poll_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496359616,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-al-fic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-al-fic.c:al_fic_irq_handler",
        "drivers/irqchip/irq-al-fic.c:al_fic_irq_set_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496360216,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-bcm2835.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-bcm2835.c:get_next_armctrl_hwirq",
        "drivers/irqchip/irq-bcm2835.c:get_next_armctrl_hwirq",
        "drivers/irqchip/irq-bcm2835.c:get_next_armctrl_hwirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490161872,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-bcm2836.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_handle_irq",
        "drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_handle_irq",
        "drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_unmask_per_cpu_irq",
        "drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_mask_per_cpu_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496361864,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-dw-apb-ictl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_handler"
      ],
      "caller_func": [
        "drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init",
        "drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init"
      ]
    },
    {
      "addr": 18446603336496362304,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-sun4i.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-sun4i.c:sun4i_irq_unmask",
        "drivers/irqchip/irq-sun4i.c:sun4i_irq_mask",
        "drivers/irqchip/irq-sun4i.c:sun4i_handle_irq",
        "drivers/irqchip/irq-sun4i.c:sun4i_handle_irq",
        "drivers/irqchip/irq-sun4i.c:sun4i_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496363156,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-sunxi-nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_set_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496366660,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-gic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic.c:gic_init_bases",
        "drivers/irqchip/irq-gic.c:gic_cpu_save",
        "drivers/irqchip/irq-gic.c:gic_cpu_save",
        "drivers/irqchip/irq-gic.c:gic_cpu_save",
        "drivers/irqchip/irq-gic.c:gic_dist_save",
        "drivers/irqchip/irq-gic.c:gic_dist_save",
        "drivers/irqchip/irq-gic.c:gic_dist_save",
        "drivers/irqchip/irq-gic.c:gic_dist_save",
        "drivers/irqchip/irq-gic.c:gic_cpu_if_down",
        "drivers/irqchip/irq-gic.c:gic_cpu_if_up",
        "drivers/irqchip/irq-gic.c:gic_cpu_if_up",
        "drivers/irqchip/irq-gic.c:gic_handle_cascade_irq",
        "drivers/irqchip/irq-gic.c:gic_handle_irq",
        "drivers/irqchip/irq-gic.c:gic_set_affinity",
        "drivers/irqchip/irq-gic.c:gic_peek_irq"
      ],
      "caller_func": [
        "drivers/irqchip/irq-gic.c:gic_of_init",
        "drivers/irqchip/irq-gic.c:gic_of_init",
        "drivers/irqchip/irq-gic.c:gic_of_init",
        "drivers/irqchip/irq-gic.c:gic_of_init"
      ]
    },
    {
      "addr": 18446603336496369496,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-gic-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-common.c:gic_configure_irq",
        "drivers/irqchip/irq-gic-common.c:gic_configure_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496371592,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-gic-v2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic-v2m.c:gicv2m_init_one",
        "drivers/irqchip/irq-gic-v2m.c:gicv2m_init_one"
      ]
    },
    {
      "addr": 18446603336496374880,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3.c:gic_dist_supports_lpis",
        "drivers/irqchip/irq-gic-v3.c:gic_cpu_sys_reg_init",
        "drivers/irqchip/irq-gic-v3.c:gic_iterate_rdists",
        "drivers/irqchip/irq-gic-v3.c:gic_peek_irq"
      ],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3.c:gic_acpi_parse_madt_gicc",
        "drivers/irqchip/irq-gic-v3.c:gic_validate_dist_version",
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases",
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases",
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases"
      ]
    },
    {
      "addr": 18446603336496401104,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_save_disable",
        "drivers/irqchip/irq-gic-v3-its.c:its_send_single_vcommand",
        "drivers/irqchip/irq-gic-v3-its.c:its_send_single_command",
        "drivers/irqchip/irq-gic-v3-its.c:its_wait_for_range_completion"
      ],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3-its.c:its_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_probe_one",
        "drivers/irqchip/irq-gic-v3-its.c:its_probe_one",
        "drivers/irqchip/irq-gic-v3-its.c:its_probe_one",
        "drivers/irqchip/irq-gic-v3-its.c:its_probe_one",
        "drivers/irqchip/irq-gic-v3-its.c:its_probe_one",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis"
      ]
    },
    {
      "addr": 18446603336496407416,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-mbigen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mbigen.c:mbigen_write_msg",
        "drivers/irqchip/irq-mbigen.c:mbigen_set_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496409236,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-renesas-irqc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-renesas-irqc.c:irqc_irq_handler",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496410636,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-bcm7038-l1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_irq_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496413304,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-brcmstb-l2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_suspend",
        "drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_irq_handle",
        "drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_irq_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496414052,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-mtk-sysirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_set_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496415816,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-mtk-cirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_resume",
        "drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_resume",
        "drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496417164,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-imx-gpcv2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_mask",
        "drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_unmask",
        "drivers/irqchip/irq-imx-gpcv2.c:gpcv2_wakeup_source_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496420604,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-mvebu-icu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496422736,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-mvebu-pic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_handle_cascade_irq",
        "drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_unmask_irq",
        "drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_mask_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496425308,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-mvebu-sei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_handle_cascade_irq",
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_unmask_irq",
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_mask_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496427148,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-ls-scfg-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496429640,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/qcom-irq-combiner.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/qcom-irq-combiner.c:combiner_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496432296,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-sni-exiu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-sni-exiu.c:exiu_irq_set_type",
        "drivers/irqchip/irq-sni-exiu.c:exiu_irq_set_type",
        "drivers/irqchip/irq-sni-exiu.c:exiu_irq_enable",
        "drivers/irqchip/irq-sni-exiu.c:exiu_irq_unmask",
        "drivers/irqchip/irq-sni-exiu.c:exiu_irq_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496433556,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-meson-gpio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496435892,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/qcom-pdc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496437800,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/irqchip/irq-imx-irqsteer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_suspend",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_handler",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_mask",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_unmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496443864,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/bus/hisi_lpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/hisi_lpc.c:wait_lpc_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496447416,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/bus/brcmstb_gisb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/brcmstb_gisb.c:gisb_read",
        "drivers/bus/brcmstb_gisb.c:gisb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496467984,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/bus/imx-weim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/imx-weim.c:weim_parse_dt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496469748,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/bus/qcom-ebi2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496480748,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/phy/phy-xgene.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496490948,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/phy/broadcom/phy-brcm-sata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_wr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496524808,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pinctrl/pinctrl-amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496531964,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pinctrl/pinctrl-bm1880.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinconf_cfg_set",
        "drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinconf_cfg_get",
        "drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinmux_set_mux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496558528,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pinctrl/pinctrl-rockchip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_suspend",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set_config",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_get",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set",
        "drivers/pinctrl/pinctrl-rockchip.c:_rockchip_pmx_gpio_set_direction",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_get_direction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496559696,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pinctrl/pinctrl-single.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-single.c:pcs_readl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496581320,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pinctrl/actions/pinctrl-owl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_ack",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_unmask",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_unmask",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask",
        "drivers/pinctrl/actions/pinctrl-owl.c:irq_set_type",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_input",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_input",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_set",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_get",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_free",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_free",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_request",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_set",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_get",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_set",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_get",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_set_mux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496593564,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pinctrl/bcm/pinctrl-bcm2835.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2711_pull_config_set",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pmx_gpio_set_direction",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pmx_gpio_disable_free",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pmx_set",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pmx_free",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pctl_pin_dbg_show",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pctl_pin_dbg_show",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_handle_bank",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_get_direction",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496603484,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_pin_config_set",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_pin_config_get",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_get_pull",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_get_pull",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_get_pull",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_get_pull",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set_pull",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set_pull",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set_pull",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set_pull",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set_pull",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_get",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_get_direction",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_direction_output",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_direction_output",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_direction_input",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_set_type",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_set_type",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_set_type",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_unmask",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_mask",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496608300,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pinctrl/bcm/pinctrl-ns2-mux.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_get_pull",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_set_pull",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496611916,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pinctrl/freescale/pinctrl-imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_dbg_show",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_set",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_get",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496622084,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pinctrl/mvebu/pinctrl-mvebu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_mmio_mpp_ctrl_set",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_mmio_mpp_ctrl_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496628916,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_suspend",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_suspend",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_suspend",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_suspend",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_set_type",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_set_wake",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_unmask",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496634684,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pinctrl/qcom/pinctrl-msm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_ack",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_clear_unmask",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_clear_unmask",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_mask",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_dbg_show",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_dbg_show",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_set",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_get",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_get_direction",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_output",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_output",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_input",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_get",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_get",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_set_mux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496643136,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pinctrl/sh-pfc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496657564,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pinctrl/sprd/pinctrl-sprd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_get_config",
        "drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_get_config",
        "drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_set",
        "drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_set",
        "drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_get",
        "drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_get",
        "drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pmx_set_mux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496666652,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pinctrl/sunxi/pinctrl-sunxi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_handler",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_unmask",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_mask",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_set_type",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_gpio_set",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_gpio_get",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_request",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_request",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_set",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pconf_set",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pconf_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496675860,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pinctrl/mediatek/mtk-eint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_debounce",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_debounce",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496689184,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_get_value",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_get_value",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_get_value",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_rmw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496759584,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_read32be",
        "drivers/gpio/gpio-mmio.c:bgpio_read32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496767904,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/gpio/gpio-davinci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-davinci.c:gpio_irq_handler",
        "drivers/gpio/gpio-davinci.c:davinci_gpio_get",
        "drivers/gpio/gpio-davinci.c:davinci_direction_out",
        "drivers/gpio/gpio-davinci.c:davinci_direction_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496770548,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/gpio/gpio-ftgpio010.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_unmask_irq",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_mask_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496778396,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/gpio/gpio-mvebu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend",
        "drivers/gpio/gpio-mvebu.c:mvebu_pwm_get_state",
        "drivers/gpio/gpio-mvebu.c:mvebu_pwm_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496784464,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/gpio/gpio-mxc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend",
        "drivers/gpio/gpio-mxc.c:mx2_gpio_irq_handler",
        "drivers/gpio/gpio-mxc.c:mx2_gpio_irq_handler",
        "drivers/gpio/gpio-mxc.c:mx3_gpio_irq_handler",
        "drivers/gpio/gpio-mxc.c:mx3_gpio_irq_handler",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_irq_handler",
        "drivers/gpio/gpio-mxc.c:gpio_set_irq_type",
        "drivers/gpio/gpio-mxc.c:gpio_set_irq_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496801412,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/gpio/gpio-xgene.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-xgene.c:xgene_gpio_suspend",
        "drivers/gpio/gpio-xgene.c:xgene_gpio_dir_out",
        "drivers/gpio/gpio-xgene.c:xgene_gpio_dir_in",
        "drivers/gpio/gpio-xgene.c:xgene_gpio_get_direction",
        "drivers/gpio/gpio-xgene.c:__xgene_gpio_set",
        "drivers/gpio/gpio-xgene.c:xgene_gpio_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496802736,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/gpio/gpio-xilinx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-xilinx.c:xgpio_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496817460,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32",
        "drivers/pci/access.c:pci_generic_config_read32",
        "drivers/pci/access.c:pci_generic_config_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496904316,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/rom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496967884,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume_early"
      ],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias"
      ]
    },
    {
      "addr": 18446603336497039196,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_query_power_fault",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_status",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_get_latch_status",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_get_power_status",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_get_attention_status"
      ],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init"
      ]
    },
    {
      "addr": 18446603336497059260,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/msi.c:msi_set_mask_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497092484,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/pcie-cadence-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497097116,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/pcie-cadence-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497100352,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/pci-ftpci100.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_unmask_irq",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_mask_irq",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_ack_irq",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_read_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497103812,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/pci-aardvark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_probe",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_probe",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_probe",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_irq_unmask",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_irq_mask",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_wr_conf",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_rd_conf",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_rd_conf",
        "drivers/pci/controller/pci-aardvark.c:advk_pci_bridge_emul_pcie_conf_write",
        "drivers/pci/controller/pci-aardvark.c:advk_pci_bridge_emul_pcie_conf_read",
        "drivers/pci/controller/pci-aardvark.c:advk_pci_bridge_emul_pcie_conf_read",
        "drivers/pci/controller/pci-aardvark.c:advk_pci_bridge_emul_pcie_conf_read",
        "drivers/pci/controller/pci-aardvark.c:advk_pci_bridge_emul_pcie_conf_read",
        "drivers/pci/controller/pci-aardvark.c:advk_pci_bridge_emul_pcie_conf_read",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_wait_pio",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_wait_pio",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_check_pio_status",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_link_up"
      ],
      "caller_func": [
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_check_pio_status"
      ]
    },
    {
      "addr": 18446603336497112828,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/pcie-rcar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_resume_noirq",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_resume_noirq",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs",
        "drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs",
        "drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irq",
        "drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irq",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_msi_irq",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_msi_irq",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_wait_for_dl",
        "drivers/pci/controller/pcie-rcar.c:phy_wait_for_ack",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access",
        "drivers/pci/controller/pcie-rcar.c:rcar_rmw32"
      ],
      "caller_func": [
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe"
      ]
    },
    {
      "addr": 18446603336497116944,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/pcie-xilinx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_map_bus"
      ],
      "caller_func": [
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe"
      ]
    },
    {
      "addr": 18446603336497123468,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/pcie-xilinx-nwl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_unmask_leg_irq",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_mask_leg_irq",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_handle_msi_irq",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_leg_handler",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_misc_handler",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_map_bus"
      ],
      "caller_func": [
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init"
      ]
    },
    {
      "addr": 18446603336497125864,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/pci-xgene-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_isr",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_isr",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_isr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497129200,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/pcie-iproc-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_exit",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_exit",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_handler",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_handler",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497134064,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/pcie-altera.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-altera.c:altera_pcie_isr",
        "drivers/pci/controller/pcie-altera.c:s10_rp_read_cfg",
        "drivers/pci/controller/pcie-altera.c:s10_tlp_read_packet",
        "drivers/pci/controller/pcie-altera.c:s10_tlp_read_packet",
        "drivers/pci/controller/pcie-altera.c:s10_tlp_read_packet",
        "drivers/pci/controller/pcie-altera.c:s10_tlp_read_packet",
        "drivers/pci/controller/pcie-altera.c:tlp_read_packet",
        "drivers/pci/controller/pcie-altera.c:tlp_read_packet",
        "drivers/pci/controller/pcie-altera.c:tlp_read_packet",
        "drivers/pci/controller/pcie-altera.c:altera_pcie_link_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497136248,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/pcie-altera-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_free",
        "drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_alloc",
        "drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr",
        "drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497136432,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/pcie-rockchip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497142784,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/pcie-rockchip-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_raise_irq",
        "drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_raise_irq",
        "drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_get_msi",
        "drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_msi",
        "drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_clear_bar",
        "drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497150192,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/pcie-mediatek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_write",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_read",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497154800,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/pcie-mobiveil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497155564,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497168280,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497179432,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/dwc/pci-keystone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_err_irq_handler",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_legacy_irq_handler",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_irq_handler",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_start_link",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_stop_link",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_clear_dbi_mode",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_clear_dbi_mode",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_set_dbi_mode",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_set_dbi_mode"
      ],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init"
      ]
    },
    {
      "addr": 18446603336497182100,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/dwc/pci-layerscape.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_host_init",
        "drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_link_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497189496,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/dwc/pcie-qcom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_2_3_2_ltssm_enable",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_2_1_0_ltssm_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497194596,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/dwc/pcie-kirin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_link_up",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_write_dbi",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_write_dbi",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_wr_own_conf",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_wr_own_conf",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_sideband_dbi_r_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497196932,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/dwc/pcie-histb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_link_up",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_link_up",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_dbi_r_mode",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_dbi_w_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497199488,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/dwc/pcie-al.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-al.c:al_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-al.c:al_pcie_host_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497202880,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/pci-thunder-ecam.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read",
        "drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read",
        "drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read",
        "drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read",
        "drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read",
        "drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read",
        "drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read",
        "drivers/pci/controller/pci-thunder-ecam.c:handle_ea_bar",
        "drivers/pci/controller/pci-thunder-ecam.c:handle_ea_bar",
        "drivers/pci/controller/pci-thunder-ecam.c:handle_ea_bar",
        "drivers/pci/controller/pci-thunder-ecam.c:handle_ea_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497208752,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/pci/controller/pci-xgene.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-xgene.c:xgene_pcie_setup",
        "drivers/pci/controller/pci-xgene.c:xgene_pcie_setup",
        "drivers/pci/controller/pci-xgene.c:xgene_pcie_setup",
        "drivers/pci/controller/pci-xgene.c:xgene_pcie_setup",
        "drivers/pci/controller/pci-xgene.c:xgene_pcie_setup",
        "drivers/pci/controller/pci-xgene.c:xgene_pcie_setup",
        "drivers/pci/controller/pci-xgene.c:xgene_pcie_map_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497336400,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/video/fbdev/core/cfbimgblt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit",
        "drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit",
        "drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit",
        "drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497342812,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/video/fbdev/imsttfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_ioctl",
        "drivers/video/fbdev/imsttfb.c:imsttfb_ioctl",
        "drivers/video/fbdev/imsttfb.c:imsttfb_copyarea",
        "drivers/video/fbdev/imsttfb.c:imsttfb_copyarea",
        "drivers/video/fbdev/imsttfb.c:imsttfb_copyarea",
        "drivers/video/fbdev/imsttfb.c:imsttfb_fillrect",
        "drivers/video/fbdev/imsttfb.c:imsttfb_fillrect",
        "drivers/video/fbdev/imsttfb.c:imsttfb_fillrect",
        "drivers/video/fbdev/imsttfb.c:imsttfb_fillrect",
        "drivers/video/fbdev/imsttfb.c:imsttfb_fillrect",
        "drivers/video/fbdev/imsttfb.c:imsttfb_fillrect",
        "drivers/video/fbdev/imsttfb.c:imsttfb_blank"
      ],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/imsttfb.c:init_imstt"
      ]
    },
    {
      "addr": 18446603336497345984,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/video/fbdev/amba-clcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/amba-clcd.c:clcdfb_setcolreg",
        "drivers/video/fbdev/amba-clcd.c:clcdfb_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497367552,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/video/fbdev/mx3fb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:sdc_init_panel",
        "drivers/video/fbdev/mx3fb.c:sdc_init_panel",
        "drivers/video/fbdev/mx3fb.c:sdc_init_panel",
        "drivers/video/fbdev/mx3fb.c:sdc_init_panel",
        "drivers/video/fbdev/mx3fb.c:sdc_init_panel",
        "drivers/video/fbdev/mx3fb.c:sdc_disable_channel",
        "drivers/video/fbdev/mx3fb.c:sdc_enable_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497380196,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497666768,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:cpc_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497731468,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/amba/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/amba/bus.c:amba_device_try_add",
        "drivers/amba/bus.c:amba_device_try_add",
        "drivers/amba/bus.c:amba_device_try_add",
        "drivers/amba/bus.c:amba_device_try_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497776564,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_set_rate",
        "drivers/clk/clk-divider.c:clk_divider_set_rate",
        "drivers/clk/clk-divider.c:clk_divider_round_rate",
        "drivers/clk/clk-divider.c:clk_divider_round_rate",
        "drivers/clk/clk-divider.c:clk_divider_recalc_rate",
        "drivers/clk/clk-divider.c:clk_divider_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497780356,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/clk-gate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-gate.c:clk_gate_is_enabled",
        "drivers/clk/clk-gate.c:clk_gate_is_enabled",
        "drivers/clk/clk-gate.c:clk_gate_endisable",
        "drivers/clk/clk-gate.c:clk_gate_endisable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497781528,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/clk-multiplier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-multiplier.c:clk_multiplier_set_rate",
        "drivers/clk/clk-multiplier.c:clk_multiplier_set_rate",
        "drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate",
        "drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497783696,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/clk-mux.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-mux.c:clk_mux_set_parent",
        "drivers/clk/clk-mux.c:clk_mux_set_parent",
        "drivers/clk/clk-mux.c:clk_mux_get_parent",
        "drivers/clk/clk-mux.c:clk_mux_get_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497787208,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/clk-fractional-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-fractional-divider.c:clk_fd_set_rate",
        "drivers/clk/clk-fractional-divider.c:clk_fd_set_rate",
        "drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate",
        "drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497790596,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/clk-fixed-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497792248,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/clk-hsdk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_core_update_rate",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_core_update_rate",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497792416,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/clk-qoriq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-qoriq.c:p5040_init_periph",
        "drivers/clk/clk-qoriq.c:p5020_init_periph",
        "drivers/clk/clk-qoriq.c:p4080_init_periph",
        "drivers/clk/clk-qoriq.c:p2041_init_periph"
      ]
    },
    {
      "addr": 18446603336497796420,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/clk-xgene.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-xgene.c:xgene_clk_set_rate",
        "drivers/clk/clk-xgene.c:xgene_clk_recalc_rate",
        "drivers/clk/clk-xgene.c:xgene_clk_is_enabled",
        "drivers/clk/clk-xgene.c:xgene_clk_disable",
        "drivers/clk/clk-xgene.c:xgene_clk_disable",
        "drivers/clk/clk-xgene.c:xgene_clk_enable",
        "drivers/clk/clk-xgene.c:xgene_clk_enable",
        "drivers/clk/clk-xgene.c:xgene_clk_pmd_set_rate",
        "drivers/clk/clk-xgene.c:xgene_clk_pmd_recalc_rate",
        "drivers/clk/clk-xgene.c:xgene_clk_pll_recalc_rate",
        "drivers/clk/clk-xgene.c:xgene_clk_pll_is_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497803840,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/bcm/clk-iproc-armpll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497809816,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/bcm/clk-iproc-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_clk_setup",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_clk_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_clk_recalc_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_clk_disable",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_clk_enable",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_clk_enable",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_recalc_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_recalc_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_recalc_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_recalc_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_disable",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_disable",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_disable",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate",
        "drivers/clk/bcm/clk-iproc-pll.c:__pll_enable",
        "drivers/clk/bcm/clk-iproc-pll.c:__pll_enable",
        "drivers/clk/bcm/clk-iproc-pll.c:__pll_enable",
        "drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497810576,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/bcm/clk-iproc-asiu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_clk_set_rate",
        "drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_clk_set_rate",
        "drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_clk_recalc_rate",
        "drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_clk_disable",
        "drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_clk_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497818100,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/bcm/clk-bcm2835.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_register_clock",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_get_parent",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_set_rate",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_on",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_off",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_off",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_get_rate",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_is_on",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_set_rate",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_on",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_on",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_off",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_off",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_is_on",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_set_rate",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_set_rate",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_set_rate",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_on",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_on",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_on",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_on",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_off",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_get_rate",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_get_rate",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_get_rate",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_is_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497819968,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/berlin/berlin2-avpll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_disable",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_enable",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_vco_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_vco_disable",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_vco_enable",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_vco_is_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497820416,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/berlin/berlin2-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/berlin/berlin2-pll.c:berlin2_pll_recalc_rate",
        "drivers/clk/berlin/berlin2-pll.c:berlin2_pll_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497821204,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/berlin/berlin2-div.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_recalc_rate",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_recalc_rate",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_recalc_rate",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_get_parent",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_get_parent",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_set_parent",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_set_parent",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_disable",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_enable",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_is_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497824440,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/hisilicon/clkgate-separated.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_is_enabled",
        "drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_disable",
        "drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497825308,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/hisilicon/clkdivider-hi6220.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/hisilicon/clkdivider-hi6220.c:hi6220_clkdiv_set_rate",
        "drivers/clk/hisilicon/clkdivider-hi6220.c:hi6220_clkdiv_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497826416,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/hisilicon/clk-hisi-phase.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/hisilicon/clk-hisi-phase.c:hisi_clk_set_phase",
        "drivers/clk/hisilicon/clk-hisi-phase.c:hisi_clk_get_phase"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497828900,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/hisilicon/reset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/hisilicon/reset.c:hisi_reset_deassert",
        "drivers/clk/hisilicon/reset.c:hisi_reset_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497830504,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/hisilicon/clk-hi3660-stub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/hisilicon/clk-hi3660-stub.c:hi3660_stub_clk_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511150404,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/imx/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk.c:imx_mmdc_mask_handshake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497831720,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/imx/clk-busy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-busy.c:clk_busy_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497833140,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/imx/clk-composite-8m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-composite-8m.c:imx8m_clk_composite_divider_set_rate",
        "drivers/clk/imx/clk-composite-8m.c:imx8m_clk_composite_divider_recalc_rate",
        "drivers/clk/imx/clk-composite-8m.c:imx8m_clk_composite_divider_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497836480,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/imx/clk-divider-gate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-divider-gate.c:imx_clk_divider_gate",
        "drivers/clk/imx/clk-divider-gate.c:clk_divider_is_enabled",
        "drivers/clk/imx/clk-divider-gate.c:clk_divider_disable",
        "drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_set_rate",
        "drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_recalc_rate",
        "drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_recalc_rate_ro"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497837024,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/imx/clk-fixup-div.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-fixup-div.c:clk_fixup_div_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497837708,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/imx/clk-fixup-mux.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-fixup-mux.c:clk_fixup_mux_set_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497838748,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/imx/clk-frac-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_recalc_rate",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_recalc_rate",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_is_prepared",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_unprepare",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_prepare",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_prepare",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497839192,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/imx/clk-gate-exclusive.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-gate-exclusive.c:clk_gate_exclusive_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497840052,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/imx/clk-gate2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-gate2.c:clk_gate2_disable_unused",
        "drivers/clk/imx/clk-gate2.c:clk_gate2_is_enabled",
        "drivers/clk/imx/clk-gate2.c:clk_gate2_disable",
        "drivers/clk/imx/clk-gate2.c:clk_gate2_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497841224,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/imx/clk-pfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-pfd.c:clk_pfd_is_enabled",
        "drivers/clk/imx/clk-pfd.c:clk_pfd_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497842564,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/imx/clk-pfdv2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_set_rate",
        "drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_is_enabled",
        "drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_disable",
        "drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable",
        "drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable",
        "drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497843076,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/imx/clk-pllv1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-pllv1.c:clk_pllv1_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497844068,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/imx/clk-pllv2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-pllv2.c:clk_pllv2_unprepare",
        "drivers/clk/imx/clk-pllv2.c:clk_pllv2_prepare",
        "drivers/clk/imx/clk-pllv2.c:clk_pllv2_prepare",
        "drivers/clk/imx/clk-pllv2.c:clk_pllv2_set_rate",
        "drivers/clk/imx/clk-pllv2.c:clk_pllv2_recalc_rate",
        "drivers/clk/imx/clk-pllv2.c:clk_pllv2_recalc_rate",
        "drivers/clk/imx/clk-pllv2.c:clk_pllv2_recalc_rate",
        "drivers/clk/imx/clk-pllv2.c:clk_pllv2_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497846408,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/imx/clk-pllv3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_set_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_recalc_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_recalc_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_recalc_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_set_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_recalc_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_recalc_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_recalc_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_sys_set_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_sys_recalc_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_set_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_recalc_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_is_prepared",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_unprepare",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497847596,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/imx/clk-pllv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-pllv4.c:clk_pllv4_disable",
        "drivers/clk/imx/clk-pllv4.c:clk_pllv4_enable",
        "drivers/clk/imx/clk-pllv4.c:clk_pllv4_enable",
        "drivers/clk/imx/clk-pllv4.c:clk_pllv4_enable",
        "drivers/clk/imx/clk-pllv4.c:clk_pllv4_set_rate",
        "drivers/clk/imx/clk-pllv4.c:clk_pllv4_recalc_rate",
        "drivers/clk/imx/clk-pllv4.c:clk_pllv4_recalc_rate",
        "drivers/clk/imx/clk-pllv4.c:clk_pllv4_recalc_rate",
        "drivers/clk/imx/clk-pllv4.c:clk_pllv4_is_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497849992,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/imx/clk-sccg-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_set_parent",
        "drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_get_parent",
        "drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_set_rate",
        "drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_set_rate",
        "drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_recalc_rate",
        "drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_recalc_rate",
        "drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_unprepare",
        "drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_prepare",
        "drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_is_prepared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497852228,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/imx/clk-pll14xx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-pll14xx.c:imx_clk_pll14xx",
        "drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_unprepare",
        "drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_is_prepared",
        "drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_prepare",
        "drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate",
        "drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate",
        "drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate",
        "drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate",
        "drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_recalc_rate",
        "drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_recalc_rate",
        "drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497854200,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/imx/clk-lpcg-scu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-lpcg-scu.c:clk_lpcg_scu_disable",
        "drivers/clk/imx/clk-lpcg-scu.c:clk_lpcg_scu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497899124,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/mediatek/clk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_unprepare",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_unprepare",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_unprepare",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_unprepare",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_prepare",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_prepare",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_prepare",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_prepare",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_recalc_rate",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_recalc_rate",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_is_prepared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497901048,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/mediatek/clk-apmixed.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mediatek/clk-apmixed.c:mtk_ref2usb_tx_unprepare",
        "drivers/clk/mediatek/clk-apmixed.c:mtk_ref2usb_tx_prepare",
        "drivers/clk/mediatek/clk-apmixed.c:mtk_ref2usb_tx_is_prepared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497924788,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/mvebu/armada-37xx-tbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mvebu/armada-37xx-tbg.c:armada_3700_tbg_clock_probe",
        "drivers/clk/mvebu/armada-37xx-tbg.c:armada_3700_tbg_clock_probe",
        "drivers/clk/mvebu/armada-37xx-tbg.c:armada_3700_tbg_clock_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497927892,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/mvebu/armada-37xx-periph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_suspend",
        "drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_suspend",
        "drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_suspend",
        "drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_suspend",
        "drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_suspend",
        "drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_suspend",
        "drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_recalc_rate",
        "drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_get_parent",
        "drivers/clk/mvebu/armada-37xx-periph.c:clk_double_div_recalc_rate",
        "drivers/clk/mvebu/armada-37xx-periph.c:clk_double_div_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497931404,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/renesas/r9a06g032-clocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_div_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497934168,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/renesas/rcar-gen3-cpg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/rcar-gen3-cpg.c:cpg_sd_clock_is_enabled",
        "drivers/clk/renesas/rcar-gen3-cpg.c:cpg_z_clk_recalc_rate",
        "drivers/clk/renesas/rcar-gen3-cpg.c:cpg_reg_modify"
      ],
      "caller_func": [
        "drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_clk_register",
        "drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_clk_register",
        "drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_clk_register",
        "drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_clk_register",
        "drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_clk_register"
      ]
    },
    {
      "addr": 18446603336497938508,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/renesas/renesas-cpg-mssr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_resume_noirq",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_resume_noirq",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_suspend_noirq",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_status",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_is_enabled",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_endisable",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_endisable"
      ],
      "caller_func": [
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_register_core_clk"
      ]
    },
    {
      "addr": 18446603336497940456,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/renesas/clk-div6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/clk-div6.c:cpg_div6_clock_set_parent",
        "drivers/clk/renesas/clk-div6.c:cpg_div6_clock_set_rate",
        "drivers/clk/renesas/clk-div6.c:cpg_div6_clock_is_enabled",
        "drivers/clk/renesas/clk-div6.c:cpg_div6_clock_disable",
        "drivers/clk/renesas/clk-div6.c:cpg_div6_clock_enable"
      ],
      "caller_func": [
        "drivers/clk/renesas/clk-div6.c:cpg_div6_register"
      ]
    },
    {
      "addr": 18446603336497942392,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/rockchip/clk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_is_enabled",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_set_params",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_is_enabled",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_is_enabled",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_set_params"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497947920,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/rockchip/clk-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497950656,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/rockchip/clk-half-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk-half-divider.c:clk_half_divider_set_rate",
        "drivers/clk/rockchip/clk-half-divider.c:clk_half_divider_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497951612,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/rockchip/clk-inverter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk-inverter.c:rockchip_inv_set_phase",
        "drivers/clk/rockchip/clk-inverter.c:rockchip_inv_get_phase"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497952244,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/rockchip/clk-mmc-phase.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk-mmc-phase.c:rockchip_mmc_get_phase"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497953840,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/rockchip/clk-ddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk-ddr.c:rockchip_ddrclk_get_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497954980,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/rockchip/softrst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/softrst.c:rockchip_softrst_deassert",
        "drivers/clk/rockchip/softrst.c:rockchip_softrst_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497955528,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/rockchip/clk-rk3288.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497956872,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/socfpga/clk-pll-s10.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/socfpga/clk-pll-s10.c:clk_pll_prepare",
        "drivers/clk/socfpga/clk-pll-s10.c:clk_boot_get_parent",
        "drivers/clk/socfpga/clk-pll-s10.c:clk_pll_get_parent",
        "drivers/clk/socfpga/clk-pll-s10.c:clk_boot_clk_recalc_rate",
        "drivers/clk/socfpga/clk-pll-s10.c:clk_pll_recalc_rate",
        "drivers/clk/socfpga/clk-pll-s10.c:clk_pll_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497957492,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/socfpga/clk-periph-s10.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/socfpga/clk-periph-s10.c:clk_peri_cnt_clk_recalc_rate",
        "drivers/clk/socfpga/clk-periph-s10.c:clk_peri_c_clk_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497958604,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/socfpga/clk-gate-s10.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/socfpga/clk-gate-s10.c:socfpga_gate_get_parent",
        "drivers/clk/socfpga/clk-gate-s10.c:socfpga_dbg_clk_recalc_rate",
        "drivers/clk/socfpga/clk-gate-s10.c:socfpga_gate_clk_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497960080,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi/clk-factors.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-factors.c:clk_factors_set_rate",
        "drivers/clk/sunxi/clk-factors.c:clk_factors_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511177624,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi/clk-a10-pll2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-a10-pll2.c:sun4i_pll2_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497963860,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi/clk-a10-ve.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-a10-ve.c:sunxi_ve_reset_deassert",
        "drivers/clk/sunxi/clk-a10-ve.c:sunxi_ve_reset_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497964732,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi/clk-mod0.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-mod0.c:mmc_set_phase",
        "drivers/clk/sunxi/clk-mod0.c:mmc_get_phase"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497965300,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi/clk-sun4i-display.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_status",
        "drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_deassert",
        "drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497966208,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi/clk-sun4i-tcon-ch1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_set_rate",
        "drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_recalc_rate",
        "drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_set_parent",
        "drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_get_parent",
        "drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_is_enabled",
        "drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_enable",
        "drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497969016,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi/clk-sun9i-mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_deassert",
        "drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497969972,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi/clk-usb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_deassert",
        "drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497971760,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi/clk-sun9i-cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-sun9i-cpus.c:sun9i_a80_cpus_clk_set_rate",
        "drivers/clk/sunxi/clk-sun9i-cpus.c:sun9i_a80_cpus_clk_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497973352,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi-ng/ccu_common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497974448,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi-ng/ccu_mmc_timing.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_mmc_timing.c:sunxi_ccu_get_mmc_timing_mode",
        "drivers/clk/sunxi-ng/ccu_mmc_timing.c:sunxi_ccu_set_mmc_timing_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497974836,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi-ng/ccu_reset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_reset.c:ccu_reset_status",
        "drivers/clk/sunxi-ng/ccu_reset.c:ccu_reset_deassert",
        "drivers/clk/sunxi-ng/ccu_reset.c:ccu_reset_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497975876,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi-ng/ccu_div.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_div.c:ccu_div_set_rate",
        "drivers/clk/sunxi-ng/ccu_div.c:ccu_div_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497977404,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi-ng/ccu_frac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_set_rate",
        "drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_read_rate",
        "drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_disable",
        "drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_enable",
        "drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_is_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497977968,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi-ng/ccu_gate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_gate.c:ccu_gate_is_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497980544,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi-ng/ccu_mux.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_helper_set_parent",
        "drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_helper_get_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497981760,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi-ng/ccu_mult.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_mult.c:ccu_mult_set_rate",
        "drivers/clk/sunxi-ng/ccu_mult.c:ccu_mult_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497982460,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi-ng/ccu_phase.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_phase.c:ccu_phase_set_phase",
        "drivers/clk/sunxi-ng/ccu_phase.c:ccu_phase_get_phase"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497984196,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi-ng/ccu_sdm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_read_rate",
        "drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_disable",
        "drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_disable",
        "drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_enable",
        "drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_enable",
        "drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_is_enabled",
        "drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_is_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497985524,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi-ng/ccu_nk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_nk.c:ccu_nk_set_rate",
        "drivers/clk/sunxi-ng/ccu_nk.c:ccu_nk_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497987272,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi-ng/ccu_nkm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_nkm.c:ccu_nkm_set_rate",
        "drivers/clk/sunxi-ng/ccu_nkm.c:ccu_nkm_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497989296,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi-ng/ccu_nkmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_nkmp.c:ccu_nkmp_set_rate",
        "drivers/clk/sunxi-ng/ccu_nkmp.c:ccu_nkmp_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497991728,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi-ng/ccu_nm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_set_rate",
        "drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_set_rate",
        "drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497993612,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi-ng/ccu_mp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_mmc_set_rate",
        "drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_mmc_recalc_rate",
        "drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_set_rate",
        "drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497994260,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi-ng/ccu-sun50i-a64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497994508,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi-ng/ccu-sun50i-h6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu-sun50i-h6.c:sun50i_h6_ccu_probe",
        "drivers/clk/sunxi-ng/ccu-sun50i-h6.c:sun50i_h6_ccu_probe",
        "drivers/clk/sunxi-ng/ccu-sun50i-h6.c:sun50i_h6_ccu_probe",
        "drivers/clk/sunxi-ng/ccu-sun50i-h6.c:sun50i_h6_ccu_probe",
        "drivers/clk/sunxi-ng/ccu-sun50i-h6.c:sun50i_h6_ccu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497994956,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi-ng/ccu-sun8i-a83t.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu-sun8i-a83t.c:sun8i_a83t_ccu_probe",
        "drivers/clk/sunxi-ng/ccu-sun8i-a83t.c:sun8i_a83t_cpu_pll_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511186820,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/sunxi-ng/ccu-sun8i-h3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu-sun8i-h3.c:sunxi_h3_h5_ccu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497995884,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clk/versatile/clk-sp810.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/versatile/clk-sp810.c:clk_sp810_timerclken_set_parent",
        "drivers/clk/versatile/clk-sp810.c:clk_sp810_timerclken_get_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498030968,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/dma/amba-pl08x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/amba-pl08x.c:pl08x_irq",
        "drivers/dma/amba-pl08x.c:pl08x_irq",
        "drivers/dma/amba-pl08x.c:pl08x_resume",
        "drivers/dma/amba-pl08x.c:pl08x_resume",
        "drivers/dma/amba-pl08x.c:pl08x_pause",
        "drivers/dma/amba-pl08x.c:pl08x_pause",
        "drivers/dma/amba-pl08x.c:pl08x_phy_free",
        "drivers/dma/amba-pl08x.c:pl08x_phy_free",
        "drivers/dma/amba-pl08x.c:pl08x_phy_free",
        "drivers/dma/amba-pl08x.c:pl08x_start_next_txd",
        "drivers/dma/amba-pl08x.c:pl08x_start_next_txd",
        "drivers/dma/amba-pl08x.c:pl08x_start_next_txd",
        "drivers/dma/amba-pl08x.c:pl08x_start_next_txd",
        "drivers/dma/amba-pl08x.c:pl08x_start_next_txd",
        "drivers/dma/amba-pl08x.c:pl08x_start_next_txd"
      ],
      "caller_func": [
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/amba-pl08x.c:pl08x_probe"
      ]
    },
    {
      "addr": 18446603336498039180,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/dma/bcm2835-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_probe",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_callback",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498045164,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/dma/mv_xor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mv_xor.c:mv_xor_suspend",
        "drivers/dma/mv_xor.c:mv_xor_suspend",
        "drivers/dma/mv_xor.c:mv_xor_interrupt_handler",
        "drivers/dma/mv_xor.c:mv_xor_tx_submit",
        "drivers/dma/mv_xor.c:mv_xor_tx_submit",
        "drivers/dma/mv_xor.c:mv_chan_slot_cleanup",
        "drivers/dma/mv_xor.c:mv_chan_slot_cleanup"
      ],
      "caller_func": [
        "drivers/dma/mv_xor.c:mv_xor_channel_add",
        "drivers/dma/mv_xor.c:mv_xor_interrupt_handler",
        "drivers/dma/mv_xor.c:mv_xor_interrupt_handler",
        "drivers/dma/mv_xor.c:mv_xor_interrupt_handler",
        "drivers/dma/mv_xor.c:mv_xor_interrupt_handler",
        "drivers/dma/mv_xor.c:mv_xor_interrupt_handler",
        "drivers/dma/mv_xor.c:mv_xor_interrupt_handler"
      ]
    },
    {
      "addr": 18446603336498057904,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/dma/mv_xor_v2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_resume",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_resume",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_descq_init",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_descq_init",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_descq_init",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_tasklet",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_interrupt_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498059164,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/dma/mxs-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mxs-dma.c:mxs_dma_tx_status",
        "drivers/dma/mxs-dma.c:mxs_dma_int_handler",
        "drivers/dma/mxs-dma.c:mxs_dma_int_handler",
        "drivers/dma/mxs-dma.c:mxs_dma_reset_chan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498062200,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/dma/ipu/ipu_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_handler",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_handler",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_status",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_mask",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_unmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498073964,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/dma/ipu/ipu_idmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel",
        "drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel",
        "drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel",
        "drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel",
        "drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit",
        "drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit",
        "drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit",
        "drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit",
        "drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer",
        "drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer",
        "drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer",
        "drivers/dma/ipu/ipu_idmac.c:ipu_ic_disable_task",
        "drivers/dma/ipu/ipu_idmac.c:dump_idmac_reg",
        "drivers/dma/ipu/ipu_idmac.c:dump_idmac_reg",
        "drivers/dma/ipu/ipu_idmac.c:dump_idmac_reg",
        "drivers/dma/ipu/ipu_idmac.c:dump_idmac_reg",
        "drivers/dma/ipu/ipu_idmac.c:dump_idmac_reg",
        "drivers/dma/ipu/ipu_idmac.c:dump_idmac_reg",
        "drivers/dma/ipu/ipu_idmac.c:dump_idmac_reg",
        "drivers/dma/ipu/ipu_idmac.c:dump_idmac_reg",
        "drivers/dma/ipu/ipu_idmac.c:dump_idmac_reg",
        "drivers/dma/ipu/ipu_idmac.c:dump_idmac_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498075968,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/soc/actions/owl-sps-helper.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498077944,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/soc/bcm/bcm2835-power.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_power_probe",
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_off",
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_off",
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_on",
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_on",
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_on",
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_on",
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_off",
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on"
      ],
      "caller_func": [
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on"
      ]
    },
    {
      "addr": 18446603336498082964,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/soc/bcm/brcmstb/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/soc/bcm/brcmstb/common.c:brcmstb_soc_device_early_init",
        "drivers/soc/bcm/brcmstb/common.c:brcmstb_soc_device_early_init"
      ]
    },
    {
      "addr": 18446603336498082976,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/soc/bcm/brcmstb/biuctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/soc/bcm/brcmstb/biuctrl.c:brcmstb_biuctrl_init",
        "drivers/soc/bcm/brcmstb/biuctrl.c:brcmstb_biuctrl_init",
        "drivers/soc/bcm/brcmstb/biuctrl.c:brcmstb_biuctrl_init",
        "drivers/soc/bcm/brcmstb/biuctrl.c:brcmstb_biuctrl_init"
      ]
    },
    {
      "addr": 18446603336498083824,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/soc/fsl/qbman/bman_ccsr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe",
        "drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe",
        "drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe",
        "drivers/soc/fsl/qbman/bman_ccsr.c:bman_isr",
        "drivers/soc/fsl/qbman/bman_ccsr.c:bman_isr",
        "drivers/soc/fsl/qbman/bman_ccsr.c:bman_isr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498086568,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/soc/fsl/qbman/qman_ccsr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe",
        "drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe",
        "drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe",
        "drivers/soc/fsl/qbman/qman_ccsr.c:qman_set_sdest",
        "drivers/soc/fsl/qbman/qman_ccsr.c:qman_set_sdest",
        "drivers/soc/fsl/qbman/qman_ccsr.c:__qman_liodn_fixup",
        "drivers/soc/fsl/qbman/qman_ccsr.c:__qman_liodn_fixup",
        "drivers/soc/fsl/qbman/qman_ccsr.c:qman_isr",
        "drivers/soc/fsl/qbman/qman_ccsr.c:qman_isr",
        "drivers/soc/fsl/qbman/qman_ccsr.c:qman_isr",
        "drivers/soc/fsl/qbman/qman_ccsr.c:qman_isr",
        "drivers/soc/fsl/qbman/qman_ccsr.c:qman_isr",
        "drivers/soc/fsl/qbman/qman_ccsr.c:qm_set_memory",
        "drivers/soc/fsl/qbman/qman_ccsr.c:qm_set_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498093836,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/soc/fsl/qbman/bman.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/bman.c:bman_create_portal",
        "drivers/soc/fsl/qbman/bman.c:bman_create_portal",
        "drivers/soc/fsl/qbman/bman.c:bman_create_portal",
        "drivers/soc/fsl/qbman/bman.c:bman_create_portal",
        "drivers/soc/fsl/qbman/bman.c:bman_create_portal",
        "drivers/soc/fsl/qbman/bman.c:bman_create_portal",
        "drivers/soc/fsl/qbman/bman.c:bman_create_portal",
        "drivers/soc/fsl/qbman/bman.c:portal_isr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498099748,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/soc/fsl/qbman/qman.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/qman.c:qman_p_irqsource_remove",
        "drivers/soc/fsl/qbman/qman.c:qman_destroy_affine_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_destroy_affine_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_create_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_create_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_create_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_create_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_create_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_create_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_create_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_create_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_create_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_create_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_create_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_create_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_create_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_create_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_create_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_create_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_create_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_create_portal",
        "drivers/soc/fsl/qbman/qman.c:portal_isr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498117916,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/soc/fsl/guts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/guts.c:fsl_guts_probe",
        "drivers/soc/fsl/guts.c:fsl_guts_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498120552,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/soc/imx/soc-imx8.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision",
        "drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision",
        "drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision",
        "drivers/soc/imx/soc-imx8.c:imx8mq_soc_revision",
        "drivers/soc/imx/soc-imx8.c:imx8mq_soc_revision",
        "drivers/soc/imx/soc-imx8.c:imx8mq_soc_revision"
      ]
    },
    {
      "addr": 18446603336498123848,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/soc/mediatek/mtk-scpsys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498131796,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/soc/qcom/rpmh-rsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_probe",
        "drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_send_data",
        "drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_send_data",
        "drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_send_data",
        "drivers/soc/qcom/rpmh-rsc.c:__tcs_buffer_write",
        "drivers/soc/qcom/rpmh-rsc.c:__tcs_buffer_write",
        "drivers/soc/qcom/rpmh-rsc.c:tcs_tx_done",
        "drivers/soc/qcom/rpmh-rsc.c:tcs_tx_done",
        "drivers/soc/qcom/rpmh-rsc.c:tcs_is_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498143604,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/soc/renesas/renesas-soc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init",
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init"
      ]
    },
    {
      "addr": 18446603336511197328,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/soc/renesas/rcar-rst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/renesas/rcar-rst.c:rcar_rst_read_mode_pins"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511198148,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/soc/renesas/rcar-sysc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498149816,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/soc/sunxi/sunxi_sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_claim",
        "drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498178392,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/virtio/virtio_mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_mmio.c:vm_interrupt",
        "drivers/virtio/virtio_mmio.c:vm_get_status",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_mmio.c:vm_get_features",
        "drivers/virtio/virtio_mmio.c:vm_get_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498181488,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498189216,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498338308,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/reset/reset-meson.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/reset-meson.c:meson_reset_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498339732,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/reset/reset-simple.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/reset-simple.c:reset_simple_status",
        "drivers/reset/reset-simple.c:reset_simple_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498575756,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_in",
        "drivers/tty/serial/8250/8250_port.c:mem32_serial_in",
        "drivers/tty/serial/8250/8250_port.c:au_serial_dl_read",
        "drivers/tty/serial/8250/8250_port.c:au_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498594804,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/tty/serial/8250/8250_dwlib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498610412,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498611956,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_in",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498613036,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/tty/serial/8250/8250_dw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dw.c:dw8250_serial_in32be",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_serial_in32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498633188,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/tty/serial/amba-pl011.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/amba-pl011.c:pl011_putc",
        "drivers/tty/serial/amba-pl011.c:pl011_putc",
        "drivers/tty/serial/amba-pl011.c:qdf2400_e44_putc",
        "drivers/tty/serial/amba-pl011.c:qdf2400_e44_putc",
        "drivers/tty/serial/amba-pl011.c:pl011_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498656640,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/tty/serial/imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_console_early_putchar",
        "drivers/tty/serial/imx.c:imx_uart_console_write",
        "drivers/tty/serial/imx.c:imx_uart_poll_put_char",
        "drivers/tty/serial/imx.c:imx_uart_poll_put_char",
        "drivers/tty/serial/imx.c:imx_uart_set_termios",
        "drivers/tty/serial/imx.c:imx_uart_set_termios",
        "drivers/tty/serial/imx.c:imx_uart_flush_buffer",
        "drivers/tty/serial/imx.c:imx_uart_flush_buffer",
        "drivers/tty/serial/imx.c:imx_uart_flush_buffer",
        "drivers/tty/serial/imx.c:imx_uart_dma_rx_callback",
        "drivers/tty/serial/imx.c:imx_uart_dma_rx_callback",
        "drivers/tty/serial/imx.c:imx_uart_tx_empty",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_get_hwmctrl",
        "drivers/tty/serial/imx.c:imx_uart_get_hwmctrl",
        "drivers/tty/serial/imx.c:imx_uart_get_hwmctrl"
      ],
      "caller_func": [
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/imx.c:imx_uart_console_setup"
      ]
    },
    {
      "addr": 18446603336498669344,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/tty/serial/meson_uart.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/meson_uart.c:meson_serial_port_write",
        "drivers/tty/serial/meson_uart.c:meson_uart_set_termios",
        "drivers/tty/serial/meson_uart.c:meson_uart_set_termios",
        "drivers/tty/serial/meson_uart.c:meson_uart_startup",
        "drivers/tty/serial/meson_uart.c:meson_uart_interrupt",
        "drivers/tty/serial/meson_uart.c:meson_uart_interrupt",
        "drivers/tty/serial/meson_uart.c:meson_uart_interrupt",
        "drivers/tty/serial/meson_uart.c:meson_uart_interrupt",
        "drivers/tty/serial/meson_uart.c:meson_uart_interrupt",
        "drivers/tty/serial/meson_uart.c:meson_uart_interrupt",
        "drivers/tty/serial/meson_uart.c:meson_uart_interrupt",
        "drivers/tty/serial/meson_uart.c:meson_uart_start_tx",
        "drivers/tty/serial/meson_uart.c:meson_uart_start_tx",
        "drivers/tty/serial/meson_uart.c:meson_uart_shutdown",
        "drivers/tty/serial/meson_uart.c:meson_uart_stop_rx",
        "drivers/tty/serial/meson_uart.c:meson_uart_stop_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498688636,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/tty/serial/msm_serial.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/msm_serial.c:__msm_console_write",
        "drivers/tty/serial/msm_serial.c:__msm_console_write",
        "drivers/tty/serial/msm_serial.c:__msm_console_write",
        "drivers/tty/serial/msm_serial.c:__msm_console_write",
        "drivers/tty/serial/msm_serial.c:msm_poll_put_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_put_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_put_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_put_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_put_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_put_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_get_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_get_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_get_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_get_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_get_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_get_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_get_char",
        "drivers/tty/serial/msm_serial.c:msm_set_termios",
        "drivers/tty/serial/msm_serial.c:msm_set_termios",
        "drivers/tty/serial/msm_serial.c:msm_set_termios",
        "drivers/tty/serial/msm_serial.c:msm_startup",
        "drivers/tty/serial/msm_serial.c:msm_set_mctrl",
        "drivers/tty/serial/msm_serial.c:msm_tx_empty",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx_pio",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx_pio",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx_pio",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx_pio",
        "drivers/tty/serial/msm_serial.c:msm_complete_rx_dma",
        "drivers/tty/serial/msm_serial.c:msm_complete_rx_dma",
        "drivers/tty/serial/msm_serial.c:msm_complete_rx_dma",
        "drivers/tty/serial/msm_serial.c:msm_complete_tx_dma",
        "drivers/tty/serial/msm_serial.c:msm_stop_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498698920,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/tty/serial/mvebu-uart.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write",
        "drivers/tty/serial/mvebu-uart.c:wait_for_xmitr",
        "drivers/tty/serial/mvebu-uart.c:wait_for_xmitr",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_putc",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_putc",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_put_poll_char",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_get_poll_char",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_get_poll_char",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_tx_isr",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_isr",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_isr",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_break_ctl",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_rx",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_rx",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_start_tx",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_tx",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_tx_empty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498704140,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/tty/serial/owl-uart.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/owl-uart.c:owl_uart_port_write",
        "drivers/tty/serial/owl-uart.c:owl_uart_port_write",
        "drivers/tty/serial/owl-uart.c:owl_uart_port_write",
        "drivers/tty/serial/owl-uart.c:owl_uart_set_termios",
        "drivers/tty/serial/owl-uart.c:owl_uart_shutdown",
        "drivers/tty/serial/owl-uart.c:owl_uart_irq",
        "drivers/tty/serial/owl-uart.c:owl_uart_irq",
        "drivers/tty/serial/owl-uart.c:owl_uart_irq",
        "drivers/tty/serial/owl-uart.c:owl_uart_irq",
        "drivers/tty/serial/owl-uart.c:owl_uart_irq",
        "drivers/tty/serial/owl-uart.c:owl_uart_irq",
        "drivers/tty/serial/owl-uart.c:owl_uart_irq",
        "drivers/tty/serial/owl-uart.c:owl_uart_irq",
        "drivers/tty/serial/owl-uart.c:owl_uart_stop_tx",
        "drivers/tty/serial/owl-uart.c:owl_uart_stop_tx",
        "drivers/tty/serial/owl-uart.c:owl_uart_stop_rx",
        "drivers/tty/serial/owl-uart.c:owl_uart_stop_rx",
        "drivers/tty/serial/owl-uart.c:owl_uart_tx_empty",
        "drivers/tty/serial/owl-uart.c:owl_uart_get_mctrl",
        "drivers/tty/serial/owl-uart.c:owl_uart_get_mctrl",
        "drivers/tty/serial/owl-uart.c:owl_uart_set_mctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498816988,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498820872,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_req_canceled",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498879924,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/iommu/arm-smmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/arm-smmu.c:arm_smmu_device_reset",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_reset",
        "drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard",
        "drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard",
        "drivers/iommu/arm-smmu.c:arm_smmu_global_fault",
        "drivers/iommu/arm-smmu.c:arm_smmu_global_fault",
        "drivers/iommu/arm-smmu.c:arm_smmu_global_fault",
        "drivers/iommu/arm-smmu.c:arm_smmu_global_fault",
        "drivers/iommu/arm-smmu.c:arm_smmu_context_fault",
        "drivers/iommu/arm-smmu.c:arm_smmu_context_fault",
        "drivers/iommu/arm-smmu.c:arm_smmu_context_fault",
        "drivers/iommu/arm-smmu.c:__arm_smmu_tlb_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498884968,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/iommu/arm-smmu-impl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/arm-smmu-impl.c:arm_mmu500_reset",
        "drivers/iommu/arm-smmu-impl.c:arm_mmu500_reset",
        "drivers/iommu/arm-smmu-impl.c:arm_mmu500_reset",
        "drivers/iommu/arm-smmu-impl.c:arm_smmu_read_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498891204,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/iommu/arm-smmu-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_device_hw_probe",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_device_hw_probe",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_device_hw_probe",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_gerror_handler",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_gerror_handler",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_priq_thread",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_evtq_thread",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist"
      ],
      "caller_func": [
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_gerror_handler",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist"
      ]
    },
    {
      "addr": 18446603336498908036,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/iommu/rockchip-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/rockchip-iommu.c:rk_iommu_enable",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_irq",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_irq",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_irq"
      ],
      "caller_func": [
        "drivers/iommu/rockchip-iommu.c:rk_iommu_enable",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_disable",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_irq",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_disable_stall",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_enable_stall"
      ]
    },
    {
      "addr": 18446603336498918268,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/iommu/qcom_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_fault",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_fault",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_sync",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499184868,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/base/regmap/regmap-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32le"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499248636,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/misc/vexpress-syscfg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec",
        "drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec",
        "drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499391936,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/mfd/vexpress-sysreg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe",
        "drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499692840,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499791516,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_data_xfer32",
        "drivers/ata/libata-sff.c:ata_sff_data_xfer32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499823272,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/ata/ahci_imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/ahci_imx.c:imx_ahci_probe",
        "drivers/ata/ahci_imx.c:imx_ahci_probe",
        "drivers/ata/ahci_imx.c:imx_phy_crbit_assert",
        "drivers/ata/ahci_imx.c:imx_phy_crbit_assert"
      ],
      "caller_func": [
        "drivers/ata/ahci_imx.c:ahci_imx_error_handler"
      ]
    },
    {
      "addr": 18446603336499828920,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/ata/libahci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libahci.c:ahci_set_em_messages",
        "drivers/ata/libahci.c:ahci_set_em_messages",
        "drivers/ata/libahci.c:ahci_port_start",
        "drivers/ata/libahci.c:ahci_port_suspend",
        "drivers/ata/libahci.c:ahci_port_suspend",
        "drivers/ata/libahci.c:ahci_port_resume",
        "drivers/ata/libahci.c:ahci_pmp_detach",
        "drivers/ata/libahci.c:ahci_pmp_attach",
        "drivers/ata/libahci.c:ahci_disable_fbs",
        "drivers/ata/libahci.c:ahci_disable_fbs",
        "drivers/ata/libahci.c:ahci_enable_fbs",
        "drivers/ata/libahci.c:ahci_enable_fbs",
        "drivers/ata/libahci.c:ahci_set_aggressive_devslp",
        "drivers/ata/libahci.c:ahci_thaw",
        "drivers/ata/libahci.c:ahci_qc_issue",
        "drivers/ata/libahci.c:ahci_single_level_irq_intr",
        "drivers/ata/libahci.c:ahci_handle_port_intr",
        "drivers/ata/libahci.c:ahci_multi_irqs_intr_hard",
        "drivers/ata/libahci.c:ahci_handle_port_interrupt",
        "drivers/ata/libahci.c:ahci_handle_port_interrupt",
        "drivers/ata/libahci.c:ahci_handle_port_interrupt",
        "drivers/ata/libahci.c:ahci_handle_port_interrupt",
        "drivers/ata/libahci.c:ahci_error_intr",
        "drivers/ata/libahci.c:ahci_error_intr",
        "drivers/ata/libahci.c:ahci_error_intr",
        "drivers/ata/libahci.c:ahci_error_intr",
        "drivers/ata/libahci.c:ahci_postreset",
        "drivers/ata/libahci.c:ahci_postreset",
        "drivers/ata/libahci.c:ahci_pmp_retry_softreset",
        "drivers/ata/libahci.c:ahci_bad_pmp_check_ready",
        "drivers/ata/libahci.c:ahci_bad_pmp_check_ready",
        "drivers/ata/libahci.c:ahci_check_ready",
        "drivers/ata/libahci.c:ahci_kick_engine",
        "drivers/ata/libahci.c:ahci_kick_engine",
        "drivers/ata/libahci.c:ahci_dev_classify",
        "drivers/ata/libahci.c:ahci_init_controller",
        "drivers/ata/libahci.c:ahci_init_controller",
        "drivers/ata/libahci.c:ahci_init_controller",
        "drivers/ata/libahci.c:ahci_init_controller",
        "drivers/ata/libahci.c:ahci_init_controller",
        "drivers/ata/libahci.c:ahci_transmit_led_message",
        "drivers/ata/libahci.c:ahci_reset_em",
        "drivers/ata/libahci.c:ahci_reset_controller",
        "drivers/ata/libahci.c:ahci_reset_controller",
        "drivers/ata/libahci.c:ahci_reset_controller",
        "drivers/ata/libahci.c:ahci_set_lpm",
        "drivers/ata/libahci.c:ahci_set_lpm",
        "drivers/ata/libahci.c:ahci_start_fis_rx",
        "drivers/ata/libahci.c:ahci_start_fis_rx",
        "drivers/ata/libahci.c:ahci_stop_engine",
        "drivers/ata/libahci.c:ahci_start_engine",
        "drivers/ata/libahci.c:ahci_start_engine",
        "drivers/ata/libahci.c:ahci_scr_read",
        "drivers/ata/libahci.c:ahci_save_initial_config",
        "drivers/ata/libahci.c:ahci_save_initial_config",
        "drivers/ata/libahci.c:ahci_save_initial_config",
        "drivers/ata/libahci.c:ahci_save_initial_config",
        "drivers/ata/libahci.c:ahci_save_initial_config",
        "drivers/ata/libahci.c:ahci_show_em_supported",
        "drivers/ata/libahci.c:ahci_store_em_buffer",
        "drivers/ata/libahci.c:ahci_read_em_buffer",
        "drivers/ata/libahci.c:ahci_read_em_buffer",
        "drivers/ata/libahci.c:ahci_show_port_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499845896,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/ata/libahci_platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libahci_platform.c:ahci_platform_suspend_host",
        "drivers/ata/libahci_platform.c:ahci_platform_suspend_host",
        "drivers/ata/libahci_platform.c:ahci_platform_shutdown",
        "drivers/ata/libahci_platform.c:ahci_platform_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499904060,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/spi/spi-fsl-spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_irq",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_irq",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_irq",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499911116,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/spi/spi-omap2-mcspi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_prepare_message",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_irq_handler",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup_transfer",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_tx_callback",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_callback",
        "drivers/spi/spi-omap2-mcspi.c:mcspi_wait_for_reg_bit",
        "drivers/spi/spi-omap2-mcspi.c:mcspi_wait_for_reg_bit",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_fifo",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_fifo",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs"
      ],
      "caller_func": [
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma"
      ]
    },
    {
      "addr": 18446603336499957812,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/net/phy/mdio-mux-bcm-iproc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio-mux-bcm-iproc.c:start_miim_ops",
        "drivers/net/phy/mdio-mux-bcm-iproc.c:start_miim_ops",
        "drivers/net/phy/mdio-mux-bcm-iproc.c:iproc_mdio_wait_for_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500006268,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/net/ethernet/broadcom/bgmac-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/broadcom/bgmac-platform.c:platform_bgmac_idm_read",
        "drivers/net/ethernet/broadcom/bgmac-platform.c:platform_bgmac_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500029096,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_init",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_init",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_update_ethtool_stats",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_interrupt",
        "drivers/net/ethernet/freescale/fec_main.c:fec_stop",
        "drivers/net/ethernet/freescale/fec_main.c:fec_stop",
        "drivers/net/ethernet/freescale/fec_main.c:fec_stop",
        "drivers/net/ethernet/freescale/fec_main.c:fec_restart",
        "drivers/net/ethernet/freescale/fec_main.c:fec_restart",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500037588,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/net/ethernet/freescale/fec_ptp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_adjfreq",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_read",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500041600,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/net/ethernet/freescale/xgmac_mdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500052976,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/net/ethernet/freescale/fman/fman.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fman/fman.c:fman_probe",
        "drivers/net/ethernet/freescale/fman/fman.c:fman_probe",
        "drivers/net/ethernet/freescale/fman/fman.c:fman_probe",
        "drivers/net/ethernet/freescale/fman/fman.c:fman_probe",
        "drivers/net/ethernet/freescale/fman/fman.c:fman_probe",
        "drivers/net/ethernet/freescale/fman/fman.c:fman_probe",
        "drivers/net/ethernet/freescale/fman/fman.c:fman_probe",
        "drivers/net/ethernet/freescale/fman/fman.c:fman_probe",
        "drivers/net/ethernet/freescale/fman/fman.c:fman_probe",
        "drivers/net/ethernet/freescale/fman/fman.c:fman_get_revision",
        "drivers/net/ethernet/freescale/fman/fman.c:fman_reset_mac",
        "drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params",
        "drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params",
        "drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params",
        "drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params",
        "drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params",
        "drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params",
        "drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params",
        "drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params",
        "drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params",
        "drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params",
        "drivers/net/ethernet/freescale/fman/fman.c:dma_init",
        "drivers/net/ethernet/freescale/fman/fman.c:disable_rams_ecc",
        "drivers/net/ethernet/freescale/fman/fman.c:enable_rams_ecc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500056844,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/net/ethernet/freescale/fman/fman_keygen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fman/fman_keygen.c:keygen_init",
        "drivers/net/ethernet/freescale/fman/fman_keygen.c:keygen_write_sp",
        "drivers/net/ethernet/freescale/fman/fman_keygen.c:keygen_write_ar_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500063008,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/net/ethernet/freescale/fman/fman_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver",
        "drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver",
        "drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500076300,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/net/ethernet/freescale/fman/fman_dtsec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_exception",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_exception",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_exception",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_exception",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_get_version",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_adjust_link",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_adjust_link",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_adjust_link",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_adjust_link",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_promiscuous",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_promiscuous",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_del_hash_mac_address",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_tstamp",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_tstamp",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_allmulti",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_add_hash_mac_address",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_modify_mac_address",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_modify_mac_address",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_accept_rx_pause_frames",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_accept_rx_pause_frames",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_accept_rx_pause_frames",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_tx_pause_frames",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_tx_pause_frames",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_tx_pause_frames",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_tx_pause_frames",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_tx_pause_frames",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_disable",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_enable",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_1588_isr",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_1588_isr",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:set_bucket",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:set_bucket",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500082332,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/net/ethernet/freescale/fman/fman_memac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fman/fman_memac.c:memac_init",
        "drivers/net/ethernet/freescale/fman/fman_memac.c:memac_init",
        "drivers/net/ethernet/freescale/fman/fman_memac.c:memac_init",
        "drivers/net/ethernet/freescale/fman/fman_memac.c:memac_accept_rx_pause_frames",
        "drivers/net/ethernet/freescale/fman/fman_memac.c:memac_set_tx_pause_frames",
        "drivers/net/ethernet/freescale/fman/fman_memac.c:memac_set_tx_pause_frames",
        "drivers/net/ethernet/freescale/fman/fman_memac.c:memac_set_tx_pause_frames",
        "drivers/net/ethernet/freescale/fman/fman_memac.c:memac_set_tx_pause_frames",
        "drivers/net/ethernet/freescale/fman/fman_memac.c:memac_adjust_link",
        "drivers/net/ethernet/freescale/fman/fman_memac.c:memac_set_promiscuous",
        "drivers/net/ethernet/freescale/fman/fman_memac.c:memac_disable",
        "drivers/net/ethernet/freescale/fman/fman_memac.c:memac_enable",
        "drivers/net/ethernet/freescale/fman/fman_memac.c:memac_exception",
        "drivers/net/ethernet/freescale/fman/fman_memac.c:memac_exception",
        "drivers/net/ethernet/freescale/fman/fman_memac.c:memac_err_exception",
        "drivers/net/ethernet/freescale/fman/fman_memac.c:memac_err_exception",
        "drivers/net/ethernet/freescale/fman/fman_memac.c:set_exception"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500086996,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/net/ethernet/freescale/fman/fman_tgec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_init",
        "drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_init",
        "drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_exception",
        "drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_exception",
        "drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_get_version",
        "drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_tstamp",
        "drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_accept_rx_pause_frames",
        "drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_promiscuous",
        "drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_disable",
        "drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_enable",
        "drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_err_exception",
        "drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_err_exception"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500099580,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/net/ethernet/smsc/smc91x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500353400,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/phy/phy-mxs-usb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500355368,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/phy/phy-ulpi-viewport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_read",
        "drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500363364,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel",
        "drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear",
        "drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set",
        "drivers/usb/dwc2/core.c:dwc2_hw_is_device",
        "drivers/usb/dwc2/core.c:dwc2_hw_is_host",
        "drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts",
        "drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts",
        "drivers/usb/dwc2/core.c:dwc2_is_controller_alive",
        "drivers/usb/dwc2/core.c:dwc2_enable_acg",
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/core.c:dwc2_force_mode",
        "drivers/usb/dwc2/core.c:dwc2_force_mode",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled",
        "drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled",
        "drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled",
        "drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled",
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
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500368768,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500372420,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:dwc2_resume",
        "drivers/usb/dwc2/platform.c:dwc2_suspend",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500377688,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500412832,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer",
        "drivers/usb/dwc2/hcd.c:dwc2_read_packet",
        "drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval",
        "drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval",
        "drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts",
        "drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500425036,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500431524,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500437168,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500449140,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci",
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci",
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci",
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci",
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci",
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci",
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci",
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci",
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci"
      ],
      "caller_func": [
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci",
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci"
      ]
    },
    {
      "addr": 18446603336500499608,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_get_frame",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_silence_controller",
        "drivers/usb/host/ehci-hcd.c:iso_stream_schedule",
        "drivers/usb/host/ehci-hcd.c:ehci_port_power",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_status_data",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_status_data",
        "drivers/usb/host/ehci-hcd.c:set_owner",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_clear_command_bit",
        "drivers/usb/host/ehci-hcd.c:ehci_set_command_bit",
        "drivers/usb/host/ehci-hcd.c:ehci_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/ehci-hcd.c:ehci_handshake",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer"
      ],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_resume",
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_reset",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer"
      ]
    },
    {
      "addr": 18446603336500503224,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/host/ehci-pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    },
    {
      "addr": 18446603336500505956,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/host/ehci-orion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500534228,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:_ohci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_usb_reset",
        "drivers/usb/host/ohci-hcd.c:start_ed_unlink",
        "drivers/usb/host/ohci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ohci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ohci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ohci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data"
      ]
    },
    {
      "addr": 18446603336500584200,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:compliance_mode_recovery",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_quiesce",
        "drivers/usb/host/xhci.c:xhci_quiesce",
        "drivers/usb/host/xhci.c:xhci_handshake",
        "drivers/usb/host/xhci.c:xhci_handshake"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs"
      ]
    },
    {
      "addr": 18446603336500620508,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_add_in_port",
        "drivers/usb/host/xhci-mem.c:xhci_add_in_port",
        "drivers/usb/host/xhci-mem.c:xhci_add_in_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500623896,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500642936,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500669784,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_test_and_clear_bit",
        "drivers/usb/host/xhci-hub.c:xhci_set_link_state",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ]
    },
    {
      "addr": 18446603336500690324,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500708008,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500711892,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500824720,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/rtc/rtc-mv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-mv.c:mv_rtc_interrupt",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_time"
      ],
      "caller_func": [
        "drivers/rtc/rtc-mv.c:mv_rtc_probe",
        "drivers/rtc/rtc-mv.c:mv_rtc_probe"
      ]
    },
    {
      "addr": 18446603336500825332,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/rtc/rtc-rtd119x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_remove",
        "drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe",
        "drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe",
        "drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_set_time",
        "drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_read_time",
        "drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_read_time",
        "drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_read_time",
        "drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_read_time",
        "drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_read_time",
        "drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_read_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500829144,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/rtc/rtc-sun6i.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_getalarm",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_getalarm",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_gettime",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_gettime",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_gettime",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_gettime",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_alarmirq",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_osc_set_parent",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_osc_get_parent",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_osc_recalc_rate",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_osc_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500831020,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/rtc/rtc-xgene.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-xgene.c:xgene_rtc_suspend",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_alarm_irq_enable",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_read_alarm",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_set_time",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_read_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500874016,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:dw_readl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500892128,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/i2c/busses/i2c-sprd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_isr",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_isr",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_isr",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_isr_thread",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_isr_thread",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_enable",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_enable",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_enable",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_data_transfer",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_data_transfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501041340,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/watchdog/rtd119x_wdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_ping",
        "drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501263536,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/edac/altera_edac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/altera_edac.c:s10_edac_dberr_handler",
        "drivers/edac/altera_edac.c:altr_edac_a10_device_trig2",
        "drivers/edac/altera_edac.c:altr_edac_a10_device_trig2",
        "drivers/edac/altera_edac.c:altr_edac_a10_device_trig2",
        "drivers/edac/altera_edac.c:altr_edac_a10_device_trig2",
        "drivers/edac/altera_edac.c:altr_edac_a10_device_trig2",
        "drivers/edac/altera_edac.c:altr_edac_a10_device_trig2",
        "drivers/edac/altera_edac.c:altr_check_ocram_deps_init"
      ],
      "caller_func": [
        "drivers/edac/altera_edac.c:altr_init_a10_ecc_block",
        "drivers/edac/altera_edac.c:altr_init_a10_ecc_block",
        "drivers/edac/altera_edac.c:altr_init_memory_port",
        "drivers/edac/altera_edac.c:altr_init_memory_port"
      ]
    },
    {
      "addr": 18446603336501459112,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/mmc/host/mmci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/mmci.c:mmci_irq",
        "drivers/mmc/host/mmci.c:mmci_irq",
        "drivers/mmc/host/mmci.c:mmci_pio_irq",
        "drivers/mmc/host/mmci.c:mmci_pio_irq",
        "drivers/mmc/host/mmci.c:mmci_pio_irq",
        "drivers/mmc/host/mmci.c:mmci_pio_irq",
        "drivers/mmc/host/mmci.c:mmci_pio_irq",
        "drivers/mmc/host/mmci.c:mmci_pio_irq",
        "drivers/mmc/host/mmci.c:mmci_pio_irq",
        "drivers/mmc/host/mmci.c:mmci_pio_irq",
        "drivers/mmc/host/mmci.c:mmci_pio_irq",
        "drivers/mmc/host/mmci.c:mmci_get_rx_fifocnt",
        "drivers/mmc/host/mmci.c:mmci_cmd_irq",
        "drivers/mmc/host/mmci.c:mmci_cmd_irq",
        "drivers/mmc/host/mmci.c:mmci_cmd_irq",
        "drivers/mmc/host/mmci.c:mmci_cmd_irq",
        "drivers/mmc/host/mmci.c:mmci_cmd_irq",
        "drivers/mmc/host/mmci.c:mmci_cmd_irq",
        "drivers/mmc/host/mmci.c:mmci_cmd_irq",
        "drivers/mmc/host/mmci.c:mmci_data_irq",
        "drivers/mmc/host/mmci.c:mmci_start_data",
        "drivers/mmc/host/mmci.c:mmci_dmae_finalize",
        "drivers/mmc/host/mmci.c:mmci_set_mask1",
        "drivers/mmc/host/mmci.c:mmci_dma_start",
        "drivers/mmc/host/mmci.c:mmci_card_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501460272,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/mmc/host/mmci_qcom_dml.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start",
        "drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start",
        "drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start",
        "drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501520484,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/firmware/arm_scmi/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/driver.c:scmi_xfer_done_no_timeout",
        "drivers/firmware/arm_scmi/driver.c:scmi_xfer_done_no_timeout",
        "drivers/firmware/arm_scmi/driver.c:scmi_rx_callback",
        "drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare",
        "drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare",
        "drivers/firmware/arm_scmi/driver.c:scmi_fetch_response",
        "drivers/firmware/arm_scmi/driver.c:scmi_fetch_response"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501529468,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/firmware/arm_scmi/perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_level_get",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501574868,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clocksource/sh_cmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_cmt.c:sh_cmt_read32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501582612,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clocksource/sh_tmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_tmu.c:sh_tmu_clocksource_read",
        "drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501584712,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clocksource/mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/mmio.c:clocksource_mmio_readl_down",
        "drivers/clocksource/mmio.c:clocksource_mmio_readl_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501585120,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clocksource/timer-rockchip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-rockchip.c:rk_timer_sched_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511293676,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clocksource/timer-mediatek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-mediatek.c:mtk_gpt_init",
        "drivers/clocksource/timer-mediatek.c:mtk_gpt_read_sched_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501586392,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clocksource/timer-owl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-owl.c:owl_timer_set_next_event",
        "drivers/clocksource/timer-owl.c:owl_timer_set_next_event",
        "drivers/clocksource/timer-owl.c:owl_timer_set_state_shutdown",
        "drivers/clocksource/timer-owl.c:owl_timer_sched_read"
      ],
      "caller_func": [
        "drivers/clocksource/timer-owl.c:owl_timer_init"
      ]
    },
    {
      "addr": 18446603336501586548,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clocksource/timer-sprd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-sprd.c:sprd_suspend_timer_disable",
        "drivers/clocksource/timer-sprd.c:sprd_suspend_timer_enable",
        "drivers/clocksource/timer-sprd.c:sprd_suspend_timer_read",
        "drivers/clocksource/timer-sprd.c:sprd_timer_interrupt",
        "drivers/clocksource/timer-sprd.c:sprd_timer_interrupt",
        "drivers/clocksource/timer-sprd.c:sprd_timer_shutdown",
        "drivers/clocksource/timer-sprd.c:sprd_timer_set_periodic",
        "drivers/clocksource/timer-sprd.c:sprd_timer_set_periodic",
        "drivers/clocksource/timer-sprd.c:sprd_timer_set_next_event",
        "drivers/clocksource/timer-sprd.c:sprd_timer_set_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501588896,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clocksource/arm_arch_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/arm_arch_timer.c:arch_counter_get_cntvct_mem",
        "drivers/clocksource/arm_arch_timer.c:arch_counter_get_cntvct_mem",
        "drivers/clocksource/arm_arch_timer.c:arch_counter_get_cntvct_mem",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_set_next_event_phys_mem",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_set_next_event_virt_mem",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_shutdown_phys_mem",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_shutdown_virt_mem",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_handler_virt_mem",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_handler_phys_mem"
      ],
      "caller_func": [
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_find_best_frame",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_find_best_frame",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_frame_get_cntfrq"
      ]
    },
    {
      "addr": 18446603336501591984,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clocksource/timer-sp804.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-sp804.c:sp804_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501592448,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clocksource/timer-versatile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-versatile.c:versatile_sys_24mhz_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511300172,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/clocksource/timer-imx-sysctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-imx-sysctr.c:sysctr_timer_init",
        "drivers/clocksource/timer-imx-sysctr.c:sysctr_set_next_event",
        "drivers/clocksource/timer-imx-sysctr.c:sysctr_set_next_event",
        "drivers/clocksource/timer-imx-sysctr.c:sysctr_set_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501669432,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/mailbox/pl320-ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pl320-ipc.c:__ipc_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501670052,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/mailbox/rockchip-mailbox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501671652,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:read_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501674796,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/mailbox/bcm2835-mailbox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/bcm2835-mailbox.c:bcm2835_last_tx_done",
        "drivers/mailbox/bcm2835-mailbox.c:bcm2835_mbox_irq",
        "drivers/mailbox/bcm2835-mailbox.c:bcm2835_mbox_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501678160,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/mailbox/ti-msgmgr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/ti-msgmgr.c:ti_msgmgr_queue_startup",
        "drivers/mailbox/ti-msgmgr.c:ti_msgmgr_queue_startup",
        "drivers/mailbox/ti-msgmgr.c:ti_msgmgr_send_data",
        "drivers/mailbox/ti-msgmgr.c:ti_msgmgr_last_tx_done",
        "drivers/mailbox/ti-msgmgr.c:ti_msgmgr_last_tx_done",
        "drivers/mailbox/ti-msgmgr.c:ti_msgmgr_queue_peek_data",
        "drivers/mailbox/ti-msgmgr.c:ti_msgmgr_queue_peek_data",
        "drivers/mailbox/ti-msgmgr.c:ti_msgmgr_queue_rx_interrupt",
        "drivers/mailbox/ti-msgmgr.c:ti_msgmgr_queue_rx_interrupt",
        "drivers/mailbox/ti-msgmgr.c:ti_msgmgr_queue_rx_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501734228,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/memory/brcmstb_dpfe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/memory/brcmstb_dpfe.c:show_vendor",
        "drivers/memory/brcmstb_dpfe.c:show_vendor",
        "drivers/memory/brcmstb_dpfe.c:show_vendor",
        "drivers/memory/brcmstb_dpfe.c:show_vendor",
        "drivers/memory/brcmstb_dpfe.c:show_vendor",
        "drivers/memory/brcmstb_dpfe.c:show_refresh",
        "drivers/memory/brcmstb_dpfe.c:show_refresh",
        "drivers/memory/brcmstb_dpfe.c:show_refresh",
        "drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_download_firmware",
        "drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_download_firmware",
        "drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_download_firmware",
        "drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_download_firmware",
        "drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_download_firmware",
        "drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_download_firmware",
        "drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_download_firmware",
        "drivers/memory/brcmstb_dpfe.c:__send_command",
        "drivers/memory/brcmstb_dpfe.c:__send_command",
        "drivers/memory/brcmstb_dpfe.c:__send_command"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501736416,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/memory/fsl_ifc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_irq",
        "drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_irq",
        "drivers/memory/fsl_ifc.c:check_nand_stat",
        "drivers/memory/fsl_ifc.c:check_nand_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501737900,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/memory/mtk-smi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/memory/mtk-smi.c:mtk_smi_larb_config_port_gen1",
        "drivers/memory/mtk-smi.c:mtk_smi_larb_config_port_gen2_general"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501758464,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/perf/arm-cci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-cci.c:cci_pmu_probe",
        "drivers/perf/arm-cci.c:cci_pmu_disable",
        "drivers/perf/arm-cci.c:pmu_handle_irq",
        "drivers/perf/arm-cci.c:pmu_handle_irq",
        "drivers/perf/arm-cci.c:pmu_event_update",
        "drivers/perf/arm-cci.c:cci5xx_pmu_write_counters",
        "drivers/perf/arm-cci.c:cci5xx_pmu_write_counters",
        "drivers/perf/arm-cci.c:cci5xx_pmu_write_counters",
        "drivers/perf/arm-cci.c:__cci_pmu_enable_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501770152,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/perf/arm-ccn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-ccn.c:arm_ccn_probe",
        "drivers/perf/arm-ccn.c:arm_ccn_irq_handler",
        "drivers/perf/arm-ccn.c:arm_ccn_irq_handler",
        "drivers/perf/arm-ccn.c:arm_ccn_for_each_valid_region",
        "drivers/perf/arm-ccn.c:arm_ccn_for_each_valid_region",
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_overflow_handler",
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_disable",
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_enable",
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_xp_dt_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501784112,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_isr",
        "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_disable_counter_int",
        "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_enable_counter_int",
        "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_disable_counter",
        "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_enable_counter",
        "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_stop_counters",
        "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_start_counters",
        "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_write_evtype"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501786248,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_isr",
        "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_disable_counter_int",
        "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_enable_counter_int",
        "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_disable_counter",
        "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_enable_counter",
        "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_stop_counters",
        "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_start_counters",
        "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_write_evtype"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501788368,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_isr",
        "drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_disable_counter_int",
        "drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_enable_counter_int",
        "drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_disable_counter",
        "drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_enable_counter",
        "drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_stop_counters",
        "drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_start_counters",
        "drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501799684,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/perf/qcom_l3_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__handle_irq",
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_update",
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_stop",
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_start",
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_update",
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_update",
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_update",
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_stop",
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501807328,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:72",
      "file": "drivers/perf/xgene_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/xgene_pmu.c:xgene_pmu_isr",
        "drivers/perf/xgene_pmu.c:xgene_pmu_stop_counters",
        "drivers/perf/xgene_pmu.c:xgene_pmu_start_counters",
        "drivers/perf/xgene_pmu.c:xgene_pmu_reset_counters",
        "drivers/perf/xgene_pmu.c:xgene_pmu_disable_counter_int",
        "drivers/perf/xgene_pmu.c:xgene_pmu_enable_counter_int",
        "drivers/perf/xgene_pmu.c:xgene_pmu_disable_counter",
        "drivers/perf/xgene_pmu.c:xgene_pmu_enable_counter",
        "drivers/perf/xgene_pmu.c:xgene_pmu_read_counter64",
        "drivers/perf/xgene_pmu.c:xgene_pmu_read_counter64",
        "drivers/perf/xgene_pmu.c:xgene_pmu_read_counter64"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496363208,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336496372120,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336496361608,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336496371592,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336496381392,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336496947128,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336497035416,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336497101208,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336497107408,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336497115808,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336497118864,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336497177472,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336497336832,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336497792416,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336497933768,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336497936392,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336497939688,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336498018912,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336498043944,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336498076896,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336498082964,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336498082976,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336498120552,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336498143604,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336498650696,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336498885544,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336498903904,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336499817680,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336499906768,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336500443752,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336500451168,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336500503224,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336500506312,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336500565064,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336500655608,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336500824096,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336501253736,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336501586064,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336501587112,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336501800064,
      "name": "__raw_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__raw_readl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224454472,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/kernel/smp_scu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/smp_scu.c:scu_enable",
        "arch/arm/kernel/smp_scu.c:scu_enable",
        "arch/arm/kernel/smp_scu.c:scu_get_core_count"
      ],
      "caller_func": []
    },
    {
      "addr": 3224455720,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/kernel/smp_twd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/smp_twd.c:twd_timer_setup",
        "arch/arm/kernel/smp_twd.c:twd_handler",
        "arch/arm/kernel/smp_twd.c:twd_set_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3224477232,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/kernel/io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/io.c:atomic_io_modify",
        "arch/arm/kernel/io.c:atomic_io_modify_relaxed"
      ],
      "caller_func": []
    },
    {
      "addr": 3243285464,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mm/cache-feroceon-l2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/cache-feroceon-l2.c:feroceon_of_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243290540,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mm/cache-l2x0.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/cache-l2x0.c:l2x0_of_init",
        "arch/arm/mm/cache-l2x0.c:l2x0_of_init",
        "arch/arm/mm/cache-l2x0.c:l2x0_of_init",
        "arch/arm/mm/cache-l2x0.c:tauros3_configure",
        "arch/arm/mm/cache-l2x0.c:tauros3_save",
        "arch/arm/mm/cache-l2x0.c:tauros3_save",
        "arch/arm/mm/cache-l2x0.c:tauros3_save",
        "arch/arm/mm/cache-l2x0.c:aurora_save",
        "arch/arm/mm/cache-l2x0.c:aurora_save",
        "arch/arm/mm/cache-l2x0.c:aurora_disable",
        "arch/arm/mm/cache-l2x0.c:__l2c_init",
        "arch/arm/mm/cache-l2x0.c:__l2c_init",
        "arch/arm/mm/cache-l2x0.c:__l2c_init",
        "arch/arm/mm/cache-l2x0.c:l2c310_enable",
        "arch/arm/mm/cache-l2x0.c:l2c310_enable",
        "arch/arm/mm/cache-l2x0.c:l2c310_enable",
        "arch/arm/mm/cache-l2x0.c:l2c310_enable",
        "arch/arm/mm/cache-l2x0.c:l2c310_enable",
        "arch/arm/mm/cache-l2x0.c:l2c310_configure",
        "arch/arm/mm/cache-l2x0.c:l2c310_configure",
        "arch/arm/mm/cache-l2x0.c:l2c310_configure",
        "arch/arm/mm/cache-l2x0.c:l2c310_configure",
        "arch/arm/mm/cache-l2x0.c:l2c310_configure",
        "arch/arm/mm/cache-l2x0.c:l2c310_configure",
        "arch/arm/mm/cache-l2x0.c:l2c310_configure",
        "arch/arm/mm/cache-l2x0.c:l2c310_configure",
        "arch/arm/mm/cache-l2x0.c:l2c310_save",
        "arch/arm/mm/cache-l2x0.c:l2c310_save",
        "arch/arm/mm/cache-l2x0.c:l2c310_save",
        "arch/arm/mm/cache-l2x0.c:l2c310_save",
        "arch/arm/mm/cache-l2x0.c:l2c310_save",
        "arch/arm/mm/cache-l2x0.c:l2c310_save",
        "arch/arm/mm/cache-l2x0.c:l2c310_save",
        "arch/arm/mm/cache-l2x0.c:l2c310_save",
        "arch/arm/mm/cache-l2x0.c:l2c310_flush_all_erratum",
        "arch/arm/mm/cache-l2x0.c:l2c310_flush_all_erratum",
        "arch/arm/mm/cache-l2x0.c:l2c310_flush_range_erratum",
        "arch/arm/mm/cache-l2x0.c:l2c310_flush_range_erratum",
        "arch/arm/mm/cache-l2x0.c:l2c310_inv_range_erratum",
        "arch/arm/mm/cache-l2x0.c:l2c310_inv_range_erratum",
        "arch/arm/mm/cache-l2x0.c:l2c220_sync",
        "arch/arm/mm/cache-l2x0.c:l2c220_flush_range",
        "arch/arm/mm/cache-l2x0.c:l2c220_flush_range",
        "arch/arm/mm/cache-l2x0.c:l2c220_clean_range",
        "arch/arm/mm/cache-l2x0.c:l2c220_clean_range",
        "arch/arm/mm/cache-l2x0.c:l2c220_inv_range",
        "arch/arm/mm/cache-l2x0.c:l2c220_inv_range",
        "arch/arm/mm/cache-l2x0.c:l2c220_inv_range",
        "arch/arm/mm/cache-l2x0.c:l2c220_op_pa_range",
        "arch/arm/mm/cache-l2x0.c:l2c220_op_way",
        "arch/arm/mm/cache-l2x0.c:l2c_resume",
        "arch/arm/mm/cache-l2x0.c:l2c_disable",
        "arch/arm/mm/cache-l2x0.c:l2c_enable",
        "arch/arm/mm/cache-l2x0.c:l2c_enable",
        "arch/arm/mm/cache-l2x0.c:__l2c_op_way",
        "arch/arm/mm/cache-l2x0.c:l2x0_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243291156,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mm/cache-l2x0-pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_init",
        "arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_resume",
        "arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_poll",
        "arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_poll",
        "arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3243292600,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mm/cache-uniphier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/cache-uniphier.c:__uniphier_cache_init",
        "arch/arm/mm/cache-uniphier.c:uniphier_cache_sync",
        "arch/arm/mm/cache-uniphier.c:uniphier_cache_maint_all",
        "arch/arm/mm/cache-uniphier.c:__uniphier_cache_maint_range",
        "arch/arm/mm/cache-uniphier.c:__uniphier_cache_maint_range",
        "arch/arm/mm/cache-uniphier.c:__uniphier_cache_maint_common",
        "arch/arm/mm/cache-uniphier.c:__uniphier_cache_maint_common"
      ],
      "caller_func": []
    },
    {
      "addr": 3243295104,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-alpine/alpine_cpu_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-alpine/alpine_cpu_pm.c:alpine_cpu_pm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3224554236,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-berlin/platsmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-berlin/platsmp.c:berlin_cpu_kill",
        "arch/arm/mach-berlin/platsmp.c:berlin_boot_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 3224554516,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-exynos/exynos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-exynos/exynos.c:exynos_set_delayed_reset_assertion"
      ],
      "caller_func": []
    },
    {
      "addr": 3224555672,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-exynos/firmware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-exynos/firmware.c:exynos_clear_boot_flag",
        "arch/arm/mach-exynos/firmware.c:exynos_set_boot_flag",
        "arch/arm/mach-exynos/firmware.c:exynos_get_cpu_boot_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 3224556540,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-exynos/pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-exynos/pm.c:exynos_enter_aftr",
        "arch/arm/mach-exynos/pm.c:exynos_enter_aftr"
      ],
      "caller_func": []
    },
    {
      "addr": 3224558220,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-exynos/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-exynos/suspend.c:exynos_suspend_enter",
        "arch/arm/mach-exynos/suspend.c:exynos_suspend_enter",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos3250_pm_prepare",
        "arch/arm/mach-exynos/suspend.c:exynos_pm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3224561408,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-exynos/platsmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-exynos/platsmp.c:exynos_boot_secondary",
        "arch/arm/mach-exynos/platsmp.c:exynos_boot_secondary",
        "arch/arm/mach-exynos/platsmp.c:exynos_get_boot_addr",
        "arch/arm/mach-exynos/platsmp.c:exynos_cluster_power_state",
        "arch/arm/mach-exynos/platsmp.c:exynos_cpu_power_down",
        "arch/arm/mach-exynos/platsmp.c:exynos_cpu_power_down"
      ],
      "caller_func": []
    },
    {
      "addr": 3243297616,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-exynos/mcpm-exynos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-exynos/mcpm-exynos.c:exynos_mcpm_init",
        "arch/arm/mach-exynos/mcpm-exynos.c:exynos_cpu_powerup"
      ],
      "caller_func": []
    },
    {
      "addr": 3224563660,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-highbank/highbank.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3224565012,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-hisi/platmcpm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-hisi/platmcpm.c:hip04_cpu_kill",
        "arch/arm/mach-hisi/platmcpm.c:hip04_cpu_kill",
        "arch/arm/mach-hisi/platmcpm.c:hip04_boot_secondary",
        "arch/arm/mach-hisi/platmcpm.c:hip04_boot_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 3224566068,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-hisi/platsmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-hisi/platsmp.c:hip01_boot_secondary",
        "arch/arm/mach-hisi/platsmp.c:hi3xxx_get_cpu_jump"
      ],
      "caller_func": []
    },
    {
      "addr": 3224567104,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-hisi/hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-hisi/hotplug.c:hip01_set_cpu",
        "arch/arm/mach-hisi/hotplug.c:hip01_set_cpu",
        "arch/arm/mach-hisi/hotplug.c:hi3xxx_set_cpu",
        "arch/arm/mach-hisi/hotplug.c:hi3xxx_set_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3224569704,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-meson/platsmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-meson/platsmp.c:meson8_smp_cpu_die",
        "arch/arm/mach-meson/platsmp.c:meson_smp_finalize_secondary_boot",
        "arch/arm/mach-meson/platsmp.c:meson_smp_finalize_secondary_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 3224570040,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-mvebu/system-controller.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-mvebu/system-controller.c:mvebu_system_controller_get_soc_id",
        "arch/arm/mach-mvebu/system-controller.c:mvebu_system_controller_get_soc_id"
      ],
      "caller_func": []
    },
    {
      "addr": 3243299964,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-mvebu/mvebu-soc-id.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-mvebu/mvebu-soc-id.c:mvebu_soc_id_init",
        "arch/arm/mach-mvebu/mvebu-soc-id.c:mvebu_soc_id_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3224570472,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-mvebu/cpu-reset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-mvebu/cpu-reset.c:mvebu_cpu_reset_deassert"
      ],
      "caller_func": []
    },
    {
      "addr": 3224570652,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-mvebu/coherency.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-mvebu/coherency.c:armada_xp_clear_shared_l2"
      ],
      "caller_func": []
    },
    {
      "addr": 3224572712,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-mvebu/pmsu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-mvebu/pmsu.c:mvebu_pmsu_dfs_request",
        "arch/arm/mach-mvebu/pmsu.c:mvebu_pmsu_dfs_request",
        "arch/arm/mach-mvebu/pmsu.c:mvebu_pmsu_dfs_request",
        "arch/arm/mach-mvebu/pmsu.c:mvebu_pmsu_dfs_request",
        "arch/arm/mach-mvebu/pmsu.c:mvebu_pmsu_dfs_request_local",
        "arch/arm/mach-mvebu/pmsu.c:mvebu_pmsu_dfs_request_local",
        "arch/arm/mach-mvebu/pmsu.c:mvebu_pmsu_dfs_request_local",
        "arch/arm/mach-mvebu/pmsu.c:mvebu_v7_cpu_pm_init",
        "arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_idle_exit",
        "arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_idle_exit",
        "arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_idle_prepare",
        "arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_idle_prepare",
        "arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_idle_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 3224573128,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-mvebu/pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-mvebu/pm.c:mvebu_pm_powerdown",
        "arch/arm/mach-mvebu/pm.c:mvebu_pm_powerdown",
        "arch/arm/mach-mvebu/pm.c:mvebu_pm_powerdown"
      ],
      "caller_func": []
    },
    {
      "addr": 3224573832,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-mvebu/pm-board.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-mvebu/pm-board.c:mvebu_armada_pm_enter",
        "arch/arm/mach-mvebu/pm-board.c:mvebu_armada_pm_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3243304496,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-imx/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-imx/cpu.c:imx_set_aips"
      ],
      "caller_func": []
    },
    {
      "addr": 3243305532,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-imx/system.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-imx/system.c:imx_init_l2cache",
        "arch/arm/mach-imx/system.c:imx_init_l2cache"
      ],
      "caller_func": []
    },
    {
      "addr": 3243305780,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-imx/cpu-imx5.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-imx/cpu-imx5.c:imx5_pmu_init",
        "arch/arm/mach-imx/cpu-imx5.c:imx5_read_srev_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 3224575912,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-imx/pm-imx5.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-imx/pm-imx5.c:mx5_cpu_lp_set",
        "arch/arm/mach-imx/pm-imx5.c:mx5_cpu_lp_set",
        "arch/arm/mach-imx/pm-imx5.c:mx5_cpu_lp_set",
        "arch/arm/mach-imx/pm-imx5.c:mx5_cpu_lp_set",
        "arch/arm/mach-imx/pm-imx5.c:mx5_cpu_lp_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3224576604,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-imx/tzic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-imx/tzic.c:tzic_enable_wake",
        "arch/arm/mach-imx/tzic.c:tzic_enable_wake",
        "arch/arm/mach-imx/tzic.c:tzic_init_dt",
        "arch/arm/mach-imx/tzic.c:tzic_handle_irq",
        "arch/arm/mach-imx/tzic.c:tzic_handle_irq",
        "arch/arm/mach-imx/tzic.c:tzic_irq_resume",
        "arch/arm/mach-imx/tzic.c:tzic_set_irq_fiq"
      ],
      "caller_func": []
    },
    {
      "addr": 3243307092,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-imx/anatop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-imx/anatop.c:imx_init_revision_from_anatop",
        "arch/arm/mach-imx/anatop.c:imx_init_revision_from_anatop"
      ],
      "caller_func": []
    },
    {
      "addr": 3224578664,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-imx/gpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-imx/gpc.c:imx_gpc_irq_mask",
        "arch/arm/mach-imx/gpc.c:imx_gpc_irq_unmask",
        "arch/arm/mach-imx/gpc.c:imx_gpc_mask_all",
        "arch/arm/mach-imx/gpc.c:imx_gpc_pre_suspend",
        "arch/arm/mach-imx/gpc.c:imx_gpc_set_l2_mem_power_in_lpm"
      ],
      "caller_func": []
    },
    {
      "addr": 3224580620,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-imx/mmdc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-imx/mmdc.c:imx_mmdc_probe",
        "arch/arm/mach-imx/mmdc.c:imx_mmdc_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3243307992,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-imx/src.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-imx/src.c:imx_src_init",
        "arch/arm/mach-imx/src.c:imx_get_cpu_arg",
        "arch/arm/mach-imx/src.c:imx_enable_cpu",
        "arch/arm/mach-imx/src.c:imx_src_reset_module",
        "arch/arm/mach-imx/src.c:imx_src_reset_module"
      ],
      "caller_func": []
    },
    {
      "addr": 3243311364,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-imx/pm-imx7ulp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-imx/pm-imx7ulp.c:imx7ulp_pm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243312572,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-imx/pm-imx6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-imx/pm-imx6.c:imx6_pm_ccm_init",
        "arch/arm/mach-imx/pm-imx6.c:imx6q_suspend_init",
        "arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter",
        "arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter",
        "arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter",
        "arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter",
        "arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter",
        "arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter",
        "arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter",
        "arch/arm/mach-imx/pm-imx6.c:imx6_set_lpm",
        "arch/arm/mach-imx/pm-imx6.c:imx6_enable_rbc",
        "arch/arm/mach-imx/pm-imx6.c:imx6_enable_rbc"
      ],
      "caller_func": []
    },
    {
      "addr": 3243313056,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-imx/mach-imx51.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-imx/mach-imx51.c:imx51_dt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243318060,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/id.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/id.c:dra7xxx_check_revision",
        "arch/arm/mach-omap2/id.c:omap5xxx_check_revision",
        "arch/arm/mach-omap2/id.c:omap4xxx_check_revision",
        "arch/arm/mach-omap2/id.c:omap3xxx_check_revision",
        "arch/arm/mach-omap2/id.c:omap4xxx_check_features",
        "arch/arm/mach-omap2/id.c:omap2xxx_check_revision",
        "arch/arm/mach-omap2/id.c:omap2xxx_check_revision"
      ],
      "caller_func": []
    },
    {
      "addr": 3224590740,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/control.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/control.c:am43xx_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_ctrl_init",
        "arch/arm/mach-omap2/control.c:omap3_ctrl_init",
        "arch/arm/mach-omap2/control.c:omap3_ctrl_init",
        "arch/arm/mach-omap2/control.c:omap3_ctrl_init",
        "arch/arm/mach-omap2/control.c:omap3_ctrl_save_padconf",
        "arch/arm/mach-omap2/control.c:omap3_ctrl_save_padconf",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_control_save_context",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap_ctrl_writeb",
        "arch/arm/mach-omap2/control.c:omap_ctrl_readb"
      ],
      "caller_func": []
    },
    {
      "addr": 3243322784,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/timer.c:realtime_counter_init",
        "arch/arm/mach-omap2/timer.c:realtime_counter_init",
        "arch/arm/mach-omap2/timer.c:clocksource_read_cycles",
        "arch/arm/mach-omap2/timer.c:omap_dm_timer_init_one",
        "arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic",
        "arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic",
        "arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic",
        "arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic",
        "arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic",
        "arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic",
        "arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic",
        "arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic",
        "arch/arm/mach-omap2/timer.c:omap2_gp_timer_shutdown",
        "arch/arm/mach-omap2/timer.c:omap2_gp_timer_shutdown",
        "arch/arm/mach-omap2/timer.c:omap2_gp_timer_shutdown",
        "arch/arm/mach-omap2/timer.c:omap2_gp_timer_shutdown",
        "arch/arm/mach-omap2/timer.c:omap2_gp_timer_shutdown",
        "arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_next_event",
        "arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3243324900,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/dma.c:omap2_system_dma_init_dev",
        "arch/arm/mach-omap2/dma.c:omap2_show_dma_caps"
      ],
      "caller_func": []
    },
    {
      "addr": 3224593268,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/wd_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/wd_timer.c:omap2_wd_timer_disable",
        "arch/arm/mach-omap2/wd_timer.c:omap2_wd_timer_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 3224595356,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/omap_hwmod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/omap_hwmod.c:_wait_softreset_complete",
        "arch/arm/mach-omap2/omap_hwmod.c:_wait_softreset_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 3243330480,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/sdrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/sdrc.c:omap2_sdrc_init",
        "arch/arm/mach-omap2/sdrc.c:omap2_sdrc_init",
        "arch/arm/mach-omap2/sdrc.c:omap2_sdrc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3224616564,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/omap4-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/omap4-common.c:gic_timer_retrigger",
        "arch/arm/mach-omap2/omap4-common.c:gic_timer_retrigger",
        "arch/arm/mach-omap2/omap4-common.c:gic_timer_retrigger",
        "arch/arm/mach-omap2/omap4-common.c:gic_dist_disabled",
        "arch/arm/mach-omap2/omap4-common.c:omap_interconnect_sync",
        "arch/arm/mach-omap2/omap4-common.c:omap_interconnect_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 3243331900,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/omap-wakeupgen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init",
        "arch/arm/mach-omap2/omap-wakeupgen.c:omap_wakeupgen_cpu_dead",
        "arch/arm/mach-omap2/omap-wakeupgen.c:irq_sar_clear",
        "arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_unmask",
        "arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 3243332628,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/omap-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus",
        "arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus",
        "arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 3224619736,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/omap-hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/omap-hotplug.c:omap4_cpu_die"
      ],
      "caller_func": []
    },
    {
      "addr": 3224620728,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/ti81xx-restart.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/ti81xx-restart.c:ti81xx_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 3243333664,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/omap-mpuss-lowpower.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_early_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3224622572,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/pm34xx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/pm34xx.c:omap_sram_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 3224635264,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/prm2xxx_3xxx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_clkdm_clear_all_wkdeps",
        "arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_clkdm_read_wkdep",
        "arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_clkdm_del_wkdep",
        "arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_clkdm_add_wkdep",
        "arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_pwrdm_wait_transition",
        "arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_pwrdm_set_logic_retst",
        "arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_pwrdm_read_mem_retst",
        "arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_pwrdm_read_mem_pwrst",
        "arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_pwrdm_set_mem_retst",
        "arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_pwrdm_set_mem_onst",
        "arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_prm_deassert_hardreset",
        "arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_prm_deassert_hardreset",
        "arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_prm_deassert_hardreset",
        "arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_prm_deassert_hardreset",
        "arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_prm_assert_hardreset",
        "arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_prm_is_hardreset_asserted"
      ],
      "caller_func": []
    },
    {
      "addr": 3224636592,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/prm3xxx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_disable_hdwr_sar",
        "arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_enable_hdwr_sar",
        "arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_read_prev_mem_pwrst",
        "arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_read_prev_logic_pwrst",
        "arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_read_logic_retst",
        "arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_read_logic_pwrst",
        "arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_read_prev_pwrst",
        "arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_read_pwrst",
        "arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_read_next_pwrst",
        "arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_set_next_pwrst",
        "arch/arm/mach-omap2/prm3xxx.c:omap3_prm_save_scratchpad_contents",
        "arch/arm/mach-omap2/prm3xxx.c:omap3_prm_save_scratchpad_contents",
        "arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_global_cold_reset",
        "arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_global_cold_reset",
        "arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_read_reset_sources",
        "arch/arm/mach-omap2/prm3xxx.c:omap3_prm_reconfigure_io_chain",
        "arch/arm/mach-omap2/prm3xxx.c:omap3_prm_reconfigure_io_chain",
        "arch/arm/mach-omap2/prm3xxx.c:omap3_prm_reconfigure_io_chain",
        "arch/arm/mach-omap2/prm3xxx.c:omap3_prm_reconfigure_io_chain",
        "arch/arm/mach-omap2/prm3xxx.c:omap3_prm_reconfigure_io_chain",
        "arch/arm/mach-omap2/prm3xxx.c:omap3430_pre_es3_1_reconfigure_io_chain",
        "arch/arm/mach-omap2/prm3xxx.c:omap3430_pre_es3_1_reconfigure_io_chain",
        "arch/arm/mach-omap2/prm3xxx.c:omap3430_pre_es3_1_reconfigure_io_chain",
        "arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm",
        "arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm",
        "arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs",
        "arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs",
        "arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs",
        "arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs",
        "arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs",
        "arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs",
        "arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs",
        "arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_save_and_clear_irqen",
        "arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_save_and_clear_irqen",
        "arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_ocp_barrier",
        "arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_read_pending_irqs",
        "arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_read_pending_irqs",
        "arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_dpll3_reset",
        "arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_dpll3_reset",
        "arch/arm/mach-omap2/prm3xxx.c:omap3_prm_vcvp_rmw",
        "arch/arm/mach-omap2/prm3xxx.c:omap3_prm_vcvp_read",
        "arch/arm/mach-omap2/prm3xxx.c:omap3_prm_vp_check_txdone"
      ],
      "caller_func": []
    },
    {
      "addr": 3224640024,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/cm3xxx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_scratchpad_contents",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_scratchpad_contents",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_scratchpad_contents",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_scratchpad_contents",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_scratchpad_contents",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_scratchpad_contents",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_scratchpad_contents",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_scratchpad_contents",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_scratchpad_contents",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_scratchpad_contents",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_scratchpad_contents",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context",
        "arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_disable",
        "arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_disable",
        "arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_disable",
        "arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_disable",
        "arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_disable",
        "arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_enable",
        "arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_enable",
        "arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_enable",
        "arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_enable",
        "arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_deny_idle",
        "arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_allow_idle",
        "arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clear_all_sleepdeps",
        "arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_read_sleepdep",
        "arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_del_sleepdep",
        "arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_add_sleepdep",
        "arch/arm/mach-omap2/cm3xxx.c:omap3xxx_cm_wait_module_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 3224640288,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/cminst44xx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/cminst44xx.c:omap4_clkdm_save_context",
        "arch/arm/mach-omap2/cminst44xx.c:omap4_clkdm_clk_disable",
        "arch/arm/mach-omap2/cminst44xx.c:omap4_clkdm_read_wkup_sleep_dep",
        "arch/arm/mach-omap2/cminst44xx.c:omap4_clkdm_del_wkup_sleep_dep",
        "arch/arm/mach-omap2/cminst44xx.c:omap4_clkdm_add_wkup_sleep_dep",
        "arch/arm/mach-omap2/cminst44xx.c:omap4_cminst_module_disable",
        "arch/arm/mach-omap2/cminst44xx.c:omap4_cminst_wait_module_idle",
        "arch/arm/mach-omap2/cminst44xx.c:omap4_cminst_wait_module_ready",
        "arch/arm/mach-omap2/cminst44xx.c:_clktrctrl_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3224644828,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/prm44xx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/prm44xx.c:prm_save_context",
        "arch/arm/mach-omap2/prm44xx.c:prm_save_context",
        "arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_read_reset_sources",
        "arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_reconfigure_io_chain",
        "arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_reconfigure_io_chain",
        "arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_reconfigure_io_chain",
        "arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_reconfigure_io_chain",
        "arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_save_and_clear_irqen",
        "arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_save_and_clear_irqen",
        "arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_ocp_barrier",
        "arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_read_pending_irqs",
        "arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_read_pending_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 3224645068,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/prcm_mpu44xx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/prcm_mpu44xx.c:omap4_prcm_mpu_rmw_inst_reg_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 3224646004,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/prminst44xx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_global_warm_sw_reset",
        "arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_global_warm_sw_reset",
        "arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_deassert_hardreset",
        "arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_deassert_hardreset",
        "arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_deassert_hardreset"
      ],
      "caller_func": []
    },
    {
      "addr": 3224647752,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/prm33xx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_restore_context",
        "arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_save_context",
        "arch/arm/mach-omap2/prm33xx.c:am33xx_prm_global_warm_sw_reset",
        "arch/arm/mach-omap2/prm33xx.c:am33xx_prm_global_warm_sw_reset",
        "arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_read_mem_retst",
        "arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_read_mem_pwrst",
        "arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_set_mem_retst",
        "arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_set_mem_onst",
        "arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_read_logic_retst",
        "arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_read_logic_pwrst",
        "arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_set_logic_retst",
        "arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_clear_all_prev_pwrst",
        "arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_set_lowpwrstchange",
        "arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_read_pwrst",
        "arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_read_next_pwrst",
        "arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_set_next_pwrst",
        "arch/arm/mach-omap2/prm33xx.c:am33xx_prm_deassert_hardreset",
        "arch/arm/mach-omap2/prm33xx.c:am33xx_prm_deassert_hardreset",
        "arch/arm/mach-omap2/prm33xx.c:am33xx_prm_deassert_hardreset",
        "arch/arm/mach-omap2/prm33xx.c:am33xx_prm_deassert_hardreset",
        "arch/arm/mach-omap2/prm33xx.c:am33xx_prm_assert_hardreset"
      ],
      "caller_func": []
    },
    {
      "addr": 3224648712,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/cm33xx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_restore_context",
        "arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_restore_context",
        "arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_restore_context",
        "arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_restore_context",
        "arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_save_context",
        "arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_clk_disable",
        "arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_clk_disable",
        "arch/arm/mach-omap2/cm33xx.c:am33xx_cm_module_disable",
        "arch/arm/mach-omap2/cm33xx.c:am33xx_cm_module_enable",
        "arch/arm/mach-omap2/cm33xx.c:am33xx_cm_wait_module_idle",
        "arch/arm/mach-omap2/cm33xx.c:am33xx_cm_wait_module_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 3224659892,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-omap2/powerdomains3xxx_data.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/powerdomains3xxx_data.c:ti81xx_pwrdm_read_logic_pwrst",
        "arch/arm/mach-omap2/powerdomains3xxx_data.c:ti81xx_pwrdm_read_pwrst",
        "arch/arm/mach-omap2/powerdomains3xxx_data.c:ti81xx_pwrdm_read_next_pwrst",
        "arch/arm/mach-omap2/powerdomains3xxx_data.c:ti81xx_pwrdm_set_next_pwrst"
      ],
      "caller_func": []
    },
    {
      "addr": 3243350988,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-shmobile/setup-rcar-gen2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init",
        "arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3224672168,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-shmobile/platsmp-apmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-shmobile/platsmp-apmu.c:shmobile_smp_apmu_boot_secondary",
        "arch/arm/mach-shmobile/platsmp-apmu.c:shmobile_smp_apmu_cpu_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 3243352404,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c:rcar_gen2_regulator_quirk"
      ],
      "caller_func": []
    },
    {
      "addr": 3243353204,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-shmobile/pm-rcar-gen2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init",
        "arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3224675188,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-shmobile/smp-sh73a0.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-shmobile/smp-sh73a0.c:sh73a0_boot_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 3224675468,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-shmobile/platsmp-scu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-shmobile/platsmp-scu.c:shmobile_smp_scu_cpu_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 3224675796,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-tegra/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-tegra/irq.c:tegra_pending_sgi"
      ],
      "caller_func": []
    },
    {
      "addr": 3243354520,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-tegra/reset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-tegra/reset.c:tegra_cpu_reset_handler_init",
        "arch/arm/mach-tegra/reset.c:tegra_cpu_reset_handler_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243355680,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-vexpress/dcscb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-vexpress/dcscb.c:dcscb_init",
        "arch/arm/mach-vexpress/dcscb.c:dcscb_cluster_powerup",
        "arch/arm/mach-vexpress/dcscb.c:dcscb_cpu_powerup"
      ],
      "caller_func": []
    },
    {
      "addr": 3224686544,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-vexpress/spc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-vexpress/spc.c:spc_recalc_rate",
        "arch/arm/mach-vexpress/spc.c:ve_spc_populate_opps",
        "arch/arm/mach-vexpress/spc.c:ve_spc_irq_handler",
        "arch/arm/mach-vexpress/spc.c:ve_spc_cpu_in_wfi",
        "arch/arm/mach-vexpress/spc.c:ve_spc_cpu_wakeup_irq",
        "arch/arm/mach-vexpress/spc.c:ve_spc_global_wakeup_irq",
        "arch/arm/mach-vexpress/spc.c:ve_spc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243356972,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/mach-vexpress/tc2_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-vexpress/tc2_pm.c:tc2_pm_init",
        "arch/arm/mach-vexpress/tc2_pm.c:tc2_pm_init",
        "arch/arm/mach-vexpress/tc2_pm.c:tc2_pm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243357872,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/plat-omap/counter_32k.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/plat-omap/counter_32k.c:omap_init_clocksource_32k",
        "arch/arm/plat-omap/counter_32k.c:omap_read_persistent_clock64",
        "arch/arm/plat-omap/counter_32k.c:omap_32k_read_sched_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 3243358500,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/plat-samsung/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/plat-samsung/cpu.c:s5p_init_cpu",
        "arch/arm/plat-samsung/cpu.c:s3c64xx_init_cpu",
        "arch/arm/plat-samsung/cpu.c:s3c64xx_init_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3224697224,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "arch/arm/plat-samsung/pm-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/plat-samsung/pm-common.c:s3c_pm_do_restore",
        "arch/arm/plat-samsung/pm-common.c:s3c_pm_do_save"
      ],
      "caller_func": []
    },
    {
      "addr": 3225225584,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "kernel/irq/generic-chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:irq_gc_init_mask_cache",
        "kernel/irq/generic-chip.c:irq_readl_be"
      ],
      "caller_func": []
    },
    {
      "addr": 3228379596,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "fs/debugfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:debugfs_print_regs32"
      ],
      "caller_func": []
    },
    {
      "addr": 3229498064,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "lib/iomap_copy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iomap_copy.c:__ioread32_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 3229680020,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "lib/stmp_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/stmp_device.c:stmp_reset_block",
        "lib/stmp_device.c:stmp_clear_poll_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 3229691808,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-al-fic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-al-fic.c:al_fic_irq_handler",
        "drivers/irqchip/irq-al-fic.c:al_fic_irq_set_type"
      ],
      "caller_func": []
    },
    {
      "addr": 3229693820,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/exynos-combiner.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/exynos-combiner.c:combiner_suspend",
        "drivers/irqchip/exynos-combiner.c:combiner_handle_cascade_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3243547656,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-hip04.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-hip04.c:hip04_of_init",
        "drivers/irqchip/irq-hip04.c:hip04_handle_irq",
        "drivers/irqchip/irq-hip04.c:hip04_irq_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 3229696152,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-tegra.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-tegra.c:tegra_ictlr_suspend",
        "drivers/irqchip/irq-tegra.c:tegra_ictlr_suspend",
        "drivers/irqchip/irq-tegra.c:tegra_ictlr_suspend",
        "drivers/irqchip/irq-tegra.c:tegra_ictlr_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3243548764,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-dw-apb-ictl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init",
        "drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init",
        "drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3229697592,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-orion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-orion.c:orion_bridge_irq_handler",
        "drivers/irqchip/irq-orion.c:orion_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3243551184,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-omap-intc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-omap-intc.c:intc_of_init",
        "drivers/irqchip/irq-omap-intc.c:omap_intc_handle_irq",
        "drivers/irqchip/irq-omap-intc.c:omap_irq_pending",
        "drivers/irqchip/irq-omap-intc.c:omap_irq_soft_reset",
        "drivers/irqchip/irq-omap-intc.c:omap_irq_soft_reset",
        "drivers/irqchip/irq-omap-intc.c:omap_irq_soft_reset",
        "drivers/irqchip/irq-omap-intc.c:omap_intc_save_context",
        "drivers/irqchip/irq-omap-intc.c:omap_intc_save_context",
        "drivers/irqchip/irq-omap-intc.c:omap_intc_save_context",
        "drivers/irqchip/irq-omap-intc.c:omap_intc_save_context",
        "drivers/irqchip/irq-omap-intc.c:omap_intc_save_context",
        "drivers/irqchip/irq-omap-intc.c:omap_intc_save_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3243552440,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-gic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic.c:gic_of_init",
        "drivers/irqchip/irq-gic.c:gic_of_init",
        "drivers/irqchip/irq-gic.c:gic_of_init",
        "drivers/irqchip/irq-gic.c:gic_of_init",
        "drivers/irqchip/irq-gic.c:gic_init_bases",
        "drivers/irqchip/irq-gic.c:gic_migrate_target",
        "drivers/irqchip/irq-gic.c:gic_migrate_target",
        "drivers/irqchip/irq-gic.c:gic_cpu_save",
        "drivers/irqchip/irq-gic.c:gic_cpu_save",
        "drivers/irqchip/irq-gic.c:gic_cpu_save",
        "drivers/irqchip/irq-gic.c:gic_dist_save",
        "drivers/irqchip/irq-gic.c:gic_dist_save",
        "drivers/irqchip/irq-gic.c:gic_dist_save",
        "drivers/irqchip/irq-gic.c:gic_dist_save",
        "drivers/irqchip/irq-gic.c:gic_cpu_if_down",
        "drivers/irqchip/irq-gic.c:gic_cpu_if_up",
        "drivers/irqchip/irq-gic.c:gic_cpu_if_up",
        "drivers/irqchip/irq-gic.c:gic_get_cpumask",
        "drivers/irqchip/irq-gic.c:gic_handle_cascade_irq",
        "drivers/irqchip/irq-gic.c:gic_handle_irq",
        "drivers/irqchip/irq-gic.c:gic_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 3229704556,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-gic-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-common.c:gic_configure_irq",
        "drivers/irqchip/irq-gic-common.c:gic_configure_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3243553416,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-gic-v2m.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243556948,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3.c:gic_of_init",
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases",
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases",
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3.c:__gic_update_rdist_properties",
        "drivers/irqchip/irq-gic-v3.c:__gic_update_rdist_properties",
        "drivers/irqchip/irq-gic-v3.c:__gic_populate_rdist",
        "drivers/irqchip/irq-gic-v3.c:__gic_populate_rdist",
        "drivers/irqchip/irq-gic-v3.c:gic_iterate_rdists",
        "drivers/irqchip/irq-gic-v3.c:gic_iterate_rdists",
        "drivers/irqchip/irq-gic-v3.c:gic_iterate_rdists",
        "drivers/irqchip/irq-gic-v3.c:gic_peek_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3243559992,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its.c:its_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_restore_enable",
        "drivers/irqchip/irq-gic-v3-its.c:its_restore_enable",
        "drivers/irqchip/irq-gic-v3-its.c:its_restore_enable",
        "drivers/irqchip/irq-gic-v3-its.c:its_restore_enable",
        "drivers/irqchip/irq-gic-v3-its.c:its_save_disable",
        "drivers/irqchip/irq-gic-v3-its.c:its_save_disable",
        "drivers/irqchip/irq-gic-v3-its.c:its_save_disable",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_irqchip_state",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_send_inv",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_clear_vpend_valid",
        "drivers/irqchip/irq-gic-v3-its.c:its_clear_vpend_valid",
        "drivers/irqchip/irq-gic-v3-its.c:its_clear_vpend_valid",
        "drivers/irqchip/irq-gic-v3-its.c:its_clear_vpend_valid",
        "drivers/irqchip/irq-gic-v3-its.c:its_clear_vpend_valid",
        "drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables",
        "drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables",
        "drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables",
        "drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables",
        "drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables",
        "drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables",
        "drivers/irqchip/irq-gic-v3-its.c:its_parse_indirect_baser",
        "drivers/irqchip/irq-gic-v3-its.c:its_parse_indirect_baser",
        "drivers/irqchip/irq-gic-v3-its.c:its_parse_indirect_baser",
        "drivers/irqchip/irq-gic-v3-its.c:its_parse_indirect_baser",
        "drivers/irqchip/irq-gic-v3-its.c:its_send_single_vcommand",
        "drivers/irqchip/irq-gic-v3-its.c:its_send_single_command",
        "drivers/irqchip/irq-gic-v3-its.c:its_wait_for_range_completion",
        "drivers/irqchip/irq-gic-v3-its.c:its_allocate_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 3243562080,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-armada-370-xp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_resume",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_suspend",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_handle_irq",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_handle_irq",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_handle_cascade_irq",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_handle_cascade_irq",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_handle_msi_irq",
        "drivers/irqchip/irq-armada-370-xp.c:armada_xp_mpic_smp_cpu_init",
        "drivers/irqchip/irq-armada-370-xp.c:armada_xp_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 3224381412,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-rda-intc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-rda-intc.c:rda_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3229740296,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-renesas-intc-irqpin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_read32"
      ],
      "caller_func": []
    },
    {
      "addr": 3229744764,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-renesas-irqc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-renesas-irqc.c:irqc_irq_handler",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_type"
      ],
      "caller_func": []
    },
    {
      "addr": 3229748804,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-mtk-sysirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_set_type"
      ],
      "caller_func": []
    },
    {
      "addr": 3229749792,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-mtk-cirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_resume",
        "drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_resume",
        "drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3229751716,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-imx-gpcv2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_mask",
        "drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_unmask",
        "drivers/irqchip/irq-imx-gpcv2.c:gpcv2_wakeup_source_save"
      ],
      "caller_func": []
    },
    {
      "addr": 3243566528,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-aspeed-vic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-aspeed-vic.c:avic_of_init",
        "drivers/irqchip/irq-aspeed-vic.c:avic_of_init",
        "drivers/irqchip/irq-aspeed-vic.c:avic_handle_irq",
        "drivers/irqchip/irq-aspeed-vic.c:avic_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3229752504,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-aspeed-i2c-ic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-aspeed-i2c-ic.c:aspeed_i2c_ic_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3229752816,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-uniphier-aidet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-uniphier-aidet.c:uniphier_aidet_suspend",
        "drivers/irqchip/irq-uniphier-aidet.c:uniphier_aidet_irq_set_type"
      ],
      "caller_func": []
    },
    {
      "addr": 3229754432,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-meson-gpio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3229755292,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/qcom-pdc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/qcom-pdc.c:pdc_enable_intr"
      ],
      "caller_func": []
    },
    {
      "addr": 3229757148,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/irqchip/irq-imx-irqsteer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_suspend",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_handler",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_mask",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_unmask"
      ],
      "caller_func": []
    },
    {
      "addr": 3229759060,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/bus/arm-cci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229761264,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/bus/brcmstb_gisb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_suspend",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_suspend",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr",
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr",
        "drivers/bus/brcmstb_gisb.c:gisb_arb_get_timeout",
        "drivers/bus/brcmstb_gisb.c:gisb_arb_get_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 3229762584,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/bus/imx-weim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/imx-weim.c:weim_parse_dt"
      ],
      "caller_func": []
    },
    {
      "addr": 3229764736,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/bus/mvebu-mbus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/mvebu-mbus.c:mvebu_mbus_dove_save_cpu_target",
        "drivers/bus/mvebu-mbus.c:mvebu_mbus_dove_setup_cpu_target",
        "drivers/bus/mvebu-mbus.c:mvebu_mbus_default_save_cpu_target",
        "drivers/bus/mvebu-mbus.c:mvebu_mbus_default_save_cpu_target",
        "drivers/bus/mvebu-mbus.c:mvebu_mbus_default_setup_cpu_target",
        "drivers/bus/mvebu-mbus.c:mvebu_mbus_default_setup_cpu_target",
        "drivers/bus/mvebu-mbus.c:mvebu_sdram_debug_show_dove",
        "drivers/bus/mvebu-mbus.c:mvebu_sdram_debug_show_orion",
        "drivers/bus/mvebu-mbus.c:mvebu_sdram_debug_show_orion"
      ],
      "caller_func": []
    },
    {
      "addr": 3229769372,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/bus/omap_l3_noc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/omap_l3_noc.c:l3_resume_noirq",
        "drivers/bus/omap_l3_noc.c:l3_resume_noirq",
        "drivers/bus/omap_l3_noc.c:l3_resume_noirq",
        "drivers/bus/omap_l3_noc.c:l3_interrupt_handler",
        "drivers/bus/omap_l3_noc.c:l3_interrupt_handler",
        "drivers/bus/omap_l3_noc.c:l3_interrupt_handler",
        "drivers/bus/omap_l3_noc.c:l3_interrupt_handler",
        "drivers/bus/omap_l3_noc.c:l3_interrupt_handler",
        "drivers/bus/omap_l3_noc.c:l3_interrupt_handler",
        "drivers/bus/omap_l3_noc.c:l3_interrupt_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3229771352,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/bus/qcom-ebi2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3229780448,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/bus/ti-sysc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/ti-sysc.c:sysc_init_module",
        "drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt",
        "drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt",
        "drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt",
        "drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt",
        "drivers/bus/ti-sysc.c:sysc_clk_quirk_i2c",
        "drivers/bus/ti-sysc.c:sysc_pre_reset_quirk_hdq1w",
        "drivers/bus/ti-sysc.c:sysc_disable_module",
        "drivers/bus/ti-sysc.c:sysc_enable_module",
        "drivers/bus/ti-sysc.c:sysc_read_sysstatus",
        "drivers/bus/ti-sysc.c:sysc_read_sysconfig"
      ],
      "caller_func": []
    },
    {
      "addr": 3229784552,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/bus/uniphier-system-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/uniphier-system-bus.c:uniphier_system_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3229793196,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/phy/marvell/phy-armada375-usb2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/marvell/phy-armada375-usb2.c:armada375_usb_phy_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3229793884,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/phy/marvell/phy-mvebu-sata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_off",
        "drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_off",
        "drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_on",
        "drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 3229796236,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/phy/samsung/phy-exynos-pcie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_off",
        "drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_off",
        "drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_off",
        "drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_off",
        "drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_off",
        "drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_off",
        "drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_off",
        "drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_on",
        "drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_on",
        "drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_on",
        "drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_on",
        "drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_on"
      ],
      "caller_func": []
    },
    {
      "addr": 3229797520,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/phy/samsung/phy-exynos5250-sata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init",
        "drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init",
        "drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init",
        "drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init",
        "drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init",
        "drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init",
        "drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init",
        "drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init",
        "drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init",
        "drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3229828008,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/pinctrl-amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction"
      ],
      "caller_func": []
    },
    {
      "addr": 3229852296,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/pinctrl-rockchip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_suspend",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set_config",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_get",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set",
        "drivers/pinctrl/pinctrl-rockchip.c:_rockchip_pmx_gpio_set_direction",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_get_direction"
      ],
      "caller_func": []
    },
    {
      "addr": 3229864584,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/pinctrl-rzn1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinconf_set",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinconf_get",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinconf_get",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_set_mux",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_set_mux"
      ],
      "caller_func": []
    },
    {
      "addr": 3229869028,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/pinctrl-single.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-single.c:pcs_readl"
      ],
      "caller_func": []
    },
    {
      "addr": 3229888840,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/tegra/pinctrl-tegra.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_probe",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_probe",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_resume",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_suspend",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinconf_group_dbg_show",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinconf_group_set",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinconf_group_set",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinconf_group_get",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_set_mux",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_set_mux"
      ],
      "caller_func": []
    },
    {
      "addr": 3229889712,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:sata_phy_power_off",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:sata_phy_power_off",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:sata_phy_power_off",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:sata_phy_power_off",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:sata_phy_power_on",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:sata_phy_power_on",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:sata_phy_power_on",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:sata_phy_power_on",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:sata_phy_power_on",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:pcie_phy_power_off",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:pcie_phy_power_on",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:pcie_phy_power_on",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:pcie_phy_power_on",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:pcie_phy_power_on",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_phy_exit",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_phy_exit",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_phy_exit",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_phy_init",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_phy_init",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_phy_init",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_pinconf_group_set",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_pinconf_group_get",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_pinmux_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3229899812,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/actions/pinctrl-owl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_ack",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_unmask",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_unmask",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask",
        "drivers/pinctrl/actions/pinctrl-owl.c:irq_set_type",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_input",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_input",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_set",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_get",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_free",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_free",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_request",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_set",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_get",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_set",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_get",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_set_mux"
      ],
      "caller_func": []
    },
    {
      "addr": 3229911372,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/freescale/pinctrl-imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_dbg_show",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_set",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_get",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3229916060,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/freescale/pinctrl-imx7ulp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/freescale/pinctrl-imx7ulp.c:imx7ulp_pmx_gpio_set_direction"
      ],
      "caller_func": []
    },
    {
      "addr": 3229916224,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/freescale/pinctrl-vf610.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/freescale/pinctrl-vf610.c:vf610_pmx_gpio_set_direction"
      ],
      "caller_func": []
    },
    {
      "addr": 3229919304,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/mvebu/pinctrl-mvebu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_mmio_mpp_ctrl_set",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_mmio_mpp_ctrl_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3229923684,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/mvebu/pinctrl-dove.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/mvebu/pinctrl-dove.c:dove_audio1_ctrl_set",
        "drivers/pinctrl/mvebu/pinctrl-dove.c:dove_audio1_ctrl_get",
        "drivers/pinctrl/mvebu/pinctrl-dove.c:dove_audio0_ctrl_set",
        "drivers/pinctrl/mvebu/pinctrl-dove.c:dove_audio0_ctrl_get",
        "drivers/pinctrl/mvebu/pinctrl-dove.c:dove_mpp4_ctrl_set",
        "drivers/pinctrl/mvebu/pinctrl-dove.c:dove_mpp4_ctrl_get",
        "drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pmu_mpp_ctrl_set",
        "drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pmu_mpp_ctrl_set",
        "drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pmu_mpp_ctrl_get",
        "drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pmu_mpp_ctrl_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3229925700,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/mvebu/pinctrl-armada-xp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/mvebu/pinctrl-armada-xp.c:armada_xp_pinctrl_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3229929112,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_handler",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_handler",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm_gpio_clr",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3229937212,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/qcom/pinctrl-msm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_ack",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_clear_unmask",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_clear_unmask",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_mask",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_dbg_show",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_dbg_show",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_set",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_get",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_get_direction",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_output",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_output",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_input",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_get",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_get",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_set_mux"
      ],
      "caller_func": []
    },
    {
      "addr": 3229942456,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/samsung/pinctrl-samsung.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_resume",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_resume",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_resume",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_suspend",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_suspend",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_gpio_set_direction",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_gpio_get",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_gpio_set_value",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinconf_rw",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinmux_set_mux"
      ],
      "caller_func": []
    },
    {
      "addr": 3229952880,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/samsung/pinctrl-exynos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_pinctrl_resume",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_pinctrl_resume",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_pinctrl_resume",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_pinctrl_suspend",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_pinctrl_suspend",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_pinctrl_suspend",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_demux_eint16_31",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_demux_eint16_31",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_gpio_irq",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_release_resources",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_request_resources",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_set_type",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_unmask",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 3229953392,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/samsung/pinctrl-exynos-arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/samsung/pinctrl-exynos-arm.c:s5pv210_retention_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 3229955376,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/sh-pfc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_save_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 3229964760,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/sh-pfc/pfc-r8a7778.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sh-pfc/pfc-r8a7778.c:r8a7778_pinmux_set_bias",
        "drivers/pinctrl/sh-pfc/pfc-r8a7778.c:r8a7778_pinmux_get_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 3229965020,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/sh-pfc/pfc-sh73a0.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sh-pfc/pfc-sh73a0.c:sh73a0_vccq_mc0_is_enabled",
        "drivers/pinctrl/sh-pfc/pfc-sh73a0.c:sh73a0_vccq_mc0_endisable"
      ],
      "caller_func": []
    },
    {
      "addr": 3229977484,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/mediatek/mtk-eint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_debounce",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_debounce",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3229990000,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_get_value",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_get_value",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_get_value",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value"
      ],
      "caller_func": []
    },
    {
      "addr": 3230039964,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_read32be",
        "drivers/gpio/gpio-mmio.c:bgpio_read32"
      ],
      "caller_func": []
    },
    {
      "addr": 3230042052,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/gpio/gpio-ftgpio010.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_unmask_irq",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_mask_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3230047736,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/gpio/gpio-mvebu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend",
        "drivers/gpio/gpio-mvebu.c:mvebu_pwm_get_state",
        "drivers/gpio/gpio-mvebu.c:mvebu_pwm_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 3230055764,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/gpio/gpio-mxc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend",
        "drivers/gpio/gpio-mxc.c:mx2_gpio_irq_handler",
        "drivers/gpio/gpio-mxc.c:mx2_gpio_irq_handler",
        "drivers/gpio/gpio-mxc.c:mx3_gpio_irq_handler",
        "drivers/gpio/gpio-mxc.c:mx3_gpio_irq_handler",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_irq_handler",
        "drivers/gpio/gpio-mxc.c:gpio_set_irq_type",
        "drivers/gpio/gpio-mxc.c:gpio_set_irq_type"
      ],
      "caller_func": []
    },
    {
      "addr": 3230062252,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/gpio/gpio-omap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-omap.c:omap_gpio_probe",
        "drivers/gpio/gpio-omap.c:omap_gpio_probe",
        "drivers/gpio/gpio-omap.c:omap_gpio_probe",
        "drivers/gpio/gpio-omap.c:omap_gpio_unidle",
        "drivers/gpio/gpio-omap.c:omap_gpio_unidle",
        "drivers/gpio/gpio-omap.c:omap_gpio_unidle",
        "drivers/gpio/gpio-omap.c:omap_gpio_unidle",
        "drivers/gpio/gpio-omap.c:omap_gpio_unidle",
        "drivers/gpio/gpio-omap.c:omap_gpio_unidle",
        "drivers/gpio/gpio-omap.c:omap_gpio_unidle",
        "drivers/gpio/gpio-omap.c:omap_gpio_unidle",
        "drivers/gpio/gpio-omap.c:omap_gpio_unidle",
        "drivers/gpio/gpio-omap.c:omap_gpio_unidle",
        "drivers/gpio/gpio-omap.c:omap_gpio_unidle",
        "drivers/gpio/gpio-omap.c:omap_gpio_unidle",
        "drivers/gpio/gpio-omap.c:omap_gpio_unidle",
        "drivers/gpio/gpio-omap.c:omap_gpio_set_multiple",
        "drivers/gpio/gpio-omap.c:omap_gpio_set_config",
        "drivers/gpio/gpio-omap.c:omap_gpio_get_multiple",
        "drivers/gpio/gpio-omap.c:omap_gpio_get_multiple",
        "drivers/gpio/gpio-omap.c:omap_gpio_get_multiple",
        "drivers/gpio/gpio-omap.c:omap_gpio_output",
        "drivers/gpio/gpio-omap.c:omap_gpio_get",
        "drivers/gpio/gpio-omap.c:omap_gpio_get",
        "drivers/gpio/gpio-omap.c:omap_gpio_input",
        "drivers/gpio/gpio-omap.c:omap_gpio_get_direction",
        "drivers/gpio/gpio-omap.c:omap_gpio_free",
        "drivers/gpio/gpio-omap.c:omap_gpio_free",
        "drivers/gpio/gpio-omap.c:omap_gpio_unmask_irq",
        "drivers/gpio/gpio-omap.c:omap_gpio_unmask_irq",
        "drivers/gpio/gpio-omap.c:omap_gpio_unmask_irq",
        "drivers/gpio/gpio-omap.c:omap_gpio_mask_irq",
        "drivers/gpio/gpio-omap.c:omap_gpio_mask_irq",
        "drivers/gpio/gpio-omap.c:omap_gpio_irq_shutdown",
        "drivers/gpio/gpio-omap.c:omap_gpio_irq_shutdown",
        "drivers/gpio/gpio-omap.c:omap_gpio_irq_shutdown",
        "drivers/gpio/gpio-omap.c:omap_gpio_irq_shutdown",
        "drivers/gpio/gpio-omap.c:omap_gpio_irq_startup",
        "drivers/gpio/gpio-omap.c:omap_gpio_irq_handler",
        "drivers/gpio/gpio-omap.c:omap_gpio_irq_handler",
        "drivers/gpio/gpio-omap.c:omap_gpio_irq_handler",
        "drivers/gpio/gpio-omap.c:omap_gpio_irq_type",
        "drivers/gpio/gpio-omap.c:omap_gpio_irq_type",
        "drivers/gpio/gpio-omap.c:omap_enable_gpio_module",
        "drivers/gpio/gpio-omap.c:omap_enable_gpio_module",
        "drivers/gpio/gpio-omap.c:omap_set_gpio_triggering",
        "drivers/gpio/gpio-omap.c:omap_set_gpio_triggering",
        "drivers/gpio/gpio-omap.c:omap_set_gpio_triggering",
        "drivers/gpio/gpio-omap.c:omap_set_gpio_triggering",
        "drivers/gpio/gpio-omap.c:omap_set_gpio_triggering",
        "drivers/gpio/gpio-omap.c:omap_set_gpio_triggering",
        "drivers/gpio/gpio-omap.c:omap_set_gpio_triggering",
        "drivers/gpio/gpio-omap.c:omap_set_gpio_triggering",
        "drivers/gpio/gpio-omap.c:omap_set_gpio_triggering",
        "drivers/gpio/gpio-omap.c:omap_set_gpio_triggering",
        "drivers/gpio/gpio-omap.c:omap_set_gpio_dataout_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 3230079892,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/gpio/gpio-tegra.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-tegra.c:tegra_dbg_gpio_show",
        "drivers/gpio/gpio-tegra.c:tegra_dbg_gpio_show",
        "drivers/gpio/gpio-tegra.c:tegra_dbg_gpio_show",
        "drivers/gpio/gpio-tegra.c:tegra_dbg_gpio_show",
        "drivers/gpio/gpio-tegra.c:tegra_dbg_gpio_show",
        "drivers/gpio/gpio-tegra.c:tegra_dbg_gpio_show",
        "drivers/gpio/gpio-tegra.c:tegra_dbg_gpio_show",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_suspend",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_suspend",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_suspend",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_suspend",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_suspend",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_suspend",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_irq_handler",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_irq_handler",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_irq_handler",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_irq_set_type",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_get_direction",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_get_direction",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_get",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3230086592,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/gpio/gpio-vf610.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-vf610.c:vf610_gpio_irq_handler",
        "drivers/gpio/gpio-vf610.c:vf610_gpio_direction_input",
        "drivers/gpio/gpio-vf610.c:vf610_gpio_get",
        "drivers/gpio/gpio-vf610.c:vf610_gpio_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3230088444,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/gpio/gpio-xilinx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-xilinx.c:xgpio_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3230090212,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/gpio/gpio-zevio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-zevio.c:zevio_gpio_direction_output",
        "drivers/gpio/gpio-zevio.c:zevio_gpio_direction_output",
        "drivers/gpio/gpio-zevio.c:zevio_gpio_direction_input",
        "drivers/gpio/gpio-zevio.c:zevio_gpio_set",
        "drivers/gpio/gpio-zevio.c:zevio_gpio_get",
        "drivers/gpio/gpio-zevio.c:zevio_gpio_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3230102648,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32",
        "drivers/pci/access.c:pci_generic_config_read32",
        "drivers/pci/access.c:pci_generic_config_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3230178964,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io"
      ],
      "caller_func": []
    },
    {
      "addr": 3230180448,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/rom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 3230224832,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume_early"
      ],
      "caller_func": []
    },
    {
      "addr": 3230269340,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/msi.c:msi_set_mask_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 3230295960,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/controller/pcie-cadence-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 3230300312,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/controller/pcie-cadence-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 3230302816,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/controller/pci-ftpci100.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_unmask_irq",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_mask_irq",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_ack_irq",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_read_config"
      ],
      "caller_func": []
    },
    {
      "addr": 3230309596,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/controller/pci-mvebu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pcie_suspend",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pcie_rd_conf",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pcie_rd_conf",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pcie_wr_conf",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pci_bridge_emul_base_conf_write",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pci_bridge_emul_pcie_conf_read",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pci_bridge_emul_pcie_conf_read",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pci_bridge_emul_pcie_conf_read",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pci_bridge_emul_pcie_conf_read",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pci_bridge_emul_pcie_conf_read",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pcie_setup_hw",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pcie_setup_hw"
      ],
      "caller_func": []
    },
    {
      "addr": 3230321272,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/controller/pci-tegra.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_ports_seq_show",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_ports_seq_show",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_msi_irq",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_msi_irq",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_isr",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_isr",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_isr",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_disable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_disable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_disable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_reset",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3230325364,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/controller/pci-rcar-gen2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup",
        "drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 3230327028,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/controller/pcie-rcar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_resume_noirq",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_resume_noirq",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs",
        "drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs",
        "drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irq",
        "drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irq",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_msi_irq",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_msi_irq",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_wait_for_dl",
        "drivers/pci/controller/pcie-rcar.c:phy_wait_for_ack",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access"
      ],
      "caller_func": []
    },
    {
      "addr": 3230335672,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/controller/pcie-xilinx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_map_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 3230338772,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/controller/pci-v3-semi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe",
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230343536,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/controller/pcie-altera.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-altera.c:altera_pcie_isr",
        "drivers/pci/controller/pcie-altera.c:s10_rp_read_cfg",
        "drivers/pci/controller/pcie-altera.c:s10_tlp_read_packet",
        "drivers/pci/controller/pcie-altera.c:s10_tlp_read_packet",
        "drivers/pci/controller/pcie-altera.c:s10_tlp_read_packet",
        "drivers/pci/controller/pcie-altera.c:s10_tlp_read_packet",
        "drivers/pci/controller/pcie-altera.c:tlp_read_packet",
        "drivers/pci/controller/pcie-altera.c:tlp_read_packet",
        "drivers/pci/controller/pcie-altera.c:tlp_read_packet",
        "drivers/pci/controller/pcie-altera.c:altera_pcie_link_up"
      ],
      "caller_func": []
    },
    {
      "addr": 3230346776,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/controller/pcie-altera-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_free",
        "drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_alloc",
        "drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr",
        "drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr"
      ],
      "caller_func": []
    },
    {
      "addr": 3230348872,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/controller/pcie-rockchip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses"
      ],
      "caller_func": []
    },
    {
      "addr": 3230353324,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/controller/pcie-rockchip-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_raise_irq",
        "drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_raise_irq",
        "drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_get_msi",
        "drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_msi",
        "drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_clear_bar",
        "drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 3230356768,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/controller/pcie-mediatek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_write",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_read",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_read",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_check_cfg_cpld",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_check_cfg_cpld",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_check_cfg_cpld"
      ],
      "caller_func": []
    },
    {
      "addr": 3230361104,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230372372,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3243582352,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/controller/dwc/pci-dra7xx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_irq_handler",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_msi_irq_handler",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_establish_link",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_stop_link",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_link_up"
      ],
      "caller_func": []
    },
    {
      "addr": 3230391644,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/controller/dwc/pcie-qcom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_2_3_2_ltssm_enable",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_2_1_0_ltssm_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3230393848,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/controller/dwc/pcie-histb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_link_up",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_link_up",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_wr_own_conf",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_wr_own_conf",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_write_dbi",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_write_dbi",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_dbi_r_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 3230397104,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/pci/controller/dwc/pcie-uniphier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_irq_handler",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_irq_handler",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_irq_unmask",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_irq_mask",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_irq_ack",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_stop_link",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_establish_link",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_link_up"
      ],
      "caller_func": []
    },
    {
      "addr": 3230508304,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/video/fbdev/core/cfbfillrect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230510024,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/video/fbdev/core/cfbcopyarea.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230515032,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/video/fbdev/core/cfbimgblt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit",
        "drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit",
        "drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit",
        "drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit"
      ],
      "caller_func": []
    },
    {
      "addr": 3230521884,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/video/fbdev/imsttfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/imsttfb.c:imsttfb_ioctl",
        "drivers/video/fbdev/imsttfb.c:imsttfb_copyarea",
        "drivers/video/fbdev/imsttfb.c:imsttfb_copyarea",
        "drivers/video/fbdev/imsttfb.c:imsttfb_copyarea",
        "drivers/video/fbdev/imsttfb.c:imsttfb_fillrect",
        "drivers/video/fbdev/imsttfb.c:imsttfb_fillrect",
        "drivers/video/fbdev/imsttfb.c:imsttfb_fillrect",
        "drivers/video/fbdev/imsttfb.c:imsttfb_fillrect",
        "drivers/video/fbdev/imsttfb.c:imsttfb_fillrect",
        "drivers/video/fbdev/imsttfb.c:imsttfb_fillrect",
        "drivers/video/fbdev/imsttfb.c:imsttfb_blank"
      ],
      "caller_func": []
    },
    {
      "addr": 3230524560,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/video/fbdev/amba-clcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/amba-clcd.c:clcdfb_setcolreg",
        "drivers/video/fbdev/amba-clcd.c:clcdfb_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 3230544760,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/video/fbdev/mx3fb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:__set_par",
        "drivers/video/fbdev/mx3fb.c:__set_par",
        "drivers/video/fbdev/mx3fb.c:__set_par",
        "drivers/video/fbdev/mx3fb.c:__set_par",
        "drivers/video/fbdev/mx3fb.c:__set_par",
        "drivers/video/fbdev/mx3fb.c:sdc_disable_channel",
        "drivers/video/fbdev/mx3fb.c:sdc_enable_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 3230554356,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/amba/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/amba/bus.c:amba_device_try_add",
        "drivers/amba/bus.c:amba_device_try_add",
        "drivers/amba/bus.c:amba_device_try_add",
        "drivers/amba/bus.c:amba_device_try_add"
      ],
      "caller_func": []
    },
    {
      "addr": 3230556412,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/amba/tegra-ahb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/amba/tegra-ahb.c:tegra_ahb_probe",
        "drivers/amba/tegra-ahb.c:tegra_ahb_probe",
        "drivers/amba/tegra-ahb.c:tegra_ahb_probe",
        "drivers/amba/tegra-ahb.c:tegra_ahb_probe",
        "drivers/amba/tegra-ahb.c:tegra_ahb_probe",
        "drivers/amba/tegra-ahb.c:tegra_ahb_probe",
        "drivers/amba/tegra-ahb.c:tegra_ahb_probe",
        "drivers/amba/tegra-ahb.c:tegra_ahb_probe",
        "drivers/amba/tegra-ahb.c:tegra_ahb_probe",
        "drivers/amba/tegra-ahb.c:tegra_ahb_suspend",
        "drivers/amba/tegra-ahb.c:tegra_ahb_enable_smmu"
      ],
      "caller_func": []
    },
    {
      "addr": 3230595484,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_set_rate",
        "drivers/clk/clk-divider.c:clk_divider_set_rate",
        "drivers/clk/clk-divider.c:clk_divider_round_rate",
        "drivers/clk/clk-divider.c:clk_divider_round_rate",
        "drivers/clk/clk-divider.c:clk_divider_recalc_rate",
        "drivers/clk/clk-divider.c:clk_divider_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3230600776,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/clk-gate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-gate.c:clk_gate_is_enabled",
        "drivers/clk/clk-gate.c:clk_gate_is_enabled",
        "drivers/clk/clk-gate.c:clk_gate_endisable",
        "drivers/clk/clk-gate.c:clk_gate_endisable"
      ],
      "caller_func": []
    },
    {
      "addr": 3230601328,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/clk-multiplier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-multiplier.c:clk_multiplier_set_rate",
        "drivers/clk/clk-multiplier.c:clk_multiplier_set_rate",
        "drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate",
        "drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3230602776,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/clk-mux.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-mux.c:clk_mux_set_parent",
        "drivers/clk/clk-mux.c:clk_mux_set_parent",
        "drivers/clk/clk-mux.c:clk_mux_get_parent",
        "drivers/clk/clk-mux.c:clk_mux_get_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 3230605668,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/clk-fractional-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-fractional-divider.c:clk_fd_set_rate",
        "drivers/clk/clk-fractional-divider.c:clk_fd_set_rate",
        "drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate",
        "drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3230608904,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/clk-fixed-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 3230614876,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/clk-highbank.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-highbank.c:clk_periclk_recalc_rate",
        "drivers/clk/clk-highbank.c:clk_cpu_a9bclk_recalc_rate",
        "drivers/clk/clk-highbank.c:clk_cpu_periphclk_recalc_rate",
        "drivers/clk/clk-highbank.c:clk_pll_set_rate",
        "drivers/clk/clk-highbank.c:clk_pll_set_rate",
        "drivers/clk/clk-highbank.c:clk_pll_set_rate",
        "drivers/clk/clk-highbank.c:clk_pll_recalc_rate",
        "drivers/clk/clk-highbank.c:clk_pll_disable",
        "drivers/clk/clk-highbank.c:clk_pll_enable",
        "drivers/clk/clk-highbank.c:clk_pll_unprepare",
        "drivers/clk/clk-highbank.c:clk_pll_prepare",
        "drivers/clk/clk-highbank.c:clk_pll_prepare",
        "drivers/clk/clk-highbank.c:clk_pll_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 3230617036,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/clk-hsdk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3230617212,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/clk-milbeaut.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-milbeaut.c:m10v_clk_divider_set_rate",
        "drivers/clk/clk-milbeaut.c:m10v_clk_divider_set_rate",
        "drivers/clk/clk-milbeaut.c:m10v_clk_divider_set_rate",
        "drivers/clk/clk-milbeaut.c:m10v_clk_divider_recalc_rate",
        "drivers/clk/clk-milbeaut.c:m10v_mux_set_parent",
        "drivers/clk/clk-milbeaut.c:m10v_mux_get_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 3230619068,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/clk-npcm7xx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-npcm7xx.c:npcm7xx_clk_pll_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3243597852,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/clk-qoriq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-qoriq.c:clockgen_init",
        "drivers/clk/clk-qoriq.c:clockgen_init",
        "drivers/clk/clk-qoriq.c:clockgen_init",
        "drivers/clk/clk-qoriq.c:clockgen_init",
        "drivers/clk/clk-qoriq.c:p5040_init_periph",
        "drivers/clk/clk-qoriq.c:p5020_init_periph",
        "drivers/clk/clk-qoriq.c:p4080_init_periph",
        "drivers/clk/clk-qoriq.c:p2041_init_periph"
      ],
      "caller_func": []
    },
    {
      "addr": 3230625264,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/berlin/berlin2-avpll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_disable",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_enable",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_is_enabled",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_vco_recalc_rate",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_vco_disable",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_vco_enable",
        "drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_vco_is_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 3230625816,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/berlin/berlin2-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/berlin/berlin2-pll.c:berlin2_pll_recalc_rate",
        "drivers/clk/berlin/berlin2-pll.c:berlin2_pll_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3230626780,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/berlin/berlin2-div.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_recalc_rate",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_recalc_rate",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_recalc_rate",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_get_parent",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_get_parent",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_set_parent",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_set_parent",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_disable",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_enable",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_is_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 3230629104,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/hisilicon/clkgate-separated.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_is_enabled",
        "drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_disable",
        "drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3230629504,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/hisilicon/clkdivider-hi6220.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/hisilicon/clkdivider-hi6220.c:hi6220_clkdiv_set_rate",
        "drivers/clk/hisilicon/clkdivider-hi6220.c:hi6220_clkdiv_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3230630404,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/hisilicon/clk-hisi-phase.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/hisilicon/clk-hisi-phase.c:hisi_clk_set_phase",
        "drivers/clk/hisilicon/clk-hisi-phase.c:hisi_clk_get_phase"
      ],
      "caller_func": []
    },
    {
      "addr": 3230631248,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/hisilicon/clk-hi3620.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/hisilicon/clk-hi3620.c:mmc_clk_set_timing",
        "drivers/clk/hisilicon/clk-hi3620.c:mmc_clk_set_timing",
        "drivers/clk/hisilicon/clk-hi3620.c:mmc_clk_set_timing",
        "drivers/clk/hisilicon/clk-hi3620.c:mmc_clk_set_timing",
        "drivers/clk/hisilicon/clk-hi3620.c:mmc_clk_set_timing"
      ],
      "caller_func": []
    },
    {
      "addr": 3230632092,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/hisilicon/clk-hix5hd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/hisilicon/clk-hix5hd2.c:clk_complex_disable",
        "drivers/clk/hisilicon/clk-hix5hd2.c:clk_complex_disable",
        "drivers/clk/hisilicon/clk-hix5hd2.c:clk_complex_enable",
        "drivers/clk/hisilicon/clk-hix5hd2.c:clk_complex_enable",
        "drivers/clk/hisilicon/clk-hix5hd2.c:clk_ether_unprepare",
        "drivers/clk/hisilicon/clk-hix5hd2.c:clk_ether_prepare",
        "drivers/clk/hisilicon/clk-hix5hd2.c:clk_ether_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 3230633672,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/hisilicon/reset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/hisilicon/reset.c:hisi_reset_deassert",
        "drivers/clk/hisilicon/reset.c:hisi_reset_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 3230635240,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/hisilicon/clk-hi3660-stub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/hisilicon/clk-hi3660-stub.c:hi3660_stub_clk_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3243605700,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/imx/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk.c:imx_mmdc_mask_handshake"
      ],
      "caller_func": []
    },
    {
      "addr": 3230636372,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/imx/clk-busy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230637488,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/imx/clk-composite-8m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-composite-8m.c:imx8m_clk_composite_divider_set_rate",
        "drivers/clk/imx/clk-composite-8m.c:imx8m_clk_composite_divider_recalc_rate",
        "drivers/clk/imx/clk-composite-8m.c:imx8m_clk_composite_divider_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3230640004,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/imx/clk-divider-gate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-divider-gate.c:imx_clk_divider_gate",
        "drivers/clk/imx/clk-divider-gate.c:clk_divider_is_enabled",
        "drivers/clk/imx/clk-divider-gate.c:clk_divider_disable",
        "drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_set_rate",
        "drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_recalc_rate",
        "drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_recalc_rate_ro"
      ],
      "caller_func": []
    },
    {
      "addr": 3230640288,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/imx/clk-fixup-div.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-fixup-div.c:clk_fixup_div_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3230640816,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/imx/clk-fixup-mux.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-fixup-mux.c:clk_fixup_mux_set_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 3230641672,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/imx/clk-frac-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_recalc_rate",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_recalc_rate",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_is_prepared",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_unprepare",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_prepare",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_prepare",
        "drivers/clk/imx/clk-frac-pll.c:clk_pll_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 3230642264,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/imx/clk-gate-exclusive.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-gate-exclusive.c:clk_gate_exclusive_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3230642788,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/imx/clk-gate2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-gate2.c:clk_gate2_disable_unused",
        "drivers/clk/imx/clk-gate2.c:clk_gate2_is_enabled",
        "drivers/clk/imx/clk-gate2.c:clk_gate2_disable",
        "drivers/clk/imx/clk-gate2.c:clk_gate2_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3230643552,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/imx/clk-pfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-pfd.c:clk_pfd_is_enabled",
        "drivers/clk/imx/clk-pfd.c:clk_pfd_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3230644836,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/imx/clk-pfdv2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_set_rate",
        "drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_is_enabled",
        "drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_recalc_rate",
        "drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_disable",
        "drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable",
        "drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable",
        "drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3230645396,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/imx/clk-pllv1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-pllv1.c:clk_pllv1_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3230645852,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/imx/clk-pllv2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-pllv2.c:clk_pllv2_unprepare",
        "drivers/clk/imx/clk-pllv2.c:clk_pllv2_prepare",
        "drivers/clk/imx/clk-pllv2.c:clk_pllv2_prepare",
        "drivers/clk/imx/clk-pllv2.c:clk_pllv2_set_rate",
        "drivers/clk/imx/clk-pllv2.c:clk_pllv2_recalc_rate",
        "drivers/clk/imx/clk-pllv2.c:clk_pllv2_recalc_rate",
        "drivers/clk/imx/clk-pllv2.c:clk_pllv2_recalc_rate",
        "drivers/clk/imx/clk-pllv2.c:clk_pllv2_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3230648032,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/imx/clk-pllv3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_set_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_recalc_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_recalc_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_recalc_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_set_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_recalc_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_recalc_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_recalc_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_sys_set_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_sys_recalc_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_set_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_recalc_rate",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_is_prepared",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_unprepare",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_prepare",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_wait_lock",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_wait_lock",
        "drivers/clk/imx/clk-pllv3.c:clk_pllv3_wait_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 3230649640,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/imx/clk-pllv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-pllv4.c:clk_pllv4_disable",
        "drivers/clk/imx/clk-pllv4.c:clk_pllv4_enable",
        "drivers/clk/imx/clk-pllv4.c:clk_pllv4_enable",
        "drivers/clk/imx/clk-pllv4.c:clk_pllv4_enable",
        "drivers/clk/imx/clk-pllv4.c:clk_pllv4_set_rate",
        "drivers/clk/imx/clk-pllv4.c:clk_pllv4_recalc_rate",
        "drivers/clk/imx/clk-pllv4.c:clk_pllv4_recalc_rate",
        "drivers/clk/imx/clk-pllv4.c:clk_pllv4_recalc_rate",
        "drivers/clk/imx/clk-pllv4.c:clk_pllv4_is_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 3230651232,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/imx/clk-sccg-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_set_parent",
        "drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_set_parent",
        "drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_get_parent",
        "drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_set_rate",
        "drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_set_rate",
        "drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_set_rate",
        "drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_recalc_rate",
        "drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_recalc_rate",
        "drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_unprepare",
        "drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_prepare",
        "drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_prepare",
        "drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_is_prepared"
      ],
      "caller_func": []
    },
    {
      "addr": 3230655340,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/imx/clk-pll14xx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-pll14xx.c:imx_clk_pll14xx",
        "drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_unprepare",
        "drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_is_prepared",
        "drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_prepare",
        "drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate",
        "drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate",
        "drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate",
        "drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate",
        "drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_wait_lock",
        "drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_wait_lock",
        "drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_recalc_rate",
        "drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_recalc_rate",
        "drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3243621060,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/imx/clk-imx5.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-imx5.c:mx51_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx51_clocks_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243629900,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/imx/clk-imx6q.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init",
        "drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3230656264,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/imx/clk-imx6sl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-imx6sl.c:imx6sl_set_wait_clk",
        "drivers/clk/imx/clk-imx6sl.c:imx6sl_set_wait_clk",
        "drivers/clk/imx/clk-imx6sl.c:imx6sl_set_wait_clk",
        "drivers/clk/imx/clk-imx6sl.c:imx6sl_set_wait_clk",
        "drivers/clk/imx/clk-imx6sl.c:imx6sl_set_wait_clk",
        "drivers/clk/imx/clk-imx6sl.c:imx6sl_set_wait_clk"
      ],
      "caller_func": []
    },
    {
      "addr": 3230656576,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/imx/clk-vf610.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-vf610.c:vf610_clk_suspend",
        "drivers/clk/imx/clk-vf610.c:vf610_clk_suspend",
        "drivers/clk/imx/clk-vf610.c:vf610_clk_suspend",
        "drivers/clk/imx/clk-vf610.c:vf610_clk_suspend",
        "drivers/clk/imx/clk-vf610.c:vf610_clk_suspend",
        "drivers/clk/imx/clk-vf610.c:vf610_clk_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3230659500,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/mediatek/clk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_unprepare",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_unprepare",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_unprepare",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_unprepare",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_prepare",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_prepare",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_prepare",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_prepare",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_recalc_rate",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_recalc_rate",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate",
        "drivers/clk/mediatek/clk-pll.c:mtk_pll_is_prepared"
      ],
      "caller_func": []
    },
    {
      "addr": 3230662440,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/mediatek/clk-apmixed.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mediatek/clk-apmixed.c:mtk_ref2usb_tx_unprepare",
        "drivers/clk/mediatek/clk-apmixed.c:mtk_ref2usb_tx_prepare",
        "drivers/clk/mediatek/clk-apmixed.c:mtk_ref2usb_tx_is_prepared"
      ],
      "caller_func": []
    },
    {
      "addr": 3230675864,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/mvebu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mvebu/common.c:mvebu_clk_gating_suspend",
        "drivers/clk/mvebu/common.c:kirkwood_fix_sscg_deviation"
      ],
      "caller_func": []
    },
    {
      "addr": 3230676608,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/mvebu/clk-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mvebu/clk-cpu.c:clk_cpu_set_rate",
        "drivers/clk/mvebu/clk-cpu.c:clk_cpu_set_rate",
        "drivers/clk/mvebu/clk-cpu.c:clk_cpu_set_rate",
        "drivers/clk/mvebu/clk-cpu.c:clk_cpu_set_rate",
        "drivers/clk/mvebu/clk-cpu.c:clk_cpu_set_rate",
        "drivers/clk/mvebu/clk-cpu.c:clk_cpu_set_rate",
        "drivers/clk/mvebu/clk-cpu.c:clk_cpu_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3230677264,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/mvebu/clk-corediv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mvebu/clk-corediv.c:clk_corediv_set_rate",
        "drivers/clk/mvebu/clk-corediv.c:clk_corediv_set_rate",
        "drivers/clk/mvebu/clk-corediv.c:clk_corediv_set_rate",
        "drivers/clk/mvebu/clk-corediv.c:clk_corediv_recalc_rate",
        "drivers/clk/mvebu/clk-corediv.c:clk_corediv_disable",
        "drivers/clk/mvebu/clk-corediv.c:clk_corediv_enable",
        "drivers/clk/mvebu/clk-corediv.c:clk_corediv_is_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 3230677760,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/mvebu/armada-370.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mvebu/armada-370.c:a370_is_sscg_enabled",
        "drivers/clk/mvebu/armada-370.c:a370_get_clk_ratio",
        "drivers/clk/mvebu/armada-370.c:a370_get_cpu_freq",
        "drivers/clk/mvebu/armada-370.c:a370_get_tclk_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 3243759860,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/mvebu/armada-375.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mvebu/armada-375.c:armada_375_get_clk_ratio",
        "drivers/clk/mvebu/armada-375.c:armada_375_get_cpu_freq",
        "drivers/clk/mvebu/armada-375.c:armada_375_get_tclk_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 3243760172,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/mvebu/armada-38x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mvebu/armada-38x.c:armada_38x_get_clk_ratio",
        "drivers/clk/mvebu/armada-38x.c:armada_38x_get_cpu_freq",
        "drivers/clk/mvebu/armada-38x.c:armada_38x_get_tclk_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 3243760552,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/mvebu/armada-39x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mvebu/armada-39x.c:armada_39x_refclk_ratio",
        "drivers/clk/mvebu/armada-39x.c:armada_39x_get_cpu_freq",
        "drivers/clk/mvebu/armada-39x.c:armada_39x_get_tclk_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 3243760792,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/mvebu/armada-xp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mvebu/armada-xp.c:axp_get_clk_ratio",
        "drivers/clk/mvebu/armada-xp.c:axp_get_clk_ratio",
        "drivers/clk/mvebu/armada-xp.c:axp_get_cpu_freq",
        "drivers/clk/mvebu/armada-xp.c:axp_get_cpu_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 3243761296,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/mvebu/mv98dx3236.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mvebu/mv98dx3236.c:mv98dx3236_get_clk_ratio",
        "drivers/clk/mvebu/mv98dx3236.c:mv98dx3236_get_cpu_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 3243761852,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/mvebu/dove.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mvebu/dove.c:dove_get_clk_ratio",
        "drivers/clk/mvebu/dove.c:dove_get_clk_ratio",
        "drivers/clk/mvebu/dove.c:dove_get_cpu_freq",
        "drivers/clk/mvebu/dove.c:dove_get_tclk_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 3230678428,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/mvebu/dove-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mvebu/dove-divider.c:dove_set_clock",
        "drivers/clk/mvebu/dove-divider.c:dove_set_clock",
        "drivers/clk/mvebu/dove-divider.c:dove_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3243763980,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/renesas/clk-rz.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/clk-rz.c:rz_cpg_clocks_init",
        "drivers/clk/renesas/clk-rz.c:rz_cpg_clocks_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243764432,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/renesas/r7s9210-cpg-mssr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/r7s9210-cpg-mssr.c:rza2_cpg_clk_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3243765452,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/renesas/clk-r8a7740.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/clk-r8a7740.c:r8a7740_cpg_clocks_init",
        "drivers/clk/renesas/clk-r8a7740.c:r8a7740_cpg_clocks_init",
        "drivers/clk/renesas/clk-r8a7740.c:r8a7740_cpg_clocks_init",
        "drivers/clk/renesas/clk-r8a7740.c:r8a7740_cpg_clocks_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3230678916,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/renesas/r9a06g032-clocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_dualgate_is_enabled",
        "drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_dualgate_is_enabled",
        "drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_dualgate_setenable",
        "drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_mux_get_parent",
        "drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_div_recalc_rate",
        "drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_is_enabled",
        "drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_is_enabled",
        "drivers/clk/renesas/r9a06g032-clocks.c:clk_rdesc_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3243770740,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/renesas/clk-sh73a0.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/clk-sh73a0.c:sh73a0_cpg_clocks_init",
        "drivers/clk/renesas/clk-sh73a0.c:sh73a0_cpg_clocks_init",
        "drivers/clk/renesas/clk-sh73a0.c:sh73a0_cpg_clocks_init",
        "drivers/clk/renesas/clk-sh73a0.c:sh73a0_cpg_clocks_init",
        "drivers/clk/renesas/clk-sh73a0.c:sh73a0_cpg_clocks_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243772904,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/renesas/clk-rcar-gen2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/clk-rcar-gen2.c:rcar_gen2_cpg_clocks_init",
        "drivers/clk/renesas/clk-rcar-gen2.c:rcar_gen2_cpg_register_clock",
        "drivers/clk/renesas/clk-rcar-gen2.c:cpg_z_clk_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3243773536,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/renesas/rcar-gen2-cpg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/rcar-gen2-cpg.c:rcar_gen2_cpg_clk_register",
        "drivers/clk/renesas/rcar-gen2-cpg.c:cpg_z_clk_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3230685360,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/renesas/renesas-cpg-mssr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_resume_noirq",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_resume_noirq",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_suspend_noirq",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_status",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_register_core_clk",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_is_enabled",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_endisable",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_endisable"
      ],
      "caller_func": []
    },
    {
      "addr": 3230685608,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/renesas/clk-mstp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/clk-mstp.c:cpg_mstp_clock_is_enabled",
        "drivers/clk/renesas/clk-mstp.c:cpg_mstp_clock_is_enabled",
        "drivers/clk/renesas/clk-mstp.c:cpg_mstp_clock_endisable",
        "drivers/clk/renesas/clk-mstp.c:cpg_mstp_clock_endisable",
        "drivers/clk/renesas/clk-mstp.c:cpg_mstp_clock_endisable"
      ],
      "caller_func": []
    },
    {
      "addr": 3243778192,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/renesas/clk-div6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/clk-div6.c:cpg_div6_register",
        "drivers/clk/renesas/clk-div6.c:cpg_div6_clock_set_parent",
        "drivers/clk/renesas/clk-div6.c:cpg_div6_clock_set_rate",
        "drivers/clk/renesas/clk-div6.c:cpg_div6_clock_is_enabled",
        "drivers/clk/renesas/clk-div6.c:cpg_div6_clock_disable",
        "drivers/clk/renesas/clk-div6.c:cpg_div6_clock_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3230688504,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/rockchip/clk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_is_enabled",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_enable",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_set_params",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_set_params",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_get_params",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_get_params",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_get_params",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_get_params",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_is_enabled",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_recalc_rate",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_get_params",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_get_params",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_get_params",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_is_enabled",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_set_params",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_get_params",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_get_params",
        "drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_get_params"
      ],
      "caller_func": []
    },
    {
      "addr": 3230694872,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/rockchip/clk-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3230697328,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/rockchip/clk-half-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk-half-divider.c:clk_half_divider_set_rate",
        "drivers/clk/rockchip/clk-half-divider.c:clk_half_divider_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3230698348,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/rockchip/clk-inverter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk-inverter.c:rockchip_inv_set_phase",
        "drivers/clk/rockchip/clk-inverter.c:rockchip_inv_get_phase"
      ],
      "caller_func": []
    },
    {
      "addr": 3230698820,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/rockchip/clk-mmc-phase.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk-mmc-phase.c:rockchip_mmc_get_phase"
      ],
      "caller_func": []
    },
    {
      "addr": 3230700280,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/rockchip/clk-ddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk-ddr.c:rockchip_ddrclk_get_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 3230701204,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/rockchip/softrst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/softrst.c:rockchip_softrst_deassert",
        "drivers/clk/rockchip/softrst.c:rockchip_softrst_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 3230701480,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/rockchip/clk-rk3288.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3230701860,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/samsung/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/samsung/clk.c:samsung_clk_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3230702984,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/samsung/clk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/samsung/clk-pll.c:samsung_pll2650xx_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll2650xx_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll2650xx_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll2650xx_recalc_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll2650xx_recalc_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll2650x_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll2650x_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll2650x_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll2650x_recalc_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll2650x_recalc_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll2550xx_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll2550xx_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll2550xx_recalc_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll2550x_recalc_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_s3c2410_upll_disable",
        "drivers/clk/samsung/clk-pll.c:samsung_s3c2410_upll_enable",
        "drivers/clk/samsung/clk-pll.c:samsung_s3c2410_mpll_disable",
        "drivers/clk/samsung/clk-pll.c:samsung_s3c2410_mpll_enable",
        "drivers/clk/samsung/clk-pll.c:samsung_s3c2440_mpll_recalc_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_s3c2410_pll_recalc_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll6553_recalc_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll6553_recalc_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll6552_recalc_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll46xx_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll46xx_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll46xx_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll46xx_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll46xx_recalc_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll46xx_recalc_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll45xx_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll45xx_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll45xx_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll45xx_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll45xx_recalc_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll36xx_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll36xx_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll36xx_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll36xx_recalc_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll36xx_recalc_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll35xx_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll35xx_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll35xx_recalc_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll3000_recalc_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll2126_recalc_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll3xxx_disable",
        "drivers/clk/samsung/clk-pll.c:samsung_pll3xxx_enable",
        "drivers/clk/samsung/clk-pll.c:samsung_pll3xxx_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3230709084,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/samsung/clk-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/samsung/clk-cpu.c:exynos5433_cpuclk_notifier_cb",
        "drivers/clk/samsung/clk-cpu.c:exynos5433_cpuclk_notifier_cb",
        "drivers/clk/samsung/clk-cpu.c:exynos_cpuclk_notifier_cb",
        "drivers/clk/samsung/clk-cpu.c:exynos_cpuclk_notifier_cb",
        "drivers/clk/samsung/clk-cpu.c:exynos_cpuclk_notifier_cb",
        "drivers/clk/samsung/clk-cpu.c:exynos_cpuclk_notifier_cb",
        "drivers/clk/samsung/clk-cpu.c:exynos_set_safe_div"
      ],
      "caller_func": []
    },
    {
      "addr": 3230709640,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/samsung/clk-exynos5-subcmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_subcmu_resume",
        "drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_subcmu_clk_save"
      ],
      "caller_func": []
    },
    {
      "addr": 3230709904,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/samsung/clk-exynos-clkout.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/samsung/clk-exynos-clkout.c:exynos_clkout_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3230712420,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/tegra/clk-dfll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/tegra/clk-dfll.c:dfll_init",
        "drivers/clk/tegra/clk-dfll.c:dfll_init",
        "drivers/clk/tegra/clk-dfll.c:dfll_init",
        "drivers/clk/tegra/clk-dfll.c:dfll_init",
        "drivers/clk/tegra/clk-dfll.c:dfll_init",
        "drivers/clk/tegra/clk-dfll.c:dfll_init",
        "drivers/clk/tegra/clk-dfll.c:dfll_init",
        "drivers/clk/tegra/clk-dfll.c:dfll_init",
        "drivers/clk/tegra/clk-dfll.c:dfll_init",
        "drivers/clk/tegra/clk-dfll.c:dfll_init",
        "drivers/clk/tegra/clk-dfll.c:dfll_init",
        "drivers/clk/tegra/clk-dfll.c:attr_registers_show",
        "drivers/clk/tegra/clk-dfll.c:attr_registers_show",
        "drivers/clk/tegra/clk-dfll.c:attr_registers_show",
        "drivers/clk/tegra/clk-dfll.c:attr_registers_show",
        "drivers/clk/tegra/clk-dfll.c:attr_registers_show",
        "drivers/clk/tegra/clk-dfll.c:attr_registers_show",
        "drivers/clk/tegra/clk-dfll.c:attr_rate_get",
        "drivers/clk/tegra/clk-dfll.c:attr_rate_get",
        "drivers/clk/tegra/clk-dfll.c:dfll_set_open_loop_config",
        "drivers/clk/tegra/clk-dfll.c:dfll_set_open_loop_config",
        "drivers/clk/tegra/clk-dfll.c:dfll_set_open_loop_config",
        "drivers/clk/tegra/clk-dfll.c:dfll_enable",
        "drivers/clk/tegra/clk-dfll.c:dfll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 3230718664,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/tegra/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/tegra/clk-divider.c:clk_frac_div_set_rate",
        "drivers/clk/tegra/clk-divider.c:clk_frac_div_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3230720452,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/tegra/clk-periph-fixed.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/tegra/clk-periph-fixed.c:tegra_clk_periph_fixed_is_enabled",
        "drivers/clk/tegra/clk-periph-fixed.c:tegra_clk_periph_fixed_is_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 3230721908,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/tegra/clk-periph-gate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/tegra/clk-periph-gate.c:tegra_clk_register_periph_gate",
        "drivers/clk/tegra/clk-periph-gate.c:clk_periph_enable",
        "drivers/clk/tegra/clk-periph-gate.c:clk_periph_is_enabled",
        "drivers/clk/tegra/clk-periph-gate.c:clk_periph_is_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 3230735800,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/tegra/clk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllss",
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllss",
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllss",
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_plle_tegra114",
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_plle_tegra114",
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllre",
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllre",
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllre",
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllxc",
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllxc",
        "drivers/clk/tegra/clk-pll.c:clk_pllu_tegra114_enable",
        "drivers/clk/tegra/clk-pll.c:clk_pllu_tegra114_enable",
        "drivers/clk/tegra/clk-pll.c:clk_pllu_tegra114_enable",
        "drivers/clk/tegra/clk-pll.c:clk_pllu_tegra114_enable",
        "drivers/clk/tegra/clk-pll.c:clk_pllu_tegra114_enable",
        "drivers/clk/tegra/clk-pll.c:clk_pllu_tegra114_enable",
        "drivers/clk/tegra/clk-pll.c:clk_pllu_tegra114_enable",
        "drivers/clk/tegra/clk-pll.c:clk_plle_tegra114_disable",
        "drivers/clk/tegra/clk-pll.c:_clk_pllc_disable",
        "drivers/clk/tegra/clk-pll.c:clk_pllu_enable",
        "drivers/clk/tegra/clk-pll.c:clk_pllu_enable",
        "drivers/clk/tegra/clk-pll.c:clk_pllu_enable",
        "drivers/clk/tegra/clk-pll.c:clk_plle_recalc_rate",
        "drivers/clk/tegra/clk-pll.c:clk_pll_recalc_rate",
        "drivers/clk/tegra/clk-pll.c:_program_pll",
        "drivers/clk/tegra/clk-pll.c:_program_pll",
        "drivers/clk/tegra/clk-pll.c:_program_pll",
        "drivers/clk/tegra/clk-pll.c:_get_pll_mnp",
        "drivers/clk/tegra/clk-pll.c:_get_pll_mnp",
        "drivers/clk/tegra/clk-pll.c:_get_pll_mnp",
        "drivers/clk/tegra/clk-pll.c:_get_pll_mnp",
        "drivers/clk/tegra/clk-pll.c:_get_pll_mnp",
        "drivers/clk/tegra/clk-pll.c:_get_pll_mnp",
        "drivers/clk/tegra/clk-pll.c:_update_pll_mnp",
        "drivers/clk/tegra/clk-pll.c:_update_pll_mnp",
        "drivers/clk/tegra/clk-pll.c:_update_pll_mnp",
        "drivers/clk/tegra/clk-pll.c:_update_pll_mnp",
        "drivers/clk/tegra/clk-pll.c:_update_pll_mnp",
        "drivers/clk/tegra/clk-pll.c:_update_pll_mnp",
        "drivers/clk/tegra/clk-pll.c:clk_pll_disable",
        "drivers/clk/tegra/clk-pll.c:_clk_pll_disable",
        "drivers/clk/tegra/clk-pll.c:_clk_pll_disable",
        "drivers/clk/tegra/clk-pll.c:_clk_pll_disable",
        "drivers/clk/tegra/clk-pll.c:_clk_pll_disable",
        "drivers/clk/tegra/clk-pll.c:_clk_pll_enable",
        "drivers/clk/tegra/clk-pll.c:_clk_pll_enable",
        "drivers/clk/tegra/clk-pll.c:_clk_pll_enable",
        "drivers/clk/tegra/clk-pll.c:_clk_pll_enable",
        "drivers/clk/tegra/clk-pll.c:_clk_pll_enable",
        "drivers/clk/tegra/clk-pll.c:clk_pll_is_enabled",
        "drivers/clk/tegra/clk-pll.c:clk_pll_is_enabled",
        "drivers/clk/tegra/clk-pll.c:clk_pll_wait_for_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 3230736552,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/tegra/clk-pll-out.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/tegra/clk-pll-out.c:clk_pll_out_disable",
        "drivers/clk/tegra/clk-pll-out.c:clk_pll_out_enable",
        "drivers/clk/tegra/clk-pll-out.c:clk_pll_out_is_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 3230737652,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/tegra/clk-sdmmc-mux.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/tegra/clk-sdmmc-mux.c:clk_sdmmc_mux_set_rate",
        "drivers/clk/tegra/clk-sdmmc-mux.c:clk_sdmmc_mux_recalc_rate",
        "drivers/clk/tegra/clk-sdmmc-mux.c:clk_sdmmc_mux_set_parent",
        "drivers/clk/tegra/clk-sdmmc-mux.c:clk_sdmmc_mux_get_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 3230738492,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/tegra/clk-super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/tegra/clk-super.c:clk_super_set_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 3243797620,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/tegra/clk-tegra-fixed.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/tegra/clk-tegra-fixed.c:tegra_osc_clk_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3230741892,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/tegra/clk-emc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/tegra/clk-emc.c:tegra_clk_register_emc",
        "drivers/clk/tegra/clk-emc.c:emc_set_rate",
        "drivers/clk/tegra/clk-emc.c:emc_set_timing",
        "drivers/clk/tegra/clk-emc.c:emc_set_timing",
        "drivers/clk/tegra/clk-emc.c:emc_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3243800256,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/tegra/clk-tegra20.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/tegra/clk-tegra20.c:tegra20_clock_init",
        "drivers/clk/tegra/clk-tegra20.c:tegra20_clock_init",
        "drivers/clk/tegra/clk-tegra20.c:tegra20_cpu_clock_resume",
        "drivers/clk/tegra/clk-tegra20.c:tegra20_cpu_clock_suspend",
        "drivers/clk/tegra/clk-tegra20.c:tegra20_cpu_clock_suspend",
        "drivers/clk/tegra/clk-tegra20.c:tegra20_cpu_clock_suspend",
        "drivers/clk/tegra/clk-tegra20.c:tegra20_cpu_clock_suspend",
        "drivers/clk/tegra/clk-tegra20.c:tegra20_cpu_clock_suspend",
        "drivers/clk/tegra/clk-tegra20.c:tegra20_cpu_rail_off_ready",
        "drivers/clk/tegra/clk-tegra20.c:tegra20_disable_cpu_clock",
        "drivers/clk/tegra/clk-tegra20.c:tegra20_enable_cpu_clock",
        "drivers/clk/tegra/clk-tegra20.c:tegra20_enable_cpu_clock",
        "drivers/clk/tegra/clk-tegra20.c:tegra20_wait_cpu_in_reset",
        "drivers/clk/tegra/clk-tegra20.c:tegra20_periph_clk_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3230744008,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/tegra/clk-tegra30.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/tegra/clk-tegra30.c:tegra30_cpu_clock_resume",
        "drivers/clk/tegra/clk-tegra30.c:tegra30_cpu_clock_suspend",
        "drivers/clk/tegra/clk-tegra30.c:tegra30_cpu_clock_suspend",
        "drivers/clk/tegra/clk-tegra30.c:tegra30_cpu_clock_suspend",
        "drivers/clk/tegra/clk-tegra30.c:tegra30_cpu_clock_suspend",
        "drivers/clk/tegra/clk-tegra30.c:tegra30_cpu_clock_suspend",
        "drivers/clk/tegra/clk-tegra30.c:tegra30_cpu_rail_off_ready",
        "drivers/clk/tegra/clk-tegra30.c:tegra30_disable_cpu_clock",
        "drivers/clk/tegra/clk-tegra30.c:tegra30_enable_cpu_clock",
        "drivers/clk/tegra/clk-tegra30.c:tegra30_wait_cpu_in_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3230745136,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/tegra/clk-tegra114.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/tegra/clk-tegra114.c:tegra114_clock_deassert_dfll_dvco_reset",
        "drivers/clk/tegra/clk-tegra114.c:tegra114_clock_deassert_dfll_dvco_reset",
        "drivers/clk/tegra/clk-tegra114.c:tegra114_clock_assert_dfll_dvco_reset",
        "drivers/clk/tegra/clk-tegra114.c:tegra114_clock_assert_dfll_dvco_reset",
        "drivers/clk/tegra/clk-tegra114.c:tegra114_clock_tune_cpu_trimmers_init",
        "drivers/clk/tegra/clk-tegra114.c:tegra114_clock_tune_cpu_trimmers_high",
        "drivers/clk/tegra/clk-tegra114.c:tegra114_cpu_clock_suspend",
        "drivers/clk/tegra/clk-tegra114.c:tegra114_cpu_clock_suspend",
        "drivers/clk/tegra/clk-tegra114.c:tegra114_cpu_clock_suspend",
        "drivers/clk/tegra/clk-tegra114.c:tegra114_wait_cpu_in_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3243808816,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/tegra/clk-tegra124.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/tegra/clk-tegra124.c:tegra124_132_clock_init_pre",
        "drivers/clk/tegra/clk-tegra124.c:tegra124_reset_deassert",
        "drivers/clk/tegra/clk-tegra124.c:tegra124_reset_deassert",
        "drivers/clk/tegra/clk-tegra124.c:tegra124_reset_assert",
        "drivers/clk/tegra/clk-tegra124.c:tegra124_reset_assert",
        "drivers/clk/tegra/clk-tegra124.c:tegra124_cpu_clock_suspend",
        "drivers/clk/tegra/clk-tegra124.c:tegra124_cpu_clock_suspend",
        "drivers/clk/tegra/clk-tegra124.c:tegra124_cpu_clock_suspend",
        "drivers/clk/tegra/clk-tegra124.c:tegra124_wait_cpu_in_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3230751072,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/ti/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/ti/clk.c:clk_memmap_readl",
        "drivers/clk/ti/clk.c:clk_memmap_readl",
        "drivers/clk/ti/clk.c:clk_memmap_rmw",
        "drivers/clk/ti/clk.c:clk_memmap_rmw"
      ],
      "caller_func": []
    },
    {
      "addr": 3243824184,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/ti/fapll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/ti/fapll.c:ti_fapll_setup",
        "drivers/clk/ti/fapll.c:ti_fapll_synth_set_rate",
        "drivers/clk/ti/fapll.c:ti_fapll_synth_set_rate",
        "drivers/clk/ti/fapll.c:ti_fapll_synth_set_rate",
        "drivers/clk/ti/fapll.c:ti_fapll_synth_round_rate",
        "drivers/clk/ti/fapll.c:ti_fapll_synth_round_rate",
        "drivers/clk/ti/fapll.c:ti_fapll_synth_set_frac_rate",
        "drivers/clk/ti/fapll.c:ti_fapll_synth_is_enabled",
        "drivers/clk/ti/fapll.c:ti_fapll_synth_disable",
        "drivers/clk/ti/fapll.c:ti_fapll_synth_enable",
        "drivers/clk/ti/fapll.c:ti_fapll_set_rate",
        "drivers/clk/ti/fapll.c:ti_fapll_set_rate",
        "drivers/clk/ti/fapll.c:ti_fapll_set_rate",
        "drivers/clk/ti/fapll.c:ti_fapll_set_rate",
        "drivers/clk/ti/fapll.c:ti_fapll_get_parent",
        "drivers/clk/ti/fapll.c:ti_fapll_recalc_rate",
        "drivers/clk/ti/fapll.c:ti_fapll_recalc_rate",
        "drivers/clk/ti/fapll.c:ti_fapll_disable",
        "drivers/clk/ti/fapll.c:ti_fapll_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3230775760,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/ti/adpll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/ti/adpll.c:ti_adpll_probe",
        "drivers/clk/ti/adpll.c:ti_adpll_clkout_get_parent",
        "drivers/clk/ti/adpll.c:ti_adpll_is_prepared",
        "drivers/clk/ti/adpll.c:ti_adpll_unprepare",
        "drivers/clk/ti/adpll.c:ti_adpll_prepare",
        "drivers/clk/ti/adpll.c:ti_adpll_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 3230782516,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clk/versatile/clk-sp810.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/versatile/clk-sp810.c:clk_sp810_timerclken_set_parent",
        "drivers/clk/versatile/clk-sp810.c:clk_sp810_timerclken_get_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 3230801324,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/dma/amba-pl08x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/amba-pl08x.c:pl08x_irq",
        "drivers/dma/amba-pl08x.c:pl08x_irq",
        "drivers/dma/amba-pl08x.c:pl08x_resume",
        "drivers/dma/amba-pl08x.c:pl08x_resume",
        "drivers/dma/amba-pl08x.c:pl08x_pause",
        "drivers/dma/amba-pl08x.c:pl08x_pause",
        "drivers/dma/amba-pl08x.c:pl08x_pause",
        "drivers/dma/amba-pl08x.c:pl08x_pause",
        "drivers/dma/amba-pl08x.c:pl08x_pause",
        "drivers/dma/amba-pl08x.c:pl08x_pause",
        "drivers/dma/amba-pl08x.c:pl08x_phy_free",
        "drivers/dma/amba-pl08x.c:pl08x_phy_free",
        "drivers/dma/amba-pl08x.c:pl08x_phy_free",
        "drivers/dma/amba-pl08x.c:pl08x_start_next_txd",
        "drivers/dma/amba-pl08x.c:pl08x_start_next_txd",
        "drivers/dma/amba-pl08x.c:pl08x_start_next_txd",
        "drivers/dma/amba-pl08x.c:pl08x_start_next_txd",
        "drivers/dma/amba-pl08x.c:pl08x_start_next_txd",
        "drivers/dma/amba-pl08x.c:pl08x_start_next_txd",
        "drivers/dma/amba-pl08x.c:pl08x_start_next_txd"
      ],
      "caller_func": []
    },
    {
      "addr": 3230808964,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/dma/mv_xor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mv_xor.c:mv_xor_suspend",
        "drivers/dma/mv_xor.c:mv_xor_suspend",
        "drivers/dma/mv_xor.c:mv_xor_channel_add",
        "drivers/dma/mv_xor.c:mv_xor_channel_add",
        "drivers/dma/mv_xor.c:mv_xor_channel_add",
        "drivers/dma/mv_xor.c:mv_xor_interrupt_handler",
        "drivers/dma/mv_xor.c:mv_xor_interrupt_handler",
        "drivers/dma/mv_xor.c:mv_xor_interrupt_handler",
        "drivers/dma/mv_xor.c:mv_xor_interrupt_handler",
        "drivers/dma/mv_xor.c:mv_xor_interrupt_handler",
        "drivers/dma/mv_xor.c:mv_xor_interrupt_handler",
        "drivers/dma/mv_xor.c:mv_xor_interrupt_handler",
        "drivers/dma/mv_xor.c:mv_xor_add_io_win",
        "drivers/dma/mv_xor.c:mv_xor_tx_submit",
        "drivers/dma/mv_xor.c:mv_xor_tx_submit",
        "drivers/dma/mv_xor.c:mv_chan_slot_cleanup",
        "drivers/dma/mv_xor.c:mv_chan_slot_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 3230818864,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/dma/mxs-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mxs-dma.c:mxs_dma_tx_status",
        "drivers/dma/mxs-dma.c:mxs_dma_int_handler",
        "drivers/dma/mxs-dma.c:mxs_dma_int_handler",
        "drivers/dma/mxs-dma.c:mxs_dma_reset_chan"
      ],
      "caller_func": []
    },
    {
      "addr": 3230822408,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/dma/ipu/ipu_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_handler",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_handler",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_status",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_mask",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_unmask"
      ],
      "caller_func": []
    },
    {
      "addr": 3230826320,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/dma/ipu/ipu_idmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:idmac_pause",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:ipu_disable_channel",
        "drivers/dma/ipu/ipu_idmac.c:ipu_disable_channel",
        "drivers/dma/ipu/ipu_idmac.c:ipu_disable_channel",
        "drivers/dma/ipu/ipu_idmac.c:ipu_disable_channel",
        "drivers/dma/ipu/ipu_idmac.c:ipu_disable_channel",
        "drivers/dma/ipu/ipu_idmac.c:ipu_disable_channel",
        "drivers/dma/ipu/ipu_idmac.c:ipu_disable_channel",
        "drivers/dma/ipu/ipu_idmac.c:ipu_disable_channel",
        "drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel",
        "drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel",
        "drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel",
        "drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel",
        "drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit",
        "drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit",
        "drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit",
        "drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit",
        "drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer",
        "drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer",
        "drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer",
        "drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer",
        "drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 3230834100,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/dma/tegra20-apb-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_suspend",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_suspend",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_suspend",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_suspend",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_suspend",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_suspend",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_suspend",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_terminate_all",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_terminate_all",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_terminate_all",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_isr",
        "drivers/dma/tegra20-apb-dma.c:tdc_configure_next_head_desc",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_stop",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 3230845608,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/dma/ti/edma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/ti/edma.c:edma_pm_resume",
        "drivers/dma/ti/edma.c:edma_pm_resume",
        "drivers/dma/ti/edma.c:edma_probe",
        "drivers/dma/ti/edma.c:edma_probe",
        "drivers/dma/ti/edma.c:edma_xbar_event_map",
        "drivers/dma/ti/edma.c:edma_alloc_chan_resources",
        "drivers/dma/ti/edma.c:dma_ccerr_handler",
        "drivers/dma/ti/edma.c:dma_ccerr_handler",
        "drivers/dma/ti/edma.c:dma_ccerr_handler",
        "drivers/dma/ti/edma.c:dma_ccerr_handler",
        "drivers/dma/ti/edma.c:dma_ccerr_handler",
        "drivers/dma/ti/edma.c:dma_ccerr_handler",
        "drivers/dma/ti/edma.c:dma_ccerr_handler",
        "drivers/dma/ti/edma.c:dma_ccerr_handler",
        "drivers/dma/ti/edma.c:dma_ccerr_handler",
        "drivers/dma/ti/edma.c:dma_ccerr_handler",
        "drivers/dma/ti/edma.c:dma_ccerr_handler",
        "drivers/dma/ti/edma.c:dma_irq_handler",
        "drivers/dma/ti/edma.c:dma_irq_handler",
        "drivers/dma/ti/edma.c:dma_irq_handler",
        "drivers/dma/ti/edma.c:dma_irq_handler",
        "drivers/dma/ti/edma.c:edma_assign_channel_eventq",
        "drivers/dma/ti/edma.c:edma_clean_channel",
        "drivers/dma/ti/edma.c:edma_trigger_channel",
        "drivers/dma/ti/edma.c:edma_stop",
        "drivers/dma/ti/edma.c:edma_start",
        "drivers/dma/ti/edma.c:edma_start",
        "drivers/dma/ti/edma.c:edma_start",
        "drivers/dma/ti/edma.c:edma_link"
      ],
      "caller_func": []
    },
    {
      "addr": 3230863644,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/dma/ti/omap-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230873812,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/soc/actions/owl-sps-helper.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243833380,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/soc/dove/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/dove/pmu.c:dove_init_pmu",
        "drivers/soc/dove/pmu.c:dove_init_pmu_legacy",
        "drivers/soc/dove/pmu.c:pmu_irq_handler",
        "drivers/soc/dove/pmu.c:pmu_irq_handler",
        "drivers/soc/dove/pmu.c:pmu_domain_power_on",
        "drivers/soc/dove/pmu.c:pmu_domain_power_on",
        "drivers/soc/dove/pmu.c:pmu_domain_power_on",
        "drivers/soc/dove/pmu.c:pmu_domain_power_off",
        "drivers/soc/dove/pmu.c:pmu_domain_power_off",
        "drivers/soc/dove/pmu.c:pmu_domain_power_off",
        "drivers/soc/dove/pmu.c:pmu_reset_deassert",
        "drivers/soc/dove/pmu.c:pmu_reset_assert",
        "drivers/soc/dove/pmu.c:pmu_reset_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3230875696,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/soc/fsl/guts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/guts.c:fsl_guts_probe",
        "drivers/soc/fsl/guts.c:fsl_guts_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3243833880,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/soc/imx/soc-imx8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision",
        "drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision",
        "drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision",
        "drivers/soc/imx/soc-imx8.c:imx8mq_soc_revision",
        "drivers/soc/imx/soc-imx8.c:imx8mq_soc_revision",
        "drivers/soc/imx/soc-imx8.c:imx8mq_soc_revision"
      ],
      "caller_func": []
    },
    {
      "addr": 3230883056,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/soc/mediatek/mtk-scpsys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_domain_is_on",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_domain_is_on"
      ],
      "caller_func": []
    },
    {
      "addr": 3230891776,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/soc/qcom/spm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/qcom/spm.c:spm_set_low_power_mode",
        "drivers/soc/qcom/spm.c:spm_set_low_power_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 3243837128,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/soc/renesas/renesas-soc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init",
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243838148,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/soc/renesas/rcar-rst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/renesas/rcar-rst.c:rcar_rst_read_mode_pins"
      ],
      "caller_func": []
    },
    {
      "addr": 3243839064,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/soc/renesas/rcar-sysc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power"
      ],
      "caller_func": []
    },
    {
      "addr": 3230895000,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/soc/renesas/rmobile-sysc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/renesas/rmobile-sysc.c:__rmobile_pd_power_up",
        "drivers/soc/renesas/rmobile-sysc.c:__rmobile_pd_power_up",
        "drivers/soc/renesas/rmobile-sysc.c:__rmobile_pd_power_up",
        "drivers/soc/renesas/rmobile-sysc.c:rmobile_pd_power_down",
        "drivers/soc/renesas/rmobile-sysc.c:rmobile_pd_power_down",
        "drivers/soc/renesas/rmobile-sysc.c:rmobile_pd_power_down"
      ],
      "caller_func": []
    },
    {
      "addr": 3230899760,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/soc/samsung/exynos-pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/samsung/exynos-pmu.c:pmu_raw_readl"
      ],
      "caller_func": []
    },
    {
      "addr": 3243842112,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/soc/samsung/pm_domains.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/samsung/pm_domains.c:exynos4_pm_init_power_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 3243842824,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/soc/tegra/fuse/fuse-tegra.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/tegra/fuse/fuse-tegra.c:tegra_init_fuse",
        "drivers/soc/tegra/fuse/fuse-tegra.c:tegra_init_fuse"
      ],
      "caller_func": []
    },
    {
      "addr": 3230901552,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/soc/tegra/fuse/fuse-tegra30.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/tegra/fuse/fuse-tegra30.c:tegra30_fuse_read",
        "drivers/soc/tegra/fuse/fuse-tegra30.c:tegra30_fuse_read_early"
      ],
      "caller_func": []
    },
    {
      "addr": 3243843804,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/soc/tegra/fuse/tegra-apbmisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/tegra/fuse/tegra-apbmisc.c:tegra_init_revision",
        "drivers/soc/tegra/fuse/tegra-apbmisc.c:tegra_read_ram_code",
        "drivers/soc/tegra/fuse/tegra-apbmisc.c:tegra_get_chip_id"
      ],
      "caller_func": []
    },
    {
      "addr": 3230902040,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/soc/tegra/fuse/fuse-tegra20.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_read_early"
      ],
      "caller_func": []
    },
    {
      "addr": 3230903328,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/soc/tegra/flowctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/tegra/flowctrl.c:flowctrl_read_cpu_csr",
        "drivers/soc/tegra/flowctrl.c:flowctrl_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3243847776,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/soc/tegra/pmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/tegra/pmc.c:tegra_pmc_early_init",
        "drivers/soc/tegra/pmc.c:tegra_pmc_early_init",
        "drivers/soc/tegra/pmc.c:tegra186_pmc_setup_irq_polarity",
        "drivers/soc/tegra/pmc.c:tegra20_pmc_setup_irq_polarity",
        "drivers/soc/tegra/pmc.c:tegra20_pmc_init",
        "drivers/soc/tegra/pmc.c:tegra20_pmc_init",
        "drivers/soc/tegra/pmc.c:tegra20_pmc_init",
        "drivers/soc/tegra/pmc.c:tegra_pmc_irq_set_type",
        "drivers/soc/tegra/pmc.c:tegra_pmc_irq_set_wake",
        "drivers/soc/tegra/pmc.c:reset_level_show",
        "drivers/soc/tegra/pmc.c:reset_reason_show",
        "drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_set",
        "drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_set",
        "drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_set",
        "drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_get",
        "drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_get",
        "drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_get",
        "drivers/soc/tegra/pmc.c:tegra_pmc_enter_suspend_mode",
        "drivers/soc/tegra/pmc.c:tegra_pmc_restart_notify",
        "drivers/soc/tegra/pmc.c:tegra_pmc_restart_notify",
        "drivers/soc/tegra/pmc.c:tegra_powergate_is_powered",
        "drivers/soc/tegra/pmc.c:tegra_powergate_is_powered",
        "drivers/soc/tegra/pmc.c:tegra_powergate_set",
        "drivers/soc/tegra/pmc.c:tegra_powergate_set",
        "drivers/soc/tegra/pmc.c:tegra_powergate_set",
        "drivers/soc/tegra/pmc.c:tegra_powergate_set",
        "drivers/soc/tegra/pmc.c:tegra_powergate_set",
        "drivers/soc/tegra/pmc.c:tegra_powergate_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3230944100,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/virtio/virtio_mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_mmio.c:vm_interrupt",
        "drivers/virtio/virtio_mmio.c:vm_get_status",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_mmio.c:vm_get_features",
        "drivers/virtio/virtio_mmio.c:vm_get_features"
      ],
      "caller_func": []
    },
    {
      "addr": 3230945704,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features"
      ],
      "caller_func": []
    },
    {
      "addr": 3230952932,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features"
      ],
      "caller_func": []
    },
    {
      "addr": 3231015428,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/regulator/ti-abb-regulator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/ti-abb-regulator.c:ti_abb_probe",
        "drivers/regulator/ti-abb-regulator.c:ti_abb_probe",
        "drivers/regulator/ti-abb-regulator.c:ti_abb_init_table",
        "drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel",
        "drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel",
        "drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel",
        "drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel",
        "drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel",
        "drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel",
        "drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel",
        "drivers/regulator/ti-abb-regulator.c:ti_abb_clear_all_txdone",
        "drivers/regulator/ti-abb-regulator.c:ti_abb_clear_all_txdone"
      ],
      "caller_func": []
    },
    {
      "addr": 3231030636,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/reset/reset-meson.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/reset-meson.c:meson_reset_deassert",
        "drivers/reset/reset-meson.c:meson_reset_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 3231031228,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/reset/reset-simple.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/reset-simple.c:reset_simple_status",
        "drivers/reset/reset-simple.c:reset_simple_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3231207208,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_in",
        "drivers/tty/serial/8250/8250_port.c:mem32_serial_in",
        "drivers/tty/serial/8250/8250_port.c:au_serial_dl_read",
        "drivers/tty/serial/8250/8250_port.c:au_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 3231227148,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/tty/serial/8250/8250_dwlib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231231708,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3231239636,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_in",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_in"
      ],
      "caller_func": []
    },
    {
      "addr": 3231249508,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/tty/serial/amba-pl011.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/amba-pl011.c:pl011_putc",
        "drivers/tty/serial/amba-pl011.c:pl011_putc",
        "drivers/tty/serial/amba-pl011.c:qdf2400_e44_putc",
        "drivers/tty/serial/amba-pl011.c:qdf2400_e44_putc",
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_write",
        "drivers/tty/serial/amba-pl011.c:pl011_console_write",
        "drivers/tty/serial/amba-pl011.c:pl011_console_putchar",
        "drivers/tty/serial/amba-pl011.c:pl011_set_termios",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts",
        "drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts",
        "drivers/tty/serial/amba-pl011.c:pl011_put_poll_char",
        "drivers/tty/serial/amba-pl011.c:pl011_get_poll_char",
        "drivers/tty/serial/amba-pl011.c:pl011_get_poll_char",
        "drivers/tty/serial/amba-pl011.c:pl011_get_poll_char",
        "drivers/tty/serial/amba-pl011.c:pl011_get_poll_char",
        "drivers/tty/serial/amba-pl011.c:pl011_break_ctl",
        "drivers/tty/serial/amba-pl011.c:pl011_set_mctrl",
        "drivers/tty/serial/amba-pl011.c:pl011_get_mctrl",
        "drivers/tty/serial/amba-pl011.c:pl011_tx_empty",
        "drivers/tty/serial/amba-pl011.c:pl011_int",
        "drivers/tty/serial/amba-pl011.c:pl011_int",
        "drivers/tty/serial/amba-pl011.c:pl011_int",
        "drivers/tty/serial/amba-pl011.c:pl011_int",
        "drivers/tty/serial/amba-pl011.c:pl011_int",
        "drivers/tty/serial/amba-pl011.c:pl011_tx_char",
        "drivers/tty/serial/amba-pl011.c:pl011_start_tx",
        "drivers/tty/serial/amba-pl011.c:pl011_fifo_to_tty",
        "drivers/tty/serial/amba-pl011.c:pl011_fifo_to_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 3231273444,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/tty/serial/imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_console_early_putchar",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/imx.c:imx_uart_console_write",
        "drivers/tty/serial/imx.c:imx_uart_poll_put_char",
        "drivers/tty/serial/imx.c:imx_uart_poll_put_char",
        "drivers/tty/serial/imx.c:imx_uart_poll_get_char",
        "drivers/tty/serial/imx.c:imx_uart_poll_get_char",
        "drivers/tty/serial/imx.c:imx_uart_set_termios",
        "drivers/tty/serial/imx.c:imx_uart_set_termios",
        "drivers/tty/serial/imx.c:imx_uart_flush_buffer",
        "drivers/tty/serial/imx.c:imx_uart_flush_buffer",
        "drivers/tty/serial/imx.c:imx_uart_flush_buffer",
        "drivers/tty/serial/imx.c:imx_uart_dma_rx_callback",
        "drivers/tty/serial/imx.c:imx_uart_dma_rx_callback",
        "drivers/tty/serial/imx.c:imx_uart_tx_empty",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_get_hwmctrl",
        "drivers/tty/serial/imx.c:imx_uart_get_hwmctrl",
        "drivers/tty/serial/imx.c:imx_uart_get_hwmctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 3231290260,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/tty/serial/meson_uart.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/meson_uart.c:meson_serial_early_console_setup",
        "drivers/tty/serial/meson_uart.c:meson_serial_console_setup",
        "drivers/tty/serial/meson_uart.c:meson_serial_port_write",
        "drivers/tty/serial/meson_uart.c:meson_uart_set_termios",
        "drivers/tty/serial/meson_uart.c:meson_uart_set_termios",
        "drivers/tty/serial/meson_uart.c:meson_uart_startup",
        "drivers/tty/serial/meson_uart.c:meson_uart_interrupt",
        "drivers/tty/serial/meson_uart.c:meson_uart_interrupt",
        "drivers/tty/serial/meson_uart.c:meson_uart_interrupt",
        "drivers/tty/serial/meson_uart.c:meson_uart_interrupt",
        "drivers/tty/serial/meson_uart.c:meson_uart_interrupt",
        "drivers/tty/serial/meson_uart.c:meson_uart_interrupt",
        "drivers/tty/serial/meson_uart.c:meson_uart_interrupt",
        "drivers/tty/serial/meson_uart.c:meson_uart_start_tx",
        "drivers/tty/serial/meson_uart.c:meson_uart_start_tx",
        "drivers/tty/serial/meson_uart.c:meson_uart_start_tx",
        "drivers/tty/serial/meson_uart.c:meson_uart_shutdown",
        "drivers/tty/serial/meson_uart.c:meson_uart_stop_rx"
      ],
      "caller_func": []
    },
    {
      "addr": 3231301448,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/tty/serial/msm_serial.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/msm_serial.c:__msm_console_write",
        "drivers/tty/serial/msm_serial.c:__msm_console_write",
        "drivers/tty/serial/msm_serial.c:__msm_console_write",
        "drivers/tty/serial/msm_serial.c:__msm_console_write",
        "drivers/tty/serial/msm_serial.c:msm_poll_put_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_put_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_put_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_put_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_put_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_put_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_get_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_get_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_get_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_get_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_get_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_get_char",
        "drivers/tty/serial/msm_serial.c:msm_poll_get_char",
        "drivers/tty/serial/msm_serial.c:msm_set_termios",
        "drivers/tty/serial/msm_serial.c:msm_set_termios",
        "drivers/tty/serial/msm_serial.c:msm_set_termios",
        "drivers/tty/serial/msm_serial.c:msm_startup",
        "drivers/tty/serial/msm_serial.c:msm_set_mctrl",
        "drivers/tty/serial/msm_serial.c:msm_tx_empty",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx_pio",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx_pio",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx_pio",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx_pio",
        "drivers/tty/serial/msm_serial.c:msm_complete_rx_dma",
        "drivers/tty/serial/msm_serial.c:msm_complete_rx_dma",
        "drivers/tty/serial/msm_serial.c:msm_complete_rx_dma",
        "drivers/tty/serial/msm_serial.c:msm_complete_tx_dma",
        "drivers/tty/serial/msm_serial.c:msm_stop_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 3231318460,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/tty/serial/omap-serial.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/omap-serial.c:serial_omap_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3231324256,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/tty/serial/mvebu-uart.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write",
        "drivers/tty/serial/mvebu-uart.c:wait_for_xmitr",
        "drivers/tty/serial/mvebu-uart.c:wait_for_xmitr",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_putc",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_putc",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_put_poll_char",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_get_poll_char",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_get_poll_char",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_tx_isr",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_isr",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_isr",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_break_ctl",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_rx",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_rx",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_start_tx",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_tx",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_tx_empty"
      ],
      "caller_func": []
    },
    {
      "addr": 3231328268,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/tty/serial/owl-uart.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/owl-uart.c:owl_uart_port_write",
        "drivers/tty/serial/owl-uart.c:owl_uart_port_write",
        "drivers/tty/serial/owl-uart.c:owl_uart_port_write",
        "drivers/tty/serial/owl-uart.c:owl_uart_set_termios",
        "drivers/tty/serial/owl-uart.c:owl_uart_shutdown",
        "drivers/tty/serial/owl-uart.c:owl_uart_irq",
        "drivers/tty/serial/owl-uart.c:owl_uart_irq",
        "drivers/tty/serial/owl-uart.c:owl_uart_irq",
        "drivers/tty/serial/owl-uart.c:owl_uart_irq",
        "drivers/tty/serial/owl-uart.c:owl_uart_irq",
        "drivers/tty/serial/owl-uart.c:owl_uart_irq",
        "drivers/tty/serial/owl-uart.c:owl_uart_irq",
        "drivers/tty/serial/owl-uart.c:owl_uart_irq",
        "drivers/tty/serial/owl-uart.c:owl_uart_stop_tx",
        "drivers/tty/serial/owl-uart.c:owl_uart_stop_tx",
        "drivers/tty/serial/owl-uart.c:owl_uart_stop_rx",
        "drivers/tty/serial/owl-uart.c:owl_uart_stop_rx",
        "drivers/tty/serial/owl-uart.c:owl_uart_tx_empty",
        "drivers/tty/serial/owl-uart.c:owl_uart_get_mctrl",
        "drivers/tty/serial/owl-uart.c:owl_uart_get_mctrl",
        "drivers/tty/serial/owl-uart.c:owl_uart_set_mctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 3231332040,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/tty/serial/rda-uart.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/rda-uart.c:rda_uart_port_write",
        "drivers/tty/serial/rda-uart.c:rda_uart_port_write",
        "drivers/tty/serial/rda-uart.c:rda_uart_shutdown",
        "drivers/tty/serial/rda-uart.c:rda_uart_startup",
        "drivers/tty/serial/rda-uart.c:rda_uart_startup",
        "drivers/tty/serial/rda-uart.c:rda_interrupt",
        "drivers/tty/serial/rda-uart.c:rda_interrupt",
        "drivers/tty/serial/rda-uart.c:rda_interrupt",
        "drivers/tty/serial/rda-uart.c:rda_interrupt",
        "drivers/tty/serial/rda-uart.c:rda_interrupt",
        "drivers/tty/serial/rda-uart.c:rda_interrupt",
        "drivers/tty/serial/rda-uart.c:rda_interrupt",
        "drivers/tty/serial/rda-uart.c:rda_uart_set_termios",
        "drivers/tty/serial/rda-uart.c:rda_uart_set_termios",
        "drivers/tty/serial/rda-uart.c:rda_uart_set_termios",
        "drivers/tty/serial/rda-uart.c:rda_uart_set_termios",
        "drivers/tty/serial/rda-uart.c:rda_uart_stop_rx",
        "drivers/tty/serial/rda-uart.c:rda_uart_stop_rx",
        "drivers/tty/serial/rda-uart.c:rda_uart_stop_rx",
        "drivers/tty/serial/rda-uart.c:rda_uart_stop_tx",
        "drivers/tty/serial/rda-uart.c:rda_uart_stop_tx",
        "drivers/tty/serial/rda-uart.c:rda_uart_set_mctrl",
        "drivers/tty/serial/rda-uart.c:rda_uart_set_mctrl",
        "drivers/tty/serial/rda-uart.c:rda_uart_set_mctrl",
        "drivers/tty/serial/rda-uart.c:rda_uart_get_mctrl",
        "drivers/tty/serial/rda-uart.c:rda_uart_get_mctrl",
        "drivers/tty/serial/rda-uart.c:rda_uart_tx_empty"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231428384,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32"
      ],
      "caller_func": []
    },
    {
      "addr": 3231456388,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/iommu/ipmmu-vmsa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_irq",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_irq",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_tlb_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 3231461868,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/iommu/omap-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/omap-iommu.c:omap_iommu_runtime_resume",
        "drivers/iommu/omap-iommu.c:omap_iommu_runtime_resume",
        "drivers/iommu/omap-iommu.c:omap_iommu_runtime_suspend",
        "drivers/iommu/omap-iommu.c:omap_iommu_runtime_suspend",
        "drivers/iommu/omap-iommu.c:omap_iommu_runtime_suspend",
        "drivers/iommu/omap-iommu.c:omap_iommu_runtime_suspend",
        "drivers/iommu/omap-iommu.c:omap_iommu_runtime_suspend",
        "drivers/iommu/omap-iommu.c:iommu_fault_handler",
        "drivers/iommu/omap-iommu.c:iommu_fault_handler",
        "drivers/iommu/omap-iommu.c:flush_iotlb_page",
        "drivers/iommu/omap-iommu.c:flush_iotlb_page",
        "drivers/iommu/omap-iommu.c:flush_iotlb_page",
        "drivers/iommu/omap-iommu.c:omap_iommu_save_ctx"
      ],
      "caller_func": []
    },
    {
      "addr": 3231473308,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/iommu/rockchip-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/rockchip-iommu.c:rk_iommu_enable",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_enable",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_enable",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_enable",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_enable",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_enable",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_enable",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_disable",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_disable",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_disable",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_disable",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_irq",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_irq",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_irq",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3231479408,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/iommu/tegra-gart.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/tegra-gart.c:tegra_gart_probe",
        "drivers/iommu/tegra-gart.c:tegra_gart_resume",
        "drivers/iommu/tegra-gart.c:tegra_gart_suspend",
        "drivers/iommu/tegra-gart.c:tegra_gart_suspend",
        "drivers/iommu/tegra-gart.c:gart_iommu_sync",
        "drivers/iommu/tegra-gart.c:gart_iommu_iova_to_phys",
        "drivers/iommu/tegra-gart.c:gart_iommu_unmap",
        "drivers/iommu/tegra-gart.c:gart_iommu_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3231485032,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/iommu/tegra-smmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/tegra-smmu.c:tegra_smmu_probe",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_clients_show",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_swgroups_show",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_set_pte",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_set_pde",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_detach_dev",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_detach_dev",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_attach_dev",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_attach_dev",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_attach_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 3231491120,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/iommu/exynos-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/exynos-iommu.c:exynos_sysmmu_probe",
        "drivers/iommu/exynos-iommu.c:exynos_sysmmu_irq",
        "drivers/iommu/exynos-iommu.c:exynos_sysmmu_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3231499384,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/iommu/qcom_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_fault",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_fault",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_fault",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_fault",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_sync",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 3231718540,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/base/regmap/regmap-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32le"
      ],
      "caller_func": []
    },
    {
      "addr": 3231753328,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/misc/vexpress-syscfg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec",
        "drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec",
        "drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 3231765572,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/mfd/sm501.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/sm501.c:sm501_plat_resume",
        "drivers/mfd/sm501.c:sm501_plat_suspend",
        "drivers/mfd/sm501.c:sm501_init_dev",
        "drivers/mfd/sm501.c:sm501_init_dev",
        "drivers/mfd/sm501.c:sm501_init_dev",
        "drivers/mfd/sm501.c:sm501_init_regs",
        "drivers/mfd/sm501.c:sm501_init_regs",
        "drivers/mfd/sm501.c:sm501_init_regs",
        "drivers/mfd/sm501.c:sm501_dbg_regs",
        "drivers/mfd/sm501.c:sm501_gpio_output",
        "drivers/mfd/sm501.c:sm501_gpio_output",
        "drivers/mfd/sm501.c:sm501_gpio_output",
        "drivers/mfd/sm501.c:sm501_gpio_output",
        "drivers/mfd/sm501.c:sm501_gpio_input",
        "drivers/mfd/sm501.c:sm501_gpio_input",
        "drivers/mfd/sm501.c:sm501_gpio_input",
        "drivers/mfd/sm501.c:sm501_gpio_set",
        "drivers/mfd/sm501.c:sm501_gpio_set",
        "drivers/mfd/sm501.c:sm501_gpio_set",
        "drivers/mfd/sm501.c:sm501_gpio_get",
        "drivers/mfd/sm501.c:sm501_set_clock",
        "drivers/mfd/sm501.c:sm501_set_clock",
        "drivers/mfd/sm501.c:sm501_set_clock",
        "drivers/mfd/sm501.c:sm501_set_clock",
        "drivers/mfd/sm501.c:sm501_set_clock",
        "drivers/mfd/sm501.c:sm501_set_clock",
        "drivers/mfd/sm501.c:sm501_set_clock",
        "drivers/mfd/sm501.c:sm501_unit_power",
        "drivers/mfd/sm501.c:sm501_unit_power",
        "drivers/mfd/sm501.c:sm501_unit_power",
        "drivers/mfd/sm501.c:sm501_unit_power",
        "drivers/mfd/sm501.c:sm501_modify_reg",
        "drivers/mfd/sm501.c:sm501_modify_reg",
        "drivers/mfd/sm501.c:sm501_misc_control",
        "drivers/mfd/sm501.c:sm501_misc_control"
      ],
      "caller_func": []
    },
    {
      "addr": 3231927488,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/mfd/omap-usb-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/omap-usb-host.c:usbhs_omap_probe",
        "drivers/mfd/omap-usb-host.c:usbhs_omap_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3231930600,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/mfd/omap-usb-tll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/omap-usb-tll.c:omap_tll_init",
        "drivers/mfd/omap-usb-tll.c:omap_tll_init",
        "drivers/mfd/omap-usb-tll.c:usbtll_omap_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3231943784,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/mfd/vexpress-sysreg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe",
        "drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3232137352,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3232251704,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/ata/libahci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libahci.c:ahci_set_em_messages",
        "drivers/ata/libahci.c:ahci_set_em_messages",
        "drivers/ata/libahci.c:ahci_port_start",
        "drivers/ata/libahci.c:ahci_port_suspend",
        "drivers/ata/libahci.c:ahci_port_suspend",
        "drivers/ata/libahci.c:ahci_port_resume",
        "drivers/ata/libahci.c:ahci_pmp_detach",
        "drivers/ata/libahci.c:ahci_pmp_attach",
        "drivers/ata/libahci.c:ahci_disable_fbs",
        "drivers/ata/libahci.c:ahci_disable_fbs",
        "drivers/ata/libahci.c:ahci_enable_fbs",
        "drivers/ata/libahci.c:ahci_enable_fbs",
        "drivers/ata/libahci.c:ahci_set_aggressive_devslp",
        "drivers/ata/libahci.c:ahci_thaw",
        "drivers/ata/libahci.c:ahci_qc_issue",
        "drivers/ata/libahci.c:ahci_single_level_irq_intr",
        "drivers/ata/libahci.c:ahci_handle_port_intr",
        "drivers/ata/libahci.c:ahci_multi_irqs_intr_hard",
        "drivers/ata/libahci.c:ahci_handle_port_interrupt",
        "drivers/ata/libahci.c:ahci_handle_port_interrupt",
        "drivers/ata/libahci.c:ahci_handle_port_interrupt",
        "drivers/ata/libahci.c:ahci_handle_port_interrupt",
        "drivers/ata/libahci.c:ahci_error_intr",
        "drivers/ata/libahci.c:ahci_error_intr",
        "drivers/ata/libahci.c:ahci_error_intr",
        "drivers/ata/libahci.c:ahci_error_intr",
        "drivers/ata/libahci.c:ahci_error_intr",
        "drivers/ata/libahci.c:ahci_postreset",
        "drivers/ata/libahci.c:ahci_postreset",
        "drivers/ata/libahci.c:ahci_pmp_retry_softreset",
        "drivers/ata/libahci.c:ahci_bad_pmp_check_ready",
        "drivers/ata/libahci.c:ahci_bad_pmp_check_ready",
        "drivers/ata/libahci.c:ahci_check_ready",
        "drivers/ata/libahci.c:ahci_kick_engine",
        "drivers/ata/libahci.c:ahci_kick_engine",
        "drivers/ata/libahci.c:ahci_dev_classify",
        "drivers/ata/libahci.c:ahci_init_controller",
        "drivers/ata/libahci.c:ahci_init_controller",
        "drivers/ata/libahci.c:ahci_init_controller",
        "drivers/ata/libahci.c:ahci_init_controller",
        "drivers/ata/libahci.c:ahci_init_controller",
        "drivers/ata/libahci.c:ahci_transmit_led_message",
        "drivers/ata/libahci.c:ahci_reset_em",
        "drivers/ata/libahci.c:ahci_reset_controller",
        "drivers/ata/libahci.c:ahci_reset_controller",
        "drivers/ata/libahci.c:ahci_reset_controller",
        "drivers/ata/libahci.c:ahci_set_lpm",
        "drivers/ata/libahci.c:ahci_set_lpm",
        "drivers/ata/libahci.c:ahci_start_fis_rx",
        "drivers/ata/libahci.c:ahci_start_fis_rx",
        "drivers/ata/libahci.c:ahci_stop_engine",
        "drivers/ata/libahci.c:ahci_start_engine",
        "drivers/ata/libahci.c:ahci_start_engine",
        "drivers/ata/libahci.c:ahci_save_initial_config",
        "drivers/ata/libahci.c:ahci_save_initial_config",
        "drivers/ata/libahci.c:ahci_save_initial_config",
        "drivers/ata/libahci.c:ahci_save_initial_config",
        "drivers/ata/libahci.c:ahci_save_initial_config",
        "drivers/ata/libahci.c:ahci_show_em_supported",
        "drivers/ata/libahci.c:ahci_store_em_buffer",
        "drivers/ata/libahci.c:ahci_read_em_buffer",
        "drivers/ata/libahci.c:ahci_read_em_buffer",
        "drivers/ata/libahci.c:ahci_show_port_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 3232267928,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/ata/libahci_platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libahci_platform.c:ahci_platform_suspend_host",
        "drivers/ata/libahci_platform.c:ahci_platform_suspend_host",
        "drivers/ata/libahci_platform.c:ahci_platform_shutdown",
        "drivers/ata/libahci_platform.c:ahci_platform_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 3232271228,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/ata/sata_highbank.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/sata_highbank.c:ahci_highbank_suspend",
        "drivers/ata/sata_highbank.c:ahci_highbank_suspend",
        "drivers/ata/sata_highbank.c:__combo_phy_reg_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3232279380,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/ata/ahci_imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/ahci_imx.c:imx_ahci_probe",
        "drivers/ata/ahci_imx.c:imx_ahci_probe",
        "drivers/ata/ahci_imx.c:ahci_imx_error_handler",
        "drivers/ata/ahci_imx.c:imx_phy_crbit_assert",
        "drivers/ata/ahci_imx.c:imx_phy_crbit_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 3232339408,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/mtd/maps/map_funcs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mtd/maps/map_funcs.c:simple_map_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3232413624,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/mtd/nand/raw/omap2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mtd/nand/raw/omap2.c:omap_calculate_ecc_bch_multi",
        "drivers/mtd/nand/raw/omap2.c:omap_calculate_ecc",
        "drivers/mtd/nand/raw/omap2.c:omap_calculate_ecc",
        "drivers/mtd/nand/raw/omap2.c:omap_write_buf_irq_pref",
        "drivers/mtd/nand/raw/omap2.c:omap_nand_irq",
        "drivers/mtd/nand/raw/omap2.c:omap_write_buf_dma_pref",
        "drivers/mtd/nand/raw/omap2.c:omap_read_buf_dma_pref",
        "drivers/mtd/nand/raw/omap2.c:omap_write_buf_pref",
        "drivers/mtd/nand/raw/omap2.c:omap_write_buf_pref",
        "drivers/mtd/nand/raw/omap2.c:omap_read_buf_pref",
        "drivers/mtd/nand/raw/omap2.c:omap_prefetch_reset",
        "drivers/mtd/nand/raw/omap2.c:omap_prefetch_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3232419520,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/mtd/nand/raw/omap_elm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mtd/nand/raw/omap_elm.c:elm_suspend",
        "drivers/mtd/nand/raw/omap_elm.c:elm_suspend",
        "drivers/mtd/nand/raw/omap_elm.c:elm_suspend",
        "drivers/mtd/nand/raw/omap_elm.c:elm_suspend",
        "drivers/mtd/nand/raw/omap_elm.c:elm_suspend",
        "drivers/mtd/nand/raw/omap_elm.c:elm_suspend",
        "drivers/mtd/nand/raw/omap_elm.c:elm_suspend",
        "drivers/mtd/nand/raw/omap_elm.c:elm_suspend",
        "drivers/mtd/nand/raw/omap_elm.c:elm_suspend",
        "drivers/mtd/nand/raw/omap_elm.c:elm_suspend",
        "drivers/mtd/nand/raw/omap_elm.c:elm_suspend",
        "drivers/mtd/nand/raw/omap_elm.c:elm_suspend",
        "drivers/mtd/nand/raw/omap_elm.c:elm_isr",
        "drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page",
        "drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page",
        "drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page",
        "drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page",
        "drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page",
        "drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page",
        "drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3232453956,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/spi/spi-fsl-spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_irq",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_irq",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_irq",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_setup",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 3232464596,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/spi/spi-omap2-mcspi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_prepare_message",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_irq_handler",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup_transfer",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_tx_callback",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_callback",
        "drivers/spi/spi-omap2-mcspi.c:mcspi_wait_for_reg_bit",
        "drivers/spi/spi-omap2-mcspi.c:mcspi_wait_for_reg_bit",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs"
      ],
      "caller_func": []
    },
    {
      "addr": 3232549680,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_init",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_init",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_init",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_close",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_ethtool_stats",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_interrupt",
        "drivers/net/ethernet/freescale/fec_main.c:fec_stop",
        "drivers/net/ethernet/freescale/fec_main.c:fec_stop",
        "drivers/net/ethernet/freescale/fec_main.c:fec_stop",
        "drivers/net/ethernet/freescale/fec_main.c:fec_restart",
        "drivers/net/ethernet/freescale/fec_main.c:fec_restart",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso"
      ],
      "caller_func": []
    },
    {
      "addr": 3232556540,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/net/ethernet/freescale/fec_ptp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_adjfreq",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_read",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3232560184,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/net/ethernet/freescale/xgmac_mdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_write",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_write",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_wait_until_done",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_wait_until_done",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_wait_until_free",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_wait_until_free"
      ],
      "caller_func": []
    },
    {
      "addr": 3232561852,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/net/ethernet/ti/davinci_mdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_runtime_suspend",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_runtime_suspend",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_runtime_suspend",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_reset",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3232565076,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/net/ethernet/ti/cpts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/cpts.c:cpts_fifo_read",
        "drivers/net/ethernet/ti/cpts.c:cpts_fifo_read",
        "drivers/net/ethernet/ti/cpts.c:cpts_fifo_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3232579992,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/net/ethernet/ti/cpsw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_ioctl",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_set_fifo_rlimit",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_set_fifo_rlimit",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_set_fifo_rlimit",
        "drivers/net/ethernet/ti/cpsw.c:_cpsw_adjust_link",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_fifo_shp_on"
      ],
      "caller_func": []
    },
    {
      "addr": 3232598568,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/net/ethernet/ti/davinci_cpdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_control_get",
        "drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_stop",
        "drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_stop",
        "drivers/net/ethernet/ti/davinci_cpdma.c:__cpdma_chan_process",
        "drivers/net/ethernet/ti/davinci_cpdma.c:__cpdma_chan_process",
        "drivers/net/ethernet/ti/davinci_cpdma.c:__cpdma_chan_free",
        "drivers/net/ethernet/ti/davinci_cpdma.c:__cpdma_chan_free",
        "drivers/net/ethernet/ti/davinci_cpdma.c:__cpdma_chan_free",
        "drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si",
        "drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si",
        "drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctrl_txchs_state",
        "drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctrl_rxchs_state",
        "drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_start",
        "drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_set_chan_shaper",
        "drivers/net/ethernet/ti/davinci_cpdma.c:_cpdma_control_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3232603212,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/net/ethernet/ti/cpsw_ale.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_create",
        "drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_create",
        "drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_control_get",
        "drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_control_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3232603632,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/net/ethernet/ti/cpsw_priv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/cpsw_priv.c:cpsw_init_common"
      ],
      "caller_func": []
    },
    {
      "addr": 3232604456,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/net/ethernet/ti/cpsw_sl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232607316,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/net/ethernet/ti/cpsw_ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_get_ethtool_stats",
        "drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_set_coalesce"
      ],
      "caller_func": []
    },
    {
      "addr": 3232663020,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/auxdisplay/arm-charlcd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232811360,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/phy/phy-mxs-usb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3232813724,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/phy/phy-ulpi-viewport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_write",
        "drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_write",
        "drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_read",
        "drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_read",
        "drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3232821152,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel",
        "drivers/usb/dwc2/core.c:dwc2_hw_is_device",
        "drivers/usb/dwc2/core.c:dwc2_hw_is_host",
        "drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts",
        "drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts",
        "drivers/usb/dwc2/core.c:dwc2_is_controller_alive",
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo",
        "drivers/usb/dwc2/core.c:dwc2_enable_acg",
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
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
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers"
      ],
      "caller_func": []
    },
    {
      "addr": 3232826164,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr"
      ],
      "caller_func": []
    },
    {
      "addr": 3232829196,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:dwc2_resume",
        "drivers/usb/dwc2/platform.c:dwc2_suspend",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3232834644,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ],
      "caller_func": []
    },
    {
      "addr": 3232868580,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_halt",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_halt",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_halt",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_halt",
        "drivers/usb/dwc2/hcd.c:dwc2_read_packet",
        "drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval",
        "drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval",
        "drivers/usb/dwc2/hcd.c:dwc2_config_fifos",
        "drivers/usb/dwc2/hcd.c:dwc2_config_fifos",
        "drivers/usb/dwc2/hcd.c:dwc2_config_fifos",
        "drivers/usb/dwc2/hcd.c:dwc2_config_fifos",
        "drivers/usb/dwc2/hcd.c:dwc2_config_fifos",
        "drivers/usb/dwc2/hcd.c:dwc2_config_fifos",
        "drivers/usb/dwc2/hcd.c:dwc2_config_fifos",
        "drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts",
        "drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts"
      ],
      "caller_func": []
    },
    {
      "addr": 3232879640,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state_abn",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state"
      ],
      "caller_func": []
    },
    {
      "addr": 3232885868,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3232891292,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 3232899980,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll"
      ],
      "caller_func": []
    },
    {
      "addr": 3232931376,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_get_frame",
        "drivers/usb/host/ehci-hcd.c:ehci_get_frame",
        "drivers/usb/host/ehci-hcd.c:ehci_get_frame",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_silence_controller",
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:iso_stream_schedule",
        "drivers/usb/host/ehci-hcd.c:iso_stream_schedule",
        "drivers/usb/host/ehci-hcd.c:iso_stream_schedule",
        "drivers/usb/host/ehci-hcd.c:ehci_port_power",
        "drivers/usb/host/ehci-hcd.c:ehci_port_handed_over",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_status_data",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_status_data",
        "drivers/usb/host/ehci-hcd.c:set_owner",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_disable_PSE",
        "drivers/usb/host/ehci-hcd.c:ehci_disable_ASE",
        "drivers/usb/host/ehci-hcd.c:ehci_set_command_bit",
        "drivers/usb/host/ehci-hcd.c:ehci_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 3232955364,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/host/ehci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 3232956732,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/host/ehci-orion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3232983788,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:_ohci_shutdown",
        "drivers/usb/host/ohci-hcd.c:start_ed_unlink",
        "drivers/usb/host/ohci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ohci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ohci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ohci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3233002164,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number",
        "drivers/usb/host/uhci-hcd.c:uhci_irq",
        "drivers/usb/host/uhci-hcd.c:wakeup_rh",
        "drivers/usb/host/uhci-hcd.c:wakeup_rh",
        "drivers/usb/host/uhci-hcd.c:start_rh",
        "drivers/usb/host/uhci-hcd.c:suspend_rh",
        "drivers/usb/host/uhci-hcd.c:suspend_rh",
        "drivers/usb/host/uhci-hcd.c:uhci_generic_check_and_reset_hc",
        "drivers/usb/host/uhci-hcd.c:uhci_generic_check_and_reset_hc",
        "drivers/usb/host/uhci-hcd.c:uhci_generic_reset_hc",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_check_ports",
        "drivers/usb/host/uhci-hcd.c:uhci_finish_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_finish_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_finish_suspend",
        "drivers/usb/host/uhci-hcd.c:any_ports_active",
        "drivers/usb/host/uhci-hcd.c:uhci_show_status",
        "drivers/usb/host/uhci-hcd.c:uhci_show_status",
        "drivers/usb/host/uhci-hcd.c:uhci_show_status",
        "drivers/usb/host/uhci-hcd.c:uhci_show_status",
        "drivers/usb/host/uhci-hcd.c:uhci_show_status",
        "drivers/usb/host/uhci-hcd.c:uhci_show_status",
        "drivers/usb/host/uhci-hcd.c:uhci_show_status",
        "drivers/usb/host/uhci-hcd.c:uhci_show_status",
        "drivers/usb/host/uhci-hcd.c:uhci_show_status",
        "drivers/usb/host/uhci-hcd.c:uhci_show_status"
      ],
      "caller_func": []
    },
    {
      "addr": 3233045580,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:compliance_mode_recovery",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_quiesce",
        "drivers/usb/host/xhci.c:xhci_quiesce",
        "drivers/usb/host/xhci.c:xhci_handshake",
        "drivers/usb/host/xhci.c:xhci_handshake"
      ],
      "caller_func": []
    },
    {
      "addr": 3233080832,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
      ],
      "caller_func": []
    },
    {
      "addr": 3233083248,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3233101984,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 3233127692,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_link_state",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": []
    },
    {
      "addr": 3233147780,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ],
      "caller_func": []
    },
    {
      "addr": 3233162500,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
      ],
      "caller_func": []
    },
    {
      "addr": 3233163568,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk"
      ],
      "caller_func": []
    },
    {
      "addr": 3233169108,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/usb/musb/musb_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/musb/musb_core.c:musb_readl"
      ],
      "caller_func": []
    },
    {
      "addr": 3243902196,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/rtc/rtc-mv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-mv.c:mv_rtc_probe",
        "drivers/rtc/rtc-mv.c:mv_rtc_probe",
        "drivers/rtc/rtc-mv.c:mv_rtc_interrupt",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_read_time"
      ],
      "caller_func": []
    },
    {
      "addr": 3233331116,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/rtc/rtc-omap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-omap.c:omap_rtc_scratch_read",
        "drivers/rtc/rtc-omap.c:rtc_pinconf_set",
        "drivers/rtc/rtc-omap.c:rtc_pinconf_get",
        "drivers/rtc/rtc-omap.c:omap_rtc_power_off",
        "drivers/rtc/rtc-omap.c:omap_rtc_power_off_program"
      ],
      "caller_func": []
    },
    {
      "addr": 3233340244,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/rtc/rtc-pl031.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-pl031.c:pl031_probe",
        "drivers/rtc/rtc-pl031.c:pl031_probe",
        "drivers/rtc/rtc-pl031.c:pl031_probe",
        "drivers/rtc/rtc-pl031.c:pl031_read_alarm",
        "drivers/rtc/rtc-pl031.c:pl031_read_alarm",
        "drivers/rtc/rtc-pl031.c:pl031_read_alarm",
        "drivers/rtc/rtc-pl031.c:pl031_read_time",
        "drivers/rtc/rtc-pl031.c:pl031_stv2_read_alarm",
        "drivers/rtc/rtc-pl031.c:pl031_stv2_read_alarm",
        "drivers/rtc/rtc-pl031.c:pl031_stv2_read_alarm",
        "drivers/rtc/rtc-pl031.c:pl031_stv2_read_alarm",
        "drivers/rtc/rtc-pl031.c:pl031_stv2_read_time",
        "drivers/rtc/rtc-pl031.c:pl031_stv2_read_time",
        "drivers/rtc/rtc-pl031.c:pl031_alarm_irq_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3233340936,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/rtc/rtc-s3c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-s3c.c:s3c6410_rtc_save_tick_cnt"
      ],
      "caller_func": []
    },
    {
      "addr": 3233382632,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access"
      ],
      "caller_func": []
    },
    {
      "addr": 3233406932,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/i2c/busses/i2c-s3c2410.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_init",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_init",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_xfer",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_xfer",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_xfer",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_xfer",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_wait_idle",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_wait_idle",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_wait_idle",
        "drivers/i2c/busses/i2c-s3c2410.c:i2c_s3c_irq_nextbyte",
        "drivers/i2c/busses/i2c-s3c2410.c:i2c_s3c_irq_nextbyte",
        "drivers/i2c/busses/i2c-s3c2410.c:i2c_s3c_irq_nextbyte",
        "drivers/i2c/busses/i2c-s3c2410.c:i2c_s3c_irq_nextbyte",
        "drivers/i2c/busses/i2c-s3c2410.c:i2c_s3c_irq_nextbyte",
        "drivers/i2c/busses/i2c-s3c2410.c:i2c_s3c_irq_nextbyte",
        "drivers/i2c/busses/i2c-s3c2410.c:i2c_s3c_irq_nextbyte",
        "drivers/i2c/busses/i2c-s3c2410.c:i2c_s3c_irq_nextbyte",
        "drivers/i2c/busses/i2c-s3c2410.c:i2c_s3c_irq_nextbyte",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_message_start",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_message_start",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_message_start",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_message_start",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_message_start"
      ],
      "caller_func": []
    },
    {
      "addr": 3233454940,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/power/avs/smartreflex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/avs/smartreflex.c:sr_disable",
        "drivers/power/avs/smartreflex.c:sr_disable",
        "drivers/power/avs/smartreflex.c:sr_disable",
        "drivers/power/avs/smartreflex.c:sr_disable",
        "drivers/power/avs/smartreflex.c:sr_disable",
        "drivers/power/avs/smartreflex.c:sr_disable",
        "drivers/power/avs/smartreflex.c:sr_disable",
        "drivers/power/avs/smartreflex.c:sr_disable",
        "drivers/power/avs/smartreflex.c:sr_disable",
        "drivers/power/avs/smartreflex.c:sr_disable",
        "drivers/power/avs/smartreflex.c:sr_disable",
        "drivers/power/avs/smartreflex.c:sr_disable",
        "drivers/power/avs/smartreflex.c:sr_enable",
        "drivers/power/avs/smartreflex.c:sr_enable",
        "drivers/power/avs/smartreflex.c:sr_configure_minmax",
        "drivers/power/avs/smartreflex.c:sr_disable_errgen",
        "drivers/power/avs/smartreflex.c:sr_disable_errgen",
        "drivers/power/avs/smartreflex.c:sr_configure_errgen",
        "drivers/power/avs/smartreflex.c:sr_configure_errgen",
        "drivers/power/avs/smartreflex.c:sr_interrupt",
        "drivers/power/avs/smartreflex.c:sr_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 3233538616,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/thermal/samsung/exynos_tmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/samsung/exynos_tmu.c:exynos4210_tmu_clear_irqs",
        "drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_set_emulation",
        "drivers/thermal/samsung/exynos_tmu.c:exynos7_tmu_control",
        "drivers/thermal/samsung/exynos_tmu.c:exynos5433_tmu_control",
        "drivers/thermal/samsung/exynos_tmu.c:exynos4210_tmu_control",
        "drivers/thermal/samsung/exynos_tmu.c:exynos7_tmu_set_trip_hyst",
        "drivers/thermal/samsung/exynos_tmu.c:exynos7_tmu_set_trip_temp",
        "drivers/thermal/samsung/exynos_tmu.c:exynos5433_tmu_initialize",
        "drivers/thermal/samsung/exynos_tmu.c:exynos5433_tmu_set_trip_hyst",
        "drivers/thermal/samsung/exynos_tmu.c:exynos5433_tmu_set_trip_temp",
        "drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_initialize",
        "drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_initialize",
        "drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_initialize",
        "drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_set_trip_hyst",
        "drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_set_trip_temp",
        "drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_set_trip_temp",
        "drivers/thermal/samsung/exynos_tmu.c:exynos4210_tmu_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 3233556352,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/watchdog/npcm_wdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/npcm_wdt.c:npcm_wdt_probe",
        "drivers/watchdog/npcm_wdt.c:npcm_wdt_ping"
      ],
      "caller_func": []
    },
    {
      "addr": 3233557548,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/watchdog/aspeed_wdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/aspeed_wdt.c:aspeed_wdt_probe",
        "drivers/watchdog/aspeed_wdt.c:aspeed_wdt_probe",
        "drivers/watchdog/aspeed_wdt.c:aspeed_wdt_probe",
        "drivers/watchdog/aspeed_wdt.c:access_cs0_show"
      ],
      "caller_func": []
    },
    {
      "addr": 3233752444,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/edac/armada_xp_edac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/armada_xp_edac.c:aurora_l2_probe",
        "drivers/edac/armada_xp_edac.c:aurora_l2_check",
        "drivers/edac/armada_xp_edac.c:aurora_l2_check",
        "drivers/edac/armada_xp_edac.c:aurora_l2_check",
        "drivers/edac/armada_xp_edac.c:aurora_l2_check",
        "drivers/edac/armada_xp_edac.c:axp_mc_probe",
        "drivers/edac/armada_xp_edac.c:axp_mc_probe",
        "drivers/edac/armada_xp_edac.c:axp_mc_probe",
        "drivers/edac/armada_xp_edac.c:axp_mc_probe",
        "drivers/edac/armada_xp_edac.c:axp_mc_check",
        "drivers/edac/armada_xp_edac.c:axp_mc_check",
        "drivers/edac/armada_xp_edac.c:axp_mc_check",
        "drivers/edac/armada_xp_edac.c:axp_mc_check",
        "drivers/edac/armada_xp_edac.c:axp_mc_check",
        "drivers/edac/armada_xp_edac.c:axp_mc_check",
        "drivers/edac/armada_xp_edac.c:axp_mc_check",
        "drivers/edac/armada_xp_edac.c:axp_mc_check",
        "drivers/edac/armada_xp_edac.c:axp_mc_check"
      ],
      "caller_func": []
    },
    {
      "addr": 3233774132,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/opp/ti-opp-supply.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233943664,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/mmc/host/mmci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/mmci.c:mmci_irq",
        "drivers/mmc/host/mmci.c:mmci_irq",
        "drivers/mmc/host/mmci.c:mmci_pio_irq",
        "drivers/mmc/host/mmci.c:mmci_pio_irq",
        "drivers/mmc/host/mmci.c:mmci_pio_irq",
        "drivers/mmc/host/mmci.c:mmci_pio_irq",
        "drivers/mmc/host/mmci.c:mmci_pio_irq",
        "drivers/mmc/host/mmci.c:mmci_pio_irq",
        "drivers/mmc/host/mmci.c:mmci_get_rx_fifocnt",
        "drivers/mmc/host/mmci.c:mmci_cmd_irq",
        "drivers/mmc/host/mmci.c:mmci_cmd_irq",
        "drivers/mmc/host/mmci.c:mmci_cmd_irq",
        "drivers/mmc/host/mmci.c:mmci_cmd_irq",
        "drivers/mmc/host/mmci.c:mmci_cmd_irq",
        "drivers/mmc/host/mmci.c:mmci_cmd_irq",
        "drivers/mmc/host/mmci.c:mmci_cmd_irq",
        "drivers/mmc/host/mmci.c:mmci_data_irq",
        "drivers/mmc/host/mmci.c:mmci_start_data",
        "drivers/mmc/host/mmci.c:mmci_dmae_finalize",
        "drivers/mmc/host/mmci.c:mmci_set_mask1",
        "drivers/mmc/host/mmci.c:mmci_dma_start",
        "drivers/mmc/host/mmci.c:mmci_card_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 3233944100,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/mmc/host/mmci_qcom_dml.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start",
        "drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start",
        "drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start",
        "drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start"
      ],
      "caller_func": []
    },
    {
      "addr": 3233959492,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/mmc/host/sdhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/sdhci.c:sdhci_setup_host",
        "drivers/mmc/host/sdhci.c:sdhci_setup_host",
        "drivers/mmc/host/sdhci.c:sdhci_setup_host",
        "drivers/mmc/host/sdhci.c:sdhci_setup_host",
        "drivers/mmc/host/sdhci.c:__sdhci_read_caps",
        "drivers/mmc/host/sdhci.c:__sdhci_read_caps",
        "drivers/mmc/host/sdhci.c:sdhci_cqe_disable",
        "drivers/mmc/host/sdhci.c:sdhci_cqe_enable",
        "drivers/mmc/host/sdhci.c:sdhci_irq",
        "drivers/mmc/host/sdhci.c:sdhci_irq",
        "drivers/mmc/host/sdhci.c:sdhci_irq",
        "drivers/mmc/host/sdhci.c:sdhci_irq",
        "drivers/mmc/host/sdhci.c:sdhci_irq",
        "drivers/mmc/host/sdhci.c:sdhci_irq",
        "drivers/mmc/host/sdhci.c:sdhci_irq",
        "drivers/mmc/host/sdhci.c:sdhci_card_busy",
        "drivers/mmc/host/sdhci.c:sdhci_check_ro",
        "drivers/mmc/host/sdhci.c:sdhci_get_cd",
        "drivers/mmc/host/sdhci.c:sdhci_send_command",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs",
        "drivers/mmc/host/sdhci.c:sdhci_dumpregs"
      ],
      "caller_func": []
    },
    {
      "addr": 3233981784,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/mmc/host/omap_hsmmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_resume",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_resume",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_resume",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_resume",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_resume",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_resume",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_resume",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_resume",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_resume",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_suspend",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_suspend",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_suspend",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_suspend",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_suspend",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_suspend",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/mmc/host/omap_hsmmc.c:mmc_regs_show",
        "drivers/mmc/host/omap_hsmmc.c:mmc_regs_show",
        "drivers/mmc/host/omap_hsmmc.c:mmc_regs_show",
        "drivers/mmc/host/omap_hsmmc.c:mmc_regs_show",
        "drivers/mmc/host/omap_hsmmc.c:mmc_regs_show",
        "drivers/mmc/host/omap_hsmmc.c:mmc_regs_show",
        "drivers/mmc/host/omap_hsmmc.c:mmc_regs_show",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_conf_bus_power",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_conf_bus_power",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_enable_sdio_irq",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_enable_sdio_irq",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_enable_sdio_irq",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios",
        "drivers/mmc/host/omap_hsmmc.c:set_data_timeout",
        "drivers/mmc/host/omap_hsmmc.c:set_sd_bus_power",
        "drivers/mmc/host/omap_hsmmc.c:set_sd_bus_power",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_irq",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_irq",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_irq",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_irq",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_irq",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_irq",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_irq",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_irq",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_bus_width",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_bus_width",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_bus_width",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 3233992680,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/mmc/host/sdhci-pltfm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 3234001656,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/mmc/host/sdhci-esdhc-imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_suspend",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_remove",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_cqe_enable",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_cqe_enable",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_cqe_enable",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_cqe_enable",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_timeout",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_uhs_signaling",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_uhs_signaling",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_uhs_signaling",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_uhs_signaling",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_uhs_signaling",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_hs400_enhanced_strobe",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_executing_tuning",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_prepare_tuning",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_prepare_tuning",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_pltfm_set_bus_width",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writeb_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writeb_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writeb_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writeb_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writeb_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writeb_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readw_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readw_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readw_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readw_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writel_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writel_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readl_le",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readl_le"
      ],
      "caller_func": []
    },
    {
      "addr": 3234003304,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/mmc/host/cqhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/cqhci.c:cqhci_init",
        "drivers/mmc/host/cqhci.c:cqhci_init",
        "drivers/mmc/host/cqhci.c:cqhci_init",
        "drivers/mmc/host/cqhci.c:cqhci_init",
        "drivers/mmc/host/cqhci.c:cqhci_recovery_finish",
        "drivers/mmc/host/cqhci.c:cqhci_halt",
        "drivers/mmc/host/cqhci.c:cqhci_halt",
        "drivers/mmc/host/cqhci.c:cqhci_halt",
        "drivers/mmc/host/cqhci.c:cqhci_halt",
        "drivers/mmc/host/cqhci.c:cqhci_halt",
        "drivers/mmc/host/cqhci.c:cqhci_irq",
        "drivers/mmc/host/cqhci.c:cqhci_irq",
        "drivers/mmc/host/cqhci.c:cqhci_irq",
        "drivers/mmc/host/cqhci.c:cqhci_request",
        "drivers/mmc/host/cqhci.c:cqhci_request",
        "drivers/mmc/host/cqhci.c:cqhci_off",
        "drivers/mmc/host/cqhci.c:cqhci_enable",
        "drivers/mmc/host/cqhci.c:__cqhci_disable",
        "drivers/mmc/host/cqhci.c:__cqhci_enable",
        "drivers/mmc/host/cqhci.c:cqhci_dumpregs",
        "drivers/mmc/host/cqhci.c:cqhci_dumpregs",
        "drivers/mmc/host/cqhci.c:cqhci_dumpregs",
        "drivers/mmc/host/cqhci.c:cqhci_dumpregs",
        "drivers/mmc/host/cqhci.c:cqhci_dumpregs",
        "drivers/mmc/host/cqhci.c:cqhci_dumpregs",
        "drivers/mmc/host/cqhci.c:cqhci_dumpregs",
        "drivers/mmc/host/cqhci.c:cqhci_dumpregs",
        "drivers/mmc/host/cqhci.c:cqhci_dumpregs",
        "drivers/mmc/host/cqhci.c:cqhci_dumpregs",
        "drivers/mmc/host/cqhci.c:cqhci_dumpregs",
        "drivers/mmc/host/cqhci.c:cqhci_dumpregs",
        "drivers/mmc/host/cqhci.c:cqhci_dumpregs",
        "drivers/mmc/host/cqhci.c:cqhci_dumpregs",
        "drivers/mmc/host/cqhci.c:cqhci_dumpregs",
        "drivers/mmc/host/cqhci.c:cqhci_dumpregs",
        "drivers/mmc/host/cqhci.c:cqhci_dumpregs",
        "drivers/mmc/host/cqhci.c:cqhci_dumpregs",
        "drivers/mmc/host/cqhci.c:cqhci_dumpregs",
        "drivers/mmc/host/cqhci.c:cqhci_dumpregs",
        "drivers/mmc/host/cqhci.c:cqhci_dumpregs",
        "drivers/mmc/host/cqhci.c:cqhci_dumpregs"
      ],
      "caller_func": []
    },
    {
      "addr": 3234034980,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/firmware/arm_scmi/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/driver.c:scmi_xfer_done_no_timeout",
        "drivers/firmware/arm_scmi/driver.c:scmi_xfer_done_no_timeout",
        "drivers/firmware/arm_scmi/driver.c:scmi_rx_callback",
        "drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare",
        "drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare",
        "drivers/firmware/arm_scmi/driver.c:scmi_fetch_response",
        "drivers/firmware/arm_scmi/driver.c:scmi_fetch_response"
      ],
      "caller_func": []
    },
    {
      "addr": 3234042832,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/firmware/arm_scmi/perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_level_get",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db"
      ],
      "caller_func": []
    },
    {
      "addr": 3234087096,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/sh_cmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_cmt.c:sh_cmt_read32"
      ],
      "caller_func": []
    },
    {
      "addr": 3234093940,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/renesas-ostm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/renesas-ostm.c:ostm_read_sched_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 3234094524,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/sh_tmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_tmu.c:sh_tmu_clocksource_read",
        "drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch"
      ],
      "caller_func": []
    },
    {
      "addr": 3234097820,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/em_sti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/em_sti.c:em_sti_count",
        "drivers/clocksource/em_sti.c:em_sti_count"
      ],
      "caller_func": []
    },
    {
      "addr": 3234099508,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/mmio.c:clocksource_mmio_readl_down",
        "drivers/clocksource/mmio.c:clocksource_mmio_readl_up"
      ],
      "caller_func": []
    },
    {
      "addr": 3234100840,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/timer-ti-dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_probe",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timers_active",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timers_active",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_int_disable",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_int_disable",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_int_disable",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_prescaler",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_prescaler",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_pwm",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_pwm",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_match",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_match",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_load",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_load",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_start",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_start",
        "drivers/clocksource/timer-ti-dm.c:_omap_dm_timer_request",
        "drivers/clocksource/timer-ti-dm.c:_omap_dm_timer_request",
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_write_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 3234105668,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/dw_apb_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/dw_apb_timer.c:__apbt_read_clocksource",
        "drivers/clocksource/dw_apb_timer.c:dw_apb_clocksource_start",
        "drivers/clocksource/dw_apb_timer.c:dw_apb_clocksource_start",
        "drivers/clocksource/dw_apb_timer.c:apbt_next_event",
        "drivers/clocksource/dw_apb_timer.c:apbt_set_periodic",
        "drivers/clocksource/dw_apb_timer.c:apbt_set_oneshot",
        "drivers/clocksource/dw_apb_timer.c:apbt_shutdown",
        "drivers/clocksource/dw_apb_timer.c:apbt_enable_int",
        "drivers/clocksource/dw_apb_timer.c:apbt_enable_int",
        "drivers/clocksource/dw_apb_timer.c:apbt_eoi",
        "drivers/clocksource/dw_apb_timer.c:dw_apb_clockevent_pause"
      ],
      "caller_func": []
    },
    {
      "addr": 3234107584,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/dw_apb_timer_of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/dw_apb_timer_of.c:dw_apb_delay_timer_read",
        "drivers/clocksource/dw_apb_timer_of.c:read_sched_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 3234107936,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/timer-rockchip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-rockchip.c:rk_timer_sched_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3243947024,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/timer-armada-370-xp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_common_init",
        "drivers/clocksource/timer-armada-370-xp.c:armada_370_delay_timer_read",
        "drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_suspend",
        "drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_suspend",
        "drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_starting_cpu",
        "drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_clkevt_set_periodic",
        "drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_clkevt_shutdown",
        "drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_clkevt_next_event",
        "drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_read_sched_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 3234109156,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/timer-orion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-orion.c:orion_read_sched_clock",
        "drivers/clocksource/timer-orion.c:orion_read_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 3243948512,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/timer-meson6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-meson6.c:meson6_timer_init",
        "drivers/clocksource/timer-meson6.c:meson6_timer_init",
        "drivers/clocksource/timer-meson6.c:meson6_clkevt_next_event",
        "drivers/clocksource/timer-meson6.c:meson6_clkevt_next_event",
        "drivers/clocksource/timer-meson6.c:meson6_set_periodic",
        "drivers/clocksource/timer-meson6.c:meson6_set_periodic",
        "drivers/clocksource/timer-meson6.c:meson6_set_oneshot",
        "drivers/clocksource/timer-meson6.c:meson6_set_oneshot",
        "drivers/clocksource/timer-meson6.c:meson6_shutdown",
        "drivers/clocksource/timer-meson6.c:meson6_timer_sched_read",
        "drivers/clocksource/timer-meson6.c:meson6_read_current_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 3234110320,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/timer-tegra.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-tegra.c:tegra_rtc_read_ms",
        "drivers/clocksource/timer-tegra.c:tegra_rtc_read_ms",
        "drivers/clocksource/timer-tegra.c:tegra_delay_timer_read_counter_long",
        "drivers/clocksource/timer-tegra.c:tegra_read_sched_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 3243950692,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/exynos_mct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/exynos_mct.c:mct_init_dt",
        "drivers/clocksource/exynos_mct.c:exynos4_mct_tick_clear",
        "drivers/clocksource/exynos_mct.c:exynos4_mct_tick_start",
        "drivers/clocksource/exynos_mct.c:exynos4_mct_tick_stop",
        "drivers/clocksource/exynos_mct.c:exynos4_mct_comp0_start",
        "drivers/clocksource/exynos_mct.c:exynos4_mct_comp0_start",
        "drivers/clocksource/exynos_mct.c:exynos4_mct_comp0_start",
        "drivers/clocksource/exynos_mct.c:exynos4_mct_comp0_start",
        "drivers/clocksource/exynos_mct.c:exynos4_mct_comp0_stop",
        "drivers/clocksource/exynos_mct.c:exynos4_read_current_timer",
        "drivers/clocksource/exynos_mct.c:exynos4_read_sched_clock",
        "drivers/clocksource/exynos_mct.c:exynos4_frc_resume",
        "drivers/clocksource/exynos_mct.c:exynos4_frc_read",
        "drivers/clocksource/exynos_mct.c:exynos4_mct_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3234112728,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/timer-qcom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-qcom.c:msm_read_timer_count",
        "drivers/clocksource/timer-qcom.c:msm_timer_shutdown",
        "drivers/clocksource/timer-qcom.c:msm_timer_set_next_event",
        "drivers/clocksource/timer-qcom.c:msm_timer_set_next_event",
        "drivers/clocksource/timer-qcom.c:msm_timer_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 3243952284,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/timer-mediatek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-mediatek.c:mtk_gpt_init",
        "drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_next_event",
        "drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_next_event",
        "drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_set_periodic",
        "drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_set_periodic",
        "drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_shutdown",
        "drivers/clocksource/timer-mediatek.c:mtk_gpt_read_sched_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 3243952428,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/timer-ti-32k.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-ti-32k.c:ti_32k_timer_init",
        "drivers/clocksource/timer-ti-32k.c:omap_32k_read_sched_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 3243952724,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/timer-owl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-owl.c:owl_timer_init",
        "drivers/clocksource/timer-owl.c:owl_timer_set_next_event",
        "drivers/clocksource/timer-owl.c:owl_timer_set_next_event",
        "drivers/clocksource/timer-owl.c:owl_timer_set_state_shutdown",
        "drivers/clocksource/timer-owl.c:owl_timer_sched_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3234114692,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/timer-milbeaut.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-milbeaut.c:mlb_timer_sched_read",
        "drivers/clocksource/timer-milbeaut.c:mlb_clkevt_next_event",
        "drivers/clocksource/timer-milbeaut.c:mlb_set_state_shutdown",
        "drivers/clocksource/timer-milbeaut.c:mlb_set_state_oneshot",
        "drivers/clocksource/timer-milbeaut.c:mlb_set_state_periodic",
        "drivers/clocksource/timer-milbeaut.c:mlb_timer_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 3243953232,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/timer-npcm7xx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_init",
        "drivers/clocksource/timer-npcm7xx.c:npcm7xx_clockevent_set_next_event",
        "drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_periodic",
        "drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_oneshot",
        "drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_shutdown",
        "drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 3234115492,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/timer-rda.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-rda.c:rda_hwtimer_read",
        "drivers/clocksource/timer-rda.c:rda_hwtimer_read",
        "drivers/clocksource/timer-rda.c:rda_hwtimer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3243955488,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/arm_arch_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init",
        "drivers/clocksource/arm_arch_timer.c:arch_counter_get_cntvct_mem",
        "drivers/clocksource/arm_arch_timer.c:arch_counter_get_cntvct_mem",
        "drivers/clocksource/arm_arch_timer.c:arch_counter_get_cntvct_mem",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_set_next_event_phys_mem",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_set_next_event_virt_mem",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_shutdown_phys_mem",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_shutdown_virt_mem",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_handler_virt_mem",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_handler_phys_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 3234117984,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/arm_global_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/arm_global_timer.c:gt_read_long",
        "drivers/clocksource/arm_global_timer.c:gt_sched_clock_read",
        "drivers/clocksource/arm_global_timer.c:gt_sched_clock_read",
        "drivers/clocksource/arm_global_timer.c:gt_sched_clock_read",
        "drivers/clocksource/arm_global_timer.c:gt_clocksource_read",
        "drivers/clocksource/arm_global_timer.c:gt_clocksource_read",
        "drivers/clocksource/arm_global_timer.c:gt_clocksource_read",
        "drivers/clocksource/arm_global_timer.c:gt_clockevent_shutdown",
        "drivers/clocksource/arm_global_timer.c:gt_compare_set",
        "drivers/clocksource/arm_global_timer.c:gt_compare_set",
        "drivers/clocksource/arm_global_timer.c:gt_compare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3234118512,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/timer-sp804.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-sp804.c:sp804_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3234118964,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/timer-versatile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-versatile.c:versatile_sys_24mhz_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3234119728,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/timer-imx-gpt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-imx-gpt.c:mxc_timer_interrupt",
        "drivers/clocksource/timer-imx-gpt.c:mxc_set_oneshot",
        "drivers/clocksource/timer-imx-gpt.c:mxc_shutdown",
        "drivers/clocksource/timer-imx-gpt.c:v2_set_next_event",
        "drivers/clocksource/timer-imx-gpt.c:v2_set_next_event",
        "drivers/clocksource/timer-imx-gpt.c:mx1_2_set_next_event",
        "drivers/clocksource/timer-imx-gpt.c:mx1_2_set_next_event",
        "drivers/clocksource/timer-imx-gpt.c:imx_read_current_timer",
        "drivers/clocksource/timer-imx-gpt.c:mxc_read_sched_clock",
        "drivers/clocksource/timer-imx-gpt.c:imx1_gpt_irq_enable",
        "drivers/clocksource/timer-imx-gpt.c:imx1_gpt_irq_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 3243959928,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/clocksource/timer-imx-tpm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-imx-tpm.c:tpm_timer_init",
        "drivers/clocksource/timer-imx-tpm.c:tpm_set_state_shutdown",
        "drivers/clocksource/timer-imx-tpm.c:tpm_set_state_oneshot",
        "drivers/clocksource/timer-imx-tpm.c:tpm_set_next_event",
        "drivers/clocksource/timer-imx-tpm.c:tpm_set_next_event",
        "drivers/clocksource/timer-imx-tpm.c:tpm_read_sched_clock",
        "drivers/clocksource/timer-imx-tpm.c:tpm_read_current_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 3234188676,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/staging/emxx_udc/emxx_udc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_suspend",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_suspend",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_vbus_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_vbus_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_fifo_flush",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_fifo_flush",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_set_stall",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_restert_transfer",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_in_transfer",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_in_transfer",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_in_transfer",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_out_transfer",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_out_transfer",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_out_transfer",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_out_transfer",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_out_transfer",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_out_transfer",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_out_transfer",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_out_transfer",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_out_transfer",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_out_transfer",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_out_transfer",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_out_transfer",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_out_transfer",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_in_transfer",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_in_transfer",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_in_transfer",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_in_transfer",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_in_transfer",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep_dma_abort",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep_dma_abort"
      ],
      "caller_func": []
    },
    {
      "addr": 3234202324,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/mailbox/pl320-ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pl320-ipc.c:pl320_ipc_transmit"
      ],
      "caller_func": []
    },
    {
      "addr": 3234203028,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/mailbox/rockchip-mailbox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3234206856,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/mailbox/tegra-hsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/tegra-hsp.c:tegra_hsp_probe",
        "drivers/mailbox/tegra-hsp.c:tegra_hsp_mailbox_flush",
        "drivers/mailbox/tegra-hsp.c:tegra_hsp_doorbell_shutdown",
        "drivers/mailbox/tegra-hsp.c:tegra_hsp_doorbell_startup",
        "drivers/mailbox/tegra-hsp.c:tegra_hsp_doorbell_startup",
        "drivers/mailbox/tegra-hsp.c:tegra_hsp_shared_irq",
        "drivers/mailbox/tegra-hsp.c:tegra_hsp_shared_irq",
        "drivers/mailbox/tegra-hsp.c:tegra_hsp_doorbell_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3234273080,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/memory/omap-gpmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/memory/omap-gpmc.c:omap3_gpmc_save_context",
        "drivers/memory/omap-gpmc.c:omap3_gpmc_save_context",
        "drivers/memory/omap-gpmc.c:omap3_gpmc_save_context",
        "drivers/memory/omap-gpmc.c:omap3_gpmc_save_context",
        "drivers/memory/omap-gpmc.c:omap3_gpmc_save_context",
        "drivers/memory/omap-gpmc.c:omap3_gpmc_save_context",
        "drivers/memory/omap-gpmc.c:omap3_gpmc_save_context",
        "drivers/memory/omap-gpmc.c:omap3_gpmc_save_context",
        "drivers/memory/omap-gpmc.c:omap3_gpmc_save_context",
        "drivers/memory/omap-gpmc.c:omap3_gpmc_save_context",
        "drivers/memory/omap-gpmc.c:omap3_gpmc_save_context",
        "drivers/memory/omap-gpmc.c:omap3_gpmc_save_context",
        "drivers/memory/omap-gpmc.c:omap3_gpmc_save_context",
        "drivers/memory/omap-gpmc.c:omap3_gpmc_save_context",
        "drivers/memory/omap-gpmc.c:omap3_gpmc_save_context",
        "drivers/memory/omap-gpmc.c:gpmc_probe",
        "drivers/memory/omap-gpmc.c:gpmc_probe",
        "drivers/memory/omap-gpmc.c:gpmc_probe",
        "drivers/memory/omap-gpmc.c:gpmc_probe",
        "drivers/memory/omap-gpmc.c:gpmc_probe",
        "drivers/memory/omap-gpmc.c:gpmc_gpio_get",
        "drivers/memory/omap-gpmc.c:gpmc_probe_generic_child",
        "drivers/memory/omap-gpmc.c:gpmc_probe_generic_child",
        "drivers/memory/omap-gpmc.c:gpmc_probe_generic_child",
        "drivers/memory/omap-gpmc.c:gpmc_probe_generic_child",
        "drivers/memory/omap-gpmc.c:gpmc_probe_generic_child",
        "drivers/memory/omap-gpmc.c:gpmc_mem_exit",
        "drivers/memory/omap-gpmc.c:gpmc_handle_irq",
        "drivers/memory/omap-gpmc.c:gpmc_irq_set_type",
        "drivers/memory/omap-gpmc.c:gpmc_irq_set_type",
        "drivers/memory/omap-gpmc.c:gpmc_irq_enable",
        "drivers/memory/omap-gpmc.c:gpmc_irq_disable",
        "drivers/memory/omap-gpmc.c:gpmc_nand_writebuffer_empty",
        "drivers/memory/omap-gpmc.c:gpmc_cs_free",
        "drivers/memory/omap-gpmc.c:gpmc_cs_request",
        "drivers/memory/omap-gpmc.c:gpmc_cs_request",
        "drivers/memory/omap-gpmc.c:gpmc_cs_request",
        "drivers/memory/omap-gpmc.c:gpmc_cs_set_memconf",
        "drivers/memory/omap-gpmc.c:gpmc_cs_set_timings",
        "drivers/memory/omap-gpmc.c:gpmc_cs_set_timings",
        "drivers/memory/omap-gpmc.c:gpmc_cs_set_timings",
        "drivers/memory/omap-gpmc.c:gpmc_cs_set_timings",
        "drivers/memory/omap-gpmc.c:gpmc_cs_set_timings",
        "drivers/memory/omap-gpmc.c:gpmc_cs_set_timings",
        "drivers/memory/omap-gpmc.c:gpmc_cs_set_timings",
        "drivers/memory/omap-gpmc.c:gpmc_cs_set_timings",
        "drivers/memory/omap-gpmc.c:set_gpmc_timing_reg",
        "drivers/memory/omap-gpmc.c:set_gpmc_timing_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 3234278268,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/memory/mtk-smi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/memory/mtk-smi.c:mtk_smi_larb_config_port_gen1",
        "drivers/memory/mtk-smi.c:mtk_smi_larb_config_port_gen2_general"
      ],
      "caller_func": []
    },
    {
      "addr": 3234280096,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/memory/samsung/exynos-srom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/memory/samsung/exynos-srom.c:exynos_srom_suspend",
        "drivers/memory/samsung/exynos-srom.c:exynos_srom_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3234283548,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/memory/tegra/mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/memory/tegra/mc.c:tegra_mc_probe",
        "drivers/memory/tegra/mc.c:tegra_mc_probe",
        "drivers/memory/tegra/mc.c:tegra20_mc_irq",
        "drivers/memory/tegra/mc.c:tegra20_mc_irq",
        "drivers/memory/tegra/mc.c:tegra20_mc_irq",
        "drivers/memory/tegra/mc.c:tegra20_mc_irq",
        "drivers/memory/tegra/mc.c:tegra20_mc_irq",
        "drivers/memory/tegra/mc.c:tegra_mc_irq",
        "drivers/memory/tegra/mc.c:tegra_mc_irq",
        "drivers/memory/tegra/mc.c:tegra_mc_irq",
        "drivers/memory/tegra/mc.c:tegra_mc_get_emem_device_count",
        "drivers/memory/tegra/mc.c:tegra_mc_reset_status_common",
        "drivers/memory/tegra/mc.c:tegra_mc_unblock_dma_common",
        "drivers/memory/tegra/mc.c:tegra_mc_dma_idling_common",
        "drivers/memory/tegra/mc.c:tegra_mc_block_dma_common"
      ],
      "caller_func": []
    },
    {
      "addr": 3234285548,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/memory/tegra/tegra20.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/memory/tegra/tegra20.c:tegra20_mc_unblock_dma",
        "drivers/memory/tegra/tegra20.c:tegra20_mc_reset_status",
        "drivers/memory/tegra/tegra20.c:tegra20_mc_dma_idling",
        "drivers/memory/tegra/tegra20.c:tegra20_mc_block_dma",
        "drivers/memory/tegra/tegra20.c:tegra20_mc_hotreset_deassert",
        "drivers/memory/tegra/tegra20.c:tegra20_mc_hotreset_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 3234286876,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/memory/tegra/tegra20-emc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe",
        "drivers/memory/tegra/tegra20-emc.c:emc_prepare_timing_change",
        "drivers/memory/tegra/tegra20-emc.c:tegra_emc_isr"
      ],
      "caller_func": []
    },
    {
      "addr": 3234290452,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/memory/tegra/tegra124-emc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe",
        "drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe",
        "drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe",
        "drivers/memory/tegra/tegra124-emc.c:tegra_emc_complete_timing_change",
        "drivers/memory/tegra/tegra124-emc.c:tegra_emc_complete_timing_change",
        "drivers/memory/tegra/tegra124-emc.c:tegra_emc_prepare_timing_change",
        "drivers/memory/tegra/tegra124-emc.c:tegra_emc_prepare_timing_change",
        "drivers/memory/tegra/tegra124-emc.c:tegra_emc_prepare_timing_change",
        "drivers/memory/tegra/tegra124-emc.c:tegra_emc_prepare_timing_change",
        "drivers/memory/tegra/tegra124-emc.c:tegra_emc_prepare_timing_change"
      ],
      "caller_func": []
    },
    {
      "addr": 3234311704,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/perf/arm-cci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-cci.c:cci_pmu_probe",
        "drivers/perf/arm-cci.c:cci_pmu_probe",
        "drivers/perf/arm-cci.c:cci_pmu_disable",
        "drivers/perf/arm-cci.c:pmu_handle_irq",
        "drivers/perf/arm-cci.c:pmu_handle_irq",
        "drivers/perf/arm-cci.c:pmu_event_update",
        "drivers/perf/arm-cci.c:cci5xx_pmu_write_counters",
        "drivers/perf/arm-cci.c:cci5xx_pmu_write_counters",
        "drivers/perf/arm-cci.c:cci5xx_pmu_write_counters",
        "drivers/perf/arm-cci.c:__cci_pmu_enable_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 3234318584,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "drivers/perf/arm-ccn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-ccn.c:arm_ccn_probe",
        "drivers/perf/arm-ccn.c:arm_ccn_for_each_valid_region",
        "drivers/perf/arm-ccn.c:arm_ccn_for_each_valid_region",
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_overflow_handler",
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_disable",
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_enable",
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_event_start",
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_xp_dt_config",
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3234601696,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:110",
      "file": "sound/soc/fsl/imx-audmux.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "sound/soc/fsl/imx-audmux.c:imx_audmux_suspend",
        "sound/soc/fsl/imx-audmux.c:audmux_read_file",
        "sound/soc/fsl/imx-audmux.c:audmux_read_file"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__raw_readl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290451064,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/io.h:310",
      "file": "lib/iomap_copy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iomap_copy.c:__ioread32_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290870940,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/io.h:310",
      "file": "drivers/gpio/gpio-xilinx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-xilinx.c:xgpio_get"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291332416,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/io.h:310",
      "file": "drivers/video/fbdev/core/cfbimgblt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit",
        "drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit",
        "drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit",
        "drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291782668,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/powerpc/include/asm/io.h:310",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:au_serial_dl_read",
        "drivers/tty/serial/8250/8250_port.c:au_serial_in"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__raw_readl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270614324,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "arch/riscv/mm/sifive_l2_cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/sifive_l2_cache.c:sifive_l2_init",
        "arch/riscv/mm/sifive_l2_cache.c:sifive_l2_init",
        "arch/riscv/mm/sifive_l2_cache.c:l2_int_handler",
        "arch/riscv/mm/sifive_l2_cache.c:l2_int_handler",
        "arch/riscv/mm/sifive_l2_cache.c:l2_int_handler",
        "arch/riscv/mm/sifive_l2_cache.c:l2_int_handler",
        "arch/riscv/mm/sifive_l2_cache.c:l2_int_handler",
        "arch/riscv/mm/sifive_l2_cache.c:l2_int_handler",
        "arch/riscv/mm/sifive_l2_cache.c:l2_int_handler",
        "arch/riscv/mm/sifive_l2_cache.c:l2_int_handler",
        "arch/riscv/mm/sifive_l2_cache.c:l2_int_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271747946,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "kernel/irq/generic-chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:irq_gc_init_mask_cache",
        "kernel/irq/generic-chip.c:irq_readl_be"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274274596,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "fs/debugfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:debugfs_print_regs32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275231620,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "lib/iomap_copy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iomap_copy.c:__ioread32_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275403882,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/irqchip/irq-al-fic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-al-fic.c:al_fic_irq_handler",
        "drivers/irqchip/irq-al-fic.c:al_fic_irq_set_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275404438,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/irqchip/irq-sifive-plic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-sifive-plic.c:plic_handle_irq",
        "drivers/irqchip/irq-sifive-plic.c:plic_set_affinity",
        "drivers/irqchip/irq-sifive-plic.c:plic_set_affinity",
        "drivers/irqchip/irq-sifive-plic.c:plic_irq_mask",
        "drivers/irqchip/irq-sifive-plic.c:plic_irq_unmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275442092,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/pinctrl/pinctrl-amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275447076,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/pinctrl/pinctrl-single.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-single.c:pcs_readl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275502048,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_read32be",
        "drivers/gpio/gpio-mmio.c:bgpio_read32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275507238,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/gpio/gpio-ftgpio010.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_unmask_irq",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_mask_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275524454,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/pwm/pwm-sifive.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/pwm-sifive.c:pwm_sifive_get_state",
        "drivers/pwm/pwm-sifive.c:pwm_sifive_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275529052,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32",
        "drivers/pci/access.c:pci_generic_config_read32",
        "drivers/pci/access.c:pci_generic_config_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275592904,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/pci/rom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275630000,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:disable_igfx_irq",
        "drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275697282,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_isr",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_query_power_fault",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_status",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_get_latch_status",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_get_power_status",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_get_attention_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275705220,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/msi.c:__pci_read_msi_msg",
        "drivers/pci/msi.c:msi_set_mask_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275727474,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/pci/controller/pcie-cadence-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275732608,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/pci/controller/pcie-cadence-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275735708,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/pci/controller/pci-ftpci100.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_unmask_irq",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_mask_irq",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_ack_irq",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_read_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275738150,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/pci/controller/pcie-xilinx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_map_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275740174,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/pci/controller/dwc/pcie-designware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275750836,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275867430,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/video/fbdev/imsttfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/imsttfb.c:init_imstt",
        "drivers/video/fbdev/imsttfb.c:imsttfb_ioctl",
        "drivers/video/fbdev/imsttfb.c:imsttfb_ioctl",
        "drivers/video/fbdev/imsttfb.c:imsttfb_copyarea",
        "drivers/video/fbdev/imsttfb.c:imsttfb_copyarea",
        "drivers/video/fbdev/imsttfb.c:imsttfb_copyarea",
        "drivers/video/fbdev/imsttfb.c:imsttfb_fillrect",
        "drivers/video/fbdev/imsttfb.c:imsttfb_fillrect",
        "drivers/video/fbdev/imsttfb.c:imsttfb_fillrect",
        "drivers/video/fbdev/imsttfb.c:imsttfb_fillrect",
        "drivers/video/fbdev/imsttfb.c:imsttfb_fillrect",
        "drivers/video/fbdev/imsttfb.c:imsttfb_fillrect",
        "drivers/video/fbdev/imsttfb.c:imsttfb_blank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275912658,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_set_rate",
        "drivers/clk/clk-divider.c:clk_divider_set_rate",
        "drivers/clk/clk-divider.c:clk_divider_round_rate",
        "drivers/clk/clk-divider.c:clk_divider_round_rate",
        "drivers/clk/clk-divider.c:clk_divider_recalc_rate",
        "drivers/clk/clk-divider.c:clk_divider_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275917878,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/clk/clk-gate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-gate.c:clk_gate_is_enabled",
        "drivers/clk/clk-gate.c:clk_gate_is_enabled",
        "drivers/clk/clk-gate.c:clk_gate_endisable",
        "drivers/clk/clk-gate.c:clk_gate_endisable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275918368,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/clk/clk-multiplier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-multiplier.c:clk_multiplier_set_rate",
        "drivers/clk/clk-multiplier.c:clk_multiplier_set_rate",
        "drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate",
        "drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275919440,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/clk/clk-mux.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-mux.c:clk_mux_set_parent",
        "drivers/clk/clk-mux.c:clk_mux_set_parent",
        "drivers/clk/clk-mux.c:clk_mux_get_parent",
        "drivers/clk/clk-mux.c:clk_mux_get_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275922758,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/clk/clk-fractional-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-fractional-divider.c:clk_fd_set_rate",
        "drivers/clk/clk-fractional-divider.c:clk_fd_set_rate",
        "drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate",
        "drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275925866,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/clk/clk-fixed-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275927536,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/clk/clk-hsdk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate",
        "drivers/clk/clk-hsdk-pll.c:hsdk_pll_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275928894,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/clk/sifive/fu540-prci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sifive/fu540-prci.c:sifive_fu540_prci_probe",
        "drivers/clk/sifive/fu540-prci.c:sifive_fu540_prci_tlclksel_recalc_rate",
        "drivers/clk/sifive/fu540-prci.c:__prci_coreclksel_use_corepll",
        "drivers/clk/sifive/fu540-prci.c:__prci_coreclksel_use_corepll",
        "drivers/clk/sifive/fu540-prci.c:__prci_coreclksel_use_hfclk",
        "drivers/clk/sifive/fu540-prci.c:__prci_coreclksel_use_hfclk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275960164,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/virtio/virtio_mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:vm_setup_vq",
        "drivers/virtio/virtio_mmio.c:vm_setup_vq",
        "drivers/virtio/virtio_mmio.c:vm_setup_vq",
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_mmio.c:vm_interrupt",
        "drivers/virtio/virtio_mmio.c:vm_get_status",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_mmio.c:vm_get",
        "drivers/virtio/virtio_mmio.c:vm_get_features",
        "drivers/virtio/virtio_mmio.c:vm_get_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275962278,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features",
        "drivers/virtio/virtio_pci_modern.c:vp_get_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275969456,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_get_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276172708,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_in",
        "drivers/tty/serial/8250/8250_port.c:mem32_serial_in",
        "drivers/tty/serial/8250/8250_port.c:au_serial_dl_read",
        "drivers/tty/serial/8250/8250_port.c:au_serial_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276192062,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/tty/serial/8250/8250_dwlib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276197748,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_endrun_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276207534,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_in",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276226090,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/tty/serial/sifive.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sifive.c:sifive_serial_console_write",
        "drivers/tty/serial/sifive.c:sifive_serial_console_putchar",
        "drivers/tty/serial/sifive.c:early_sifive_serial_putc",
        "drivers/tty/serial/sifive.c:sifive_serial_set_termios",
        "drivers/tty/serial/sifive.c:sifive_serial_set_termios",
        "drivers/tty/serial/sifive.c:sifive_serial_irq",
        "drivers/tty/serial/sifive.c:sifive_serial_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276314512,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tcg_read32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276479912,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/base/regmap/regmap-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32le"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276860484,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_wait_register",
        "drivers/ata/libata-core.c:ata_wait_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276941470,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_data_xfer32",
        "drivers/ata/libata-sff.c:ata_sff_data_xfer32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277004296,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/spi/spi-fsl-spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_irq",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_irq",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_irq",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_setup",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277005202,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/spi/spi-sifive.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-sifive.c:sifive_spi_probe",
        "drivers/spi/spi-sifive.c:sifive_spi_probe",
        "drivers/spi/spi-sifive.c:sifive_spi_transfer_one",
        "drivers/spi/spi-sifive.c:sifive_spi_transfer_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277248064,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_phy_init",
        "drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel",
        "drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear",
        "drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set",
        "drivers/usb/dwc2/core.c:dwc2_hw_is_device",
        "drivers/usb/dwc2/core.c:dwc2_hw_is_host",
        "drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts",
        "drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts",
        "drivers/usb/dwc2/core.c:dwc2_is_controller_alive",
        "drivers/usb/dwc2/core.c:dwc2_enable_acg",
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
        "drivers/usb/dwc2/core.c:dwc2_core_reset",
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
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers",
        "drivers/usb/dwc2/core.c:dwc2_backup_global_registers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277255044,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277259620,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277263626,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277303336,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_host_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_core_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_set_even_odd_frame",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_halt",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_halt",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_halt",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_halt",
        "drivers/usb/dwc2/hcd.c:dwc2_read_packet",
        "drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval",
        "drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval",
        "drivers/usb/dwc2/hcd.c:dwc2_config_fifos",
        "drivers/usb/dwc2/hcd.c:dwc2_config_fifos",
        "drivers/usb/dwc2/hcd.c:dwc2_config_fifos",
        "drivers/usb/dwc2/hcd.c:dwc2_config_fifos",
        "drivers/usb/dwc2/hcd.c:dwc2_config_fifos",
        "drivers/usb/dwc2/hcd.c:dwc2_config_fifos",
        "drivers/usb/dwc2/hcd.c:dwc2_config_fifos",
        "drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts",
        "drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277315146,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277321128,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277326502,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277334946,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277377970,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_get_frame",
        "drivers/usb/host/ehci-hcd.c:ehci_get_frame",
        "drivers/usb/host/ehci-hcd.c:ehci_get_frame",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ehci-hcd.c:ehci_irq",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_run",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_silence_controller",
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:scan_isoc",
        "drivers/usb/host/ehci-hcd.c:iso_stream_schedule",
        "drivers/usb/host/ehci-hcd.c:iso_stream_schedule",
        "drivers/usb/host/ehci-hcd.c:iso_stream_schedule",
        "drivers/usb/host/ehci-hcd.c:ehci_port_power",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_status_data",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_status_data",
        "drivers/usb/host/ehci-hcd.c:set_owner",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_disable_PSE",
        "drivers/usb/host/ehci-hcd.c:ehci_disable_ASE",
        "drivers/usb/host/ehci-hcd.c:ehci_set_command_bit",
        "drivers/usb/host/ehci-hcd.c:ehci_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_reset",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ehci-hcd.c:fill_registers_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277387030,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/usb/host/ehci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277413634,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:_ohci_shutdown",
        "drivers/usb/host/ohci-hcd.c:start_ed_unlink",
        "drivers/usb/host/ohci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ohci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ohci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ohci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_dump_status",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_control",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277426770,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277456428,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:compliance_mode_recovery",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_reset",
        "drivers/usb/host/xhci.c:xhci_start",
        "drivers/usb/host/xhci.c:xhci_quiesce",
        "drivers/usb/host/xhci.c:xhci_quiesce",
        "drivers/usb/host/xhci.c:xhci_handshake",
        "drivers/usb/host/xhci.c:xhci_handshake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277488408,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays",
        "drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277490736,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/usb/host/xhci-ext-caps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init",
        "drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277507468,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277530094,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_link_state",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277547566,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277558514,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277559548,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277666402,
      "name": "__raw_readl",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:77",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:dw_readl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
u32 __raw_readl(volatile const void * addr)
```
</details>
</li>
</ul>
