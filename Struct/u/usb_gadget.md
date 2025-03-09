# Struct: <code>usb_gadget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int out_epnum;
    unsigned int in_epnum;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
    unsigned int lpm_capable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
    unsigned int lpm_capable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int isoch_delay;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
    unsigned int lpm_capable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int isoch_delay;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
    unsigned int lpm_capable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int isoch_delay;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
    unsigned int lpm_capable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int isoch_delay;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
    unsigned int lpm_capable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int isoch_delay;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
    unsigned int lpm_capable;
    int irq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int isoch_delay;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
    unsigned int lpm_capable;
    int irq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_ssp_rate ssp_rate;
    enum usb_ssp_rate max_ssp_rate;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int isoch_delay;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
    unsigned int lpm_capable;
    int irq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_ssp_rate ssp_rate;
    enum usb_ssp_rate max_ssp_rate;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int isoch_delay;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
    unsigned int lpm_capable;
    int irq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_ssp_rate ssp_rate;
    enum usb_ssp_rate max_ssp_rate;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int isoch_delay;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
    unsigned int lpm_capable;
    int irq;
    int id_number;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_ssp_rate ssp_rate;
    enum usb_ssp_rate max_ssp_rate;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int isoch_delay;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
    unsigned int lpm_capable;
    int irq;
    int id_number;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_ssp_rate ssp_rate;
    enum usb_ssp_rate max_ssp_rate;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int isoch_delay;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
    unsigned int lpm_capable;
    unsigned int wakeup_capable;
    unsigned int wakeup_armed;
    int irq;
    int id_number;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_ssp_rate ssp_rate;
    enum usb_ssp_rate max_ssp_rate;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int isoch_delay;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
    unsigned int lpm_capable;
    unsigned int wakeup_capable;
    unsigned int wakeup_armed;
    int irq;
    int id_number;
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
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int isoch_delay;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
    unsigned int lpm_capable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int isoch_delay;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
    unsigned int lpm_capable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int isoch_delay;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
    unsigned int lpm_capable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int isoch_delay;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
    unsigned int lpm_capable;
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
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int isoch_delay;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
    unsigned int lpm_capable;
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
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int isoch_delay;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
    unsigned int lpm_capable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int isoch_delay;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
    unsigned int lpm_capable;
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
<code>unsigned int mA</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int hnp_polling_support</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int host_request_flag</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int quirk_avoids_skb_reserve</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int lpm_capable</code>
</li>
</ul>
</details>
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
<code>unsigned int isoch_delay</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int irq</code>
</li>
</ul>
</details>
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
<code>enum usb_ssp_rate ssp_rate</code>
</li>
<li>
<b>Field added. </b>
<code>enum usb_ssp_rate max_ssp_rate</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int id_number</code>
</li>
</ul>
</details>
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
<code>unsigned int wakeup_capable</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int wakeup_armed</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct usb_udc * udc</code> ➡️ <code>struct usb_udc * udc</code>
</li>
</ul>
</details>
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
struct usb_gadget {
    struct work_struct work;
    struct usb_udc * udc;
    const struct usb_gadget_ops * ops;
    struct usb_ep * ep0;
    struct list_head ep_list;
    enum usb_device_speed speed;
    enum usb_device_speed max_speed;
    enum usb_device_state state;
    const char * name;
    struct device dev;
    unsigned int isoch_delay;
    unsigned int out_epnum;
    unsigned int in_epnum;
    unsigned int mA;
    struct usb_otg_caps * otg_caps;
    unsigned int sg_supported;
    unsigned int is_otg;
    unsigned int is_a_peripheral;
    unsigned int b_hnp_enable;
    unsigned int a_hnp_support;
    unsigned int a_alt_hnp_support;
    unsigned int hnp_polling_support;
    unsigned int host_request_flag;
    unsigned int quirk_ep_out_aligned_size;
    unsigned int quirk_altset_not_supp;
    unsigned int quirk_stall_not_supp;
    unsigned int quirk_zlp_not_supp;
    unsigned int quirk_avoids_skb_reserve;
    unsigned int is_selfpowered;
    unsigned int deactivated;
    unsigned int connected;
    unsigned int lpm_capable;
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
