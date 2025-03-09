# Struct: <code>sigcontext</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct sigcontext {
    __u64 fault_address;
    __u64[31] regs;
    __u64 sp;
    __u64 pc;
    __u64 pstate;
    __u8[4096] __reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sigcontext {
    long unsigned int trap_no;
    long unsigned int error_code;
    long unsigned int oldmask;
    long unsigned int arm_r0;
    long unsigned int arm_r1;
    long unsigned int arm_r2;
    long unsigned int arm_r3;
    long unsigned int arm_r4;
    long unsigned int arm_r5;
    long unsigned int arm_r6;
    long unsigned int arm_r7;
    long unsigned int arm_r8;
    long unsigned int arm_r9;
    long unsigned int arm_r10;
    long unsigned int arm_fp;
    long unsigned int arm_ip;
    long unsigned int arm_sp;
    long unsigned int arm_lr;
    long unsigned int arm_pc;
    long unsigned int arm_cpsr;
    long unsigned int fault_address;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sigcontext {
    long unsigned int[4] _unused;
    int signal;
    int _pad0;
    long unsigned int handler;
    long unsigned int oldmask;
    struct user_pt_regs * regs;
    elf_gregset_t gp_regs;
    elf_fpregset_t fp_regs;
    elf_vrreg_t * v_regs;
    long int[101] vmx_reserve;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sigcontext {
    struct user_regs_struct sc_regs;
    union __riscv_fp_state sc_fpregs;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct sigcontext {
    __u64 fault_address;
    __u64[31] regs;
    __u64 sp;
    __u64 pc;
    __u64 pstate;
    __u8[4096] __reserved;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct sigcontext {
    long unsigned int trap_no;
    long unsigned int error_code;
    long unsigned int oldmask;
    long unsigned int arm_r0;
    long unsigned int arm_r1;
    long unsigned int arm_r2;
    long unsigned int arm_r3;
    long unsigned int arm_r4;
    long unsigned int arm_r5;
    long unsigned int arm_r6;
    long unsigned int arm_r7;
    long unsigned int arm_r8;
    long unsigned int arm_r9;
    long unsigned int arm_r10;
    long unsigned int arm_fp;
    long unsigned int arm_ip;
    long unsigned int arm_sp;
    long unsigned int arm_lr;
    long unsigned int arm_pc;
    long unsigned int arm_cpsr;
    long unsigned int fault_address;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct sigcontext {
    long unsigned int[4] _unused;
    int signal;
    int _pad0;
    long unsigned int handler;
    long unsigned int oldmask;
    struct user_pt_regs * regs;
    elf_gregset_t gp_regs;
    elf_fpregset_t fp_regs;
    elf_vrreg_t * v_regs;
    long int[101] vmx_reserve;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct sigcontext {
    struct user_regs_struct sc_regs;
    union __riscv_fp_state sc_fpregs;
}
```
</details>
</li>
</ul>
