# Struct: <code>bpf_verifier_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id) get_func_proto;
    bool (*)(int, int, enum bpf_access_type) is_valid_access;
    u32 (*)(enum bpf_access_type, int, int, int, struct bpf_insn *, struct bpf_prog *) convert_ctx_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, enum bpf_reg_type *) is_valid_access;
    u32 (*)(enum bpf_access_type, int, int, int, struct bpf_insn *, struct bpf_prog *) convert_ctx_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, enum bpf_reg_type *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    u32 (*)(enum bpf_access_type, int, int, int, struct bpf_insn *, struct bpf_prog *) convert_ctx_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, struct bpf_insn_access_aux *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access;
    int (*)(struct bpf_prog *, const union bpf_attr *, union bpf_attr *) test_run;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, struct bpf_insn_access_aux *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id, const struct bpf_prog *) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, const struct bpf_prog *, struct bpf_insn_access_aux *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    int (*)(const struct bpf_insn *, struct bpf_insn *) gen_ld_abs;
    u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id, const struct bpf_prog *) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, const struct bpf_prog *, struct bpf_insn_access_aux *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    int (*)(const struct bpf_insn *, struct bpf_insn *) gen_ld_abs;
    u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id, const struct bpf_prog *) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, const struct bpf_prog *, struct bpf_insn_access_aux *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    int (*)(const struct bpf_insn *, struct bpf_insn *) gen_ld_abs;
    u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id, const struct bpf_prog *) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, const struct bpf_prog *, struct bpf_insn_access_aux *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    int (*)(const struct bpf_insn *, struct bpf_insn *) gen_ld_abs;
    u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id, const struct bpf_prog *) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, const struct bpf_prog *, struct bpf_insn_access_aux *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    int (*)(const struct bpf_insn *, struct bpf_insn *) gen_ld_abs;
    u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access;
    int (*)(struct bpf_verifier_log *, const struct btf_type *, int, int, enum bpf_access_type, u32 *) btf_struct_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id, const struct bpf_prog *) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, const struct bpf_prog *, struct bpf_insn_access_aux *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    int (*)(const struct bpf_insn *, struct bpf_insn *) gen_ld_abs;
    u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access;
    int (*)(struct bpf_verifier_log *, const struct btf *, const struct btf_type *, int, int, enum bpf_access_type, u32 *) btf_struct_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id, const struct bpf_prog *) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, const struct bpf_prog *, struct bpf_insn_access_aux *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    int (*)(const struct bpf_insn *, struct bpf_insn *) gen_ld_abs;
    u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access;
    int (*)(struct bpf_verifier_log *, const struct btf *, const struct btf_type *, int, int, enum bpf_access_type, u32 *) btf_struct_access;
    bool (*)(u32) check_kfunc_call;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id, const struct bpf_prog *) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, const struct bpf_prog *, struct bpf_insn_access_aux *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    int (*)(const struct bpf_insn *, struct bpf_insn *) gen_ld_abs;
    u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access;
    int (*)(struct bpf_verifier_log *, const struct btf *, const struct btf_type *, int, int, enum bpf_access_type, u32 *) btf_struct_access;
    bool (*)(u32) check_kfunc_call;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id, const struct bpf_prog *) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, const struct bpf_prog *, struct bpf_insn_access_aux *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    int (*)(const struct bpf_insn *, struct bpf_insn *) gen_ld_abs;
    u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access;
    int (*)(struct bpf_verifier_log *, const struct btf *, const struct btf_type *, int, int, enum bpf_access_type, u32 *, enum bpf_type_flag *) btf_struct_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id, const struct bpf_prog *) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, const struct bpf_prog *, struct bpf_insn_access_aux *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    int (*)(const struct bpf_insn *, struct bpf_insn *) gen_ld_abs;
    u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access;
    int (*)(struct bpf_verifier_log *, const struct bpf_reg_state *, int, int, enum bpf_access_type, u32 *, enum bpf_type_flag *) btf_struct_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id, const struct bpf_prog *) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, const struct bpf_prog *, struct bpf_insn_access_aux *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    int (*)(const struct bpf_insn *, struct bpf_insn *) gen_ld_abs;
    u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access;
    int (*)(struct bpf_verifier_log *, const struct bpf_reg_state *, int, int) btf_struct_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id, const struct bpf_prog *) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, const struct bpf_prog *, struct bpf_insn_access_aux *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    int (*)(const struct bpf_insn *, struct bpf_insn *) gen_ld_abs;
    u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access;
    int (*)(struct bpf_verifier_log *, const struct bpf_reg_state *, int, int) btf_struct_access;
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
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id, const struct bpf_prog *) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, const struct bpf_prog *, struct bpf_insn_access_aux *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    int (*)(const struct bpf_insn *, struct bpf_insn *) gen_ld_abs;
    u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id, const struct bpf_prog *) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, const struct bpf_prog *, struct bpf_insn_access_aux *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    int (*)(const struct bpf_insn *, struct bpf_insn *) gen_ld_abs;
    u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id, const struct bpf_prog *) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, const struct bpf_prog *, struct bpf_insn_access_aux *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    int (*)(const struct bpf_insn *, struct bpf_insn *) gen_ld_abs;
    u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id, const struct bpf_prog *) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, const struct bpf_prog *, struct bpf_insn_access_aux *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    int (*)(const struct bpf_insn *, struct bpf_insn *) gen_ld_abs;
    u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access;
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
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id, const struct bpf_prog *) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, const struct bpf_prog *, struct bpf_insn_access_aux *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    int (*)(const struct bpf_insn *, struct bpf_insn *) gen_ld_abs;
    u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id, const struct bpf_prog *) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, const struct bpf_prog *, struct bpf_insn_access_aux *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    int (*)(const struct bpf_insn *, struct bpf_insn *) gen_ld_abs;
    u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id, const struct bpf_prog *) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, const struct bpf_prog *, struct bpf_insn_access_aux *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    int (*)(const struct bpf_insn *, struct bpf_insn *) gen_ld_abs;
    u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bpf_verifier_ops {
    const struct bpf_func_proto * (*)(enum bpf_func_id, const struct bpf_prog *) get_func_proto;
    bool (*)(int, int, enum bpf_access_type, const struct bpf_prog *, struct bpf_insn_access_aux *) is_valid_access;
    int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue;
    int (*)(const struct bpf_insn *, struct bpf_insn *) gen_ld_abs;
    u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access;
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
<b>Field type changed. </b>
<code>bool (*)(int, int, enum bpf_access_type) is_valid_access</code> ➡️ <code>bool (*)(int, int, enum bpf_access_type, enum bpf_reg_type *) is_valid_access</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct bpf_insn *, bool, const struct bpf_prog *) gen_prologue</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct bpf_prog *, const union bpf_attr *, union bpf_attr *) test_run</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool (*)(int, int, enum bpf_access_type, enum bpf_reg_type *) is_valid_access</code> ➡️ <code>bool (*)(int, int, enum bpf_access_type, struct bpf_insn_access_aux *) is_valid_access</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 (*)(enum bpf_access_type, int, int, int, struct bpf_insn *, struct bpf_prog *) convert_ctx_access</code> ➡️ <code>u32 (*)(enum bpf_access_type, const struct bpf_insn *, struct bpf_insn *, struct bpf_prog *, u32 *) convert_ctx_access</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct bpf_prog *, const union bpf_attr *, union bpf_attr *) test_run</code>
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
<code>int (*)(const struct bpf_insn *, struct bpf_insn *) gen_ld_abs</code>
</li>
<li>
<b>Field type changed. </b>
<code>const struct bpf_func_proto * (*)(enum bpf_func_id) get_func_proto</code> ➡️ <code>const struct bpf_func_proto * (*)(enum bpf_func_id, const struct bpf_prog *) get_func_proto</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool (*)(int, int, enum bpf_access_type, struct bpf_insn_access_aux *) is_valid_access</code> ➡️ <code>bool (*)(int, int, enum bpf_access_type, const struct bpf_prog *, struct bpf_insn_access_aux *) is_valid_access</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct bpf_verifier_log *, const struct btf_type *, int, int, enum bpf_access_type, u32 *) btf_struct_access</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct bpf_verifier_log *, const struct btf_type *, int, int, enum bpf_access_type, u32 *) btf_struct_access</code> ➡️ <code>int (*)(struct bpf_verifier_log *, const struct btf *, const struct btf_type *, int, int, enum bpf_access_type, u32 *) btf_struct_access</code>
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
<code>bool (*)(u32) check_kfunc_call</code>
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
<b>Field removed. </b>
<code>bool (*)(u32) check_kfunc_call</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct bpf_verifier_log *, const struct btf *, const struct btf_type *, int, int, enum bpf_access_type, u32 *) btf_struct_access</code> ➡️ <code>int (*)(struct bpf_verifier_log *, const struct btf *, const struct btf_type *, int, int, enum bpf_access_type, u32 *, enum bpf_type_flag *) btf_struct_access</code>
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
<code>int (*)(struct bpf_verifier_log *, const struct btf *, const struct btf_type *, int, int, enum bpf_access_type, u32 *, enum bpf_type_flag *) btf_struct_access</code> ➡️ <code>int (*)(struct bpf_verifier_log *, const struct bpf_reg_state *, int, int, enum bpf_access_type, u32 *, enum bpf_type_flag *) btf_struct_access</code>
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
<code>int (*)(struct bpf_verifier_log *, const struct bpf_reg_state *, int, int, enum bpf_access_type, u32 *, enum bpf_type_flag *) btf_struct_access</code> ➡️ <code>int (*)(struct bpf_verifier_log *, const struct bpf_reg_state *, int, int) btf_struct_access</code>
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
