# Struct: <code>uv_hub_info_s</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct uv_hub_info_s {
    long unsigned int global_mmr_base;
    long unsigned int global_mmr_shift;
    long unsigned int gpa_mask;
    short unsigned int * socket_to_node;
    short unsigned int * socket_to_pnode;
    short unsigned int * pnode_to_socket;
    struct uv_gam_range_s * gr_table;
    short unsigned int min_socket;
    short unsigned int min_pnode;
    unsigned char m_val;
    unsigned char n_val;
    unsigned char gr_table_len;
    unsigned char hub_revision;
    unsigned char apic_pnode_shift;
    unsigned char gpa_shift;
    unsigned char m_shift;
    unsigned char n_lshift;
    unsigned int gnode_extra;
    long unsigned int gnode_upper;
    long unsigned int lowmem_remap_top;
    long unsigned int lowmem_remap_base;
    long unsigned int global_gru_base;
    long unsigned int global_gru_shift;
    short unsigned int pnode;
    short unsigned int pnode_mask;
    short unsigned int coherency_domain_number;
    short unsigned int numa_blade_id;
    short unsigned int nr_possible_cpus;
    short unsigned int nr_online_cpus;
    short int memory_nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct uv_hub_info_s {
    long unsigned int global_mmr_base;
    long unsigned int global_mmr_shift;
    long unsigned int gpa_mask;
    short unsigned int * socket_to_node;
    short unsigned int * socket_to_pnode;
    short unsigned int * pnode_to_socket;
    struct uv_gam_range_s * gr_table;
    short unsigned int min_socket;
    short unsigned int min_pnode;
    unsigned char m_val;
    unsigned char n_val;
    unsigned char gr_table_len;
    unsigned char hub_revision;
    unsigned char apic_pnode_shift;
    unsigned char gpa_shift;
    unsigned char m_shift;
    unsigned char n_lshift;
    unsigned int gnode_extra;
    long unsigned int gnode_upper;
    long unsigned int lowmem_remap_top;
    long unsigned int lowmem_remap_base;
    long unsigned int global_gru_base;
    long unsigned int global_gru_shift;
    short unsigned int pnode;
    short unsigned int pnode_mask;
    short unsigned int coherency_domain_number;
    short unsigned int numa_blade_id;
    short unsigned int nr_possible_cpus;
    short unsigned int nr_online_cpus;
    short int memory_nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct uv_hub_info_s {
    unsigned int hub_type;
    unsigned char hub_revision;
    long unsigned int global_mmr_base;
    long unsigned int global_mmr_shift;
    long unsigned int gpa_mask;
    short unsigned int * socket_to_node;
    short unsigned int * socket_to_pnode;
    short unsigned int * pnode_to_socket;
    struct uv_gam_range_s * gr_table;
    short unsigned int min_socket;
    short unsigned int min_pnode;
    unsigned char m_val;
    unsigned char n_val;
    unsigned char gr_table_len;
    unsigned char apic_pnode_shift;
    unsigned char gpa_shift;
    unsigned char nasid_shift;
    unsigned char m_shift;
    unsigned char n_lshift;
    unsigned int gnode_extra;
    long unsigned int gnode_upper;
    long unsigned int lowmem_remap_top;
    long unsigned int lowmem_remap_base;
    long unsigned int global_gru_base;
    long unsigned int global_gru_shift;
    short unsigned int pnode;
    short unsigned int pnode_mask;
    short unsigned int coherency_domain_number;
    short unsigned int numa_blade_id;
    short unsigned int nr_possible_cpus;
    short unsigned int nr_online_cpus;
    short int memory_nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct uv_hub_info_s {
    unsigned int hub_type;
    unsigned char hub_revision;
    long unsigned int global_mmr_base;
    long unsigned int global_mmr_shift;
    long unsigned int gpa_mask;
    short unsigned int * socket_to_node;
    short unsigned int * socket_to_pnode;
    short unsigned int * pnode_to_socket;
    struct uv_gam_range_s * gr_table;
    short unsigned int min_socket;
    short unsigned int min_pnode;
    unsigned char m_val;
    unsigned char n_val;
    unsigned char gr_table_len;
    unsigned char apic_pnode_shift;
    unsigned char gpa_shift;
    unsigned char nasid_shift;
    unsigned char m_shift;
    unsigned char n_lshift;
    unsigned int gnode_extra;
    long unsigned int gnode_upper;
    long unsigned int lowmem_remap_top;
    long unsigned int lowmem_remap_base;
    long unsigned int global_gru_base;
    long unsigned int global_gru_shift;
    short unsigned int pnode;
    short unsigned int pnode_mask;
    short unsigned int coherency_domain_number;
    short unsigned int numa_blade_id;
    short unsigned int nr_possible_cpus;
    short unsigned int nr_online_cpus;
    short int memory_nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct uv_hub_info_s {
    unsigned int hub_type;
    unsigned char hub_revision;
    long unsigned int global_mmr_base;
    long unsigned int global_mmr_shift;
    long unsigned int gpa_mask;
    short unsigned int * socket_to_node;
    short unsigned int * socket_to_pnode;
    short unsigned int * pnode_to_socket;
    struct uv_gam_range_s * gr_table;
    short unsigned int min_socket;
    short unsigned int min_pnode;
    unsigned char m_val;
    unsigned char n_val;
    unsigned char gr_table_len;
    unsigned char apic_pnode_shift;
    unsigned char gpa_shift;
    unsigned char nasid_shift;
    unsigned char m_shift;
    unsigned char n_lshift;
    unsigned int gnode_extra;
    long unsigned int gnode_upper;
    long unsigned int lowmem_remap_top;
    long unsigned int lowmem_remap_base;
    long unsigned int global_gru_base;
    long unsigned int global_gru_shift;
    short unsigned int pnode;
    short unsigned int pnode_mask;
    short unsigned int coherency_domain_number;
    short unsigned int numa_blade_id;
    short unsigned int nr_possible_cpus;
    short unsigned int nr_online_cpus;
    short int memory_nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct uv_hub_info_s {
    unsigned int hub_type;
    unsigned char hub_revision;
    long unsigned int global_mmr_base;
    long unsigned int global_mmr_shift;
    long unsigned int gpa_mask;
    short unsigned int * socket_to_node;
    short unsigned int * socket_to_pnode;
    short unsigned int * pnode_to_socket;
    struct uv_gam_range_s * gr_table;
    short unsigned int min_socket;
    short unsigned int min_pnode;
    unsigned char m_val;
    unsigned char n_val;
    unsigned char gr_table_len;
    unsigned char apic_pnode_shift;
    unsigned char gpa_shift;
    unsigned char nasid_shift;
    unsigned char m_shift;
    unsigned char n_lshift;
    unsigned int gnode_extra;
    long unsigned int gnode_upper;
    long unsigned int lowmem_remap_top;
    long unsigned int lowmem_remap_base;
    long unsigned int global_gru_base;
    long unsigned int global_gru_shift;
    short unsigned int pnode;
    short unsigned int pnode_mask;
    short unsigned int coherency_domain_number;
    short unsigned int numa_blade_id;
    short unsigned int nr_possible_cpus;
    short unsigned int nr_online_cpus;
    short int memory_nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct uv_hub_info_s {
    unsigned int hub_type;
    unsigned char hub_revision;
    long unsigned int global_mmr_base;
    long unsigned int global_mmr_shift;
    long unsigned int gpa_mask;
    short unsigned int * socket_to_node;
    short unsigned int * socket_to_pnode;
    short unsigned int * pnode_to_socket;
    struct uv_gam_range_s * gr_table;
    short unsigned int min_socket;
    short unsigned int min_pnode;
    unsigned char m_val;
    unsigned char n_val;
    unsigned char gr_table_len;
    unsigned char apic_pnode_shift;
    unsigned char gpa_shift;
    unsigned char nasid_shift;
    unsigned char m_shift;
    unsigned char n_lshift;
    unsigned int gnode_extra;
    long unsigned int gnode_upper;
    long unsigned int lowmem_remap_top;
    long unsigned int lowmem_remap_base;
    long unsigned int global_gru_base;
    long unsigned int global_gru_shift;
    short unsigned int pnode;
    short unsigned int pnode_mask;
    short unsigned int coherency_domain_number;
    short unsigned int numa_blade_id;
    short unsigned int nr_possible_cpus;
    short unsigned int nr_online_cpus;
    short int memory_nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct uv_hub_info_s {
    unsigned int hub_type;
    unsigned char hub_revision;
    long unsigned int global_mmr_base;
    long unsigned int global_mmr_shift;
    long unsigned int gpa_mask;
    short unsigned int * socket_to_node;
    short unsigned int * socket_to_pnode;
    short unsigned int * pnode_to_socket;
    struct uv_gam_range_s * gr_table;
    short unsigned int min_socket;
    short unsigned int min_pnode;
    unsigned char m_val;
    unsigned char n_val;
    unsigned char gr_table_len;
    unsigned char apic_pnode_shift;
    unsigned char gpa_shift;
    unsigned char nasid_shift;
    unsigned char m_shift;
    unsigned char n_lshift;
    unsigned int gnode_extra;
    long unsigned int gnode_upper;
    long unsigned int lowmem_remap_top;
    long unsigned int lowmem_remap_base;
    long unsigned int global_gru_base;
    long unsigned int global_gru_shift;
    short unsigned int pnode;
    short unsigned int pnode_mask;
    short unsigned int coherency_domain_number;
    short unsigned int numa_blade_id;
    short unsigned int nr_possible_cpus;
    short unsigned int nr_online_cpus;
    short int memory_nid;
    short unsigned int * node_to_socket;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct uv_hub_info_s {
    unsigned int hub_type;
    unsigned char hub_revision;
    long unsigned int global_mmr_base;
    long unsigned int global_mmr_shift;
    long unsigned int gpa_mask;
    short unsigned int * socket_to_node;
    short unsigned int * socket_to_pnode;
    short unsigned int * pnode_to_socket;
    struct uv_gam_range_s * gr_table;
    short unsigned int min_socket;
    short unsigned int min_pnode;
    unsigned char m_val;
    unsigned char n_val;
    unsigned char gr_table_len;
    unsigned char apic_pnode_shift;
    unsigned char gpa_shift;
    unsigned char nasid_shift;
    unsigned char m_shift;
    unsigned char n_lshift;
    unsigned int gnode_extra;
    long unsigned int gnode_upper;
    long unsigned int lowmem_remap_top;
    long unsigned int lowmem_remap_base;
    long unsigned int global_gru_base;
    long unsigned int global_gru_shift;
    short unsigned int pnode;
    short unsigned int pnode_mask;
    short unsigned int coherency_domain_number;
    short unsigned int numa_blade_id;
    short unsigned int nr_possible_cpus;
    short unsigned int nr_online_cpus;
    short int memory_nid;
    short unsigned int * node_to_socket;
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct uv_hub_info_s {
    long unsigned int global_mmr_base;
    long unsigned int global_mmr_shift;
    long unsigned int gpa_mask;
    short unsigned int * socket_to_node;
    short unsigned int * socket_to_pnode;
    short unsigned int * pnode_to_socket;
    struct uv_gam_range_s * gr_table;
    short unsigned int min_socket;
    short unsigned int min_pnode;
    unsigned char m_val;
    unsigned char n_val;
    unsigned char gr_table_len;
    unsigned char hub_revision;
    unsigned char apic_pnode_shift;
    unsigned char gpa_shift;
    unsigned char m_shift;
    unsigned char n_lshift;
    unsigned int gnode_extra;
    long unsigned int gnode_upper;
    long unsigned int lowmem_remap_top;
    long unsigned int lowmem_remap_base;
    long unsigned int global_gru_base;
    long unsigned int global_gru_shift;
    short unsigned int pnode;
    short unsigned int pnode_mask;
    short unsigned int coherency_domain_number;
    short unsigned int numa_blade_id;
    short unsigned int nr_possible_cpus;
    short unsigned int nr_online_cpus;
    short int memory_nid;
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct uv_hub_info_s {
    long unsigned int global_mmr_base;
    long unsigned int global_mmr_shift;
    long unsigned int gpa_mask;
    short unsigned int * socket_to_node;
    short unsigned int * socket_to_pnode;
    short unsigned int * pnode_to_socket;
    struct uv_gam_range_s * gr_table;
    short unsigned int min_socket;
    short unsigned int min_pnode;
    unsigned char m_val;
    unsigned char n_val;
    unsigned char gr_table_len;
    unsigned char hub_revision;
    unsigned char apic_pnode_shift;
    unsigned char gpa_shift;
    unsigned char m_shift;
    unsigned char n_lshift;
    unsigned int gnode_extra;
    long unsigned int gnode_upper;
    long unsigned int lowmem_remap_top;
    long unsigned int lowmem_remap_base;
    long unsigned int global_gru_base;
    long unsigned int global_gru_shift;
    short unsigned int pnode;
    short unsigned int pnode_mask;
    short unsigned int coherency_domain_number;
    short unsigned int numa_blade_id;
    short unsigned int nr_possible_cpus;
    short unsigned int nr_online_cpus;
    short int memory_nid;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int hub_type</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned char nasid_shift</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>short unsigned int * node_to_socket</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct uv_hub_info_s {
    long unsigned int global_mmr_base;
    long unsigned int global_mmr_shift;
    long unsigned int gpa_mask;
    short unsigned int * socket_to_node;
    short unsigned int * socket_to_pnode;
    short unsigned int * pnode_to_socket;
    struct uv_gam_range_s * gr_table;
    short unsigned int min_socket;
    short unsigned int min_pnode;
    unsigned char m_val;
    unsigned char n_val;
    unsigned char gr_table_len;
    unsigned char hub_revision;
    unsigned char apic_pnode_shift;
    unsigned char gpa_shift;
    unsigned char m_shift;
    unsigned char n_lshift;
    unsigned int gnode_extra;
    long unsigned int gnode_upper;
    long unsigned int lowmem_remap_top;
    long unsigned int lowmem_remap_base;
    long unsigned int global_gru_base;
    long unsigned int global_gru_shift;
    short unsigned int pnode;
    short unsigned int pnode_mask;
    short unsigned int coherency_domain_number;
    short unsigned int numa_blade_id;
    short unsigned int nr_possible_cpus;
    short unsigned int nr_online_cpus;
    short int memory_nid;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct uv_hub_info_s {
    long unsigned int global_mmr_base;
    long unsigned int global_mmr_shift;
    long unsigned int gpa_mask;
    short unsigned int * socket_to_node;
    short unsigned int * socket_to_pnode;
    short unsigned int * pnode_to_socket;
    struct uv_gam_range_s * gr_table;
    short unsigned int min_socket;
    short unsigned int min_pnode;
    unsigned char m_val;
    unsigned char n_val;
    unsigned char gr_table_len;
    unsigned char hub_revision;
    unsigned char apic_pnode_shift;
    unsigned char gpa_shift;
    unsigned char m_shift;
    unsigned char n_lshift;
    unsigned int gnode_extra;
    long unsigned int gnode_upper;
    long unsigned int lowmem_remap_top;
    long unsigned int lowmem_remap_base;
    long unsigned int global_gru_base;
    long unsigned int global_gru_shift;
    short unsigned int pnode;
    short unsigned int pnode_mask;
    short unsigned int coherency_domain_number;
    short unsigned int numa_blade_id;
    short unsigned int nr_possible_cpus;
    short unsigned int nr_online_cpus;
    short int memory_nid;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct uv_hub_info_s {
    long unsigned int global_mmr_base;
    long unsigned int global_mmr_shift;
    long unsigned int gpa_mask;
    short unsigned int * socket_to_node;
    short unsigned int * socket_to_pnode;
    short unsigned int * pnode_to_socket;
    struct uv_gam_range_s * gr_table;
    short unsigned int min_socket;
    short unsigned int min_pnode;
    unsigned char m_val;
    unsigned char n_val;
    unsigned char gr_table_len;
    unsigned char hub_revision;
    unsigned char apic_pnode_shift;
    unsigned char gpa_shift;
    unsigned char m_shift;
    unsigned char n_lshift;
    unsigned int gnode_extra;
    long unsigned int gnode_upper;
    long unsigned int lowmem_remap_top;
    long unsigned int lowmem_remap_base;
    long unsigned int global_gru_base;
    long unsigned int global_gru_shift;
    short unsigned int pnode;
    short unsigned int pnode_mask;
    short unsigned int coherency_domain_number;
    short unsigned int numa_blade_id;
    short unsigned int nr_possible_cpus;
    short unsigned int nr_online_cpus;
    short int memory_nid;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct uv_hub_info_s {
    long unsigned int global_mmr_base;
    long unsigned int global_mmr_shift;
    long unsigned int gpa_mask;
    short unsigned int * socket_to_node;
    short unsigned int * socket_to_pnode;
    short unsigned int * pnode_to_socket;
    struct uv_gam_range_s * gr_table;
    short unsigned int min_socket;
    short unsigned int min_pnode;
    unsigned char m_val;
    unsigned char n_val;
    unsigned char gr_table_len;
    unsigned char hub_revision;
    unsigned char apic_pnode_shift;
    unsigned char gpa_shift;
    unsigned char m_shift;
    unsigned char n_lshift;
    unsigned int gnode_extra;
    long unsigned int gnode_upper;
    long unsigned int lowmem_remap_top;
    long unsigned int lowmem_remap_base;
    long unsigned int global_gru_base;
    long unsigned int global_gru_shift;
    short unsigned int pnode;
    short unsigned int pnode_mask;
    short unsigned int coherency_domain_number;
    short unsigned int numa_blade_id;
    short unsigned int nr_possible_cpus;
    short unsigned int nr_online_cpus;
    short int memory_nid;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
struct uv_hub_info_s {
    long unsigned int global_mmr_base;
    long unsigned int global_mmr_shift;
    long unsigned int gpa_mask;
    short unsigned int * socket_to_node;
    short unsigned int * socket_to_pnode;
    short unsigned int * pnode_to_socket;
    struct uv_gam_range_s * gr_table;
    short unsigned int min_socket;
    short unsigned int min_pnode;
    unsigned char m_val;
    unsigned char n_val;
    unsigned char gr_table_len;
    unsigned char hub_revision;
    unsigned char apic_pnode_shift;
    unsigned char gpa_shift;
    unsigned char m_shift;
    unsigned char n_lshift;
    unsigned int gnode_extra;
    long unsigned int gnode_upper;
    long unsigned int lowmem_remap_top;
    long unsigned int lowmem_remap_base;
    long unsigned int global_gru_base;
    long unsigned int global_gru_shift;
    short unsigned int pnode;
    short unsigned int pnode_mask;
    short unsigned int coherency_domain_number;
    short unsigned int numa_blade_id;
    short unsigned int nr_possible_cpus;
    short unsigned int nr_online_cpus;
    short int memory_nid;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct uv_hub_info_s {
    long unsigned int global_mmr_base;
    long unsigned int global_mmr_shift;
    long unsigned int gpa_mask;
    short unsigned int * socket_to_node;
    short unsigned int * socket_to_pnode;
    short unsigned int * pnode_to_socket;
    struct uv_gam_range_s * gr_table;
    short unsigned int min_socket;
    short unsigned int min_pnode;
    unsigned char m_val;
    unsigned char n_val;
    unsigned char gr_table_len;
    unsigned char hub_revision;
    unsigned char apic_pnode_shift;
    unsigned char gpa_shift;
    unsigned char m_shift;
    unsigned char n_lshift;
    unsigned int gnode_extra;
    long unsigned int gnode_upper;
    long unsigned int lowmem_remap_top;
    long unsigned int lowmem_remap_base;
    long unsigned int global_gru_base;
    long unsigned int global_gru_shift;
    short unsigned int pnode;
    short unsigned int pnode_mask;
    short unsigned int coherency_domain_number;
    short unsigned int numa_blade_id;
    short unsigned int nr_possible_cpus;
    short unsigned int nr_online_cpus;
    short int memory_nid;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
struct uv_hub_info_s {
    long unsigned int global_mmr_base;
    long unsigned int global_mmr_shift;
    long unsigned int gpa_mask;
    short unsigned int * socket_to_node;
    short unsigned int * socket_to_pnode;
    short unsigned int * pnode_to_socket;
    struct uv_gam_range_s * gr_table;
    short unsigned int min_socket;
    short unsigned int min_pnode;
    unsigned char m_val;
    unsigned char n_val;
    unsigned char gr_table_len;
    unsigned char hub_revision;
    unsigned char apic_pnode_shift;
    unsigned char gpa_shift;
    unsigned char m_shift;
    unsigned char n_lshift;
    unsigned int gnode_extra;
    long unsigned int gnode_upper;
    long unsigned int lowmem_remap_top;
    long unsigned int lowmem_remap_base;
    long unsigned int global_gru_base;
    long unsigned int global_gru_shift;
    short unsigned int pnode;
    short unsigned int pnode_mask;
    short unsigned int coherency_domain_number;
    short unsigned int numa_blade_id;
    short unsigned int nr_possible_cpus;
    short unsigned int nr_online_cpus;
    short int memory_nid;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
