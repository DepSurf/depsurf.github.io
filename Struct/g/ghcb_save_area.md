# Struct: <code>ghcb_save_area</code>

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
struct ghcb_save_area {
    u8[203] reserved_1;
    u8 cpl;
    u8[116] reserved_2;
    u64 xss;
    u8[24] reserved_3;
    u64 dr7;
    u8[16] reserved_4;
    u64 rip;
    u8[88] reserved_5;
    u64 rsp;
    u8[24] reserved_6;
    u64 rax;
    u8[264] reserved_7;
    u64 rcx;
    u64 rdx;
    u64 rbx;
    u8[8] reserved_8;
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
    u8[16] reserved_9;
    u64 sw_exit_code;
    u64 sw_exit_info_1;
    u64 sw_exit_info_2;
    u64 sw_scratch;
    u8[56] reserved_10;
    u64 xcr0;
    u8[16] valid_bitmap;
    u64 x87_state_gpa;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ghcb_save_area {
    u8[203] reserved_0x0;
    u8 cpl;
    u8[116] reserved_0xcc;
    u64 xss;
    u8[24] reserved_0x148;
    u64 dr7;
    u8[16] reserved_0x168;
    u64 rip;
    u8[88] reserved_0x180;
    u64 rsp;
    u8[24] reserved_0x1e0;
    u64 rax;
    u8[264] reserved_0x200;
    u64 rcx;
    u64 rdx;
    u64 rbx;
    u8[8] reserved_0x320;
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
    u64 sw_exit_code;
    u64 sw_exit_info_1;
    u64 sw_exit_info_2;
    u64 sw_scratch;
    u8[56] reserved_0x3b0;
    u64 xcr0;
    u8[16] valid_bitmap;
    u64 x87_state_gpa;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ghcb_save_area {
    u8[203] reserved_0x0;
    u8 cpl;
    u8[116] reserved_0xcc;
    u64 xss;
    u8[24] reserved_0x148;
    u64 dr7;
    u8[16] reserved_0x168;
    u64 rip;
    u8[88] reserved_0x180;
    u64 rsp;
    u8[24] reserved_0x1e0;
    u64 rax;
    u8[264] reserved_0x200;
    u64 rcx;
    u64 rdx;
    u64 rbx;
    u8[8] reserved_0x320;
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
    u64 sw_exit_code;
    u64 sw_exit_info_1;
    u64 sw_exit_info_2;
    u64 sw_scratch;
    u8[56] reserved_0x3b0;
    u64 xcr0;
    u8[16] valid_bitmap;
    u64 x87_state_gpa;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ghcb_save_area {
    u8[203] reserved_0x0;
    u8 cpl;
    u8[116] reserved_0xcc;
    u64 xss;
    u8[24] reserved_0x148;
    u64 dr7;
    u8[16] reserved_0x168;
    u64 rip;
    u8[88] reserved_0x180;
    u64 rsp;
    u8[24] reserved_0x1e0;
    u64 rax;
    u8[264] reserved_0x200;
    u64 rcx;
    u64 rdx;
    u64 rbx;
    u8[8] reserved_0x320;
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
    u64 sw_exit_code;
    u64 sw_exit_info_1;
    u64 sw_exit_info_2;
    u64 sw_scratch;
    u8[56] reserved_0x3b0;
    u64 xcr0;
    u8[16] valid_bitmap;
    u64 x87_state_gpa;
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
struct ghcb_save_area {
    u8[203] reserved_1;
    u8 cpl;
    u8[116] reserved_2;
    u64 xss;
    u8[24] reserved_3;
    u64 dr7;
    u8[16] reserved_4;
    u64 rip;
    u8[88] reserved_5;
    u64 rsp;
    u8[24] reserved_6;
    u64 rax;
    u8[264] reserved_7;
    u64 rcx;
    u64 rdx;
    u64 rbx;
    u8[8] reserved_8;
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
    u8[16] reserved_9;
    u64 sw_exit_code;
    u64 sw_exit_info_1;
    u64 sw_exit_info_2;
    u64 sw_scratch;
    u8[56] reserved_10;
    u64 xcr0;
    u8[16] valid_bitmap;
    u64 x87_state_gpa;
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
<code>u8[203] reserved_0x0</code>
</li>
<li>
<b>Field added. </b>
<code>u8[116] reserved_0xcc</code>
</li>
<li>
<b>Field added. </b>
<code>u8[24] reserved_0x148</code>
</li>
<li>
<b>Field added. </b>
<code>u8[16] reserved_0x168</code>
</li>
<li>
<b>Field added. </b>
<code>u8[88] reserved_0x180</code>
</li>
<li>
<b>Field added. </b>
<code>u8[24] reserved_0x1e0</code>
</li>
<li>
<b>Field added. </b>
<code>u8[264] reserved_0x200</code>
</li>
<li>
<b>Field added. </b>
<code>u8[8] reserved_0x320</code>
</li>
<li>
<b>Field added. </b>
<code>u8[16] reserved_0x380</code>
</li>
<li>
<b>Field added. </b>
<code>u8[56] reserved_0x3b0</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[203] reserved_1</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[116] reserved_2</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[24] reserved_3</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[16] reserved_4</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[88] reserved_5</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[24] reserved_6</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[264] reserved_7</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[8] reserved_8</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[16] reserved_9</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[56] reserved_10</code>
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
