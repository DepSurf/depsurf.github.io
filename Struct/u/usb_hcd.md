# Struct: <code>usb_hcd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct phy * phy;
    long unsigned int flags;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int remove_phy;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    long unsigned int[0] hcd_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct phy * phy;
    long unsigned int flags;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int remove_phy;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    long unsigned int[0] hcd_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct phy * phy;
    long unsigned int flags;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int remove_phy;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    long unsigned int[0] hcd_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct phy * phy;
    long unsigned int flags;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int msi_enabled;
    unsigned int remove_phy;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    long unsigned int[0] hcd_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct phy * phy;
    long unsigned int flags;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int msi_enabled;
    unsigned int remove_phy;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    long unsigned int[0] hcd_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct usb_phy_roothub * phy_roothub;
    long unsigned int flags;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int msi_enabled;
    unsigned int skip_phy_initialization;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    long unsigned int[0] hcd_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct usb_phy_roothub * phy_roothub;
    long unsigned int flags;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int msi_enabled;
    unsigned int skip_phy_initialization;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    long unsigned int[0] hcd_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    struct work_struct died_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct usb_phy_roothub * phy_roothub;
    long unsigned int flags;
    enum usb_dev_authorize_policy dev_policy;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int msi_enabled;
    unsigned int skip_phy_initialization;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    struct gen_pool * localmem_pool;
    long unsigned int[0] hcd_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    struct work_struct died_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct usb_phy_roothub * phy_roothub;
    long unsigned int flags;
    enum usb_dev_authorize_policy dev_policy;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int msi_enabled;
    unsigned int skip_phy_initialization;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    struct gen_pool * localmem_pool;
    long unsigned int[0] hcd_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    struct work_struct died_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct usb_phy_roothub * phy_roothub;
    long unsigned int flags;
    enum usb_dev_authorize_policy dev_policy;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int msi_enabled;
    unsigned int skip_phy_initialization;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    struct gen_pool * localmem_pool;
    long unsigned int[0] hcd_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    struct work_struct died_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct usb_phy_roothub * phy_roothub;
    long unsigned int flags;
    enum usb_dev_authorize_policy dev_policy;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int msi_enabled;
    unsigned int skip_phy_initialization;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    struct gen_pool * localmem_pool;
    long unsigned int[0] hcd_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    struct work_struct died_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct usb_phy_roothub * phy_roothub;
    long unsigned int flags;
    enum usb_dev_authorize_policy dev_policy;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int msi_enabled;
    unsigned int skip_phy_initialization;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    struct gen_pool * localmem_pool;
    long unsigned int[0] hcd_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    struct work_struct died_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct usb_phy_roothub * phy_roothub;
    long unsigned int flags;
    enum usb_dev_authorize_policy dev_policy;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int msi_enabled;
    unsigned int skip_phy_initialization;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    struct gen_pool * localmem_pool;
    long unsigned int[0] hcd_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    struct work_struct died_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct usb_phy_roothub * phy_roothub;
    long unsigned int flags;
    enum usb_dev_authorize_policy dev_policy;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int msi_enabled;
    unsigned int skip_phy_initialization;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    struct gen_pool * localmem_pool;
    long unsigned int[0] hcd_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    struct work_struct died_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct usb_phy_roothub * phy_roothub;
    long unsigned int flags;
    enum usb_dev_authorize_policy dev_policy;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int msi_enabled;
    unsigned int skip_phy_initialization;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    struct gen_pool * localmem_pool;
    long unsigned int[0] hcd_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    struct work_struct died_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct usb_phy_roothub * phy_roothub;
    long unsigned int flags;
    enum usb_dev_authorize_policy dev_policy;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int msi_enabled;
    unsigned int skip_phy_initialization;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    struct gen_pool * localmem_pool;
    long unsigned int[0] hcd_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    struct work_struct died_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct usb_phy_roothub * phy_roothub;
    long unsigned int flags;
    enum usb_dev_authorize_policy dev_policy;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int msi_enabled;
    unsigned int skip_phy_initialization;
    unsigned int uses_new_polling;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    struct gen_pool * localmem_pool;
    long unsigned int[0] hcd_priv;
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
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    struct work_struct died_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct usb_phy_roothub * phy_roothub;
    long unsigned int flags;
    enum usb_dev_authorize_policy dev_policy;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int msi_enabled;
    unsigned int skip_phy_initialization;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    struct gen_pool * localmem_pool;
    long unsigned int[0] hcd_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    struct work_struct died_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct usb_phy_roothub * phy_roothub;
    long unsigned int flags;
    enum usb_dev_authorize_policy dev_policy;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int msi_enabled;
    unsigned int skip_phy_initialization;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    struct gen_pool * localmem_pool;
    long unsigned int[0] hcd_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    struct work_struct died_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct usb_phy_roothub * phy_roothub;
    long unsigned int flags;
    enum usb_dev_authorize_policy dev_policy;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int msi_enabled;
    unsigned int skip_phy_initialization;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    struct gen_pool * localmem_pool;
    long unsigned int[0] hcd_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    struct work_struct died_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct usb_phy_roothub * phy_roothub;
    long unsigned int flags;
    enum usb_dev_authorize_policy dev_policy;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int msi_enabled;
    unsigned int skip_phy_initialization;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    struct gen_pool * localmem_pool;
    long unsigned int[0] hcd_priv;
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
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    struct work_struct died_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct usb_phy_roothub * phy_roothub;
    long unsigned int flags;
    enum usb_dev_authorize_policy dev_policy;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int msi_enabled;
    unsigned int skip_phy_initialization;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    struct gen_pool * localmem_pool;
    long unsigned int[0] hcd_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    struct work_struct died_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct usb_phy_roothub * phy_roothub;
    long unsigned int flags;
    enum usb_dev_authorize_policy dev_policy;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int msi_enabled;
    unsigned int skip_phy_initialization;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    struct gen_pool * localmem_pool;
    long unsigned int[0] hcd_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    struct work_struct died_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct usb_phy_roothub * phy_roothub;
    long unsigned int flags;
    enum usb_dev_authorize_policy dev_policy;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int msi_enabled;
    unsigned int skip_phy_initialization;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    struct gen_pool * localmem_pool;
    long unsigned int[0] hcd_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct usb_hcd {
    struct usb_bus self;
    struct kref kref;
    const char * product_desc;
    int speed;
    char[24] irq_descr;
    struct timer_list rh_timer;
    struct urb * status_urb;
    struct work_struct wakeup_work;
    struct work_struct died_work;
    const struct hc_driver * driver;
    struct usb_phy * usb_phy;
    struct usb_phy_roothub * phy_roothub;
    long unsigned int flags;
    enum usb_dev_authorize_policy dev_policy;
    unsigned int rh_registered;
    unsigned int rh_pollable;
    unsigned int msix_enabled;
    unsigned int msi_enabled;
    unsigned int skip_phy_initialization;
    unsigned int uses_new_polling;
    unsigned int wireless;
    unsigned int has_tt;
    unsigned int amd_resume_bug;
    unsigned int can_do_streams;
    unsigned int tpl_support;
    unsigned int cant_recv_wakeups;
    unsigned int irq;
    void * regs;
    resource_size_t rsrc_start;
    resource_size_t rsrc_len;
    unsigned int power_budget;
    struct giveback_urb_bh high_prio_bh;
    struct giveback_urb_bh low_prio_bh;
    struct mutex * address0_mutex;
    struct mutex * bandwidth_mutex;
    struct usb_hcd * shared_hcd;
    struct usb_hcd * primary_hcd;
    struct dma_pool *[4] pool;
    int state;
    struct gen_pool * localmem_pool;
    long unsigned int[0] hcd_priv;
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
<code>struct mutex * address0_mutex</code>
</li>
</ul>
</details>
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
<code>unsigned int msi_enabled</code>
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
<code>struct usb_phy_roothub * phy_roothub</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int skip_phy_initialization</code>
</li>
<li>
<b>Field removed. </b>
<code>struct phy * phy</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int remove_phy</code>
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
<code>struct work_struct died_work</code>
</li>
<li>
<b>Field added. </b>
<code>enum usb_dev_authorize_policy dev_policy</code>
</li>
<li>
<b>Field added. </b>
<code>struct gen_pool * localmem_pool</code>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int wireless</code>
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
