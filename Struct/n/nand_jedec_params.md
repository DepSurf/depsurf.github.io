# Struct: <code>nand_jedec_params</code>

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
struct nand_jedec_params {
    u8[4] sig;
    __le16 revision;
    __le16 features;
    u8[3] opt_cmd;
    __le16 sec_cmd;
    u8 num_of_param_pages;
    u8[18] reserved0;
    char[12] manufacturer;
    char[20] model;
    u8[6] jedec_id;
    u8[10] reserved1;
    __le32 byte_per_page;
    __le16 spare_bytes_per_page;
    u8[6] reserved2;
    __le32 pages_per_block;
    __le32 blocks_per_lun;
    u8 lun_count;
    u8 addr_cycles;
    u8 bits_per_cell;
    u8 programs_per_page;
    u8 multi_plane_addr;
    u8 multi_plane_op_attr;
    u8[38] reserved3;
    __le16 async_sdr_speed_grade;
    __le16 toggle_ddr_speed_grade;
    __le16 sync_ddr_speed_grade;
    u8 async_sdr_features;
    u8 toggle_ddr_features;
    u8 sync_ddr_features;
    __le16 t_prog;
    __le16 t_bers;
    __le16 t_r;
    __le16 t_r_multi_plane;
    __le16 t_ccs;
    __le16 io_pin_capacitance_typ;
    __le16 input_pin_capacitance_typ;
    __le16 clk_pin_capacitance_typ;
    u8 driver_strength_support;
    __le16 t_adl;
    u8[36] reserved4;
    u8 guaranteed_good_blocks;
    __le16 guaranteed_block_endurance;
    struct jedec_ecc_info[4] ecc_info;
    u8[29] reserved5;
    u8[148] reserved6;
    __le16 vendor_rev_num;
    u8[88] reserved7;
    __le16 crc;
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
struct nand_jedec_params {
    u8[4] sig;
    __le16 revision;
    __le16 features;
    u8[3] opt_cmd;
    __le16 sec_cmd;
    u8 num_of_param_pages;
    u8[18] reserved0;
    char[12] manufacturer;
    char[20] model;
    u8[6] jedec_id;
    u8[10] reserved1;
    __le32 byte_per_page;
    __le16 spare_bytes_per_page;
    u8[6] reserved2;
    __le32 pages_per_block;
    __le32 blocks_per_lun;
    u8 lun_count;
    u8 addr_cycles;
    u8 bits_per_cell;
    u8 programs_per_page;
    u8 multi_plane_addr;
    u8 multi_plane_op_attr;
    u8[38] reserved3;
    __le16 async_sdr_speed_grade;
    __le16 toggle_ddr_speed_grade;
    __le16 sync_ddr_speed_grade;
    u8 async_sdr_features;
    u8 toggle_ddr_features;
    u8 sync_ddr_features;
    __le16 t_prog;
    __le16 t_bers;
    __le16 t_r;
    __le16 t_r_multi_plane;
    __le16 t_ccs;
    __le16 io_pin_capacitance_typ;
    __le16 input_pin_capacitance_typ;
    __le16 clk_pin_capacitance_typ;
    u8 driver_strength_support;
    __le16 t_adl;
    u8[36] reserved4;
    u8 guaranteed_good_blocks;
    __le16 guaranteed_block_endurance;
    struct jedec_ecc_info[4] ecc_info;
    u8[29] reserved5;
    u8[148] reserved6;
    __le16 vendor_rev_num;
    u8[88] reserved7;
    __le16 crc;
}
```
</details>
</li>
</ul>
