# Struct: <code>uhci_qh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
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
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
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
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct uhci_qh {
    __le32 link;
    __le32 element;
    dma_addr_t dma_handle;
    struct list_head node;
    struct usb_host_endpoint * hep;
    struct usb_device * udev;
    struct list_head queue;
    struct uhci_td * dummy_td;
    struct uhci_td * post_td;
    struct usb_iso_packet_descriptor * iso_packet_desc;
    long unsigned int advance_jiffies;
    unsigned int unlink_frame;
    unsigned int period;
    short int phase;
    short int load;
    unsigned int iso_frame;
    int state;
    int type;
    int skel;
    unsigned int initial_toggle;
    unsigned int needs_fixup;
    unsigned int is_stopped;
    unsigned int wait_expired;
    unsigned int bandwidth_reserved;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
