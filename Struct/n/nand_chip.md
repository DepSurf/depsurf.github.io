# Struct: <code>nand_chip</code>

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
struct nand_chip {
    struct nand_device base;
    struct nand_legacy legacy;
    int (*)(struct nand_chip *, int) setup_read_retry;
    unsigned int options;
    unsigned int bbt_options;
    int page_shift;
    int phys_erase_shift;
    int bbt_erase_shift;
    int chip_shift;
    int pagemask;
    u8 * data_buf;
    struct (anon) pagecache;
    int subpagesize;
    int onfi_timing_mode_default;
    unsigned int badblockpos;
    int badblockbits;
    struct nand_id id;
    struct nand_parameters parameters;
    struct nand_data_interface data_interface;
    int cur_cs;
    int read_retries;
    struct mutex lock;
    unsigned int suspended;
    uint8_t * oob_poi;
    struct nand_controller * controller;
    struct nand_ecc_ctrl ecc;
    long unsigned int buf_align;
    uint8_t * bbt;
    struct nand_bbt_descr * bbt_td;
    struct nand_bbt_descr * bbt_md;
    struct nand_bbt_descr * badblock_pattern;
    void * priv;
    struct (anon) manufacturer;
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
struct nand_chip {
    struct nand_device base;
    struct nand_legacy legacy;
    int (*)(struct nand_chip *, int) setup_read_retry;
    unsigned int options;
    unsigned int bbt_options;
    int page_shift;
    int phys_erase_shift;
    int bbt_erase_shift;
    int chip_shift;
    int pagemask;
    u8 * data_buf;
    struct (anon) pagecache;
    int subpagesize;
    int onfi_timing_mode_default;
    unsigned int badblockpos;
    int badblockbits;
    struct nand_id id;
    struct nand_parameters parameters;
    struct nand_data_interface data_interface;
    int cur_cs;
    int read_retries;
    struct mutex lock;
    unsigned int suspended;
    uint8_t * oob_poi;
    struct nand_controller * controller;
    struct nand_ecc_ctrl ecc;
    long unsigned int buf_align;
    uint8_t * bbt;
    struct nand_bbt_descr * bbt_td;
    struct nand_bbt_descr * bbt_md;
    struct nand_bbt_descr * badblock_pattern;
    void * priv;
    struct (anon) manufacturer;
}
```
</details>
</li>
</ul>
