# Struct: <code>dwc2_host_chan</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    dma_addr_t align_buf;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    dma_addr_t align_buf;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    dma_addr_t align_buf;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    dma_addr_t align_buf;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    dma_addr_t align_buf;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    dma_addr_t align_buf;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    dma_addr_t align_buf;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    dma_addr_t align_buf;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    dma_addr_t align_buf;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    dma_addr_t align_buf;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    dma_addr_t align_buf;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    dma_addr_t align_buf;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    dma_addr_t align_buf;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
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
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    dma_addr_t align_buf;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    dma_addr_t align_buf;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    dma_addr_t align_buf;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    dma_addr_t align_buf;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
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
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    dma_addr_t align_buf;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
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
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    dma_addr_t align_buf;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    dma_addr_t align_buf;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
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
<b>Field added. </b>
<code>u32 desc_list_sz</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head split_order_list_entry</code>
</li>
<li>
<b>Field removed. </b>
<code>dma_addr_t align_buf</code>
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>dma_addr_t align_buf</code>
</li>
</ul>
</details>
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
struct dwc2_host_chan {
    u8 hc_num;
    unsigned int dev_addr;
    unsigned int ep_num;
    unsigned int ep_is_in;
    unsigned int speed;
    unsigned int ep_type;
    unsigned int max_packet;
    unsigned int data_pid_start;
    unsigned int multi_count;
    u8 * xfer_buf;
    dma_addr_t xfer_dma;
    dma_addr_t align_buf;
    u32 xfer_len;
    u32 xfer_count;
    u16 start_pkt_count;
    u8 xfer_started;
    u8 do_ping;
    u8 error_state;
    u8 halt_on_queue;
    u8 halt_pending;
    u8 do_split;
    u8 complete_split;
    u8 hub_addr;
    u8 hub_port;
    u8 xact_pos;
    u8 requests;
    u8 schinfo;
    u16 ntd;
    enum dwc2_halt_status halt_status;
    u32 hcint;
    struct dwc2_qh * qh;
    struct list_head hc_list_entry;
    dma_addr_t desc_list_addr;
    u32 desc_list_sz;
    struct list_head split_order_list_entry;
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
