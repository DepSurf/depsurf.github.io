# Function: <code>musb_dbg</code>

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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void musb_dbg(struct musb * musb, const char * fmt, void (anon))
```

```json
{
  "name": "musb_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233190044,
      "name": "musb_dbg",
      "external": true,
      "loc": "drivers/usb/musb/musb_trace.c:13",
      "file": "drivers/usb/musb/musb_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/musb/musb_core.c:musb_irq_work",
        "drivers/usb/musb/musb_core.c:musb_irq_work",
        "drivers/usb/musb/musb_core.c:musb_irq_work",
        "drivers/usb/musb/musb_core.c:musb_irq_work",
        "drivers/usb/musb/musb_core.c:musb_irq_work",
        "drivers/usb/musb/musb_core.c:musb_core_init",
        "drivers/usb/musb/musb_core.c:musb_core_init",
        "drivers/usb/musb/musb_core.c:musb_core_init",
        "drivers/usb/musb/musb_core.c:ep_config_from_hw",
        "drivers/usb/musb/musb_core.c:musb_start",
        "drivers/usb/musb/musb_core.c:musb_stage0_irq",
        "drivers/usb/musb/musb_core.c:musb_stage0_irq",
        "drivers/usb/musb/musb_core.c:musb_stage0_irq",
        "drivers/usb/musb/musb_core.c:musb_stage0_irq",
        "drivers/usb/musb/musb_core.c:musb_stage0_irq",
        "drivers/usb/musb/musb_core.c:musb_stage0_irq",
        "drivers/usb/musb/musb_core.c:musb_stage0_irq",
        "drivers/usb/musb/musb_core.c:musb_stage0_irq",
        "drivers/usb/musb/musb_core.c:musb_stage0_irq",
        "drivers/usb/musb/musb_core.c:musb_stage0_irq",
        "drivers/usb/musb/musb_core.c:musb_stage0_irq",
        "drivers/usb/musb/musb_core.c:musb_stage0_irq",
        "drivers/usb/musb/musb_core.c:musb_stage0_irq",
        "drivers/usb/musb/musb_core.c:musb_stage0_irq",
        "drivers/usb/musb/musb_core.c:musb_stage0_irq",
        "drivers/usb/musb/musb_core.c:musb_stage0_irq",
        "drivers/usb/musb/musb_core.c:musb_hnp_stop",
        "drivers/usb/musb/musb_core.c:musb_hnp_stop",
        "drivers/usb/musb/musb_core.c:musb_hnp_stop",
        "drivers/usb/musb/musb_core.c:musb_hnp_stop",
        "drivers/usb/musb/musb_core.c:musb_otg_timer_func",
        "drivers/usb/musb/musb_core.c:musb_otg_timer_func",
        "drivers/usb/musb/musb_core.c:musb_otg_timer_func",
        "drivers/usb/musb/musb_virthub.c:musb_hub_control",
        "drivers/usb/musb/musb_virthub.c:musb_hub_control",
        "drivers/usb/musb/musb_virthub.c:musb_hub_control",
        "drivers/usb/musb/musb_virthub.c:musb_hub_control",
        "drivers/usb/musb/musb_virthub.c:musb_root_disconnect",
        "drivers/usb/musb/musb_virthub.c:musb_port_reset",
        "drivers/usb/musb/musb_virthub.c:musb_port_reset",
        "drivers/usb/musb/musb_virthub.c:musb_port_reset",
        "drivers/usb/musb/musb_virthub.c:musb_port_suspend",
        "drivers/usb/musb/musb_virthub.c:musb_port_suspend",
        "drivers/usb/musb/musb_virthub.c:musb_port_suspend",
        "drivers/usb/musb/musb_virthub.c:musb_host_finish_resume",
        "drivers/usb/musb/musb_host.c:musb_urb_enqueue",
        "drivers/usb/musb/musb_host.c:musb_host_rx",
        "drivers/usb/musb/musb_host.c:musb_host_rx",
        "drivers/usb/musb/musb_host.c:musb_host_rx",
        "drivers/usb/musb/musb_host.c:musb_host_rx",
        "drivers/usb/musb/musb_host.c:musb_host_rx",
        "drivers/usb/musb/musb_host.c:musb_host_rx",
        "drivers/usb/musb/musb_host.c:musb_host_rx",
        "drivers/usb/musb/musb_host.c:musb_host_rx",
        "drivers/usb/musb/musb_host.c:musb_host_rx",
        "drivers/usb/musb/musb_host.c:musb_host_tx",
        "drivers/usb/musb/musb_host.c:musb_host_tx",
        "drivers/usb/musb/musb_host.c:musb_host_tx",
        "drivers/usb/musb/musb_host.c:musb_host_tx",
        "drivers/usb/musb/musb_host.c:musb_host_tx",
        "drivers/usb/musb/musb_host.c:musb_host_tx",
        "drivers/usb/musb/musb_host.c:musb_h_ep0_irq",
        "drivers/usb/musb/musb_host.c:musb_h_ep0_irq",
        "drivers/usb/musb/musb_host.c:musb_h_ep0_irq",
        "drivers/usb/musb/musb_host.c:musb_h_ep0_irq",
        "drivers/usb/musb/musb_host.c:musb_h_ep0_irq",
        "drivers/usb/musb/musb_host.c:musb_h_ep0_irq",
        "drivers/usb/musb/musb_host.c:musb_h_ep0_irq",
        "drivers/usb/musb/musb_host.c:musb_h_ep0_irq",
        "drivers/usb/musb/musb_host.c:musb_h_ep0_irq",
        "drivers/usb/musb/musb_host.c:musb_h_ep0_irq",
        "drivers/usb/musb/musb_host.c:musb_host_packet_rx",
        "drivers/usb/musb/musb_host.c:musb_host_packet_rx",
        "drivers/usb/musb/musb_host.c:musb_host_packet_rx",
        "drivers/usb/musb/musb_host.c:musb_advance_schedule",
        "drivers/usb/musb/musb_host.c:musb_start_urb",
        "drivers/usb/musb/musb_host.c:musb_start_urb",
        "drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_halt",
        "drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_queue",
        "drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_queue",
        "drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_irq",
        "drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_irq",
        "drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_irq",
        "drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_irq",
        "drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_irq",
        "drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_irq",
        "drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_irq",
        "drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_irq",
        "drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_irq",
        "drivers/usb/musb/musb_gadget_ep0.c:ep0_txstate",
        "drivers/usb/musb/musb_gadget_ep0.c:service_zero_data_request",
        "drivers/usb/musb/musb_gadget_ep0.c:service_zero_data_request",
        "drivers/usb/musb/musb_gadget.c:musb_g_reset",
        "drivers/usb/musb/musb_gadget.c:musb_g_disconnect",
        "drivers/usb/musb/musb_gadget.c:musb_g_disconnect",
        "drivers/usb/musb/musb_gadget.c:musb_g_suspend",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_work",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_wakeup",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_wakeup",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_wakeup",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_set_halt",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_set_halt",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_set_halt",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_set_halt",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_set_halt",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_set_halt",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_set_halt",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_queue",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_disable",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_enable",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_enable",
        "drivers/usb/musb/musb_gadget.c:musb_g_rx",
        "drivers/usb/musb/musb_gadget.c:musb_g_rx",
        "drivers/usb/musb/musb_gadget.c:musb_g_rx",
        "drivers/usb/musb/musb_gadget.c:rxstate",
        "drivers/usb/musb/musb_gadget.c:rxstate",
        "drivers/usb/musb/musb_gadget.c:musb_g_tx",
        "drivers/usb/musb/musb_gadget.c:musb_g_tx",
        "drivers/usb/musb/musb_gadget.c:txstate",
        "drivers/usb/musb/musb_gadget.c:txstate",
        "drivers/usb/musb/musb_gadget.c:txstate",
        "drivers/usb/musb/musb_gadget.c:txstate",
        "drivers/usb/musb/musb_gadget.c:txstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233190044,
      "name": "musb_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void musb_dbg(struct musb * musb, const char * fmt, void (anon))
```
</details>
</li>
</ul>
