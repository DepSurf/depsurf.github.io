# Struct: <code>user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct user {
    struct user_regs_struct regs;
    int u_fpvalid;
    int pad0;
    struct user_i387_struct i387;
    long unsigned int u_tsize;
    long unsigned int u_dsize;
    long unsigned int u_ssize;
    long unsigned int start_code;
    long unsigned int start_stack;
    long int signal;
    int reserved;
    int pad1;
    long unsigned int u_ar0;
    struct user_i387_struct * u_fpstate;
    long unsigned int magic;
    char[32] u_comm;
    long unsigned int[8] u_debugreg;
    long unsigned int error_code;
    long unsigned int fault_address;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct user {
    struct user_regs_struct regs;
    int u_fpvalid;
    int pad0;
    struct user_i387_struct i387;
    long unsigned int u_tsize;
    long unsigned int u_dsize;
    long unsigned int u_ssize;
    long unsigned int start_code;
    long unsigned int start_stack;
    long int signal;
    int reserved;
    int pad1;
    long unsigned int u_ar0;
    struct user_i387_struct * u_fpstate;
    long unsigned int magic;
    char[32] u_comm;
    long unsigned int[8] u_debugreg;
    long unsigned int error_code;
    long unsigned int fault_address;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct user {
    struct user_regs_struct regs;
    int u_fpvalid;
    int pad0;
    struct user_i387_struct i387;
    long unsigned int u_tsize;
    long unsigned int u_dsize;
    long unsigned int u_ssize;
    long unsigned int start_code;
    long unsigned int start_stack;
    long int signal;
    int reserved;
    int pad1;
    long unsigned int u_ar0;
    struct user_i387_struct * u_fpstate;
    long unsigned int magic;
    char[32] u_comm;
    long unsigned int[8] u_debugreg;
    long unsigned int error_code;
    long unsigned int fault_address;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct user {
    struct user_regs_struct regs;
    int u_fpvalid;
    int pad0;
    struct user_i387_struct i387;
    long unsigned int u_tsize;
    long unsigned int u_dsize;
    long unsigned int u_ssize;
    long unsigned int start_code;
    long unsigned int start_stack;
    long int signal;
    int reserved;
    int pad1;
    long unsigned int u_ar0;
    struct user_i387_struct * u_fpstate;
    long unsigned int magic;
    char[32] u_comm;
    long unsigned int[8] u_debugreg;
    long unsigned int error_code;
    long unsigned int fault_address;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct user {
    struct user_regs_struct regs;
    int u_fpvalid;
    int pad0;
    struct user_i387_struct i387;
    long unsigned int u_tsize;
    long unsigned int u_dsize;
    long unsigned int u_ssize;
    long unsigned int start_code;
    long unsigned int start_stack;
    long int signal;
    int reserved;
    int pad1;
    long unsigned int u_ar0;
    struct user_i387_struct * u_fpstate;
    long unsigned int magic;
    char[32] u_comm;
    long unsigned int[8] u_debugreg;
    long unsigned int error_code;
    long unsigned int fault_address;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct user {
    struct user_regs_struct regs;
    int u_fpvalid;
    int pad0;
    struct user_i387_struct i387;
    long unsigned int u_tsize;
    long unsigned int u_dsize;
    long unsigned int u_ssize;
    long unsigned int start_code;
    long unsigned int start_stack;
    long int signal;
    int reserved;
    int pad1;
    long unsigned int u_ar0;
    struct user_i387_struct * u_fpstate;
    long unsigned int magic;
    char[32] u_comm;
    long unsigned int[8] u_debugreg;
    long unsigned int error_code;
    long unsigned int fault_address;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct user {
    struct user_regs_struct regs;
    int u_fpvalid;
    int pad0;
    struct user_i387_struct i387;
    long unsigned int u_tsize;
    long unsigned int u_dsize;
    long unsigned int u_ssize;
    long unsigned int start_code;
    long unsigned int start_stack;
    long int signal;
    int reserved;
    int pad1;
    long unsigned int u_ar0;
    struct user_i387_struct * u_fpstate;
    long unsigned int magic;
    char[32] u_comm;
    long unsigned int[8] u_debugreg;
    long unsigned int error_code;
    long unsigned int fault_address;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct user {
    struct user_regs_struct regs;
    int u_fpvalid;
    int pad0;
    struct user_i387_struct i387;
    long unsigned int u_tsize;
    long unsigned int u_dsize;
    long unsigned int u_ssize;
    long unsigned int start_code;
    long unsigned int start_stack;
    long int signal;
    int reserved;
    int pad1;
    long unsigned int u_ar0;
    struct user_i387_struct * u_fpstate;
    long unsigned int magic;
    char[32] u_comm;
    long unsigned int[8] u_debugreg;
    long unsigned int error_code;
    long unsigned int fault_address;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct user {
    struct user_regs_struct regs;
    int u_fpvalid;
    int pad0;
    struct user_i387_struct i387;
    long unsigned int u_tsize;
    long unsigned int u_dsize;
    long unsigned int u_ssize;
    long unsigned int start_code;
    long unsigned int start_stack;
    long int signal;
    int reserved;
    int pad1;
    long unsigned int u_ar0;
    struct user_i387_struct * u_fpstate;
    long unsigned int magic;
    char[32] u_comm;
    long unsigned int[8] u_debugreg;
    long unsigned int error_code;
    long unsigned int fault_address;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct user {
    struct user_regs_struct regs;
    int u_fpvalid;
    int pad0;
    struct user_i387_struct i387;
    long unsigned int u_tsize;
    long unsigned int u_dsize;
    long unsigned int u_ssize;
    long unsigned int start_code;
    long unsigned int start_stack;
    long int signal;
    int reserved;
    int pad1;
    long unsigned int u_ar0;
    struct user_i387_struct * u_fpstate;
    long unsigned int magic;
    char[32] u_comm;
    long unsigned int[8] u_debugreg;
    long unsigned int error_code;
    long unsigned int fault_address;
}
```
</details>
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
struct user {
    struct user_regs_struct regs;
    int u_fpvalid;
    int pad0;
    struct user_i387_struct i387;
    long unsigned int u_tsize;
    long unsigned int u_dsize;
    long unsigned int u_ssize;
    long unsigned int start_code;
    long unsigned int start_stack;
    long int signal;
    int reserved;
    int pad1;
    long unsigned int u_ar0;
    struct user_i387_struct * u_fpstate;
    long unsigned int magic;
    char[32] u_comm;
    long unsigned int[8] u_debugreg;
    long unsigned int error_code;
    long unsigned int fault_address;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct user {
    struct user_regs_struct regs;
    int u_fpvalid;
    int pad0;
    struct user_i387_struct i387;
    long unsigned int u_tsize;
    long unsigned int u_dsize;
    long unsigned int u_ssize;
    long unsigned int start_code;
    long unsigned int start_stack;
    long int signal;
    int reserved;
    int pad1;
    long unsigned int u_ar0;
    struct user_i387_struct * u_fpstate;
    long unsigned int magic;
    char[32] u_comm;
    long unsigned int[8] u_debugreg;
    long unsigned int error_code;
    long unsigned int fault_address;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct user {
    struct user_regs_struct regs;
    int u_fpvalid;
    int pad0;
    struct user_i387_struct i387;
    long unsigned int u_tsize;
    long unsigned int u_dsize;
    long unsigned int u_ssize;
    long unsigned int start_code;
    long unsigned int start_stack;
    long int signal;
    int reserved;
    int pad1;
    long unsigned int u_ar0;
    struct user_i387_struct * u_fpstate;
    long unsigned int magic;
    char[32] u_comm;
    long unsigned int[8] u_debugreg;
    long unsigned int error_code;
    long unsigned int fault_address;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct user {
    struct user_regs_struct regs;
    int u_fpvalid;
    int pad0;
    struct user_i387_struct i387;
    long unsigned int u_tsize;
    long unsigned int u_dsize;
    long unsigned int u_ssize;
    long unsigned int start_code;
    long unsigned int start_stack;
    long int signal;
    int reserved;
    int pad1;
    long unsigned int u_ar0;
    struct user_i387_struct * u_fpstate;
    long unsigned int magic;
    char[32] u_comm;
    long unsigned int[8] u_debugreg;
    long unsigned int error_code;
    long unsigned int fault_address;
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
struct user {
    struct user_regs_struct regs;
    int u_fpvalid;
    int pad0;
    struct user_i387_struct i387;
    long unsigned int u_tsize;
    long unsigned int u_dsize;
    long unsigned int u_ssize;
    long unsigned int start_code;
    long unsigned int start_stack;
    long int signal;
    int reserved;
    int pad1;
    long unsigned int u_ar0;
    struct user_i387_struct * u_fpstate;
    long unsigned int magic;
    char[32] u_comm;
    long unsigned int[8] u_debugreg;
    long unsigned int error_code;
    long unsigned int fault_address;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct user {
    struct user_regs_struct regs;
    int u_fpvalid;
    int pad0;
    struct user_i387_struct i387;
    long unsigned int u_tsize;
    long unsigned int u_dsize;
    long unsigned int u_ssize;
    long unsigned int start_code;
    long unsigned int start_stack;
    long int signal;
    int reserved;
    int pad1;
    long unsigned int u_ar0;
    struct user_i387_struct * u_fpstate;
    long unsigned int magic;
    char[32] u_comm;
    long unsigned int[8] u_debugreg;
    long unsigned int error_code;
    long unsigned int fault_address;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct user {
    struct user_regs_struct regs;
    int u_fpvalid;
    int pad0;
    struct user_i387_struct i387;
    long unsigned int u_tsize;
    long unsigned int u_dsize;
    long unsigned int u_ssize;
    long unsigned int start_code;
    long unsigned int start_stack;
    long int signal;
    int reserved;
    int pad1;
    long unsigned int u_ar0;
    struct user_i387_struct * u_fpstate;
    long unsigned int magic;
    char[32] u_comm;
    long unsigned int[8] u_debugreg;
    long unsigned int error_code;
    long unsigned int fault_address;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct user {
    struct user_regs_struct regs;
    int u_fpvalid;
    int pad0;
    struct user_i387_struct i387;
    long unsigned int u_tsize;
    long unsigned int u_dsize;
    long unsigned int u_ssize;
    long unsigned int start_code;
    long unsigned int start_stack;
    long int signal;
    int reserved;
    int pad1;
    long unsigned int u_ar0;
    struct user_i387_struct * u_fpstate;
    long unsigned int magic;
    char[32] u_comm;
    long unsigned int[8] u_debugreg;
    long unsigned int error_code;
    long unsigned int fault_address;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct user {
    struct user_regs_struct regs;
    int u_fpvalid;
    int pad0;
    struct user_i387_struct i387;
    long unsigned int u_tsize;
    long unsigned int u_dsize;
    long unsigned int u_ssize;
    long unsigned int start_code;
    long unsigned int start_stack;
    long int signal;
    int reserved;
    int pad1;
    long unsigned int u_ar0;
    struct user_i387_struct * u_fpstate;
    long unsigned int magic;
    char[32] u_comm;
    long unsigned int[8] u_debugreg;
    long unsigned int error_code;
    long unsigned int fault_address;
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
