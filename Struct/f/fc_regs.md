# Struct: <code>fc_regs</code>

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
struct fc_regs {
    u32 USB_CONTROL;
    u32 USB_STATUS;
    u32 USB_ADDRESS;
    u32 UTMI_CHARACTER_1;
    u32 TEST_CONTROL;
    u32 reserved_14;
    u32 SETUP_DATA0;
    u32 SETUP_DATA1;
    u32 USB_INT_STA;
    u32 USB_INT_ENA;
    u32 EP0_CONTROL;
    u32 EP0_STATUS;
    u32 EP0_INT_ENA;
    u32 EP0_LENGTH;
    u32 EP0_READ;
    u32 EP0_WRITE;
    struct ep_regs[15] EP_REGS;
    u8[3552] reserved_220;
    u32 AHBSCTR;
    u32 AHBMCTR;
    u32 AHBBINT;
    u32 AHBBINTEN;
    u32 EPCTR;
    u32 USBF_EPTEST;
    u8[8] reserved_1018;
    u32 USBSSVER;
    u32 USBSSCONF;
    u8[232] reserved_1028;
    struct ep_dcr[15] EP_DCR;
    u8[3584] reserved_1200;
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
struct fc_regs {
    u32 USB_CONTROL;
    u32 USB_STATUS;
    u32 USB_ADDRESS;
    u32 UTMI_CHARACTER_1;
    u32 TEST_CONTROL;
    u32 reserved_14;
    u32 SETUP_DATA0;
    u32 SETUP_DATA1;
    u32 USB_INT_STA;
    u32 USB_INT_ENA;
    u32 EP0_CONTROL;
    u32 EP0_STATUS;
    u32 EP0_INT_ENA;
    u32 EP0_LENGTH;
    u32 EP0_READ;
    u32 EP0_WRITE;
    struct ep_regs[15] EP_REGS;
    u8[3552] reserved_220;
    u32 AHBSCTR;
    u32 AHBMCTR;
    u32 AHBBINT;
    u32 AHBBINTEN;
    u32 EPCTR;
    u32 USBF_EPTEST;
    u8[8] reserved_1018;
    u32 USBSSVER;
    u32 USBSSCONF;
    u8[232] reserved_1028;
    struct ep_dcr[15] EP_DCR;
    u8[3584] reserved_1200;
}
```
</details>
</li>
</ul>
