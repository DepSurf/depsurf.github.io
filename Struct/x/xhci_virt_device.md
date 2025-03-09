# Struct: <code>xhci_virt_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_device {
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_ring * * ring_cache;
    int num_rings_cached;
    struct xhci_virt_ep[31] eps;
    struct completion cmd_completion;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    u16 current_mel;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_device {
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_ring * * ring_cache;
    int num_rings_cached;
    struct xhci_virt_ep[31] eps;
    struct completion cmd_completion;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    u16 current_mel;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_device {
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_ring * * ring_cache;
    int num_rings_cached;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    u16 current_mel;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_device {
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    u16 current_mel;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_device {
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    u16 current_mel;
    void * debugfs_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_device {
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    u16 current_mel;
    void * debugfs_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_device {
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    u16 current_mel;
    void * debugfs_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_device {
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    long unsigned int flags;
    u16 current_mel;
    void * debugfs_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_device {
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    long unsigned int flags;
    u16 current_mel;
    void * debugfs_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_device {
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    long unsigned int flags;
    u16 current_mel;
    void * debugfs_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_device {
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    long unsigned int flags;
    u16 current_mel;
    void * debugfs_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_device {
    int slot_id;
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    long unsigned int flags;
    u16 current_mel;
    void * debugfs_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_device {
    int slot_id;
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    long unsigned int flags;
    u16 current_mel;
    void * debugfs_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_device {
    int slot_id;
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    long unsigned int flags;
    u16 current_mel;
    void * debugfs_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_device {
    int slot_id;
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    long unsigned int flags;
    u16 current_mel;
    void * debugfs_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_device {
    int slot_id;
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    long unsigned int flags;
    u16 current_mel;
    void * debugfs_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_device {
    int slot_id;
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    long unsigned int flags;
    u16 current_mel;
    void * debugfs_private;
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
struct xhci_virt_device {
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    long unsigned int flags;
    u16 current_mel;
    void * debugfs_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct xhci_virt_device {
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    long unsigned int flags;
    u16 current_mel;
    void * debugfs_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct xhci_virt_device {
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    long unsigned int flags;
    u16 current_mel;
    void * debugfs_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct xhci_virt_device {
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    long unsigned int flags;
    u16 current_mel;
    void * debugfs_private;
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
struct xhci_virt_device {
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    long unsigned int flags;
    u16 current_mel;
    void * debugfs_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct xhci_virt_device {
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    long unsigned int flags;
    u16 current_mel;
    void * debugfs_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct xhci_virt_device {
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    long unsigned int flags;
    u16 current_mel;
    void * debugfs_private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct xhci_virt_device {
    struct usb_device * udev;
    struct xhci_container_ctx * out_ctx;
    struct xhci_container_ctx * in_ctx;
    struct xhci_virt_ep[31] eps;
    u8 fake_port;
    u8 real_port;
    struct xhci_interval_bw_table * bw_table;
    struct xhci_tt_bw_info * tt_info;
    long unsigned int flags;
    u16 current_mel;
    void * debugfs_private;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct completion cmd_completion</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct xhci_ring * * ring_cache</code>
</li>
<li>
<b>Field removed. </b>
<code>int num_rings_cached</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * debugfs_private</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int slot_id</code>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
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
