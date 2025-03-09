# Struct: <code>urb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    int unlinked;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    int unlinked;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    int unlinked;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    int unlinked;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    int unlinked;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    int unlinked;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    int unlinked;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    int unlinked;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    int unlinked;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    int unlinked;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    int unlinked;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    int unlinked;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    int unlinked;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    int unlinked;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    int unlinked;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    int unlinked;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    int unlinked;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
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
struct urb {
    struct kref kref;
    int unlinked;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    int unlinked;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    int unlinked;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    int unlinked;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
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
struct urb {
    struct kref kref;
    int unlinked;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    int unlinked;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    int unlinked;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct urb {
    struct kref kref;
    int unlinked;
    void * hcpriv;
    atomic_t use_count;
    atomic_t reject;
    struct list_head urb_list;
    struct list_head anchor_list;
    struct usb_anchor * anchor;
    struct usb_device * dev;
    struct usb_host_endpoint * ep;
    unsigned int pipe;
    unsigned int stream_id;
    int status;
    unsigned int transfer_flags;
    void * transfer_buffer;
    dma_addr_t transfer_dma;
    struct scatterlist * sg;
    int num_mapped_sgs;
    int num_sgs;
    u32 transfer_buffer_length;
    u32 actual_length;
    unsigned char * setup_packet;
    dma_addr_t setup_dma;
    int start_frame;
    int number_of_packets;
    int interval;
    int error_count;
    void * context;
    usb_complete_t complete;
    struct usb_iso_packet_descriptor[0] iso_frame_desc;
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
