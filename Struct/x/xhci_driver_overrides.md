# Struct: <code>xhci_driver_overrides</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
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
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
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
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct xhci_driver_overrides {
    size_t extra_priv_size;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control</code>
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
