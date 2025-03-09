# Struct: <code>snd_card</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct snd_card {
    int number;
    char[16] id;
    char[16] driver;
    char[32] shortname;
    char[80] longname;
    char[32] irq_descr;
    char[80] mixername;
    char[128] components;
    struct module * module;
    void * private_data;
    void (*)(struct snd_card *) private_free;
    struct list_head devices;
    struct device ctl_dev;
    unsigned int last_numid;
    struct rw_semaphore controls_rwsem;
    rwlock_t ctl_files_rwlock;
    int controls_count;
    int user_ctl_count;
    struct list_head controls;
    struct list_head ctl_files;
    struct snd_info_entry * proc_root;
    struct proc_dir_entry * proc_root_link;
    struct list_head files_list;
    struct snd_shutdown_f_ops * s_f_ops;
    spinlock_t files_lock;
    int shutdown;
    struct completion * release_completion;
    struct device * dev;
    struct device card_dev;
    const struct attribute_group *[4] dev_groups;
    bool registered;
    wait_queue_head_t remove_sleep;
    unsigned int power_state;
    wait_queue_head_t power_sleep;
    struct snd_mixer_oss * mixer_oss;
    int mixer_oss_change_count;
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct snd_card {
    int number;
    char[16] id;
    char[16] driver;
    char[32] shortname;
    char[80] longname;
    char[32] irq_descr;
    char[80] mixername;
    char[128] components;
    struct module * module;
    void * private_data;
    void (*)(struct snd_card *) private_free;
    struct list_head devices;
    struct device ctl_dev;
    unsigned int last_numid;
    struct rw_semaphore controls_rwsem;
    rwlock_t ctl_files_rwlock;
    int controls_count;
    int user_ctl_count;
    struct list_head controls;
    struct list_head ctl_files;
    struct snd_info_entry * proc_root;
    struct proc_dir_entry * proc_root_link;
    struct list_head files_list;
    struct snd_shutdown_f_ops * s_f_ops;
    spinlock_t files_lock;
    int shutdown;
    struct completion * release_completion;
    struct device * dev;
    struct device card_dev;
    const struct attribute_group *[4] dev_groups;
    bool registered;
    wait_queue_head_t remove_sleep;
    unsigned int power_state;
    wait_queue_head_t power_sleep;
    struct snd_mixer_oss * mixer_oss;
    int mixer_oss_change_count;
}
```
</details>
</li>
</ul>
