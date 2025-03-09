# Struct: <code>bpf_iter_reg</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_iter_reg {
    const char * target;
    const struct seq_operations * seq_ops;
    bpf_iter_init_seq_priv_t init_seq_private;
    bpf_iter_fini_seq_priv_t fini_seq_private;
    u32 seq_priv_size;
    u32 ctx_arg_info_size;
    struct bpf_ctx_arg_aux[2] ctx_arg_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_iter_reg {
    const char * target;
    bpf_iter_attach_target_t attach_target;
    bpf_iter_detach_target_t detach_target;
    bpf_iter_show_fdinfo_t show_fdinfo;
    bpf_iter_fill_link_info_t fill_link_info;
    u32 ctx_arg_info_size;
    u32 feature;
    struct bpf_ctx_arg_aux[2] ctx_arg_info;
    const struct bpf_iter_seq_info * seq_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_iter_reg {
    const char * target;
    bpf_iter_attach_target_t attach_target;
    bpf_iter_detach_target_t detach_target;
    bpf_iter_show_fdinfo_t show_fdinfo;
    bpf_iter_fill_link_info_t fill_link_info;
    u32 ctx_arg_info_size;
    u32 feature;
    struct bpf_ctx_arg_aux[2] ctx_arg_info;
    const struct bpf_iter_seq_info * seq_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_iter_reg {
    const char * target;
    bpf_iter_attach_target_t attach_target;
    bpf_iter_detach_target_t detach_target;
    bpf_iter_show_fdinfo_t show_fdinfo;
    bpf_iter_fill_link_info_t fill_link_info;
    bpf_iter_get_func_proto_t get_func_proto;
    u32 ctx_arg_info_size;
    u32 feature;
    struct bpf_ctx_arg_aux[2] ctx_arg_info;
    const struct bpf_iter_seq_info * seq_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_iter_reg {
    const char * target;
    bpf_iter_attach_target_t attach_target;
    bpf_iter_detach_target_t detach_target;
    bpf_iter_show_fdinfo_t show_fdinfo;
    bpf_iter_fill_link_info_t fill_link_info;
    bpf_iter_get_func_proto_t get_func_proto;
    u32 ctx_arg_info_size;
    u32 feature;
    struct bpf_ctx_arg_aux[2] ctx_arg_info;
    const struct bpf_iter_seq_info * seq_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_iter_reg {
    const char * target;
    bpf_iter_attach_target_t attach_target;
    bpf_iter_detach_target_t detach_target;
    bpf_iter_show_fdinfo_t show_fdinfo;
    bpf_iter_fill_link_info_t fill_link_info;
    bpf_iter_get_func_proto_t get_func_proto;
    u32 ctx_arg_info_size;
    u32 feature;
    struct bpf_ctx_arg_aux[2] ctx_arg_info;
    const struct bpf_iter_seq_info * seq_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_iter_reg {
    const char * target;
    bpf_iter_attach_target_t attach_target;
    bpf_iter_detach_target_t detach_target;
    bpf_iter_show_fdinfo_t show_fdinfo;
    bpf_iter_fill_link_info_t fill_link_info;
    bpf_iter_get_func_proto_t get_func_proto;
    u32 ctx_arg_info_size;
    u32 feature;
    struct bpf_ctx_arg_aux[2] ctx_arg_info;
    const struct bpf_iter_seq_info * seq_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_iter_reg {
    const char * target;
    bpf_iter_attach_target_t attach_target;
    bpf_iter_detach_target_t detach_target;
    bpf_iter_show_fdinfo_t show_fdinfo;
    bpf_iter_fill_link_info_t fill_link_info;
    bpf_iter_get_func_proto_t get_func_proto;
    u32 ctx_arg_info_size;
    u32 feature;
    struct bpf_ctx_arg_aux[2] ctx_arg_info;
    const struct bpf_iter_seq_info * seq_info;
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct bpf_iter_reg {
    const char * target;
    const struct seq_operations * seq_ops;
    bpf_iter_init_seq_priv_t init_seq_private;
    bpf_iter_fini_seq_priv_t fini_seq_private;
    u32 seq_priv_size;
    u32 ctx_arg_info_size;
    struct bpf_ctx_arg_aux[2] ctx_arg_info;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bpf_iter_attach_target_t attach_target</code>
</li>
<li>
<b>Field added. </b>
<code>bpf_iter_detach_target_t detach_target</code>
</li>
<li>
<b>Field added. </b>
<code>bpf_iter_show_fdinfo_t show_fdinfo</code>
</li>
<li>
<b>Field added. </b>
<code>bpf_iter_fill_link_info_t fill_link_info</code>
</li>
<li>
<b>Field added. </b>
<code>u32 feature</code>
</li>
<li>
<b>Field added. </b>
<code>const struct bpf_iter_seq_info * seq_info</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct seq_operations * seq_ops</code>
</li>
<li>
<b>Field removed. </b>
<code>bpf_iter_init_seq_priv_t init_seq_private</code>
</li>
<li>
<b>Field removed. </b>
<code>bpf_iter_fini_seq_priv_t fini_seq_private</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 seq_priv_size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bpf_iter_get_func_proto_t get_func_proto</code>
</li>
</ul>
</details>
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
