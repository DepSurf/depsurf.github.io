# Struct: <code>pmc_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regmap;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    bool init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regmap;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    bool init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regmap;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    bool init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regbase;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    bool has_slp_s0_res;
    int pmc_xram_read_bit;
    struct mutex lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regbase;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    int pmc_xram_read_bit;
    struct mutex lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regbase;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    int pmc_xram_read_bit;
    struct mutex lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regbase;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    int pmc_xram_read_bit;
    struct mutex lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regbase;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    int pmc_xram_read_bit;
    struct mutex lock;
    bool check_counters;
    u64 pc10_counter;
    u64 s0ix_counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regbase;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    int pmc_xram_read_bit;
    struct mutex lock;
    bool check_counters;
    u64 pc10_counter;
    u64 s0ix_counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regbase;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    int pmc_xram_read_bit;
    struct mutex lock;
    bool check_counters;
    u64 pc10_counter;
    u64 s0ix_counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regbase;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    int pmc_xram_read_bit;
    struct mutex lock;
    bool check_counters;
    u64 pc10_counter;
    u64 s0ix_counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regbase;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    int pmc_xram_read_bit;
    struct mutex lock;
    bool check_counters;
    u64 pc10_counter;
    u64 s0ix_counter;
    int num_lpm_modes;
    int[8] lpm_en_modes;
    u32 * lpm_req_regs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regbase;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    int pmc_xram_read_bit;
    struct mutex lock;
    bool check_counters;
    u64 pc10_counter;
    u64 s0ix_counter;
    int num_lpm_modes;
    int[8] lpm_en_modes;
    u32 * lpm_req_regs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regbase;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    int pmc_xram_read_bit;
    struct mutex lock;
    bool check_counters;
    u64 pc10_counter;
    u64 s0ix_counter;
    int num_lpm_modes;
    int[8] lpm_en_modes;
    u32 * lpm_req_regs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regbase;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    struct platform_device * pdev;
    int pmc_xram_read_bit;
    struct mutex lock;
    bool check_counters;
    u64 pc10_counter;
    u64 s0ix_counter;
    int num_lpm_modes;
    int[8] lpm_en_modes;
    u32 * lpm_req_regs;
    void (*)(struct pmc_dev *) core_configure;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pmc_dev {
    struct pmc *[3] pmcs;
    struct dentry * dbgfs_dir;
    struct platform_device * pdev;
    struct pci_dev * ssram_pcidev;
    int pmc_xram_read_bit;
    struct mutex lock;
    u64 pc10_counter;
    u64 s0ix_counter;
    int num_lpm_modes;
    int[8] lpm_en_modes;
    int (*)(struct pmc_dev *) resume;
    bool has_die_c6;
    u32 die_c6_offset;
    struct telem_endpoint * punit_ep;
    struct pmc_info * regmap_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regmap;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    bool init;
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
struct pmc_dev {
    u32 base_addr;
    void * regbase;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    int pmc_xram_read_bit;
    struct mutex lock;
    bool check_counters;
    u64 pc10_counter;
    u64 s0ix_counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regbase;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    int pmc_xram_read_bit;
    struct mutex lock;
    bool check_counters;
    u64 pc10_counter;
    u64 s0ix_counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regbase;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    int pmc_xram_read_bit;
    struct mutex lock;
    bool check_counters;
    u64 pc10_counter;
    u64 s0ix_counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regbase;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    int pmc_xram_read_bit;
    struct mutex lock;
    bool check_counters;
    u64 pc10_counter;
    u64 s0ix_counter;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * regbase</code>
</li>
<li>
<b>Field added. </b>
<code>bool has_slp_s0_res</code>
</li>
<li>
<b>Field added. </b>
<code>int pmc_xram_read_bit</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex lock</code>
</li>
<li>
<b>Field removed. </b>
<code>void * regmap</code>
</li>
<li>
<b>Field removed. </b>
<code>bool init</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool has_slp_s0_res</code>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool check_counters</code>
</li>
<li>
<b>Field added. </b>
<code>u64 pc10_counter</code>
</li>
<li>
<b>Field added. </b>
<code>u64 s0ix_counter</code>
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
<b>Field added. </b>
<code>int num_lpm_modes</code>
</li>
<li>
<b>Field added. </b>
<code>int[8] lpm_en_modes</code>
</li>
<li>
<b>Field added. </b>
<code>u32 * lpm_req_regs</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct platform_device * pdev</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct pmc_dev *) core_configure</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct pmc *[3] pmcs</code>
</li>
<li>
<b>Field added. </b>
<code>struct pci_dev * ssram_pcidev</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct pmc_dev *) resume</code>
</li>
<li>
<b>Field added. </b>
<code>bool has_die_c6</code>
</li>
<li>
<b>Field added. </b>
<code>u32 die_c6_offset</code>
</li>
<li>
<b>Field added. </b>
<code>struct telem_endpoint * punit_ep</code>
</li>
<li>
<b>Field added. </b>
<code>struct pmc_info * regmap_list</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 base_addr</code>
</li>
<li>
<b>Field removed. </b>
<code>void * regbase</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct pmc_reg_map * map</code>
</li>
<li>
<b>Field removed. </b>
<code>bool check_counters</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 * lpm_req_regs</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct pmc_dev *) core_configure</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 base_addr</code>
</li>
<li>
<b>Field added. </b>
<code>void * regmap</code>
</li>
<li>
<b>Field added. </b>
<code>const struct pmc_reg_map * map</code>
</li>
<li>
<b>Field added. </b>
<code>bool init</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pmc *[3] pmcs</code>
</li>
<li>
<b>Field removed. </b>
<code>struct platform_device * pdev</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pci_dev * ssram_pcidev</code>
</li>
<li>
<b>Field removed. </b>
<code>int pmc_xram_read_bit</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex lock</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 pc10_counter</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 s0ix_counter</code>
</li>
<li>
<b>Field removed. </b>
<code>int num_lpm_modes</code>
</li>
<li>
<b>Field removed. </b>
<code>int[8] lpm_en_modes</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct pmc_dev *) resume</code>
</li>
<li>
<b>Field removed. </b>
<code>bool has_die_c6</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 die_c6_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>struct telem_endpoint * punit_ep</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pmc_info * regmap_list</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regbase;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    int pmc_xram_read_bit;
    struct mutex lock;
    bool check_counters;
    u64 pc10_counter;
    u64 s0ix_counter;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regbase;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    int pmc_xram_read_bit;
    struct mutex lock;
    bool check_counters;
    u64 pc10_counter;
    u64 s0ix_counter;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regbase;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    int pmc_xram_read_bit;
    struct mutex lock;
    bool check_counters;
    u64 pc10_counter;
    u64 s0ix_counter;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct pmc_dev {
    u32 base_addr;
    void * regbase;
    const struct pmc_reg_map * map;
    struct dentry * dbgfs_dir;
    int pmc_xram_read_bit;
    struct mutex lock;
    bool check_counters;
    u64 pc10_counter;
    u64 s0ix_counter;
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
