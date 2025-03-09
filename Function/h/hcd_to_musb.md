# Function: <code>hcd_to_musb</code>

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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct musb * hcd_to_musb(struct usb_hcd * hcd)
```

```json
{
  "name": "hcd_to_musb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233195744,
      "name": "hcd_to_musb",
      "external": true,
      "loc": "drivers/usb/musb/musb_host.c:73",
      "file": "drivers/usb/musb/musb_host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/musb/musb_host.c:musb_bus_resume",
        "drivers/usb/musb/musb_host.c:musb_bus_suspend",
        "drivers/usb/musb/musb_host.c:musb_h_stop",
        "drivers/usb/musb/musb_host.c:musb_h_start",
        "drivers/usb/musb/musb_host.c:musb_h_get_frame_number",
        "drivers/usb/musb/musb_host.c:musb_h_disable",
        "drivers/usb/musb/musb_host.c:musb_urb_dequeue",
        "drivers/usb/musb/musb_host.c:musb_urb_enqueue"
      ],
      "caller_func": [
        "drivers/usb/musb/musb_virthub.c:musb_hub_control",
        "drivers/usb/musb/musb_virthub.c:musb_hub_status_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233202320,
      "name": "hcd_to_musb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct musb * hcd_to_musb(struct usb_hcd * hcd)
```
</details>
</li>
</ul>
