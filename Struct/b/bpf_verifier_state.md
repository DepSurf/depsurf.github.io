# Struct: <code>bpf_verifier_state</code>

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
struct bpf_verifier_state {
    struct bpf_reg_state[11] regs;
    u8[512] stack_slot_type;
    struct bpf_reg_state[64] spilled_regs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_state {
    struct bpf_reg_state[11] regs;
    u8[512] stack_slot_type;
    struct bpf_reg_state[64] spilled_regs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_state {
    struct bpf_reg_state[11] regs;
    struct bpf_verifier_state * parent;
    int allocated_stack;
    struct bpf_stack_state * stack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_state {
    struct bpf_func_state *[8] frame;
    struct bpf_verifier_state * parent;
    u32 curframe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_state {
    struct bpf_func_state *[8] frame;
    u32 curframe;
    bool speculative;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_state {
    struct bpf_func_state *[8] frame;
    struct bpf_verifier_state * parent;
    u32 branches;
    u32 insn_idx;
    u32 curframe;
    u32 active_spin_lock;
    bool speculative;
    u32 first_insn_idx;
    u32 last_insn_idx;
    struct bpf_idx_pair * jmp_history;
    u32 jmp_history_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_state {
    struct bpf_func_state *[8] frame;
    struct bpf_verifier_state * parent;
    u32 branches;
    u32 insn_idx;
    u32 curframe;
    u32 active_spin_lock;
    bool speculative;
    u32 first_insn_idx;
    u32 last_insn_idx;
    struct bpf_idx_pair * jmp_history;
    u32 jmp_history_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_state {
    struct bpf_func_state *[8] frame;
    struct bpf_verifier_state * parent;
    u32 branches;
    u32 insn_idx;
    u32 curframe;
    u32 active_spin_lock;
    bool speculative;
    u32 first_insn_idx;
    u32 last_insn_idx;
    struct bpf_idx_pair * jmp_history;
    u32 jmp_history_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_state {
    struct bpf_func_state *[8] frame;
    struct bpf_verifier_state * parent;
    u32 branches;
    u32 insn_idx;
    u32 curframe;
    u32 active_spin_lock;
    bool speculative;
    u32 first_insn_idx;
    u32 last_insn_idx;
    struct bpf_idx_pair * jmp_history;
    u32 jmp_history_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_state {
    struct bpf_func_state *[8] frame;
    struct bpf_verifier_state * parent;
    u32 branches;
    u32 insn_idx;
    u32 curframe;
    u32 active_spin_lock;
    bool speculative;
    u32 first_insn_idx;
    u32 last_insn_idx;
    struct bpf_idx_pair * jmp_history;
    u32 jmp_history_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_state {
    struct bpf_func_state *[8] frame;
    struct bpf_verifier_state * parent;
    u32 branches;
    u32 insn_idx;
    u32 curframe;
    u32 active_spin_lock;
    bool speculative;
    u32 first_insn_idx;
    u32 last_insn_idx;
    struct bpf_idx_pair * jmp_history;
    u32 jmp_history_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_state {
    struct bpf_func_state *[8] frame;
    struct bpf_verifier_state * parent;
    u32 branches;
    u32 insn_idx;
    u32 curframe;
    u32 active_spin_lock;
    bool speculative;
    u32 first_insn_idx;
    u32 last_insn_idx;
    struct bpf_idx_pair * jmp_history;
    u32 jmp_history_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_state {
    struct bpf_func_state *[8] frame;
    struct bpf_verifier_state * parent;
    u32 branches;
    u32 insn_idx;
    u32 curframe;
    struct (anon) active_lock;
    bool speculative;
    bool active_rcu_lock;
    u32 first_insn_idx;
    u32 last_insn_idx;
    struct bpf_idx_pair * jmp_history;
    u32 jmp_history_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_state {
    struct bpf_func_state *[8] frame;
    struct bpf_verifier_state * parent;
    u32 branches;
    u32 insn_idx;
    u32 curframe;
    struct bpf_active_lock active_lock;
    bool speculative;
    bool active_rcu_lock;
    u32 first_insn_idx;
    u32 last_insn_idx;
    struct bpf_idx_pair * jmp_history;
    u32 jmp_history_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_state {
    struct bpf_func_state *[8] frame;
    struct bpf_verifier_state * parent;
    u32 branches;
    u32 insn_idx;
    u32 curframe;
    struct bpf_active_lock active_lock;
    bool speculative;
    bool active_rcu_lock;
    bool used_as_loop_entry;
    u32 first_insn_idx;
    u32 last_insn_idx;
    struct bpf_verifier_state * loop_entry;
    struct bpf_jmp_history_entry * jmp_history;
    u32 jmp_history_cnt;
    u32 dfs_depth;
    u32 callback_unroll_depth;
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
struct bpf_verifier_state {
    struct bpf_func_state *[8] frame;
    struct bpf_verifier_state * parent;
    u32 branches;
    u32 insn_idx;
    u32 curframe;
    u32 active_spin_lock;
    bool speculative;
    u32 first_insn_idx;
    u32 last_insn_idx;
    struct bpf_idx_pair * jmp_history;
    u32 jmp_history_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bpf_verifier_state {
    struct bpf_func_state *[8] frame;
    struct bpf_verifier_state * parent;
    u32 branches;
    u32 insn_idx;
    u32 curframe;
    u32 active_spin_lock;
    bool speculative;
    u32 first_insn_idx;
    u32 last_insn_idx;
    struct bpf_idx_pair * jmp_history;
    u32 jmp_history_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bpf_verifier_state {
    struct bpf_func_state *[8] frame;
    struct bpf_verifier_state * parent;
    u32 branches;
    u32 insn_idx;
    u32 curframe;
    u32 active_spin_lock;
    bool speculative;
    u32 first_insn_idx;
    u32 last_insn_idx;
    struct bpf_idx_pair * jmp_history;
    u32 jmp_history_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bpf_verifier_state {
    struct bpf_func_state *[8] frame;
    struct bpf_verifier_state * parent;
    u32 branches;
    u32 insn_idx;
    u32 curframe;
    u32 active_spin_lock;
    bool speculative;
    u32 first_insn_idx;
    u32 last_insn_idx;
    struct bpf_idx_pair * jmp_history;
    u32 jmp_history_cnt;
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
struct bpf_verifier_state {
    struct bpf_func_state *[8] frame;
    struct bpf_verifier_state * parent;
    u32 branches;
    u32 insn_idx;
    u32 curframe;
    u32 active_spin_lock;
    bool speculative;
    u32 first_insn_idx;
    u32 last_insn_idx;
    struct bpf_idx_pair * jmp_history;
    u32 jmp_history_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bpf_verifier_state {
    struct bpf_func_state *[8] frame;
    struct bpf_verifier_state * parent;
    u32 branches;
    u32 insn_idx;
    u32 curframe;
    u32 active_spin_lock;
    bool speculative;
    u32 first_insn_idx;
    u32 last_insn_idx;
    struct bpf_idx_pair * jmp_history;
    u32 jmp_history_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bpf_verifier_state {
    struct bpf_func_state *[8] frame;
    struct bpf_verifier_state * parent;
    u32 branches;
    u32 insn_idx;
    u32 curframe;
    u32 active_spin_lock;
    bool speculative;
    u32 first_insn_idx;
    u32 last_insn_idx;
    struct bpf_idx_pair * jmp_history;
    u32 jmp_history_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bpf_verifier_state {
    struct bpf_func_state *[8] frame;
    struct bpf_verifier_state * parent;
    u32 branches;
    u32 insn_idx;
    u32 curframe;
    u32 active_spin_lock;
    bool speculative;
    u32 first_insn_idx;
    u32 last_insn_idx;
    struct bpf_idx_pair * jmp_history;
    u32 jmp_history_cnt;
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
struct bpf_verifier_state {
    struct bpf_reg_state[11] regs;
    u8[512] stack_slot_type;
    struct bpf_reg_state[64] spilled_regs;
}
```
</details>
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
<code>struct bpf_verifier_state * parent</code>
</li>
<li>
<b>Field added. </b>
<code>int allocated_stack</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_stack_state * stack</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[512] stack_slot_type</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bpf_reg_state[64] spilled_regs</code>
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
<code>struct bpf_func_state *[8] frame</code>
</li>
<li>
<b>Field added. </b>
<code>u32 curframe</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bpf_reg_state[11] regs</code>
</li>
<li>
<b>Field removed. </b>
<code>int allocated_stack</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bpf_stack_state * stack</code>
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
<code>bool speculative</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bpf_verifier_state * parent</code>
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
<code>struct bpf_verifier_state * parent</code>
</li>
<li>
<b>Field added. </b>
<code>u32 branches</code>
</li>
<li>
<b>Field added. </b>
<code>u32 insn_idx</code>
</li>
<li>
<b>Field added. </b>
<code>u32 active_spin_lock</code>
</li>
<li>
<b>Field added. </b>
<code>u32 first_insn_idx</code>
</li>
<li>
<b>Field added. </b>
<code>u32 last_insn_idx</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_idx_pair * jmp_history</code>
</li>
<li>
<b>Field added. </b>
<code>u32 jmp_history_cnt</code>
</li>
</ul>
</details>
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
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
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
<code>struct (anon) active_lock</code>
</li>
<li>
<b>Field added. </b>
<code>bool active_rcu_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 active_spin_lock</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct (anon) active_lock</code> ➡️ <code>struct bpf_active_lock active_lock</code>
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
<code>bool used_as_loop_entry</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_verifier_state * loop_entry</code>
</li>
<li>
<b>Field added. </b>
<code>u32 dfs_depth</code>
</li>
<li>
<b>Field added. </b>
<code>u32 callback_unroll_depth</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct bpf_idx_pair * jmp_history</code> ➡️ <code>struct bpf_jmp_history_entry * jmp_history</code>
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
