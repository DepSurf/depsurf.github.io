# Struct: <code>x86_perf_task_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct x86_perf_task_context {
    u64[32] lbr_from;
    u64[32] lbr_to;
    u64[32] lbr_info;
    int tos;
    int lbr_callstack_users;
    int lbr_stack_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct x86_perf_task_context {
    u64[32] lbr_from;
    u64[32] lbr_to;
    u64[32] lbr_info;
    int tos;
    int lbr_callstack_users;
    int lbr_stack_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct x86_perf_task_context {
    u64[32] lbr_from;
    u64[32] lbr_to;
    u64[32] lbr_info;
    int tos;
    int lbr_callstack_users;
    int lbr_stack_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct x86_perf_task_context {
    u64[32] lbr_from;
    u64[32] lbr_to;
    u64[32] lbr_info;
    int tos;
    int lbr_callstack_users;
    int lbr_stack_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct x86_perf_task_context {
    u64[32] lbr_from;
    u64[32] lbr_to;
    u64[32] lbr_info;
    int tos;
    int lbr_callstack_users;
    int lbr_stack_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct x86_perf_task_context {
    u64[32] lbr_from;
    u64[32] lbr_to;
    u64[32] lbr_info;
    int tos;
    int valid_lbrs;
    int lbr_callstack_users;
    int lbr_stack_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct x86_perf_task_context {
    u64[32] lbr_from;
    u64[32] lbr_to;
    u64[32] lbr_info;
    int tos;
    int valid_lbrs;
    int lbr_callstack_users;
    int lbr_stack_state;
    int log_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct x86_perf_task_context {
    u64[32] lbr_from;
    u64[32] lbr_to;
    u64[32] lbr_info;
    int tos;
    int valid_lbrs;
    int lbr_callstack_users;
    int lbr_stack_state;
    int log_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct x86_perf_task_context {
    u64[32] lbr_from;
    u64[32] lbr_to;
    u64[32] lbr_info;
    int tos;
    int valid_lbrs;
    int lbr_callstack_users;
    int lbr_stack_state;
    int log_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct x86_perf_task_context {
    u64[32] lbr_from;
    u64[32] lbr_to;
    u64[32] lbr_info;
    int tos;
    int valid_lbrs;
    int lbr_callstack_users;
    int lbr_stack_state;
    int log_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct x86_perf_task_context {
    u64 lbr_sel;
    int tos;
    int valid_lbrs;
    struct x86_perf_task_context_opt opt;
    struct lbr_entry[32] lbr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct x86_perf_task_context {
    u64 lbr_sel;
    int tos;
    int valid_lbrs;
    struct x86_perf_task_context_opt opt;
    struct lbr_entry[32] lbr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct x86_perf_task_context {
    u64 lbr_sel;
    int tos;
    int valid_lbrs;
    struct x86_perf_task_context_opt opt;
    struct lbr_entry[32] lbr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct x86_perf_task_context {
    u64 lbr_sel;
    int tos;
    int valid_lbrs;
    struct x86_perf_task_context_opt opt;
    struct lbr_entry[32] lbr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct x86_perf_task_context {
    u64 lbr_sel;
    int tos;
    int valid_lbrs;
    struct x86_perf_task_context_opt opt;
    struct lbr_entry[32] lbr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct x86_perf_task_context {
    u64 lbr_sel;
    int tos;
    int valid_lbrs;
    struct x86_perf_task_context_opt opt;
    struct lbr_entry[32] lbr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct x86_perf_task_context {
    u64 lbr_sel;
    int tos;
    int valid_lbrs;
    struct x86_perf_task_context_opt opt;
    struct lbr_entry[32] lbr;
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
struct x86_perf_task_context {
    u64[32] lbr_from;
    u64[32] lbr_to;
    u64[32] lbr_info;
    int tos;
    int valid_lbrs;
    int lbr_callstack_users;
    int lbr_stack_state;
    int log_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct x86_perf_task_context {
    u64[32] lbr_from;
    u64[32] lbr_to;
    u64[32] lbr_info;
    int tos;
    int valid_lbrs;
    int lbr_callstack_users;
    int lbr_stack_state;
    int log_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct x86_perf_task_context {
    u64[32] lbr_from;
    u64[32] lbr_to;
    u64[32] lbr_info;
    int tos;
    int valid_lbrs;
    int lbr_callstack_users;
    int lbr_stack_state;
    int log_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct x86_perf_task_context {
    u64[32] lbr_from;
    u64[32] lbr_to;
    u64[32] lbr_info;
    int tos;
    int valid_lbrs;
    int lbr_callstack_users;
    int lbr_stack_state;
    int log_id;
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int valid_lbrs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int log_id</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 lbr_sel</code>
</li>
<li>
<b>Field added. </b>
<code>struct x86_perf_task_context_opt opt</code>
</li>
<li>
<b>Field added. </b>
<code>struct lbr_entry[32] lbr</code>
</li>
<li>
<b>Field removed. </b>
<code>u64[32] lbr_from</code>
</li>
<li>
<b>Field removed. </b>
<code>u64[32] lbr_to</code>
</li>
<li>
<b>Field removed. </b>
<code>u64[32] lbr_info</code>
</li>
<li>
<b>Field removed. </b>
<code>int lbr_callstack_users</code>
</li>
<li>
<b>Field removed. </b>
<code>int lbr_stack_state</code>
</li>
<li>
<b>Field removed. </b>
<code>int log_id</code>
</li>
</ul>
</details>
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
struct x86_perf_task_context {
    u64[32] lbr_from;
    u64[32] lbr_to;
    u64[32] lbr_info;
    int tos;
    int valid_lbrs;
    int lbr_callstack_users;
    int lbr_stack_state;
    int log_id;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct x86_perf_task_context {
    u64[32] lbr_from;
    u64[32] lbr_to;
    u64[32] lbr_info;
    int tos;
    int valid_lbrs;
    int lbr_callstack_users;
    int lbr_stack_state;
    int log_id;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct x86_perf_task_context {
    u64[32] lbr_from;
    u64[32] lbr_to;
    u64[32] lbr_info;
    int tos;
    int valid_lbrs;
    int lbr_callstack_users;
    int lbr_stack_state;
    int log_id;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct x86_perf_task_context {
    u64[32] lbr_from;
    u64[32] lbr_to;
    u64[32] lbr_info;
    int tos;
    int valid_lbrs;
    int lbr_callstack_users;
    int lbr_stack_state;
    int log_id;
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
