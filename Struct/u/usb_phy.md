# Struct: <code>usb_phy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct extcon_dev * edev;
    struct extcon_dev * id_edev;
    struct notifier_block vbus_nb;
    struct notifier_block id_nb;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct extcon_dev * edev;
    struct extcon_dev * id_edev;
    struct notifier_block vbus_nb;
    struct notifier_block id_nb;
    struct notifier_block type_nb;
    enum usb_charger_type chg_type;
    enum usb_charger_state chg_state;
    struct usb_charger_current chg_cur;
    struct work_struct chg_work;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
    enum usb_charger_type (*)(struct usb_phy *) charger_detect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct extcon_dev * edev;
    struct extcon_dev * id_edev;
    struct notifier_block vbus_nb;
    struct notifier_block id_nb;
    struct notifier_block type_nb;
    enum usb_charger_type chg_type;
    enum usb_charger_state chg_state;
    struct usb_charger_current chg_cur;
    struct work_struct chg_work;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
    enum usb_charger_type (*)(struct usb_phy *) charger_detect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct extcon_dev * edev;
    struct extcon_dev * id_edev;
    struct notifier_block vbus_nb;
    struct notifier_block id_nb;
    struct notifier_block type_nb;
    enum usb_charger_type chg_type;
    enum usb_charger_state chg_state;
    struct usb_charger_current chg_cur;
    struct work_struct chg_work;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
    enum usb_charger_type (*)(struct usb_phy *) charger_detect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct extcon_dev * edev;
    struct extcon_dev * id_edev;
    struct notifier_block vbus_nb;
    struct notifier_block id_nb;
    struct notifier_block type_nb;
    enum usb_charger_type chg_type;
    enum usb_charger_state chg_state;
    struct usb_charger_current chg_cur;
    struct work_struct chg_work;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
    enum usb_charger_type (*)(struct usb_phy *) charger_detect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct extcon_dev * edev;
    struct extcon_dev * id_edev;
    struct notifier_block vbus_nb;
    struct notifier_block id_nb;
    struct notifier_block type_nb;
    enum usb_charger_type chg_type;
    enum usb_charger_state chg_state;
    struct usb_charger_current chg_cur;
    struct work_struct chg_work;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
    enum usb_charger_type (*)(struct usb_phy *) charger_detect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct extcon_dev * edev;
    struct extcon_dev * id_edev;
    struct notifier_block vbus_nb;
    struct notifier_block id_nb;
    struct notifier_block type_nb;
    enum usb_charger_type chg_type;
    enum usb_charger_state chg_state;
    struct usb_charger_current chg_cur;
    struct work_struct chg_work;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
    enum usb_charger_type (*)(struct usb_phy *) charger_detect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct extcon_dev * edev;
    struct extcon_dev * id_edev;
    struct notifier_block vbus_nb;
    struct notifier_block id_nb;
    struct notifier_block type_nb;
    enum usb_charger_type chg_type;
    enum usb_charger_state chg_state;
    struct usb_charger_current chg_cur;
    struct work_struct chg_work;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
    enum usb_charger_type (*)(struct usb_phy *) charger_detect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct extcon_dev * edev;
    struct extcon_dev * id_edev;
    struct notifier_block vbus_nb;
    struct notifier_block id_nb;
    struct notifier_block type_nb;
    enum usb_charger_type chg_type;
    enum usb_charger_state chg_state;
    struct usb_charger_current chg_cur;
    struct work_struct chg_work;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
    enum usb_charger_type (*)(struct usb_phy *) charger_detect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct extcon_dev * edev;
    struct extcon_dev * id_edev;
    struct notifier_block vbus_nb;
    struct notifier_block id_nb;
    struct notifier_block type_nb;
    enum usb_charger_type chg_type;
    enum usb_charger_state chg_state;
    struct usb_charger_current chg_cur;
    struct work_struct chg_work;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
    enum usb_charger_type (*)(struct usb_phy *) charger_detect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct extcon_dev * edev;
    struct extcon_dev * id_edev;
    struct notifier_block vbus_nb;
    struct notifier_block id_nb;
    struct notifier_block type_nb;
    enum usb_charger_type chg_type;
    enum usb_charger_state chg_state;
    struct usb_charger_current chg_cur;
    struct work_struct chg_work;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
    enum usb_charger_type (*)(struct usb_phy *) charger_detect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct extcon_dev * edev;
    struct extcon_dev * id_edev;
    struct notifier_block vbus_nb;
    struct notifier_block id_nb;
    struct notifier_block type_nb;
    enum usb_charger_type chg_type;
    enum usb_charger_state chg_state;
    struct usb_charger_current chg_cur;
    struct work_struct chg_work;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
    enum usb_charger_type (*)(struct usb_phy *) charger_detect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct extcon_dev * edev;
    struct extcon_dev * id_edev;
    struct notifier_block vbus_nb;
    struct notifier_block id_nb;
    struct notifier_block type_nb;
    enum usb_charger_type chg_type;
    enum usb_charger_state chg_state;
    struct usb_charger_current chg_cur;
    struct work_struct chg_work;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
    enum usb_charger_type (*)(struct usb_phy *) charger_detect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct extcon_dev * edev;
    struct extcon_dev * id_edev;
    struct notifier_block vbus_nb;
    struct notifier_block id_nb;
    struct notifier_block type_nb;
    enum usb_charger_type chg_type;
    enum usb_charger_state chg_state;
    struct usb_charger_current chg_cur;
    struct work_struct chg_work;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
    enum usb_charger_type (*)(struct usb_phy *) charger_detect;
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
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct extcon_dev * edev;
    struct extcon_dev * id_edev;
    struct notifier_block vbus_nb;
    struct notifier_block id_nb;
    struct notifier_block type_nb;
    enum usb_charger_type chg_type;
    enum usb_charger_state chg_state;
    struct usb_charger_current chg_cur;
    struct work_struct chg_work;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
    enum usb_charger_type (*)(struct usb_phy *) charger_detect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct extcon_dev * edev;
    struct extcon_dev * id_edev;
    struct notifier_block vbus_nb;
    struct notifier_block id_nb;
    struct notifier_block type_nb;
    enum usb_charger_type chg_type;
    enum usb_charger_state chg_state;
    struct usb_charger_current chg_cur;
    struct work_struct chg_work;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
    enum usb_charger_type (*)(struct usb_phy *) charger_detect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct extcon_dev * edev;
    struct extcon_dev * id_edev;
    struct notifier_block vbus_nb;
    struct notifier_block id_nb;
    struct notifier_block type_nb;
    enum usb_charger_type chg_type;
    enum usb_charger_state chg_state;
    struct usb_charger_current chg_cur;
    struct work_struct chg_work;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
    enum usb_charger_type (*)(struct usb_phy *) charger_detect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct extcon_dev * edev;
    struct extcon_dev * id_edev;
    struct notifier_block vbus_nb;
    struct notifier_block id_nb;
    struct notifier_block type_nb;
    enum usb_charger_type chg_type;
    enum usb_charger_state chg_state;
    struct usb_charger_current chg_cur;
    struct work_struct chg_work;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
    enum usb_charger_type (*)(struct usb_phy *) charger_detect;
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
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct extcon_dev * edev;
    struct extcon_dev * id_edev;
    struct notifier_block vbus_nb;
    struct notifier_block id_nb;
    struct notifier_block type_nb;
    enum usb_charger_type chg_type;
    enum usb_charger_state chg_state;
    struct usb_charger_current chg_cur;
    struct work_struct chg_work;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
    enum usb_charger_type (*)(struct usb_phy *) charger_detect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct extcon_dev * edev;
    struct extcon_dev * id_edev;
    struct notifier_block vbus_nb;
    struct notifier_block id_nb;
    struct notifier_block type_nb;
    enum usb_charger_type chg_type;
    enum usb_charger_state chg_state;
    struct usb_charger_current chg_cur;
    struct work_struct chg_work;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
    enum usb_charger_type (*)(struct usb_phy *) charger_detect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct extcon_dev * edev;
    struct extcon_dev * id_edev;
    struct notifier_block vbus_nb;
    struct notifier_block id_nb;
    struct notifier_block type_nb;
    enum usb_charger_type chg_type;
    enum usb_charger_state chg_state;
    struct usb_charger_current chg_cur;
    struct work_struct chg_work;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
    enum usb_charger_type (*)(struct usb_phy *) charger_detect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct usb_phy {
    struct device * dev;
    const char * label;
    unsigned int flags;
    enum usb_phy_type type;
    enum usb_phy_events last_event;
    struct usb_otg * otg;
    struct device * io_dev;
    struct usb_phy_io_ops * io_ops;
    void * io_priv;
    struct extcon_dev * edev;
    struct extcon_dev * id_edev;
    struct notifier_block vbus_nb;
    struct notifier_block id_nb;
    struct notifier_block type_nb;
    enum usb_charger_type chg_type;
    enum usb_charger_state chg_state;
    struct usb_charger_current chg_cur;
    struct work_struct chg_work;
    struct atomic_notifier_head notifier;
    u16 port_status;
    u16 port_change;
    struct list_head head;
    int (*)(struct usb_phy *) init;
    void (*)(struct usb_phy *) shutdown;
    int (*)(struct usb_phy *, int) set_vbus;
    int (*)(struct usb_phy *, unsigned int) set_power;
    int (*)(struct usb_phy *, int) set_suspend;
    int (*)(struct usb_phy *, bool) set_wakeup;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_connect;
    int (*)(struct usb_phy *, enum usb_device_speed) notify_disconnect;
    enum usb_charger_type (*)(struct usb_phy *) charger_detect;
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
<code>struct extcon_dev * edev</code>
</li>
<li>
<b>Field added. </b>
<code>struct extcon_dev * id_edev</code>
</li>
<li>
<b>Field added. </b>
<code>struct notifier_block vbus_nb</code>
</li>
<li>
<b>Field added. </b>
<code>struct notifier_block id_nb</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct notifier_block type_nb</code>
</li>
<li>
<b>Field added. </b>
<code>enum usb_charger_type chg_type</code>
</li>
<li>
<b>Field added. </b>
<code>enum usb_charger_state chg_state</code>
</li>
<li>
<b>Field added. </b>
<code>struct usb_charger_current chg_cur</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct chg_work</code>
</li>
<li>
<b>Field added. </b>
<code>enum usb_charger_type (*)(struct usb_phy *) charger_detect</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct extcon_dev * edev</code> ➡️ <code>struct extcon_dev * edev</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct extcon_dev * id_edev</code> ➡️ <code>struct extcon_dev * id_edev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
