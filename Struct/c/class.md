# Struct: <code>class</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct class {
    const char * name;
    struct module * owner;
    struct class_attribute * class_attrs;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(struct device *) namespace;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct class {
    const char * name;
    struct module * owner;
    struct class_attribute * class_attrs;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(struct device *) namespace;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct class {
    const char * name;
    struct module * owner;
    struct class_attribute * class_attrs;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(struct device *) namespace;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct class {
    const char * name;
    struct module * owner;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) shutdown;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(struct device *) namespace;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct class {
    const char * name;
    struct module * owner;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *) shutdown_pre;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(struct device *) namespace;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct class {
    const char * name;
    struct module * owner;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *) shutdown_pre;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(struct device *) namespace;
    void (*)(struct device *, kuid_t *, kgid_t *) get_ownership;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct class {
    const char * name;
    struct module * owner;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *) shutdown_pre;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(struct device *) namespace;
    void (*)(struct device *, kuid_t *, kgid_t *) get_ownership;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct class {
    const char * name;
    struct module * owner;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *) shutdown_pre;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(struct device *) namespace;
    void (*)(struct device *, kuid_t *, kgid_t *) get_ownership;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct class {
    const char * name;
    struct module * owner;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *) shutdown_pre;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(struct device *) namespace;
    void (*)(struct device *, kuid_t *, kgid_t *) get_ownership;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct class {
    const char * name;
    struct module * owner;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *) shutdown_pre;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(struct device *) namespace;
    void (*)(struct device *, kuid_t *, kgid_t *) get_ownership;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct class {
    const char * name;
    struct module * owner;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *) shutdown_pre;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(struct device *) namespace;
    void (*)(struct device *, kuid_t *, kgid_t *) get_ownership;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct class {
    const char * name;
    struct module * owner;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *) shutdown_pre;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(struct device *) namespace;
    void (*)(struct device *, kuid_t *, kgid_t *) get_ownership;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct class {
    const char * name;
    struct module * owner;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *) shutdown_pre;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(struct device *) namespace;
    void (*)(struct device *, kuid_t *, kgid_t *) get_ownership;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct class {
    const char * name;
    struct module * owner;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *) shutdown_pre;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(struct device *) namespace;
    void (*)(struct device *, kuid_t *, kgid_t *) get_ownership;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct class {
    const char * name;
    struct module * owner;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(const struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(const struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *) shutdown_pre;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(const struct device *) namespace;
    void (*)(const struct device *, kuid_t *, kgid_t *) get_ownership;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct class {
    const char * name;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    int (*)(const struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(const struct device *, umode_t *) devnode;
    void (*)(const struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *) shutdown_pre;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(const struct device *) namespace;
    void (*)(const struct device *, kuid_t *, kgid_t *) get_ownership;
    const struct dev_pm_ops * pm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct class {
    const char * name;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    int (*)(const struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(const struct device *, umode_t *) devnode;
    void (*)(const struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *) shutdown_pre;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(const struct device *) namespace;
    void (*)(const struct device *, kuid_t *, kgid_t *) get_ownership;
    const struct dev_pm_ops * pm;
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
struct class {
    const char * name;
    struct module * owner;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *) shutdown_pre;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(struct device *) namespace;
    void (*)(struct device *, kuid_t *, kgid_t *) get_ownership;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct class {
    const char * name;
    struct module * owner;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *) shutdown_pre;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(struct device *) namespace;
    void (*)(struct device *, kuid_t *, kgid_t *) get_ownership;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct class {
    const char * name;
    struct module * owner;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *) shutdown_pre;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(struct device *) namespace;
    void (*)(struct device *, kuid_t *, kgid_t *) get_ownership;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct class {
    const char * name;
    struct module * owner;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *) shutdown_pre;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(struct device *) namespace;
    void (*)(struct device *, kuid_t *, kgid_t *) get_ownership;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
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
struct class {
    const char * name;
    struct module * owner;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *) shutdown_pre;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(struct device *) namespace;
    void (*)(struct device *, kuid_t *, kgid_t *) get_ownership;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct class {
    const char * name;
    struct module * owner;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *) shutdown_pre;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(struct device *) namespace;
    void (*)(struct device *, kuid_t *, kgid_t *) get_ownership;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct class {
    const char * name;
    struct module * owner;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *) shutdown_pre;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(struct device *) namespace;
    void (*)(struct device *, kuid_t *, kgid_t *) get_ownership;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct class {
    const char * name;
    struct module * owner;
    const struct attribute_group * * class_groups;
    const struct attribute_group * * dev_groups;
    struct kobject * dev_kobj;
    int (*)(struct device *, struct kobj_uevent_env *) dev_uevent;
    char * (*)(struct device *, umode_t *) devnode;
    void (*)(struct class *) class_release;
    void (*)(struct device *) dev_release;
    int (*)(struct device *) shutdown_pre;
    const struct kobj_ns_type_operations * ns_type;
    const void * (*)(struct device *) namespace;
    void (*)(struct device *, kuid_t *, kgid_t *) get_ownership;
    const struct dev_pm_ops * pm;
    struct subsys_private * p;
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
<code>const struct attribute_group * * class_groups</code>
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
<code>int (*)(struct device *) shutdown</code>
</li>
<li>
<b>Field removed. </b>
<code>struct class_attribute * class_attrs</code>
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
<code>int (*)(struct device *) shutdown_pre</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct device *, pm_message_t) suspend</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct device *) resume</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct device *) shutdown</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct device *, kuid_t *, kgid_t *) get_ownership</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct device *, struct kobj_uevent_env *) dev_uevent</code> ➡️ <code>int (*)(const struct device *, struct kobj_uevent_env *) dev_uevent</code>
</li>
<li>
<b>Field type changed. </b>
<code>char * (*)(struct device *, umode_t *) devnode</code> ➡️ <code>char * (*)(const struct device *, umode_t *) devnode</code>
</li>
<li>
<b>Field type changed. </b>
<code>const void * (*)(struct device *) namespace</code> ➡️ <code>const void * (*)(const struct device *) namespace</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct device *, kuid_t *, kgid_t *) get_ownership</code> ➡️ <code>void (*)(const struct device *, kuid_t *, kgid_t *) get_ownership</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct module * owner</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kobject * dev_kobj</code>
</li>
<li>
<b>Field removed. </b>
<code>struct subsys_private * p</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct class *) class_release</code> ➡️ <code>void (*)(const struct class *) class_release</code>
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
