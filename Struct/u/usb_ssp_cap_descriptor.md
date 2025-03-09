# Struct: <code>usb_ssp_cap_descriptor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __u16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32 legacy_padding;
    struct (anon) __empty_bmSublinkSpeedAttr;
    __le32[0] bmSublinkSpeedAttr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32 legacy_padding;
    struct (anon) __empty_bmSublinkSpeedAttr;
    __le32[0] bmSublinkSpeedAttr;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct usb_ssp_cap_descriptor {
    __u8 bLength;
    __u8 bDescriptorType;
    __u8 bDevCapabilityType;
    __u8 bReserved;
    __le32 bmAttributes;
    __le16 wFunctionalitySupport;
    __le16 wReserved;
    __le32[1] bmSublinkSpeedAttr;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>__u16 wFunctionalitySupport</code> ➡️ <code>__le16 wFunctionalitySupport</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__le32 legacy_padding</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) __empty_bmSublinkSpeedAttr</code>
</li>
<li>
<b>Field type changed. </b>
<code>__le32[1] bmSublinkSpeedAttr</code> ➡️ <code>__le32[0] bmSublinkSpeedAttr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
