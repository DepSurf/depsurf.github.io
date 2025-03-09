# Struct: <code>pv_cpu_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pv_cpu_ops {
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    void (*)() clts;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    long unsigned int (*)() read_cr4_safe;
    long unsigned int (*)() read_cr4;
    void (*)(long unsigned int) write_cr4;
    long unsigned int (*)() read_cr8;
    void (*)(long unsigned int) write_cr8;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(struct desc_ptr *) store_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(struct tss_struct *, struct thread_struct *) load_sp0;
    void (*)(unsigned int) set_iopl_mask;
    void (*)() wbinvd;
    void (*)() io_delay;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int, int *) read_msr;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(int) read_pmc;
    void (*)() usergs_sysret64;
    void (*)() usergs_sysret32;
    void (*)() iret;
    void (*)() swapgs;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pv_cpu_ops {
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    void (*)() clts;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    long unsigned int (*)() read_cr4_safe;
    long unsigned int (*)() read_cr4;
    void (*)(long unsigned int) write_cr4;
    long unsigned int (*)() read_cr8;
    void (*)(long unsigned int) write_cr8;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(struct desc_ptr *) store_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(struct tss_struct *, struct thread_struct *) load_sp0;
    void (*)(unsigned int) set_iopl_mask;
    void (*)() wbinvd;
    void (*)() io_delay;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)() usergs_sysret64;
    void (*)() iret;
    void (*)() swapgs;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pv_cpu_ops {
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    long unsigned int (*)() read_cr4;
    void (*)(long unsigned int) write_cr4;
    long unsigned int (*)() read_cr8;
    void (*)(long unsigned int) write_cr8;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(struct desc_ptr *) store_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(struct tss_struct *, struct thread_struct *) load_sp0;
    void (*)(unsigned int) set_iopl_mask;
    void (*)() wbinvd;
    void (*)() io_delay;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)() usergs_sysret64;
    void (*)() iret;
    void (*)() swapgs;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pv_cpu_ops {
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    long unsigned int (*)() read_cr4;
    void (*)(long unsigned int) write_cr4;
    long unsigned int (*)() read_cr8;
    void (*)(long unsigned int) write_cr8;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(struct desc_ptr *) store_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(struct tss_struct *, struct thread_struct *) load_sp0;
    void (*)(unsigned int) set_iopl_mask;
    void (*)() wbinvd;
    void (*)() io_delay;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)() usergs_sysret64;
    void (*)() iret;
    void (*)() swapgs;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pv_cpu_ops {
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    void (*)(long unsigned int) write_cr4;
    long unsigned int (*)() read_cr8;
    void (*)(long unsigned int) write_cr8;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(long unsigned int) load_sp0;
    void (*)(unsigned int) set_iopl_mask;
    void (*)() wbinvd;
    void (*)() io_delay;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)() usergs_sysret64;
    void (*)() iret;
    void (*)() swapgs;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pv_cpu_ops {
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    void (*)(long unsigned int) write_cr4;
    long unsigned int (*)() read_cr8;
    void (*)(long unsigned int) write_cr8;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(long unsigned int) load_sp0;
    void (*)(unsigned int) set_iopl_mask;
    void (*)() wbinvd;
    void (*)() io_delay;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)() usergs_sysret64;
    void (*)() iret;
    void (*)() swapgs;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pv_cpu_ops {
    void (*)() io_delay;
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    void (*)(long unsigned int) write_cr4;
    long unsigned int (*)() read_cr8;
    void (*)(long unsigned int) write_cr8;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(long unsigned int) load_sp0;
    void (*)(unsigned int) set_iopl_mask;
    void (*)() wbinvd;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)() usergs_sysret64;
    void (*)() iret;
    void (*)() swapgs;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pv_cpu_ops {
    void (*)() io_delay;
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    void (*)(long unsigned int) write_cr4;
    long unsigned int (*)() read_cr8;
    void (*)(long unsigned int) write_cr8;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(long unsigned int) load_sp0;
    void (*)(unsigned int) set_iopl_mask;
    void (*)() wbinvd;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)() usergs_sysret64;
    void (*)() iret;
    void (*)() swapgs;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pv_cpu_ops {
    void (*)() io_delay;
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    void (*)(long unsigned int) write_cr4;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(long unsigned int) load_sp0;
    void (*)(unsigned int) set_iopl_mask;
    void (*)() wbinvd;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)() usergs_sysret64;
    void (*)() iret;
    void (*)() swapgs;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pv_cpu_ops {
    void (*)() io_delay;
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    void (*)(long unsigned int) write_cr4;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(long unsigned int) load_sp0;
    void (*)() invalidate_io_bitmap;
    void (*)() update_io_bitmap;
    void (*)() wbinvd;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)() usergs_sysret64;
    void (*)() iret;
    void (*)() swapgs;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pv_cpu_ops {
    void (*)() io_delay;
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    void (*)(long unsigned int) write_cr4;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(long unsigned int) load_sp0;
    void (*)() invalidate_io_bitmap;
    void (*)() update_io_bitmap;
    void (*)() wbinvd;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)() usergs_sysret64;
    void (*)() iret;
    void (*)() swapgs;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pv_cpu_ops {
    void (*)() io_delay;
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    void (*)(long unsigned int) write_cr4;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(long unsigned int) load_sp0;
    void (*)() invalidate_io_bitmap;
    void (*)() update_io_bitmap;
    void (*)() wbinvd;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pv_cpu_ops {
    void (*)() io_delay;
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    void (*)(long unsigned int) write_cr4;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(long unsigned int) load_sp0;
    void (*)() invalidate_io_bitmap;
    void (*)() update_io_bitmap;
    void (*)() wbinvd;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pv_cpu_ops {
    void (*)() io_delay;
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    void (*)(long unsigned int) write_cr4;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(long unsigned int) load_sp0;
    void (*)() invalidate_io_bitmap;
    void (*)() update_io_bitmap;
    void (*)() wbinvd;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pv_cpu_ops {
    void (*)() io_delay;
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    void (*)(long unsigned int) write_cr4;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(long unsigned int) load_sp0;
    void (*)() invalidate_io_bitmap;
    void (*)() update_io_bitmap;
    void (*)() wbinvd;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pv_cpu_ops {
    void (*)() io_delay;
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    void (*)(long unsigned int) write_cr4;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(long unsigned int) load_sp0;
    void (*)() invalidate_io_bitmap;
    void (*)() update_io_bitmap;
    void (*)() wbinvd;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pv_cpu_ops {
    void (*)() io_delay;
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    void (*)(long unsigned int) write_cr4;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(long unsigned int) load_sp0;
    void (*)() invalidate_io_bitmap;
    void (*)() update_io_bitmap;
    void (*)() wbinvd;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
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
struct pv_cpu_ops {
    void (*)() io_delay;
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    void (*)(long unsigned int) write_cr4;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(long unsigned int) load_sp0;
    void (*)(unsigned int) set_iopl_mask;
    void (*)() wbinvd;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)() usergs_sysret64;
    void (*)() iret;
    void (*)() swapgs;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pv_cpu_ops {
    void (*)() io_delay;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pv_cpu_ops {
    void (*)() io_delay;
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    void (*)(long unsigned int) write_cr4;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(long unsigned int) load_sp0;
    void (*)(unsigned int) set_iopl_mask;
    void (*)() wbinvd;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)() usergs_sysret64;
    void (*)() iret;
    void (*)() swapgs;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pv_cpu_ops {
    void (*)() io_delay;
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    void (*)(long unsigned int) write_cr4;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(long unsigned int) load_sp0;
    void (*)(unsigned int) set_iopl_mask;
    void (*)() wbinvd;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)() usergs_sysret64;
    void (*)() iret;
    void (*)() swapgs;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
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
<code>u64 (*)(unsigned int, int *) read_msr_safe</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)() usergs_sysret32</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64 (*)(unsigned int, int *) read_msr</code> ➡️ <code>u64 (*)(unsigned int) read_msr</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(unsigned int, unsigned int, unsigned int) write_msr</code> ➡️ <code>void (*)(unsigned int, unsigned int, unsigned int) write_msr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>void (*)() clts</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int (*)() read_cr4_safe</code>
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
<code>long unsigned int (*)() read_cr4</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct desc_ptr *) store_idt</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct tss_struct *, struct thread_struct *) load_sp0</code> ➡️ <code>void (*)(long unsigned int) load_sp0</code>
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long unsigned int (*)() read_cr8</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(long unsigned int) write_cr8</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)() invalidate_io_bitmap</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)() update_io_bitmap</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(unsigned int) set_iopl_mask</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>void (*)() usergs_sysret64</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)() iret</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)() swapgs</code>
</li>
</ul>
</details>
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
struct pv_cpu_ops {
    void (*)() io_delay;
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    void (*)(long unsigned int) write_cr4;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(long unsigned int) load_sp0;
    void (*)(unsigned int) set_iopl_mask;
    void (*)() wbinvd;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)() usergs_sysret64;
    void (*)() iret;
    void (*)() swapgs;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct pv_cpu_ops {
    void (*)() io_delay;
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    void (*)(long unsigned int) write_cr4;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(long unsigned int) load_sp0;
    void (*)(unsigned int) set_iopl_mask;
    void (*)() wbinvd;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)() usergs_sysret64;
    void (*)() iret;
    void (*)() swapgs;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct pv_cpu_ops {
    void (*)() io_delay;
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    void (*)(long unsigned int) write_cr4;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(long unsigned int) load_sp0;
    void (*)(unsigned int) set_iopl_mask;
    void (*)() wbinvd;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)() usergs_sysret64;
    void (*)() iret;
    void (*)() swapgs;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct pv_cpu_ops {
    void (*)() io_delay;
    long unsigned int (*)(int) get_debugreg;
    void (*)(int, long unsigned int) set_debugreg;
    long unsigned int (*)() read_cr0;
    void (*)(long unsigned int) write_cr0;
    void (*)(long unsigned int) write_cr4;
    void (*)() load_tr_desc;
    void (*)(const struct desc_ptr *) load_gdt;
    void (*)(const struct desc_ptr *) load_idt;
    void (*)(const void *, unsigned int) set_ldt;
    long unsigned int (*)() store_tr;
    void (*)(struct thread_struct *, unsigned int) load_tls;
    void (*)(unsigned int) load_gs_index;
    void (*)(struct desc_struct *, int, const void *) write_ldt_entry;
    void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry;
    void (*)(gate_desc *, int, const gate_desc *) write_idt_entry;
    void (*)(struct desc_struct *, unsigned int) alloc_ldt;
    void (*)(struct desc_struct *, unsigned int) free_ldt;
    void (*)(long unsigned int) load_sp0;
    void (*)(unsigned int) set_iopl_mask;
    void (*)() wbinvd;
    void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid;
    u64 (*)(unsigned int) read_msr;
    void (*)(unsigned int, unsigned int, unsigned int) write_msr;
    u64 (*)(unsigned int, int *) read_msr_safe;
    int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe;
    u64 (*)(int) read_pmc;
    void (*)() usergs_sysret64;
    void (*)() iret;
    void (*)() swapgs;
    void (*)(struct task_struct *) start_context_switch;
    void (*)(struct task_struct *) end_context_switch;
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long unsigned int (*)(int) get_debugreg</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(int, long unsigned int) set_debugreg</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int (*)() read_cr0</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(long unsigned int) write_cr0</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(long unsigned int) write_cr4</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)() load_tr_desc</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(const struct desc_ptr *) load_gdt</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(const struct desc_ptr *) load_idt</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(const void *, unsigned int) set_ldt</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int (*)() store_tr</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct thread_struct *, unsigned int) load_tls</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(unsigned int) load_gs_index</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct desc_struct *, int, const void *) write_ldt_entry</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct desc_struct *, int, const void *, int) write_gdt_entry</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(gate_desc *, int, const gate_desc *) write_idt_entry</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct desc_struct *, unsigned int) alloc_ldt</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct desc_struct *, unsigned int) free_ldt</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(long unsigned int) load_sp0</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(unsigned int) set_iopl_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)() wbinvd</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(unsigned int *, unsigned int *, unsigned int *, unsigned int *) cpuid</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 (*)(unsigned int) read_msr</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(unsigned int, unsigned int, unsigned int) write_msr</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 (*)(unsigned int, int *) read_msr_safe</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(unsigned int, unsigned int, unsigned int) write_msr_safe</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 (*)(int) read_pmc</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)() usergs_sysret64</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)() iret</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)() swapgs</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct task_struct *) start_context_switch</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct task_struct *) end_context_switch</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
