# Struct: <code>bpf_func_state</code>

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
struct bpf_func_state {
    struct bpf_reg_state[11] regs;
    struct bpf_verifier_state * parent;
    int callsite;
    u32 frameno;
    u32 subprogno;
    int allocated_stack;
    struct bpf_stack_state * stack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_state {
    struct bpf_reg_state[11] regs;
    int callsite;
    u32 frameno;
    u32 subprogno;
    int acquired_refs;
    struct bpf_reference_state * refs;
    int allocated_stack;
    struct bpf_stack_state * stack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_state {
    struct bpf_reg_state[11] regs;
    int callsite;
    u32 frameno;
    u32 subprogno;
    int acquired_refs;
    struct bpf_reference_state * refs;
    int allocated_stack;
    struct bpf_stack_state * stack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_state {
    struct bpf_reg_state[11] regs;
    int callsite;
    u32 frameno;
    u32 subprogno;
    int acquired_refs;
    struct bpf_reference_state * refs;
    int allocated_stack;
    struct bpf_stack_state * stack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_state {
    struct bpf_reg_state[11] regs;
    int callsite;
    u32 frameno;
    u32 subprogno;
    int acquired_refs;
    struct bpf_reference_state * refs;
    int allocated_stack;
    struct bpf_stack_state * stack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_state {
    struct bpf_reg_state[11] regs;
    int callsite;
    u32 frameno;
    u32 subprogno;
    int acquired_refs;
    struct bpf_reference_state * refs;
    int allocated_stack;
    struct bpf_stack_state * stack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_state {
    struct bpf_reg_state[11] regs;
    int callsite;
    u32 frameno;
    u32 subprogno;
    int acquired_refs;
    struct bpf_reference_state * refs;
    int allocated_stack;
    bool in_callback_fn;
    struct bpf_stack_state * stack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_state {
    struct bpf_reg_state[11] regs;
    int callsite;
    u32 frameno;
    u32 subprogno;
    u32 async_entry_cnt;
    bool in_callback_fn;
    bool in_async_callback_fn;
    int acquired_refs;
    struct bpf_reference_state * refs;
    int allocated_stack;
    struct bpf_stack_state * stack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_state {
    struct bpf_reg_state[11] regs;
    int callsite;
    u32 frameno;
    u32 subprogno;
    u32 async_entry_cnt;
    bool in_callback_fn;
    bool in_async_callback_fn;
    int acquired_refs;
    struct bpf_reference_state * refs;
    int allocated_stack;
    struct bpf_stack_state * stack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_state {
    struct bpf_reg_state[11] regs;
    int callsite;
    u32 frameno;
    u32 subprogno;
    u32 async_entry_cnt;
    bool in_callback_fn;
    struct tnum callback_ret_range;
    bool in_async_callback_fn;
    int acquired_refs;
    struct bpf_reference_state * refs;
    int allocated_stack;
    struct bpf_stack_state * stack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_state {
    struct bpf_reg_state[11] regs;
    int callsite;
    u32 frameno;
    u32 subprogno;
    u32 async_entry_cnt;
    bool in_callback_fn;
    struct tnum callback_ret_range;
    bool in_async_callback_fn;
    int acquired_refs;
    struct bpf_reference_state * refs;
    int allocated_stack;
    struct bpf_stack_state * stack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_state {
    struct bpf_reg_state[11] regs;
    int callsite;
    u32 frameno;
    u32 subprogno;
    u32 async_entry_cnt;
    struct bpf_retval_range callback_ret_range;
    bool in_callback_fn;
    bool in_async_callback_fn;
    bool in_exception_callback_fn;
    u32 callback_depth;
    int acquired_refs;
    struct bpf_reference_state * refs;
    struct bpf_stack_state * stack;
    int allocated_stack;
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
struct bpf_func_state {
    struct bpf_reg_state[11] regs;
    int callsite;
    u32 frameno;
    u32 subprogno;
    int acquired_refs;
    struct bpf_reference_state * refs;
    int allocated_stack;
    struct bpf_stack_state * stack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bpf_func_state {
    struct bpf_reg_state[11] regs;
    int callsite;
    u32 frameno;
    u32 subprogno;
    int acquired_refs;
    struct bpf_reference_state * refs;
    int allocated_stack;
    struct bpf_stack_state * stack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bpf_func_state {
    struct bpf_reg_state[11] regs;
    int callsite;
    u32 frameno;
    u32 subprogno;
    int acquired_refs;
    struct bpf_reference_state * refs;
    int allocated_stack;
    struct bpf_stack_state * stack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bpf_func_state {
    struct bpf_reg_state[11] regs;
    int callsite;
    u32 frameno;
    u32 subprogno;
    int acquired_refs;
    struct bpf_reference_state * refs;
    int allocated_stack;
    struct bpf_stack_state * stack;
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
struct bpf_func_state {
    struct bpf_reg_state[11] regs;
    int callsite;
    u32 frameno;
    u32 subprogno;
    int acquired_refs;
    struct bpf_reference_state * refs;
    int allocated_stack;
    struct bpf_stack_state * stack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bpf_func_state {
    struct bpf_reg_state[11] regs;
    int callsite;
    u32 frameno;
    u32 subprogno;
    int acquired_refs;
    struct bpf_reference_state * refs;
    int allocated_stack;
    struct bpf_stack_state * stack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bpf_func_state {
    struct bpf_reg_state[11] regs;
    int callsite;
    u32 frameno;
    u32 subprogno;
    int acquired_refs;
    struct bpf_reference_state * refs;
    int allocated_stack;
    struct bpf_stack_state * stack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bpf_func_state {
    struct bpf_reg_state[11] regs;
    int callsite;
    u32 frameno;
    u32 subprogno;
    int acquired_refs;
    struct bpf_reference_state * refs;
    int allocated_stack;
    struct bpf_stack_state * stack;
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
struct bpf_func_state {
    struct bpf_reg_state[11] regs;
    struct bpf_verifier_state * parent;
    int callsite;
    u32 frameno;
    u32 subprogno;
    int allocated_stack;
    struct bpf_stack_state * stack;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int acquired_refs</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_reference_state * refs</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bpf_verifier_state * parent</code>
</li>
</ul>
</details>
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
<code>bool in_callback_fn</code>
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
<code>u32 async_entry_cnt</code>
</li>
<li>
<b>Field added. </b>
<code>bool in_async_callback_fn</code>
</li>
</ul>
</details>
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
<code>struct tnum callback_ret_range</code>
</li>
</ul>
</details>
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
<code>bool in_exception_callback_fn</code>
</li>
<li>
<b>Field added. </b>
<code>u32 callback_depth</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct tnum callback_ret_range</code> ➡️ <code>struct bpf_retval_range callback_ret_range</code>
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
