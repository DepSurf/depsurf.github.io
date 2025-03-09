# Struct: <code>bpf_kfunc_call_arg_meta</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_kfunc_call_arg_meta {
    struct btf * btf;
    u32 func_id;
    u32 kfunc_flags;
    const struct btf_type * func_proto;
    const char * func_name;
    u32 ref_obj_id;
    u8 release_regno;
    bool r0_rdonly;
    u32 ret_btf_id;
    u64 r0_size;
    struct (anon) arg_constant;
    struct (anon) arg_obj_drop;
    struct (anon) arg_list_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_kfunc_call_arg_meta {
    struct btf * btf;
    u32 func_id;
    u32 kfunc_flags;
    const struct btf_type * func_proto;
    const char * func_name;
    u32 ref_obj_id;
    u8 release_regno;
    bool r0_rdonly;
    u32 ret_btf_id;
    u64 r0_size;
    u32 subprogno;
    struct (anon) arg_constant;
    struct btf * arg_btf;
    u32 arg_btf_id;
    bool arg_owning_ref;
    struct (anon) arg_list_head;
    struct (anon) arg_rbtree_root;
    struct (anon) initialized_dynptr;
    struct (anon) iter;
    u64 mem_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_kfunc_call_arg_meta {
    struct btf * btf;
    u32 func_id;
    u32 kfunc_flags;
    const struct btf_type * func_proto;
    const char * func_name;
    u32 ref_obj_id;
    u8 release_regno;
    bool r0_rdonly;
    u32 ret_btf_id;
    u64 r0_size;
    u32 subprogno;
    struct (anon) arg_constant;
    struct btf * arg_btf;
    u32 arg_btf_id;
    bool arg_owning_ref;
    struct (anon) arg_list_head;
    struct (anon) arg_rbtree_root;
    struct (anon) initialized_dynptr;
    struct (anon) iter;
    u64 mem_size;
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct bpf_kfunc_call_arg_meta {
    struct btf * btf;
    u32 func_id;
    u32 kfunc_flags;
    const struct btf_type * func_proto;
    const char * func_name;
    u32 ref_obj_id;
    u8 release_regno;
    bool r0_rdonly;
    u32 ret_btf_id;
    u64 r0_size;
    struct (anon) arg_constant;
    struct (anon) arg_obj_drop;
    struct (anon) arg_list_head;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 subprogno</code>
</li>
<li>
<b>Field added. </b>
<code>struct btf * arg_btf</code>
</li>
<li>
<b>Field added. </b>
<code>u32 arg_btf_id</code>
</li>
<li>
<b>Field added. </b>
<code>bool arg_owning_ref</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) arg_rbtree_root</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) initialized_dynptr</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) iter</code>
</li>
<li>
<b>Field added. </b>
<code>u64 mem_size</code>
</li>
<li>
<b>Field removed. </b>
<code>struct (anon) arg_obj_drop</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
