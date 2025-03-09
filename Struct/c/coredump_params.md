# Struct: <code>coredump_params</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct coredump_params {
    const siginfo_t * siginfo;
    struct pt_regs * regs;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    loff_t written;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct coredump_params {
    const siginfo_t * siginfo;
    struct pt_regs * regs;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    loff_t written;
    loff_t pos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct coredump_params {
    const siginfo_t * siginfo;
    struct pt_regs * regs;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    loff_t written;
    loff_t pos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct coredump_params {
    const siginfo_t * siginfo;
    struct pt_regs * regs;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    loff_t written;
    loff_t pos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct coredump_params {
    const siginfo_t * siginfo;
    struct pt_regs * regs;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    loff_t written;
    loff_t pos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct coredump_params {
    const siginfo_t * siginfo;
    struct pt_regs * regs;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    loff_t written;
    loff_t pos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct coredump_params {
    const kernel_siginfo_t * siginfo;
    struct pt_regs * regs;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    loff_t written;
    loff_t pos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct coredump_params {
    const kernel_siginfo_t * siginfo;
    struct pt_regs * regs;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    loff_t written;
    loff_t pos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct coredump_params {
    const kernel_siginfo_t * siginfo;
    struct pt_regs * regs;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    loff_t written;
    loff_t pos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct coredump_params {
    const kernel_siginfo_t * siginfo;
    struct pt_regs * regs;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    loff_t written;
    loff_t pos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct coredump_params {
    const kernel_siginfo_t * siginfo;
    struct pt_regs * regs;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    loff_t written;
    loff_t pos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct coredump_params {
    const kernel_siginfo_t * siginfo;
    struct pt_regs * regs;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    loff_t written;
    loff_t pos;
    loff_t to_skip;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct coredump_params {
    const kernel_siginfo_t * siginfo;
    struct pt_regs * regs;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    loff_t written;
    loff_t pos;
    loff_t to_skip;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct coredump_params {
    const kernel_siginfo_t * siginfo;
    struct pt_regs * regs;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    loff_t written;
    loff_t pos;
    loff_t to_skip;
    int vma_count;
    size_t vma_data_size;
    struct core_vma_metadata * vma_meta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct coredump_params {
    const kernel_siginfo_t * siginfo;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    int cpu;
    loff_t written;
    loff_t pos;
    loff_t to_skip;
    int vma_count;
    size_t vma_data_size;
    struct core_vma_metadata * vma_meta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct coredump_params {
    const kernel_siginfo_t * siginfo;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    int cpu;
    loff_t written;
    loff_t pos;
    loff_t to_skip;
    int vma_count;
    size_t vma_data_size;
    struct core_vma_metadata * vma_meta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct coredump_params {
    const kernel_siginfo_t * siginfo;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    int cpu;
    loff_t written;
    loff_t pos;
    loff_t to_skip;
    int vma_count;
    size_t vma_data_size;
    struct core_vma_metadata * vma_meta;
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
struct coredump_params {
    const kernel_siginfo_t * siginfo;
    struct pt_regs * regs;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    loff_t written;
    loff_t pos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct coredump_params {
    const kernel_siginfo_t * siginfo;
    struct pt_regs * regs;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    loff_t written;
    loff_t pos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct coredump_params {
    const kernel_siginfo_t * siginfo;
    struct pt_regs * regs;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    loff_t written;
    loff_t pos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct coredump_params {
    const kernel_siginfo_t * siginfo;
    struct pt_regs * regs;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    loff_t written;
    loff_t pos;
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
struct coredump_params {
    const kernel_siginfo_t * siginfo;
    struct pt_regs * regs;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    loff_t written;
    loff_t pos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct coredump_params {
    const kernel_siginfo_t * siginfo;
    struct pt_regs * regs;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    loff_t written;
    loff_t pos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct coredump_params {
    const kernel_siginfo_t * siginfo;
    struct pt_regs * regs;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    loff_t written;
    loff_t pos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct coredump_params {
    const kernel_siginfo_t * siginfo;
    struct pt_regs * regs;
    struct file * file;
    long unsigned int limit;
    long unsigned int mm_flags;
    loff_t written;
    loff_t pos;
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
<code>loff_t pos</code>
</li>
</ul>
</details>
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
<b>Field type changed. </b>
<code>const siginfo_t * siginfo</code> ➡️ <code>const kernel_siginfo_t * siginfo</code>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>loff_t to_skip</code>
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
<b>Field added. </b>
<code>int vma_count</code>
</li>
<li>
<b>Field added. </b>
<code>size_t vma_data_size</code>
</li>
<li>
<b>Field added. </b>
<code>struct core_vma_metadata * vma_meta</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int cpu</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pt_regs * regs</code>
</li>
</ul>
</details>
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
