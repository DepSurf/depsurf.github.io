# Struct: <code>mem_ctl_info</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mem_ctl_info {
    struct device dev;
    struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * mod_ver;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    u32 *[3] ce_per_layer;
    u32 *[3] ue_per_layer;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mem_ctl_info {
    struct device dev;
    struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    u32 *[3] ce_per_layer;
    u32 *[3] ue_per_layer;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mem_ctl_info {
    struct device dev;
    struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    u32 *[3] ce_per_layer;
    u32 *[3] ue_per_layer;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mem_ctl_info {
    struct device dev;
    struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    u32 *[3] ce_per_layer;
    u32 *[3] ue_per_layer;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mem_ctl_info {
    struct device dev;
    struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    u32 *[3] ce_per_layer;
    u32 *[3] ue_per_layer;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mem_ctl_info {
    struct device dev;
    struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    u32 *[3] ce_per_layer;
    u32 *[3] ue_per_layer;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mem_ctl_info {
    struct device dev;
    struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mem_ctl_info {
    struct device dev;
    struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mem_ctl_info {
    struct device dev;
    struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mem_ctl_info {
    struct device dev;
    struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mem_ctl_info {
    struct device dev;
    struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mem_ctl_info {
    struct device dev;
    struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mem_ctl_info {
    struct device dev;
    struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mem_ctl_info {
    struct device dev;
    const struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
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
struct mem_ctl_info {
    struct device dev;
    struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    u32 *[3] ce_per_layer;
    u32 *[3] ue_per_layer;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mem_ctl_info {
    struct device dev;
    struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    u32 *[3] ce_per_layer;
    u32 *[3] ue_per_layer;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mem_ctl_info {
    struct device dev;
    struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    u32 *[3] ce_per_layer;
    u32 *[3] ue_per_layer;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mem_ctl_info {
    struct device dev;
    struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    u32 *[3] ce_per_layer;
    u32 *[3] ue_per_layer;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
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
struct mem_ctl_info {
    struct device dev;
    struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    u32 *[3] ce_per_layer;
    u32 *[3] ue_per_layer;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct mem_ctl_info {
    struct device dev;
    struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    u32 *[3] ce_per_layer;
    u32 *[3] ue_per_layer;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mem_ctl_info {
    struct device dev;
    struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    u32 *[3] ce_per_layer;
    u32 *[3] ue_per_layer;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mem_ctl_info {
    struct device dev;
    struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    u32 *[3] ce_per_layer;
    u32 *[3] ue_per_layer;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct mem_ctl_info {
    struct device dev;
    struct bus_type * bus;
    struct list_head link;
    struct module * owner;
    long unsigned int mtype_cap;
    long unsigned int edac_ctl_cap;
    long unsigned int edac_cap;
    long unsigned int scrub_cap;
    enum scrub_type scrub_mode;
    int (*)(struct mem_ctl_info *, u32) set_sdram_scrub_rate;
    int (*)(struct mem_ctl_info *) get_sdram_scrub_rate;
    void (*)(struct mem_ctl_info *) edac_check;
    long unsigned int (*)(struct mem_ctl_info *, long unsigned int) ctl_page_to_phys;
    int mc_idx;
    struct csrow_info * * csrows;
    unsigned int nr_csrows;
    unsigned int num_cschannel;
    unsigned int n_layers;
    struct edac_mc_layer * layers;
    bool csbased;
    unsigned int tot_dimms;
    struct dimm_info * * dimms;
    struct device * pdev;
    const char * mod_name;
    const char * mod_ver;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    u32 ce_noinfo_count;
    u32 ue_noinfo_count;
    u32 ue_mc;
    u32 ce_mc;
    u32 *[3] ce_per_layer;
    u32 *[3] ue_per_layer;
    struct completion complete;
    const struct mcidev_sysfs_attribute * mc_driver_sysfs_attributes;
    struct delayed_work work;
    struct edac_raw_error_desc error_desc;
    int op_state;
    struct dentry * debugfs;
    u8[3] fake_inject_layer;
    bool fake_inject_ue;
    u16 fake_inject_count;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>const char * mod_ver</code>
</li>
</ul>
</details>
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
<b>Field removed. </b>
<code>u32 *[3] ce_per_layer</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 *[3] ue_per_layer</code>
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
<b>Field type changed. </b>
<code>struct bus_type * bus</code> ➡️ <code>const struct bus_type * bus</code>
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
