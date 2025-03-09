# Struct: <code>hc_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    long unsigned int (*)(struct usb_hcd *) get_resuming_ports;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    long unsigned int (*)(struct usb_hcd *) get_resuming_ports;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    long unsigned int (*)(struct usb_hcd *) get_resuming_ports;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    long unsigned int (*)(struct usb_hcd *) get_resuming_ports;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    long unsigned int (*)(struct usb_hcd *) get_resuming_ports;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    long unsigned int (*)(struct usb_hcd *) get_resuming_ports;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    long unsigned int (*)(struct usb_hcd *) get_resuming_ports;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
    int (*)(struct usb_hcd *, struct urb *, int) submit_single_step_set_feature;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    long unsigned int (*)(struct usb_hcd *) get_resuming_ports;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
    int (*)(struct usb_hcd *, struct urb *, int) submit_single_step_set_feature;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    int (*)(struct usb_hcd *, bool) pci_poweroff_late;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    long unsigned int (*)(struct usb_hcd *) get_resuming_ports;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
    int (*)(struct usb_hcd *, struct urb *, int) submit_single_step_set_feature;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, pm_message_t) pci_resume;
    int (*)(struct usb_hcd *, bool) pci_poweroff_late;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    long unsigned int (*)(struct usb_hcd *) get_resuming_ports;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
    int (*)(struct usb_hcd *, struct urb *, int) submit_single_step_set_feature;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, pm_message_t) pci_resume;
    int (*)(struct usb_hcd *, bool) pci_poweroff_late;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    long unsigned int (*)(struct usb_hcd *) get_resuming_ports;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *, unsigned int) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
    int (*)(struct usb_hcd *, struct urb *, int) submit_single_step_set_feature;
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
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    long unsigned int (*)(struct usb_hcd *) get_resuming_ports;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    long unsigned int (*)(struct usb_hcd *) get_resuming_ports;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    long unsigned int (*)(struct usb_hcd *) get_resuming_ports;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    long unsigned int (*)(struct usb_hcd *) get_resuming_ports;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
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
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    long unsigned int (*)(struct usb_hcd *) get_resuming_ports;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    long unsigned int (*)(struct usb_hcd *) get_resuming_ports;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    long unsigned int (*)(struct usb_hcd *) get_resuming_ports;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct hc_driver {
    const char * description;
    const char * product_desc;
    size_t hcd_priv_size;
    irqreturn_t (*)(struct usb_hcd *) irq;
    int flags;
    int (*)(struct usb_hcd *) reset;
    int (*)(struct usb_hcd *) start;
    int (*)(struct usb_hcd *, bool) pci_suspend;
    int (*)(struct usb_hcd *, bool) pci_resume;
    void (*)(struct usb_hcd *) stop;
    void (*)(struct usb_hcd *) shutdown;
    int (*)(struct usb_hcd *) get_frame_number;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) urb_enqueue;
    int (*)(struct usb_hcd *, struct urb *, int) urb_dequeue;
    int (*)(struct usb_hcd *, struct urb *, gfp_t) map_urb_for_dma;
    void (*)(struct usb_hcd *, struct urb *) unmap_urb_for_dma;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_disable;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) endpoint_reset;
    int (*)(struct usb_hcd *, char *) hub_status_data;
    int (*)(struct usb_hcd *, u16, u16, u16, char *, u16) hub_control;
    int (*)(struct usb_hcd *) bus_suspend;
    int (*)(struct usb_hcd *) bus_resume;
    int (*)(struct usb_hcd *, unsigned int) start_port_reset;
    long unsigned int (*)(struct usb_hcd *) get_resuming_ports;
    void (*)(struct usb_hcd *, int) relinquish_port;
    int (*)(struct usb_hcd *, int) port_handed_over;
    void (*)(struct usb_hcd *, struct usb_host_endpoint *) clear_tt_buffer_complete;
    int (*)(struct usb_hcd *, struct usb_device *) alloc_dev;
    void (*)(struct usb_hcd *, struct usb_device *) free_dev;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, unsigned int, gfp_t) alloc_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint * *, unsigned int, gfp_t) free_streams;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) add_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_host_endpoint *) drop_endpoint;
    int (*)(struct usb_hcd *, struct usb_device *) check_bandwidth;
    void (*)(struct usb_hcd *, struct usb_device *) reset_bandwidth;
    int (*)(struct usb_hcd *, struct usb_device *) address_device;
    int (*)(struct usb_hcd *, struct usb_device *) enable_device;
    int (*)(struct usb_hcd *, struct usb_device *, struct usb_tt *, gfp_t) update_hub_device;
    int (*)(struct usb_hcd *, struct usb_device *) reset_device;
    int (*)(struct usb_hcd *, struct usb_device *) update_device;
    int (*)(struct usb_hcd *, struct usb_device *, int) set_usb2_hw_lpm;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) enable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, struct usb_device *, enum usb3_link_state) disable_usb3_lpm_timeout;
    int (*)(struct usb_hcd *, int) find_raw_port_number;
    int (*)(struct usb_hcd *, int, bool) port_power;
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int (*)(struct usb_hcd *) get_resuming_ports</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct usb_hcd *, struct urb *, int) submit_single_step_set_feature</code>
</li>
</ul>
</details>
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
<code>int (*)(struct usb_hcd *, bool) pci_poweroff_late</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct usb_hcd *, bool) pci_resume</code> ➡️ <code>int (*)(struct usb_hcd *, pm_message_t) pci_resume</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct usb_hcd *, struct usb_device *) address_device</code> ➡️ <code>int (*)(struct usb_hcd *, struct usb_device *, unsigned int) address_device</code>
</li>
</ul>
</details>
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
