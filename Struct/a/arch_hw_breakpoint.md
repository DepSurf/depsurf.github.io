# Struct: <code>arch_hw_breakpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    long unsigned int mask;
    u8 len;
    u8 type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    long unsigned int mask;
    u8 len;
    u8 type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    long unsigned int mask;
    u8 len;
    u8 type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    long unsigned int mask;
    u8 len;
    u8 type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    long unsigned int mask;
    u8 len;
    u8 type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    long unsigned int mask;
    u8 len;
    u8 type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    long unsigned int mask;
    u8 len;
    u8 type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    long unsigned int mask;
    u8 len;
    u8 type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    long unsigned int mask;
    u8 len;
    u8 type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    long unsigned int mask;
    u8 len;
    u8 type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    long unsigned int mask;
    u8 len;
    u8 type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    long unsigned int mask;
    u8 len;
    u8 type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    long unsigned int mask;
    u8 len;
    u8 type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    long unsigned int mask;
    u8 len;
    u8 type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    long unsigned int mask;
    u8 len;
    u8 type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    long unsigned int mask;
    u8 len;
    u8 type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    long unsigned int mask;
    u8 len;
    u8 type;
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
struct arch_hw_breakpoint {
    u64 address;
    u64 trigger;
    struct arch_hw_breakpoint_ctrl ctrl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    u32 address;
    u32 trigger;
    struct arch_hw_breakpoint_ctrl step_ctrl;
    struct arch_hw_breakpoint_ctrl ctrl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    u16 type;
    u16 len;
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    long unsigned int mask;
    u8 len;
    u8 type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    long unsigned int mask;
    u8 len;
    u8 type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    long unsigned int mask;
    u8 len;
    u8 type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    long unsigned int mask;
    u8 len;
    u8 type;
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 trigger</code>
</li>
<li>
<b>Field added. </b>
<code>struct arch_hw_breakpoint_ctrl ctrl</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int mask</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 len</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 type</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int address</code> ➡️ <code>u64 address</code>
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
<code>u32 trigger</code>
</li>
<li>
<b>Field added. </b>
<code>struct arch_hw_breakpoint_ctrl step_ctrl</code>
</li>
<li>
<b>Field added. </b>
<code>struct arch_hw_breakpoint_ctrl ctrl</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int mask</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 len</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 type</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int address</code> ➡️ <code>u32 address</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long unsigned int mask</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8 len</code> ➡️ <code>u16 len</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8 type</code> ➡️ <code>u16 type</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct arch_hw_breakpoint {
    long unsigned int address;
    long unsigned int mask;
    u8 len;
    u8 type;
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
