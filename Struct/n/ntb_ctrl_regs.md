# Struct: <code>ntb_ctrl_regs</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ntb_ctrl_regs {
    u32 partition_status;
    u32 partition_op;
    u32 partition_ctrl;
    u32 bar_setup;
    u32 bar_error;
    u16 lut_table_entries;
    u16 lut_table_offset;
    u32 lut_error;
    u16 req_id_table_size;
    u16 req_id_table_offset;
    u32 req_id_error;
    u32[7] reserved1;
    struct (anon)[6] bar_entry;
    u32[216] reserved2;
    u32[256] req_id_table;
    u32[512] reserved3;
    u64[512] lut_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ntb_ctrl_regs {
    u32 partition_status;
    u32 partition_op;
    u32 partition_ctrl;
    u32 bar_setup;
    u32 bar_error;
    u16 lut_table_entries;
    u16 lut_table_offset;
    u32 lut_error;
    u16 req_id_table_size;
    u16 req_id_table_offset;
    u32 req_id_error;
    u32[7] reserved1;
    struct (anon)[6] bar_entry;
    struct (anon)[6] bar_ext_entry;
    u32[192] reserved2;
    u32[512] req_id_table;
    u32[256] reserved3;
    u64[512] lut_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ntb_ctrl_regs {
    u32 partition_status;
    u32 partition_op;
    u32 partition_ctrl;
    u32 bar_setup;
    u32 bar_error;
    u16 lut_table_entries;
    u16 lut_table_offset;
    u32 lut_error;
    u16 req_id_table_size;
    u16 req_id_table_offset;
    u32 req_id_error;
    u32[7] reserved1;
    struct (anon)[6] bar_entry;
    struct (anon)[6] bar_ext_entry;
    u32[192] reserved2;
    u32[512] req_id_table;
    u32[256] reserved3;
    u64[512] lut_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ntb_ctrl_regs {
    u32 partition_status;
    u32 partition_op;
    u32 partition_ctrl;
    u32 bar_setup;
    u32 bar_error;
    u16 lut_table_entries;
    u16 lut_table_offset;
    u32 lut_error;
    u16 req_id_table_size;
    u16 req_id_table_offset;
    u32 req_id_error;
    u32[7] reserved1;
    struct (anon)[6] bar_entry;
    struct (anon)[6] bar_ext_entry;
    u32[192] reserved2;
    u32[512] req_id_table;
    u32[256] reserved3;
    u64[512] lut_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ntb_ctrl_regs {
    u32 partition_status;
    u32 partition_op;
    u32 partition_ctrl;
    u32 bar_setup;
    u32 bar_error;
    u16 lut_table_entries;
    u16 lut_table_offset;
    u32 lut_error;
    u16 req_id_table_size;
    u16 req_id_table_offset;
    u32 req_id_error;
    u32[7] reserved1;
    struct (anon)[6] bar_entry;
    struct (anon)[6] bar_ext_entry;
    u32[192] reserved2;
    u32[512] req_id_table;
    u32[256] reserved3;
    u64[512] lut_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ntb_ctrl_regs {
    u32 partition_status;
    u32 partition_op;
    u32 partition_ctrl;
    u32 bar_setup;
    u32 bar_error;
    u16 lut_table_entries;
    u16 lut_table_offset;
    u32 lut_error;
    u16 req_id_table_size;
    u16 req_id_table_offset;
    u32 req_id_error;
    u32[7] reserved1;
    struct (anon)[6] bar_entry;
    struct (anon)[6] bar_ext_entry;
    u32[192] reserved2;
    u32[512] req_id_table;
    u32[256] reserved3;
    u64[512] lut_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ntb_ctrl_regs {
    u32 partition_status;
    u32 partition_op;
    u32 partition_ctrl;
    u32 bar_setup;
    u32 bar_error;
    u16 lut_table_entries;
    u16 lut_table_offset;
    u32 lut_error;
    u16 req_id_table_size;
    u16 req_id_table_offset;
    u32 req_id_error;
    u32[7] reserved1;
    struct (anon)[6] bar_entry;
    struct (anon)[6] bar_ext_entry;
    u32[192] reserved2;
    u32[512] req_id_table;
    u32[256] reserved3;
    u64[512] lut_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ntb_ctrl_regs {
    u32 partition_status;
    u32 partition_op;
    u32 partition_ctrl;
    u32 bar_setup;
    u32 bar_error;
    u16 lut_table_entries;
    u16 lut_table_offset;
    u32 lut_error;
    u16 req_id_table_size;
    u16 req_id_table_offset;
    u32 req_id_error;
    u32[7] reserved1;
    struct (anon)[6] bar_entry;
    struct (anon)[6] bar_ext_entry;
    u32[192] reserved2;
    u32[512] req_id_table;
    u32[256] reserved3;
    u64[512] lut_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ntb_ctrl_regs {
    u32 partition_status;
    u32 partition_op;
    u32 partition_ctrl;
    u32 bar_setup;
    u32 bar_error;
    u16 lut_table_entries;
    u16 lut_table_offset;
    u32 lut_error;
    u16 req_id_table_size;
    u16 req_id_table_offset;
    u32 req_id_error;
    u32[7] reserved1;
    struct (anon)[6] bar_entry;
    struct (anon)[6] bar_ext_entry;
    u32[192] reserved2;
    u32[512] req_id_table;
    u32[256] reserved3;
    u64[512] lut_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ntb_ctrl_regs {
    u32 partition_status;
    u32 partition_op;
    u32 partition_ctrl;
    u32 bar_setup;
    u32 bar_error;
    u16 lut_table_entries;
    u16 lut_table_offset;
    u32 lut_error;
    u16 req_id_table_size;
    u16 req_id_table_offset;
    u32 req_id_error;
    u32[7] reserved1;
    struct (anon)[6] bar_entry;
    struct (anon)[6] bar_ext_entry;
    u32[192] reserved2;
    u32[512] req_id_table;
    u32[256] reserved3;
    u64[512] lut_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ntb_ctrl_regs {
    u32 partition_status;
    u32 partition_op;
    u32 partition_ctrl;
    u32 bar_setup;
    u32 bar_error;
    u16 lut_table_entries;
    u16 lut_table_offset;
    u32 lut_error;
    u16 req_id_table_size;
    u16 req_id_table_offset;
    u32 req_id_error;
    u32[7] reserved1;
    struct (anon)[6] bar_entry;
    struct (anon)[6] bar_ext_entry;
    u32[192] reserved2;
    u32[512] req_id_table;
    u32[256] reserved3;
    u64[512] lut_entry;
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
struct ntb_ctrl_regs {
    u32 partition_status;
    u32 partition_op;
    u32 partition_ctrl;
    u32 bar_setup;
    u32 bar_error;
    u16 lut_table_entries;
    u16 lut_table_offset;
    u32 lut_error;
    u16 req_id_table_size;
    u16 req_id_table_offset;
    u32 req_id_error;
    u32[7] reserved1;
    struct (anon)[6] bar_entry;
    struct (anon)[6] bar_ext_entry;
    u32[192] reserved2;
    u32[512] req_id_table;
    u32[256] reserved3;
    u64[512] lut_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ntb_ctrl_regs {
    u32 partition_status;
    u32 partition_op;
    u32 partition_ctrl;
    u32 bar_setup;
    u32 bar_error;
    u16 lut_table_entries;
    u16 lut_table_offset;
    u32 lut_error;
    u16 req_id_table_size;
    u16 req_id_table_offset;
    u32 req_id_error;
    u32[7] reserved1;
    struct (anon)[6] bar_entry;
    struct (anon)[6] bar_ext_entry;
    u32[192] reserved2;
    u32[512] req_id_table;
    u32[256] reserved3;
    u64[512] lut_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ntb_ctrl_regs {
    u32 partition_status;
    u32 partition_op;
    u32 partition_ctrl;
    u32 bar_setup;
    u32 bar_error;
    u16 lut_table_entries;
    u16 lut_table_offset;
    u32 lut_error;
    u16 req_id_table_size;
    u16 req_id_table_offset;
    u32 req_id_error;
    u32[7] reserved1;
    struct (anon)[6] bar_entry;
    struct (anon)[6] bar_ext_entry;
    u32[192] reserved2;
    u32[512] req_id_table;
    u32[256] reserved3;
    u64[512] lut_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ntb_ctrl_regs {
    u32 partition_status;
    u32 partition_op;
    u32 partition_ctrl;
    u32 bar_setup;
    u32 bar_error;
    u16 lut_table_entries;
    u16 lut_table_offset;
    u32 lut_error;
    u16 req_id_table_size;
    u16 req_id_table_offset;
    u32 req_id_error;
    u32[7] reserved1;
    struct (anon)[6] bar_entry;
    struct (anon)[6] bar_ext_entry;
    u32[192] reserved2;
    u32[512] req_id_table;
    u32[256] reserved3;
    u64[512] lut_entry;
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
struct ntb_ctrl_regs {
    u32 partition_status;
    u32 partition_op;
    u32 partition_ctrl;
    u32 bar_setup;
    u32 bar_error;
    u16 lut_table_entries;
    u16 lut_table_offset;
    u32 lut_error;
    u16 req_id_table_size;
    u16 req_id_table_offset;
    u32 req_id_error;
    u32[7] reserved1;
    struct (anon)[6] bar_entry;
    struct (anon)[6] bar_ext_entry;
    u32[192] reserved2;
    u32[512] req_id_table;
    u32[256] reserved3;
    u64[512] lut_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ntb_ctrl_regs {
    u32 partition_status;
    u32 partition_op;
    u32 partition_ctrl;
    u32 bar_setup;
    u32 bar_error;
    u16 lut_table_entries;
    u16 lut_table_offset;
    u32 lut_error;
    u16 req_id_table_size;
    u16 req_id_table_offset;
    u32 req_id_error;
    u32[7] reserved1;
    struct (anon)[6] bar_entry;
    struct (anon)[6] bar_ext_entry;
    u32[192] reserved2;
    u32[512] req_id_table;
    u32[256] reserved3;
    u64[512] lut_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ntb_ctrl_regs {
    u32 partition_status;
    u32 partition_op;
    u32 partition_ctrl;
    u32 bar_setup;
    u32 bar_error;
    u16 lut_table_entries;
    u16 lut_table_offset;
    u32 lut_error;
    u16 req_id_table_size;
    u16 req_id_table_offset;
    u32 req_id_error;
    u32[7] reserved1;
    struct (anon)[6] bar_entry;
    struct (anon)[6] bar_ext_entry;
    u32[192] reserved2;
    u32[512] req_id_table;
    u32[256] reserved3;
    u64[512] lut_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ntb_ctrl_regs {
    u32 partition_status;
    u32 partition_op;
    u32 partition_ctrl;
    u32 bar_setup;
    u32 bar_error;
    u16 lut_table_entries;
    u16 lut_table_offset;
    u32 lut_error;
    u16 req_id_table_size;
    u16 req_id_table_offset;
    u32 req_id_error;
    u32[7] reserved1;
    struct (anon)[6] bar_entry;
    struct (anon)[6] bar_ext_entry;
    u32[192] reserved2;
    u32[512] req_id_table;
    u32[256] reserved3;
    u64[512] lut_entry;
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct ntb_ctrl_regs {
    u32 partition_status;
    u32 partition_op;
    u32 partition_ctrl;
    u32 bar_setup;
    u32 bar_error;
    u16 lut_table_entries;
    u16 lut_table_offset;
    u32 lut_error;
    u16 req_id_table_size;
    u16 req_id_table_offset;
    u32 req_id_error;
    u32[7] reserved1;
    struct (anon)[6] bar_entry;
    u32[216] reserved2;
    u32[256] req_id_table;
    u32[512] reserved3;
    u64[512] lut_entry;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct (anon)[6] bar_ext_entry</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32[216] reserved2</code> ➡️ <code>u32[192] reserved2</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32[256] req_id_table</code> ➡️ <code>u32[512] req_id_table</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32[512] reserved3</code> ➡️ <code>u32[256] reserved3</code>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
