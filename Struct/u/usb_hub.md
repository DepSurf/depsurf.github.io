# Struct: <code>usb_hub</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    struct usb_port * * ports;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    struct usb_port * * ports;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    struct usb_port * * ports;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    struct usb_port * * ports;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    struct usb_port * * ports;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    struct usb_port * * ports;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    struct usb_port * * ports;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    spinlock_t irq_urb_lock;
    struct timer_list irq_urb_retry;
    struct usb_port * * ports;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_disable_autosuspend;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    spinlock_t irq_urb_lock;
    struct timer_list irq_urb_retry;
    struct usb_port * * ports;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_disable_autosuspend;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    spinlock_t irq_urb_lock;
    struct timer_list irq_urb_retry;
    struct usb_port * * ports;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_disable_autosuspend;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    spinlock_t irq_urb_lock;
    struct timer_list irq_urb_retry;
    struct usb_port * * ports;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_disable_autosuspend;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    spinlock_t irq_urb_lock;
    struct timer_list irq_urb_retry;
    struct usb_port * * ports;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_disable_autosuspend;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    spinlock_t irq_urb_lock;
    struct timer_list irq_urb_retry;
    struct usb_port * * ports;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_disable_autosuspend;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    spinlock_t irq_urb_lock;
    struct timer_list irq_urb_retry;
    struct usb_port * * ports;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_disable_autosuspend;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    spinlock_t irq_urb_lock;
    struct timer_list irq_urb_retry;
    struct usb_port * * ports;
    struct list_head onboard_hub_devs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_disable_autosuspend;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    spinlock_t irq_urb_lock;
    struct timer_list irq_urb_retry;
    struct usb_port * * ports;
    struct list_head onboard_hub_devs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_disable_autosuspend;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    spinlock_t irq_urb_lock;
    struct timer_list irq_urb_retry;
    struct usb_port * * ports;
    struct list_head onboard_hub_devs;
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
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_disable_autosuspend;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    spinlock_t irq_urb_lock;
    struct timer_list irq_urb_retry;
    struct usb_port * * ports;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_disable_autosuspend;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    spinlock_t irq_urb_lock;
    struct timer_list irq_urb_retry;
    struct usb_port * * ports;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_disable_autosuspend;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    spinlock_t irq_urb_lock;
    struct timer_list irq_urb_retry;
    struct usb_port * * ports;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_disable_autosuspend;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    spinlock_t irq_urb_lock;
    struct timer_list irq_urb_retry;
    struct usb_port * * ports;
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
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_disable_autosuspend;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    spinlock_t irq_urb_lock;
    struct timer_list irq_urb_retry;
    struct usb_port * * ports;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_disable_autosuspend;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    spinlock_t irq_urb_lock;
    struct timer_list irq_urb_retry;
    struct usb_port * * ports;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_disable_autosuspend;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    spinlock_t irq_urb_lock;
    struct timer_list irq_urb_retry;
    struct usb_port * * ports;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct usb_hub {
    struct device * intfdev;
    struct usb_device * hdev;
    struct kref kref;
    struct urb * urb;
    u8[8] * buffer;
    union (anon) * status;
    struct mutex status_mutex;
    int error;
    int nerrors;
    long unsigned int[1] event_bits;
    long unsigned int[1] change_bits;
    long unsigned int[1] removed_bits;
    long unsigned int[1] wakeup_bits;
    long unsigned int[1] power_bits;
    long unsigned int[1] child_usage_bits;
    long unsigned int[1] warm_reset_bits;
    struct usb_hub_descriptor * descriptor;
    struct usb_tt tt;
    unsigned int mA_per_port;
    unsigned int wakeup_enabled_descendants;
    unsigned int limited_power;
    unsigned int quiescing;
    unsigned int disconnected;
    unsigned int in_reset;
    unsigned int quirk_disable_autosuspend;
    unsigned int quirk_check_port_auto_suspend;
    unsigned int has_indicators;
    u8[31] indicator;
    struct delayed_work leds;
    struct delayed_work init_work;
    struct work_struct events;
    spinlock_t irq_urb_lock;
    struct timer_list irq_urb_retry;
    struct usb_port * * ports;
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>spinlock_t irq_urb_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct timer_list irq_urb_retry</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int quirk_disable_autosuspend</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head onboard_hub_devs</code>
</li>
</ul>
</details>
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
