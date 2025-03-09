# Struct: <code>device_link</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    enum device_link_state status;
    u32 flags;
    bool rpm_active;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    enum device_link_state status;
    u32 flags;
    bool rpm_active;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    enum device_link_state status;
    u32 flags;
    bool rpm_active;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    enum device_link_state status;
    u32 flags;
    bool rpm_active;
    struct kref kref;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    enum device_link_state status;
    u32 flags;
    bool rpm_active;
    struct kref kref;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    enum device_link_state status;
    u32 flags;
    refcount_t rpm_active;
    struct kref kref;
    struct callback_head callback_head;
    bool supplier_preactivated;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    enum device_link_state status;
    u32 flags;
    refcount_t rpm_active;
    struct kref kref;
    struct callback_head callback_head;
    bool supplier_preactivated;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    enum device_link_state status;
    u32 flags;
    refcount_t rpm_active;
    struct kref kref;
    struct callback_head callback_head;
    bool supplier_preactivated;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    struct device link_dev;
    enum device_link_state status;
    u32 flags;
    refcount_t rpm_active;
    struct kref kref;
    struct callback_head callback_head;
    bool supplier_preactivated;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    struct device link_dev;
    enum device_link_state status;
    u32 flags;
    refcount_t rpm_active;
    struct kref kref;
    struct work_struct rm_work;
    bool supplier_preactivated;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    struct device link_dev;
    enum device_link_state status;
    u32 flags;
    refcount_t rpm_active;
    struct kref kref;
    struct work_struct rm_work;
    bool supplier_preactivated;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    struct device link_dev;
    enum device_link_state status;
    u32 flags;
    refcount_t rpm_active;
    struct kref kref;
    struct work_struct rm_work;
    bool supplier_preactivated;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    struct device link_dev;
    enum device_link_state status;
    u32 flags;
    refcount_t rpm_active;
    struct kref kref;
    struct work_struct rm_work;
    bool supplier_preactivated;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    struct device link_dev;
    enum device_link_state status;
    u32 flags;
    refcount_t rpm_active;
    struct kref kref;
    struct work_struct rm_work;
    bool supplier_preactivated;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    struct device link_dev;
    enum device_link_state status;
    u32 flags;
    refcount_t rpm_active;
    struct kref kref;
    struct work_struct rm_work;
    bool supplier_preactivated;
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
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    enum device_link_state status;
    u32 flags;
    refcount_t rpm_active;
    struct kref kref;
    struct callback_head callback_head;
    bool supplier_preactivated;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    enum device_link_state status;
    u32 flags;
    refcount_t rpm_active;
    struct kref kref;
    struct callback_head callback_head;
    bool supplier_preactivated;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    enum device_link_state status;
    u32 flags;
    refcount_t rpm_active;
    struct kref kref;
    struct callback_head callback_head;
    bool supplier_preactivated;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    enum device_link_state status;
    u32 flags;
    refcount_t rpm_active;
    struct kref kref;
    struct callback_head callback_head;
    bool supplier_preactivated;
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
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    enum device_link_state status;
    u32 flags;
    refcount_t rpm_active;
    struct kref kref;
    struct callback_head callback_head;
    bool supplier_preactivated;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    enum device_link_state status;
    u32 flags;
    refcount_t rpm_active;
    struct kref kref;
    struct callback_head callback_head;
    bool supplier_preactivated;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    enum device_link_state status;
    u32 flags;
    refcount_t rpm_active;
    struct kref kref;
    struct callback_head callback_head;
    bool supplier_preactivated;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    enum device_link_state status;
    u32 flags;
    refcount_t rpm_active;
    struct kref kref;
    struct callback_head callback_head;
    bool supplier_preactivated;
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct device_link {
    struct device * supplier;
    struct list_head s_node;
    struct device * consumer;
    struct list_head c_node;
    enum device_link_state status;
    u32 flags;
    bool rpm_active;
    struct callback_head callback_head;
}
```
</details>
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
<code>struct kref kref</code>
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
<code>bool supplier_preactivated</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool rpm_active</code> ➡️ <code>refcount_t rpm_active</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct device link_dev</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct work_struct rm_work</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head callback_head</code>
</li>
</ul>
</details>
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
