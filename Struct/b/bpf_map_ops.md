# Struct: <code>bpf_map_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_map_ops {
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    void * (*)(struct bpf_map *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct bpf_map_ops {
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_map_ops {
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_map_ops {
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
    u32 (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup;
    u32 (*)(void *) map_fd_sys_lookup_elem;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_map_ops {
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
    u32 (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup;
    u32 (*)(void *) map_fd_sys_lookup_elem;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct bpf_map_ops {
    int (*)(union bpf_attr *) map_alloc_check;
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void (*)(struct bpf_map *) map_release_uref;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
    u32 (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup;
    u32 (*)(void *) map_fd_sys_lookup_elem;
    void (*)(struct bpf_map *, void *, struct seq_file *) map_seq_show_elem;
    int (*)(const struct bpf_map *, const struct btf *, u32, u32) map_check_btf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bpf_map_ops {
    int (*)(union bpf_attr *) map_alloc_check;
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void (*)(struct bpf_map *) map_release_uref;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    int (*)(struct bpf_map *, void *, u64) map_push_elem;
    int (*)(struct bpf_map *, void *) map_pop_elem;
    int (*)(struct bpf_map *, void *) map_peek_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
    u32 (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup;
    u32 (*)(void *) map_fd_sys_lookup_elem;
    void (*)(struct bpf_map *, void *, struct seq_file *) map_seq_show_elem;
    int (*)(const struct bpf_map *, const struct btf *, const struct btf_type *, const struct btf_type *) map_check_btf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bpf_map_ops {
    int (*)(union bpf_attr *) map_alloc_check;
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void (*)(struct bpf_map *) map_release_uref;
    void * (*)(struct bpf_map *, void *) map_lookup_elem_sys_only;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    int (*)(struct bpf_map *, void *, u64) map_push_elem;
    int (*)(struct bpf_map *, void *) map_pop_elem;
    int (*)(struct bpf_map *, void *) map_peek_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
    u32 (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup;
    u32 (*)(void *) map_fd_sys_lookup_elem;
    void (*)(struct bpf_map *, void *, struct seq_file *) map_seq_show_elem;
    int (*)(const struct bpf_map *, const struct btf *, const struct btf_type *, const struct btf_type *) map_check_btf;
    int (*)(const struct bpf_map *, u64 *, u32) map_direct_value_addr;
    int (*)(const struct bpf_map *, u64, u32 *) map_direct_value_meta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bpf_map_ops {
    int (*)(union bpf_attr *) map_alloc_check;
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void (*)(struct bpf_map *) map_release_uref;
    void * (*)(struct bpf_map *, void *) map_lookup_elem_sys_only;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    int (*)(struct bpf_map *, void *, u64) map_push_elem;
    int (*)(struct bpf_map *, void *) map_pop_elem;
    int (*)(struct bpf_map *, void *) map_peek_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
    u32 (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup;
    u32 (*)(void *) map_fd_sys_lookup_elem;
    void (*)(struct bpf_map *, void *, struct seq_file *) map_seq_show_elem;
    int (*)(const struct bpf_map *, const struct btf *, const struct btf_type *, const struct btf_type *) map_check_btf;
    int (*)(const struct bpf_map *, u64 *, u32) map_direct_value_addr;
    int (*)(const struct bpf_map *, u64, u32 *) map_direct_value_meta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_map_ops {
    int (*)(union bpf_attr *) map_alloc_check;
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void (*)(struct bpf_map *) map_release_uref;
    void * (*)(struct bpf_map *, void *) map_lookup_elem_sys_only;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_lookup_batch;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_lookup_and_delete_batch;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_update_batch;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_delete_batch;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    int (*)(struct bpf_map *, void *, u64) map_push_elem;
    int (*)(struct bpf_map *, void *) map_pop_elem;
    int (*)(struct bpf_map *, void *) map_peek_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
    u32 (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup;
    u32 (*)(void *) map_fd_sys_lookup_elem;
    void (*)(struct bpf_map *, void *, struct seq_file *) map_seq_show_elem;
    int (*)(const struct bpf_map *, const struct btf *, const struct btf_type *, const struct btf_type *) map_check_btf;
    int (*)(struct bpf_map *, struct bpf_prog_aux *) map_poke_track;
    void (*)(struct bpf_map *, struct bpf_prog_aux *) map_poke_untrack;
    void (*)(struct bpf_map *, u32, struct bpf_prog *, struct bpf_prog *) map_poke_run;
    int (*)(const struct bpf_map *, u64 *, u32) map_direct_value_addr;
    int (*)(const struct bpf_map *, u64, u32 *) map_direct_value_meta;
    int (*)(struct bpf_map *, struct vm_area_struct *) map_mmap;
    __poll_t (*)(struct bpf_map *, struct file *, struct poll_table_struct *) map_poll;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_map_ops {
    int (*)(union bpf_attr *) map_alloc_check;
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void (*)(struct bpf_map *) map_release_uref;
    void * (*)(struct bpf_map *, void *) map_lookup_elem_sys_only;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_lookup_batch;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_lookup_and_delete_batch;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_update_batch;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_delete_batch;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    int (*)(struct bpf_map *, void *, u64) map_push_elem;
    int (*)(struct bpf_map *, void *) map_pop_elem;
    int (*)(struct bpf_map *, void *) map_peek_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
    int (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup;
    u32 (*)(void *) map_fd_sys_lookup_elem;
    void (*)(struct bpf_map *, void *, struct seq_file *) map_seq_show_elem;
    int (*)(const struct bpf_map *, const struct btf *, const struct btf_type *, const struct btf_type *) map_check_btf;
    int (*)(struct bpf_map *, struct bpf_prog_aux *) map_poke_track;
    void (*)(struct bpf_map *, struct bpf_prog_aux *) map_poke_untrack;
    void (*)(struct bpf_map *, u32, struct bpf_prog *, struct bpf_prog *) map_poke_run;
    int (*)(const struct bpf_map *, u64 *, u32) map_direct_value_addr;
    int (*)(const struct bpf_map *, u64, u32 *) map_direct_value_meta;
    int (*)(struct bpf_map *, struct vm_area_struct *) map_mmap;
    __poll_t (*)(struct bpf_map *, struct file *, struct poll_table_struct *) map_poll;
    int (*)(struct bpf_local_storage_map *, void *, u32) map_local_storage_charge;
    void (*)(struct bpf_local_storage_map *, void *, u32) map_local_storage_uncharge;
    struct bpf_local_storage * * (*)(void *) map_owner_storage_ptr;
    bool (*)(const struct bpf_map *, const struct bpf_map *) map_meta_equal;
    const const char * map_btf_name;
    int * map_btf_id;
    const struct bpf_iter_seq_info * iter_seq_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_map_ops {
    int (*)(union bpf_attr *) map_alloc_check;
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void (*)(struct bpf_map *) map_release_uref;
    void * (*)(struct bpf_map *, void *) map_lookup_elem_sys_only;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_lookup_batch;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_lookup_and_delete_batch;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_update_batch;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_delete_batch;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    int (*)(struct bpf_map *, void *, u64) map_push_elem;
    int (*)(struct bpf_map *, void *) map_pop_elem;
    int (*)(struct bpf_map *, void *) map_peek_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
    int (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup;
    u32 (*)(void *) map_fd_sys_lookup_elem;
    void (*)(struct bpf_map *, void *, struct seq_file *) map_seq_show_elem;
    int (*)(const struct bpf_map *, const struct btf *, const struct btf_type *, const struct btf_type *) map_check_btf;
    int (*)(struct bpf_map *, struct bpf_prog_aux *) map_poke_track;
    void (*)(struct bpf_map *, struct bpf_prog_aux *) map_poke_untrack;
    void (*)(struct bpf_map *, u32, struct bpf_prog *, struct bpf_prog *) map_poke_run;
    int (*)(const struct bpf_map *, u64 *, u32) map_direct_value_addr;
    int (*)(const struct bpf_map *, u64, u32 *) map_direct_value_meta;
    int (*)(struct bpf_map *, struct vm_area_struct *) map_mmap;
    __poll_t (*)(struct bpf_map *, struct file *, struct poll_table_struct *) map_poll;
    int (*)(struct bpf_local_storage_map *, void *, u32) map_local_storage_charge;
    void (*)(struct bpf_local_storage_map *, void *, u32) map_local_storage_uncharge;
    struct bpf_local_storage * * (*)(void *) map_owner_storage_ptr;
    int (*)(struct bpf_map *, u32, u64) map_redirect;
    bool (*)(const struct bpf_map *, const struct bpf_map *) map_meta_equal;
    int (*)(struct bpf_verifier_env *, struct bpf_func_state *, struct bpf_func_state *) map_set_for_each_callback_args;
    int (*)(struct bpf_map *, void *, void *, u64) map_for_each_callback;
    const const char * map_btf_name;
    int * map_btf_id;
    const struct bpf_iter_seq_info * iter_seq_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_map_ops {
    int (*)(union bpf_attr *) map_alloc_check;
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void (*)(struct bpf_map *) map_release_uref;
    void * (*)(struct bpf_map *, void *) map_lookup_elem_sys_only;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_lookup_batch;
    int (*)(struct bpf_map *, void *, void *, u64) map_lookup_and_delete_elem;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_lookup_and_delete_batch;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_update_batch;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_delete_batch;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    int (*)(struct bpf_map *, void *, u64) map_push_elem;
    int (*)(struct bpf_map *, void *) map_pop_elem;
    int (*)(struct bpf_map *, void *) map_peek_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
    int (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup;
    u32 (*)(void *) map_fd_sys_lookup_elem;
    void (*)(struct bpf_map *, void *, struct seq_file *) map_seq_show_elem;
    int (*)(const struct bpf_map *, const struct btf *, const struct btf_type *, const struct btf_type *) map_check_btf;
    int (*)(struct bpf_map *, struct bpf_prog_aux *) map_poke_track;
    void (*)(struct bpf_map *, struct bpf_prog_aux *) map_poke_untrack;
    void (*)(struct bpf_map *, u32, struct bpf_prog *, struct bpf_prog *) map_poke_run;
    int (*)(const struct bpf_map *, u64 *, u32) map_direct_value_addr;
    int (*)(const struct bpf_map *, u64, u32 *) map_direct_value_meta;
    int (*)(struct bpf_map *, struct vm_area_struct *) map_mmap;
    __poll_t (*)(struct bpf_map *, struct file *, struct poll_table_struct *) map_poll;
    int (*)(struct bpf_local_storage_map *, void *, u32) map_local_storage_charge;
    void (*)(struct bpf_local_storage_map *, void *, u32) map_local_storage_uncharge;
    struct bpf_local_storage * * (*)(void *) map_owner_storage_ptr;
    int (*)(struct bpf_map *, u32, u64) map_redirect;
    bool (*)(const struct bpf_map *, const struct bpf_map *) map_meta_equal;
    int (*)(struct bpf_verifier_env *, struct bpf_func_state *, struct bpf_func_state *) map_set_for_each_callback_args;
    int (*)(struct bpf_map *, void *, void *, u64) map_for_each_callback;
    const const char * map_btf_name;
    int * map_btf_id;
    const struct bpf_iter_seq_info * iter_seq_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_map_ops {
    int (*)(union bpf_attr *) map_alloc_check;
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void (*)(struct bpf_map *) map_release_uref;
    void * (*)(struct bpf_map *, void *) map_lookup_elem_sys_only;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_lookup_batch;
    int (*)(struct bpf_map *, void *, void *, u64) map_lookup_and_delete_elem;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_lookup_and_delete_batch;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_update_batch;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_delete_batch;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    int (*)(struct bpf_map *, void *, u64) map_push_elem;
    int (*)(struct bpf_map *, void *) map_pop_elem;
    int (*)(struct bpf_map *, void *) map_peek_elem;
    void * (*)(struct bpf_map *, void *, u32) map_lookup_percpu_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
    int (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup;
    u32 (*)(void *) map_fd_sys_lookup_elem;
    void (*)(struct bpf_map *, void *, struct seq_file *) map_seq_show_elem;
    int (*)(const struct bpf_map *, const struct btf *, const struct btf_type *, const struct btf_type *) map_check_btf;
    int (*)(struct bpf_map *, struct bpf_prog_aux *) map_poke_track;
    void (*)(struct bpf_map *, struct bpf_prog_aux *) map_poke_untrack;
    void (*)(struct bpf_map *, u32, struct bpf_prog *, struct bpf_prog *) map_poke_run;
    int (*)(const struct bpf_map *, u64 *, u32) map_direct_value_addr;
    int (*)(const struct bpf_map *, u64, u32 *) map_direct_value_meta;
    int (*)(struct bpf_map *, struct vm_area_struct *) map_mmap;
    __poll_t (*)(struct bpf_map *, struct file *, struct poll_table_struct *) map_poll;
    int (*)(struct bpf_local_storage_map *, void *, u32) map_local_storage_charge;
    void (*)(struct bpf_local_storage_map *, void *, u32) map_local_storage_uncharge;
    struct bpf_local_storage * * (*)(void *) map_owner_storage_ptr;
    int (*)(struct bpf_map *, u32, u64) map_redirect;
    bool (*)(const struct bpf_map *, const struct bpf_map *) map_meta_equal;
    int (*)(struct bpf_verifier_env *, struct bpf_func_state *, struct bpf_func_state *) map_set_for_each_callback_args;
    int (*)(struct bpf_map *, bpf_callback_t, void *, u64) map_for_each_callback;
    int * map_btf_id;
    const struct bpf_iter_seq_info * iter_seq_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_map_ops {
    int (*)(union bpf_attr *) map_alloc_check;
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void (*)(struct bpf_map *) map_release_uref;
    void * (*)(struct bpf_map *, void *) map_lookup_elem_sys_only;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_lookup_batch;
    int (*)(struct bpf_map *, void *, void *, u64) map_lookup_and_delete_elem;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_lookup_and_delete_batch;
    int (*)(struct bpf_map *, struct file *, const union bpf_attr *, union bpf_attr *) map_update_batch;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_delete_batch;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    int (*)(struct bpf_map *, void *, u64) map_push_elem;
    int (*)(struct bpf_map *, void *) map_pop_elem;
    int (*)(struct bpf_map *, void *) map_peek_elem;
    void * (*)(struct bpf_map *, void *, u32) map_lookup_percpu_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
    int (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup;
    u32 (*)(void *) map_fd_sys_lookup_elem;
    void (*)(struct bpf_map *, void *, struct seq_file *) map_seq_show_elem;
    int (*)(const struct bpf_map *, const struct btf *, const struct btf_type *, const struct btf_type *) map_check_btf;
    int (*)(struct bpf_map *, struct bpf_prog_aux *) map_poke_track;
    void (*)(struct bpf_map *, struct bpf_prog_aux *) map_poke_untrack;
    void (*)(struct bpf_map *, u32, struct bpf_prog *, struct bpf_prog *) map_poke_run;
    int (*)(const struct bpf_map *, u64 *, u32) map_direct_value_addr;
    int (*)(const struct bpf_map *, u64, u32 *) map_direct_value_meta;
    int (*)(struct bpf_map *, struct vm_area_struct *) map_mmap;
    __poll_t (*)(struct bpf_map *, struct file *, struct poll_table_struct *) map_poll;
    int (*)(struct bpf_local_storage_map *, void *, u32) map_local_storage_charge;
    void (*)(struct bpf_local_storage_map *, void *, u32) map_local_storage_uncharge;
    struct bpf_local_storage * * (*)(void *) map_owner_storage_ptr;
    int (*)(struct bpf_map *, u64, u64) map_redirect;
    bool (*)(const struct bpf_map *, const struct bpf_map *) map_meta_equal;
    int (*)(struct bpf_verifier_env *, struct bpf_func_state *, struct bpf_func_state *) map_set_for_each_callback_args;
    int (*)(struct bpf_map *, bpf_callback_t, void *, u64) map_for_each_callback;
    int * map_btf_id;
    const struct bpf_iter_seq_info * iter_seq_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_map_ops {
    int (*)(union bpf_attr *) map_alloc_check;
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void (*)(struct bpf_map *) map_release_uref;
    void * (*)(struct bpf_map *, void *) map_lookup_elem_sys_only;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_lookup_batch;
    int (*)(struct bpf_map *, void *, void *, u64) map_lookup_and_delete_elem;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_lookup_and_delete_batch;
    int (*)(struct bpf_map *, struct file *, const union bpf_attr *, union bpf_attr *) map_update_batch;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_delete_batch;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    long int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    long int (*)(struct bpf_map *, void *) map_delete_elem;
    long int (*)(struct bpf_map *, void *, u64) map_push_elem;
    long int (*)(struct bpf_map *, void *) map_pop_elem;
    long int (*)(struct bpf_map *, void *) map_peek_elem;
    void * (*)(struct bpf_map *, void *, u32) map_lookup_percpu_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
    int (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup;
    u32 (*)(void *) map_fd_sys_lookup_elem;
    void (*)(struct bpf_map *, void *, struct seq_file *) map_seq_show_elem;
    int (*)(const struct bpf_map *, const struct btf *, const struct btf_type *, const struct btf_type *) map_check_btf;
    int (*)(struct bpf_map *, struct bpf_prog_aux *) map_poke_track;
    void (*)(struct bpf_map *, struct bpf_prog_aux *) map_poke_untrack;
    void (*)(struct bpf_map *, u32, struct bpf_prog *, struct bpf_prog *) map_poke_run;
    int (*)(const struct bpf_map *, u64 *, u32) map_direct_value_addr;
    int (*)(const struct bpf_map *, u64, u32 *) map_direct_value_meta;
    int (*)(struct bpf_map *, struct vm_area_struct *) map_mmap;
    __poll_t (*)(struct bpf_map *, struct file *, struct poll_table_struct *) map_poll;
    int (*)(struct bpf_local_storage_map *, void *, u32) map_local_storage_charge;
    void (*)(struct bpf_local_storage_map *, void *, u32) map_local_storage_uncharge;
    struct bpf_local_storage * * (*)(void *) map_owner_storage_ptr;
    long int (*)(struct bpf_map *, u64, u64) map_redirect;
    bool (*)(const struct bpf_map *, const struct bpf_map *) map_meta_equal;
    int (*)(struct bpf_verifier_env *, struct bpf_func_state *, struct bpf_func_state *) map_set_for_each_callback_args;
    long int (*)(struct bpf_map *, bpf_callback_t, void *, u64) map_for_each_callback;
    u64 (*)(const struct bpf_map *) map_mem_usage;
    int * map_btf_id;
    const struct bpf_iter_seq_info * iter_seq_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_map_ops {
    int (*)(union bpf_attr *) map_alloc_check;
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void (*)(struct bpf_map *) map_release_uref;
    void * (*)(struct bpf_map *, void *) map_lookup_elem_sys_only;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_lookup_batch;
    int (*)(struct bpf_map *, void *, void *, u64) map_lookup_and_delete_elem;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_lookup_and_delete_batch;
    int (*)(struct bpf_map *, struct file *, const union bpf_attr *, union bpf_attr *) map_update_batch;
    int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_delete_batch;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    long int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    long int (*)(struct bpf_map *, void *) map_delete_elem;
    long int (*)(struct bpf_map *, void *, u64) map_push_elem;
    long int (*)(struct bpf_map *, void *) map_pop_elem;
    long int (*)(struct bpf_map *, void *) map_peek_elem;
    void * (*)(struct bpf_map *, void *, u32) map_lookup_percpu_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(struct bpf_map *, void *, bool) map_fd_put_ptr;
    int (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup;
    u32 (*)(void *) map_fd_sys_lookup_elem;
    void (*)(struct bpf_map *, void *, struct seq_file *) map_seq_show_elem;
    int (*)(const struct bpf_map *, const struct btf *, const struct btf_type *, const struct btf_type *) map_check_btf;
    int (*)(struct bpf_map *, struct bpf_prog_aux *) map_poke_track;
    void (*)(struct bpf_map *, struct bpf_prog_aux *) map_poke_untrack;
    void (*)(struct bpf_map *, u32, struct bpf_prog *, struct bpf_prog *) map_poke_run;
    int (*)(const struct bpf_map *, u64 *, u32) map_direct_value_addr;
    int (*)(const struct bpf_map *, u64, u32 *) map_direct_value_meta;
    int (*)(struct bpf_map *, struct vm_area_struct *) map_mmap;
    __poll_t (*)(struct bpf_map *, struct file *, struct poll_table_struct *) map_poll;
    int (*)(struct bpf_local_storage_map *, void *, u32) map_local_storage_charge;
    void (*)(struct bpf_local_storage_map *, void *, u32) map_local_storage_uncharge;
    struct bpf_local_storage * * (*)(void *) map_owner_storage_ptr;
    long int (*)(struct bpf_map *, u64, u64) map_redirect;
    bool (*)(const struct bpf_map *, const struct bpf_map *) map_meta_equal;
    int (*)(struct bpf_verifier_env *, struct bpf_func_state *, struct bpf_func_state *) map_set_for_each_callback_args;
    long int (*)(struct bpf_map *, bpf_callback_t, void *, u64) map_for_each_callback;
    u64 (*)(const struct bpf_map *) map_mem_usage;
    int * map_btf_id;
    const struct bpf_iter_seq_info * iter_seq_info;
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
struct bpf_map_ops {
    int (*)(union bpf_attr *) map_alloc_check;
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void (*)(struct bpf_map *) map_release_uref;
    void * (*)(struct bpf_map *, void *) map_lookup_elem_sys_only;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    int (*)(struct bpf_map *, void *, u64) map_push_elem;
    int (*)(struct bpf_map *, void *) map_pop_elem;
    int (*)(struct bpf_map *, void *) map_peek_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
    u32 (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup;
    u32 (*)(void *) map_fd_sys_lookup_elem;
    void (*)(struct bpf_map *, void *, struct seq_file *) map_seq_show_elem;
    int (*)(const struct bpf_map *, const struct btf *, const struct btf_type *, const struct btf_type *) map_check_btf;
    int (*)(const struct bpf_map *, u64 *, u32) map_direct_value_addr;
    int (*)(const struct bpf_map *, u64, u32 *) map_direct_value_meta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bpf_map_ops {
    int (*)(union bpf_attr *) map_alloc_check;
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void (*)(struct bpf_map *) map_release_uref;
    void * (*)(struct bpf_map *, void *) map_lookup_elem_sys_only;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    int (*)(struct bpf_map *, void *, u64) map_push_elem;
    int (*)(struct bpf_map *, void *) map_pop_elem;
    int (*)(struct bpf_map *, void *) map_peek_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
    u32 (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup;
    u32 (*)(void *) map_fd_sys_lookup_elem;
    void (*)(struct bpf_map *, void *, struct seq_file *) map_seq_show_elem;
    int (*)(const struct bpf_map *, const struct btf *, const struct btf_type *, const struct btf_type *) map_check_btf;
    int (*)(const struct bpf_map *, u64 *, u32) map_direct_value_addr;
    int (*)(const struct bpf_map *, u64, u32 *) map_direct_value_meta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bpf_map_ops {
    int (*)(union bpf_attr *) map_alloc_check;
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void (*)(struct bpf_map *) map_release_uref;
    void * (*)(struct bpf_map *, void *) map_lookup_elem_sys_only;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    int (*)(struct bpf_map *, void *, u64) map_push_elem;
    int (*)(struct bpf_map *, void *) map_pop_elem;
    int (*)(struct bpf_map *, void *) map_peek_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
    u32 (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup;
    u32 (*)(void *) map_fd_sys_lookup_elem;
    void (*)(struct bpf_map *, void *, struct seq_file *) map_seq_show_elem;
    int (*)(const struct bpf_map *, const struct btf *, const struct btf_type *, const struct btf_type *) map_check_btf;
    int (*)(const struct bpf_map *, u64 *, u32) map_direct_value_addr;
    int (*)(const struct bpf_map *, u64, u32 *) map_direct_value_meta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bpf_map_ops {
    int (*)(union bpf_attr *) map_alloc_check;
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void (*)(struct bpf_map *) map_release_uref;
    void * (*)(struct bpf_map *, void *) map_lookup_elem_sys_only;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    int (*)(struct bpf_map *, void *, u64) map_push_elem;
    int (*)(struct bpf_map *, void *) map_pop_elem;
    int (*)(struct bpf_map *, void *) map_peek_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
    u32 (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup;
    u32 (*)(void *) map_fd_sys_lookup_elem;
    void (*)(struct bpf_map *, void *, struct seq_file *) map_seq_show_elem;
    int (*)(const struct bpf_map *, const struct btf *, const struct btf_type *, const struct btf_type *) map_check_btf;
    int (*)(const struct bpf_map *, u64 *, u32) map_direct_value_addr;
    int (*)(const struct bpf_map *, u64, u32 *) map_direct_value_meta;
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
struct bpf_map_ops {
    int (*)(union bpf_attr *) map_alloc_check;
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void (*)(struct bpf_map *) map_release_uref;
    void * (*)(struct bpf_map *, void *) map_lookup_elem_sys_only;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    int (*)(struct bpf_map *, void *, u64) map_push_elem;
    int (*)(struct bpf_map *, void *) map_pop_elem;
    int (*)(struct bpf_map *, void *) map_peek_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
    u32 (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup;
    u32 (*)(void *) map_fd_sys_lookup_elem;
    void (*)(struct bpf_map *, void *, struct seq_file *) map_seq_show_elem;
    int (*)(const struct bpf_map *, const struct btf *, const struct btf_type *, const struct btf_type *) map_check_btf;
    int (*)(const struct bpf_map *, u64 *, u32) map_direct_value_addr;
    int (*)(const struct bpf_map *, u64, u32 *) map_direct_value_meta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bpf_map_ops {
    int (*)(union bpf_attr *) map_alloc_check;
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void (*)(struct bpf_map *) map_release_uref;
    void * (*)(struct bpf_map *, void *) map_lookup_elem_sys_only;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    int (*)(struct bpf_map *, void *, u64) map_push_elem;
    int (*)(struct bpf_map *, void *) map_pop_elem;
    int (*)(struct bpf_map *, void *) map_peek_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
    u32 (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup;
    u32 (*)(void *) map_fd_sys_lookup_elem;
    void (*)(struct bpf_map *, void *, struct seq_file *) map_seq_show_elem;
    int (*)(const struct bpf_map *, const struct btf *, const struct btf_type *, const struct btf_type *) map_check_btf;
    int (*)(const struct bpf_map *, u64 *, u32) map_direct_value_addr;
    int (*)(const struct bpf_map *, u64, u32 *) map_direct_value_meta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bpf_map_ops {
    int (*)(union bpf_attr *) map_alloc_check;
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void (*)(struct bpf_map *) map_release_uref;
    void * (*)(struct bpf_map *, void *) map_lookup_elem_sys_only;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    int (*)(struct bpf_map *, void *, u64) map_push_elem;
    int (*)(struct bpf_map *, void *) map_pop_elem;
    int (*)(struct bpf_map *, void *) map_peek_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
    u32 (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup;
    u32 (*)(void *) map_fd_sys_lookup_elem;
    void (*)(struct bpf_map *, void *, struct seq_file *) map_seq_show_elem;
    int (*)(const struct bpf_map *, const struct btf *, const struct btf_type *, const struct btf_type *) map_check_btf;
    int (*)(const struct bpf_map *, u64 *, u32) map_direct_value_addr;
    int (*)(const struct bpf_map *, u64, u32 *) map_direct_value_meta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bpf_map_ops {
    int (*)(union bpf_attr *) map_alloc_check;
    struct bpf_map * (*)(union bpf_attr *) map_alloc;
    void (*)(struct bpf_map *, struct file *) map_release;
    void (*)(struct bpf_map *) map_free;
    int (*)(struct bpf_map *, void *, void *) map_get_next_key;
    void (*)(struct bpf_map *) map_release_uref;
    void * (*)(struct bpf_map *, void *) map_lookup_elem_sys_only;
    void * (*)(struct bpf_map *, void *) map_lookup_elem;
    int (*)(struct bpf_map *, void *, void *, u64) map_update_elem;
    int (*)(struct bpf_map *, void *) map_delete_elem;
    int (*)(struct bpf_map *, void *, u64) map_push_elem;
    int (*)(struct bpf_map *, void *) map_pop_elem;
    int (*)(struct bpf_map *, void *) map_peek_elem;
    void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr;
    void (*)(void *) map_fd_put_ptr;
    u32 (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup;
    u32 (*)(void *) map_fd_sys_lookup_elem;
    void (*)(struct bpf_map *, void *, struct seq_file *) map_seq_show_elem;
    int (*)(const struct bpf_map *, const struct btf *, const struct btf_type *, const struct btf_type *) map_check_btf;
    int (*)(const struct bpf_map *, u64 *, u32) map_direct_value_addr;
    int (*)(const struct bpf_map *, u64, u32 *) map_direct_value_meta;
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct bpf_map *, struct file *) map_release</code>
</li>
<li>
<b>Field type changed. </b>
<code>void * (*)(struct bpf_map *, int) map_fd_get_ptr</code> ➡️ <code>void * (*)(struct bpf_map *, struct file *, int) map_fd_get_ptr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup</code>
</li>
<li>
<b>Field added. </b>
<code>u32 (*)(void *) map_fd_sys_lookup_elem</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(union bpf_attr *) map_alloc_check</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct bpf_map *) map_release_uref</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct bpf_map *, void *, struct seq_file *) map_seq_show_elem</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(const struct bpf_map *, const struct btf *, u32, u32) map_check_btf</code>
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
<code>int (*)(struct bpf_map *, void *, u64) map_push_elem</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct bpf_map *, void *) map_pop_elem</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct bpf_map *, void *) map_peek_elem</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(const struct bpf_map *, const struct btf *, u32, u32) map_check_btf</code> ➡️ <code>int (*)(const struct bpf_map *, const struct btf *, const struct btf_type *, const struct btf_type *) map_check_btf</code>
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
<code>void * (*)(struct bpf_map *, void *) map_lookup_elem_sys_only</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(const struct bpf_map *, u64 *, u32) map_direct_value_addr</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(const struct bpf_map *, u64, u32 *) map_direct_value_meta</code>
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
<code>int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_lookup_batch</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_lookup_and_delete_batch</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_update_batch</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_delete_batch</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct bpf_map *, struct bpf_prog_aux *) map_poke_track</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct bpf_map *, struct bpf_prog_aux *) map_poke_untrack</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct bpf_map *, u32, struct bpf_prog *, struct bpf_prog *) map_poke_run</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct bpf_map *, struct vm_area_struct *) map_mmap</code>
</li>
<li>
<b>Field added. </b>
<code>__poll_t (*)(struct bpf_map *, struct file *, struct poll_table_struct *) map_poll</code>
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
<code>int (*)(struct bpf_local_storage_map *, void *, u32) map_local_storage_charge</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct bpf_local_storage_map *, void *, u32) map_local_storage_uncharge</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_local_storage * * (*)(void *) map_owner_storage_ptr</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(const struct bpf_map *, const struct bpf_map *) map_meta_equal</code>
</li>
<li>
<b>Field added. </b>
<code>const const char * map_btf_name</code>
</li>
<li>
<b>Field added. </b>
<code>int * map_btf_id</code>
</li>
<li>
<b>Field added. </b>
<code>const struct bpf_iter_seq_info * iter_seq_info</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup</code> ➡️ <code>int (*)(struct bpf_map *, struct bpf_insn *) map_gen_lookup</code>
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
<code>int (*)(struct bpf_map *, u32, u64) map_redirect</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct bpf_verifier_env *, struct bpf_func_state *, struct bpf_func_state *) map_set_for_each_callback_args</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct bpf_map *, void *, void *, u64) map_for_each_callback</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct bpf_map *, void *, void *, u64) map_lookup_and_delete_elem</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * (*)(struct bpf_map *, void *, u32) map_lookup_percpu_elem</code>
</li>
<li>
<b>Field removed. </b>
<code>const const char * map_btf_name</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct bpf_map *, void *, void *, u64) map_for_each_callback</code> ➡️ <code>int (*)(struct bpf_map *, bpf_callback_t, void *, u64) map_for_each_callback</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct bpf_map *, const union bpf_attr *, union bpf_attr *) map_update_batch</code> ➡️ <code>int (*)(struct bpf_map *, struct file *, const union bpf_attr *, union bpf_attr *) map_update_batch</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct bpf_map *, u32, u64) map_redirect</code> ➡️ <code>int (*)(struct bpf_map *, u64, u64) map_redirect</code>
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
<code>u64 (*)(const struct bpf_map *) map_mem_usage</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct bpf_map *, void *, void *, u64) map_update_elem</code> ➡️ <code>long int (*)(struct bpf_map *, void *, void *, u64) map_update_elem</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct bpf_map *, void *) map_delete_elem</code> ➡️ <code>long int (*)(struct bpf_map *, void *) map_delete_elem</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct bpf_map *, void *, u64) map_push_elem</code> ➡️ <code>long int (*)(struct bpf_map *, void *, u64) map_push_elem</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct bpf_map *, void *) map_pop_elem</code> ➡️ <code>long int (*)(struct bpf_map *, void *) map_pop_elem</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct bpf_map *, void *) map_peek_elem</code> ➡️ <code>long int (*)(struct bpf_map *, void *) map_peek_elem</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct bpf_map *, u64, u64) map_redirect</code> ➡️ <code>long int (*)(struct bpf_map *, u64, u64) map_redirect</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct bpf_map *, bpf_callback_t, void *, u64) map_for_each_callback</code> ➡️ <code>long int (*)(struct bpf_map *, bpf_callback_t, void *, u64) map_for_each_callback</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void (*)(void *) map_fd_put_ptr</code> ➡️ <code>void (*)(struct bpf_map *, void *, bool) map_fd_put_ptr</code>
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
