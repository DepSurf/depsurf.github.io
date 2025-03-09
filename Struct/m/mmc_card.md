# Struct: <code>mmc_card</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    unsigned int sdio_funcs;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    unsigned int sdio_funcs;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    unsigned int sdio_funcs;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    bool reenable_cmdq;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    unsigned int sdio_funcs;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
    unsigned int bouncesz;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    bool reenable_cmdq;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    unsigned int sdio_funcs;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
    unsigned int bouncesz;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int quirk_max_rate;
    bool reenable_cmdq;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    unsigned int sdio_funcs;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
    unsigned int bouncesz;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int quirk_max_rate;
    bool reenable_cmdq;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    unsigned int sdio_funcs;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
    unsigned int bouncesz;
    struct workqueue_struct * complete_wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int quirk_max_rate;
    bool reenable_cmdq;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    unsigned int erase_arg;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    unsigned int sdio_funcs;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
    unsigned int bouncesz;
    struct workqueue_struct * complete_wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int quirk_max_rate;
    bool reenable_cmdq;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    unsigned int erase_arg;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    unsigned int sdio_funcs;
    atomic_t sdio_funcs_probed;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
    unsigned int bouncesz;
    struct workqueue_struct * complete_wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int quirk_max_rate;
    bool reenable_cmdq;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    unsigned int erase_arg;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    unsigned int sdio_funcs;
    atomic_t sdio_funcs_probed;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
    unsigned int bouncesz;
    struct workqueue_struct * complete_wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int quirk_max_rate;
    bool reenable_cmdq;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    unsigned int erase_arg;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    unsigned int sdio_funcs;
    atomic_t sdio_funcs_probed;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    u8 major_rev;
    u8 minor_rev;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
    unsigned int bouncesz;
    struct workqueue_struct * complete_wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int quirk_max_rate;
    bool reenable_cmdq;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    unsigned int erase_arg;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    unsigned int sdio_funcs;
    atomic_t sdio_funcs_probed;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    u8 major_rev;
    u8 minor_rev;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
    struct workqueue_struct * complete_wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int quirk_max_rate;
    bool reenable_cmdq;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    unsigned int erase_arg;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    struct sd_ext_reg ext_power;
    struct sd_ext_reg ext_perf;
    unsigned int sdio_funcs;
    atomic_t sdio_funcs_probed;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    u8 major_rev;
    u8 minor_rev;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
    struct workqueue_struct * complete_wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int quirk_max_rate;
    bool reenable_cmdq;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    unsigned int erase_arg;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    struct sd_ext_reg ext_power;
    struct sd_ext_reg ext_perf;
    unsigned int sdio_funcs;
    atomic_t sdio_funcs_probed;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    u8 major_rev;
    u8 minor_rev;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
    struct workqueue_struct * complete_wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int quirk_max_rate;
    bool reenable_cmdq;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    unsigned int erase_arg;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    struct sd_ext_reg ext_power;
    struct sd_ext_reg ext_perf;
    unsigned int sdio_funcs;
    atomic_t sdio_funcs_probed;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    u8 major_rev;
    u8 minor_rev;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
    struct workqueue_struct * complete_wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int quirk_max_rate;
    bool reenable_cmdq;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    unsigned int erase_arg;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    struct sd_ext_reg ext_power;
    struct sd_ext_reg ext_perf;
    unsigned int sdio_funcs;
    atomic_t sdio_funcs_probed;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    u8 major_rev;
    u8 minor_rev;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
    struct workqueue_struct * complete_wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int quirk_max_rate;
    bool written_flag;
    bool reenable_cmdq;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    unsigned int erase_arg;
    u8 erased_byte;
    unsigned int wp_grp_size;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    struct sd_ext_reg ext_power;
    struct sd_ext_reg ext_perf;
    unsigned int sdio_funcs;
    atomic_t sdio_funcs_probed;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    u8 major_rev;
    u8 minor_rev;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
    struct workqueue_struct * complete_wq;
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
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int quirk_max_rate;
    bool reenable_cmdq;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    unsigned int erase_arg;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    unsigned int sdio_funcs;
    atomic_t sdio_funcs_probed;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
    unsigned int bouncesz;
    struct workqueue_struct * complete_wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int quirk_max_rate;
    bool reenable_cmdq;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    unsigned int erase_arg;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    unsigned int sdio_funcs;
    atomic_t sdio_funcs_probed;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
    unsigned int bouncesz;
    struct workqueue_struct * complete_wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int quirk_max_rate;
    bool reenable_cmdq;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    unsigned int erase_arg;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    unsigned int sdio_funcs;
    atomic_t sdio_funcs_probed;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
    unsigned int bouncesz;
    struct workqueue_struct * complete_wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int quirk_max_rate;
    bool reenable_cmdq;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    unsigned int erase_arg;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    unsigned int sdio_funcs;
    atomic_t sdio_funcs_probed;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
    unsigned int bouncesz;
    struct workqueue_struct * complete_wq;
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
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int quirk_max_rate;
    bool reenable_cmdq;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    unsigned int erase_arg;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    unsigned int sdio_funcs;
    atomic_t sdio_funcs_probed;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
    unsigned int bouncesz;
    struct workqueue_struct * complete_wq;
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
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int quirk_max_rate;
    bool reenable_cmdq;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    unsigned int erase_arg;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    unsigned int sdio_funcs;
    atomic_t sdio_funcs_probed;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
    unsigned int bouncesz;
    struct workqueue_struct * complete_wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int quirk_max_rate;
    bool reenable_cmdq;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    unsigned int erase_arg;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    unsigned int sdio_funcs;
    atomic_t sdio_funcs_probed;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
    unsigned int bouncesz;
    struct workqueue_struct * complete_wq;
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
<code>u32[16] raw_ssr</code>
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
<code>bool reenable_cmdq</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int bouncesz</code>
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
<code>unsigned int quirk_max_rate</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct workqueue_struct * complete_wq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int erase_arg</code>
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
<code>atomic_t sdio_funcs_probed</code>
</li>
</ul>
</details>
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
<code>u8 major_rev</code>
</li>
<li>
<b>Field added. </b>
<code>u8 minor_rev</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int bouncesz</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct sd_ext_reg ext_power</code>
</li>
<li>
<b>Field added. </b>
<code>struct sd_ext_reg ext_perf</code>
</li>
</ul>
</details>
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
<b>Field added. </b>
<code>bool written_flag</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int wp_grp_size</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct mmc_card {
    struct mmc_host * host;
    struct device dev;
    u32 ocr;
    unsigned int rca;
    unsigned int type;
    unsigned int state;
    unsigned int quirks;
    unsigned int quirk_max_rate;
    bool reenable_cmdq;
    unsigned int erase_size;
    unsigned int erase_shift;
    unsigned int pref_erase;
    unsigned int eg_boundary;
    unsigned int erase_arg;
    u8 erased_byte;
    u32[4] raw_cid;
    u32[4] raw_csd;
    u32[2] raw_scr;
    u32[16] raw_ssr;
    struct mmc_cid cid;
    struct mmc_csd csd;
    struct mmc_ext_csd ext_csd;
    struct sd_scr scr;
    struct sd_ssr ssr;
    struct sd_switch_caps sw_caps;
    unsigned int sdio_funcs;
    atomic_t sdio_funcs_probed;
    struct sdio_cccr cccr;
    struct sdio_cis cis;
    struct sdio_func *[7] sdio_func;
    struct sdio_func * sdio_single_irq;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
    unsigned int sd_bus_speed;
    unsigned int mmc_avail_type;
    unsigned int drive_strength;
    struct dentry * debugfs_root;
    struct mmc_part[7] part;
    unsigned int nr_parts;
    unsigned int bouncesz;
    struct workqueue_struct * complete_wq;
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
