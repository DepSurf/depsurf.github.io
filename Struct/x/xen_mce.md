# Struct: <code>xen_mce</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
    __u64 synd;
    __u64 ipid;
    __u64 ppin;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
    __u64 synd;
    __u64 ipid;
    __u64 ppin;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
    __u64 synd;
    __u64 ipid;
    __u64 ppin;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
    __u64 synd;
    __u64 ipid;
    __u64 ppin;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
    __u64 synd;
    __u64 ipid;
    __u64 ppin;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
    __u64 synd;
    __u64 ipid;
    __u64 ppin;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
    __u64 synd;
    __u64 ipid;
    __u64 ppin;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
    __u64 synd;
    __u64 ipid;
    __u64 ppin;
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
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
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
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u64 synd</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 ipid</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 ppin</code>
</li>
</ul>
</details>
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
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
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
struct xen_mce {
    __u64 status;
    __u64 misc;
    __u64 addr;
    __u64 mcgstatus;
    __u64 ip;
    __u64 tsc;
    __u64 time;
    __u8 cpuvendor;
    __u8 inject_flags;
    __u16 pad;
    __u32 cpuid;
    __u8 cs;
    __u8 bank;
    __u8 cpu;
    __u8 finished;
    __u32 extcpu;
    __u32 socketid;
    __u32 apicid;
    __u64 mcgcap;
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
