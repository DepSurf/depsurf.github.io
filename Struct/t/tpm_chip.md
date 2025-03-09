# Struct: <code>tpm_chip</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tpm_chip {
    struct device * pdev;
    struct device dev;
    struct cdev cdev;
    const struct tpm_class_ops * ops;
    unsigned int flags;
    int dev_num;
    char[7] devname;
    long unsigned int is_open;
    int time_expired;
    struct mutex tpm_mutex;
    struct tpm_vendor_specific vendor;
    struct dentry * * bios_dir;
    const struct attribute_group *[2] groups;
    unsigned int groups_cnt;
    acpi_handle acpi_dev_handle;
    char[4] ppi_version;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct tpm_chip {
    struct device dev;
    struct cdev cdev;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[3] duration;
    bool duration_adjusted;
    struct dentry * * bios_dir;
    const struct attribute_group *[3] groups;
    unsigned int groups_cnt;
    acpi_handle acpi_dev_handle;
    char[4] ppi_version;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct tpm_chip {
    struct device dev;
    struct cdev cdev;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[3] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[3] groups;
    unsigned int groups_cnt;
    acpi_handle acpi_dev_handle;
    char[4] ppi_version;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct tpm_chip {
    struct device dev;
    struct device devs;
    struct cdev cdev;
    struct cdev cdevs;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[3] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[3] groups;
    unsigned int groups_cnt;
    u16[7] active_banks;
    acpi_handle acpi_dev_handle;
    char[4] ppi_version;
    struct tpm_space work_space;
    u32 nr_commands;
    u32 * cc_attrs_tbl;
    int locality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tpm_chip {
    struct device dev;
    struct device devs;
    struct cdev cdev;
    struct cdev cdevs;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[3] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[3] groups;
    unsigned int groups_cnt;
    u16[7] active_banks;
    acpi_handle acpi_dev_handle;
    char[4] ppi_version;
    struct tpm_space work_space;
    u32 nr_commands;
    u32 * cc_attrs_tbl;
    int locality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct tpm_chip {
    struct device dev;
    struct device devs;
    struct cdev cdev;
    struct cdev cdevs;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    char[64] hwrng_name;
    struct hwrng hwrng;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[4] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[3] groups;
    unsigned int groups_cnt;
    u16[7] active_banks;
    acpi_handle acpi_dev_handle;
    char[4] ppi_version;
    struct tpm_space work_space;
    u32 nr_commands;
    u32 * cc_attrs_tbl;
    int locality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct tpm_chip {
    struct device dev;
    struct device devs;
    struct cdev cdev;
    struct cdev cdevs;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    char[64] hwrng_name;
    struct hwrng hwrng;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[4] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[3] groups;
    unsigned int groups_cnt;
    u16[7] active_banks;
    acpi_handle acpi_dev_handle;
    char[4] ppi_version;
    struct tpm_space work_space;
    u32 nr_commands;
    u32 * cc_attrs_tbl;
    int locality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tpm_chip {
    struct device dev;
    struct device devs;
    struct cdev cdev;
    struct cdev cdevs;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    char[64] hwrng_name;
    struct hwrng hwrng;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[4] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[3] groups;
    unsigned int groups_cnt;
    u32 nr_allocated_banks;
    struct tpm_bank_info * allocated_banks;
    acpi_handle acpi_dev_handle;
    char[4] ppi_version;
    struct tpm_space work_space;
    u32 last_cc;
    u32 nr_commands;
    u32 * cc_attrs_tbl;
    int locality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tpm_chip {
    struct device dev;
    struct device devs;
    struct cdev cdev;
    struct cdev cdevs;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    char[64] hwrng_name;
    struct hwrng hwrng;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[4] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[3] groups;
    unsigned int groups_cnt;
    u32 nr_allocated_banks;
    struct tpm_bank_info * allocated_banks;
    acpi_handle acpi_dev_handle;
    char[4] ppi_version;
    struct tpm_space work_space;
    u32 last_cc;
    u32 nr_commands;
    u32 * cc_attrs_tbl;
    int locality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tpm_chip {
    struct device dev;
    struct device devs;
    struct cdev cdev;
    struct cdev cdevs;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    char[64] hwrng_name;
    struct hwrng hwrng;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[4] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[3] groups;
    unsigned int groups_cnt;
    u32 nr_allocated_banks;
    struct tpm_bank_info * allocated_banks;
    acpi_handle acpi_dev_handle;
    char[4] ppi_version;
    struct tpm_space work_space;
    u32 last_cc;
    u32 nr_commands;
    u32 * cc_attrs_tbl;
    int locality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tpm_chip {
    struct device dev;
    struct device devs;
    struct cdev cdev;
    struct cdev cdevs;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    char[64] hwrng_name;
    struct hwrng hwrng;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[4] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[3] groups;
    unsigned int groups_cnt;
    u32 nr_allocated_banks;
    struct tpm_bank_info * allocated_banks;
    acpi_handle acpi_dev_handle;
    char[4] ppi_version;
    struct tpm_space work_space;
    u32 last_cc;
    u32 nr_commands;
    u32 * cc_attrs_tbl;
    int locality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tpm_chip {
    struct device dev;
    struct device devs;
    struct cdev cdev;
    struct cdev cdevs;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    char[64] hwrng_name;
    struct hwrng hwrng;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[4] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[8] groups;
    unsigned int groups_cnt;
    u32 nr_allocated_banks;
    struct tpm_bank_info * allocated_banks;
    acpi_handle acpi_dev_handle;
    char[4] ppi_version;
    struct tpm_space work_space;
    u32 last_cc;
    u32 nr_commands;
    u32 * cc_attrs_tbl;
    int locality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tpm_chip {
    struct device dev;
    struct device devs;
    struct cdev cdev;
    struct cdev cdevs;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    char[64] hwrng_name;
    struct hwrng hwrng;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[4] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[8] groups;
    unsigned int groups_cnt;
    u32 nr_allocated_banks;
    struct tpm_bank_info * allocated_banks;
    acpi_handle acpi_dev_handle;
    char[4] ppi_version;
    struct tpm_space work_space;
    u32 last_cc;
    u32 nr_commands;
    u32 * cc_attrs_tbl;
    int locality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tpm_chip {
    struct device dev;
    struct device devs;
    struct cdev cdev;
    struct cdev cdevs;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    char[64] hwrng_name;
    struct hwrng hwrng;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[4] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[8] groups;
    unsigned int groups_cnt;
    u32 nr_allocated_banks;
    struct tpm_bank_info * allocated_banks;
    acpi_handle acpi_dev_handle;
    char[4] ppi_version;
    struct tpm_space work_space;
    u32 last_cc;
    u32 nr_commands;
    u32 * cc_attrs_tbl;
    int locality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tpm_chip {
    struct device dev;
    struct device devs;
    struct cdev cdev;
    struct cdev cdevs;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    char[64] hwrng_name;
    struct hwrng hwrng;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[4] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[8] groups;
    unsigned int groups_cnt;
    u32 nr_allocated_banks;
    struct tpm_bank_info * allocated_banks;
    acpi_handle acpi_dev_handle;
    char[4] ppi_version;
    struct tpm_space work_space;
    u32 last_cc;
    u32 nr_commands;
    u32 * cc_attrs_tbl;
    int locality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tpm_chip {
    struct device dev;
    struct device devs;
    struct cdev cdev;
    struct cdev cdevs;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    char[64] hwrng_name;
    struct hwrng hwrng;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[4] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[8] groups;
    unsigned int groups_cnt;
    u32 nr_allocated_banks;
    struct tpm_bank_info * allocated_banks;
    acpi_handle acpi_dev_handle;
    char[4] ppi_version;
    struct tpm_space work_space;
    u32 last_cc;
    u32 nr_commands;
    u32 * cc_attrs_tbl;
    int locality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tpm_chip {
    struct device dev;
    struct device devs;
    struct cdev cdev;
    struct cdev cdevs;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    char[64] hwrng_name;
    struct hwrng hwrng;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[4] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[8] groups;
    unsigned int groups_cnt;
    u32 nr_allocated_banks;
    struct tpm_bank_info * allocated_banks;
    acpi_handle acpi_dev_handle;
    char[4] ppi_version;
    struct tpm_space work_space;
    u32 last_cc;
    u32 nr_commands;
    u32 * cc_attrs_tbl;
    int locality;
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
struct tpm_chip {
    struct device dev;
    struct device devs;
    struct cdev cdev;
    struct cdev cdevs;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    char[64] hwrng_name;
    struct hwrng hwrng;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[4] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[3] groups;
    unsigned int groups_cnt;
    u32 nr_allocated_banks;
    struct tpm_bank_info * allocated_banks;
    acpi_handle acpi_dev_handle;
    char[4] ppi_version;
    struct tpm_space work_space;
    u32 last_cc;
    u32 nr_commands;
    u32 * cc_attrs_tbl;
    int locality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tpm_chip {
    struct device dev;
    struct device devs;
    struct cdev cdev;
    struct cdev cdevs;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    char[64] hwrng_name;
    struct hwrng hwrng;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[4] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[3] groups;
    unsigned int groups_cnt;
    u32 nr_allocated_banks;
    struct tpm_bank_info * allocated_banks;
    struct tpm_space work_space;
    u32 last_cc;
    u32 nr_commands;
    u32 * cc_attrs_tbl;
    int locality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tpm_chip {
    struct device dev;
    struct device devs;
    struct cdev cdev;
    struct cdev cdevs;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    char[64] hwrng_name;
    struct hwrng hwrng;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[4] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[3] groups;
    unsigned int groups_cnt;
    u32 nr_allocated_banks;
    struct tpm_bank_info * allocated_banks;
    struct tpm_space work_space;
    u32 last_cc;
    u32 nr_commands;
    u32 * cc_attrs_tbl;
    int locality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tpm_chip {
    struct device dev;
    struct device devs;
    struct cdev cdev;
    struct cdev cdevs;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    char[64] hwrng_name;
    struct hwrng hwrng;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[4] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[3] groups;
    unsigned int groups_cnt;
    u32 nr_allocated_banks;
    struct tpm_bank_info * allocated_banks;
    struct tpm_space work_space;
    u32 last_cc;
    u32 nr_commands;
    u32 * cc_attrs_tbl;
    int locality;
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
struct tpm_chip {
    struct device dev;
    struct device devs;
    struct cdev cdev;
    struct cdev cdevs;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    char[64] hwrng_name;
    struct hwrng hwrng;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[4] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[3] groups;
    unsigned int groups_cnt;
    u32 nr_allocated_banks;
    struct tpm_bank_info * allocated_banks;
    acpi_handle acpi_dev_handle;
    char[4] ppi_version;
    struct tpm_space work_space;
    u32 last_cc;
    u32 nr_commands;
    u32 * cc_attrs_tbl;
    int locality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tpm_chip {
    struct device dev;
    struct device devs;
    struct cdev cdev;
    struct cdev cdevs;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    char[64] hwrng_name;
    struct hwrng hwrng;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[4] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[3] groups;
    unsigned int groups_cnt;
    u32 nr_allocated_banks;
    struct tpm_bank_info * allocated_banks;
    acpi_handle acpi_dev_handle;
    char[4] ppi_version;
    struct tpm_space work_space;
    u32 last_cc;
    u32 nr_commands;
    u32 * cc_attrs_tbl;
    int locality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tpm_chip {
    struct device dev;
    struct device devs;
    struct cdev cdev;
    struct cdev cdevs;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    char[64] hwrng_name;
    struct hwrng hwrng;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[4] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[3] groups;
    unsigned int groups_cnt;
    u32 nr_allocated_banks;
    struct tpm_bank_info * allocated_banks;
    acpi_handle acpi_dev_handle;
    char[4] ppi_version;
    struct tpm_space work_space;
    u32 last_cc;
    u32 nr_commands;
    u32 * cc_attrs_tbl;
    int locality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tpm_chip {
    struct device dev;
    struct device devs;
    struct cdev cdev;
    struct cdev cdevs;
    struct rw_semaphore ops_sem;
    const struct tpm_class_ops * ops;
    struct tpm_bios_log log;
    struct tpm_chip_seqops bin_log_seqops;
    struct tpm_chip_seqops ascii_log_seqops;
    unsigned int flags;
    int dev_num;
    long unsigned int is_open;
    char[64] hwrng_name;
    struct hwrng hwrng;
    struct mutex tpm_mutex;
    long unsigned int timeout_a;
    long unsigned int timeout_b;
    long unsigned int timeout_c;
    long unsigned int timeout_d;
    bool timeout_adjusted;
    long unsigned int[4] duration;
    bool duration_adjusted;
    struct dentry *[3] bios_dir;
    const struct attribute_group *[3] groups;
    unsigned int groups_cnt;
    u32 nr_allocated_banks;
    struct tpm_bank_info * allocated_banks;
    acpi_handle acpi_dev_handle;
    char[4] ppi_version;
    struct tpm_space work_space;
    u32 last_cc;
    u32 nr_commands;
    u32 * cc_attrs_tbl;
    int locality;
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
<code>struct rw_semaphore ops_sem</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int timeout_a</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int timeout_b</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int timeout_c</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int timeout_d</code>
</li>
<li>
<b>Field added. </b>
<code>bool timeout_adjusted</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int[3] duration</code>
</li>
<li>
<b>Field added. </b>
<code>bool duration_adjusted</code>
</li>
<li>
<b>Field removed. </b>
<code>struct device * pdev</code>
</li>
<li>
<b>Field removed. </b>
<code>char[7] devname</code>
</li>
<li>
<b>Field removed. </b>
<code>int time_expired</code>
</li>
<li>
<b>Field removed. </b>
<code>struct tpm_vendor_specific vendor</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head list</code>
</li>
<li>
<b>Field type changed. </b>
<code>const struct attribute_group *[2] groups</code> ➡️ <code>const struct attribute_group *[3] groups</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct tpm_bios_log log</code>
</li>
<li>
<b>Field added. </b>
<code>struct tpm_chip_seqops bin_log_seqops</code>
</li>
<li>
<b>Field added. </b>
<code>struct tpm_chip_seqops ascii_log_seqops</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct dentry * * bios_dir</code> ➡️ <code>struct dentry *[3] bios_dir</code>
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
<code>struct device devs</code>
</li>
<li>
<b>Field added. </b>
<code>struct cdev cdevs</code>
</li>
<li>
<b>Field added. </b>
<code>u16[7] active_banks</code>
</li>
<li>
<b>Field added. </b>
<code>struct tpm_space work_space</code>
</li>
<li>
<b>Field added. </b>
<code>u32 nr_commands</code>
</li>
<li>
<b>Field added. </b>
<code>u32 * cc_attrs_tbl</code>
</li>
<li>
<b>Field added. </b>
<code>int locality</code>
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
<code>char[64] hwrng_name</code>
</li>
<li>
<b>Field added. </b>
<code>struct hwrng hwrng</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[3] duration</code> ➡️ <code>long unsigned int[4] duration</code>
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
<code>u32 nr_allocated_banks</code>
</li>
<li>
<b>Field added. </b>
<code>struct tpm_bank_info * allocated_banks</code>
</li>
<li>
<b>Field added. </b>
<code>u32 last_cc</code>
</li>
<li>
<b>Field removed. </b>
<code>u16[7] active_banks</code>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>const struct attribute_group *[3] groups</code> ➡️ <code>const struct attribute_group *[8] groups</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>acpi_handle acpi_dev_handle</code>
</li>
<li>
<b>Field removed. </b>
<code>char[4] ppi_version</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>acpi_handle acpi_dev_handle</code>
</li>
<li>
<b>Field removed. </b>
<code>char[4] ppi_version</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>acpi_handle acpi_dev_handle</code>
</li>
<li>
<b>Field removed. </b>
<code>char[4] ppi_version</code>
</li>
</ul>
</details>
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
