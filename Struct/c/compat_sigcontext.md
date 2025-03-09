# Struct: <code>compat_sigcontext</code>

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
struct compat_sigcontext {
    compat_ulong_t trap_no;
    compat_ulong_t error_code;
    compat_ulong_t oldmask;
    compat_ulong_t arm_r0;
    compat_ulong_t arm_r1;
    compat_ulong_t arm_r2;
    compat_ulong_t arm_r3;
    compat_ulong_t arm_r4;
    compat_ulong_t arm_r5;
    compat_ulong_t arm_r6;
    compat_ulong_t arm_r7;
    compat_ulong_t arm_r8;
    compat_ulong_t arm_r9;
    compat_ulong_t arm_r10;
    compat_ulong_t arm_fp;
    compat_ulong_t arm_ip;
    compat_ulong_t arm_sp;
    compat_ulong_t arm_lr;
    compat_ulong_t arm_pc;
    compat_ulong_t arm_cpsr;
    compat_ulong_t fault_address;
}
```
</details>
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
struct compat_sigcontext {
    compat_ulong_t trap_no;
    compat_ulong_t error_code;
    compat_ulong_t oldmask;
    compat_ulong_t arm_r0;
    compat_ulong_t arm_r1;
    compat_ulong_t arm_r2;
    compat_ulong_t arm_r3;
    compat_ulong_t arm_r4;
    compat_ulong_t arm_r5;
    compat_ulong_t arm_r6;
    compat_ulong_t arm_r7;
    compat_ulong_t arm_r8;
    compat_ulong_t arm_r9;
    compat_ulong_t arm_r10;
    compat_ulong_t arm_fp;
    compat_ulong_t arm_ip;
    compat_ulong_t arm_sp;
    compat_ulong_t arm_lr;
    compat_ulong_t arm_pc;
    compat_ulong_t arm_cpsr;
    compat_ulong_t fault_address;
}
```
</details>
</li>
</ul>
