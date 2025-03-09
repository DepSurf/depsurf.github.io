# Struct: <code>bpf_insn_aux_data</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
    struct bpf_map * map_ptr;
    int ctx_field_size;
    int converted_op_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
    struct bpf_map * map_ptr;
    int ctx_field_size;
    bool seen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
    long unsigned int map_state;
    s32 call_imm;
    int ctx_field_size;
    int sanitize_stack_off;
    bool seen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
    long unsigned int map_state;
    s32 call_imm;
    u32 alu_limit;
    int ctx_field_size;
    int sanitize_stack_off;
    bool seen;
    u8 alu_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
    long unsigned int map_state;
    s32 call_imm;
    u32 alu_limit;
    u32 map_index;
    u32 map_off;
    int ctx_field_size;
    int sanitize_stack_off;
    bool seen;
    bool zext_dst;
    u8 alu_state;
    bool prune_point;
    unsigned int orig_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
    long unsigned int map_state;
    s32 call_imm;
    u32 alu_limit;
    u32 map_index;
    u32 map_off;
    int ctx_field_size;
    int sanitize_stack_off;
    bool seen;
    bool zext_dst;
    u8 alu_state;
    bool prune_point;
    unsigned int orig_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
    long unsigned int map_ptr_state;
    s32 call_imm;
    u32 alu_limit;
    u32 map_index;
    u32 map_off;
    u64 map_key_state;
    int ctx_field_size;
    int sanitize_stack_off;
    u32 seen;
    bool zext_dst;
    u8 alu_state;
    unsigned int orig_idx;
    bool prune_point;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
    long unsigned int map_ptr_state;
    s32 call_imm;
    u32 alu_limit;
    u32 map_index;
    u32 map_off;
    struct (anon) btf_var;
    u64 map_key_state;
    int ctx_field_size;
    int sanitize_stack_off;
    u32 seen;
    bool zext_dst;
    u8 alu_state;
    unsigned int orig_idx;
    bool prune_point;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
    long unsigned int map_ptr_state;
    s32 call_imm;
    u32 alu_limit;
    u32 map_index;
    u32 map_off;
    struct (anon) btf_var;
    u64 map_key_state;
    int ctx_field_size;
    u32 seen;
    bool sanitize_stack_spill;
    bool zext_dst;
    u8 alu_state;
    unsigned int orig_idx;
    bool prune_point;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
    long unsigned int map_ptr_state;
    s32 call_imm;
    u32 alu_limit;
    u32 map_index;
    u32 map_off;
    struct (anon) btf_var;
    u64 map_key_state;
    int ctx_field_size;
    u32 seen;
    bool sanitize_stack_spill;
    bool zext_dst;
    u8 alu_state;
    unsigned int orig_idx;
    bool prune_point;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
    long unsigned int map_ptr_state;
    s32 call_imm;
    u32 alu_limit;
    u32 map_index;
    u32 map_off;
    struct (anon) btf_var;
    u64 map_key_state;
    int ctx_field_size;
    u32 seen;
    bool sanitize_stack_spill;
    bool zext_dst;
    u8 alu_state;
    unsigned int orig_idx;
    bool prune_point;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
    long unsigned int map_ptr_state;
    s32 call_imm;
    u32 alu_limit;
    u32 map_index;
    u32 map_off;
    struct (anon) btf_var;
    struct bpf_loop_inline_state loop_inline_state;
    u64 obj_new_size;
    struct btf_struct_meta * kptr_struct_meta;
    u64 map_key_state;
    int ctx_field_size;
    u32 seen;
    bool sanitize_stack_spill;
    bool zext_dst;
    bool storage_get_func_atomic;
    u8 alu_state;
    unsigned int orig_idx;
    bool prune_point;
    bool jmp_point;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
    long unsigned int map_ptr_state;
    s32 call_imm;
    u32 alu_limit;
    u32 map_index;
    u32 map_off;
    struct (anon) btf_var;
    struct bpf_loop_inline_state loop_inline_state;
    u64 obj_new_size;
    u64 insert_off;
    struct btf_struct_meta * kptr_struct_meta;
    u64 map_key_state;
    int ctx_field_size;
    u32 seen;
    bool sanitize_stack_spill;
    bool zext_dst;
    bool storage_get_func_atomic;
    bool is_iter_next;
    u8 alu_state;
    unsigned int orig_idx;
    bool jmp_point;
    bool prune_point;
    bool force_checkpoint;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
    long unsigned int map_ptr_state;
    s32 call_imm;
    u32 alu_limit;
    u32 map_index;
    u32 map_off;
    struct (anon) btf_var;
    struct bpf_loop_inline_state loop_inline_state;
    u64 obj_new_size;
    u64 insert_off;
    struct btf_struct_meta * kptr_struct_meta;
    u64 map_key_state;
    int ctx_field_size;
    u32 seen;
    bool sanitize_stack_spill;
    bool zext_dst;
    bool storage_get_func_atomic;
    bool is_iter_next;
    bool call_with_percpu_alloc_ptr;
    u8 alu_state;
    unsigned int orig_idx;
    bool jmp_point;
    bool prune_point;
    bool force_checkpoint;
    bool calls_callback;
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
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
    long unsigned int map_state;
    s32 call_imm;
    u32 alu_limit;
    u32 map_index;
    u32 map_off;
    int ctx_field_size;
    int sanitize_stack_off;
    bool seen;
    bool zext_dst;
    u8 alu_state;
    bool prune_point;
    unsigned int orig_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
    long unsigned int map_state;
    s32 call_imm;
    u32 alu_limit;
    u32 map_index;
    u32 map_off;
    int ctx_field_size;
    int sanitize_stack_off;
    bool seen;
    bool zext_dst;
    u8 alu_state;
    bool prune_point;
    unsigned int orig_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
    long unsigned int map_state;
    s32 call_imm;
    u32 alu_limit;
    u32 map_index;
    u32 map_off;
    int ctx_field_size;
    int sanitize_stack_off;
    bool seen;
    bool zext_dst;
    u8 alu_state;
    bool prune_point;
    unsigned int orig_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
    long unsigned int map_state;
    s32 call_imm;
    u32 alu_limit;
    u32 map_index;
    u32 map_off;
    int ctx_field_size;
    int sanitize_stack_off;
    bool seen;
    bool zext_dst;
    u8 alu_state;
    bool prune_point;
    unsigned int orig_idx;
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
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
    long unsigned int map_state;
    s32 call_imm;
    u32 alu_limit;
    u32 map_index;
    u32 map_off;
    int ctx_field_size;
    int sanitize_stack_off;
    bool seen;
    bool zext_dst;
    u8 alu_state;
    bool prune_point;
    unsigned int orig_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
    long unsigned int map_state;
    s32 call_imm;
    u32 alu_limit;
    u32 map_index;
    u32 map_off;
    int ctx_field_size;
    int sanitize_stack_off;
    bool seen;
    bool zext_dst;
    u8 alu_state;
    bool prune_point;
    unsigned int orig_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
    long unsigned int map_state;
    s32 call_imm;
    u32 alu_limit;
    u32 map_index;
    u32 map_off;
    int ctx_field_size;
    int sanitize_stack_off;
    bool seen;
    bool zext_dst;
    u8 alu_state;
    bool prune_point;
    unsigned int orig_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
    long unsigned int map_state;
    s32 call_imm;
    u32 alu_limit;
    u32 map_index;
    u32 map_off;
    int ctx_field_size;
    int sanitize_stack_off;
    bool seen;
    bool zext_dst;
    u8 alu_state;
    bool prune_point;
    unsigned int orig_idx;
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct bpf_insn_aux_data {
    enum bpf_reg_type ptr_type;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct bpf_map * map_ptr</code>
</li>
<li>
<b>Field added. </b>
<code>int ctx_field_size</code>
</li>
<li>
<b>Field added. </b>
<code>int converted_op_size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool seen</code>
</li>
<li>
<b>Field removed. </b>
<code>int converted_op_size</code>
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
<code>long unsigned int map_state</code>
</li>
<li>
<b>Field added. </b>
<code>s32 call_imm</code>
</li>
<li>
<b>Field added. </b>
<code>int sanitize_stack_off</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bpf_map * map_ptr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 alu_limit</code>
</li>
<li>
<b>Field added. </b>
<code>u8 alu_state</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 map_index</code>
</li>
<li>
<b>Field added. </b>
<code>u32 map_off</code>
</li>
<li>
<b>Field added. </b>
<code>bool zext_dst</code>
</li>
<li>
<b>Field added. </b>
<code>bool prune_point</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int orig_idx</code>
</li>
</ul>
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
<code>long unsigned int map_ptr_state</code>
</li>
<li>
<b>Field added. </b>
<code>u64 map_key_state</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int map_state</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool seen</code> ➡️ <code>u32 seen</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct (anon) btf_var</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool sanitize_stack_spill</code>
</li>
<li>
<b>Field removed. </b>
<code>int sanitize_stack_off</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct bpf_loop_inline_state loop_inline_state</code>
</li>
<li>
<b>Field added. </b>
<code>u64 obj_new_size</code>
</li>
<li>
<b>Field added. </b>
<code>struct btf_struct_meta * kptr_struct_meta</code>
</li>
<li>
<b>Field added. </b>
<code>bool storage_get_func_atomic</code>
</li>
<li>
<b>Field added. </b>
<code>bool jmp_point</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 insert_off</code>
</li>
<li>
<b>Field added. </b>
<code>bool is_iter_next</code>
</li>
<li>
<b>Field added. </b>
<code>bool force_checkpoint</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool call_with_percpu_alloc_ptr</code>
</li>
<li>
<b>Field added. </b>
<code>bool calls_callback</code>
</li>
</ul>
</details>
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
