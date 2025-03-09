# Struct: <code>snp_secrets_page_layout</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct snp_secrets_page_layout {
    u32 version;
    u32 imien;
    u32 rsvd1;
    u32 fms;
    u32 rsvd2;
    u8[16] gosvw;
    u8[32] vmpck0;
    u8[32] vmpck1;
    u8[32] vmpck2;
    u8[32] vmpck3;
    struct secrets_os_area os_area;
    u8[3840] rsvd3;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct snp_secrets_page_layout {
    u32 version;
    u32 imien;
    u32 rsvd1;
    u32 fms;
    u32 rsvd2;
    u8[16] gosvw;
    u8[32] vmpck0;
    u8[32] vmpck1;
    u8[32] vmpck2;
    u8[32] vmpck3;
    struct secrets_os_area os_area;
    u8[3840] rsvd3;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct snp_secrets_page_layout {
    u32 version;
    u32 imien;
    u32 rsvd1;
    u32 fms;
    u32 rsvd2;
    u8[16] gosvw;
    u8[32] vmpck0;
    u8[32] vmpck1;
    u8[32] vmpck2;
    u8[32] vmpck3;
    struct secrets_os_area os_area;
    u8[3840] rsvd3;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct snp_secrets_page_layout {
    u32 version;
    u32 imien;
    u32 rsvd1;
    u32 fms;
    u32 rsvd2;
    u8[16] gosvw;
    u8[32] vmpck0;
    u8[32] vmpck1;
    u8[32] vmpck2;
    u8[32] vmpck3;
    struct secrets_os_area os_area;
    u8[3840] rsvd3;
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct snp_secrets_page_layout {
    u32 version;
    u32 imien;
    u32 rsvd1;
    u32 fms;
    u32 rsvd2;
    u8[16] gosvw;
    u8[32] vmpck0;
    u8[32] vmpck1;
    u8[32] vmpck2;
    u8[32] vmpck3;
    struct secrets_os_area os_area;
    u8[3840] rsvd3;
}
```
</details>
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
