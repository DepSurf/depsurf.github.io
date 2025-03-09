# Struct: <code>cros_ec_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    bool was_wake_device;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    bool was_wake_device;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    bool was_wake_device;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
    bool mkbp_event_supported;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event event_data;
    int event_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    bool was_wake_device;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    bool suspended;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
    bool mkbp_event_supported;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event event_data;
    int event_size;
    u32 host_event_wake_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    bool was_wake_device;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    bool suspended;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
    bool mkbp_event_supported;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event event_data;
    int event_size;
    u32 host_event_wake_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    bool was_wake_device;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    bool suspended;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
    bool mkbp_event_supported;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event event_data;
    int event_size;
    u32 host_event_wake_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    bool was_wake_device;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    bool suspended;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
    bool mkbp_event_supported;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event_v1 event_data;
    int event_size;
    u32 host_event_wake_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    bool was_wake_device;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    bool suspended;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
    bool mkbp_event_supported;
    bool host_sleep_v1;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event_v1 event_data;
    int event_size;
    u32 host_event_wake_mask;
    u32 last_resume_result;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    bool was_wake_device;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    bool suspended;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
    bool mkbp_event_supported;
    bool host_sleep_v1;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event_v1 event_data;
    int event_size;
    u32 host_event_wake_mask;
    u32 last_resume_result;
    struct platform_device * ec;
    struct platform_device * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    bool was_wake_device;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    bool suspended;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
    u8 mkbp_event_supported;
    bool host_sleep_v1;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event_v1 event_data;
    int event_size;
    u32 host_event_wake_mask;
    u32 last_resume_result;
    ktime_t last_event_time;
    struct notifier_block notifier_ready;
    struct platform_device * ec;
    struct platform_device * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    bool was_wake_device;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    bool suspended;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
    u8 mkbp_event_supported;
    bool host_sleep_v1;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event_v1 event_data;
    int event_size;
    u32 host_event_wake_mask;
    u32 last_resume_result;
    ktime_t last_event_time;
    struct notifier_block notifier_ready;
    struct platform_device * ec;
    struct platform_device * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    bool was_wake_device;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    bool suspended;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
    u8 mkbp_event_supported;
    bool host_sleep_v1;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event_v1 event_data;
    int event_size;
    u32 host_event_wake_mask;
    u32 last_resume_result;
    ktime_t last_event_time;
    struct notifier_block notifier_ready;
    struct platform_device * ec;
    struct platform_device * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    bool was_wake_device;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    bool suspended;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
    u8 mkbp_event_supported;
    bool host_sleep_v1;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event_v1 event_data;
    int event_size;
    u32 host_event_wake_mask;
    u32 last_resume_result;
    ktime_t last_event_time;
    struct notifier_block notifier_ready;
    struct platform_device * ec;
    struct platform_device * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    bool suspended;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
    u8 mkbp_event_supported;
    bool host_sleep_v1;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event_v1 event_data;
    int event_size;
    u32 host_event_wake_mask;
    u32 last_resume_result;
    ktime_t last_event_time;
    struct notifier_block notifier_ready;
    struct platform_device * ec;
    struct platform_device * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    bool suspended;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
    u8 mkbp_event_supported;
    bool host_sleep_v1;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event_v1 event_data;
    int event_size;
    u32 host_event_wake_mask;
    u32 last_resume_result;
    u16 suspend_timeout_ms;
    ktime_t last_event_time;
    struct notifier_block notifier_ready;
    struct platform_device * ec;
    struct platform_device * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    bool suspended;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct lock_class_key lockdep_key;
    struct mutex lock;
    u8 mkbp_event_supported;
    bool host_sleep_v1;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event_v1 event_data;
    int event_size;
    u32 host_event_wake_mask;
    u32 last_resume_result;
    u16 suspend_timeout_ms;
    ktime_t last_event_time;
    struct notifier_block notifier_ready;
    struct platform_device * ec;
    struct platform_device * pd;
    struct blocking_notifier_head panic_notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    bool suspended;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct lock_class_key lockdep_key;
    struct mutex lock;
    u8 mkbp_event_supported;
    bool host_sleep_v1;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event_v1 event_data;
    int event_size;
    u32 host_event_wake_mask;
    u32 last_resume_result;
    u16 suspend_timeout_ms;
    ktime_t last_event_time;
    struct notifier_block notifier_ready;
    struct platform_device * ec;
    struct platform_device * pd;
    struct blocking_notifier_head panic_notifier;
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
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    bool was_wake_device;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    bool suspended;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
    bool mkbp_event_supported;
    bool host_sleep_v1;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event_v1 event_data;
    int event_size;
    u32 host_event_wake_mask;
    u32 last_resume_result;
    struct platform_device * ec;
    struct platform_device * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    bool was_wake_device;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    bool suspended;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
    bool mkbp_event_supported;
    bool host_sleep_v1;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event_v1 event_data;
    int event_size;
    u32 host_event_wake_mask;
    u32 last_resume_result;
    struct platform_device * ec;
    struct platform_device * pd;
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    bool was_wake_device;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    bool suspended;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
    bool mkbp_event_supported;
    bool host_sleep_v1;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event_v1 event_data;
    int event_size;
    u32 host_event_wake_mask;
    u32 last_resume_result;
    struct platform_device * ec;
    struct platform_device * pd;
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
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    bool was_wake_device;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    bool suspended;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
    bool mkbp_event_supported;
    bool host_sleep_v1;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event_v1 event_data;
    int event_size;
    u32 host_event_wake_mask;
    u32 last_resume_result;
    struct platform_device * ec;
    struct platform_device * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    bool was_wake_device;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    bool suspended;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
    bool mkbp_event_supported;
    bool host_sleep_v1;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event_v1 event_data;
    int event_size;
    u32 host_event_wake_mask;
    u32 last_resume_result;
    struct platform_device * ec;
    struct platform_device * pd;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool mkbp_event_supported</code>
