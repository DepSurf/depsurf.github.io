# Function: <code>ndelay</code>

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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ndelay",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224670132,
      "name": "ndelay",
      "external": false,
      "loc": "include/linux/delay.h:49",
      "file": "arch/arm/mach-qcom/platsmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-qcom/platsmp.c:kpssv1_release_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 3230678468,
      "name": "ndelay",
      "external": false,
      "loc": "include/linux/delay.h:49",
      "file": "drivers/clk/mvebu/dove-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mvebu/dove-divider.c:dove_set_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 3231291068,
      "name": "ndelay",
      "external": false,
      "loc": "include/linux/delay.h:49",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_get_mctrl",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_port_read",
        "drivers/tty/serial/sccnxp.c:sccnxp_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3232237564,
      "name": "ndelay",
      "external": false,
      "loc": "include/linux/delay.h:49",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_dev_select"
      ],
      "caller_func": []
    },
    {
      "addr": 3232367868,
      "name": "ndelay",
      "external": false,
      "loc": "include/linux/delay.h:49",
      "file": "drivers/mtd/nand/raw/nand_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mtd/nand/raw/nand_base.c:nand_soft_waitrdy"
      ],
      "caller_func": []
    },
    {
      "addr": 3232381396,
      "name": "ndelay",
      "external": false,
      "loc": "include/linux/delay.h:49",
      "file": "drivers/mtd/nand/raw/nand_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mtd/nand/raw/nand_legacy.c:nand_command_lp",
        "drivers/mtd/nand/raw/nand_legacy.c:nand_command"
      ],
      "caller_func": []
    },
    {
      "addr": 3232433652,
      "name": "ndelay",
      "external": false,
      "loc": "include/linux/delay.h:49",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232454920,
      "name": "ndelay",
      "external": false,
      "loc": "include/linux/delay.h:49",
      "file": "drivers/spi/spi-fsl-spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 3232816424,
      "name": "ndelay",
      "external": false,
      "loc": "include/linux/delay.h:49",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down",
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down"
      ],
      "caller_func": []
    },
    {
      "addr": 3233361008,
      "name": "ndelay",
      "external": false,
      "loc": "include/linux/delay.h:49",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery"
      ],
      "caller_func": []
    },
    {
      "addr": 3233410476,
      "name": "ndelay",
      "external": false,
      "loc": "include/linux/delay.h:49",
      "file": "drivers/i2c/busses/i2c-s3c2410.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-s3c2410.c:i2c_s3c_irq_nextbyte",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_message_start"
      ],
      "caller_func": []
    },
    {
      "addr": 3233939756,
      "name": "ndelay",
      "external": false,
      "loc": "include/linux/delay.h:49",
      "file": "drivers/mmc/host/mmci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/mmci.c:mmci_runtime_resume",
        "drivers/mmc/host/mmci.c:mmci_runtime_suspend",
        "drivers/mmc/host/mmci.c:mmci_set_ios"
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
  "name": "ndelay",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291848288,
      "name": "ndelay",
      "external": false,
      "loc": "include/linux/delay.h:49",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_write",
        "drivers/tty/serial/sccnxp.c:sccnxp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293145036,
      "name": "ndelay",
      "external": false,
      "loc": "include/linux/delay.h:49",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_dev_select"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293202128,
      "name": "ndelay",
      "external": false,
      "loc": "include/linux/delay.h:49",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055293233632,
      "name": "ndelay",
      "external": false,
      "loc": "include/linux/delay.h:49",
      "file": "drivers/spi/spi-fsl-spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293666668,
      "name": "ndelay",
      "external": false,
      "loc": "include/linux/delay.h:49",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down",
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294293532,
      "name": "ndelay",
      "external": false,
      "loc": "include/linux/delay.h:49",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void ndelay(long unsigned int nsecs)
```

```json
{
  "name": "ndelay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279788586,
      "name": "ndelay",
      "external": true,
      "loc": "arch/riscv/lib/delay.c:98",
      "file": "arch/riscv/lib/delay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_get_mctrl",
        "drivers/tty/serial/sccnxp.c:sccnxp_handle_events",
        "drivers/tty/serial/sccnxp.c:sccnxp_port_read",
        "drivers/tty/serial/sccnxp.c:sccnxp_write",
        "drivers/ata/libata-sff.c:ata_sff_exec_command",
        "drivers/ata/libata-sff.c:ata_sff_dev_select",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down",
        "drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279788586,
      "name": "ndelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void ndelay(long unsigned int nsecs)
```
</details>
</li>
</ul>
