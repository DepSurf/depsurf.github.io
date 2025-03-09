# Struct: <code>nh_group</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nh_group {
    u16 num_nh;
    bool mpath;
    bool has_v4;
    struct nh_grp_entry[0] nh_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nh_group {
    u16 num_nh;
    bool mpath;
    bool has_v4;
    struct nh_grp_entry[0] nh_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct nh_group {
    struct nh_group * spare;
    u16 num_nh;
    bool mpath;
    bool fdb_nh;
    bool has_v4;
    struct nh_grp_entry[0] nh_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct nh_group {
    struct nh_group * spare;
    u16 num_nh;
    bool mpath;
    bool fdb_nh;
    bool has_v4;
    struct nh_grp_entry[0] nh_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct nh_group {
    struct nh_group * spare;
    u16 num_nh;
    bool is_multipath;
    bool hash_threshold;
    bool resilient;
    bool fdb_nh;
    bool has_v4;
    struct nh_res_table * res_table;
    struct nh_grp_entry[0] nh_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nh_group {
    struct nh_group * spare;
    u16 num_nh;
    bool is_multipath;
    bool hash_threshold;
    bool resilient;
    bool fdb_nh;
    bool has_v4;
    struct nh_res_table * res_table;
    struct nh_grp_entry[0] nh_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nh_group {
    struct nh_group * spare;
    u16 num_nh;
    bool is_multipath;
    bool hash_threshold;
    bool resilient;
    bool fdb_nh;
    bool has_v4;
    struct nh_res_table * res_table;
    struct nh_grp_entry[0] nh_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nh_group {
    struct nh_group * spare;
    u16 num_nh;
    bool is_multipath;
    bool hash_threshold;
    bool resilient;
    bool fdb_nh;
    bool has_v4;
    struct nh_res_table * res_table;
    struct nh_grp_entry[0] nh_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nh_group {
    struct nh_group * spare;
    u16 num_nh;
    bool is_multipath;
    bool hash_threshold;
    bool resilient;
    bool fdb_nh;
    bool has_v4;
    struct nh_res_table * res_table;
    struct nh_grp_entry[0] nh_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nh_group {
    struct nh_group * spare;
    u16 num_nh;
    bool is_multipath;
    bool hash_threshold;
    bool resilient;
    bool fdb_nh;
    bool has_v4;
    struct nh_res_table * res_table;
    struct nh_grp_entry[0] nh_entries;
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
struct nh_group {
    u16 num_nh;
    bool mpath;
    bool has_v4;
    struct nh_grp_entry[0] nh_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct nh_group {
    u16 num_nh;
    bool mpath;
    bool has_v4;
    struct nh_grp_entry[0] nh_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nh_group {
    u16 num_nh;
    bool mpath;
    bool has_v4;
    struct nh_grp_entry[0] nh_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nh_group {
    u16 num_nh;
    bool mpath;
    bool has_v4;
    struct nh_grp_entry[0] nh_entries;
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
struct nh_group {
    u16 num_nh;
    bool mpath;
    bool has_v4;
    struct nh_grp_entry[0] nh_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nh_group {
    u16 num_nh;
    bool mpath;
    bool has_v4;
    struct nh_grp_entry[0] nh_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nh_group {
    u16 num_nh;
    bool mpath;
    bool has_v4;
    struct nh_grp_entry[0] nh_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nh_group {
    u16 num_nh;
    bool mpath;
    bool has_v4;
    struct nh_grp_entry[0] nh_entries;
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct nh_group {
    u16 num_nh;
    bool mpath;
    bool has_v4;
    struct nh_grp_entry[0] nh_entries;
}
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct nh_group * spare</code>
</li>
<li>
<b>Field added. </b>
<code>bool fdb_nh</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool is_multipath</code>
</li>
<li>
<b>Field added. </b>
<code>bool hash_threshold</code>
</li>
<li>
<b>Field added. </b>
<code>bool resilient</code>
</li>
<li>
<b>Field added. </b>
<code>struct nh_res_table * res_table</code>
</li>
<li>
<b>Field removed. </b>
<code>bool mpath</code>
</li>
</ul>
</details>
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
