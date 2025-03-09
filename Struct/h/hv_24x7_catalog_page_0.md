# Struct: <code>hv_24x7_catalog_page_0</code>

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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct hv_24x7_catalog_page_0 {
    __be32 magic;
    __be32 length;
    __be64 version;
    __u8[16] build_time_stamp;
    __u8[32] reserved2;
    __be16 schema_data_offs;
    __be16 schema_data_len;
    __be16 schema_entry_count;
    __u8[2] reserved3;
    __be16 event_data_offs;
    __be16 event_data_len;
    __be16 event_entry_count;
    __u8[2] reserved4;
    __be16 group_data_offs;
    __be16 group_data_len;
    __be16 group_entry_count;
    __u8[2] reserved5;
    __be16 formula_data_offs;
    __be16 formula_data_len;
    __be16 formula_entry_count;
    __u8[2] reserved6;
}
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct hv_24x7_catalog_page_0 {
    __be32 magic;
    __be32 length;
    __be64 version;
    __u8[16] build_time_stamp;
    __u8[32] reserved2;
    __be16 schema_data_offs;
    __be16 schema_data_len;
    __be16 schema_entry_count;
    __u8[2] reserved3;
    __be16 event_data_offs;
    __be16 event_data_len;
    __be16 event_entry_count;
    __u8[2] reserved4;
    __be16 group_data_offs;
    __be16 group_data_len;
    __be16 group_entry_count;
    __u8[2] reserved5;
    __be16 formula_data_offs;
    __be16 formula_data_len;
    __be16 formula_entry_count;
    __u8[2] reserved6;
}
```
</details>
</li>
</ul>
