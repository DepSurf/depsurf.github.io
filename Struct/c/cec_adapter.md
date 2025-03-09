# Struct: <code>cec_adapter</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cec_adapter {
    struct module * owner;
    char[32] name;
    struct cec_devnode devnode;
    struct mutex lock;
    struct rc_dev * rc;
    struct list_head transmit_queue;
    unsigned int transmit_queue_sz;
    struct list_head wait_queue;
    struct cec_data * transmitting;
    bool transmit_in_progress;
    struct task_struct * kthread_config;
    struct completion config_completion;
    struct task_struct * kthread;
    wait_queue_head_t kthread_waitq;
    wait_queue_head_t waitq;
    const struct cec_adap_ops * ops;
    void * priv;
    u32 capabilities;
    u8 available_log_addrs;
    u16 phys_addr;
    bool needs_hpd;
    bool is_configuring;
    bool is_configured;
    bool cec_pin_is_high;
    u8 last_initiator;
    u32 monitor_all_cnt;
    u32 monitor_pin_cnt;
    u32 follower_cnt;
    struct cec_fh * cec_follower;
    struct cec_fh * cec_initiator;
    bool passthrough;
    struct cec_log_addrs log_addrs;
    u32 tx_timeouts;
    struct cec_notifier * notifier;
    struct dentry * cec_dir;
    struct dentry * status_file;
    struct dentry * error_inj_file;
    u16[15] phys_addrs;
    u32 sequence;
    char[32] input_phys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cec_adapter {
    struct module * owner;
    char[32] name;
    struct cec_devnode devnode;
    struct mutex lock;
    struct rc_dev * rc;
    struct list_head transmit_queue;
    unsigned int transmit_queue_sz;
    struct list_head wait_queue;
    struct cec_data * transmitting;
    bool transmit_in_progress;
    struct task_struct * kthread_config;
    struct completion config_completion;
    struct task_struct * kthread;
    wait_queue_head_t kthread_waitq;
    wait_queue_head_t waitq;
    const struct cec_adap_ops * ops;
    void * priv;
    u32 capabilities;
    u8 available_log_addrs;
    u16 phys_addr;
    bool needs_hpd;
    bool is_configuring;
    bool is_configured;
    bool cec_pin_is_high;
    u8 last_initiator;
    u32 monitor_all_cnt;
    u32 monitor_pin_cnt;
    u32 follower_cnt;
    struct cec_fh * cec_follower;
    struct cec_fh * cec_initiator;
    bool passthrough;
    struct cec_log_addrs log_addrs;
    struct cec_connector_info conn_info;
    u32 tx_timeouts;
    struct cec_notifier * notifier;
    struct dentry * cec_dir;
    struct dentry * status_file;
    struct dentry * error_inj_file;
    u16[15] phys_addrs;
    u32 sequence;
    char[32] input_phys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cec_adapter {
    struct module * owner;
    char[32] name;
    struct cec_devnode devnode;
    struct mutex lock;
    struct rc_dev * rc;
    struct list_head transmit_queue;
    unsigned int transmit_queue_sz;
    struct list_head wait_queue;
    struct cec_data * transmitting;
    bool transmit_in_progress;
    struct task_struct * kthread_config;
    struct completion config_completion;
    struct task_struct * kthread;
    wait_queue_head_t kthread_waitq;
    wait_queue_head_t waitq;
    const struct cec_adap_ops * ops;
    void * priv;
    u32 capabilities;
    u8 available_log_addrs;
    u16 phys_addr;
    bool needs_hpd;
    bool is_configuring;
    bool is_configured;
    bool cec_pin_is_high;
    u8 last_initiator;
    u32 monitor_all_cnt;
    u32 monitor_pin_cnt;
    u32 follower_cnt;
    struct cec_fh * cec_follower;
    struct cec_fh * cec_initiator;
    bool passthrough;
    struct cec_log_addrs log_addrs;
    struct cec_connector_info conn_info;
    u32 tx_timeouts;
    struct cec_notifier * notifier;
    struct dentry * cec_dir;
    struct dentry * status_file;
    struct dentry * error_inj_file;
    u16[15] phys_addrs;
    u32 sequence;
    char[32] input_phys;
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct cec_adapter {
    struct module * owner;
    char[32] name;
    struct cec_devnode devnode;
    struct mutex lock;
    struct rc_dev * rc;
    struct list_head transmit_queue;
    unsigned int transmit_queue_sz;
    struct list_head wait_queue;
    struct cec_data * transmitting;
    bool transmit_in_progress;
    struct task_struct * kthread_config;
    struct completion config_completion;
    struct task_struct * kthread;
    wait_queue_head_t kthread_waitq;
    wait_queue_head_t waitq;
    const struct cec_adap_ops * ops;
    void * priv;
    u32 capabilities;
    u8 available_log_addrs;
    u16 phys_addr;
    bool needs_hpd;
    bool is_configuring;
    bool is_configured;
    bool cec_pin_is_high;
    u8 last_initiator;
    u32 monitor_all_cnt;
    u32 monitor_pin_cnt;
    u32 follower_cnt;
    struct cec_fh * cec_follower;
    struct cec_fh * cec_initiator;
    bool passthrough;
    struct cec_log_addrs log_addrs;
    struct cec_connector_info conn_info;
    u32 tx_timeouts;
    struct cec_notifier * notifier;
    struct cec_pin * pin;
    struct dentry * cec_dir;
    struct dentry * status_file;
    struct dentry * error_inj_file;
    u16[15] phys_addrs;
    u32 sequence;
    char[32] input_phys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cec_adapter {
    struct module * owner;
    char[32] name;
    struct cec_devnode devnode;
    struct mutex lock;
    struct rc_dev * rc;
    struct list_head transmit_queue;
    unsigned int transmit_queue_sz;
    struct list_head wait_queue;
    struct cec_data * transmitting;
    bool transmit_in_progress;
    struct task_struct * kthread_config;
    struct completion config_completion;
    struct task_struct * kthread;
    wait_queue_head_t kthread_waitq;
    wait_queue_head_t waitq;
    const struct cec_adap_ops * ops;
    void * priv;
    u32 capabilities;
    u8 available_log_addrs;
    u16 phys_addr;
    bool needs_hpd;
    bool is_configuring;
    bool is_configured;
    bool cec_pin_is_high;
    u8 last_initiator;
    u32 monitor_all_cnt;
    u32 monitor_pin_cnt;
    u32 follower_cnt;
    struct cec_fh * cec_follower;
    struct cec_fh * cec_initiator;
    bool passthrough;
    struct cec_log_addrs log_addrs;
    struct cec_connector_info conn_info;
    u32 tx_timeouts;
    struct cec_notifier * notifier;
    struct dentry * cec_dir;
    struct dentry * status_file;
    struct dentry * error_inj_file;
    u16[15] phys_addrs;
    u32 sequence;
    char[32] input_phys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cec_adapter {
    struct module * owner;
    char[32] name;
    struct cec_devnode devnode;
    struct mutex lock;
    struct rc_dev * rc;
    struct list_head transmit_queue;
    unsigned int transmit_queue_sz;
    struct list_head wait_queue;
    struct cec_data * transmitting;
    bool transmit_in_progress;
    struct task_struct * kthread_config;
    struct completion config_completion;
    struct task_struct * kthread;
    wait_queue_head_t kthread_waitq;
    wait_queue_head_t waitq;
    const struct cec_adap_ops * ops;
    void * priv;
    u32 capabilities;
    u8 available_log_addrs;
    u16 phys_addr;
    bool needs_hpd;
    bool is_configuring;
    bool is_configured;
    bool cec_pin_is_high;
    u8 last_initiator;
    u32 monitor_all_cnt;
    u32 monitor_pin_cnt;
    u32 follower_cnt;
    struct cec_fh * cec_follower;
    struct cec_fh * cec_initiator;
    bool passthrough;
    struct cec_log_addrs log_addrs;
    struct cec_connector_info conn_info;
    u32 tx_timeouts;
    struct cec_notifier * notifier;
    struct dentry * cec_dir;
    struct dentry * status_file;
    struct dentry * error_inj_file;
    u16[15] phys_addrs;
    u32 sequence;
    char[32] input_phys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cec_adapter {
    struct module * owner;
    char[32] name;
    struct cec_devnode devnode;
    struct mutex lock;
    struct rc_dev * rc;
    struct list_head transmit_queue;
    unsigned int transmit_queue_sz;
    struct list_head wait_queue;
    struct cec_data * transmitting;
    bool transmit_in_progress;
    struct task_struct * kthread_config;
    struct completion config_completion;
    struct task_struct * kthread;
    wait_queue_head_t kthread_waitq;
    wait_queue_head_t waitq;
    const struct cec_adap_ops * ops;
    void * priv;
    u32 capabilities;
    u8 available_log_addrs;
    u16 phys_addr;
    bool needs_hpd;
    bool is_configuring;
    bool is_configured;
    bool cec_pin_is_high;
    u8 last_initiator;
    u32 monitor_all_cnt;
    u32 monitor_pin_cnt;
    u32 follower_cnt;
    struct cec_fh * cec_follower;
    struct cec_fh * cec_initiator;
    bool passthrough;
    struct cec_log_addrs log_addrs;
    struct cec_connector_info conn_info;
    u32 tx_timeouts;
    struct cec_notifier * notifier;
    struct dentry * cec_dir;
    struct dentry * status_file;
    struct dentry * error_inj_file;
    u16[15] phys_addrs;
    u32 sequence;
    char[32] input_phys;
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
struct cec_adapter {
    struct module * owner;
    char[32] name;
    struct cec_devnode devnode;
    struct mutex lock;
    struct rc_dev * rc;
    struct list_head transmit_queue;
    unsigned int transmit_queue_sz;
    struct list_head wait_queue;
    struct cec_data * transmitting;
    bool transmit_in_progress;
    struct task_struct * kthread_config;
    struct completion config_completion;
    struct task_struct * kthread;
    wait_queue_head_t kthread_waitq;
    wait_queue_head_t waitq;
    const struct cec_adap_ops * ops;
    void * priv;
    u32 capabilities;
    u8 available_log_addrs;
    u16 phys_addr;
    bool needs_hpd;
    bool is_configuring;
    bool is_configured;
    bool cec_pin_is_high;
    u8 last_initiator;
    u32 monitor_all_cnt;
    u32 monitor_pin_cnt;
    u32 follower_cnt;
    struct cec_fh * cec_follower;
    struct cec_fh * cec_initiator;
    bool passthrough;
    struct cec_log_addrs log_addrs;
    struct cec_connector_info conn_info;
    u32 tx_timeouts;
    struct cec_notifier * notifier;
    struct dentry * cec_dir;
    struct dentry * status_file;
    struct dentry * error_inj_file;
    u16[15] phys_addrs;
    u32 sequence;
    char[32] input_phys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cec_adapter {
    struct module * owner;
    char[32] name;
    struct cec_devnode devnode;
    struct mutex lock;
    struct rc_dev * rc;
    struct list_head transmit_queue;
    unsigned int transmit_queue_sz;
    struct list_head wait_queue;
    struct cec_data * transmitting;
    bool transmit_in_progress;
    struct task_struct * kthread_config;
    struct completion config_completion;
    struct task_struct * kthread;
    wait_queue_head_t kthread_waitq;
    wait_queue_head_t waitq;
    const struct cec_adap_ops * ops;
    void * priv;
    u32 capabilities;
    u8 available_log_addrs;
    u16 phys_addr;
    bool needs_hpd;
    bool is_configuring;
    bool is_configured;
    bool cec_pin_is_high;
    u8 last_initiator;
    u32 monitor_all_cnt;
    u32 monitor_pin_cnt;
    u32 follower_cnt;
    struct cec_fh * cec_follower;
    struct cec_fh * cec_initiator;
    bool passthrough;
    struct cec_log_addrs log_addrs;
    struct cec_connector_info conn_info;
    u32 tx_timeouts;
    struct cec_notifier * notifier;
    struct dentry * cec_dir;
    struct dentry * status_file;
    struct dentry * error_inj_file;
    u16[15] phys_addrs;
    u32 sequence;
    char[32] input_phys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cec_adapter {
    struct module * owner;
    char[32] name;
    struct cec_devnode devnode;
    struct mutex lock;
    struct rc_dev * rc;
    struct list_head transmit_queue;
    unsigned int transmit_queue_sz;
    struct list_head wait_queue;
    struct cec_data * transmitting;
    bool transmit_in_progress;
    struct task_struct * kthread_config;
    struct completion config_completion;
    struct task_struct * kthread;
    wait_queue_head_t kthread_waitq;
    wait_queue_head_t waitq;
    const struct cec_adap_ops * ops;
    void * priv;
    u32 capabilities;
    u8 available_log_addrs;
    u16 phys_addr;
    bool needs_hpd;
    bool is_configuring;
    bool is_configured;
    bool cec_pin_is_high;
    u8 last_initiator;
    u32 monitor_all_cnt;
    u32 monitor_pin_cnt;
    u32 follower_cnt;
    struct cec_fh * cec_follower;
    struct cec_fh * cec_initiator;
    bool passthrough;
    struct cec_log_addrs log_addrs;
    struct cec_connector_info conn_info;
    u32 tx_timeouts;
    struct cec_notifier * notifier;
    struct dentry * cec_dir;
    struct dentry * status_file;
    struct dentry * error_inj_file;
    u16[15] phys_addrs;
    u32 sequence;
    char[32] input_phys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cec_adapter {
    struct module * owner;
    char[32] name;
    struct cec_devnode devnode;
    struct mutex lock;
    struct rc_dev * rc;
    struct list_head transmit_queue;
    unsigned int transmit_queue_sz;
    struct list_head wait_queue;
    struct cec_data * transmitting;
    bool transmit_in_progress;
    struct task_struct * kthread_config;
    struct completion config_completion;
    struct task_struct * kthread;
    wait_queue_head_t kthread_waitq;
    wait_queue_head_t waitq;
    const struct cec_adap_ops * ops;
    void * priv;
    u32 capabilities;
    u8 available_log_addrs;
    u16 phys_addr;
    bool needs_hpd;
    bool is_configuring;
    bool is_configured;
    bool cec_pin_is_high;
    u8 last_initiator;
    u32 monitor_all_cnt;
    u32 monitor_pin_cnt;
    u32 follower_cnt;
    struct cec_fh * cec_follower;
    struct cec_fh * cec_initiator;
    bool passthrough;
    struct cec_log_addrs log_addrs;
    struct cec_connector_info conn_info;
    u32 tx_timeouts;
    struct cec_notifier * notifier;
    struct cec_pin * pin;
    struct dentry * cec_dir;
    struct dentry * status_file;
    struct dentry * error_inj_file;
    u16[15] phys_addrs;
    u32 sequence;
    char[32] input_phys;
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct cec_adapter {
    struct module * owner;
    char[32] name;
    struct cec_devnode devnode;
    struct mutex lock;
    struct rc_dev * rc;
    struct list_head transmit_queue;
    unsigned int transmit_queue_sz;
    struct list_head wait_queue;
    struct cec_data * transmitting;
    bool transmit_in_progress;
    struct task_struct * kthread_config;
    struct completion config_completion;
    struct task_struct * kthread;
    wait_queue_head_t kthread_waitq;
    wait_queue_head_t waitq;
    const struct cec_adap_ops * ops;
    void * priv;
    u32 capabilities;
    u8 available_log_addrs;
    u16 phys_addr;
    bool needs_hpd;
    bool is_configuring;
    bool is_configured;
    bool cec_pin_is_high;
    u8 last_initiator;
    u32 monitor_all_cnt;
    u32 monitor_pin_cnt;
    u32 follower_cnt;
    struct cec_fh * cec_follower;
    struct cec_fh * cec_initiator;
    bool passthrough;
    struct cec_log_addrs log_addrs;
    u32 tx_timeouts;
    struct cec_notifier * notifier;
    struct dentry * cec_dir;
    struct dentry * status_file;
    struct dentry * error_inj_file;
    u16[15] phys_addrs;
    u32 sequence;
    char[32] input_phys;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct cec_connector_info conn_info</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct cec_adapter {
    struct module * owner;
    char[32] name;
    struct cec_devnode devnode;
    struct mutex lock;
    struct rc_dev * rc;
    struct list_head transmit_queue;
    unsigned int transmit_queue_sz;
    struct list_head wait_queue;
    struct cec_data * transmitting;
    bool transmit_in_progress;
    struct task_struct * kthread_config;
    struct completion config_completion;
    struct task_struct * kthread;
    wait_queue_head_t kthread_waitq;
    wait_queue_head_t waitq;
    const struct cec_adap_ops * ops;
    void * priv;
    u32 capabilities;
    u8 available_log_addrs;
    u16 phys_addr;
    bool needs_hpd;
    bool is_configuring;
    bool is_configured;
    bool cec_pin_is_high;
    u8 last_initiator;
    u32 monitor_all_cnt;
    u32 monitor_pin_cnt;
    u32 follower_cnt;
    struct cec_fh * cec_follower;
    struct cec_fh * cec_initiator;
    bool passthrough;
    struct cec_log_addrs log_addrs;
    struct cec_connector_info conn_info;
    u32 tx_timeouts;
    struct cec_notifier * notifier;
    struct dentry * cec_dir;
    struct dentry * status_file;
    struct dentry * error_inj_file;
    u16[15] phys_addrs;
    u32 sequence;
    char[32] input_phys;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct cec_pin * pin</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct cec_pin * pin</code>
</li>
</ul>
</details>
</li>
</ul>
