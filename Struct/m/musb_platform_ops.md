# Struct: <code>musb_platform_ops</code>

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
struct musb_platform_ops {
    u32 quirks;
    int (*)(struct musb *) init;
    int (*)(struct musb *) exit;
    void (*)(struct musb *) enable;
    void (*)(struct musb *) disable;
    u32 (*)(u8, u16) ep_offset;
    void (*)(void *, u8) ep_select;
    u16 fifo_mode;
    u32 (*)(u8) fifo_offset;
    u32 (*)(u8, u16) busctl_offset;
    u8 (*)(const void *, unsigned int) readb;
    void (*)(void *, unsigned int, u8) writeb;
    u16 (*)(const void *, unsigned int) readw;
    void (*)(void *, unsigned int, u16) writew;
    void (*)(struct musb_hw_ep *, u16, u8 *) read_fifo;
    void (*)(struct musb_hw_ep *, u16, const u8 *) write_fifo;
    struct dma_controller * (*)(struct musb *, void *) dma_init;
    void (*)(struct dma_controller *) dma_exit;
    int (*)(struct musb *, u8) set_mode;
    void (*)(struct musb *, long unsigned int) try_idle;
    int (*)(struct musb *) recover;
    int (*)(struct musb *) vbus_status;
    void (*)(struct musb *, int) set_vbus;
    void (*)(struct musb *) pre_root_reset_end;
    void (*)(struct musb *) post_root_reset_end;
    int (*)(enum musb_vbus_id_status) phy_callback;
    void (*)(struct musb *, int) clear_ep_rxintr;
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
struct musb_platform_ops {
    u32 quirks;
    int (*)(struct musb *) init;
    int (*)(struct musb *) exit;
    void (*)(struct musb *) enable;
    void (*)(struct musb *) disable;
    u32 (*)(u8, u16) ep_offset;
    void (*)(void *, u8) ep_select;
    u16 fifo_mode;
    u32 (*)(u8) fifo_offset;
    u32 (*)(u8, u16) busctl_offset;
    u8 (*)(const void *, unsigned int) readb;
    void (*)(void *, unsigned int, u8) writeb;
    u16 (*)(const void *, unsigned int) readw;
    void (*)(void *, unsigned int, u16) writew;
    void (*)(struct musb_hw_ep *, u16, u8 *) read_fifo;
    void (*)(struct musb_hw_ep *, u16, const u8 *) write_fifo;
    struct dma_controller * (*)(struct musb *, void *) dma_init;
    void (*)(struct dma_controller *) dma_exit;
    int (*)(struct musb *, u8) set_mode;
    void (*)(struct musb *, long unsigned int) try_idle;
    int (*)(struct musb *) recover;
    int (*)(struct musb *) vbus_status;
    void (*)(struct musb *, int) set_vbus;
    void (*)(struct musb *) pre_root_reset_end;
    void (*)(struct musb *) post_root_reset_end;
    int (*)(enum musb_vbus_id_status) phy_callback;
    void (*)(struct musb *, int) clear_ep_rxintr;
}
```
</details>
</li>
</ul>
