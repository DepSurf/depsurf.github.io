# Struct: <code>vdso_image</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    struct vm_special_mapping text_mapping;
    long unsigned int alt;
    long unsigned int alt_len;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_hpet_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_hpet_page;
    long int sym_pvclock_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_hpet_page;
    long int sym_pvclock_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_hpet_page;
    long int sym_pvclock_page;
    long int sym_hvclock_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_hpet_page;
    long int sym_pvclock_page;
    long int sym_hvclock_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_hpet_page;
    long int sym_pvclock_page;
    long int sym_hvclock_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_hpet_page;
    long int sym_pvclock_page;
    long int sym_hvclock_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_pvclock_page;
    long int sym_hvclock_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_pvclock_page;
    long int sym_hvclock_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_pvclock_page;
    long int sym_hvclock_page;
    long int sym_timens_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long unsigned int extable_base;
    long unsigned int extable_len;
    const void * extable;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_pvclock_page;
    long int sym_hvclock_page;
    long int sym_timens_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
    long int sym_vdso32_sigreturn_landing_pad;
    long int sym_vdso32_rt_sigreturn_landing_pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long unsigned int extable_base;
    long unsigned int extable_len;
    const void * extable;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_pvclock_page;
    long int sym_hvclock_page;
    long int sym_timens_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
    long int sym_vdso32_sigreturn_landing_pad;
    long int sym_vdso32_rt_sigreturn_landing_pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long unsigned int extable_base;
    long unsigned int extable_len;
    const void * extable;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_pvclock_page;
    long int sym_hvclock_page;
    long int sym_timens_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
    long int sym_vdso32_sigreturn_landing_pad;
    long int sym_vdso32_rt_sigreturn_landing_pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long unsigned int extable_base;
    long unsigned int extable_len;
    const void * extable;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_pvclock_page;
    long int sym_hvclock_page;
    long int sym_timens_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
    long int sym_vdso32_sigreturn_landing_pad;
    long int sym_vdso32_rt_sigreturn_landing_pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long unsigned int extable_base;
    long unsigned int extable_len;
    const void * extable;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_pvclock_page;
    long int sym_hvclock_page;
    long int sym_timens_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
    long int sym_vdso32_sigreturn_landing_pad;
    long int sym_vdso32_rt_sigreturn_landing_pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long unsigned int extable_base;
    long unsigned int extable_len;
    const void * extable;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_pvclock_page;
    long int sym_hvclock_page;
    long int sym_timens_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
    long int sym_vdso32_sigreturn_landing_pad;
    long int sym_vdso32_rt_sigreturn_landing_pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long unsigned int extable_base;
    long unsigned int extable_len;
    const void * extable;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_pvclock_page;
    long int sym_hvclock_page;
    long int sym_timens_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
    long int sym_vdso32_sigreturn_landing_pad;
    long int sym_vdso32_rt_sigreturn_landing_pad;
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
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_pvclock_page;
    long int sym_hvclock_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_pvclock_page;
    long int sym_hvclock_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_pvclock_page;
    long int sym_hvclock_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_pvclock_page;
    long int sym_hvclock_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
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
<b>Field added. </b>
<code>long int sym_pvclock_page</code>
</li>
<li>
<b>Field removed. </b>
<code>struct vm_special_mapping text_mapping</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long int sym_hvclock_page</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long int sym_hpet_page</code>
</li>
</ul>
</details>
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
<code>long int sym_timens_page</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int extable_base</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int extable_len</code>
</li>
<li>
<b>Field added. </b>
<code>const void * extable</code>
</li>
<li>
<b>Field added. </b>
<code>long int sym_vdso32_sigreturn_landing_pad</code>
</li>
<li>
<b>Field added. </b>
<code>long int sym_vdso32_rt_sigreturn_landing_pad</code>
</li>
</ul>
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_pvclock_page;
    long int sym_hvclock_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_pvclock_page;
    long int sym_hvclock_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_pvclock_page;
    long int sym_hvclock_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct vdso_image {
    void * data;
    long unsigned int size;
    long unsigned int alt;
    long unsigned int alt_len;
    long int sym_vvar_start;
    long int sym_vvar_page;
    long int sym_pvclock_page;
    long int sym_hvclock_page;
    long int sym_VDSO32_NOTE_MASK;
    long int sym___kernel_sigreturn;
    long int sym___kernel_rt_sigreturn;
    long int sym___kernel_vsyscall;
    long int sym_int80_landing_pad;
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
