# Struct: <code>exception_stacks</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct exception_stacks {
    char[0] DF_stack_guard;
    char[4096] DF_stack;
    char[0] NMI_stack_guard;
    char[4096] NMI_stack;
    char[0] DB2_stack_guard;
    char[0] DB2_stack;
    char[0] DB1_stack_guard;
    char[4096] DB1_stack;
    char[0] DB_stack_guard;
    char[4096] DB_stack;
    char[0] MCE_stack_guard;
    char[4096] MCE_stack;
    char[0] IST_top_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct exception_stacks {
    char[0] DF_stack_guard;
    char[4096] DF_stack;
    char[0] NMI_stack_guard;
    char[4096] NMI_stack;
    char[0] DB2_stack_guard;
    char[0] DB2_stack;
    char[0] DB1_stack_guard;
    char[4096] DB1_stack;
    char[0] DB_stack_guard;
    char[4096] DB_stack;
    char[0] MCE_stack_guard;
    char[4096] MCE_stack;
    char[0] IST_top_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct exception_stacks {
    char[0] DF_stack_guard;
    char[4096] DF_stack;
    char[0] NMI_stack_guard;
    char[4096] NMI_stack;
    char[0] DB_stack_guard;
    char[4096] DB_stack;
    char[0] MCE_stack_guard;
    char[4096] MCE_stack;
    char[0] IST_top_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct exception_stacks {
    char[0] DF_stack_guard;
    char[4096] DF_stack;
    char[0] NMI_stack_guard;
    char[4096] NMI_stack;
    char[0] DB_stack_guard;
    char[4096] DB_stack;
    char[0] MCE_stack_guard;
    char[4096] MCE_stack;
    char[0] VC_stack_guard;
    char[0] VC_stack;
    char[0] VC2_stack_guard;
    char[0] VC2_stack;
    char[0] IST_top_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct exception_stacks {
    char[0] DF_stack_guard;
    char[4096] DF_stack;
    char[0] NMI_stack_guard;
    char[4096] NMI_stack;
    char[0] DB_stack_guard;
    char[4096] DB_stack;
    char[0] MCE_stack_guard;
    char[4096] MCE_stack;
    char[0] VC_stack_guard;
    char[0] VC_stack;
    char[0] VC2_stack_guard;
    char[0] VC2_stack;
    char[0] IST_top_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct exception_stacks {
    char[0] DF_stack_guard;
    char[8192] DF_stack;
    char[0] NMI_stack_guard;
    char[8192] NMI_stack;
    char[0] DB_stack_guard;
    char[8192] DB_stack;
    char[0] MCE_stack_guard;
    char[8192] MCE_stack;
    char[0] VC_stack_guard;
    char[8192] VC_stack;
    char[0] VC2_stack_guard;
    char[8192] VC2_stack;
    char[0] IST_top_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct exception_stacks {
    char[0] DF_stack_guard;
    char[8192] DF_stack;
    char[0] NMI_stack_guard;
    char[8192] NMI_stack;
    char[0] DB_stack_guard;
    char[8192] DB_stack;
    char[0] MCE_stack_guard;
    char[8192] MCE_stack;
    char[0] VC_stack_guard;
    char[8192] VC_stack;
    char[0] VC2_stack_guard;
    char[8192] VC2_stack;
    char[0] IST_top_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct exception_stacks {
    char[0] DF_stack_guard;
    char[8192] DF_stack;
    char[0] NMI_stack_guard;
    char[8192] NMI_stack;
    char[0] DB_stack_guard;
    char[8192] DB_stack;
    char[0] MCE_stack_guard;
    char[8192] MCE_stack;
    char[0] VC_stack_guard;
    char[8192] VC_stack;
    char[0] VC2_stack_guard;
    char[8192] VC2_stack;
    char[0] IST_top_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct exception_stacks {
    char[0] DF_stack_guard;
    char[8192] DF_stack;
    char[0] NMI_stack_guard;
    char[8192] NMI_stack;
    char[0] DB_stack_guard;
    char[8192] DB_stack;
    char[0] MCE_stack_guard;
    char[8192] MCE_stack;
    char[0] VC_stack_guard;
    char[8192] VC_stack;
    char[0] VC2_stack_guard;
    char[8192] VC2_stack;
    char[0] IST_top_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct exception_stacks {
    char[0] DF_stack_guard;
    char[8192] DF_stack;
    char[0] NMI_stack_guard;
    char[8192] NMI_stack;
    char[0] DB_stack_guard;
    char[8192] DB_stack;
    char[0] MCE_stack_guard;
    char[8192] MCE_stack;
    char[0] VC_stack_guard;
    char[8192] VC_stack;
    char[0] VC2_stack_guard;
    char[8192] VC2_stack;
    char[0] IST_top_guard;
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
struct exception_stacks {
    char[0] DF_stack_guard;
    char[4096] DF_stack;
    char[0] NMI_stack_guard;
    char[4096] NMI_stack;
    char[0] DB2_stack_guard;
    char[0] DB2_stack;
    char[0] DB1_stack_guard;
    char[4096] DB1_stack;
    char[0] DB_stack_guard;
    char[4096] DB_stack;
    char[0] MCE_stack_guard;
    char[4096] MCE_stack;
    char[0] IST_top_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct exception_stacks {
    char[0] DF_stack_guard;
    char[4096] DF_stack;
    char[0] NMI_stack_guard;
    char[4096] NMI_stack;
    char[0] DB2_stack_guard;
    char[0] DB2_stack;
    char[0] DB1_stack_guard;
    char[4096] DB1_stack;
    char[0] DB_stack_guard;
    char[4096] DB_stack;
    char[0] MCE_stack_guard;
    char[4096] MCE_stack;
    char[0] IST_top_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct exception_stacks {
    char[0] DF_stack_guard;
    char[4096] DF_stack;
    char[0] NMI_stack_guard;
    char[4096] NMI_stack;
    char[0] DB2_stack_guard;
    char[0] DB2_stack;
    char[0] DB1_stack_guard;
    char[4096] DB1_stack;
    char[0] DB_stack_guard;
    char[4096] DB_stack;
    char[0] MCE_stack_guard;
    char[4096] MCE_stack;
    char[0] IST_top_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct exception_stacks {
    char[0] DF_stack_guard;
    char[4096] DF_stack;
    char[0] NMI_stack_guard;
    char[4096] NMI_stack;
    char[0] DB2_stack_guard;
    char[0] DB2_stack;
    char[0] DB1_stack_guard;
    char[4096] DB1_stack;
    char[0] DB_stack_guard;
    char[4096] DB_stack;
    char[0] MCE_stack_guard;
    char[4096] MCE_stack;
    char[0] IST_top_guard;
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct exception_stacks {
    char[0] DF_stack_guard;
    char[4096] DF_stack;
    char[0] NMI_stack_guard;
    char[4096] NMI_stack;
    char[0] DB2_stack_guard;
    char[0] DB2_stack;
    char[0] DB1_stack_guard;
    char[4096] DB1_stack;
    char[0] DB_stack_guard;
    char[4096] DB_stack;
    char[0] MCE_stack_guard;
    char[4096] MCE_stack;
    char[0] IST_top_guard;
}
```
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
<b>Field removed. </b>
<code>char[0] DB2_stack_guard</code>
</li>
<li>
<b>Field removed. </b>
<code>char[0] DB2_stack</code>
</li>
<li>
<b>Field removed. </b>
<code>char[0] DB1_stack_guard</code>
</li>
<li>
<b>Field removed. </b>
<code>char[4096] DB1_stack</code>
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
<code>char[0] VC_stack_guard</code>
</li>
<li>
<b>Field added. </b>
<code>char[0] VC_stack</code>
</li>
<li>
<b>Field added. </b>
<code>char[0] VC2_stack_guard</code>
</li>
<li>
<b>Field added. </b>
<code>char[0] VC2_stack</code>
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
<b>Field type changed. </b>
<code>char[4096] DF_stack</code> ➡️ <code>char[8192] DF_stack</code>
</li>
<li>
<b>Field type changed. </b>
<code>char[4096] NMI_stack</code> ➡️ <code>char[8192] NMI_stack</code>
</li>
<li>
<b>Field type changed. </b>
<code>char[4096] DB_stack</code> ➡️ <code>char[8192] DB_stack</code>
</li>
<li>
<b>Field type changed. </b>
<code>char[4096] MCE_stack</code> ➡️ <code>char[8192] MCE_stack</code>
</li>
<li>
<b>Field type changed. </b>
<code>char[0] VC_stack</code> ➡️ <code>char[8192] VC_stack</code>
</li>
<li>
<b>Field type changed. </b>
<code>char[0] VC2_stack</code> ➡️ <code>char[8192] VC2_stack</code>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct exception_stacks {
    char[0] DF_stack_guard;
    char[4096] DF_stack;
    char[0] NMI_stack_guard;
    char[4096] NMI_stack;
    char[0] DB2_stack_guard;
    char[0] DB2_stack;
    char[0] DB1_stack_guard;
    char[4096] DB1_stack;
    char[0] DB_stack_guard;
    char[4096] DB_stack;
    char[0] MCE_stack_guard;
    char[4096] MCE_stack;
    char[0] IST_top_guard;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct exception_stacks {
    char[0] DF_stack_guard;
    char[4096] DF_stack;
    char[0] NMI_stack_guard;
    char[4096] NMI_stack;
    char[0] DB2_stack_guard;
    char[0] DB2_stack;
    char[0] DB1_stack_guard;
    char[4096] DB1_stack;
    char[0] DB_stack_guard;
    char[4096] DB_stack;
    char[0] MCE_stack_guard;
    char[4096] MCE_stack;
    char[0] IST_top_guard;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct exception_stacks {
    char[0] DF_stack_guard;
    char[4096] DF_stack;
    char[0] NMI_stack_guard;
    char[4096] NMI_stack;
    char[0] DB2_stack_guard;
    char[0] DB2_stack;
    char[0] DB1_stack_guard;
    char[4096] DB1_stack;
    char[0] DB_stack_guard;
    char[4096] DB_stack;
    char[0] MCE_stack_guard;
    char[4096] MCE_stack;
    char[0] IST_top_guard;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct exception_stacks {
    char[0] DF_stack_guard;
    char[4096] DF_stack;
    char[0] NMI_stack_guard;
    char[4096] NMI_stack;
    char[0] DB2_stack_guard;
    char[0] DB2_stack;
    char[0] DB1_stack_guard;
    char[4096] DB1_stack;
    char[0] DB_stack_guard;
    char[4096] DB_stack;
    char[0] MCE_stack_guard;
    char[4096] MCE_stack;
    char[0] IST_top_guard;
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
