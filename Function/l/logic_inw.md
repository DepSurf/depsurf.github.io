# Function: <code>logic_inw</code>

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
u16 logic_inw(long unsigned int addr)
```

```json
{
  "name": "logic_inw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496178264,
      "name": "logic_inw",
      "external": true,
      "loc": "lib/logic_pio.c:303",
      "file": "lib/logic_pio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_read_resource_io",
        "drivers/pci/quirks.c:quirk_tigerpoint_bm_sts",
        "drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc",
        "drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc",
        "drivers/usb/host/pci-quirks.c:uhci_reset_hc",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number",
        "drivers/usb/host/uhci-hcd.c:uhci_irq",
        "drivers/usb/host/uhci-hcd.c:wakeup_rh",
        "drivers/usb/host/uhci-hcd.c:wakeup_rh",
        "drivers/usb/host/uhci-hcd.c:suspend_rh",
        "drivers/usb/host/uhci-hcd.c:suspend_rh",
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
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule",
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule",
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule",
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule",
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule",
        "drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496178264,
      "name": "logic_inw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
u16 logic_inw(long unsigned int addr)
```
</details>
</li>
</ul>
