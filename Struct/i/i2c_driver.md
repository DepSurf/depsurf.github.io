# Struct: <code>i2c_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_adapter *) attach_adapter;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    int (*)(struct i2c_client *) remove;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_adapter *) attach_adapter;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    int (*)(struct i2c_client *) remove;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_adapter *) attach_adapter;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    int (*)(struct i2c_client *) remove;
    int (*)(struct i2c_client *) probe_new;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_adapter *) attach_adapter;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    int (*)(struct i2c_client *) remove;
    int (*)(struct i2c_client *) probe_new;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
    bool disable_i2c_core_irq_mapping;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_adapter *) attach_adapter;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    int (*)(struct i2c_client *) remove;
    int (*)(struct i2c_client *) probe_new;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
    bool disable_i2c_core_irq_mapping;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_adapter *) attach_adapter;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    int (*)(struct i2c_client *) remove;
    int (*)(struct i2c_client *) probe_new;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
    bool disable_i2c_core_irq_mapping;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    int (*)(struct i2c_client *) remove;
    int (*)(struct i2c_client *) probe_new;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
    bool disable_i2c_core_irq_mapping;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    int (*)(struct i2c_client *) remove;
    int (*)(struct i2c_client *) probe_new;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
    bool disable_i2c_core_irq_mapping;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    int (*)(struct i2c_client *) remove;
    int (*)(struct i2c_client *) probe_new;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
    bool disable_i2c_core_irq_mapping;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    int (*)(struct i2c_client *) remove;
    int (*)(struct i2c_client *) probe_new;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
    bool disable_i2c_core_irq_mapping;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    int (*)(struct i2c_client *) remove;
    int (*)(struct i2c_client *) probe_new;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    int (*)(struct i2c_client *) remove;
    int (*)(struct i2c_client *) probe_new;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    int (*)(struct i2c_client *) remove;
    int (*)(struct i2c_client *) probe_new;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    int (*)(struct i2c_client *) remove;
    int (*)(struct i2c_client *) probe_new;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
    u32 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    void (*)(struct i2c_client *) remove;
    int (*)(struct i2c_client *) probe_new;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
    u32 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_client *) probe;
    int (*)(struct i2c_client *) probe_new;
    void (*)(struct i2c_client *) remove;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
    u32 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_client *) probe;
    void (*)(struct i2c_client *) remove;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
    u32 flags;
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
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    int (*)(struct i2c_client *) remove;
    int (*)(struct i2c_client *) probe_new;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
    bool disable_i2c_core_irq_mapping;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    int (*)(struct i2c_client *) remove;
    int (*)(struct i2c_client *) probe_new;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
    bool disable_i2c_core_irq_mapping;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    int (*)(struct i2c_client *) remove;
    int (*)(struct i2c_client *) probe_new;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
    bool disable_i2c_core_irq_mapping;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    int (*)(struct i2c_client *) remove;
    int (*)(struct i2c_client *) probe_new;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
    bool disable_i2c_core_irq_mapping;
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    int (*)(struct i2c_client *) remove;
    int (*)(struct i2c_client *) probe_new;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
    bool disable_i2c_core_irq_mapping;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    int (*)(struct i2c_client *) remove;
    int (*)(struct i2c_client *) probe_new;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
    bool disable_i2c_core_irq_mapping;
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
<b>Field type changed. </b>
<code>void (*)(struct i2c_client *, unsigned int) alert</code> ➡️ <code>void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert</code>
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
<code>int (*)(struct i2c_client *) probe_new</code>
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
<code>bool disable_i2c_core_irq_mapping</code>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct i2c_adapter *) attach_adapter</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool disable_i2c_core_irq_mapping</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
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
<code>u32 flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct i2c_client *) remove</code> ➡️ <code>void (*)(struct i2c_client *) remove</code>
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
<code>int (*)(struct i2c_client *, const struct i2c_device_id *) probe</code> ➡️ <code>int (*)(struct i2c_client *) probe</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct i2c_client *) probe_new</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    int (*)(struct i2c_client *) remove;
    int (*)(struct i2c_client *) probe_new;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
    bool disable_i2c_core_irq_mapping;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct i2c_driver {
    unsigned int class;
    int (*)(struct i2c_client *, const struct i2c_device_id *) probe;
    int (*)(struct i2c_client *) remove;
    int (*)(struct i2c_client *) probe_new;
    void (*)(struct i2c_client *) shutdown;
    void (*)(struct i2c_client *, enum i2c_alert_protocol, unsigned int) alert;
    int (*)(struct i2c_client *, unsigned int, void *) command;
    struct device_driver driver;
    const struct i2c_device_id * id_table;
    int (*)(struct i2c_client *, struct i2c_board_info *) detect;
    const short unsigned int * address_list;
    struct list_head clients;
    bool disable_i2c_core_irq_mapping;
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
