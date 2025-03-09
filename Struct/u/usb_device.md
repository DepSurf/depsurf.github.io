# Struct: <code>usb_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_enabled;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    enum usb_device_removable removable;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    enum usb_device_removable removable;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    enum usb_device_removable removable;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    enum usb_device_removable removable;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    enum usb_device_removable removable;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    unsigned int rx_lanes;
    unsigned int tx_lanes;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    enum usb_device_removable removable;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
    u16 hub_delay;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    unsigned int rx_lanes;
    unsigned int tx_lanes;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    enum usb_device_removable removable;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
    u16 hub_delay;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    unsigned int rx_lanes;
    unsigned int tx_lanes;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    u8 devaddr;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    enum usb_device_removable removable;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
    u16 hub_delay;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    unsigned int rx_lanes;
    unsigned int tx_lanes;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    u8 devaddr;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    enum usb_device_removable removable;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
    u16 hub_delay;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    unsigned int rx_lanes;
    unsigned int tx_lanes;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    u8 devaddr;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    enum usb_device_removable removable;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
    u16 hub_delay;
    unsigned int use_generic_driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    unsigned int rx_lanes;
    unsigned int tx_lanes;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    u8 devaddr;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    enum usb_device_removable removable;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
    u16 hub_delay;
    unsigned int use_generic_driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    unsigned int rx_lanes;
    unsigned int tx_lanes;
    enum usb_ssp_rate ssp_rate;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    u8 devaddr;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    enum usb_device_removable removable;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
    u16 hub_delay;
    unsigned int use_generic_driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    unsigned int rx_lanes;
    unsigned int tx_lanes;
    enum usb_ssp_rate ssp_rate;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    u8 devaddr;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
    u16 hub_delay;
    unsigned int use_generic_driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    unsigned int rx_lanes;
    unsigned int tx_lanes;
    enum usb_ssp_rate ssp_rate;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    u8 devaddr;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
    u16 hub_delay;
    unsigned int use_generic_driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    unsigned int rx_lanes;
    unsigned int tx_lanes;
    enum usb_ssp_rate ssp_rate;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    u8 devaddr;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int reset_in_progress;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int lpm_devinit_allow;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
    u16 hub_delay;
    unsigned int use_generic_driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    unsigned int rx_lanes;
    unsigned int tx_lanes;
    enum usb_ssp_rate ssp_rate;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    u8 devaddr;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int reset_in_progress;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int lpm_devinit_allow;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
    u16 hub_delay;
    unsigned int use_generic_driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    unsigned int rx_lanes;
    unsigned int tx_lanes;
    enum usb_ssp_rate ssp_rate;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    u8 devaddr;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int reset_in_progress;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int lpm_capable;
    unsigned int lpm_devinit_allow;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    int slot_id;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
    u16 hub_delay;
    unsigned int use_generic_driver;
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
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    unsigned int rx_lanes;
    unsigned int tx_lanes;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    u8 devaddr;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    enum usb_device_removable removable;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
    u16 hub_delay;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    unsigned int rx_lanes;
    unsigned int tx_lanes;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    u8 devaddr;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    enum usb_device_removable removable;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
    u16 hub_delay;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    unsigned int rx_lanes;
    unsigned int tx_lanes;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    u8 devaddr;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    enum usb_device_removable removable;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
    u16 hub_delay;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    unsigned int rx_lanes;
    unsigned int tx_lanes;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    u8 devaddr;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    enum usb_device_removable removable;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
    u16 hub_delay;
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
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    unsigned int rx_lanes;
    unsigned int tx_lanes;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    u8 devaddr;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    enum usb_device_removable removable;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
    u16 hub_delay;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    unsigned int rx_lanes;
    unsigned int tx_lanes;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    u8 devaddr;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    enum usb_device_removable removable;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
    u16 hub_delay;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    unsigned int rx_lanes;
    unsigned int tx_lanes;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    u8 devaddr;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    enum usb_device_removable removable;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
    u16 hub_delay;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct usb_device {
    int devnum;
    char[16] devpath;
    u32 route;
    enum usb_device_state state;
    enum usb_device_speed speed;
    unsigned int rx_lanes;
    unsigned int tx_lanes;
    struct usb_tt * tt;
    int ttport;
    unsigned int[2] toggle;
    struct usb_device * parent;
    struct usb_bus * bus;
    struct usb_host_endpoint ep0;
    struct device dev;
    struct usb_device_descriptor descriptor;
    struct usb_host_bos * bos;
    struct usb_host_config * config;
    struct usb_host_config * actconfig;
    struct usb_host_endpoint *[16] ep_in;
    struct usb_host_endpoint *[16] ep_out;
    char * * rawdescriptors;
    short unsigned int bus_mA;
    u8 portnum;
    u8 level;
    u8 devaddr;
    unsigned int can_submit;
    unsigned int persist_enabled;
    unsigned int have_langid;
    unsigned int authorized;
    unsigned int authenticated;
    unsigned int wusb;
    unsigned int lpm_capable;
    unsigned int usb2_hw_lpm_capable;
    unsigned int usb2_hw_lpm_besl_capable;
    unsigned int usb2_hw_lpm_enabled;
    unsigned int usb2_hw_lpm_allowed;
    unsigned int usb3_lpm_u1_enabled;
    unsigned int usb3_lpm_u2_enabled;
    int string_langid;
    char * product;
    char * manufacturer;
    char * serial;
    struct list_head filelist;
    int maxchild;
    u32 quirks;
    atomic_t urbnum;
    long unsigned int active_duration;
    long unsigned int connect_time;
    unsigned int do_remote_wakeup;
    unsigned int reset_resume;
    unsigned int port_is_suspended;
    struct wusb_dev * wusb_dev;
    int slot_id;
    enum usb_device_removable removable;
    struct usb2_lpm_parameters l1_params;
    struct usb3_lpm_parameters u1_params;
    struct usb3_lpm_parameters u2_params;
    unsigned int lpm_disable_count;
    u16 hub_delay;
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
<b>Field removed. </b>
<code>unsigned int usb3_lpm_enabled</code>
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
<code>unsigned int rx_lanes</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int tx_lanes</code>
</li>
<li>
<b>Field added. </b>
<code>u16 hub_delay</code>
</li>
</ul>
</details>
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
<code>u8 devaddr</code>
</li>
</ul>
</details>
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
<code>unsigned int use_generic_driver</code>
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
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>enum usb_device_removable removable</code>
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
<code>unsigned int reset_in_progress</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int lpm_devinit_allow</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int wusb</code>
</li>
<li>
<b>Field removed. </b>
<code>struct wusb_dev * wusb_dev</code>
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
