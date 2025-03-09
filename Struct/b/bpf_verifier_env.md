# Struct: <code>bpf_verifier_env</code>

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
struct bpf_verifier_env {
    struct bpf_prog * prog;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    struct bpf_verifier_state cur_state;
    struct bpf_verifier_state_list * * explored_states;
    const struct bpf_ext_analyzer_ops * analyzer_ops;
    void * analyzer_priv;
    struct bpf_map *[64] used_maps;
    u32 used_map_cnt;
    u32 id_gen;
    bool allow_ptr_leaks;
    bool seen_direct_write;
    bool varlen_map_value_access;
    struct bpf_insn_aux_data * insn_aux_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_env {
    struct bpf_prog * prog;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    bool strict_alignment;
    struct bpf_verifier_state cur_state;
    struct bpf_verifier_state_list * * explored_states;
    const struct bpf_ext_analyzer_ops * analyzer_ops;
    void * analyzer_priv;
    struct bpf_map *[64] used_maps;
    u32 used_map_cnt;
    u32 id_gen;
    bool allow_ptr_leaks;
    bool seen_direct_write;
    bool varlen_map_value_access;
    struct bpf_insn_aux_data * insn_aux_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_env {
    struct bpf_prog * prog;
    const struct bpf_verifier_ops * ops;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    bool strict_alignment;
    struct bpf_verifier_state * cur_state;
    struct bpf_verifier_state_list * * explored_states;
    const struct bpf_ext_analyzer_ops * dev_ops;
    struct bpf_map *[64] used_maps;
    u32 used_map_cnt;
    u32 id_gen;
    bool allow_ptr_leaks;
    bool seen_direct_write;
    struct bpf_insn_aux_data * insn_aux_data;
    struct bpf_verifer_log log;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_env {
    struct bpf_prog * prog;
    const struct bpf_verifier_ops * ops;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    bool strict_alignment;
    struct bpf_verifier_state * cur_state;
    struct bpf_verifier_state_list * * explored_states;
    struct bpf_map *[64] used_maps;
    u32 used_map_cnt;
    u32 id_gen;
    bool allow_ptr_leaks;
    bool seen_direct_write;
    struct bpf_insn_aux_data * insn_aux_data;
    struct bpf_verifier_log log;
    struct bpf_subprog_info[257] subprog_info;
    u32 subprog_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_env {
    u32 insn_idx;
    u32 prev_insn_idx;
    struct bpf_prog * prog;
    const struct bpf_verifier_ops * ops;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    bool strict_alignment;
    struct bpf_verifier_state * cur_state;
    struct bpf_verifier_state_list * * explored_states;
    struct bpf_map *[64] used_maps;
    u32 used_map_cnt;
    u32 id_gen;
    bool allow_ptr_leaks;
    bool seen_direct_write;
    struct bpf_insn_aux_data * insn_aux_data;
    const struct bpf_line_info * prev_linfo;
    struct bpf_verifier_log log;
    struct bpf_subprog_info[257] subprog_info;
    u32 subprog_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_env {
    u32 insn_idx;
    u32 prev_insn_idx;
    struct bpf_prog * prog;
    const struct bpf_verifier_ops * ops;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    bool strict_alignment;
    struct bpf_verifier_state * cur_state;
    struct bpf_verifier_state_list * * explored_states;
    struct bpf_verifier_state_list * free_list;
    struct bpf_map *[64] used_maps;
    u32 used_map_cnt;
    u32 id_gen;
    bool allow_ptr_leaks;
    bool seen_direct_write;
    struct bpf_insn_aux_data * insn_aux_data;
    const struct bpf_line_info * prev_linfo;
    struct bpf_verifier_log log;
    struct bpf_subprog_info[257] subprog_info;
    struct (anon) cfg;
    u32 subprog_cnt;
    u32 prev_insn_processed;
    u32 insn_processed;
    u32 prev_jmps_processed;
    u32 jmps_processed;
    u64 verification_time;
    u32 max_states_per_insn;
    u32 total_states;
    u32 peak_states;
    u32 longest_mark_read_walk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_env {
    u32 insn_idx;
    u32 prev_insn_idx;
    struct bpf_prog * prog;
    const struct bpf_verifier_ops * ops;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    bool strict_alignment;
    bool test_state_freq;
    struct bpf_verifier_state * cur_state;
    struct bpf_verifier_state_list * * explored_states;
    struct bpf_verifier_state_list * free_list;
    struct bpf_map *[64] used_maps;
    u32 used_map_cnt;
    u32 id_gen;
    bool allow_ptr_leaks;
    bool seen_direct_write;
    struct bpf_insn_aux_data * insn_aux_data;
    const struct bpf_line_info * prev_linfo;
    struct bpf_verifier_log log;
    struct bpf_subprog_info[257] subprog_info;
    struct (anon) cfg;
    u32 subprog_cnt;
    u32 prev_insn_processed;
    u32 insn_processed;
    u32 prev_jmps_processed;
    u32 jmps_processed;
    u64 verification_time;
    u32 max_states_per_insn;
    u32 total_states;
    u32 peak_states;
    u32 longest_mark_read_walk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_env {
    u32 insn_idx;
    u32 prev_insn_idx;
    struct bpf_prog * prog;
    const struct bpf_verifier_ops * ops;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    bool strict_alignment;
    bool test_state_freq;
    struct bpf_verifier_state * cur_state;
    struct bpf_verifier_state_list * * explored_states;
    struct bpf_verifier_state_list * free_list;
    struct bpf_map *[64] used_maps;
    u32 used_map_cnt;
    u32 id_gen;
    bool allow_ptr_leaks;
    bool bpf_capable;
    bool bypass_spec_v1;
    bool bypass_spec_v4;
    bool seen_direct_write;
    struct bpf_insn_aux_data * insn_aux_data;
    const struct bpf_line_info * prev_linfo;
    struct bpf_verifier_log log;
    struct bpf_subprog_info[257] subprog_info;
    struct (anon) cfg;
    u32 pass_cnt;
    u32 subprog_cnt;
    u32 prev_insn_processed;
    u32 insn_processed;
    u32 prev_jmps_processed;
    u32 jmps_processed;
    u64 verification_time;
    u32 max_states_per_insn;
    u32 total_states;
    u32 peak_states;
    u32 longest_mark_read_walk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_env {
    u32 insn_idx;
    u32 prev_insn_idx;
    struct bpf_prog * prog;
    const struct bpf_verifier_ops * ops;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    bool strict_alignment;
    bool test_state_freq;
    struct bpf_verifier_state * cur_state;
    struct bpf_verifier_state_list * * explored_states;
    struct bpf_verifier_state_list * free_list;
    struct bpf_map *[64] used_maps;
    u32 used_map_cnt;
    u32 id_gen;
    bool allow_ptr_leaks;
    bool allow_ptr_to_map_access;
    bool bpf_capable;
    bool bypass_spec_v1;
    bool bypass_spec_v4;
    bool seen_direct_write;
    struct bpf_insn_aux_data * insn_aux_data;
    const struct bpf_line_info * prev_linfo;
    struct bpf_verifier_log log;
    struct bpf_subprog_info[257] subprog_info;
    struct (anon) cfg;
    u32 pass_cnt;
    u32 subprog_cnt;
    u32 prev_insn_processed;
    u32 insn_processed;
    u32 prev_jmps_processed;
    u32 jmps_processed;
    u64 verification_time;
    u32 max_states_per_insn;
    u32 total_states;
    u32 peak_states;
    u32 longest_mark_read_walk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_env {
    u32 insn_idx;
    u32 prev_insn_idx;
    struct bpf_prog * prog;
    const struct bpf_verifier_ops * ops;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    bool strict_alignment;
    bool test_state_freq;
    struct bpf_verifier_state * cur_state;
    struct bpf_verifier_state_list * * explored_states;
    struct bpf_verifier_state_list * free_list;
    struct bpf_map *[64] used_maps;
    struct btf_mod_pair[64] used_btfs;
    u32 used_map_cnt;
    u32 used_btf_cnt;
    u32 id_gen;
    bool explore_alu_limits;
    bool allow_ptr_leaks;
    bool allow_uninit_stack;
    bool allow_ptr_to_map_access;
    bool bpf_capable;
    bool bypass_spec_v1;
    bool bypass_spec_v4;
    bool seen_direct_write;
    struct bpf_insn_aux_data * insn_aux_data;
    const struct bpf_line_info * prev_linfo;
    struct bpf_verifier_log log;
    struct bpf_subprog_info[257] subprog_info;
    struct bpf_id_pair[75] idmap_scratch;
    struct (anon) cfg;
    u32 pass_cnt;
    u32 subprog_cnt;
    u32 prev_insn_processed;
    u32 insn_processed;
    u32 prev_jmps_processed;
    u32 jmps_processed;
    u64 verification_time;
    u32 max_states_per_insn;
    u32 total_states;
    u32 peak_states;
    u32 longest_mark_read_walk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_env {
    u32 insn_idx;
    u32 prev_insn_idx;
    struct bpf_prog * prog;
    const struct bpf_verifier_ops * ops;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    bool strict_alignment;
    bool test_state_freq;
    struct bpf_verifier_state * cur_state;
    struct bpf_verifier_state_list * * explored_states;
    struct bpf_verifier_state_list * free_list;
    struct bpf_map *[64] used_maps;
    struct btf_mod_pair[64] used_btfs;
    u32 used_map_cnt;
    u32 used_btf_cnt;
    u32 id_gen;
    bool explore_alu_limits;
    bool allow_ptr_leaks;
    bool allow_uninit_stack;
    bool allow_ptr_to_map_access;
    bool bpf_capable;
    bool bypass_spec_v1;
    bool bypass_spec_v4;
    bool seen_direct_write;
    struct bpf_insn_aux_data * insn_aux_data;
    const struct bpf_line_info * prev_linfo;
    struct bpf_verifier_log log;
    struct bpf_subprog_info[257] subprog_info;
    struct bpf_id_pair[75] idmap_scratch;
    struct (anon) cfg;
    u32 pass_cnt;
    u32 subprog_cnt;
    u32 prev_insn_processed;
    u32 insn_processed;
    u32 prev_jmps_processed;
    u32 jmps_processed;
    u64 verification_time;
    u32 max_states_per_insn;
    u32 total_states;
    u32 peak_states;
    u32 longest_mark_read_walk;
    bpfptr_t fd_array;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_env {
    u32 insn_idx;
    u32 prev_insn_idx;
    struct bpf_prog * prog;
    const struct bpf_verifier_ops * ops;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    bool strict_alignment;
    bool test_state_freq;
    struct bpf_verifier_state * cur_state;
    struct bpf_verifier_state_list * * explored_states;
    struct bpf_verifier_state_list * free_list;
    struct bpf_map *[64] used_maps;
    struct btf_mod_pair[64] used_btfs;
    u32 used_map_cnt;
    u32 used_btf_cnt;
    u32 id_gen;
    bool explore_alu_limits;
    bool allow_ptr_leaks;
    bool allow_uninit_stack;
    bool allow_ptr_to_map_access;
    bool bpf_capable;
    bool bypass_spec_v1;
    bool bypass_spec_v4;
    bool seen_direct_write;
    struct bpf_insn_aux_data * insn_aux_data;
    const struct bpf_line_info * prev_linfo;
    struct bpf_verifier_log log;
    struct bpf_subprog_info[257] subprog_info;
    struct bpf_id_pair[75] idmap_scratch;
    struct (anon) cfg;
    u32 pass_cnt;
    u32 subprog_cnt;
    u32 prev_insn_processed;
    u32 insn_processed;
    u32 prev_jmps_processed;
    u32 jmps_processed;
    u64 verification_time;
    u32 max_states_per_insn;
    u32 total_states;
    u32 peak_states;
    u32 longest_mark_read_walk;
    bpfptr_t fd_array;
    u32 scratched_regs;
    u64 scratched_stack_slots;
    u32 prev_log_len;
    u32 prev_insn_print_len;
    char[64] type_str_buf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_env {
    u32 insn_idx;
    u32 prev_insn_idx;
    struct bpf_prog * prog;
    const struct bpf_verifier_ops * ops;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    bool strict_alignment;
    bool test_state_freq;
    struct bpf_verifier_state * cur_state;
    struct bpf_verifier_state_list * * explored_states;
    struct bpf_verifier_state_list * free_list;
    struct bpf_map *[64] used_maps;
    struct btf_mod_pair[64] used_btfs;
    u32 used_map_cnt;
    u32 used_btf_cnt;
    u32 id_gen;
    bool explore_alu_limits;
    bool allow_ptr_leaks;
    bool allow_uninit_stack;
    bool bpf_capable;
    bool bypass_spec_v1;
    bool bypass_spec_v4;
    bool seen_direct_write;
    bool rcu_tag_supported;
    struct bpf_insn_aux_data * insn_aux_data;
    const struct bpf_line_info * prev_linfo;
    struct bpf_verifier_log log;
    struct bpf_subprog_info[257] subprog_info;
    struct bpf_id_pair[600] idmap_scratch;
    struct (anon) cfg;
    u32 pass_cnt;
    u32 subprog_cnt;
    u32 prev_insn_processed;
    u32 insn_processed;
    u32 prev_jmps_processed;
    u32 jmps_processed;
    u64 verification_time;
    u32 max_states_per_insn;
    u32 total_states;
    u32 peak_states;
    u32 longest_mark_read_walk;
    bpfptr_t fd_array;
    u32 scratched_regs;
    u64 scratched_stack_slots;
    u32 prev_log_len;
    u32 prev_insn_print_len;
    char[128] type_str_buf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_env {
    u32 insn_idx;
    u32 prev_insn_idx;
    struct bpf_prog * prog;
    const struct bpf_verifier_ops * ops;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    bool strict_alignment;
    bool test_state_freq;
    struct bpf_verifier_state * cur_state;
    struct bpf_verifier_state_list * * explored_states;
    struct bpf_verifier_state_list * free_list;
    struct bpf_map *[64] used_maps;
    struct btf_mod_pair[64] used_btfs;
    u32 used_map_cnt;
    u32 used_btf_cnt;
    u32 id_gen;
    bool explore_alu_limits;
    bool allow_ptr_leaks;
    bool allow_uninit_stack;
    bool bpf_capable;
    bool bypass_spec_v1;
    bool bypass_spec_v4;
    bool seen_direct_write;
    struct bpf_insn_aux_data * insn_aux_data;
    const struct bpf_line_info * prev_linfo;
    struct bpf_verifier_log log;
    struct bpf_subprog_info[257] subprog_info;
    struct bpf_idmap idmap_scratch;
    struct bpf_idset idset_scratch;
    struct (anon) cfg;
    struct backtrack_state bt;
    u32 pass_cnt;
    u32 subprog_cnt;
    u32 prev_insn_processed;
    u32 insn_processed;
    u32 prev_jmps_processed;
    u32 jmps_processed;
    u64 verification_time;
    u32 max_states_per_insn;
    u32 total_states;
    u32 peak_states;
    u32 longest_mark_read_walk;
    bpfptr_t fd_array;
    u32 scratched_regs;
    u64 scratched_stack_slots;
    u64 prev_log_pos;
    u64 prev_insn_print_pos;
    char[320] tmp_str_buf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_env {
    u32 insn_idx;
    u32 prev_insn_idx;
    struct bpf_prog * prog;
    const struct bpf_verifier_ops * ops;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    bool strict_alignment;
    bool test_state_freq;
    bool test_reg_invariants;
    struct bpf_verifier_state * cur_state;
    struct bpf_verifier_state_list * * explored_states;
    struct bpf_verifier_state_list * free_list;
    struct bpf_map *[64] used_maps;
    struct btf_mod_pair[64] used_btfs;
    u32 used_map_cnt;
    u32 used_btf_cnt;
    u32 id_gen;
    u32 hidden_subprog_cnt;
    int exception_callback_subprog;
    bool explore_alu_limits;
    bool allow_ptr_leaks;
    bool allow_uninit_stack;
    bool bpf_capable;
    bool bypass_spec_v1;
    bool bypass_spec_v4;
    bool seen_direct_write;
    bool seen_exception;
    struct bpf_insn_aux_data * insn_aux_data;
    const struct bpf_line_info * prev_linfo;
    struct bpf_verifier_log log;
    struct bpf_subprog_info[258] subprog_info;
    struct bpf_idmap idmap_scratch;
    struct bpf_idset idset_scratch;
    struct (anon) cfg;
    struct backtrack_state bt;
    struct bpf_jmp_history_entry * cur_hist_ent;
    u32 pass_cnt;
    u32 subprog_cnt;
    u32 prev_insn_processed;
    u32 insn_processed;
    u32 prev_jmps_processed;
    u32 jmps_processed;
    u64 verification_time;
    u32 max_states_per_insn;
    u32 total_states;
    u32 peak_states;
    u32 longest_mark_read_walk;
    bpfptr_t fd_array;
    u32 scratched_regs;
    u64 scratched_stack_slots;
    u64 prev_log_pos;
    u64 prev_insn_print_pos;
    char[320] tmp_str_buf;
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
struct bpf_verifier_env {
    u32 insn_idx;
    u32 prev_insn_idx;
    struct bpf_prog * prog;
    const struct bpf_verifier_ops * ops;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    bool strict_alignment;
    bool test_state_freq;
    struct bpf_verifier_state * cur_state;
    struct bpf_verifier_state_list * * explored_states;
    struct bpf_verifier_state_list * free_list;
    struct bpf_map *[64] used_maps;
    u32 used_map_cnt;
    u32 id_gen;
    bool allow_ptr_leaks;
    bool seen_direct_write;
    struct bpf_insn_aux_data * insn_aux_data;
    const struct bpf_line_info * prev_linfo;
    struct bpf_verifier_log log;
    struct bpf_subprog_info[257] subprog_info;
    struct (anon) cfg;
    u32 subprog_cnt;
    u32 prev_insn_processed;
    u32 insn_processed;
    u32 prev_jmps_processed;
    u32 jmps_processed;
    u64 verification_time;
    u32 max_states_per_insn;
    u32 total_states;
    u32 peak_states;
    u32 longest_mark_read_walk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bpf_verifier_env {
    u32 insn_idx;
    u32 prev_insn_idx;
    struct bpf_prog * prog;
    const struct bpf_verifier_ops * ops;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    bool strict_alignment;
    bool test_state_freq;
    struct bpf_verifier_state * cur_state;
    struct bpf_verifier_state_list * * explored_states;
    struct bpf_verifier_state_list * free_list;
    struct bpf_map *[64] used_maps;
    u32 used_map_cnt;
    u32 id_gen;
    bool allow_ptr_leaks;
    bool seen_direct_write;
    struct bpf_insn_aux_data * insn_aux_data;
    const struct bpf_line_info * prev_linfo;
    struct bpf_verifier_log log;
    struct bpf_subprog_info[257] subprog_info;
    struct (anon) cfg;
    u32 subprog_cnt;
    u32 prev_insn_processed;
    u32 insn_processed;
    u32 prev_jmps_processed;
    u32 jmps_processed;
    u64 verification_time;
    u32 max_states_per_insn;
    u32 total_states;
    u32 peak_states;
    u32 longest_mark_read_walk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bpf_verifier_env {
    u32 insn_idx;
    u32 prev_insn_idx;
    struct bpf_prog * prog;
    const struct bpf_verifier_ops * ops;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    bool strict_alignment;
    bool test_state_freq;
    struct bpf_verifier_state * cur_state;
    struct bpf_verifier_state_list * * explored_states;
    struct bpf_verifier_state_list * free_list;
    struct bpf_map *[64] used_maps;
    u32 used_map_cnt;
    u32 id_gen;
    bool allow_ptr_leaks;
    bool seen_direct_write;
    struct bpf_insn_aux_data * insn_aux_data;
    const struct bpf_line_info * prev_linfo;
    struct bpf_verifier_log log;
    struct bpf_subprog_info[257] subprog_info;
    struct (anon) cfg;
    u32 subprog_cnt;
    u32 prev_insn_processed;
    u32 insn_processed;
    u32 prev_jmps_processed;
    u32 jmps_processed;
    u64 verification_time;
    u32 max_states_per_insn;
    u32 total_states;
    u32 peak_states;
    u32 longest_mark_read_walk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bpf_verifier_env {
    u32 insn_idx;
    u32 prev_insn_idx;
    struct bpf_prog * prog;
    const struct bpf_verifier_ops * ops;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    bool strict_alignment;
    bool test_state_freq;
    struct bpf_verifier_state * cur_state;
    struct bpf_verifier_state_list * * explored_states;
    struct bpf_verifier_state_list * free_list;
    struct bpf_map *[64] used_maps;
    u32 used_map_cnt;
    u32 id_gen;
    bool allow_ptr_leaks;
    bool seen_direct_write;
    struct bpf_insn_aux_data * insn_aux_data;
    const struct bpf_line_info * prev_linfo;
    struct bpf_verifier_log log;
    struct bpf_subprog_info[257] subprog_info;
    struct (anon) cfg;
    u32 subprog_cnt;
    u32 prev_insn_processed;
    u32 insn_processed;
    u32 prev_jmps_processed;
    u32 jmps_processed;
    u64 verification_time;
    u32 max_states_per_insn;
    u32 total_states;
    u32 peak_states;
    u32 longest_mark_read_walk;
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
struct bpf_verifier_env {
    u32 insn_idx;
    u32 prev_insn_idx;
    struct bpf_prog * prog;
    const struct bpf_verifier_ops * ops;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    bool strict_alignment;
    bool test_state_freq;
    struct bpf_verifier_state * cur_state;
    struct bpf_verifier_state_list * * explored_states;
    struct bpf_verifier_state_list * free_list;
    struct bpf_map *[64] used_maps;
    u32 used_map_cnt;
    u32 id_gen;
    bool allow_ptr_leaks;
    bool seen_direct_write;
    struct bpf_insn_aux_data * insn_aux_data;
    const struct bpf_line_info * prev_linfo;
    struct bpf_verifier_log log;
    struct bpf_subprog_info[257] subprog_info;
    struct (anon) cfg;
    u32 subprog_cnt;
    u32 prev_insn_processed;
    u32 insn_processed;
    u32 prev_jmps_processed;
    u32 jmps_processed;
    u64 verification_time;
    u32 max_states_per_insn;
    u32 total_states;
    u32 peak_states;
    u32 longest_mark_read_walk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bpf_verifier_env {
    u32 insn_idx;
    u32 prev_insn_idx;
    struct bpf_prog * prog;
    const struct bpf_verifier_ops * ops;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    bool strict_alignment;
    bool test_state_freq;
    struct bpf_verifier_state * cur_state;
    struct bpf_verifier_state_list * * explored_states;
    struct bpf_verifier_state_list * free_list;
    struct bpf_map *[64] used_maps;
    u32 used_map_cnt;
    u32 id_gen;
    bool allow_ptr_leaks;
    bool seen_direct_write;
    struct bpf_insn_aux_data * insn_aux_data;
    const struct bpf_line_info * prev_linfo;
    struct bpf_verifier_log log;
    struct bpf_subprog_info[257] subprog_info;
    struct (anon) cfg;
    u32 subprog_cnt;
    u32 prev_insn_processed;
    u32 insn_processed;
    u32 prev_jmps_processed;
    u32 jmps_processed;
    u64 verification_time;
    u32 max_states_per_insn;
    u32 total_states;
    u32 peak_states;
    u32 longest_mark_read_walk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bpf_verifier_env {
    u32 insn_idx;
    u32 prev_insn_idx;
    struct bpf_prog * prog;
    const struct bpf_verifier_ops * ops;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    bool strict_alignment;
    bool test_state_freq;
    struct bpf_verifier_state * cur_state;
    struct bpf_verifier_state_list * * explored_states;
    struct bpf_verifier_state_list * free_list;
    struct bpf_map *[64] used_maps;
    u32 used_map_cnt;
    u32 id_gen;
    bool allow_ptr_leaks;
    bool seen_direct_write;
    struct bpf_insn_aux_data * insn_aux_data;
    const struct bpf_line_info * prev_linfo;
    struct bpf_verifier_log log;
    struct bpf_subprog_info[257] subprog_info;
    struct (anon) cfg;
    u32 subprog_cnt;
    u32 prev_insn_processed;
    u32 insn_processed;
    u32 prev_jmps_processed;
    u32 jmps_processed;
    u64 verification_time;
    u32 max_states_per_insn;
    u32 total_states;
    u32 peak_states;
    u32 longest_mark_read_walk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bpf_verifier_env {
    u32 insn_idx;
    u32 prev_insn_idx;
    struct bpf_prog * prog;
    const struct bpf_verifier_ops * ops;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    bool strict_alignment;
    bool test_state_freq;
    struct bpf_verifier_state * cur_state;
    struct bpf_verifier_state_list * * explored_states;
    struct bpf_verifier_state_list * free_list;
    struct bpf_map *[64] used_maps;
    u32 used_map_cnt;
    u32 id_gen;
    bool allow_ptr_leaks;
    bool seen_direct_write;
    struct bpf_insn_aux_data * insn_aux_data;
    const struct bpf_line_info * prev_linfo;
    struct bpf_verifier_log log;
    struct bpf_subprog_info[257] subprog_info;
    struct (anon) cfg;
    u32 subprog_cnt;
    u32 prev_insn_processed;
    u32 insn_processed;
    u32 prev_jmps_processed;
    u32 jmps_processed;
    u64 verification_time;
    u32 max_states_per_insn;
    u32 total_states;
    u32 peak_states;
    u32 longest_mark_read_walk;
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
struct bpf_verifier_env {
    struct bpf_prog * prog;
    struct bpf_verifier_stack_elem * head;
    int stack_size;
    struct bpf_verifier_state cur_state;
    struct bpf_verifier_state_list * * explored_states;
    const struct bpf_ext_analyzer_ops * analyzer_ops;
    void * analyzer_priv;
    struct bpf_map *[64] used_maps;
    u32 used_map_cnt;
    u32 id_gen;
    bool allow_ptr_leaks;
    bool seen_direct_write;
    bool varlen_map_value_access;
    struct bpf_insn_aux_data * insn_aux_data;
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
<code>bool strict_alignment</code>
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
<code>const struct bpf_verifier_ops * ops</code>
</li>
<li>
<b>Field added. </b>
<code>const struct bpf_ext_analyzer_ops * dev_ops</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_verifer_log log</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct bpf_ext_analyzer_ops * analyzer_ops</code>
</li>
<li>
<b>Field removed. </b>
<code>void * analyzer_priv</code>
</li>
<li>
<b>Field removed. </b>
<code>bool varlen_map_value_access</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct bpf_verifier_state cur_state</code> ➡️ <code>struct bpf_verifier_state * cur_state</code>
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
<code>struct bpf_subprog_info[257] subprog_info</code>
</li>
<li>
<b>Field added. </b>
<code>u32 subprog_cnt</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct bpf_ext_analyzer_ops * dev_ops</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct bpf_verifer_log log</code> ➡️ <code>struct bpf_verifier_log log</code>
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
<code>u32 insn_idx</code>
</li>
<li>
<b>Field added. </b>
<code>u32 prev_insn_idx</code>
</li>
<li>
<b>Field added. </b>
<code>const struct bpf_line_info * prev_linfo</code>
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
<code>struct bpf_verifier_state_list * free_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) cfg</code>
</li>
<li>
<b>Field added. </b>
<code>u32 prev_insn_processed</code>
</li>
<li>
<b>Field added. </b>
<code>u32 insn_processed</code>
</li>
<li>
<b>Field added. </b>
<code>u32 prev_jmps_processed</code>
</li>
<li>
<b>Field added. </b>
<code>u32 jmps_processed</code>
</li>
<li>
<b>Field added. </b>
<code>u64 verification_time</code>
</li>
<li>
<b>Field added. </b>
<code>u32 max_states_per_insn</code>
</li>
<li>
<b>Field added. </b>
<code>u32 total_states</code>
</li>
<li>
<b>Field added. </b>
<code>u32 peak_states</code>
</li>
<li>
<b>Field added. </b>
<code>u32 longest_mark_read_walk</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool test_state_freq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool bpf_capable</code>
</li>
<li>
<b>Field added. </b>
<code>bool bypass_spec_v1</code>
</li>
<li>
<b>Field added. </b>
<code>bool bypass_spec_v4</code>
</li>
<li>
<b>Field added. </b>
<code>u32 pass_cnt</code>
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
<code>bool allow_ptr_to_map_access</code>
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
<code>struct btf_mod_pair[64] used_btfs</code>
</li>
<li>
<b>Field added. </b>
<code>u32 used_btf_cnt</code>
</li>
<li>
<b>Field added. </b>
<code>bool explore_alu_limits</code>
</li>
<li>
<b>Field added. </b>
<code>bool allow_uninit_stack</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_id_pair[75] idmap_scratch</code>
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
<code>bpfptr_t fd_array</code>
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
<code>u32 scratched_regs</code>
</li>
<li>
<b>Field added. </b>
<code>u64 scratched_stack_slots</code>
</li>
<li>
<b>Field added. </b>
<code>u32 prev_log_len</code>
</li>
<li>
<b>Field added. </b>
<code>u32 prev_insn_print_len</code>
</li>
<li>
<b>Field added. </b>
<code>char[64] type_str_buf</code>
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
<code>bool rcu_tag_supported</code>
</li>
<li>
<b>Field removed. </b>
<code>bool allow_ptr_to_map_access</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct bpf_id_pair[75] idmap_scratch</code> ➡️ <code>struct bpf_id_pair[600] idmap_scratch</code>
</li>
<li>
<b>Field type changed. </b>
<code>char[64] type_str_buf</code> ➡️ <code>char[128] type_str_buf</code>
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
<code>struct bpf_idset idset_scratch</code>
</li>
<li>
<b>Field added. </b>
<code>struct backtrack_state bt</code>
</li>
<li>
<b>Field added. </b>
<code>u64 prev_log_pos</code>
</li>
<li>
<b>Field added. </b>
<code>u64 prev_insn_print_pos</code>
</li>
<li>
<b>Field added. </b>
<code>char[320] tmp_str_buf</code>
</li>
<li>
<b>Field removed. </b>
<code>bool rcu_tag_supported</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 prev_log_len</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 prev_insn_print_len</code>
</li>
<li>
<b>Field removed. </b>
<code>char[128] type_str_buf</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct bpf_id_pair[600] idmap_scratch</code> ➡️ <code>struct bpf_idmap idmap_scratch</code>
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
<code>bool test_reg_invariants</code>
</li>
<li>
<b>Field added. </b>
<code>u32 hidden_subprog_cnt</code>
</li>
<li>
<b>Field added. </b>
<code>int exception_callback_subprog</code>
</li>
<li>
<b>Field added. </b>
<code>bool seen_exception</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_jmp_history_entry * cur_hist_ent</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct bpf_subprog_info[257] subprog_info</code> ➡️ <code>struct bpf_subprog_info[258] subprog_info</code>
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
