# Struct: <code>nand_legacy</code>

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
struct nand_legacy {
    void * IO_ADDR_R;
    void * IO_ADDR_W;
    void (*)(struct nand_chip *, int) select_chip;
    u8 (*)(struct nand_chip *) read_byte;
    void (*)(struct nand_chip *, u8) write_byte;
    void (*)(struct nand_chip *, const u8 *, int) write_buf;
    void (*)(struct nand_chip *, u8 *, int) read_buf;
    void (*)(struct nand_chip *, int, unsigned int) cmd_ctrl;
    void (*)(struct nand_chip *, unsigned int, int, int) cmdfunc;
    int (*)(struct nand_chip *) dev_ready;
    int (*)(struct nand_chip *) waitfunc;
    int (*)(struct nand_chip *, loff_t) block_bad;
    int (*)(struct nand_chip *, loff_t) block_markbad;
    int (*)(struct nand_chip *, int, u8 *) set_features;
    int (*)(struct nand_chip *, int, u8 *) get_features;
    int chip_delay;
    struct nand_controller dummy_controller;
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
struct nand_legacy {
    void * IO_ADDR_R;
    void * IO_ADDR_W;
    void (*)(struct nand_chip *, int) select_chip;
    u8 (*)(struct nand_chip *) read_byte;
    void (*)(struct nand_chip *, u8) write_byte;
    void (*)(struct nand_chip *, const u8 *, int) write_buf;
    void (*)(struct nand_chip *, u8 *, int) read_buf;
    void (*)(struct nand_chip *, int, unsigned int) cmd_ctrl;
    void (*)(struct nand_chip *, unsigned int, int, int) cmdfunc;
    int (*)(struct nand_chip *) dev_ready;
    int (*)(struct nand_chip *) waitfunc;
    int (*)(struct nand_chip *, loff_t) block_bad;
    int (*)(struct nand_chip *, loff_t) block_markbad;
    int (*)(struct nand_chip *, int, u8 *) set_features;
    int (*)(struct nand_chip *, int, u8 *) get_features;
    int chip_delay;
    struct nand_controller dummy_controller;
}
```
</details>
</li>
</ul>
