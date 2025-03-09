# Struct: <code>crb_priv</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct crb_priv {
    u32 sm;
    const char * hid;
    void * iobase;
    struct crb_regs_head * regs_h;
    struct crb_regs_tail * regs_t;
    u8 * cmd;
    u8 * rsp;
    u32 cmd_size;
    u32 smc_func_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct crb_priv {
    u32 sm;
    const char * hid;
    void * iobase;
    struct crb_regs_head * regs_h;
    struct crb_regs_tail * regs_t;
    u8 * cmd;
    u8 * rsp;
    u32 cmd_size;
    u32 smc_func_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct crb_priv {
    u32 sm;
    const char * hid;
    void * iobase;
    struct crb_regs_head * regs_h;
    struct crb_regs_tail * regs_t;
    u8 * cmd;
    u8 * rsp;
    u32 cmd_size;
    u32 smc_func_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct crb_priv {
    u32 sm;
    const char * hid;
    void * iobase;
    struct crb_regs_head * regs_h;
    struct crb_regs_tail * regs_t;
    u8 * cmd;
    u8 * rsp;
    u32 cmd_size;
    u32 smc_func_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct crb_priv {
    u32 sm;
    const char * hid;
    struct crb_regs_head * regs_h;
    struct crb_regs_tail * regs_t;
    u8 * cmd;
    u8 * rsp;
    u32 cmd_size;
    u32 smc_func_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct crb_priv {
    u32 sm;
    const char * hid;
    struct crb_regs_head * regs_h;
    struct crb_regs_tail * regs_t;
    u8 * cmd;
    u8 * rsp;
    u32 cmd_size;
    u32 smc_func_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct crb_priv {
    u32 sm;
    const char * hid;
    struct crb_regs_head * regs_h;
    struct crb_regs_tail * regs_t;
    u8 * cmd;
    u8 * rsp;
    u32 cmd_size;
    u32 smc_func_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct crb_priv {
    u32 sm;
    const char * hid;
    struct crb_regs_head * regs_h;
    struct crb_regs_tail * regs_t;
    u8 * cmd;
    u8 * rsp;
    u32 cmd_size;
    u32 smc_func_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct crb_priv {
    u32 sm;
    const char * hid;
    struct crb_regs_head * regs_h;
    struct crb_regs_tail * regs_t;
    u8 * cmd;
    u8 * rsp;
    u32 cmd_size;
    u32 smc_func_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct crb_priv {
    u32 sm;
    const char * hid;
    struct crb_regs_head * regs_h;
    struct crb_regs_tail * regs_t;
    u8 * cmd;
    u8 * rsp;
    u32 cmd_size;
    u32 smc_func_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct crb_priv {
    u32 sm;
    const char * hid;
    struct crb_regs_head * regs_h;
    struct crb_regs_tail * regs_t;
    u8 * cmd;
    u8 * rsp;
    u32 cmd_size;
    u32 smc_func_id;
    u32 * pluton_start_addr;
    u32 * pluton_reply_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct crb_priv {
    u32 sm;
    const char * hid;
    struct crb_regs_head * regs_h;
    struct crb_regs_tail * regs_t;
    u8 * cmd;
    u8 * rsp;
    u32 cmd_size;
    u32 smc_func_id;
    u32 * pluton_start_addr;
    u32 * pluton_reply_addr;
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
struct crb_priv {
    u32 sm;
    const char * hid;
    void * iobase;
    struct crb_regs_head * regs_h;
    struct crb_regs_tail * regs_t;
    u8 * cmd;
    u8 * rsp;
    u32 cmd_size;
    u32 smc_func_id;
}
```
</details>
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
struct crb_priv {
    u32 sm;
    const char * hid;
    void * iobase;
    struct crb_regs_head * regs_h;
    struct crb_regs_tail * regs_t;
    u8 * cmd;
    u8 * rsp;
    u32 cmd_size;
    u32 smc_func_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct crb_priv {
    u32 sm;
    const char * hid;
    void * iobase;
    struct crb_regs_head * regs_h;
    struct crb_regs_tail * regs_t;
    u8 * cmd;
    u8 * rsp;
    u32 cmd_size;
    u32 smc_func_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct crb_priv {
    u32 sm;
    const char * hid;
    void * iobase;
    struct crb_regs_head * regs_h;
    struct crb_regs_tail * regs_t;
    u8 * cmd;
    u8 * rsp;
    u32 cmd_size;
    u32 smc_func_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct crb_priv {
    u32 sm;
    const char * hid;
    void * iobase;
    struct crb_regs_head * regs_h;
    struct crb_regs_tail * regs_t;
    u8 * cmd;
    u8 * rsp;
    u32 cmd_size;
    u32 smc_func_id;
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct crb_priv {
    u32 sm;
    const char * hid;
    void * iobase;
    struct crb_regs_head * regs_h;
    struct crb_regs_tail * regs_t;
    u8 * cmd;
    u8 * rsp;
    u32 cmd_size;
    u32 smc_func_id;
}
```
</details>
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
<b>Field removed. </b>
<code>void * iobase</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 * pluton_start_addr</code>
</li>
<li>
<b>Field added. </b>
<code>u32 * pluton_reply_addr</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct crb_priv {
    u32 sm;
    const char * hid;
    void * iobase;
    struct crb_regs_head * regs_h;
    struct crb_regs_tail * regs_t;
    u8 * cmd;
    u8 * rsp;
    u32 cmd_size;
    u32 smc_func_id;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct crb_priv {
    u32 sm;
    const char * hid;
    void * iobase;
    struct crb_regs_head * regs_h;
    struct crb_regs_tail * regs_t;
    u8 * cmd;
    u8 * rsp;
    u32 cmd_size;
    u32 smc_func_id;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct crb_priv {
    u32 sm;
    const char * hid;
    void * iobase;
    struct crb_regs_head * regs_h;
    struct crb_regs_tail * regs_t;
    u8 * cmd;
    u8 * rsp;
    u32 cmd_size;
    u32 smc_func_id;
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
