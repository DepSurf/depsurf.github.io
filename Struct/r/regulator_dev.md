# Struct: <code>regulator_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct blocking_notifier_head notifier;
    struct mutex mutex;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    int deferred_disables;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    long unsigned int last_off_jiffy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct blocking_notifier_head notifier;
    struct mutex mutex;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    int deferred_disables;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    long unsigned int last_off_jiffy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct blocking_notifier_head notifier;
    struct mutex mutex;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    int deferred_disables;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    long unsigned int last_off_jiffy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct blocking_notifier_head notifier;
    struct mutex mutex;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    int deferred_disables;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    unsigned int is_switch;
    long unsigned int last_off_jiffy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct blocking_notifier_head notifier;
    struct mutex mutex;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    int deferred_disables;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    unsigned int is_switch;
    long unsigned int last_off_jiffy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct coupling_desc coupling_desc;
    struct blocking_notifier_head notifier;
    struct mutex mutex;
    struct task_struct * mutex_owner;
    int ref_cnt;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    int deferred_disables;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    unsigned int is_switch;
    long unsigned int last_off_jiffy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct coupling_desc coupling_desc;
    struct blocking_notifier_head notifier;
    struct ww_mutex mutex;
    struct task_struct * mutex_owner;
    int ref_cnt;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    unsigned int is_switch;
    long unsigned int last_off_jiffy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct coupling_desc coupling_desc;
    struct blocking_notifier_head notifier;
    struct ww_mutex mutex;
    struct task_struct * mutex_owner;
    int ref_cnt;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    unsigned int is_switch;
    long unsigned int last_off_jiffy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct coupling_desc coupling_desc;
    struct blocking_notifier_head notifier;
    struct ww_mutex mutex;
    struct task_struct * mutex_owner;
    int ref_cnt;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    unsigned int is_switch;
    long unsigned int last_off_jiffy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct coupling_desc coupling_desc;
    struct blocking_notifier_head notifier;
    struct ww_mutex mutex;
    struct task_struct * mutex_owner;
    int ref_cnt;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    unsigned int is_switch;
    long unsigned int last_off_jiffy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct coupling_desc coupling_desc;
    struct blocking_notifier_head notifier;
    struct ww_mutex mutex;
    struct task_struct * mutex_owner;
    int ref_cnt;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    unsigned int is_switch;
    long unsigned int last_off_jiffy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct coupling_desc coupling_desc;
    struct blocking_notifier_head notifier;
    struct ww_mutex mutex;
    struct task_struct * mutex_owner;
    int ref_cnt;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    unsigned int is_switch;
    ktime_t last_off;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct coupling_desc coupling_desc;
    struct blocking_notifier_head notifier;
    struct ww_mutex mutex;
    struct task_struct * mutex_owner;
    int ref_cnt;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    unsigned int is_switch;
    ktime_t last_off;
    int cached_err;
    bool use_cached_err;
    spinlock_t err_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct coupling_desc coupling_desc;
    struct blocking_notifier_head notifier;
    struct ww_mutex mutex;
    struct task_struct * mutex_owner;
    int ref_cnt;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    unsigned int is_switch;
    ktime_t last_off;
    int cached_err;
    bool use_cached_err;
    spinlock_t err_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct coupling_desc coupling_desc;
    struct blocking_notifier_head notifier;
    struct ww_mutex mutex;
    struct task_struct * mutex_owner;
    int ref_cnt;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    unsigned int is_switch;
    ktime_t last_off;
    int cached_err;
    bool use_cached_err;
    spinlock_t err_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct coupling_desc coupling_desc;
    struct blocking_notifier_head notifier;
    struct ww_mutex mutex;
    struct task_struct * mutex_owner;
    int ref_cnt;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    unsigned int is_switch;
    ktime_t last_off;
    int cached_err;
    bool use_cached_err;
    spinlock_t err_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct coupling_desc coupling_desc;
    struct blocking_notifier_head notifier;
    struct ww_mutex mutex;
    struct task_struct * mutex_owner;
    int ref_cnt;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    unsigned int is_switch;
    ktime_t last_off;
    int cached_err;
    bool use_cached_err;
    spinlock_t err_lock;
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
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct coupling_desc coupling_desc;
    struct blocking_notifier_head notifier;
    struct ww_mutex mutex;
    struct task_struct * mutex_owner;
    int ref_cnt;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    unsigned int is_switch;
    long unsigned int last_off_jiffy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct coupling_desc coupling_desc;
    struct blocking_notifier_head notifier;
    struct ww_mutex mutex;
    struct task_struct * mutex_owner;
    int ref_cnt;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    unsigned int is_switch;
    long unsigned int last_off_jiffy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct coupling_desc coupling_desc;
    struct blocking_notifier_head notifier;
    struct ww_mutex mutex;
    struct task_struct * mutex_owner;
    int ref_cnt;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    unsigned int is_switch;
    long unsigned int last_off_jiffy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct coupling_desc coupling_desc;
    struct blocking_notifier_head notifier;
    struct ww_mutex mutex;
    struct task_struct * mutex_owner;
    int ref_cnt;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    unsigned int is_switch;
    long unsigned int last_off_jiffy;
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
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct coupling_desc coupling_desc;
    struct blocking_notifier_head notifier;
    struct ww_mutex mutex;
    struct task_struct * mutex_owner;
    int ref_cnt;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    unsigned int is_switch;
    long unsigned int last_off_jiffy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct coupling_desc coupling_desc;
    struct blocking_notifier_head notifier;
    struct ww_mutex mutex;
    struct task_struct * mutex_owner;
    int ref_cnt;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    unsigned int is_switch;
    long unsigned int last_off_jiffy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct coupling_desc coupling_desc;
    struct blocking_notifier_head notifier;
    struct ww_mutex mutex;
    struct task_struct * mutex_owner;
    int ref_cnt;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    unsigned int is_switch;
    long unsigned int last_off_jiffy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct regulator_dev {
    const struct regulator_desc * desc;
    int exclusive;
    u32 use_count;
    u32 open_count;
    u32 bypass_count;
    struct list_head list;
    struct list_head consumer_list;
    struct coupling_desc coupling_desc;
    struct blocking_notifier_head notifier;
    struct ww_mutex mutex;
    struct task_struct * mutex_owner;
    int ref_cnt;
    struct module * owner;
    struct device dev;
    struct regulation_constraints * constraints;
    struct regulator * supply;
    const char * supply_name;
    struct regmap * regmap;
    struct delayed_work disable_work;
    void * reg_data;
    struct dentry * debugfs;
    struct regulator_enable_gpio * ena_pin;
    unsigned int ena_gpio_state;
    unsigned int is_switch;
    long unsigned int last_off_jiffy;
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
<code>unsigned int is_switch</code>
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
<code>struct coupling_desc coupling_desc</code>
</li>
<li>
<b>Field added. </b>
<code>struct task_struct * mutex_owner</code>
</li>
<li>
<b>Field added. </b>
<code>int ref_cnt</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int deferred_disables</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct mutex mutex</code> ➡️ <code>struct ww_mutex mutex</code>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>ktime_t last_off</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int last_off_jiffy</code>
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
<code>int cached_err</code>
</li>
<li>
<b>Field added. </b>
<code>bool use_cached_err</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t err_lock</code>
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
