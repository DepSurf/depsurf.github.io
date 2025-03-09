# Struct: <code>mz_hdr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[64] message;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[64] message;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[64] message;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[64] message;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[64] message;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[64] message;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[0] message;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[0] message;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[0] message;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[0] message;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[0] message;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[0] message;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[0] message;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[0] message;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[0] message;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[0] message;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[0] message;
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
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[0] message;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[0] message;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[0] message;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[0] message;
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
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[0] message;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[0] message;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[0] message;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mz_hdr {
    uint16_t magic;
    uint16_t lbsize;
    uint16_t blocks;
    uint16_t relocs;
    uint16_t hdrsize;
    uint16_t min_extra_pps;
    uint16_t max_extra_pps;
    uint16_t ss;
    uint16_t sp;
    uint16_t checksum;
    uint16_t ip;
    uint16_t cs;
    uint16_t reloc_table_offset;
    uint16_t overlay_num;
    uint16_t[4] reserved0;
    uint16_t oem_id;
    uint16_t oem_info;
    uint16_t[10] reserved1;
    uint32_t peaddr;
    char[0] message;
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>char[64] message</code> ➡️ <code>char[0] message</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
