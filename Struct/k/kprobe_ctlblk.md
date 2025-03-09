# Struct: <code>kprobe_ctlblk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_old_flags;
    long unsigned int kprobe_saved_flags;
    long unsigned int * jprobe_saved_sp;
    struct pt_regs jprobe_saved_regs;
    kprobe_opcode_t[64] jprobes_stack;
    struct prev_kprobe prev_kprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_old_flags;
    long unsigned int kprobe_saved_flags;
    long unsigned int * jprobe_saved_sp;
    struct pt_regs jprobe_saved_regs;
    kprobe_opcode_t[64] jprobes_stack;
    struct prev_kprobe prev_kprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_old_flags;
    long unsigned int kprobe_saved_flags;
    long unsigned int * jprobe_saved_sp;
    struct pt_regs jprobe_saved_regs;
    kprobe_opcode_t[64] jprobes_stack;
    struct prev_kprobe prev_kprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_old_flags;
    long unsigned int kprobe_saved_flags;
    long unsigned int * jprobe_saved_sp;
    struct pt_regs jprobe_saved_regs;
    kprobe_opcode_t[64] jprobes_stack;
    struct prev_kprobe prev_kprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_old_flags;
    long unsigned int kprobe_saved_flags;
    long unsigned int * jprobe_saved_sp;
    struct pt_regs jprobe_saved_regs;
    kprobe_opcode_t[64] jprobes_stack;
    struct prev_kprobe prev_kprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_old_flags;
    long unsigned int kprobe_saved_flags;
    long unsigned int * jprobe_saved_sp;
    struct pt_regs jprobe_saved_regs;
    kprobe_opcode_t[64] jprobes_stack;
    struct prev_kprobe prev_kprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_old_flags;
    long unsigned int kprobe_saved_flags;
    struct prev_kprobe prev_kprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_old_flags;
    long unsigned int kprobe_saved_flags;
    struct prev_kprobe prev_kprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_old_flags;
    long unsigned int kprobe_saved_flags;
    struct prev_kprobe prev_kprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_old_flags;
    long unsigned int kprobe_saved_flags;
    struct prev_kprobe prev_kprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_old_flags;
    long unsigned int kprobe_saved_flags;
    struct prev_kprobe prev_kprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_old_flags;
    long unsigned int kprobe_saved_flags;
    struct prev_kprobe prev_kprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_old_flags;
    long unsigned int kprobe_saved_flags;
    struct prev_kprobe prev_kprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_old_flags;
    long unsigned int kprobe_saved_flags;
    struct prev_kprobe prev_kprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_old_flags;
    long unsigned int kprobe_saved_flags;
    struct prev_kprobe prev_kprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_old_flags;
    long unsigned int kprobe_saved_flags;
    struct prev_kprobe prev_kprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_old_flags;
    long unsigned int kprobe_saved_flags;
    struct prev_kprobe prev_kprobe;
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
struct kprobe_ctlblk {
    unsigned int kprobe_status;
    long unsigned int saved_irqflag;
    struct prev_kprobe prev_kprobe;
    struct kprobe_step_ctx ss_ctx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    unsigned int kprobe_status;
    struct prev_kprobe prev_kprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_saved_msr;
    struct prev_kprobe prev_kprobe;
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_old_flags;
    long unsigned int kprobe_saved_flags;
    struct prev_kprobe prev_kprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_old_flags;
    long unsigned int kprobe_saved_flags;
    struct prev_kprobe prev_kprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_old_flags;
    long unsigned int kprobe_saved_flags;
    struct prev_kprobe prev_kprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_old_flags;
    long unsigned int kprobe_saved_flags;
    struct prev_kprobe prev_kprobe;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long unsigned int * jprobe_saved_sp</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pt_regs jprobe_saved_regs</code>
</li>
<li>
<b>Field removed. </b>
<code>kprobe_opcode_t[64] jprobes_stack</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int saved_irqflag</code>
</li>
<li>
<b>Field added. </b>
<code>struct kprobe_step_ctx ss_ctx</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int kprobe_old_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int kprobe_saved_flags</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int kprobe_status</code> ➡️ <code>unsigned int kprobe_status</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long unsigned int kprobe_old_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int kprobe_saved_flags</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int kprobe_status</code> ➡️ <code>unsigned int kprobe_status</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int kprobe_saved_msr</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int kprobe_old_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int kprobe_saved_flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct kprobe_ctlblk {
    long unsigned int kprobe_status;
    long unsigned int kprobe_old_flags;
    long unsigned int kprobe_saved_flags;
    struct prev_kprobe prev_kprobe;
}
```
</details>
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
