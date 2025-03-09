# Function: <code>xhci_dbc_tty_probe</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int xhci_dbc_tty_probe(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_dbc_tty_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588444368,
      "name": "xhci_dbc_tty_probe",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgtty.c:473",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588444368,
      "name": "xhci_dbc_tty_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int xhci_dbc_tty_probe(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_dbc_tty_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_dbc_tty_probe",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgtty.c:473",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591512812,
      "name": "xhci_dbc_tty_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071588327072,
      "name": "xhci_dbc_tty_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int xhci_dbc_tty_probe(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_dbc_tty_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_dbc_tty_probe",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgtty.c:471",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592615943,
      "name": "xhci_dbc_tty_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071588984752,
      "name": "xhci_dbc_tty_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int xhci_dbc_tty_probe(struct device * dev, void * base, struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_dbc_tty_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590419312,
      "name": "xhci_dbc_tty_probe",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgtty.c:493",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_create_dbc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590419312,
      "name": "xhci_dbc_tty_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int xhci_dbc_tty_probe(struct device * dev, void * base, struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_dbc_tty_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592057168,
      "name": "xhci_dbc_tty_probe",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgtty.c:493",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_create_dbc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592057168,
      "name": "xhci_dbc_tty_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int xhci_dbc_tty_probe(struct device * dev, void * base, struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_dbc_tty_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592480000,
      "name": "xhci_dbc_tty_probe",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgtty.c:493",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_create_dbc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592480000,
      "name": "xhci_dbc_tty_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int xhci_dbc_tty_probe(struct device * dev, void * base, struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_dbc_tty_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593224192,
      "name": "xhci_dbc_tty_probe",
      "external": true,
      "loc": "drivers/usb/host/xhci-dbgtty.c:492",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_create_dbc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593224192,
      "name": "xhci_dbc_tty_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int xhci_dbc_tty_probe(struct xhci_hcd * xhci)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param added. </b>
<code>void * base</code>
</li>
<li>
<b>Param reordered. </b>
<code>xhci</code> ➡️ <code>dev, base, xhci</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
