# Function: <code>zynqmp_pm_invoke_fn</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int zynqmp_pm_invoke_fn(u32 pm_api_id, u32 arg0, u32 arg1, u32 arg2, u32 arg3, u32 * ret_payload)
```

```json
{
  "name": "zynqmp_pm_invoke_fn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501574472,
      "name": "zynqmp_pm_invoke_fn",
      "external": true,
      "loc": "drivers/firmware/xilinx/zynqmp.c:154",
      "file": "drivers/firmware/xilinx/zynqmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_firmware_probe",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_set_requirement",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_release_node",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_request_node",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_set_suspend_mode",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_init_finalize",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_fpga_get_status",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_fpga_load",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_reset_get_status",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_reset_assert",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_clock_getparent",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_clock_setparent",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_clock_getrate",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_clock_setrate",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_clock_getdivider",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_clock_setdivider",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_clock_getstate",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_clock_disable",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_clock_enable",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_query_data",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_pm_get_chipid"
      ],
      "caller_func": [
        "drivers/soc/xilinx/zynqmp_power.c:zynqmp_pm_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501574656,
      "name": "zynqmp_pm_invoke_fn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int zynqmp_pm_invoke_fn(u32 pm_api_id, u32 arg0, u32 arg1, u32 arg2, u32 arg3, u32 * ret_payload)
```
</details>
</li>
</ul>
