# Struct: <code>usb_gadget_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_gadget *, struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_gadget *, struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_gadget *, struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_gadget *, struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_gadget *, struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed;
    void (*)(struct usb_gadget *, enum usb_ssp_rate) udc_set_ssp_rate;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_gadget *, struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed;
    void (*)(struct usb_gadget *, enum usb_ssp_rate) udc_set_ssp_rate;
    void (*)(struct usb_gadget *, bool) udc_async_callbacks;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
    int (*)(struct usb_gadget *) check_config;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_gadget *, struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed;
    void (*)(struct usb_gadget *, enum usb_ssp_rate) udc_set_ssp_rate;
    void (*)(struct usb_gadget *, bool) udc_async_callbacks;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
    int (*)(struct usb_gadget *) check_config;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_gadget *, struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed;
    void (*)(struct usb_gadget *, enum usb_ssp_rate) udc_set_ssp_rate;
    void (*)(struct usb_gadget *, bool) udc_async_callbacks;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
    int (*)(struct usb_gadget *) check_config;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) func_wakeup;
    int (*)(struct usb_gadget *, int) set_remote_wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_gadget *, struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed;
    void (*)(struct usb_gadget *, enum usb_ssp_rate) udc_set_ssp_rate;
    void (*)(struct usb_gadget *, bool) udc_async_callbacks;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
    int (*)(struct usb_gadget *) check_config;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) func_wakeup;
    int (*)(struct usb_gadget *, int) set_remote_wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_gadget *, struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed;
    void (*)(struct usb_gadget *, enum usb_ssp_rate) udc_set_ssp_rate;
    void (*)(struct usb_gadget *, bool) udc_async_callbacks;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
    int (*)(struct usb_gadget *) check_config;
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
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_gadget *, struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_gadget *, struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_gadget *, struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_gadget *, struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
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
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_gadget *, struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
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
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_gadget *, struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_gadget *, struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void (*)(struct usb_dcd_config_params *) get_config_params</code> ➡️ <code>void (*)(struct usb_gadget *, struct usb_dcd_config_params *) get_config_params</code>
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
<code>void (*)(struct usb_gadget *, enum usb_ssp_rate) udc_set_ssp_rate</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct usb_gadget *, bool) udc_async_callbacks</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct usb_gadget *) check_config</code>
</li>
</ul>
</details>
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
<code>int (*)(struct usb_gadget *, int) func_wakeup</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct usb_gadget *, int) set_remote_wakeup</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct usb_gadget_ops {
    int (*)(struct usb_gadget *) get_frame;
    int (*)(struct usb_gadget *) wakeup;
    int (*)(struct usb_gadget *, int) set_selfpowered;
    int (*)(struct usb_gadget *, int) vbus_session;
    int (*)(struct usb_gadget *, unsigned int) vbus_draw;
    int (*)(struct usb_gadget *, int) pullup;
    int (*)(struct usb_gadget *, unsigned int, long unsigned int) ioctl;
    void (*)(struct usb_gadget *, struct usb_dcd_config_params *) get_config_params;
    int (*)(struct usb_gadget *, struct usb_gadget_driver *) udc_start;
    int (*)(struct usb_gadget *) udc_stop;
    void (*)(struct usb_gadget *, enum usb_device_speed) udc_set_speed;
    struct usb_ep * (*)(struct usb_gadget *, struct usb_endpoint_descriptor *, struct usb_ss_ep_comp_descriptor *) match_ep;
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
