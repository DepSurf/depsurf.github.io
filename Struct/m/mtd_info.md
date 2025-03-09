# Struct: <code>mtd_info</code>

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
struct mtd_info {
    u_char type;
    uint32_t flags;
    uint32_t orig_flags;
    uint64_t size;
    uint32_t erasesize;
    uint32_t writesize;
    uint32_t writebufsize;
    uint32_t oobsize;
    uint32_t oobavail;
    unsigned int erasesize_shift;
    unsigned int writesize_shift;
    unsigned int erasesize_mask;
    unsigned int writesize_mask;
    unsigned int bitflip_threshold;
    const char * name;
    int index;
    const struct mtd_ooblayout_ops * ooblayout;
    const struct mtd_pairing_scheme * pairing;
    unsigned int ecc_step_size;
    unsigned int ecc_strength;
    int numeraseregions;
    struct mtd_erase_region_info * eraseregions;
    int (*)(struct mtd_info *, struct erase_info *) _erase;
    int (*)(struct mtd_info *, loff_t, size_t, size_t *, void * *, resource_size_t *) _point;
    int (*)(struct mtd_info *, loff_t, size_t) _unpoint;
    int (*)(struct mtd_info *, loff_t, size_t, size_t *, u_char *) _read;
    int (*)(struct mtd_info *, loff_t, size_t, size_t *, const u_char *) _write;
    int (*)(struct mtd_info *, loff_t, size_t, size_t *, const u_char *) _panic_write;
    int (*)(struct mtd_info *, loff_t, struct mtd_oob_ops *) _read_oob;
    int (*)(struct mtd_info *, loff_t, struct mtd_oob_ops *) _write_oob;
    int (*)(struct mtd_info *, size_t, size_t *, struct otp_info *) _get_fact_prot_info;
    int (*)(struct mtd_info *, loff_t, size_t, size_t *, u_char *) _read_fact_prot_reg;
    int (*)(struct mtd_info *, size_t, size_t *, struct otp_info *) _get_user_prot_info;
    int (*)(struct mtd_info *, loff_t, size_t, size_t *, u_char *) _read_user_prot_reg;
    int (*)(struct mtd_info *, loff_t, size_t, size_t *, u_char *) _write_user_prot_reg;
    int (*)(struct mtd_info *, loff_t, size_t) _lock_user_prot_reg;
    int (*)(struct mtd_info *, const struct kvec *, long unsigned int, loff_t, size_t *) _writev;
    void (*)(struct mtd_info *) _sync;
    int (*)(struct mtd_info *, loff_t, uint64_t) _lock;
    int (*)(struct mtd_info *, loff_t, uint64_t) _unlock;
    int (*)(struct mtd_info *, loff_t, uint64_t) _is_locked;
    int (*)(struct mtd_info *, loff_t) _block_isreserved;
    int (*)(struct mtd_info *, loff_t) _block_isbad;
    int (*)(struct mtd_info *, loff_t) _block_markbad;
    int (*)(struct mtd_info *, loff_t, size_t) _max_bad_blocks;
    int (*)(struct mtd_info *) _suspend;
    void (*)(struct mtd_info *) _resume;
    void (*)(struct mtd_info *) _reboot;
    int (*)(struct mtd_info *) _get_device;
    void (*)(struct mtd_info *) _put_device;
    bool oops_panic_write;
    struct notifier_block reboot_notifier;
    struct mtd_ecc_stats ecc_stats;
    int subpage_sft;
    void * priv;
    struct module * owner;
    struct device dev;
    int usecount;
    struct mtd_debug_info dbg;
    struct nvmem_device * nvmem;
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
struct mtd_info {
    u_char type;
    uint32_t flags;
    uint32_t orig_flags;
    uint64_t size;
    uint32_t erasesize;
    uint32_t writesize;
    uint32_t writebufsize;
    uint32_t oobsize;
    uint32_t oobavail;
    unsigned int erasesize_shift;
    unsigned int writesize_shift;
    unsigned int erasesize_mask;
    unsigned int writesize_mask;
    unsigned int bitflip_threshold;
    const char * name;
    int index;
    const struct mtd_ooblayout_ops * ooblayout;
    const struct mtd_pairing_scheme * pairing;
    unsigned int ecc_step_size;
    unsigned int ecc_strength;
    int numeraseregions;
    struct mtd_erase_region_info * eraseregions;
    int (*)(struct mtd_info *, struct erase_info *) _erase;
    int (*)(struct mtd_info *, loff_t, size_t, size_t *, void * *, resource_size_t *) _point;
    int (*)(struct mtd_info *, loff_t, size_t) _unpoint;
    int (*)(struct mtd_info *, loff_t, size_t, size_t *, u_char *) _read;
    int (*)(struct mtd_info *, loff_t, size_t, size_t *, const u_char *) _write;
    int (*)(struct mtd_info *, loff_t, size_t, size_t *, const u_char *) _panic_write;
    int (*)(struct mtd_info *, loff_t, struct mtd_oob_ops *) _read_oob;
    int (*)(struct mtd_info *, loff_t, struct mtd_oob_ops *) _write_oob;
    int (*)(struct mtd_info *, size_t, size_t *, struct otp_info *) _get_fact_prot_info;
    int (*)(struct mtd_info *, loff_t, size_t, size_t *, u_char *) _read_fact_prot_reg;
    int (*)(struct mtd_info *, size_t, size_t *, struct otp_info *) _get_user_prot_info;
    int (*)(struct mtd_info *, loff_t, size_t, size_t *, u_char *) _read_user_prot_reg;
    int (*)(struct mtd_info *, loff_t, size_t, size_t *, u_char *) _write_user_prot_reg;
    int (*)(struct mtd_info *, loff_t, size_t) _lock_user_prot_reg;
    int (*)(struct mtd_info *, const struct kvec *, long unsigned int, loff_t, size_t *) _writev;
    void (*)(struct mtd_info *) _sync;
    int (*)(struct mtd_info *, loff_t, uint64_t) _lock;
    int (*)(struct mtd_info *, loff_t, uint64_t) _unlock;
    int (*)(struct mtd_info *, loff_t, uint64_t) _is_locked;
    int (*)(struct mtd_info *, loff_t) _block_isreserved;
    int (*)(struct mtd_info *, loff_t) _block_isbad;
    int (*)(struct mtd_info *, loff_t) _block_markbad;
    int (*)(struct mtd_info *, loff_t, size_t) _max_bad_blocks;
    int (*)(struct mtd_info *) _suspend;
    void (*)(struct mtd_info *) _resume;
    void (*)(struct mtd_info *) _reboot;
    int (*)(struct mtd_info *) _get_device;
    void (*)(struct mtd_info *) _put_device;
    bool oops_panic_write;
    struct notifier_block reboot_notifier;
    struct mtd_ecc_stats ecc_stats;
    int subpage_sft;
    void * priv;
    struct module * owner;
    struct device dev;
    int usecount;
    struct mtd_debug_info dbg;
    struct nvmem_device * nvmem;
}
```
</details>
</li>
</ul>
