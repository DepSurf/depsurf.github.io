# Struct: <code>usb_dev_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    wait_queue_head_t wait;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    void * disccontext;
    long unsigned int ifclaimed;
    u32 secid;
    u32 disabled_bulk_eps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    void * disccontext;
    long unsigned int ifclaimed;
    u32 secid;
    u32 disabled_bulk_eps;
    bool privileges_dropped;
    long unsigned int interface_allowed_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    void * disccontext;
    long unsigned int ifclaimed;
    u32 secid;
    u32 disabled_bulk_eps;
    bool privileges_dropped;
    long unsigned int interface_allowed_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    void * disccontext;
    long unsigned int ifclaimed;
    u32 secid;
    u32 disabled_bulk_eps;
    bool privileges_dropped;
    long unsigned int interface_allowed_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    void * disccontext;
    long unsigned int ifclaimed;
    u32 secid;
    u32 disabled_bulk_eps;
    bool privileges_dropped;
    long unsigned int interface_allowed_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    void * disccontext;
    long unsigned int ifclaimed;
    u32 disabled_bulk_eps;
    bool privileges_dropped;
    long unsigned int interface_allowed_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    void * disccontext;
    long unsigned int ifclaimed;
    u32 disabled_bulk_eps;
    bool privileges_dropped;
    long unsigned int interface_allowed_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    sigval_t disccontext;
    long unsigned int ifclaimed;
    u32 disabled_bulk_eps;
    bool privileges_dropped;
    long unsigned int interface_allowed_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    wait_queue_head_t wait_for_resume;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    sigval_t disccontext;
    long unsigned int ifclaimed;
    u32 disabled_bulk_eps;
    long unsigned int interface_allowed_mask;
    int not_yet_resumed;
    bool suspend_allowed;
    bool privileges_dropped;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    wait_queue_head_t wait_for_resume;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    sigval_t disccontext;
    long unsigned int ifclaimed;
    u32 disabled_bulk_eps;
    long unsigned int interface_allowed_mask;
    int not_yet_resumed;
    bool suspend_allowed;
    bool privileges_dropped;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    wait_queue_head_t wait_for_resume;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    sigval_t disccontext;
    long unsigned int ifclaimed;
    u32 disabled_bulk_eps;
    long unsigned int interface_allowed_mask;
    int not_yet_resumed;
    bool suspend_allowed;
    bool privileges_dropped;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    wait_queue_head_t wait_for_resume;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    sigval_t disccontext;
    long unsigned int ifclaimed;
    u32 disabled_bulk_eps;
    long unsigned int interface_allowed_mask;
    int not_yet_resumed;
    bool suspend_allowed;
    bool privileges_dropped;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    wait_queue_head_t wait_for_resume;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    sigval_t disccontext;
    long unsigned int ifclaimed;
    u32 disabled_bulk_eps;
    long unsigned int interface_allowed_mask;
    int not_yet_resumed;
    bool suspend_allowed;
    bool privileges_dropped;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    wait_queue_head_t wait_for_resume;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    sigval_t disccontext;
    long unsigned int ifclaimed;
    u32 disabled_bulk_eps;
    long unsigned int interface_allowed_mask;
    int not_yet_resumed;
    bool suspend_allowed;
    bool privileges_dropped;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    wait_queue_head_t wait_for_resume;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    sigval_t disccontext;
    long unsigned int ifclaimed;
    u32 disabled_bulk_eps;
    long unsigned int interface_allowed_mask;
    int not_yet_resumed;
    bool suspend_allowed;
    bool privileges_dropped;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    wait_queue_head_t wait_for_resume;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    sigval_t disccontext;
    long unsigned int ifclaimed;
    u32 disabled_bulk_eps;
    long unsigned int interface_allowed_mask;
    int not_yet_resumed;
    bool suspend_allowed;
    bool privileges_dropped;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    wait_queue_head_t wait_for_resume;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    sigval_t disccontext;
    long unsigned int ifclaimed;
    u32 disabled_bulk_eps;
    long unsigned int interface_allowed_mask;
    int not_yet_resumed;
    bool suspend_allowed;
    bool privileges_dropped;
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
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    wait_queue_head_t wait_for_resume;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    sigval_t disccontext;
    long unsigned int ifclaimed;
    u32 disabled_bulk_eps;
    long unsigned int interface_allowed_mask;
    int not_yet_resumed;
    bool suspend_allowed;
    bool privileges_dropped;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    wait_queue_head_t wait_for_resume;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    sigval_t disccontext;
    long unsigned int ifclaimed;
    u32 disabled_bulk_eps;
    long unsigned int interface_allowed_mask;
    int not_yet_resumed;
    bool suspend_allowed;
    bool privileges_dropped;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    wait_queue_head_t wait_for_resume;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    sigval_t disccontext;
    long unsigned int ifclaimed;
    u32 disabled_bulk_eps;
    long unsigned int interface_allowed_mask;
    int not_yet_resumed;
    bool suspend_allowed;
    bool privileges_dropped;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    wait_queue_head_t wait_for_resume;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    sigval_t disccontext;
    long unsigned int ifclaimed;
    u32 disabled_bulk_eps;
    long unsigned int interface_allowed_mask;
    int not_yet_resumed;
    bool suspend_allowed;
    bool privileges_dropped;
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
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    wait_queue_head_t wait_for_resume;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    sigval_t disccontext;
    long unsigned int ifclaimed;
    u32 disabled_bulk_eps;
    long unsigned int interface_allowed_mask;
    int not_yet_resumed;
    bool suspend_allowed;
    bool privileges_dropped;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    wait_queue_head_t wait_for_resume;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    sigval_t disccontext;
    long unsigned int ifclaimed;
    u32 disabled_bulk_eps;
    long unsigned int interface_allowed_mask;
    int not_yet_resumed;
    bool suspend_allowed;
    bool privileges_dropped;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    wait_queue_head_t wait_for_resume;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    sigval_t disccontext;
    long unsigned int ifclaimed;
    u32 disabled_bulk_eps;
    long unsigned int interface_allowed_mask;
    int not_yet_resumed;
    bool suspend_allowed;
    bool privileges_dropped;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct usb_dev_state {
    struct list_head list;
    struct usb_device * dev;
    struct file * file;
    spinlock_t lock;
    struct list_head async_pending;
    struct list_head async_completed;
    struct list_head memory_list;
    wait_queue_head_t wait;
    wait_queue_head_t wait_for_resume;
    unsigned int discsignr;
    struct pid * disc_pid;
    const struct cred * cred;
    sigval_t disccontext;
    long unsigned int ifclaimed;
    u32 disabled_bulk_eps;
    long unsigned int interface_allowed_mask;
    int not_yet_resumed;
    bool suspend_allowed;
    bool privileges_dropped;
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
<code>struct list_head memory_list</code>
</li>
<li>
<b>Field added. </b>
<code>bool privileges_dropped</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int interface_allowed_mask</code>
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
<b>Field removed. </b>
<code>u32 secid</code>
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
<b>Field type changed. </b>
<code>void * disccontext</code> ➡️ <code>sigval_t disccontext</code>
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
<code>wait_queue_head_t wait_for_resume</code>
</li>
<li>
<b>Field added. </b>
<code>int not_yet_resumed</code>
</li>
<li>
<b>Field added. </b>
<code>bool suspend_allowed</code>
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
