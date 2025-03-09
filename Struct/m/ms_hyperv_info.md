# Struct: <code>ms_hyperv_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 misc_features;
    u32 hints;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 misc_features;
    u32 hints;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 misc_features;
    u32 hints;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 misc_features;
    u32 hints;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 misc_features;
    u32 hints;
    u32 max_vp_index;
    u32 max_lp_index;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 misc_features;
    u32 hints;
    u32 nested_features;
    u32 max_vp_index;
    u32 max_lp_index;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 misc_features;
    u32 hints;
    u32 nested_features;
    u32 max_vp_index;
    u32 max_lp_index;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 misc_features;
    u32 hints;
    u32 nested_features;
    u32 max_vp_index;
    u32 max_lp_index;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 misc_features;
    u32 hints;
    u32 nested_features;
    u32 max_vp_index;
    u32 max_lp_index;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 misc_features;
    u32 hints;
    u32 nested_features;
    u32 max_vp_index;
    u32 max_lp_index;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 misc_features;
    u32 hints;
    u32 nested_features;
    u32 max_vp_index;
    u32 max_lp_index;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 priv_high;
    u32 misc_features;
    u32 hints;
    u32 nested_features;
    u32 max_vp_index;
    u32 max_lp_index;
    u32 isolation_config_a;
    u32 isolation_config_b;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 priv_high;
    u32 misc_features;
    u32 hints;
    u32 nested_features;
    u32 max_vp_index;
    u32 max_lp_index;
    u32 isolation_config_a;
    u32 isolation_config_b;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 priv_high;
    u32 misc_features;
    u32 hints;
    u32 nested_features;
    u32 max_vp_index;
    u32 max_lp_index;
    u32 isolation_config_a;
    u32 isolation_config_b;
    u32 cvm_type;
    u32 reserved1;
    u32 shared_gpa_boundary_active;
    u32 shared_gpa_boundary_bits;
    u32 reserved2;
    u64 shared_gpa_boundary;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 priv_high;
    u32 misc_features;
    u32 hints;
    u32 nested_features;
    u32 max_vp_index;
    u32 max_lp_index;
    u32 isolation_config_a;
    u32 isolation_config_b;
    u32 cvm_type;
    u32 reserved1;
    u32 shared_gpa_boundary_active;
    u32 shared_gpa_boundary_bits;
    u32 reserved2;
    u64 shared_gpa_boundary;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 priv_high;
    u32 misc_features;
    u32 hints;
    u32 nested_features;
    u32 max_vp_index;
    u32 max_lp_index;
    u32 isolation_config_a;
    u32 isolation_config_b;
    u32 cvm_type;
    u32 reserved1;
    u32 shared_gpa_boundary_active;
    u32 shared_gpa_boundary_bits;
    u32 reserved2;
    u64 shared_gpa_boundary;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 priv_high;
    u32 misc_features;
    u32 hints;
    u32 nested_features;
    u32 max_vp_index;
    u32 max_lp_index;
    u8 vtl;
    u32 isolation_config_a;
    u32 paravisor_present;
    u32 reserved_a1;
    u32 isolation_config_b;
    u32 cvm_type;
    u32 reserved_b1;
    u32 shared_gpa_boundary_active;
    u32 shared_gpa_boundary_bits;
    u32 reserved_b2;
    u64 shared_gpa_boundary;
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 misc_features;
    u32 hints;
    u32 nested_features;
    u32 max_vp_index;
    u32 max_lp_index;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 misc_features;
    u32 hints;
    u32 nested_features;
    u32 max_vp_index;
    u32 max_lp_index;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 misc_features;
    u32 hints;
    u32 nested_features;
    u32 max_vp_index;
    u32 max_lp_index;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 misc_features;
    u32 hints;
    u32 nested_features;
    u32 max_vp_index;
    u32 max_lp_index;
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 max_vp_index</code>
</li>
<li>
<b>Field added. </b>
<code>u32 max_lp_index</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 nested_features</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 priv_high</code>
</li>
<li>
<b>Field added. </b>
<code>u32 isolation_config_a</code>
</li>
<li>
<b>Field added. </b>
<code>u32 isolation_config_b</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 cvm_type</code>
</li>
<li>
<b>Field added. </b>
<code>u32 reserved1</code>
</li>
<li>
<b>Field added. </b>
<code>u32 shared_gpa_boundary_active</code>
</li>
<li>
<b>Field added. </b>
<code>u32 shared_gpa_boundary_bits</code>
</li>
<li>
<b>Field added. </b>
<code>u32 reserved2</code>
</li>
<li>
<b>Field added. </b>
<code>u64 shared_gpa_boundary</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 vtl</code>
</li>
<li>
<b>Field added. </b>
<code>u32 paravisor_present</code>
</li>
<li>
<b>Field added. </b>
<code>u32 reserved_a1</code>
</li>
<li>
<b>Field added. </b>
<code>u32 reserved_b1</code>
</li>
<li>
<b>Field added. </b>
<code>u32 reserved_b2</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 reserved1</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 reserved2</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 misc_features;
    u32 hints;
    u32 nested_features;
    u32 max_vp_index;
    u32 max_lp_index;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 misc_features;
    u32 hints;
    u32 nested_features;
    u32 max_vp_index;
    u32 max_lp_index;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 misc_features;
    u32 hints;
    u32 nested_features;
    u32 max_vp_index;
    u32 max_lp_index;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct ms_hyperv_info {
    u32 features;
    u32 misc_features;
    u32 hints;
    u32 nested_features;
    u32 max_vp_index;
    u32 max_lp_index;
}
```
</details>
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
