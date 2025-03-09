# Struct: <code>thread_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct thread_struct {
    struct desc_struct[3] tls_array;
    long unsigned int sp0;
    long unsigned int sp;
    short unsigned int es;
    short unsigned int ds;
    short unsigned int fsindex;
    short unsigned int gsindex;
    long unsigned int fs;
    long unsigned int gs;
    struct perf_event *[4] ptrace_bps;
    long unsigned int debugreg6;
    long unsigned int ptrace_dr7;
    long unsigned int cr2;
    long unsigned int trap_nr;
    long unsigned int error_code;
    long unsigned int * io_bitmap_ptr;
    long unsigned int iopl;
    unsigned int io_bitmap_max;
    struct fpu fpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct thread_struct {
    struct desc_struct[3] tls_array;
    long unsigned int sp0;
    long unsigned int sp;
    short unsigned int es;
    short unsigned int ds;
    short unsigned int fsindex;
    short unsigned int gsindex;
    long unsigned int fsbase;
    long unsigned int gsbase;
    struct perf_event *[4] ptrace_bps;
    long unsigned int debugreg6;
    long unsigned int ptrace_dr7;
    long unsigned int cr2;
    long unsigned int trap_nr;
    long unsigned int error_code;
    long unsigned int * io_bitmap_ptr;
    long unsigned int iopl;
    unsigned int io_bitmap_max;
    mm_segment_t addr_limit;
    unsigned int sig_on_uaccess_err;
    unsigned int uaccess_err;
    struct fpu fpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct thread_struct {
    struct desc_struct[3] tls_array;
    long unsigned int sp0;
    long unsigned int sp;
    short unsigned int es;
    short unsigned int ds;
    short unsigned int fsindex;
    short unsigned int gsindex;
    u32 status;
    long unsigned int fsbase;
    long unsigned int gsbase;
    struct perf_event *[4] ptrace_bps;
    long unsigned int debugreg6;
    long unsigned int ptrace_dr7;
    long unsigned int cr2;
    long unsigned int trap_nr;
    long unsigned int error_code;
    long unsigned int * io_bitmap_ptr;
    long unsigned int iopl;
    unsigned int io_bitmap_max;
    mm_segment_t addr_limit;
    unsigned int sig_on_uaccess_err;
    unsigned int uaccess_err;
    struct fpu fpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct thread_struct {
    struct desc_struct[3] tls_array;
    long unsigned int sp0;
    long unsigned int sp;
    short unsigned int es;
    short unsigned int ds;
    short unsigned int fsindex;
    short unsigned int gsindex;
    u32 status;
    long unsigned int fsbase;
    long unsigned int gsbase;
    struct perf_event *[4] ptrace_bps;
    long unsigned int debugreg6;
    long unsigned int ptrace_dr7;
    long unsigned int cr2;
    long unsigned int trap_nr;
    long unsigned int error_code;
    long unsigned int * io_bitmap_ptr;
    long unsigned int iopl;
    unsigned int io_bitmap_max;
    mm_segment_t addr_limit;
    unsigned int sig_on_uaccess_err;
    unsigned int uaccess_err;
    struct fpu fpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct thread_struct {
    struct desc_struct[3] tls_array;
    long unsigned int sp;
    short unsigned int es;
    short unsigned int ds;
    short unsigned int fsindex;
    short unsigned int gsindex;
    long unsigned int fsbase;
    long unsigned int gsbase;
    struct perf_event *[4] ptrace_bps;
    long unsigned int debugreg6;
    long unsigned int ptrace_dr7;
    long unsigned int cr2;
    long unsigned int trap_nr;
    long unsigned int error_code;
    long unsigned int * io_bitmap_ptr;
    long unsigned int iopl;
    unsigned int io_bitmap_max;
    mm_segment_t addr_limit;
    unsigned int sig_on_uaccess_err;
    unsigned int uaccess_err;
    struct fpu fpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct thread_struct {
    struct desc_struct[3] tls_array;
    long unsigned int sp;
    short unsigned int es;
    short unsigned int ds;
    short unsigned int fsindex;
    short unsigned int gsindex;
    long unsigned int fsbase;
    long unsigned int gsbase;
    struct perf_event *[4] ptrace_bps;
    long unsigned int debugreg6;
    long unsigned int ptrace_dr7;
    long unsigned int cr2;
    long unsigned int trap_nr;
    long unsigned int error_code;
    long unsigned int * io_bitmap_ptr;
    long unsigned int iopl;
    unsigned int io_bitmap_max;
    mm_segment_t addr_limit;
    unsigned int sig_on_uaccess_err;
    unsigned int uaccess_err;
    struct fpu fpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct thread_struct {
    struct desc_struct[3] tls_array;
    long unsigned int sp;
    short unsigned int es;
    short unsigned int ds;
    short unsigned int fsindex;
    short unsigned int gsindex;
    long unsigned int fsbase;
    long unsigned int gsbase;
    struct perf_event *[4] ptrace_bps;
    long unsigned int debugreg6;
    long unsigned int ptrace_dr7;
    long unsigned int cr2;
    long unsigned int trap_nr;
    long unsigned int error_code;
    long unsigned int * io_bitmap_ptr;
    long unsigned int iopl;
    unsigned int io_bitmap_max;
    mm_segment_t addr_limit;
    unsigned int sig_on_uaccess_err;
    unsigned int uaccess_err;
    struct fpu fpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct thread_struct {
    struct desc_struct[3] tls_array;
    long unsigned int sp;
    short unsigned int es;
    short unsigned int ds;
    short unsigned int fsindex;
    short unsigned int gsindex;
    long unsigned int fsbase;
    long unsigned int gsbase;
    struct perf_event *[4] ptrace_bps;
    long unsigned int debugreg6;
    long unsigned int ptrace_dr7;
    long unsigned int cr2;
    long unsigned int trap_nr;
    long unsigned int error_code;
    long unsigned int * io_bitmap_ptr;
    long unsigned int iopl;
    unsigned int io_bitmap_max;
    mm_segment_t addr_limit;
    unsigned int sig_on_uaccess_err;
    unsigned int uaccess_err;
    struct fpu fpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct thread_struct {
    struct desc_struct[3] tls_array;
    long unsigned int sp;
    short unsigned int es;
    short unsigned int ds;
    short unsigned int fsindex;
    short unsigned int gsindex;
    long unsigned int fsbase;
    long unsigned int gsbase;
    struct perf_event *[4] ptrace_bps;
    long unsigned int debugreg6;
    long unsigned int ptrace_dr7;
    long unsigned int cr2;
    long unsigned int trap_nr;
    long unsigned int error_code;
    long unsigned int * io_bitmap_ptr;
    long unsigned int iopl;
    unsigned int io_bitmap_max;
    mm_segment_t addr_limit;
    unsigned int sig_on_uaccess_err;
    unsigned int uaccess_err;
    struct fpu fpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct thread_struct {
    struct desc_struct[3] tls_array;
    long unsigned int sp;
    short unsigned int es;
    short unsigned int ds;
    short unsigned int fsindex;
    short unsigned int gsindex;
    long unsigned int fsbase;
    long unsigned int gsbase;
    struct perf_event *[4] ptrace_bps;
    long unsigned int debugreg6;
    long unsigned int ptrace_dr7;
    long unsigned int cr2;
    long unsigned int trap_nr;
    long unsigned int error_code;
    struct io_bitmap * io_bitmap;
    long unsigned int iopl_emul;
    mm_segment_t addr_limit;
    unsigned int sig_on_uaccess_err;
    struct fpu fpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct thread_struct {
    struct desc_struct[3] tls_array;
    long unsigned int sp;
    short unsigned int es;
    short unsigned int ds;
    short unsigned int fsindex;
    short unsigned int gsindex;
    long unsigned int fsbase;
    long unsigned int gsbase;
    struct perf_event *[4] ptrace_bps;
    long unsigned int virtual_dr6;
    long unsigned int ptrace_dr7;
    long unsigned int cr2;
    long unsigned int trap_nr;
    long unsigned int error_code;
    struct io_bitmap * io_bitmap;
    long unsigned int iopl_emul;
    unsigned int sig_on_uaccess_err;
    struct fpu fpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct thread_struct {
    struct desc_struct[3] tls_array;
    long unsigned int sp;
    short unsigned int es;
    short unsigned int ds;
    short unsigned int fsindex;
    short unsigned int gsindex;
    long unsigned int fsbase;
    long unsigned int gsbase;
    struct perf_event *[4] ptrace_bps;
    long unsigned int virtual_dr6;
    long unsigned int ptrace_dr7;
    long unsigned int cr2;
    long unsigned int trap_nr;
    long unsigned int error_code;
    struct io_bitmap * io_bitmap;
    long unsigned int iopl_emul;
    unsigned int sig_on_uaccess_err;
    struct fpu fpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct thread_struct {
    struct desc_struct[3] tls_array;
    long unsigned int sp;
    short unsigned int es;
    short unsigned int ds;
    short unsigned int fsindex;
    short unsigned int gsindex;
    long unsigned int fsbase;
    long unsigned int gsbase;
    struct perf_event *[4] ptrace_bps;
    long unsigned int virtual_dr6;
    long unsigned int ptrace_dr7;
    long unsigned int cr2;
    long unsigned int trap_nr;
    long unsigned int error_code;
    struct io_bitmap * io_bitmap;
    long unsigned int iopl_emul;
    unsigned int iopl_warn;
    unsigned int sig_on_uaccess_err;
    u32 pkru;
    struct fpu fpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct thread_struct {
    struct desc_struct[3] tls_array;
    long unsigned int sp;
    short unsigned int es;
    short unsigned int ds;
    short unsigned int fsindex;
    short unsigned int gsindex;
    long unsigned int fsbase;
    long unsigned int gsbase;
    struct perf_event *[4] ptrace_bps;
    long unsigned int virtual_dr6;
    long unsigned int ptrace_dr7;
    long unsigned int cr2;
    long unsigned int trap_nr;
    long unsigned int error_code;
    struct io_bitmap * io_bitmap;
    long unsigned int iopl_emul;
    unsigned int iopl_warn;
    unsigned int sig_on_uaccess_err;
    u32 pkru;
    struct fpu fpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct thread_struct {
    struct desc_struct[3] tls_array;
    long unsigned int sp;
    short unsigned int es;
    short unsigned int ds;
    short unsigned int fsindex;
    short unsigned int gsindex;
    long unsigned int fsbase;
    long unsigned int gsbase;
    struct perf_event *[4] ptrace_bps;
    long unsigned int virtual_dr6;
    long unsigned int ptrace_dr7;
    long unsigned int cr2;
    long unsigned int trap_nr;
    long unsigned int error_code;
    struct io_bitmap * io_bitmap;
    long unsigned int iopl_emul;
    unsigned int iopl_warn;
    unsigned int sig_on_uaccess_err;
    u32 pkru;
    struct fpu fpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct thread_struct {
    struct desc_struct[3] tls_array;
    long unsigned int sp;
    short unsigned int es;
    short unsigned int ds;
    short unsigned int fsindex;
    short unsigned int gsindex;
    long unsigned int fsbase;
    long unsigned int gsbase;
    struct perf_event *[4] ptrace_bps;
    long unsigned int virtual_dr6;
    long unsigned int ptrace_dr7;
    long unsigned int cr2;
    long unsigned int trap_nr;
    long unsigned int error_code;
    struct io_bitmap * io_bitmap;
    long unsigned int iopl_emul;
    unsigned int iopl_warn;
    unsigned int sig_on_uaccess_err;
    u32 pkru;
    struct fpu fpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct thread_struct {
    struct desc_struct[3] tls_array;
    long unsigned int sp;
    short unsigned int es;
    short unsigned int ds;
    short unsigned int fsindex;
    short unsigned int gsindex;
    long unsigned int fsbase;
    long unsigned int gsbase;
    struct perf_event *[4] ptrace_bps;
    long unsigned int virtual_dr6;
    long unsigned int ptrace_dr7;
    long unsigned int cr2;
    long unsigned int trap_nr;
    long unsigned int error_code;
    struct io_bitmap * io_bitmap;
    long unsigned int iopl_emul;
    unsigned int iopl_warn;
    unsigned int sig_on_uaccess_err;
    u32 pkru;
    long unsigned int features;
    long unsigned int features_locked;
    struct thread_shstk shstk;
    struct fpu fpu;
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
struct thread_struct {
    struct cpu_context cpu_context;
    struct (anon) uw;
    unsigned int fpsimd_cpu;
    void * sve_state;
    unsigned int sve_vl;
    unsigned int sve_vl_onexec;
    long unsigned int fault_address;
    long unsigned int fault_code;
    struct debug_info debug;
    struct ptrauth_keys keys_user;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct thread_struct {
    long unsigned int address;
    long unsigned int trap_no;
    long unsigned int error_code;
    struct debug_info debug;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct thread_struct {
    long unsigned int ksp;
    long unsigned int ksp_vsid;
    struct pt_regs * regs;
    mm_segment_t addr_limit;
    struct debug_reg debug;
    struct thread_fp_state fp_state;
    struct thread_fp_state * fp_save_area;
    int fpexc_mode;
    unsigned int align_ctl;
    struct perf_event *[1] ptrace_bps;
    struct perf_event * last_hit_ubp;
    struct arch_hw_breakpoint hw_brk;
    long unsigned int trap_nr;
    u8 load_slb;
    u8 load_fp;
    u8 load_vec;
    struct thread_vr_state vr_state;
    struct thread_vr_state * vr_save_area;
    long unsigned int vrsave;
    int used_vr;
    int used_vsr;
    u8 load_tm;
    u64 tm_tfhar;
    u64 tm_texasr;
    u64 tm_tfiar;
    struct pt_regs ckpt_regs;
    long unsigned int tm_tar;
    long unsigned int tm_ppr;
    long unsigned int tm_dscr;
    struct thread_fp_state ckfp_state;
    struct thread_vr_state ckvr_state;
    long unsigned int ckvrsave;
    long unsigned int dscr;
    long unsigned int fscr;
    int dscr_inherit;
    long unsigned int tidr;
    long unsigned int tar;
    long unsigned int ebbrr;
    long unsigned int ebbhr;
    long unsigned int bescr;
    long unsigned int siar;
    long unsigned int sdar;
    long unsigned int sier;
    long unsigned int mmcr2;
    unsigned int mmcr0;
    unsigned int used_ebb;
    unsigned int used_vas;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct thread_struct {
    long unsigned int ra;
    long unsigned int sp;
    long unsigned int[12] s;
    struct __riscv_d_ext_state fstate;
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
struct thread_struct {
    struct desc_struct[3] tls_array;
    long unsigned int sp;
    short unsigned int es;
    short unsigned int ds;
    short unsigned int fsindex;
    short unsigned int gsindex;
    long unsigned int fsbase;
    long unsigned int gsbase;
    struct perf_event *[4] ptrace_bps;
    long unsigned int debugreg6;
    long unsigned int ptrace_dr7;
    long unsigned int cr2;
    long unsigned int trap_nr;
    long unsigned int error_code;
    long unsigned int * io_bitmap_ptr;
    long unsigned int iopl;
    unsigned int io_bitmap_max;
    mm_segment_t addr_limit;
    unsigned int sig_on_uaccess_err;
    unsigned int uaccess_err;
    struct fpu fpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct thread_struct {
    struct desc_struct[3] tls_array;
    long unsigned int sp;
    short unsigned int es;
    short unsigned int ds;
    short unsigned int fsindex;
    short unsigned int gsindex;
    long unsigned int fsbase;
    long unsigned int gsbase;
    struct perf_event *[4] ptrace_bps;
    long unsigned int debugreg6;
    long unsigned int ptrace_dr7;
    long unsigned int cr2;
    long unsigned int trap_nr;
    long unsigned int error_code;
    long unsigned int * io_bitmap_ptr;
    long unsigned int iopl;
    unsigned int io_bitmap_max;
    mm_segment_t addr_limit;
    unsigned int sig_on_uaccess_err;
    unsigned int uaccess_err;
    struct fpu fpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct thread_struct {
    struct desc_struct[3] tls_array;
    long unsigned int sp;
    short unsigned int es;
    short unsigned int ds;
    short unsigned int fsindex;
    short unsigned int gsindex;
    long unsigned int fsbase;
    long unsigned int gsbase;
    struct perf_event *[4] ptrace_bps;
    long unsigned int debugreg6;
    long unsigned int ptrace_dr7;
    long unsigned int cr2;
    long unsigned int trap_nr;
    long unsigned int error_code;
    long unsigned int * io_bitmap_ptr;
    long unsigned int iopl;
    unsigned int io_bitmap_max;
    mm_segment_t addr_limit;
    unsigned int sig_on_uaccess_err;
    unsigned int uaccess_err;
    struct fpu fpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct thread_struct {
    struct desc_struct[3] tls_array;
    long unsigned int sp;
    short unsigned int es;
    short unsigned int ds;
    short unsigned int fsindex;
    short unsigned int gsindex;
    long unsigned int fsbase;
    long unsigned int gsbase;
    struct perf_event *[4] ptrace_bps;
    long unsigned int debugreg6;
    long unsigned int ptrace_dr7;
    long unsigned int cr2;
    long unsigned int trap_nr;
    long unsigned int error_code;
    long unsigned int * io_bitmap_ptr;
    long unsigned int iopl;
    unsigned int io_bitmap_max;
    mm_segment_t addr_limit;
    unsigned int sig_on_uaccess_err;
    unsigned int uaccess_err;
    struct fpu fpu;
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
<code>long unsigned int fsbase</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int gsbase</code>
</li>
<li>
<b>Field added. </b>
<code>mm_segment_t addr_limit</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int sig_on_uaccess_err</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int uaccess_err</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int fs</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int gs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 status</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long unsigned int sp0</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 status</code>
</li>
</ul>
</details>
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
<code>struct io_bitmap * io_bitmap</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int iopl_emul</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int * io_bitmap_ptr</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int iopl</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int io_bitmap_max</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int uaccess_err</code>
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
<code>long unsigned int virtual_dr6</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int debugreg6</code>
</li>
<li>
<b>Field removed. </b>
<code>mm_segment_t addr_limit</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int iopl_warn</code>
</li>
<li>
<b>Field added. </b>
<code>u32 pkru</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int features</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int features_locked</code>
</li>
<li>
<b>Field added. </b>
<code>struct thread_shstk shstk</code>
</li>
</ul>
</details>
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
<code>struct cpu_context cpu_context</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) uw</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int fpsimd_cpu</code>
</li>
<li>
<b>Field added. </b>
<code>void * sve_state</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int sve_vl</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int sve_vl_onexec</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int fault_address</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int fault_code</code>
</li>
<li>
<b>Field added. </b>
<code>struct debug_info debug</code>
</li>
<li>
<b>Field added. </b>
<code>struct ptrauth_keys keys_user</code>
</li>
<li>
<b>Field removed. </b>
<code>struct desc_struct[3] tls_array</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int sp</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int es</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int ds</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int fsindex</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int gsindex</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int fsbase</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int gsbase</code>
</li>
<li>
<b>Field removed. </b>
<code>struct perf_event *[4] ptrace_bps</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int debugreg6</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int ptrace_dr7</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int cr2</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int trap_nr</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int error_code</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int * io_bitmap_ptr</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int iopl</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int io_bitmap_max</code>
</li>
<li>
<b>Field removed. </b>
<code>mm_segment_t addr_limit</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int sig_on_uaccess_err</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int uaccess_err</code>
</li>
<li>
<b>Field removed. </b>
<code>struct fpu fpu</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int address</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int trap_no</code>
</li>
<li>
<b>Field added. </b>
<code>struct debug_info debug</code>
</li>
<li>
<b>Field removed. </b>
<code>struct desc_struct[3] tls_array</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int sp</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int es</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int ds</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int fsindex</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int gsindex</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int fsbase</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int gsbase</code>
</li>
<li>
<b>Field removed. </b>
<code>struct perf_event *[4] ptrace_bps</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int debugreg6</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int ptrace_dr7</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int cr2</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int trap_nr</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int * io_bitmap_ptr</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int iopl</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int io_bitmap_max</code>
</li>
<li>
<b>Field removed. </b>
<code>mm_segment_t addr_limit</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int sig_on_uaccess_err</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int uaccess_err</code>
</li>
<li>
<b>Field removed. </b>
<code>struct fpu fpu</code>
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
<code>long unsigned int ksp</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int ksp_vsid</code>
</li>
<li>
<b>Field added. </b>
<code>struct pt_regs * regs</code>
</li>
<li>
<b>Field added. </b>
<code>struct debug_reg debug</code>
</li>
<li>
<b>Field added. </b>
<code>struct thread_fp_state fp_state</code>
</li>
<li>
<b>Field added. </b>
<code>struct thread_fp_state * fp_save_area</code>
</li>
<li>
<b>Field added. </b>
<code>int fpexc_mode</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int align_ctl</code>
</li>
<li>
<b>Field added. </b>
<code>struct perf_event * last_hit_ubp</code>
</li>
<li>
<b>Field added. </b>
<code>struct arch_hw_breakpoint hw_brk</code>
</li>
<li>
<b>Field added. </b>
<code>u8 load_slb</code>
</li>
<li>
<b>Field added. </b>
<code>u8 load_fp</code>
</li>
<li>
<b>Field added. </b>
<code>u8 load_vec</code>
</li>
<li>
<b>Field added. </b>
<code>struct thread_vr_state vr_state</code>
</li>
<li>
<b>Field added. </b>
<code>struct thread_vr_state * vr_save_area</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int vrsave</code>
</li>
<li>
<b>Field added. </b>
<code>int used_vr</code>
</li>
<li>
<b>Field added. </b>
<code>int used_vsr</code>
</li>
<li>
<b>Field added. </b>
<code>u8 load_tm</code>
</li>
<li>
<b>Field added. </b>
<code>u64 tm_tfhar</code>
</li>
<li>
<b>Field added. </b>
<code>u64 tm_texasr</code>
</li>
<li>
<b>Field added. </b>
<code>u64 tm_tfiar</code>
</li>
<li>
<b>Field added. </b>
<code>struct pt_regs ckpt_regs</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int tm_tar</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int tm_ppr</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int tm_dscr</code>
</li>
<li>
<b>Field added. </b>
<code>struct thread_fp_state ckfp_state</code>
</li>
<li>
<b>Field added. </b>
<code>struct thread_vr_state ckvr_state</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int ckvrsave</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int dscr</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int fscr</code>
</li>
<li>
<b>Field added. </b>
<code>int dscr_inherit</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int tidr</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int tar</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int ebbrr</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int ebbhr</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int bescr</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int siar</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int sdar</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int sier</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int mmcr2</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int mmcr0</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int used_ebb</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int used_vas</code>
</li>
<li>
<b>Field removed. </b>
<code>struct desc_struct[3] tls_array</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int sp</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int es</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int ds</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int fsindex</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int gsindex</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int fsbase</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int gsbase</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int debugreg6</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int ptrace_dr7</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int cr2</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int error_code</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int * io_bitmap_ptr</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int iopl</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int io_bitmap_max</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int sig_on_uaccess_err</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int uaccess_err</code>
</li>
<li>
<b>Field removed. </b>
<code>struct fpu fpu</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct perf_event *[4] ptrace_bps</code> ➡️ <code>struct perf_event *[1] ptrace_bps</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int ra</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int[12] s</code>
</li>
<li>
<b>Field added. </b>
<code>struct __riscv_d_ext_state fstate</code>
</li>
<li>
<b>Field removed. </b>
<code>struct desc_struct[3] tls_array</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int es</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int ds</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int fsindex</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int gsindex</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int fsbase</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int gsbase</code>
</li>
<li>
<b>Field removed. </b>
<code>struct perf_event *[4] ptrace_bps</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int debugreg6</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int ptrace_dr7</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int cr2</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int trap_nr</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int error_code</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int * io_bitmap_ptr</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int iopl</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int io_bitmap_max</code>
</li>
<li>
<b>Field removed. </b>
<code>mm_segment_t addr_limit</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int sig_on_uaccess_err</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int uaccess_err</code>
</li>
<li>
<b>Field removed. </b>
<code>struct fpu fpu</code>
</li>
</ul>
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
