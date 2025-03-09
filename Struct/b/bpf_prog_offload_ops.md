# Struct: <code>bpf_prog_offload_ops</code>

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
struct bpf_prog_offload_ops {
    int (*)(struct bpf_verifier_env *, int, int) insn_hook;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_offload_ops {
    int (*)(struct bpf_verifier_env *, int, int) insn_hook;
    int (*)(struct bpf_verifier_env *) finalize;
    int (*)(struct bpf_prog *) prepare;
    int (*)(struct bpf_prog *) translate;
    void (*)(struct bpf_prog *) destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_offload_ops {
    int (*)(struct bpf_verifier_env *, int, int) insn_hook;
    int (*)(struct bpf_verifier_env *) finalize;
    int (*)(struct bpf_verifier_env *, u32, struct bpf_insn *) replace_insn;
    int (*)(struct bpf_verifier_env *, u32, u32) remove_insns;
    int (*)(struct bpf_prog *) prepare;
    int (*)(struct bpf_prog *) translate;
    void (*)(struct bpf_prog *) destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_offload_ops {
    int (*)(struct bpf_verifier_env *, int, int) insn_hook;
    int (*)(struct bpf_verifier_env *) finalize;
    int (*)(struct bpf_verifier_env *, u32, struct bpf_insn *) replace_insn;
    int (*)(struct bpf_verifier_env *, u32, u32) remove_insns;
    int (*)(struct bpf_prog *) prepare;
    int (*)(struct bpf_prog *) translate;
    void (*)(struct bpf_prog *) destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_offload_ops {
    int (*)(struct bpf_verifier_env *, int, int) insn_hook;
    int (*)(struct bpf_verifier_env *) finalize;
    int (*)(struct bpf_verifier_env *, u32, struct bpf_insn *) replace_insn;
    int (*)(struct bpf_verifier_env *, u32, u32) remove_insns;
    int (*)(struct bpf_prog *) prepare;
    int (*)(struct bpf_prog *) translate;
    void (*)(struct bpf_prog *) destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_offload_ops {
    int (*)(struct bpf_verifier_env *, int, int) insn_hook;
    int (*)(struct bpf_verifier_env *) finalize;
    int (*)(struct bpf_verifier_env *, u32, struct bpf_insn *) replace_insn;
    int (*)(struct bpf_verifier_env *, u32, u32) remove_insns;
    int (*)(struct bpf_prog *) prepare;
    int (*)(struct bpf_prog *) translate;
    void (*)(struct bpf_prog *) destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_offload_ops {
    int (*)(struct bpf_verifier_env *, int, int) insn_hook;
    int (*)(struct bpf_verifier_env *) finalize;
    int (*)(struct bpf_verifier_env *, u32, struct bpf_insn *) replace_insn;
    int (*)(struct bpf_verifier_env *, u32, u32) remove_insns;
    int (*)(struct bpf_prog *) prepare;
    int (*)(struct bpf_prog *) translate;
    void (*)(struct bpf_prog *) destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_offload_ops {
    int (*)(struct bpf_verifier_env *, int, int) insn_hook;
    int (*)(struct bpf_verifier_env *) finalize;
    int (*)(struct bpf_verifier_env *, u32, struct bpf_insn *) replace_insn;
    int (*)(struct bpf_verifier_env *, u32, u32) remove_insns;
    int (*)(struct bpf_prog *) prepare;
    int (*)(struct bpf_prog *) translate;
    void (*)(struct bpf_prog *) destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_offload_ops {
    int (*)(struct bpf_verifier_env *, int, int) insn_hook;
    int (*)(struct bpf_verifier_env *) finalize;
    int (*)(struct bpf_verifier_env *, u32, struct bpf_insn *) replace_insn;
    int (*)(struct bpf_verifier_env *, u32, u32) remove_insns;
    int (*)(struct bpf_prog *) prepare;
    int (*)(struct bpf_prog *) translate;
    void (*)(struct bpf_prog *) destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_offload_ops {
    int (*)(struct bpf_verifier_env *, int, int) insn_hook;
    int (*)(struct bpf_verifier_env *) finalize;
    int (*)(struct bpf_verifier_env *, u32, struct bpf_insn *) replace_insn;
    int (*)(struct bpf_verifier_env *, u32, u32) remove_insns;
    int (*)(struct bpf_prog *) prepare;
    int (*)(struct bpf_prog *) translate;
    void (*)(struct bpf_prog *) destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_offload_ops {
    int (*)(struct bpf_verifier_env *, int, int) insn_hook;
    int (*)(struct bpf_verifier_env *) finalize;
    int (*)(struct bpf_verifier_env *, u32, struct bpf_insn *) replace_insn;
    int (*)(struct bpf_verifier_env *, u32, u32) remove_insns;
    int (*)(struct bpf_prog *) prepare;
    int (*)(struct bpf_prog *) translate;
    void (*)(struct bpf_prog *) destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog_offload_ops {
    int (*)(struct bpf_verifier_env *, int, int) insn_hook;
    int (*)(struct bpf_verifier_env *) finalize;
    int (*)(struct bpf_verifier_env *, u32, struct bpf_insn *) replace_insn;
    int (*)(struct bpf_verifier_env *, u32, u32) remove_insns;
    int (*)(struct bpf_prog *) prepare;
    int (*)(struct bpf_prog *) translate;
    void (*)(struct bpf_prog *) destroy;
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
struct bpf_prog_offload_ops {
    int (*)(struct bpf_verifier_env *, int, int) insn_hook;
    int (*)(struct bpf_verifier_env *) finalize;
    int (*)(struct bpf_verifier_env *, u32, struct bpf_insn *) replace_insn;
    int (*)(struct bpf_verifier_env *, u32, u32) remove_insns;
    int (*)(struct bpf_prog *) prepare;
    int (*)(struct bpf_prog *) translate;
    void (*)(struct bpf_prog *) destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bpf_prog_offload_ops {
    int (*)(struct bpf_verifier_env *, int, int) insn_hook;
    int (*)(struct bpf_verifier_env *) finalize;
    int (*)(struct bpf_verifier_env *, u32, struct bpf_insn *) replace_insn;
    int (*)(struct bpf_verifier_env *, u32, u32) remove_insns;
    int (*)(struct bpf_prog *) prepare;
    int (*)(struct bpf_prog *) translate;
    void (*)(struct bpf_prog *) destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bpf_prog_offload_ops {
    int (*)(struct bpf_verifier_env *, int, int) insn_hook;
    int (*)(struct bpf_verifier_env *) finalize;
    int (*)(struct bpf_verifier_env *, u32, struct bpf_insn *) replace_insn;
    int (*)(struct bpf_verifier_env *, u32, u32) remove_insns;
    int (*)(struct bpf_prog *) prepare;
    int (*)(struct bpf_prog *) translate;
    void (*)(struct bpf_prog *) destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bpf_prog_offload_ops {
    int (*)(struct bpf_verifier_env *, int, int) insn_hook;
    int (*)(struct bpf_verifier_env *) finalize;
    int (*)(struct bpf_verifier_env *, u32, struct bpf_insn *) replace_insn;
    int (*)(struct bpf_verifier_env *, u32, u32) remove_insns;
    int (*)(struct bpf_prog *) prepare;
    int (*)(struct bpf_prog *) translate;
    void (*)(struct bpf_prog *) destroy;
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
struct bpf_prog_offload_ops {
    int (*)(struct bpf_verifier_env *, int, int) insn_hook;
    int (*)(struct bpf_verifier_env *) finalize;
    int (*)(struct bpf_verifier_env *, u32, struct bpf_insn *) replace_insn;
    int (*)(struct bpf_verifier_env *, u32, u32) remove_insns;
    int (*)(struct bpf_prog *) prepare;
    int (*)(struct bpf_prog *) translate;
    void (*)(struct bpf_prog *) destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bpf_prog_offload_ops {
    int (*)(struct bpf_verifier_env *, int, int) insn_hook;
    int (*)(struct bpf_verifier_env *) finalize;
    int (*)(struct bpf_verifier_env *, u32, struct bpf_insn *) replace_insn;
    int (*)(struct bpf_verifier_env *, u32, u32) remove_insns;
    int (*)(struct bpf_prog *) prepare;
    int (*)(struct bpf_prog *) translate;
    void (*)(struct bpf_prog *) destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bpf_prog_offload_ops {
    int (*)(struct bpf_verifier_env *, int, int) insn_hook;
    int (*)(struct bpf_verifier_env *) finalize;
    int (*)(struct bpf_verifier_env *, u32, struct bpf_insn *) replace_insn;
    int (*)(struct bpf_verifier_env *, u32, u32) remove_insns;
    int (*)(struct bpf_prog *) prepare;
    int (*)(struct bpf_prog *) translate;
    void (*)(struct bpf_prog *) destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bpf_prog_offload_ops {
    int (*)(struct bpf_verifier_env *, int, int) insn_hook;
    int (*)(struct bpf_verifier_env *) finalize;
    int (*)(struct bpf_verifier_env *, u32, struct bpf_insn *) replace_insn;
    int (*)(struct bpf_verifier_env *, u32, u32) remove_insns;
    int (*)(struct bpf_prog *) prepare;
    int (*)(struct bpf_prog *) translate;
    void (*)(struct bpf_prog *) destroy;
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
struct bpf_prog_offload_ops {
    int (*)(struct bpf_verifier_env *, int, int) insn_hook;
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
<code>int (*)(struct bpf_verifier_env *) finalize</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct bpf_prog *) prepare</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct bpf_prog *) translate</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct bpf_prog *) destroy</code>
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
<code>int (*)(struct bpf_verifier_env *, u32, struct bpf_insn *) replace_insn</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct bpf_verifier_env *, u32, u32) remove_insns</code>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
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
