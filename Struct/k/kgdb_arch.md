# Struct: <code>kgdb_arch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct kgdb_arch {
    unsigned char[1] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct kgdb_arch {
    unsigned char[1] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct kgdb_arch {
    unsigned char[1] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct kgdb_arch {
    unsigned char[1] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct kgdb_arch {
    unsigned char[1] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct kgdb_arch {
    unsigned char[1] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct kgdb_arch {
    unsigned char[1] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct kgdb_arch {
    unsigned char[1] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct kgdb_arch {
    unsigned char[1] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct kgdb_arch {
    unsigned char[1] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct kgdb_arch {
    unsigned char[1] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kgdb_arch {
    unsigned char[1] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kgdb_arch {
    unsigned char[1] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kgdb_arch {
    unsigned char[1] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kgdb_arch {
    unsigned char[1] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kgdb_arch {
    unsigned char[1] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kgdb_arch {
    unsigned char[1] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
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
struct kgdb_arch {
    unsigned char[4] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct kgdb_arch {
    unsigned char[4] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct kgdb_arch {
    unsigned char[4] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
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
struct kgdb_arch {
    unsigned char[1] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct kgdb_arch {
    unsigned char[1] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct kgdb_arch {
    unsigned char[1] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct kgdb_arch {
    unsigned char[1] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
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
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
<b>Field type changed. </b>
<code>unsigned char[1] gdb_bpt_instr</code> ➡️ <code>unsigned char[4] gdb_bpt_instr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>unsigned char[1] gdb_bpt_instr</code> ➡️ <code>unsigned char[4] gdb_bpt_instr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>unsigned char[1] gdb_bpt_instr</code> ➡️ <code>unsigned char[4] gdb_bpt_instr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct kgdb_arch {
    unsigned char[1] gdb_bpt_instr;
    long unsigned int flags;
    int (*)(long unsigned int, char *) set_breakpoint;
    int (*)(long unsigned int, char *) remove_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) set_hw_breakpoint;
    int (*)(long unsigned int, int, enum kgdb_bptype) remove_hw_breakpoint;
    void (*)(struct pt_regs *) disable_hw_break;
    void (*)() remove_all_hw_break;
    void (*)() correct_hw_break;
    void (*)(bool) enable_nmi;
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
