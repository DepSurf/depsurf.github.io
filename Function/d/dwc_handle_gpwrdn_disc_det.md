# Function: <code>dwc_handle_gpwrdn_disc_det</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void dwc_handle_gpwrdn_disc_det(struct dwc2_hsotg * hsotg, u32 gpwrdn)
```

```json
{
  "name": "dwc_handle_gpwrdn_disc_det",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588032976,
      "name": "dwc_handle_gpwrdn_disc_det",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:689",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588032976,
      "name": "dwc_handle_gpwrdn_disc_det",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dwc_handle_gpwrdn_disc_det(struct dwc2_hsotg * hsotg, u32 gpwrdn)
```

```json
{
  "name": "dwc_handle_gpwrdn_disc_det",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588652760,
      "name": "dwc_handle_gpwrdn_disc_det",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:689",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588652080,
      "name": "dwc_handle_gpwrdn_disc_det",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
    },
    {
      "addr": 18446744071592577687,
      "name": "dwc_handle_gpwrdn_disc_det.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dwc_handle_gpwrdn_disc_det(struct dwc2_hsotg * hsotg, u32 gpwrdn)
```

```json
{
  "name": "dwc_handle_gpwrdn_disc_det",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590069473,
      "name": "dwc_handle_gpwrdn_disc_det",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:689",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590068976,
      "name": "dwc_handle_gpwrdn_disc_det",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 650
    },
    {
      "addr": 18446744071594457960,
      "name": "dwc_handle_gpwrdn_disc_det.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dwc_handle_gpwrdn_disc_det(struct dwc2_hsotg * hsotg, u32 gpwrdn)
```

```json
{
  "name": "dwc_handle_gpwrdn_disc_det",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591677169,
      "name": "dwc_handle_gpwrdn_disc_det",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:659",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591676672,
      "name": "dwc_handle_gpwrdn_disc_det",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 650
    },
    {
      "addr": 18446744071596276856,
      "name": "dwc_handle_gpwrdn_disc_det.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dwc_handle_gpwrdn_disc_det(struct dwc2_hsotg * hsotg, u32 gpwrdn)
```

```json
{
  "name": "dwc_handle_gpwrdn_disc_det",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592100081,
      "name": "dwc_handle_gpwrdn_disc_det",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:659",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592099584,
      "name": "dwc_handle_gpwrdn_disc_det",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 650
    },
    {
      "addr": 18446744071596806702,
      "name": "dwc_handle_gpwrdn_disc_det.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dwc_handle_gpwrdn_disc_det(struct dwc2_hsotg * hsotg, u32 gpwrdn)
```

```json
{
  "name": "dwc_handle_gpwrdn_disc_det",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592840513,
      "name": "dwc_handle_gpwrdn_disc_det",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:659",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592840016,
      "name": "dwc_handle_gpwrdn_disc_det",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 650
    },
    {
      "addr": 18446744071597730309,
      "name": "dwc_handle_gpwrdn_disc_det.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void dwc_handle_gpwrdn_disc_det(struct dwc2_hsotg * hsotg, u32 gpwrdn)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
