# Struct: <code>nand_ecc_ctrl</code>

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
struct nand_ecc_ctrl {
    nand_ecc_modes_t mode;
    enum nand_ecc_algo algo;
    int steps;
    int size;
    int bytes;
    int total;
    int strength;
    int prepad;
    int postpad;
    unsigned int options;
    void * priv;
    u8 * calc_buf;
    u8 * code_buf;
    void (*)(struct nand_chip *, int) hwctl;
    int (*)(struct nand_chip *, const uint8_t *, uint8_t *) calculate;
    int (*)(struct nand_chip *, uint8_t *, uint8_t *, uint8_t *) correct;
    int (*)(struct nand_chip *, uint8_t *, int, int) read_page_raw;
    int (*)(struct nand_chip *, const uint8_t *, int, int) write_page_raw;
    int (*)(struct nand_chip *, uint8_t *, int, int) read_page;
    int (*)(struct nand_chip *, uint32_t, uint32_t, uint8_t *, int) read_subpage;
    int (*)(struct nand_chip *, uint32_t, uint32_t, const uint8_t *, int, int) write_subpage;
    int (*)(struct nand_chip *, const uint8_t *, int, int) write_page;
    int (*)(struct nand_chip *, int) write_oob_raw;
    int (*)(struct nand_chip *, int) read_oob_raw;
    int (*)(struct nand_chip *, int) read_oob;
    int (*)(struct nand_chip *, int) write_oob;
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
struct nand_ecc_ctrl {
    nand_ecc_modes_t mode;
    enum nand_ecc_algo algo;
    int steps;
    int size;
    int bytes;
    int total;
    int strength;
    int prepad;
    int postpad;
    unsigned int options;
    void * priv;
    u8 * calc_buf;
    u8 * code_buf;
    void (*)(struct nand_chip *, int) hwctl;
    int (*)(struct nand_chip *, const uint8_t *, uint8_t *) calculate;
    int (*)(struct nand_chip *, uint8_t *, uint8_t *, uint8_t *) correct;
    int (*)(struct nand_chip *, uint8_t *, int, int) read_page_raw;
    int (*)(struct nand_chip *, const uint8_t *, int, int) write_page_raw;
    int (*)(struct nand_chip *, uint8_t *, int, int) read_page;
    int (*)(struct nand_chip *, uint32_t, uint32_t, uint8_t *, int) read_subpage;
    int (*)(struct nand_chip *, uint32_t, uint32_t, const uint8_t *, int, int) write_subpage;
    int (*)(struct nand_chip *, const uint8_t *, int, int) write_page;
    int (*)(struct nand_chip *, int) write_oob_raw;
    int (*)(struct nand_chip *, int) read_oob_raw;
    int (*)(struct nand_chip *, int) read_oob;
    int (*)(struct nand_chip *, int) write_oob;
}
```
</details>
</li>
</ul>
