# Function: <code>__raw_readq</code>

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
u64 __raw_readq(const volatile void * addr)
```

```json
{
  "name": "__raw_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490245480,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:83",
      "file": "arch/arm64/kernel/io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/io.c:__memcpy_fromio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490325932,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:83",
      "file": "arch/arm64/kernel/acpi_parking_protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496374312,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:83",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3.c:__gic_update_rdist_properties",
        "drivers/irqchip/irq-gic-v3.c:__gic_populate_rdist",
        "drivers/irqchip/irq-gic-v3.c:gic_iterate_rdists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496401092,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:83",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_restore_enable",
        "drivers/irqchip/irq-gic-v3-its.c:its_restore_enable",
        "drivers/irqchip/irq-gic-v3-its.c:its_save_disable",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_irqchip_state",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_send_inv",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection",
        "drivers/irqchip/irq-gic-v3-its.c:its_clear_vpend_valid",
        "drivers/irqchip/irq-gic-v3-its.c:its_clear_vpend_valid"
      ],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3-its.c:its_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_probe_one",
        "drivers/irqchip/irq-gic-v3-its.c:its_probe_one",
        "drivers/irqchip/irq-gic-v3-its.c:its_probe_one",
        "drivers/irqchip/irq-gic-v3-its.c:its_probe_one",
        "drivers/irqchip/irq-gic-v3-its.c:its_probe_one",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_parse_indirect_baser",
        "drivers/irqchip/irq-gic-v3-its.c:its_parse_indirect_baser"
      ]
    },
    {
      "addr": 18446603336496440360,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:83",
      "file": "drivers/irqchip/irq-ti-sci-inta.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496452516,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:83",
      "file": "drivers/bus/fsl-mc/mc-sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/fsl-mc/mc-sys.c:mc_send_command",
        "drivers/bus/fsl-mc/mc-sys.c:mc_send_command",
        "drivers/bus/fsl-mc/mc-sys.c:mc_send_command",
        "drivers/bus/fsl-mc/mc-sys.c:mc_send_command"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496759464,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:83",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_read64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497206172,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:83",
      "file": "drivers/pci/controller/pci-thunder-pem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-thunder-pem.c:thunder_pem_config_write",
        "drivers/pci/controller/pci-thunder-pem.c:thunder_pem_config_write",
        "drivers/pci/controller/pci-thunder-pem.c:thunder_pem_config_read",
        "drivers/pci/controller/pci-thunder-pem.c:thunder_pem_config_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497331640,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:83",
      "file": "drivers/video/fbdev/core/cfbfillrect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497333496,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:83",
      "file": "drivers/video/fbdev/core/cfbcopyarea.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497380092,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:83",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497666624,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:83",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:cpc_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498614104,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:83",
      "file": "drivers/tty/serial/8250/8250_dw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dw.c:dw8250_serial_outq",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_serial_inq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498878868,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:83",
      "file": "drivers/iommu/arm-smmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard",
        "drivers/iommu/arm-smmu.c:arm_smmu_context_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498917756,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:83",
      "file": "drivers/iommu/qcom_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/qcom_iommu.c:qcom_iommu_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499184940,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:83",
      "file": "drivers/base/regmap/regmap-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501526348,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:83",
      "file": "drivers/firmware/arm_scmi/perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501671612,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:83",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:read_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501768264,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:83",
      "file": "drivers/perf/arm-ccn.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501783992,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:83",
      "file": "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501786128,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/arm64/include/asm/io.h:83",
      "file": "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_read_counter"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496381400,
      "name": "__raw_readq",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__raw_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291327564,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/powerpc/include/asm/io.h:328",
      "file": "drivers/video/fbdev/core/cfbfillrect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291329492,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/powerpc/include/asm/io.h:328",
      "file": "drivers/video/fbdev/core/cfbcopyarea.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea",
        "drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea"
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
  "name": "__raw_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275501952,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:87",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_read64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276480004,
      "name": "__raw_readq",
      "external": false,
      "loc": "arch/riscv/include/asm/io.h:87",
      "file": "drivers/base/regmap/regmap-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le"
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
u64 __raw_readq(const volatile void * addr)
```
</details>
</li>
</ul>
