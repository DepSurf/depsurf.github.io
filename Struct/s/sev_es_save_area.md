# Struct: <code>sev_es_save_area</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sev_es_save_area {
    struct vmcb_seg es;
    struct vmcb_seg cs;
    struct vmcb_seg ss;
    struct vmcb_seg ds;
    struct vmcb_seg fs;
    struct vmcb_seg gs;
    struct vmcb_seg gdtr;
    struct vmcb_seg ldtr;
    struct vmcb_seg idtr;
    struct vmcb_seg tr;
    u64 vmpl0_ssp;
    u64 vmpl1_ssp;
    u64 vmpl2_ssp;
    u64 vmpl3_ssp;
    u64 u_cet;
    u8[2] reserved_1;
    u8 vmpl;
    u8 cpl;
    u8[4] reserved_2;
    u64 efer;
    u8[104] reserved_3;
    u64 xss;
    u64 cr4;
    u64 cr3;
    u64 cr0;
    u64 dr7;
    u64 dr6;
    u64 rflags;
    u64 rip;
    u64 dr0;
    u64 dr1;
    u64 dr2;
    u64 dr3;
    u64 dr0_addr_mask;
    u64 dr1_addr_mask;
    u64 dr2_addr_mask;
    u64 dr3_addr_mask;
    u8[24] reserved_4;
    u64 rsp;
    u64 s_cet;
    u64 ssp;
    u64 isst_addr;
    u64 rax;
    u64 star;
    u64 lstar;
    u64 cstar;
    u64 sfmask;
    u64 kernel_gs_base;
    u64 sysenter_cs;
    u64 sysenter_esp;
    u64 sysenter_eip;
    u64 cr2;
    u8[32] reserved_5;
    u64 g_pat;
    u64 dbgctl;
    u64 br_from;
    u64 br_to;
    u64 last_excp_from;
    u64 last_excp_to;
    u8[80] reserved_7;
    u32 pkru;
    u8[20] reserved_8;
    u64 reserved_9;
    u64 rcx;
    u64 rdx;
    u64 rbx;
    u64 reserved_10;
    u64 rbp;
    u64 rsi;
    u64 rdi;
    u64 r8;
    u64 r9;
    u64 r10;
    u64 r11;
    u64 r12;
    u64 r13;
    u64 r14;
    u64 r15;
    u8[16] reserved_11;
    u64 guest_exit_info_1;
    u64 guest_exit_info_2;
    u64 guest_exit_int_info;
    u64 guest_nrip;
    u64 sev_features;
    u64 vintr_ctrl;
    u64 guest_exit_code;
    u64 virtual_tom;
    u64 tlb_id;
    u64 pcpu_id;
    u64 event_inj;
    u64 xcr0;
    u8[16] reserved_12;
    u64 x87_dp;
    u32 mxcsr;
    u16 x87_ftw;
    u16 x87_fsw;
    u16 x87_fcw;
    u16 x87_fop;
    u16 x87_ds;
    u16 x87_cs;
    u64 x87_rip;
    u8[80] fpreg_x87;
    u8[256] fpreg_xmm;
    u8[256] fpreg_ymm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct sev_es_save_area {
    struct vmcb_seg es;
    struct vmcb_seg cs;
    struct vmcb_seg ss;
    struct vmcb_seg ds;
    struct vmcb_seg fs;
    struct vmcb_seg gs;
    struct vmcb_seg gdtr;
    struct vmcb_seg ldtr;
    struct vmcb_seg idtr;
    struct vmcb_seg tr;
    u64 vmpl0_ssp;
    u64 vmpl1_ssp;
    u64 vmpl2_ssp;
    u64 vmpl3_ssp;
    u64 u_cet;
    u8[2] reserved_0xc8;
    u8 vmpl;
    u8 cpl;
    u8[4] reserved_0xcc;
    u64 efer;
    u8[104] reserved_0xd8;
    u64 xss;
    u64 cr4;
    u64 cr3;
    u64 cr0;
    u64 dr7;
    u64 dr6;
    u64 rflags;
    u64 rip;
    u64 dr0;
    u64 dr1;
    u64 dr2;
    u64 dr3;
    u64 dr0_addr_mask;
    u64 dr1_addr_mask;
    u64 dr2_addr_mask;
    u64 dr3_addr_mask;
    u8[24] reserved_0x1c0;
    u64 rsp;
    u64 s_cet;
    u64 ssp;
    u64 isst_addr;
    u64 rax;
    u64 star;
    u64 lstar;
    u64 cstar;
    u64 sfmask;
    u64 kernel_gs_base;
    u64 sysenter_cs;
    u64 sysenter_esp;
    u64 sysenter_eip;
    u64 cr2;
    u8[32] reserved_0x248;
    u64 g_pat;
    u64 dbgctl;
    u64 br_from;
    u64 br_to;
    u64 last_excp_from;
    u64 last_excp_to;
    u8[80] reserved_0x298;
    u32 pkru;
    u32 tsc_aux;
    u8[24] reserved_0x2f0;
    u64 rcx;
    u64 rdx;
    u64 rbx;
    u64 reserved_0x320;
    u64 rbp;
    u64 rsi;
    u64 rdi;
    u64 r8;
    u64 r9;
    u64 r10;
    u64 r11;
    u64 r12;
    u64 r13;
    u64 r14;
    u64 r15;
    u8[16] reserved_0x380;
    u64 guest_exit_info_1;
    u64 guest_exit_info_2;
    u64 guest_exit_int_info;
    u64 guest_nrip;
    u64 sev_features;
    u64 vintr_ctrl;
    u64 guest_exit_code;
    u64 virtual_tom;
    u64 tlb_id;
    u64 pcpu_id;
    u64 event_inj;
    u64 xcr0;
    u8[16] reserved_0x3f0;
    u64 x87_dp;
    u32 mxcsr;
    u16 x87_ftw;
    u16 x87_fsw;
    u16 x87_fcw;
    u16 x87_fop;
    u16 x87_ds;
    u16 x87_cs;
    u64 x87_rip;
    u8[80] fpreg_x87;
    u8[256] fpreg_xmm;
    u8[256] fpreg_ymm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct sev_es_save_area {
    struct vmcb_seg es;
    struct vmcb_seg cs;
    struct vmcb_seg ss;
    struct vmcb_seg ds;
    struct vmcb_seg fs;
    struct vmcb_seg gs;
    struct vmcb_seg gdtr;
    struct vmcb_seg ldtr;
    struct vmcb_seg idtr;
    struct vmcb_seg tr;
    u64 vmpl0_ssp;
    u64 vmpl1_ssp;
    u64 vmpl2_ssp;
    u64 vmpl3_ssp;
    u64 u_cet;
    u8[2] reserved_0xc8;
    u8 vmpl;
    u8 cpl;
    u8[4] reserved_0xcc;
    u64 efer;
    u8[104] reserved_0xd8;
    u64 xss;
    u64 cr4;
    u64 cr3;
    u64 cr0;
    u64 dr7;
    u64 dr6;
    u64 rflags;
    u64 rip;
    u64 dr0;
    u64 dr1;
    u64 dr2;
    u64 dr3;
    u64 dr0_addr_mask;
    u64 dr1_addr_mask;
    u64 dr2_addr_mask;
    u64 dr3_addr_mask;
    u8[24] reserved_0x1c0;
    u64 rsp;
    u64 s_cet;
    u64 ssp;
    u64 isst_addr;
    u64 rax;
    u64 star;
    u64 lstar;
    u64 cstar;
    u64 sfmask;
    u64 kernel_gs_base;
    u64 sysenter_cs;
    u64 sysenter_esp;
    u64 sysenter_eip;
    u64 cr2;
    u8[32] reserved_0x248;
    u64 g_pat;
    u64 dbgctl;
    u64 br_from;
    u64 br_to;
    u64 last_excp_from;
    u64 last_excp_to;
    u8[80] reserved_0x298;
    u32 pkru;
    u32 tsc_aux;
    u8[24] reserved_0x2f0;
    u64 rcx;
    u64 rdx;
    u64 rbx;
    u64 reserved_0x320;
    u64 rbp;
    u64 rsi;
    u64 rdi;
    u64 r8;
    u64 r9;
    u64 r10;
    u64 r11;
    u64 r12;
    u64 r13;
    u64 r14;
    u64 r15;
    u8[16] reserved_0x380;
    u64 guest_exit_info_1;
    u64 guest_exit_info_2;
    u64 guest_exit_int_info;
    u64 guest_nrip;
    u64 sev_features;
    u64 vintr_ctrl;
    u64 guest_exit_code;
    u64 virtual_tom;
    u64 tlb_id;
    u64 pcpu_id;
    u64 event_inj;
    u64 xcr0;
    u8[16] reserved_0x3f0;
    u64 x87_dp;
    u32 mxcsr;
    u16 x87_ftw;
    u16 x87_fsw;
    u16 x87_fcw;
    u16 x87_fop;
    u16 x87_ds;
    u16 x87_cs;
    u64 x87_rip;
    u8[80] fpreg_x87;
    u8[256] fpreg_xmm;
    u8[256] fpreg_ymm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct sev_es_save_area {
    struct vmcb_seg es;
    struct vmcb_seg cs;
    struct vmcb_seg ss;
    struct vmcb_seg ds;
    struct vmcb_seg fs;
    struct vmcb_seg gs;
    struct vmcb_seg gdtr;
    struct vmcb_seg ldtr;
    struct vmcb_seg idtr;
    struct vmcb_seg tr;
    u64 vmpl0_ssp;
    u64 vmpl1_ssp;
    u64 vmpl2_ssp;
    u64 vmpl3_ssp;
    u64 u_cet;
    u8[2] reserved_0xc8;
    u8 vmpl;
    u8 cpl;
    u8[4] reserved_0xcc;
    u64 efer;
    u8[104] reserved_0xd8;
    u64 xss;
    u64 cr4;
    u64 cr3;
    u64 cr0;
    u64 dr7;
    u64 dr6;
    u64 rflags;
    u64 rip;
    u64 dr0;
    u64 dr1;
    u64 dr2;
    u64 dr3;
    u64 dr0_addr_mask;
    u64 dr1_addr_mask;
    u64 dr2_addr_mask;
    u64 dr3_addr_mask;
    u8[24] reserved_0x1c0;
    u64 rsp;
    u64 s_cet;
    u64 ssp;
    u64 isst_addr;
    u64 rax;
    u64 star;
    u64 lstar;
    u64 cstar;
    u64 sfmask;
    u64 kernel_gs_base;
    u64 sysenter_cs;
    u64 sysenter_esp;
    u64 sysenter_eip;
    u64 cr2;
    u8[32] reserved_0x248;
    u64 g_pat;
    u64 dbgctl;
    u64 br_from;
    u64 br_to;
    u64 last_excp_from;
    u64 last_excp_to;
    u8[80] reserved_0x298;
    u32 pkru;
    u32 tsc_aux;
    u8[24] reserved_0x2f0;
    u64 rcx;
    u64 rdx;
    u64 rbx;
    u64 reserved_0x320;
    u64 rbp;
    u64 rsi;
    u64 rdi;
    u64 r8;
    u64 r9;
    u64 r10;
    u64 r11;
    u64 r12;
    u64 r13;
    u64 r14;
    u64 r15;
    u8[16] reserved_0x380;
    u64 guest_exit_info_1;
    u64 guest_exit_info_2;
    u64 guest_exit_int_info;
    u64 guest_nrip;
    u64 sev_features;
    u64 vintr_ctrl;
    u64 guest_exit_code;
    u64 virtual_tom;
    u64 tlb_id;
    u64 pcpu_id;
    u64 event_inj;
    u64 xcr0;
    u8[16] reserved_0x3f0;
    u64 x87_dp;
    u32 mxcsr;
    u16 x87_ftw;
    u16 x87_fsw;
    u16 x87_fcw;
    u16 x87_fop;
    u16 x87_ds;
    u16 x87_cs;
    u64 x87_rip;
    u8[80] fpreg_x87;
    u8[256] fpreg_xmm;
    u8[256] fpreg_ymm;
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct sev_es_save_area {
    struct vmcb_seg es;
    struct vmcb_seg cs;
    struct vmcb_seg ss;
    struct vmcb_seg ds;
    struct vmcb_seg fs;
    struct vmcb_seg gs;
    struct vmcb_seg gdtr;
    struct vmcb_seg ldtr;
    struct vmcb_seg idtr;
    struct vmcb_seg tr;
    u64 vmpl0_ssp;
    u64 vmpl1_ssp;
    u64 vmpl2_ssp;
    u64 vmpl3_ssp;
    u64 u_cet;
    u8[2] reserved_1;
    u8 vmpl;
    u8 cpl;
    u8[4] reserved_2;
    u64 efer;
    u8[104] reserved_3;
    u64 xss;
    u64 cr4;
    u64 cr3;
    u64 cr0;
    u64 dr7;
    u64 dr6;
    u64 rflags;
    u64 rip;
    u64 dr0;
    u64 dr1;
    u64 dr2;
    u64 dr3;
    u64 dr0_addr_mask;
    u64 dr1_addr_mask;
    u64 dr2_addr_mask;
    u64 dr3_addr_mask;
    u8[24] reserved_4;
    u64 rsp;
    u64 s_cet;
    u64 ssp;
    u64 isst_addr;
    u64 rax;
    u64 star;
    u64 lstar;
    u64 cstar;
    u64 sfmask;
    u64 kernel_gs_base;
    u64 sysenter_cs;
    u64 sysenter_esp;
    u64 sysenter_eip;
    u64 cr2;
    u8[32] reserved_5;
    u64 g_pat;
    u64 dbgctl;
    u64 br_from;
    u64 br_to;
    u64 last_excp_from;
    u64 last_excp_to;
    u8[80] reserved_7;
    u32 pkru;
    u8[20] reserved_8;
    u64 reserved_9;
    u64 rcx;
    u64 rdx;
    u64 rbx;
    u64 reserved_10;
    u64 rbp;
    u64 rsi;
    u64 rdi;
    u64 r8;
    u64 r9;
    u64 r10;
    u64 r11;
    u64 r12;
    u64 r13;
    u64 r14;
    u64 r15;
    u8[16] reserved_11;
    u64 guest_exit_info_1;
    u64 guest_exit_info_2;
    u64 guest_exit_int_info;
    u64 guest_nrip;
    u64 sev_features;
    u64 vintr_ctrl;
    u64 guest_exit_code;
    u64 virtual_tom;
    u64 tlb_id;
    u64 pcpu_id;
    u64 event_inj;
    u64 xcr0;
    u8[16] reserved_12;
    u64 x87_dp;
    u32 mxcsr;
    u16 x87_ftw;
    u16 x87_fsw;
    u16 x87_fcw;
    u16 x87_fop;
    u16 x87_ds;
    u16 x87_cs;
    u64 x87_rip;
    u8[80] fpreg_x87;
    u8[256] fpreg_xmm;
    u8[256] fpreg_ymm;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8[2] reserved_0xc8</code>
</li>
<li>
<b>Field added. </b>
<code>u8[4] reserved_0xcc</code>
</li>
<li>
<b>Field added. </b>
<code>u8[104] reserved_0xd8</code>
</li>
<li>
<b>Field added. </b>
<code>u8[24] reserved_0x1c0</code>
</li>
<li>
<b>Field added. </b>
<code>u8[32] reserved_0x248</code>
</li>
<li>
<b>Field added. </b>
<code>u8[80] reserved_0x298</code>
</li>
<li>
<b>Field added. </b>
<code>u32 tsc_aux</code>
</li>
<li>
<b>Field added. </b>
<code>u8[24] reserved_0x2f0</code>
</li>
<li>
<b>Field added. </b>
<code>u64 reserved_0x320</code>
</li>
<li>
<b>Field added. </b>
<code>u8[16] reserved_0x380</code>
</li>
<li>
<b>Field added. </b>
<code>u8[16] reserved_0x3f0</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[2] reserved_1</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[4] reserved_2</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[104] reserved_3</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[24] reserved_4</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[32] reserved_5</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[80] reserved_7</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[20] reserved_8</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 reserved_9</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 reserved_10</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[16] reserved_11</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[16] reserved_12</code>
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
