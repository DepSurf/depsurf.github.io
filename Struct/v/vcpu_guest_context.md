# Struct: <code>vcpu_guest_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct vcpu_guest_context {
    struct (anon) fpu_ctxt;
    long unsigned int flags;
    struct cpu_user_regs user_regs;
    struct trap_info[256] trap_ctxt;
    long unsigned int ldt_base;
    long unsigned int ldt_ents;
    long unsigned int[16] gdt_frames;
    long unsigned int gdt_ents;
    long unsigned int kernel_ss;
    long unsigned int kernel_sp;
    long unsigned int[8] ctrlreg;
    long unsigned int[8] debugreg;
    long unsigned int event_callback_eip;
    long unsigned int failsafe_callback_eip;
    long unsigned int syscall_callback_eip;
    long unsigned int vm_assist;
    uint64_t fs_base;
    uint64_t gs_base_kernel;
    uint64_t gs_base_user;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