</li>
<li>
<b>Field added. </b>
<code>struct blocking_notifier_head event_notifier</code>
</li>
<li>
<b>Field added. </b>
<code>struct ec_response_get_next_event event_data</code>
</li>
<li>
<b>Field added. </b>
<code>int event_size</code>
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
<code>bool suspended</code>
</li>
<li>
<b>Field added. </b>
<code>u32 host_event_wake_mask</code>
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
<b>Field type changed. </b>
<code>struct ec_response_get_next_event event_data</code> ➡️ <code>struct ec_response_get_next_event_v1 event_data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool host_sleep_v1</code>
</li>
<li>
<b>Field added. </b>
<code>u32 last_resume_result</code>
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
<code>struct platform_device * ec</code>
</li>
<li>
<b>Field added. </b>
<code>struct platform_device * pd</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>ktime_t last_event_time</code>
</li>
<li>
<b>Field added. </b>
<code>struct notifier_block notifier_ready</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool mkbp_event_supported</code> ➡️ <code>u8 mkbp_event_supported</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool was_wake_device</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u16 suspend_timeout_ms</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct lock_class_key lockdep_key</code>
</li>
<li>
<b>Field added. </b>
<code>struct blocking_notifier_head panic_notifier</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    bool was_wake_device;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    bool suspended;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
    bool mkbp_event_supported;
    bool host_sleep_v1;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event_v1 event_data;
    int event_size;
    u32 host_event_wake_mask;
    u32 last_resume_result;
    struct platform_device * ec;
    struct platform_device * pd;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    bool was_wake_device;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    bool suspended;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
    bool mkbp_event_supported;
    bool host_sleep_v1;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event_v1 event_data;
    int event_size;
    u32 host_event_wake_mask;
    u32 last_resume_result;
    struct platform_device * ec;
    struct platform_device * pd;
}
```
</details>
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
struct cros_ec_device {
    const char * phys_name;
    struct device * dev;
    bool was_wake_device;
    struct class * cros_class;
    int (*)(struct cros_ec_device *, unsigned int, unsigned int, void *) cmd_readmem;
    u16 max_request;
    u16 max_response;
    u16 max_passthru;
    u16 proto_version;
    void * priv;
    int irq;
    u8 * din;
    u8 * dout;
    int din_size;
    int dout_size;
    bool wake_enabled;
    bool suspended;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) cmd_xfer;
    int (*)(struct cros_ec_device *, struct cros_ec_command *) pkt_xfer;
    struct mutex lock;
    bool mkbp_event_supported;
    bool host_sleep_v1;
    struct blocking_notifier_head event_notifier;
    struct ec_response_get_next_event_v1 event_data;
    int event_size;
    u32 host_event_wake_mask;
    u32 last_resume_result;
    struct platform_device * ec;
    struct platform_device * pd;
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
