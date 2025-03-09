# Struct: <code>led_trigger</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    void (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    rwlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    void (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    rwlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    void (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    rwlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    void (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    rwlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    void (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    rwlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    void (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    rwlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    int (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    rwlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
    const struct attribute_group * * groups;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    int (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    rwlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
    const struct attribute_group * * groups;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    int (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    rwlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
    const struct attribute_group * * groups;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    int (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    rwlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
    const struct attribute_group * * groups;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    int (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    struct led_hw_trigger_type * trigger_type;
    rwlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
    const struct attribute_group * * groups;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    int (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    struct led_hw_trigger_type * trigger_type;
    rwlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
    const struct attribute_group * * groups;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    int (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    struct led_hw_trigger_type * trigger_type;
    rwlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
    const struct attribute_group * * groups;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    int (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    struct led_hw_trigger_type * trigger_type;
    spinlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
    const struct attribute_group * * groups;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    int (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    struct led_hw_trigger_type * trigger_type;
    spinlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
    const struct attribute_group * * groups;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    int (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    struct led_hw_trigger_type * trigger_type;
    spinlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
    const struct attribute_group * * groups;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    int (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    struct led_hw_trigger_type * trigger_type;
    spinlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
    const struct attribute_group * * groups;
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
struct led_trigger {
    const char * name;
    int (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    rwlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
    const struct attribute_group * * groups;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    int (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    rwlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
    const struct attribute_group * * groups;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    int (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    rwlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
    const struct attribute_group * * groups;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    int (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    rwlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
    const struct attribute_group * * groups;
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
struct led_trigger {
    const char * name;
    int (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    rwlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
    const struct attribute_group * * groups;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    int (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    rwlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
    const struct attribute_group * * groups;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    int (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    rwlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
    const struct attribute_group * * groups;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct led_trigger {
    const char * name;
    int (*)(struct led_classdev *) activate;
    void (*)(struct led_classdev *) deactivate;
    rwlock_t leddev_list_lock;
    struct list_head led_cdevs;
    struct list_head next_trig;
    const struct attribute_group * * groups;
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct attribute_group * * groups</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct led_classdev *) activate</code> ➡️ <code>int (*)(struct led_classdev *) activate</code>
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
<b>Field added. </b>
<code>struct led_hw_trigger_type * trigger_type</code>
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
<b>Field type changed. </b>
<code>rwlock_t leddev_list_lock</code> ➡️ <code>spinlock_t leddev_list_lock</code>
</li>
</ul>
</details>
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
