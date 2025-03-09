# Function: <code>usb_port_is_power_on</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int usb_port_is_power_on(struct usb_hub * hub, unsigned int portstatus)
```

```json
{
  "name": "usb_port_is_power_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591533989,
      "name": "usb_port_is_power_on",
      "external": true,
      "loc": "drivers/usb/core/hub.c:3129",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:check_port_resume_type"
      ],
      "caller_func": [
        "drivers/usb/core/port.c:disable_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591530416,
      "name": "usb_port_is_power_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int usb_port_is_power_on(struct usb_hub * hub, unsigned int portstatus)
```

```json
{
  "name": "usb_port_is_power_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591955909,
      "name": "usb_port_is_power_on",
      "external": true,
      "loc": "drivers/usb/core/hub.c:3149",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:check_port_resume_type"
      ],
      "caller_func": [
        "drivers/usb/core/port.c:disable_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591952320,
      "name": "usb_port_is_power_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int usb_port_is_power_on(struct usb_hub * hub, unsigned int portstatus)
```

```json
{
  "name": "usb_port_is_power_on",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592695695,
      "name": "usb_port_is_power_on",
      "external": true,
      "loc": "drivers/usb/core/hub.c:3151",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:check_port_resume_type"
      ],
      "caller_func": [
        "drivers/usb/core/port.c:disable_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592692112,
      "name": "usb_port_is_power_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int usb_port_is_power_on(struct usb_hub * hub, unsigned int portstatus)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
