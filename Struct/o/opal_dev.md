# Struct: <code>opal_dev</code>

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
struct opal_dev {
    bool supported;
    void * data;
    sec_send_recv * send_recv;
    const struct opal_step * steps;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    size_t pos;
    u8[2048] cmd;
    u8[2048] resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct opal_dev {
    bool supported;
    bool mbr_enabled;
    void * data;
    sec_send_recv * send_recv;
    const struct opal_step * steps;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    size_t pos;
    u8[2048] cmd;
    u8[2048] resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct opal_dev {
    bool supported;
    bool mbr_enabled;
    void * data;
    sec_send_recv * send_recv;
    const struct opal_step * steps;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    size_t pos;
    u8[2048] cmd;
    u8[2048] resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct opal_dev {
    bool supported;
    bool mbr_enabled;
    void * data;
    sec_send_recv * send_recv;
    const struct opal_step * steps;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    size_t pos;
    u8[2048] cmd;
    u8[2048] resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct opal_dev {
    bool supported;
    bool mbr_enabled;
    void * data;
    sec_send_recv * send_recv;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    size_t pos;
    u8[2048] cmd;
    u8[2048] resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct opal_dev {
    bool supported;
    bool mbr_enabled;
    void * data;
    sec_send_recv * send_recv;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    size_t pos;
    u8[2048] cmd;
    u8[2048] resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct opal_dev {
    bool supported;
    bool mbr_enabled;
    void * data;
    sec_send_recv * send_recv;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    size_t pos;
    u8[2048] cmd;
    u8[2048] resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct opal_dev {
    bool supported;
    bool mbr_enabled;
    void * data;
    sec_send_recv * send_recv;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    size_t pos;
    u8[2048] cmd;
    u8[2048] resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct opal_dev {
    bool supported;
    bool mbr_enabled;
    void * data;
    sec_send_recv * send_recv;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    size_t pos;
    u8[2048] cmd;
    u8[2048] resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct opal_dev {
    bool supported;
    bool mbr_enabled;
    void * data;
    sec_send_recv * send_recv;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    size_t pos;
    u8[2048] cmd;
    u8[2048] resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct opal_dev {
    bool supported;
    bool mbr_enabled;
    void * data;
    sec_send_recv * send_recv;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    size_t pos;
    u8[2048] cmd;
    u8[2048] resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct opal_dev {
    u32 flags;
    void * data;
    sec_send_recv * send_recv;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    size_t pos;
    u8 * cmd;
    u8 * resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct opal_dev {
    u32 flags;
    void * data;
    sec_send_recv * send_recv;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    u32 logical_block_size;
    u8 align_required;
    size_t pos;
    u8 * cmd;
    u8 * resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct opal_dev {
    u32 flags;
    void * data;
    sec_send_recv * send_recv;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    u32 logical_block_size;
    u8 align_required;
    size_t pos;
    u8 * cmd;
    u8 * resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
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
struct opal_dev {
    bool supported;
    bool mbr_enabled;
    void * data;
    sec_send_recv * send_recv;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    size_t pos;
    u8[2048] cmd;
    u8[2048] resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct opal_dev {
    bool supported;
    bool mbr_enabled;
    void * data;
    sec_send_recv * send_recv;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    size_t pos;
    u8[2048] cmd;
    u8[2048] resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct opal_dev {
    bool supported;
    bool mbr_enabled;
    void * data;
    sec_send_recv * send_recv;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    size_t pos;
    u8[2048] cmd;
    u8[2048] resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct opal_dev {
    bool supported;
    bool mbr_enabled;
    void * data;
    sec_send_recv * send_recv;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    size_t pos;
    u8[2048] cmd;
    u8[2048] resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
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
struct opal_dev {
    bool supported;
    bool mbr_enabled;
    void * data;
    sec_send_recv * send_recv;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    size_t pos;
    u8[2048] cmd;
    u8[2048] resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct opal_dev {
    bool supported;
    bool mbr_enabled;
    void * data;
    sec_send_recv * send_recv;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    size_t pos;
    u8[2048] cmd;
    u8[2048] resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct opal_dev {
    bool supported;
    bool mbr_enabled;
    void * data;
    sec_send_recv * send_recv;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    size_t pos;
    u8[2048] cmd;
    u8[2048] resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct opal_dev {
    bool supported;
    bool mbr_enabled;
    void * data;
    sec_send_recv * send_recv;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    size_t pos;
    u8[2048] cmd;
    u8[2048] resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
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
struct opal_dev {
    bool supported;
    void * data;
    sec_send_recv * send_recv;
    const struct opal_step * steps;
    struct mutex dev_lock;
    u16 comid;
    u32 hsn;
    u32 tsn;
    u64 align;
    u64 lowest_lba;
    size_t pos;
    u8[2048] cmd;
    u8[2048] resp;
    struct parsed_resp parsed;
    size_t prev_d_len;
    void * prev_data;
    struct list_head unlk_lst;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool mbr_enabled</code>
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
<b>Field removed. </b>
<code>const struct opal_step * steps</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 flags</code>
</li>
<li>
<b>Field removed. </b>
<code>bool supported</code>
</li>
<li>
<b>Field removed. </b>
<code>bool mbr_enabled</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8[2048] cmd</code> ➡️ <code>u8 * cmd</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8[2048] resp</code> ➡️ <code>u8 * resp</code>
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
<code>u32 logical_block_size</code>
</li>
<li>
<b>Field added. </b>
<code>u8 align_required</code>
</li>
</ul>
</details>
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
