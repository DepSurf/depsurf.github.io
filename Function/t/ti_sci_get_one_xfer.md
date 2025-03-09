# Function: <code>ti_sci_get_one_xfer</code>

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
struct ti_sci_xfer * ti_sci_get_one_xfer(struct ti_sci_info * info, u16 msg_type, u32 msg_flags, size_t tx_message_size, size_t rx_message_size)
```

```json
{
  "name": "ti_sci_get_one_xfer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501497328,
      "name": "ti_sci_get_one_xfer",
      "external": false,
      "loc": "drivers/firmware/ti_sci.c:320",
      "file": "drivers/firmware/ti_sci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/ti_sci.c:ti_sci_probe",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_proc_get_status",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_proc_set_control",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_proc_set_config",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_proc_handover",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_proc_release",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_proc_request",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_rx_flow_cfg",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_rx_ch_cfg",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_tx_ch_cfg",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_rm_psil_unpair",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_rm_psil_pair",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_ring_get_config",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_ring_config",
        "drivers/firmware/ti_sci.c:ti_sci_get_resource_range",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_core_reboot",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_freq",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_clk_set_freq",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_match_freq",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_num_parents",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_parent",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_clk_set_parent",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_get_clock_state",
        "drivers/firmware/ti_sci.c:ti_sci_set_clock_state",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_set_device_resets",
        "drivers/firmware/ti_sci.c:ti_sci_get_device_state",
        "drivers/firmware/ti_sci.c:ti_sci_set_device_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501497328,
      "name": "ti_sci_get_one_xfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
struct ti_sci_xfer * ti_sci_get_one_xfer(struct ti_sci_info * info, u16 msg_type, u32 msg_flags, size_t tx_message_size, size_t rx_message_size)
```
</details>
</li>
</ul>
