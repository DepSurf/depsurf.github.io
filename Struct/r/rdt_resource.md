# Struct: <code>rdt_resource</code>

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
struct rdt_resource {
    bool enabled;
    bool capable;
    char * name;
    int num_closid;
    int cbm_len;
    int min_cbm_bits;
    u32 max_cbm;
    struct list_head domains;
    int num_domains;
    int msr_base;
    u32 * tmp_cbms;
    int num_tmp_cbms;
    int cache_level;
    int cbm_idx_multi;
    int cbm_idx_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rdt_resource {
    int rid;
    bool alloc_enabled;
    bool mon_enabled;
    bool alloc_capable;
    bool mon_capable;
    char * name;
    int num_closid;
    int cache_level;
    u32 default_ctrl;
    unsigned int msr_base;
    void (*)(struct rdt_domain *, struct msr_param *, struct rdt_resource *) msr_update;
    int data_width;
    struct list_head domains;
    struct rdt_cache cache;
    struct rdt_membw membw;
    const char * format_str;
    int (*)(char *, struct rdt_resource *, struct rdt_domain *) parse_ctrlval;
    struct list_head evt_list;
    int num_rmid;
    unsigned int mon_scale;
    long unsigned int fflags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rdt_resource {
    int rid;
    bool alloc_enabled;
    bool mon_enabled;
    bool alloc_capable;
    bool mon_capable;
    char * name;
    int num_closid;
    int cache_level;
    u32 default_ctrl;
    unsigned int msr_base;
    void (*)(struct rdt_domain *, struct msr_param *, struct rdt_resource *) msr_update;
    int data_width;
    struct list_head domains;
    struct rdt_cache cache;
    struct rdt_membw membw;
    const char * format_str;
    int (*)(char *, struct rdt_resource *, struct rdt_domain *) parse_ctrlval;
    struct list_head evt_list;
    int num_rmid;
    unsigned int mon_scale;
    long unsigned int fflags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rdt_resource {
    int rid;
    bool alloc_enabled;
    bool mon_enabled;
    bool alloc_capable;
    bool mon_capable;
    char * name;
    int num_closid;
    int cache_level;
    u32 default_ctrl;
    unsigned int msr_base;
    void (*)(struct rdt_domain *, struct msr_param *, struct rdt_resource *) msr_update;
    int data_width;
    struct list_head domains;
    struct rdt_cache cache;
    struct rdt_membw membw;
    const char * format_str;
    int (*)(char *, struct rdt_resource *, struct rdt_domain *) parse_ctrlval;
    struct list_head evt_list;
    int num_rmid;
    unsigned int mon_scale;
    long unsigned int fflags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rdt_resource {
    int rid;
    bool alloc_enabled;
    bool mon_enabled;
    bool alloc_capable;
    bool mon_capable;
    char * name;
    int num_closid;
    int cache_level;
    u32 default_ctrl;
    unsigned int msr_base;
    void (*)(struct rdt_domain *, struct msr_param *, struct rdt_resource *) msr_update;
    int data_width;
    struct list_head domains;
    struct rdt_cache cache;
    struct rdt_membw membw;
    const char * format_str;
    int (*)(struct rdt_parse_data *, struct rdt_resource *, struct rdt_domain *) parse_ctrlval;
    bool (*)(char *, u32 *, struct rdt_resource *) cbm_validate;
    struct list_head evt_list;
    int num_rmid;
    unsigned int mon_scale;
    long unsigned int fflags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rdt_resource {
    int rid;
    bool alloc_enabled;
    bool mon_enabled;
    bool alloc_capable;
    bool mon_capable;
    char * name;
    int num_closid;
    int cache_level;
    u32 default_ctrl;
    unsigned int msr_base;
    void (*)(struct rdt_domain *, struct msr_param *, struct rdt_resource *) msr_update;
    int data_width;
    struct list_head domains;
    struct rdt_cache cache;
    struct rdt_membw membw;
    const char * format_str;
    int (*)(struct rdt_parse_data *, struct rdt_resource *, struct rdt_domain *) parse_ctrlval;
    bool (*)(char *, u32 *, struct rdt_resource *) cbm_validate;
    struct list_head evt_list;
    int num_rmid;
    unsigned int mon_scale;
    long unsigned int fflags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rdt_resource {
    int rid;
    bool alloc_enabled;
    bool mon_enabled;
    bool alloc_capable;
    bool mon_capable;
    char * name;
    int num_closid;
    int cache_level;
    u32 default_ctrl;
    unsigned int msr_base;
    void (*)(struct rdt_domain *, struct msr_param *, struct rdt_resource *) msr_update;
    int data_width;
    struct list_head domains;
    struct rdt_cache cache;
    struct rdt_membw membw;
    const char * format_str;
    int (*)(struct rdt_parse_data *, struct rdt_resource *, struct rdt_domain *) parse_ctrlval;
    bool (*)(char *, u32 *, struct rdt_resource *) cbm_validate;
    struct list_head evt_list;
    int num_rmid;
    unsigned int mon_scale;
    long unsigned int fflags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rdt_resource {
    int rid;
    bool alloc_enabled;
    bool mon_enabled;
    bool alloc_capable;
    bool mon_capable;
    char * name;
    int num_closid;
    int cache_level;
    u32 default_ctrl;
    unsigned int msr_base;
    void (*)(struct rdt_domain *, struct msr_param *, struct rdt_resource *) msr_update;
    int data_width;
    struct list_head domains;
    struct rdt_cache cache;
    struct rdt_membw membw;
    const char * format_str;
    int (*)(struct rdt_parse_data *, struct rdt_resource *, struct rdt_domain *) parse_ctrlval;
    bool (*)(char *, u32 *, struct rdt_resource *) cbm_validate;
    struct list_head evt_list;
    int num_rmid;
    unsigned int mon_scale;
    unsigned int mbm_width;
    long unsigned int fflags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct rdt_resource {
    int rid;
    bool alloc_enabled;
    bool mon_enabled;
    bool alloc_capable;
    bool mon_capable;
    char * name;
    int num_closid;
    int cache_level;
    u32 default_ctrl;
    unsigned int msr_base;
    void (*)(struct rdt_domain *, struct msr_param *, struct rdt_resource *) msr_update;
    int data_width;
    struct list_head domains;
    struct rdt_cache cache;
    struct rdt_membw membw;
    const char * format_str;
    int (*)(struct rdt_parse_data *, struct rdt_resource *, struct rdt_domain *) parse_ctrlval;
    struct list_head evt_list;
    int num_rmid;
    unsigned int mon_scale;
    unsigned int mbm_width;
    long unsigned int fflags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rdt_resource {
    int rid;
    bool alloc_enabled;
    bool mon_enabled;
    bool alloc_capable;
    bool mon_capable;
    char * name;
    int num_closid;
    int cache_level;
    u32 default_ctrl;
    unsigned int msr_base;
    void (*)(struct rdt_domain *, struct msr_param *, struct rdt_resource *) msr_update;
    int data_width;
    struct list_head domains;
    struct rdt_cache cache;
    struct rdt_membw membw;
    const char * format_str;
    int (*)(struct rdt_parse_data *, struct rdt_resource *, struct rdt_domain *) parse_ctrlval;
    struct list_head evt_list;
    int num_rmid;
    unsigned int mon_scale;
    unsigned int mbm_width;
    long unsigned int fflags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rdt_resource {
    int rid;
    bool alloc_enabled;
    bool mon_enabled;
    bool alloc_capable;
    bool mon_capable;
    int num_rmid;
    int cache_level;
    struct resctrl_cache cache;
    struct resctrl_membw membw;
    struct list_head domains;
    char * name;
    int data_width;
    u32 default_ctrl;
    const char * format_str;
    int (*)(struct rdt_parse_data *, struct resctrl_schema *, struct rdt_domain *) parse_ctrlval;
    struct list_head evt_list;
    long unsigned int fflags;
    bool cdp_capable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rdt_resource {
    int rid;
    bool alloc_enabled;
    bool mon_enabled;
    bool alloc_capable;
    bool mon_capable;
    int num_rmid;
    int cache_level;
    struct resctrl_cache cache;
    struct resctrl_membw membw;
    struct list_head domains;
    char * name;
    int data_width;
    u32 default_ctrl;
    const char * format_str;
    int (*)(struct rdt_parse_data *, struct resctrl_schema *, struct rdt_domain *) parse_ctrlval;
    struct list_head evt_list;
    long unsigned int fflags;
    bool cdp_capable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rdt_resource {
    int rid;
    bool alloc_capable;
    bool mon_capable;
    int num_rmid;
    int cache_level;
    struct resctrl_cache cache;
    struct resctrl_membw membw;
    struct list_head domains;
    char * name;
    int data_width;
    u32 default_ctrl;
    const char * format_str;
    int (*)(struct rdt_parse_data *, struct resctrl_schema *, struct rdt_domain *) parse_ctrlval;
    struct list_head evt_list;
    long unsigned int fflags;
    bool cdp_capable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rdt_resource {
    int rid;
    bool alloc_capable;
    bool mon_capable;
    int num_rmid;
    int cache_level;
    struct resctrl_cache cache;
    struct resctrl_membw membw;
    struct list_head domains;
    char * name;
    int data_width;
    u32 default_ctrl;
    const char * format_str;
    int (*)(struct rdt_parse_data *, struct resctrl_schema *, struct rdt_domain *) parse_ctrlval;
    struct list_head evt_list;
    long unsigned int fflags;
    bool cdp_capable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rdt_resource {
    int rid;
    bool alloc_capable;
    bool mon_capable;
    int num_rmid;
    int cache_level;
    struct resctrl_cache cache;
    struct resctrl_membw membw;
    struct list_head domains;
    char * name;
    int data_width;
    u32 default_ctrl;
    const char * format_str;
    int (*)(struct rdt_parse_data *, struct resctrl_schema *, struct rdt_domain *) parse_ctrlval;
    struct list_head evt_list;
    long unsigned int fflags;
    bool cdp_capable;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
struct rdt_resource {
    int rid;
    bool alloc_enabled;
    bool mon_enabled;
    bool alloc_capable;
    bool mon_capable;
    char * name;
    int num_closid;
    int cache_level;
    u32 default_ctrl;
    unsigned int msr_base;
    void (*)(struct rdt_domain *, struct msr_param *, struct rdt_resource *) msr_update;
    int data_width;
    struct list_head domains;
    struct rdt_cache cache;
    struct rdt_membw membw;
    const char * format_str;
    int (*)(struct rdt_parse_data *, struct rdt_resource *, struct rdt_domain *) parse_ctrlval;
    bool (*)(char *, u32 *, struct rdt_resource *) cbm_validate;
    struct list_head evt_list;
    int num_rmid;
    unsigned int mon_scale;
    long unsigned int fflags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rdt_resource {
    int rid;
    bool alloc_enabled;
    bool mon_enabled;
    bool alloc_capable;
    bool mon_capable;
    char * name;
    int num_closid;
    int cache_level;
    u32 default_ctrl;
    unsigned int msr_base;
    void (*)(struct rdt_domain *, struct msr_param *, struct rdt_resource *) msr_update;
    int data_width;
    struct list_head domains;
    struct rdt_cache cache;
    struct rdt_membw membw;
    const char * format_str;
    int (*)(struct rdt_parse_data *, struct rdt_resource *, struct rdt_domain *) parse_ctrlval;
    bool (*)(char *, u32 *, struct rdt_resource *) cbm_validate;
    struct list_head evt_list;
    int num_rmid;
    unsigned int mon_scale;
    long unsigned int fflags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rdt_resource {
    int rid;
    bool alloc_enabled;
    bool mon_enabled;
    bool alloc_capable;
    bool mon_capable;
    char * name;
    int num_closid;
    int cache_level;
    u32 default_ctrl;
    unsigned int msr_base;
    void (*)(struct rdt_domain *, struct msr_param *, struct rdt_resource *) msr_update;
    int data_width;
    struct list_head domains;
    struct rdt_cache cache;
    struct rdt_membw membw;
    const char * format_str;
    int (*)(struct rdt_parse_data *, struct rdt_resource *, struct rdt_domain *) parse_ctrlval;
    bool (*)(char *, u32 *, struct rdt_resource *) cbm_validate;
    struct list_head evt_list;
    int num_rmid;
    unsigned int mon_scale;
    long unsigned int fflags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rdt_resource {
    int rid;
    bool alloc_enabled;
    bool mon_enabled;
    bool alloc_capable;
    bool mon_capable;
    char * name;
    int num_closid;
    int cache_level;
    u32 default_ctrl;
    unsigned int msr_base;
    void (*)(struct rdt_domain *, struct msr_param *, struct rdt_resource *) msr_update;
    int data_width;
    struct list_head domains;
    struct rdt_cache cache;
    struct rdt_membw membw;
    const char * format_str;
    int (*)(struct rdt_parse_data *, struct rdt_resource *, struct rdt_domain *) parse_ctrlval;
    bool (*)(char *, u32 *, struct rdt_resource *) cbm_validate;
    struct list_head evt_list;
    int num_rmid;
    unsigned int mon_scale;
    long unsigned int fflags;
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
struct rdt_resource {
    bool enabled;
    bool capable;
    char * name;
    int num_closid;
    int cbm_len;
    int min_cbm_bits;
    u32 max_cbm;
    struct list_head domains;
    int num_domains;
    int msr_base;
    u32 * tmp_cbms;
    int num_tmp_cbms;
    int cache_level;
    int cbm_idx_multi;
    int cbm_idx_offset;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int rid</code>
</li>
<li>
<b>Field added. </b>
<code>bool alloc_enabled</code>
</li>
<li>
<b>Field added. </b>
<code>bool mon_enabled</code>
</li>
<li>
<b>Field added. </b>
<code>bool alloc_capable</code>
</li>
<li>
<b>Field added. </b>
<code>bool mon_capable</code>
</li>
<li>
<b>Field added. </b>
<code>u32 default_ctrl</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct rdt_domain *, struct msr_param *, struct rdt_resource *) msr_update</code>
</li>
<li>
<b>Field added. </b>
<code>int data_width</code>
</li>
<li>
<b>Field added. </b>
<code>struct rdt_cache cache</code>
</li>
<li>
<b>Field added. </b>
<code>struct rdt_membw membw</code>
</li>
<li>
<b>Field added. </b>
<code>const char * format_str</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(char *, struct rdt_resource *, struct rdt_domain *) parse_ctrlval</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head evt_list</code>
</li>
<li>
<b>Field added. </b>
<code>int num_rmid</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int mon_scale</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int fflags</code>
</li>
<li>
<b>Field removed. </b>
<code>bool enabled</code>
</li>
<li>
<b>Field removed. </b>
<code>bool capable</code>
</li>
<li>
<b>Field removed. </b>
<code>int cbm_len</code>
</li>
<li>
<b>Field removed. </b>
<code>int min_cbm_bits</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 max_cbm</code>
</li>
<li>
<b>Field removed. </b>
<code>int num_domains</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 * tmp_cbms</code>
</li>
<li>
<b>Field removed. </b>
<code>int num_tmp_cbms</code>
</li>
<li>
<b>Field removed. </b>
<code>int cbm_idx_multi</code>
</li>
<li>
<b>Field removed. </b>
<code>int cbm_idx_offset</code>
</li>
<li>
<b>Field type changed. </b>
<code>int msr_base</code> ➡️ <code>unsigned int msr_base</code>
</li>
</ul>
</details>
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
<code>bool (*)(char *, u32 *, struct rdt_resource *) cbm_validate</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(char *, struct rdt_resource *, struct rdt_domain *) parse_ctrlval</code> ➡️ <code>int (*)(struct rdt_parse_data *, struct rdt_resource *, struct rdt_domain *) parse_ctrlval</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int mbm_width</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool (*)(char *, u32 *, struct rdt_resource *) cbm_validate</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool cdp_capable</code>
</li>
<li>
<b>Field removed. </b>
<code>int num_closid</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int msr_base</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct rdt_domain *, struct msr_param *, struct rdt_resource *) msr_update</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int mon_scale</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int mbm_width</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct rdt_cache cache</code> ➡️ <code>struct resctrl_cache cache</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct rdt_membw membw</code> ➡️ <code>struct resctrl_membw membw</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct rdt_parse_data *, struct rdt_resource *, struct rdt_domain *) parse_ctrlval</code> ➡️ <code>int (*)(struct rdt_parse_data *, struct resctrl_schema *, struct rdt_domain *) parse_ctrlval</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool alloc_enabled</code>
</li>
<li>
<b>Field removed. </b>
<code>bool mon_enabled</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct rdt_resource {
    int rid;
    bool alloc_enabled;
    bool mon_enabled;
    bool alloc_capable;
    bool mon_capable;
    char * name;
    int num_closid;
    int cache_level;
    u32 default_ctrl;
    unsigned int msr_base;
    void (*)(struct rdt_domain *, struct msr_param *, struct rdt_resource *) msr_update;
    int data_width;
    struct list_head domains;
    struct rdt_cache cache;
    struct rdt_membw membw;
    const char * format_str;
    int (*)(struct rdt_parse_data *, struct rdt_resource *, struct rdt_domain *) parse_ctrlval;
    bool (*)(char *, u32 *, struct rdt_resource *) cbm_validate;
    struct list_head evt_list;
    int num_rmid;
    unsigned int mon_scale;
    long unsigned int fflags;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct rdt_resource {
    int rid;
    bool alloc_enabled;
    bool mon_enabled;
    bool alloc_capable;
    bool mon_capable;
    char * name;
    int num_closid;
    int cache_level;
    u32 default_ctrl;
    unsigned int msr_base;
    void (*)(struct rdt_domain *, struct msr_param *, struct rdt_resource *) msr_update;
    int data_width;
    struct list_head domains;
    struct rdt_cache cache;
    struct rdt_membw membw;
    const char * format_str;
    int (*)(struct rdt_parse_data *, struct rdt_resource *, struct rdt_domain *) parse_ctrlval;
    bool (*)(char *, u32 *, struct rdt_resource *) cbm_validate;
    struct list_head evt_list;
    int num_rmid;
    unsigned int mon_scale;
    long unsigned int fflags;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct rdt_resource {
    int rid;
    bool alloc_enabled;
    bool mon_enabled;
    bool alloc_capable;
    bool mon_capable;
    char * name;
    int num_closid;
    int cache_level;
    u32 default_ctrl;
    unsigned int msr_base;
    void (*)(struct rdt_domain *, struct msr_param *, struct rdt_resource *) msr_update;
    int data_width;
    struct list_head domains;
    struct rdt_cache cache;
    struct rdt_membw membw;
    const char * format_str;
    int (*)(struct rdt_parse_data *, struct rdt_resource *, struct rdt_domain *) parse_ctrlval;
    bool (*)(char *, u32 *, struct rdt_resource *) cbm_validate;
    struct list_head evt_list;
    int num_rmid;
    unsigned int mon_scale;
    long unsigned int fflags;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct rdt_resource {
    int rid;
    bool alloc_enabled;
    bool mon_enabled;
    bool alloc_capable;
    bool mon_capable;
    char * name;
    int num_closid;
    int cache_level;
    u32 default_ctrl;
    unsigned int msr_base;
    void (*)(struct rdt_domain *, struct msr_param *, struct rdt_resource *) msr_update;
    int data_width;
    struct list_head domains;
    struct rdt_cache cache;
    struct rdt_membw membw;
    const char * format_str;
    int (*)(struct rdt_parse_data *, struct rdt_resource *, struct rdt_domain *) parse_ctrlval;
    bool (*)(char *, u32 *, struct rdt_resource *) cbm_validate;
    struct list_head evt_list;
    int num_rmid;
    unsigned int mon_scale;
    long unsigned int fflags;
}
```
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
