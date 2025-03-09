# Struct: <code>btf</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct btf {
    void * data;
    struct btf_type * * types;
    u32 * resolved_ids;
    u32 * resolved_sizes;
    const char * strings;
    void * nohdr_data;
    struct btf_header hdr;
    u32 nr_types;
    u32 types_size;
    u32 data_size;
    refcount_t refcnt;
    u32 id;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct btf {
    void * data;
    struct btf_type * * types;
    u32 * resolved_ids;
    u32 * resolved_sizes;
    const char * strings;
    void * nohdr_data;
    struct btf_header hdr;
    u32 nr_types;
    u32 types_size;
    u32 data_size;
    refcount_t refcnt;
    u32 id;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct btf {
    void * data;
    struct btf_type * * types;
    u32 * resolved_ids;
    u32 * resolved_sizes;
    const char * strings;
    void * nohdr_data;
    struct btf_header hdr;
    u32 nr_types;
    u32 types_size;
    u32 data_size;
    refcount_t refcnt;
    u32 id;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct btf {
    void * data;
    struct btf_type * * types;
    u32 * resolved_ids;
    u32 * resolved_sizes;
    const char * strings;
    void * nohdr_data;
    struct btf_header hdr;
    u32 nr_types;
    u32 types_size;
    u32 data_size;
    refcount_t refcnt;
    u32 id;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct btf {
    void * data;
    struct btf_type * * types;
    u32 * resolved_ids;
    u32 * resolved_sizes;
    const char * strings;
    void * nohdr_data;
    struct btf_header hdr;
    u32 nr_types;
    u32 types_size;
    u32 data_size;
    refcount_t refcnt;
    u32 id;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct btf {
    void * data;
    struct btf_type * * types;
    u32 * resolved_ids;
    u32 * resolved_sizes;
    const char * strings;
    void * nohdr_data;
    struct btf_header hdr;
    u32 nr_types;
    u32 types_size;
    u32 data_size;
    refcount_t refcnt;
    u32 id;
    struct callback_head rcu;
    struct btf * base_btf;
    u32 start_id;
    u32 start_str_off;
    char[56] name;
    bool kernel_btf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct btf {
    void * data;
    struct btf_type * * types;
    u32 * resolved_ids;
    u32 * resolved_sizes;
    const char * strings;
    void * nohdr_data;
    struct btf_header hdr;
    u32 nr_types;
    u32 types_size;
    u32 data_size;
    refcount_t refcnt;
    u32 id;
    struct callback_head rcu;
    struct btf * base_btf;
    u32 start_id;
    u32 start_str_off;
    char[56] name;
    bool kernel_btf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct btf {
    void * data;
    struct btf_type * * types;
    u32 * resolved_ids;
    u32 * resolved_sizes;
    const char * strings;
    void * nohdr_data;
    struct btf_header hdr;
    u32 nr_types;
    u32 types_size;
    u32 data_size;
    refcount_t refcnt;
    u32 id;
    struct callback_head rcu;
    struct btf * base_btf;
    u32 start_id;
    u32 start_str_off;
    char[56] name;
    bool kernel_btf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct btf {
    void * data;
    struct btf_type * * types;
    u32 * resolved_ids;
    u32 * resolved_sizes;
    const char * strings;
    void * nohdr_data;
    struct btf_header hdr;
    u32 nr_types;
    u32 types_size;
    u32 data_size;
    refcount_t refcnt;
    u32 id;
    struct callback_head rcu;
    struct btf_kfunc_set_tab * kfunc_set_tab;
    struct btf_id_dtor_kfunc_tab * dtor_kfunc_tab;
    struct btf * base_btf;
    u32 start_id;
    u32 start_str_off;
    char[56] name;
    bool kernel_btf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct btf {
    void * data;
    struct btf_type * * types;
    u32 * resolved_ids;
    u32 * resolved_sizes;
    const char * strings;
    void * nohdr_data;
    struct btf_header hdr;
    u32 nr_types;
    u32 types_size;
    u32 data_size;
    refcount_t refcnt;
    u32 id;
    struct callback_head rcu;
    struct btf_kfunc_set_tab * kfunc_set_tab;
    struct btf_id_dtor_kfunc_tab * dtor_kfunc_tab;
    struct btf_struct_metas * struct_meta_tab;
    struct btf * base_btf;
    u32 start_id;
    u32 start_str_off;
    char[56] name;
    bool kernel_btf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct btf {
    void * data;
    struct btf_type * * types;
    u32 * resolved_ids;
    u32 * resolved_sizes;
    const char * strings;
    void * nohdr_data;
    struct btf_header hdr;
    u32 nr_types;
    u32 types_size;
    u32 data_size;
    refcount_t refcnt;
    u32 id;
    struct callback_head rcu;
    struct btf_kfunc_set_tab * kfunc_set_tab;
    struct btf_id_dtor_kfunc_tab * dtor_kfunc_tab;
    struct btf_struct_metas * struct_meta_tab;
    struct btf * base_btf;
    u32 start_id;
    u32 start_str_off;
    char[56] name;
    bool kernel_btf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct btf {
    void * data;
    struct btf_type * * types;
    u32 * resolved_ids;
    u32 * resolved_sizes;
    const char * strings;
    void * nohdr_data;
    struct btf_header hdr;
    u32 nr_types;
    u32 types_size;
    u32 data_size;
    refcount_t refcnt;
    u32 id;
    struct callback_head rcu;
    struct btf_kfunc_set_tab * kfunc_set_tab;
    struct btf_id_dtor_kfunc_tab * dtor_kfunc_tab;
    struct btf_struct_metas * struct_meta_tab;
    struct btf * base_btf;
    u32 start_id;
    u32 start_str_off;
    char[56] name;
    bool kernel_btf;
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
struct btf {
    void * data;
    struct btf_type * * types;
    u32 * resolved_ids;
    u32 * resolved_sizes;
    const char * strings;
    void * nohdr_data;
    struct btf_header hdr;
    u32 nr_types;
    u32 types_size;
    u32 data_size;
    refcount_t refcnt;
    u32 id;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct btf {
    void * data;
    struct btf_type * * types;
    u32 * resolved_ids;
    u32 * resolved_sizes;
    const char * strings;
    void * nohdr_data;
    struct btf_header hdr;
    u32 nr_types;
    u32 types_size;
    u32 data_size;
    refcount_t refcnt;
    u32 id;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct btf {
    void * data;
    struct btf_type * * types;
    u32 * resolved_ids;
    u32 * resolved_sizes;
    const char * strings;
    void * nohdr_data;
    struct btf_header hdr;
    u32 nr_types;
    u32 types_size;
    u32 data_size;
    refcount_t refcnt;
    u32 id;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct btf {
    void * data;
    struct btf_type * * types;
    u32 * resolved_ids;
    u32 * resolved_sizes;
    const char * strings;
    void * nohdr_data;
    struct btf_header hdr;
    u32 nr_types;
    u32 types_size;
    u32 data_size;
    refcount_t refcnt;
    u32 id;
    struct callback_head rcu;
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
struct btf {
    void * data;
    struct btf_type * * types;
    u32 * resolved_ids;
    u32 * resolved_sizes;
    const char * strings;
    void * nohdr_data;
    struct btf_header hdr;
    u32 nr_types;
    u32 types_size;
    u32 data_size;
    refcount_t refcnt;
    u32 id;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct btf {
    void * data;
    struct btf_type * * types;
    u32 * resolved_ids;
    u32 * resolved_sizes;
    const char * strings;
    void * nohdr_data;
    struct btf_header hdr;
    u32 nr_types;
    u32 types_size;
    u32 data_size;
    refcount_t refcnt;
    u32 id;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct btf {
    void * data;
    struct btf_type * * types;
    u32 * resolved_ids;
    u32 * resolved_sizes;
    const char * strings;
    void * nohdr_data;
    struct btf_header hdr;
    u32 nr_types;
    u32 types_size;
    u32 data_size;
    refcount_t refcnt;
    u32 id;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct btf {
    void * data;
    struct btf_type * * types;
    u32 * resolved_ids;
    u32 * resolved_sizes;
    const char * strings;
    void * nohdr_data;
    struct btf_header hdr;
    u32 nr_types;
    u32 types_size;
    u32 data_size;
    refcount_t refcnt;
    u32 id;
    struct callback_head rcu;
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct btf {
    void * data;
    struct btf_type * * types;
    u32 * resolved_ids;
    u32 * resolved_sizes;
    const char * strings;
    void * nohdr_data;
    struct btf_header hdr;
    u32 nr_types;
    u32 types_size;
    u32 data_size;
    refcount_t refcnt;
    u32 id;
    struct callback_head rcu;
}
```
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct btf * base_btf</code>
</li>
<li>
<b>Field added. </b>
<code>u32 start_id</code>
</li>
<li>
<b>Field added. </b>
<code>u32 start_str_off</code>
</li>
<li>
<b>Field added. </b>
<code>char[56] name</code>
</li>
<li>
<b>Field added. </b>
<code>bool kernel_btf</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct btf_kfunc_set_tab * kfunc_set_tab</code>
</li>
<li>
<b>Field added. </b>
<code>struct btf_id_dtor_kfunc_tab * dtor_kfunc_tab</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct btf_struct_metas * struct_meta_tab</code>
</li>
</ul>
</details>
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
