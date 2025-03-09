# Struct: <code>vas_winctx</code>

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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct vas_winctx {
    void * rx_fifo;
    int rx_fifo_size;
    int wcreds_max;
    int rsvd_txbuf_count;
    bool user_win;
    bool nx_win;
    bool fault_win;
    bool rsvd_txbuf_enable;
    bool pin_win;
    bool rej_no_credit;
    bool tx_wcred_mode;
    bool rx_wcred_mode;
    bool tx_word_mode;
    bool rx_word_mode;
    bool data_stamp;
    bool xtra_write;
    bool notify_disable;
    bool intr_disable;
    bool fifo_disable;
    bool notify_early;
    bool notify_os_intr_reg;
    int lpid;
    int pidr;
    int lnotify_lpid;
    int lnotify_pid;
    int lnotify_tid;
    u32 pswid;
    int rx_win_id;
    int fault_win_id;
    int tc_mode;
    u64 irq_port;
    enum vas_dma_type dma_type;
    enum vas_notify_scope min_scope;
    enum vas_notify_scope max_scope;
    enum vas_notify_after_count notify_after_count;
}
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct vas_winctx {
    void * rx_fifo;
    int rx_fifo_size;
    int wcreds_max;
    int rsvd_txbuf_count;
    bool user_win;
    bool nx_win;
    bool fault_win;
    bool rsvd_txbuf_enable;
    bool pin_win;
    bool rej_no_credit;
    bool tx_wcred_mode;
    bool rx_wcred_mode;
    bool tx_word_mode;
    bool rx_word_mode;
    bool data_stamp;
    bool xtra_write;
    bool notify_disable;
    bool intr_disable;
    bool fifo_disable;
    bool notify_early;
    bool notify_os_intr_reg;
    int lpid;
    int pidr;
    int lnotify_lpid;
    int lnotify_pid;
    int lnotify_tid;
    u32 pswid;
    int rx_win_id;
    int fault_win_id;
    int tc_mode;
    u64 irq_port;
    enum vas_dma_type dma_type;
    enum vas_notify_scope min_scope;
    enum vas_notify_scope max_scope;
    enum vas_notify_after_count notify_after_count;
}
```
</details>
</li>
</ul>
