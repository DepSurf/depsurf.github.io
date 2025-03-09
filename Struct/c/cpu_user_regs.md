# Struct: <code>cpu_user_regs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
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
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
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
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
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
struct cpu_user_regs {
    uint64_t r15;
    uint64_t r14;
    uint64_t r13;
    uint64_t r12;
    uint64_t rbp;
    uint64_t ebp;
    uint32_t _ebp;
    uint64_t rbx;
    uint64_t ebx;
    uint32_t _ebx;
    uint64_t r11;
    uint64_t r10;
    uint64_t r9;
    uint64_t r8;
    uint64_t rax;
    uint64_t eax;
    uint32_t _eax;
    uint64_t rcx;
    uint64_t ecx;
    uint32_t _ecx;
    uint64_t rdx;
    uint64_t edx;
    uint32_t _edx;
    uint64_t rsi;
    uint64_t esi;
    uint32_t _esi;
    uint64_t rdi;
    uint64_t edi;
    uint32_t _edi;
    uint32_t error_code;
    uint32_t entry_vector;
    uint64_t rip;
    uint64_t eip;
    uint32_t _eip;
    uint16_t cs;
    uint16_t[1] _pad0;
    uint8_t saved_upcall_mask;
    uint8_t[3] _pad1;
    uint64_t rflags;
    uint64_t eflags;
    uint32_t _eflags;
    uint64_t rsp;
    uint64_t esp;
    uint32_t _esp;
    uint16_t ss;
    uint16_t[3] _pad2;
    uint16_t es;
    uint16_t[3] _pad3;
    uint16_t ds;
    uint16_t[3] _pad4;
    uint16_t fs;
    uint16_t[3] _pad5;
    uint16_t gs;
    uint16_t[3] _pad6;
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
