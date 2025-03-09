# Struct: <code>qm_mcr_queryfq_np</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct qm_mcr_queryfq_np {
    u8 verb;
    u8 result;
    u8 __reserved1;
    u8 state;
    u32 fqd_link;
    u16 odp_seq;
    u16 orp_nesn;
    u16 orp_ea_hseq;
    u16 orp_ea_tseq;
    u32 orp_ea_hptr;
    u32 orp_ea_tptr;
    u32 pfdr_hptr;
    u32 pfdr_tptr;
    u8[5] __reserved2;
    u8 is;
    u16 ics_surp;
    u32 byte_cnt;
    u32 frm_cnt;
    u32 __reserved3;
    u16 ra1_sfdr;
    u16 ra2_sfdr;
    u16 __reserved4;
    u16 od1_sfdr;
    u16 od2_sfdr;
    u16 od3_sfdr;
}
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct qm_mcr_queryfq_np {
    u8 verb;
    u8 result;
    u8 __reserved1;
    u8 state;
    u32 fqd_link;
    u16 odp_seq;
    u16 orp_nesn;
    u16 orp_ea_hseq;
    u16 orp_ea_tseq;
    u32 orp_ea_hptr;
    u32 orp_ea_tptr;
    u32 pfdr_hptr;
    u32 pfdr_tptr;
    u8[5] __reserved2;
    u8 is;
    u16 ics_surp;
    u32 byte_cnt;
    u32 frm_cnt;
    u32 __reserved3;
    u16 ra1_sfdr;
    u16 ra2_sfdr;
    u16 __reserved4;
    u16 od1_sfdr;
    u16 od2_sfdr;
    u16 od3_sfdr;
}
```
</details>
</li>
</ul>
