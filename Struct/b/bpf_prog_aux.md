# Struct: <code>bpf_prog_aux</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic_t refcnt;
    u32 used_map_cnt;
    const struct bpf_verifier_ops * ops;
    struct bpf_map * * used_maps;
    struct bpf_prog * prog;
    struct user_struct * user;
    struct work_struct work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic_t refcnt;
    u32 used_map_cnt;
    u32 max_ctx_offset;
    const struct bpf_verifier_ops * ops;
    struct bpf_map * * used_maps;
    struct bpf_prog * prog;
    struct user_struct * user;
    struct work_struct work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic_t refcnt;
    u32 used_map_cnt;
    u32 max_ctx_offset;
    const struct bpf_verifier_ops * ops;
    struct bpf_map * * used_maps;
    struct bpf_prog * prog;
    struct user_struct * user;
    struct work_struct work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic_t refcnt;
    u32 used_map_cnt;
    u32 max_ctx_offset;
    u32 stack_depth;
    u32 id;
    struct latch_tree_node ksym_tnode;
    struct list_head ksym_lnode;
    const struct bpf_verifier_ops * ops;
    struct bpf_map * * used_maps;
    struct bpf_prog * prog;
    struct user_struct * user;
    struct work_struct work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic_t refcnt;
    u32 used_map_cnt;
    u32 max_ctx_offset;
    u32 stack_depth;
    u32 id;
    struct latch_tree_node ksym_tnode;
    struct list_head ksym_lnode;
    const struct bpf_prog_ops * ops;
    struct bpf_map * * used_maps;
    struct bpf_prog * prog;
    struct user_struct * user;
    u64 load_time;
    char[16] name;
    void * security;
    struct bpf_dev_offload * offload;
    struct work_struct work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic_t refcnt;
    u32 used_map_cnt;
    u32 max_ctx_offset;
    u32 stack_depth;
    u32 id;
    u32 func_cnt;
    bool offload_requested;
    struct bpf_prog * * func;
    void * jit_data;
    struct latch_tree_node ksym_tnode;
    struct list_head ksym_lnode;
    const struct bpf_prog_ops * ops;
    struct bpf_map * * used_maps;
    struct bpf_prog * prog;
    struct user_struct * user;
    u64 load_time;
    char[16] name;
    void * security;
    struct bpf_prog_offload * offload;
    struct work_struct work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic_t refcnt;
    u32 used_map_cnt;
    u32 max_ctx_offset;
    u32 max_pkt_offset;
    u32 stack_depth;
    u32 id;
    u32 func_cnt;
    u32 func_idx;
    bool offload_requested;
    struct bpf_prog * * func;
    void * jit_data;
    struct latch_tree_node ksym_tnode;
    struct list_head ksym_lnode;
    const struct bpf_prog_ops * ops;
    struct bpf_map * * used_maps;
    struct bpf_prog * prog;
    struct user_struct * user;
    u64 load_time;
    struct bpf_map *[2] cgroup_storage;
    char[16] name;
    void * security;
    struct bpf_prog_offload * offload;
    struct btf * btf;
    struct bpf_func_info * func_info;
    struct bpf_line_info * linfo;
    void * * jited_linfo;
    u32 func_info_cnt;
    u32 nr_linfo;
    u32 linfo_idx;
    struct work_struct work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic_t refcnt;
    u32 used_map_cnt;
    u32 max_ctx_offset;
    u32 max_pkt_offset;
    u32 max_tp_access;
    u32 stack_depth;
    u32 id;
    u32 func_cnt;
    u32 func_idx;
    bool verifier_zext;
    bool offload_requested;
    struct bpf_prog * * func;
    void * jit_data;
    struct latch_tree_node ksym_tnode;
    struct list_head ksym_lnode;
    const struct bpf_prog_ops * ops;
    struct bpf_map * * used_maps;
    struct bpf_prog * prog;
    struct user_struct * user;
    u64 load_time;
    struct bpf_map *[2] cgroup_storage;
    char[16] name;
    void * security;
    struct bpf_prog_offload * offload;
    struct btf * btf;
    struct bpf_func_info * func_info;
    struct bpf_line_info * linfo;
    void * * jited_linfo;
    u32 func_info_cnt;
    u32 nr_linfo;
    u32 linfo_idx;
    struct bpf_prog_stats * stats;
    struct work_struct work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic_t refcnt;
    u32 used_map_cnt;
    u32 max_ctx_offset;
    u32 max_pkt_offset;
    u32 max_tp_access;
    u32 stack_depth;
    u32 id;
    u32 func_cnt;
    u32 func_idx;
    bool verifier_zext;
    bool offload_requested;
    struct bpf_prog * * func;
    void * jit_data;
    struct latch_tree_node ksym_tnode;
    struct list_head ksym_lnode;
    const struct bpf_prog_ops * ops;
    struct bpf_map * * used_maps;
    struct bpf_prog * prog;
    struct user_struct * user;
    u64 load_time;
    struct bpf_map *[2] cgroup_storage;
    char[16] name;
    void * security;
    struct bpf_prog_offload * offload;
    struct btf * btf;
    struct bpf_func_info * func_info;
    struct bpf_line_info * linfo;
    void * * jited_linfo;
    u32 func_info_cnt;
    u32 nr_linfo;
    u32 linfo_idx;
    struct bpf_prog_stats * stats;
    struct work_struct work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic64_t refcnt;
    u32 used_map_cnt;
    u32 max_ctx_offset;
    u32 max_pkt_offset;
    u32 max_tp_access;
    u32 stack_depth;
    u32 id;
    u32 func_cnt;
    u32 func_idx;
    u32 attach_btf_id;
    u32 ctx_arg_info_size;
    const struct bpf_ctx_arg_aux * ctx_arg_info;
    struct bpf_prog * linked_prog;
    bool verifier_zext;
    bool offload_requested;
    bool attach_btf_trace;
    bool func_proto_unreliable;
    enum bpf_tramp_prog_type trampoline_prog_type;
    struct bpf_trampoline * trampoline;
    struct hlist_node tramp_hlist;
    const struct btf_type * attach_func_proto;
    const char * attach_func_name;
    struct bpf_prog * * func;
    void * jit_data;
    struct bpf_jit_poke_descriptor * poke_tab;
    u32 size_poke_tab;
    struct bpf_ksym ksym;
    const struct bpf_prog_ops * ops;
    struct bpf_map * * used_maps;
    struct bpf_prog * prog;
    struct user_struct * user;
    u64 load_time;
    struct bpf_map *[2] cgroup_storage;
    char[16] name;
    void * security;
    struct bpf_prog_offload * offload;
    struct btf * btf;
    struct bpf_func_info * func_info;
    struct bpf_func_info_aux * func_info_aux;
    struct bpf_line_info * linfo;
    void * * jited_linfo;
    u32 func_info_cnt;
    u32 nr_linfo;
    u32 linfo_idx;
    u32 num_exentries;
    struct exception_table_entry * extable;
    struct bpf_prog_stats * stats;
    struct work_struct work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic64_t refcnt;
    u32 used_map_cnt;
    u32 max_ctx_offset;
    u32 max_pkt_offset;
    u32 max_tp_access;
    u32 stack_depth;
    u32 id;
    u32 func_cnt;
    u32 func_idx;
    u32 attach_btf_id;
    u32 ctx_arg_info_size;
    u32 max_rdonly_access;
    u32 max_rdwr_access;
    struct btf * attach_btf;
    const struct bpf_ctx_arg_aux * ctx_arg_info;
    struct mutex dst_mutex;
    struct bpf_prog * dst_prog;
    struct bpf_trampoline * dst_trampoline;
    enum bpf_prog_type saved_dst_prog_type;
    enum bpf_attach_type saved_dst_attach_type;
    bool verifier_zext;
    bool offload_requested;
    bool attach_btf_trace;
    bool func_proto_unreliable;
    bool sleepable;
    bool tail_call_reachable;
    struct hlist_node tramp_hlist;
    const struct btf_type * attach_func_proto;
    const char * attach_func_name;
    struct bpf_prog * * func;
    void * jit_data;
    struct bpf_jit_poke_descriptor * poke_tab;
    u32 size_poke_tab;
    struct bpf_ksym ksym;
    const struct bpf_prog_ops * ops;
    struct bpf_map * * used_maps;
    struct mutex used_maps_mutex;
    struct bpf_prog * prog;
    struct user_struct * user;
    u64 load_time;
    struct bpf_map *[2] cgroup_storage;
    char[16] name;
    void * security;
    struct bpf_prog_offload * offload;
    struct btf * btf;
    struct bpf_func_info * func_info;
    struct bpf_func_info_aux * func_info_aux;
    struct bpf_line_info * linfo;
    void * * jited_linfo;
    u32 func_info_cnt;
    u32 nr_linfo;
    u32 linfo_idx;
    u32 num_exentries;
    struct exception_table_entry * extable;
    struct bpf_prog_stats * stats;
    struct work_struct work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic64_t refcnt;
    u32 used_map_cnt;
    u32 used_btf_cnt;
    u32 max_ctx_offset;
    u32 max_pkt_offset;
    u32 max_tp_access;
    u32 stack_depth;
    u32 id;
    u32 func_cnt;
    u32 func_idx;
    u32 attach_btf_id;
    u32 ctx_arg_info_size;
    u32 max_rdonly_access;
    u32 max_rdwr_access;
    struct btf * attach_btf;
    const struct bpf_ctx_arg_aux * ctx_arg_info;
    struct mutex dst_mutex;
    struct bpf_prog * dst_prog;
    struct bpf_trampoline * dst_trampoline;
    enum bpf_prog_type saved_dst_prog_type;
    enum bpf_attach_type saved_dst_attach_type;
    bool verifier_zext;
    bool offload_requested;
    bool attach_btf_trace;
    bool func_proto_unreliable;
    bool sleepable;
    bool tail_call_reachable;
    struct hlist_node tramp_hlist;
    const struct btf_type * attach_func_proto;
    const char * attach_func_name;
    struct bpf_prog * * func;
    void * jit_data;
    struct bpf_jit_poke_descriptor * poke_tab;
    struct bpf_kfunc_desc_tab * kfunc_tab;
    u32 size_poke_tab;
    struct bpf_ksym ksym;
    const struct bpf_prog_ops * ops;
    struct bpf_map * * used_maps;
    struct mutex used_maps_mutex;
    struct btf_mod_pair * used_btfs;
    struct bpf_prog * prog;
    struct user_struct * user;
    u64 load_time;
    struct bpf_map *[2] cgroup_storage;
    char[16] name;
    void * security;
    struct bpf_prog_offload * offload;
    struct btf * btf;
    struct bpf_func_info * func_info;
    struct bpf_func_info_aux * func_info_aux;
    struct bpf_line_info * linfo;
    void * * jited_linfo;
    u32 func_info_cnt;
    u32 nr_linfo;
    u32 linfo_idx;
    u32 num_exentries;
    struct exception_table_entry * extable;
    struct work_struct work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic64_t refcnt;
    u32 used_map_cnt;
    u32 used_btf_cnt;
    u32 max_ctx_offset;
    u32 max_pkt_offset;
    u32 max_tp_access;
    u32 stack_depth;
    u32 id;
    u32 func_cnt;
    u32 func_idx;
    u32 attach_btf_id;
    u32 ctx_arg_info_size;
    u32 max_rdonly_access;
    u32 max_rdwr_access;
    struct btf * attach_btf;
    const struct bpf_ctx_arg_aux * ctx_arg_info;
    struct mutex dst_mutex;
    struct bpf_prog * dst_prog;
    struct bpf_trampoline * dst_trampoline;
    enum bpf_prog_type saved_dst_prog_type;
    enum bpf_attach_type saved_dst_attach_type;
    bool verifier_zext;
    bool offload_requested;
    bool attach_btf_trace;
    bool func_proto_unreliable;
    bool sleepable;
    bool tail_call_reachable;
    struct hlist_node tramp_hlist;
    const struct btf_type * attach_func_proto;
    const char * attach_func_name;
    struct bpf_prog * * func;
    void * jit_data;
    struct bpf_jit_poke_descriptor * poke_tab;
    struct bpf_kfunc_desc_tab * kfunc_tab;
    u32 size_poke_tab;
    struct bpf_ksym ksym;
    const struct bpf_prog_ops * ops;
    struct bpf_map * * used_maps;
    struct mutex used_maps_mutex;
    struct btf_mod_pair * used_btfs;
    struct bpf_prog * prog;
    struct user_struct * user;
    u64 load_time;
    struct bpf_map *[2] cgroup_storage;
    char[16] name;
    void * security;
    struct bpf_prog_offload * offload;
    struct btf * btf;
    struct bpf_func_info * func_info;
    struct bpf_func_info_aux * func_info_aux;
    struct bpf_line_info * linfo;
    void * * jited_linfo;
    u32 func_info_cnt;
    u32 nr_linfo;
    u32 linfo_idx;
    u32 num_exentries;
    struct exception_table_entry * extable;
    struct work_struct work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic64_t refcnt;
    u32 used_map_cnt;
    u32 used_btf_cnt;
    u32 max_ctx_offset;
    u32 max_pkt_offset;
    u32 max_tp_access;
    u32 stack_depth;
    u32 id;
    u32 func_cnt;
    u32 func_idx;
    u32 attach_btf_id;
    u32 ctx_arg_info_size;
    u32 max_rdonly_access;
    u32 max_rdwr_access;
    struct btf * attach_btf;
    const struct bpf_ctx_arg_aux * ctx_arg_info;
    struct mutex dst_mutex;
    struct bpf_prog * dst_prog;
    struct bpf_trampoline * dst_trampoline;
    enum bpf_prog_type saved_dst_prog_type;
    enum bpf_attach_type saved_dst_attach_type;
    bool verifier_zext;
    bool offload_requested;
    bool attach_btf_trace;
    bool func_proto_unreliable;
    bool sleepable;
    bool tail_call_reachable;
    bool xdp_has_frags;
    const struct btf_type * attach_func_proto;
    const char * attach_func_name;
    struct bpf_prog * * func;
    void * jit_data;
    struct bpf_jit_poke_descriptor * poke_tab;
    struct bpf_kfunc_desc_tab * kfunc_tab;
    struct bpf_kfunc_btf_tab * kfunc_btf_tab;
    u32 size_poke_tab;
    struct bpf_ksym ksym;
    const struct bpf_prog_ops * ops;
    struct bpf_map * * used_maps;
    struct mutex used_maps_mutex;
    struct btf_mod_pair * used_btfs;
    struct bpf_prog * prog;
    struct user_struct * user;
    u64 load_time;
    u32 verified_insns;
    struct bpf_map *[2] cgroup_storage;
    char[16] name;
    void * security;
    struct bpf_prog_offload * offload;
    struct btf * btf;
    struct bpf_func_info * func_info;
    struct bpf_func_info_aux * func_info_aux;
    struct bpf_line_info * linfo;
    void * * jited_linfo;
    u32 func_info_cnt;
    u32 nr_linfo;
    u32 linfo_idx;
    u32 num_exentries;
    struct exception_table_entry * extable;
    struct work_struct work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic64_t refcnt;
    u32 used_map_cnt;
    u32 used_btf_cnt;
    u32 max_ctx_offset;
    u32 max_pkt_offset;
    u32 max_tp_access;
    u32 stack_depth;
    u32 id;
    u32 func_cnt;
    u32 func_idx;
    u32 attach_btf_id;
    u32 ctx_arg_info_size;
    u32 max_rdonly_access;
    u32 max_rdwr_access;
    struct btf * attach_btf;
    const struct bpf_ctx_arg_aux * ctx_arg_info;
    struct mutex dst_mutex;
    struct bpf_prog * dst_prog;
    struct bpf_trampoline * dst_trampoline;
    enum bpf_prog_type saved_dst_prog_type;
    enum bpf_attach_type saved_dst_attach_type;
    bool verifier_zext;
    bool offload_requested;
    bool attach_btf_trace;
    bool func_proto_unreliable;
    bool sleepable;
    bool tail_call_reachable;
    bool xdp_has_frags;
    const struct btf_type * attach_func_proto;
    const char * attach_func_name;
    struct bpf_prog * * func;
    void * jit_data;
    struct bpf_jit_poke_descriptor * poke_tab;
    struct bpf_kfunc_desc_tab * kfunc_tab;
    struct bpf_kfunc_btf_tab * kfunc_btf_tab;
    u32 size_poke_tab;
    struct bpf_ksym ksym;
    const struct bpf_prog_ops * ops;
    struct bpf_map * * used_maps;
    struct mutex used_maps_mutex;
    struct btf_mod_pair * used_btfs;
    struct bpf_prog * prog;
    struct user_struct * user;
    u64 load_time;
    u32 verified_insns;
    int cgroup_atype;
    struct bpf_map *[2] cgroup_storage;
    char[16] name;
    void * security;
    struct bpf_prog_offload * offload;
    struct btf * btf;
    struct bpf_func_info * func_info;
    struct bpf_func_info_aux * func_info_aux;
    struct bpf_line_info * linfo;
    void * * jited_linfo;
    u32 func_info_cnt;
    u32 nr_linfo;
    u32 linfo_idx;
    u32 num_exentries;
    struct exception_table_entry * extable;
    struct work_struct work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic64_t refcnt;
    u32 used_map_cnt;
    u32 used_btf_cnt;
    u32 max_ctx_offset;
    u32 max_pkt_offset;
    u32 max_tp_access;
    u32 stack_depth;
    u32 id;
    u32 func_cnt;
    u32 func_idx;
    u32 attach_btf_id;
    u32 ctx_arg_info_size;
    u32 max_rdonly_access;
    u32 max_rdwr_access;
    struct btf * attach_btf;
    const struct bpf_ctx_arg_aux * ctx_arg_info;
    struct mutex dst_mutex;
    struct bpf_prog * dst_prog;
    struct bpf_trampoline * dst_trampoline;
    enum bpf_prog_type saved_dst_prog_type;
    enum bpf_attach_type saved_dst_attach_type;
    bool verifier_zext;
    bool dev_bound;
    bool offload_requested;
    bool attach_btf_trace;
    bool func_proto_unreliable;
    bool sleepable;
    bool tail_call_reachable;
    bool xdp_has_frags;
    const struct btf_type * attach_func_proto;
    const char * attach_func_name;
    struct bpf_prog * * func;
    void * jit_data;
    struct bpf_jit_poke_descriptor * poke_tab;
    struct bpf_kfunc_desc_tab * kfunc_tab;
    struct bpf_kfunc_btf_tab * kfunc_btf_tab;
    u32 size_poke_tab;
    struct bpf_ksym ksym;
    const struct bpf_prog_ops * ops;
    struct bpf_map * * used_maps;
    struct mutex used_maps_mutex;
    struct btf_mod_pair * used_btfs;
    struct bpf_prog * prog;
    struct user_struct * user;
    u64 load_time;
    u32 verified_insns;
    int cgroup_atype;
    struct bpf_map *[2] cgroup_storage;
    char[16] name;
    void * security;
    struct bpf_prog_offload * offload;
    struct btf * btf;
    struct bpf_func_info * func_info;
    struct bpf_func_info_aux * func_info_aux;
    struct bpf_line_info * linfo;
    void * * jited_linfo;
    u32 func_info_cnt;
    u32 nr_linfo;
    u32 linfo_idx;
    struct module * mod;
    u32 num_exentries;
    struct exception_table_entry * extable;
    struct work_struct work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic64_t refcnt;
    u32 used_map_cnt;
    u32 used_btf_cnt;
    u32 max_ctx_offset;
    u32 max_pkt_offset;
    u32 max_tp_access;
    u32 stack_depth;
    u32 id;
    u32 func_cnt;
    u32 real_func_cnt;
    u32 func_idx;
    u32 attach_btf_id;
    u32 ctx_arg_info_size;
    u32 max_rdonly_access;
    u32 max_rdwr_access;
    struct btf * attach_btf;
    const struct bpf_ctx_arg_aux * ctx_arg_info;
    struct mutex dst_mutex;
    struct bpf_prog * dst_prog;
    struct bpf_trampoline * dst_trampoline;
    enum bpf_prog_type saved_dst_prog_type;
    enum bpf_attach_type saved_dst_attach_type;
    bool verifier_zext;
    bool dev_bound;
    bool offload_requested;
    bool attach_btf_trace;
    bool attach_tracing_prog;
    bool func_proto_unreliable;
    bool sleepable;
    bool tail_call_reachable;
    bool xdp_has_frags;
    bool exception_cb;
    bool exception_boundary;
    const struct btf_type * attach_func_proto;
    const char * attach_func_name;
    struct bpf_prog * * func;
    void * jit_data;
    struct bpf_jit_poke_descriptor * poke_tab;
    struct bpf_kfunc_desc_tab * kfunc_tab;
    struct bpf_kfunc_btf_tab * kfunc_btf_tab;
    u32 size_poke_tab;
    struct bpf_ksym ksym;
    const struct bpf_prog_ops * ops;
    struct bpf_map * * used_maps;
    struct mutex used_maps_mutex;
    struct btf_mod_pair * used_btfs;
    struct bpf_prog * prog;
    struct user_struct * user;
    u64 load_time;
    u32 verified_insns;
    int cgroup_atype;
    struct bpf_map *[2] cgroup_storage;
    char[16] name;
    u64 (*)(u64, u64, u64, u64, u64) bpf_exception_cb;
    void * security;
    struct bpf_prog_offload * offload;
    struct btf * btf;
    struct bpf_func_info * func_info;
    struct bpf_func_info_aux * func_info_aux;
    struct bpf_line_info * linfo;
    void * * jited_linfo;
    u32 func_info_cnt;
    u32 nr_linfo;
    u32 linfo_idx;
    struct module * mod;
    u32 num_exentries;
    struct exception_table_entry * extable;
    struct work_struct work;
    struct callback_head rcu;
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
struct bpf_prog_aux {
    atomic_t refcnt;
    u32 used_map_cnt;
    u32 max_ctx_offset;
    u32 max_pkt_offset;
    u32 max_tp_access;
    u32 stack_depth;
    u32 id;
    u32 func_cnt;
    u32 func_idx;
    bool verifier_zext;
    bool offload_requested;
    struct bpf_prog * * func;
    void * jit_data;
    struct latch_tree_node ksym_tnode;
    struct list_head ksym_lnode;
    const struct bpf_prog_ops * ops;
    struct bpf_map * * used_maps;
    struct bpf_prog * prog;
    struct user_struct * user;
    u64 load_time;
    struct bpf_map *[2] cgroup_storage;
    char[16] name;
    void * security;
    struct bpf_prog_offload * offload;
    struct btf * btf;
    struct bpf_func_info * func_info;
    struct bpf_line_info * linfo;
    void * * jited_linfo;
    u32 func_info_cnt;
    u32 nr_linfo;
    u32 linfo_idx;
    struct bpf_prog_stats * stats;
    struct work_struct work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic_t refcnt;
    u32 used_map_cnt;
    u32 max_ctx_offset;
    u32 max_pkt_offset;
    u32 max_tp_access;
    u32 stack_depth;
    u32 id;
    u32 func_cnt;
    u32 func_idx;
    bool verifier_zext;
    bool offload_requested;
    struct bpf_prog * * func;
    void * jit_data;
    struct latch_tree_node ksym_tnode;
    struct list_head ksym_lnode;
    const struct bpf_prog_ops * ops;
    struct bpf_map * * used_maps;
    struct bpf_prog * prog;
    struct user_struct * user;
    u64 load_time;
    struct bpf_map *[2] cgroup_storage;
    char[16] name;
    void * security;
    struct bpf_prog_offload * offload;
    struct btf * btf;
    struct bpf_func_info * func_info;
    struct bpf_line_info * linfo;
    void * * jited_linfo;
    u32 func_info_cnt;
    u32 nr_linfo;
    u32 linfo_idx;
    struct bpf_prog_stats * stats;
    struct work_struct work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic_t refcnt;
    u32 used_map_cnt;
    u32 max_ctx_offset;
    u32 max_pkt_offset;
    u32 max_tp_access;
    u32 stack_depth;
    u32 id;
    u32 func_cnt;
    u32 func_idx;
    bool verifier_zext;
    bool offload_requested;
    struct bpf_prog * * func;
    void * jit_data;
    struct latch_tree_node ksym_tnode;
    struct list_head ksym_lnode;
    const struct bpf_prog_ops * ops;
    struct bpf_map * * used_maps;
    struct bpf_prog * prog;
    struct user_struct * user;
    u64 load_time;
    struct bpf_map *[2] cgroup_storage;
    char[16] name;
    void * security;
    struct bpf_prog_offload * offload;
    struct btf * btf;
    struct bpf_func_info * func_info;
    struct bpf_line_info * linfo;
    void * * jited_linfo;
    u32 func_info_cnt;
    u32 nr_linfo;
    u32 linfo_idx;
    struct bpf_prog_stats * stats;
    struct work_struct work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic_t refcnt;
    u32 used_map_cnt;
    u32 max_ctx_offset;
    u32 max_pkt_offset;
    u32 max_tp_access;
    u32 stack_depth;
    u32 id;
    u32 func_cnt;
    u32 func_idx;
    bool verifier_zext;
    bool offload_requested;
    struct bpf_prog * * func;
    void * jit_data;
    struct latch_tree_node ksym_tnode;
    struct list_head ksym_lnode;
    const struct bpf_prog_ops * ops;
    struct bpf_map * * used_maps;
    struct bpf_prog * prog;
    struct user_struct * user;
    u64 load_time;
    struct bpf_map *[2] cgroup_storage;
    char[16] name;
    void * security;
    struct bpf_prog_offload * offload;
    struct btf * btf;
    struct bpf_func_info * func_info;
    struct bpf_line_info * linfo;
    void * * jited_linfo;
    u32 func_info_cnt;
    u32 nr_linfo;
    u32 linfo_idx;
    struct bpf_prog_stats * stats;
    struct work_struct work;
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
struct bpf_prog_aux {
    atomic_t refcnt;
    u32 used_map_cnt;
    u32 max_ctx_offset;
    u32 max_pkt_offset;
    u32 max_tp_access;
    u32 stack_depth;
    u32 id;
    u32 func_cnt;
    u32 func_idx;
    bool verifier_zext;
    bool offload_requested;
    struct bpf_prog * * func;
    void * jit_data;
    struct latch_tree_node ksym_tnode;
    struct list_head ksym_lnode;
    const struct bpf_prog_ops * ops;
    struct bpf_map * * used_maps;
    struct bpf_prog * prog;
    struct user_struct * user;
    u64 load_time;
    struct bpf_map *[2] cgroup_storage;
    char[16] name;
    void * security;
    struct bpf_prog_offload * offload;
    struct btf * btf;
    struct bpf_func_info * func_info;
    struct bpf_line_info * linfo;
    void * * jited_linfo;
    u32 func_info_cnt;
    u32 nr_linfo;
    u32 linfo_idx;
    struct bpf_prog_stats * stats;
    struct work_struct work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic_t refcnt;
    u32 used_map_cnt;
    u32 max_ctx_offset;
    u32 max_pkt_offset;
    u32 max_tp_access;
    u32 stack_depth;
    u32 id;
    u32 func_cnt;
    u32 func_idx;
    bool verifier_zext;
    bool offload_requested;
    struct bpf_prog * * func;
    void * jit_data;
    struct latch_tree_node ksym_tnode;
    struct list_head ksym_lnode;
    const struct bpf_prog_ops * ops;
    struct bpf_map * * used_maps;
    struct bpf_prog * prog;
    struct user_struct * user;
    u64 load_time;
    struct bpf_map *[2] cgroup_storage;
    char[16] name;
    void * security;
    struct bpf_prog_offload * offload;
    struct btf * btf;
    struct bpf_func_info * func_info;
    struct bpf_line_info * linfo;
    void * * jited_linfo;
    u32 func_info_cnt;
    u32 nr_linfo;
    u32 linfo_idx;
    struct bpf_prog_stats * stats;
    struct work_struct work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic_t refcnt;
    u32 used_map_cnt;
    u32 max_ctx_offset;
    u32 max_pkt_offset;
    u32 max_tp_access;
    u32 stack_depth;
    u32 id;
    u32 func_cnt;
    u32 func_idx;
    bool verifier_zext;
    bool offload_requested;
    struct bpf_prog * * func;
    void * jit_data;
    struct latch_tree_node ksym_tnode;
    struct list_head ksym_lnode;
    const struct bpf_prog_ops * ops;
    struct bpf_map * * used_maps;
    struct bpf_prog * prog;
    struct user_struct * user;
    u64 load_time;
    struct bpf_map *[2] cgroup_storage;
    char[16] name;
    void * security;
    struct bpf_prog_offload * offload;
    struct btf * btf;
    struct bpf_func_info * func_info;
    struct bpf_line_info * linfo;
    void * * jited_linfo;
    u32 func_info_cnt;
    u32 nr_linfo;
    u32 linfo_idx;
    struct bpf_prog_stats * stats;
    struct work_struct work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bpf_prog_aux {
    atomic_t refcnt;
    u32 used_map_cnt;
    u32 max_ctx_offset;
    u32 max_pkt_offset;
    u32 max_tp_access;
    u32 stack_depth;
    u32 id;
    u32 func_cnt;
    u32 func_idx;
    bool verifier_zext;
    bool offload_requested;
    struct bpf_prog * * func;
    void * jit_data;
    struct latch_tree_node ksym_tnode;
    struct list_head ksym_lnode;
    const struct bpf_prog_ops * ops;
    struct bpf_map * * used_maps;
    struct bpf_prog * prog;
    struct user_struct * user;
    u64 load_time;
    struct bpf_map *[2] cgroup_storage;
    char[16] name;
    void * security;
    struct bpf_prog_offload * offload;
    struct btf * btf;
    struct bpf_func_info * func_info;
    struct bpf_line_info * linfo;
    void * * jited_linfo;
    u32 func_info_cnt;
    u32 nr_linfo;
    u32 linfo_idx;
    struct bpf_prog_stats * stats;
    struct work_struct work;
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 max_ctx_offset</code>
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
<code>u32 stack_depth</code>
</li>
<li>
<b>Field added. </b>
<code>u32 id</code>
</li>
<li>
<b>Field added. </b>
<code>struct latch_tree_node ksym_tnode</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head ksym_lnode</code>
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
<code>u64 load_time</code>
</li>
<li>
<b>Field added. </b>
<code>char[16] name</code>
</li>
<li>
<b>Field added. </b>
<code>void * security</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_dev_offload * offload</code>
</li>
<li>
<b>Field type changed. </b>
<code>const struct bpf_verifier_ops * ops</code> ➡️ <code>const struct bpf_prog_ops * ops</code>
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
<code>u32 func_cnt</code>
</li>
<li>
<b>Field added. </b>
<code>bool offload_requested</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_prog * * func</code>
</li>
<li>
<b>Field added. </b>
<code>void * jit_data</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct bpf_dev_offload * offload</code> ➡️ <code>struct bpf_prog_offload * offload</code>
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
<code>u32 max_pkt_offset</code>
</li>
<li>
<b>Field added. </b>
<code>u32 func_idx</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_map *[2] cgroup_storage</code>
</li>
<li>
<b>Field added. </b>
<code>struct btf * btf</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_func_info * func_info</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_line_info * linfo</code>
</li>
<li>
<b>Field added. </b>
<code>void * * jited_linfo</code>
</li>
<li>
<b>Field added. </b>
<code>u32 func_info_cnt</code>
</li>
<li>
<b>Field added. </b>
<code>u32 nr_linfo</code>
</li>
<li>
<b>Field added. </b>
<code>u32 linfo_idx</code>
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
<code>u32 max_tp_access</code>
</li>
<li>
<b>Field added. </b>
<code>bool verifier_zext</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_prog_stats * stats</code>
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
<code>u32 attach_btf_id</code>
</li>
<li>
<b>Field added. </b>
<code>u32 ctx_arg_info_size</code>
</li>
<li>
<b>Field added. </b>
<code>const struct bpf_ctx_arg_aux * ctx_arg_info</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_prog * linked_prog</code>
</li>
<li>
<b>Field added. </b>
<code>bool attach_btf_trace</code>
</li>
<li>
<b>Field added. </b>
<code>bool func_proto_unreliable</code>
</li>
<li>
<b>Field added. </b>
<code>enum bpf_tramp_prog_type trampoline_prog_type</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_trampoline * trampoline</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_node tramp_hlist</code>
</li>
<li>
<b>Field added. </b>
<code>const struct btf_type * attach_func_proto</code>
</li>
<li>
<b>Field added. </b>
<code>const char * attach_func_name</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_jit_poke_descriptor * poke_tab</code>
</li>
<li>
<b>Field added. </b>
<code>u32 size_poke_tab</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_ksym ksym</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_func_info_aux * func_info_aux</code>
</li>
<li>
<b>Field added. </b>
<code>u32 num_exentries</code>
</li>
<li>
<b>Field added. </b>
<code>struct exception_table_entry * extable</code>
</li>
<li>
<b>Field removed. </b>
<code>struct latch_tree_node ksym_tnode</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head ksym_lnode</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t refcnt</code> ➡️ <code>atomic64_t refcnt</code>
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
<code>u32 max_rdonly_access</code>
</li>
<li>
<b>Field added. </b>
<code>u32 max_rdwr_access</code>
</li>
<li>
<b>Field added. </b>
<code>struct btf * attach_btf</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex dst_mutex</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_prog * dst_prog</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_trampoline * dst_trampoline</code>
</li>
<li>
<b>Field added. </b>
<code>enum bpf_prog_type saved_dst_prog_type</code>
</li>
<li>
<b>Field added. </b>
<code>enum bpf_attach_type saved_dst_attach_type</code>
</li>
<li>
<b>Field added. </b>
<code>bool sleepable</code>
</li>
<li>
<b>Field added. </b>
<code>bool tail_call_reachable</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex used_maps_mutex</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bpf_prog * linked_prog</code>
</li>
<li>
<b>Field removed. </b>
<code>enum bpf_tramp_prog_type trampoline_prog_type</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bpf_trampoline * trampoline</code>
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
<code>u32 used_btf_cnt</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_kfunc_desc_tab * kfunc_tab</code>
</li>
<li>
<b>Field added. </b>
<code>struct btf_mod_pair * used_btfs</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bpf_prog_stats * stats</code>
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
<code>bool xdp_has_frags</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_kfunc_btf_tab * kfunc_btf_tab</code>
</li>
<li>
<b>Field added. </b>
<code>u32 verified_insns</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_node tramp_hlist</code>
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
<code>int cgroup_atype</code>
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
<code>bool dev_bound</code>
</li>
<li>
<b>Field added. </b>
<code>struct module * mod</code>
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
<code>u32 real_func_cnt</code>
</li>
<li>
<b>Field added. </b>
<code>bool attach_tracing_prog</code>
</li>
<li>
<b>Field added. </b>
<code>bool exception_cb</code>
</li>
<li>
<b>Field added. </b>
<code>bool exception_boundary</code>
</li>
<li>
<b>Field added. </b>
<code>u64 (*)(u64, u64, u64, u64, u64) bpf_exception_cb</code>
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
