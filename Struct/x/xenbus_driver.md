# Struct: <code>xenbus_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    int (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    int (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    int (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    int (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    int (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    int (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    int (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    int (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    int (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    bool allow_rebind;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    int (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
    void (*)(struct xenbus_device *) reclaim_memory;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    bool allow_rebind;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    int (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
    void (*)(struct xenbus_device *) reclaim_memory;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    bool allow_rebind;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    int (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
    void (*)(struct xenbus_device *) reclaim_memory;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    bool allow_rebind;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    int (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
    void (*)(struct xenbus_device *) reclaim_memory;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    bool allow_rebind;
    bool not_essential;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    int (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
    void (*)(struct xenbus_device *) reclaim_memory;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    bool allow_rebind;
    bool not_essential;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    void (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
    void (*)(struct xenbus_device *) reclaim_memory;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    bool allow_rebind;
    bool not_essential;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    void (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(const struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
    void (*)(struct xenbus_device *) reclaim_memory;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    bool allow_rebind;
    bool not_essential;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    void (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(const struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
    void (*)(struct xenbus_device *) reclaim_memory;
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
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    int (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
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
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    int (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *) freeze;
    int (*)(struct xenbus_device *) thaw;
    int (*)(struct xenbus_device *) restore;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
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
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    int (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    int (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
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
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool allow_rebind</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct xenbus_device *) reclaim_memory</code>
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
<b>Field added. </b>
<code>bool not_essential</code>
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
<code>int (*)(struct xenbus_device *) remove</code> ➡️ <code>void (*)(struct xenbus_device *) remove</code>
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
<code>int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent</code> ➡️ <code>int (*)(const struct xenbus_device *, struct kobj_uevent_env *) uevent</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    int (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    int (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    int (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct xenbus_device *) freeze</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct xenbus_device *) thaw</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct xenbus_device *) restore</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct xenbus_driver {
    const char * name;
    const struct xenbus_device_id * ids;
    int (*)(struct xenbus_device *, const struct xenbus_device_id *) probe;
    void (*)(struct xenbus_device *, enum xenbus_state) otherend_changed;
    int (*)(struct xenbus_device *) remove;
    int (*)(struct xenbus_device *) suspend;
    int (*)(struct xenbus_device *) resume;
    int (*)(struct xenbus_device *, struct kobj_uevent_env *) uevent;
    struct device_driver driver;
    int (*)(struct xenbus_device *) read_otherend_details;
    int (*)(struct xenbus_device *) is_ready;
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
