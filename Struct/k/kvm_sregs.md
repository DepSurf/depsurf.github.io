# Struct: <code>kvm_sregs</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct kvm_sregs {
    struct kvm_segment cs;
    struct kvm_segment ds;
    struct kvm_segment es;
    struct kvm_segment fs;
    struct kvm_segment gs;
    struct kvm_segment ss;
    struct kvm_segment tr;
    struct kvm_segment ldt;
    struct kvm_dtable gdt;
    struct kvm_dtable idt;
    __u64 cr0;
    __u64 cr2;
    __u64 cr3;
    __u64 cr4;
    __u64 cr8;
    __u64 efer;
    __u64 apic_base;
    __u64[4] interrupt_bitmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kvm_sregs {
    struct kvm_segment cs;
    struct kvm_segment ds;
    struct kvm_segment es;
    struct kvm_segment fs;
    struct kvm_segment gs;
    struct kvm_segment ss;
    struct kvm_segment tr;
    struct kvm_segment ldt;
    struct kvm_dtable gdt;
    struct kvm_dtable idt;
    __u64 cr0;
    __u64 cr2;
    __u64 cr3;
    __u64 cr4;
    __u64 cr8;
    __u64 efer;
    __u64 apic_base;
    __u64[4] interrupt_bitmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kvm_sregs {
    struct kvm_segment cs;
    struct kvm_segment ds;
    struct kvm_segment es;
    struct kvm_segment fs;
    struct kvm_segment gs;
    struct kvm_segment ss;
    struct kvm_segment tr;
    struct kvm_segment ldt;
    struct kvm_dtable gdt;
    struct kvm_dtable idt;
    __u64 cr0;
    __u64 cr2;
    __u64 cr3;
    __u64 cr4;
    __u64 cr8;
    __u64 efer;
    __u64 apic_base;
    __u64[4] interrupt_bitmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kvm_sregs {
    struct kvm_segment cs;
    struct kvm_segment ds;
    struct kvm_segment es;
    struct kvm_segment fs;
    struct kvm_segment gs;
    struct kvm_segment ss;
    struct kvm_segment tr;
    struct kvm_segment ldt;
    struct kvm_dtable gdt;
    struct kvm_dtable idt;
    __u64 cr0;
    __u64 cr2;
    __u64 cr3;
    __u64 cr4;
    __u64 cr8;
    __u64 efer;
    __u64 apic_base;
    __u64[4] interrupt_bitmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kvm_sregs {
    struct kvm_segment cs;
    struct kvm_segment ds;
    struct kvm_segment es;
    struct kvm_segment fs;
    struct kvm_segment gs;
    struct kvm_segment ss;
    struct kvm_segment tr;
    struct kvm_segment ldt;
    struct kvm_dtable gdt;
    struct kvm_dtable idt;
    __u64 cr0;
    __u64 cr2;
    __u64 cr3;
    __u64 cr4;
    __u64 cr8;
    __u64 efer;
    __u64 apic_base;
    __u64[4] interrupt_bitmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kvm_sregs {
    struct kvm_segment cs;
    struct kvm_segment ds;
    struct kvm_segment es;
    struct kvm_segment fs;
    struct kvm_segment gs;
    struct kvm_segment ss;
    struct kvm_segment tr;
    struct kvm_segment ldt;
    struct kvm_dtable gdt;
    struct kvm_dtable idt;
    __u64 cr0;
    __u64 cr2;
    __u64 cr3;
    __u64 cr4;
    __u64 cr8;
    __u64 efer;
    __u64 apic_base;
    __u64[4] interrupt_bitmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kvm_sregs {
    struct kvm_segment cs;
    struct kvm_segment ds;
    struct kvm_segment es;
    struct kvm_segment fs;
    struct kvm_segment gs;
    struct kvm_segment ss;
    struct kvm_segment tr;
    struct kvm_segment ldt;
    struct kvm_dtable gdt;
    struct kvm_dtable idt;
    __u64 cr0;
    __u64 cr2;
    __u64 cr3;
    __u64 cr4;
    __u64 cr8;
    __u64 efer;
    __u64 apic_base;
    __u64[4] interrupt_bitmap;
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
struct kvm_sregs {
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct kvm_sregs {
    __u32 pvr;
    union (anon) u;
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct kvm_sregs {
    struct kvm_segment cs;
    struct kvm_segment ds;
    struct kvm_segment es;
    struct kvm_segment fs;
    struct kvm_segment gs;
    struct kvm_segment ss;
    struct kvm_segment tr;
    struct kvm_segment ldt;
    struct kvm_dtable gdt;
    struct kvm_dtable idt;
    __u64 cr0;
    __u64 cr2;
    __u64 cr3;
    __u64 cr4;
    __u64 cr8;
    __u64 efer;
    __u64 apic_base;
    __u64[4] interrupt_bitmap;
}
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct kvm_sregs {
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct kvm_sregs {
    __u32 pvr;
    union (anon) u;
}
```
</details>
</li>
</ul>
