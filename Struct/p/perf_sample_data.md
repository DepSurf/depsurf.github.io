# Struct: <code>perf_sample_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 addr;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 period;
    u64 weight;
    u64 txn;
    union perf_mem_data_src data_src;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    struct perf_regs regs_user;
    struct pt_regs regs_user_copy;
    struct perf_regs regs_intr;
    u64 stack_user_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 addr;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 period;
    u64 weight;
    u64 txn;
    union perf_mem_data_src data_src;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    struct perf_regs regs_user;
    struct pt_regs regs_user_copy;
    struct perf_regs regs_intr;
    u64 stack_user_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 addr;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 period;
    u64 weight;
    u64 txn;
    union perf_mem_data_src data_src;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    struct perf_regs regs_user;
    struct pt_regs regs_user_copy;
    struct perf_regs regs_intr;
    u64 stack_user_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 addr;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 period;
    u64 weight;
    u64 txn;
    union perf_mem_data_src data_src;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    struct perf_regs regs_user;
    struct pt_regs regs_user_copy;
    struct perf_regs regs_intr;
    u64 stack_user_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 addr;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 period;
    u64 weight;
    u64 txn;
    union perf_mem_data_src data_src;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    struct perf_regs regs_user;
    struct pt_regs regs_user_copy;
    struct perf_regs regs_intr;
    u64 stack_user_size;
    u64 phys_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 addr;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 period;
    u64 weight;
    u64 txn;
    union perf_mem_data_src data_src;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    struct perf_regs regs_user;
    struct pt_regs regs_user_copy;
    struct perf_regs regs_intr;
    u64 stack_user_size;
    u64 phys_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 addr;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 period;
    u64 weight;
    u64 txn;
    union perf_mem_data_src data_src;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    struct perf_regs regs_user;
    struct pt_regs regs_user_copy;
    struct perf_regs regs_intr;
    u64 stack_user_size;
    u64 phys_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 addr;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 period;
    u64 weight;
    u64 txn;
    union perf_mem_data_src data_src;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    struct perf_regs regs_user;
    struct pt_regs regs_user_copy;
    struct perf_regs regs_intr;
    u64 stack_user_size;
    u64 phys_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 addr;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 period;
    u64 weight;
    u64 txn;
    union perf_mem_data_src data_src;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    struct perf_regs regs_user;
    struct pt_regs regs_user_copy;
    struct perf_regs regs_intr;
    u64 stack_user_size;
    u64 phys_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 addr;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 period;
    u64 weight;
    u64 txn;
    union perf_mem_data_src data_src;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    u64 aux_size;
    struct perf_regs regs_user;
    struct pt_regs regs_user_copy;
    struct perf_regs regs_intr;
    u64 stack_user_size;
    u64 phys_addr;
    u64 cgroup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 addr;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 period;
    u64 weight;
    u64 txn;
    union perf_mem_data_src data_src;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    u64 aux_size;
    struct perf_regs regs_user;
    struct perf_regs regs_intr;
    u64 stack_user_size;
    u64 phys_addr;
    u64 cgroup;
    u64 data_page_size;
    u64 code_page_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 addr;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 period;
    union perf_sample_weight weight;
    u64 txn;
    union perf_mem_data_src data_src;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    u64 aux_size;
    struct perf_regs regs_user;
    struct perf_regs regs_intr;
    u64 stack_user_size;
    u64 phys_addr;
    u64 cgroup;
    u64 data_page_size;
    u64 code_page_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 addr;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 period;
    union perf_sample_weight weight;
    u64 txn;
    union perf_mem_data_src data_src;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    u64 aux_size;
    struct perf_regs regs_user;
    struct perf_regs regs_intr;
    u64 stack_user_size;
    u64 phys_addr;
    u64 cgroup;
    u64 data_page_size;
    u64 code_page_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 addr;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 period;
    union perf_sample_weight weight;
    u64 txn;
    union perf_mem_data_src data_src;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    u64 aux_size;
    struct perf_regs regs_user;
    struct perf_regs regs_intr;
    u64 stack_user_size;
    u64 phys_addr;
    u64 cgroup;
    u64 data_page_size;
    u64 code_page_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 sample_flags;
    u64 period;
    struct perf_branch_stack * br_stack;
    union perf_sample_weight weight;
    union perf_mem_data_src data_src;
    u64 txn;
    u64 addr;
    struct perf_raw_record * raw;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    u64 aux_size;
    struct perf_regs regs_user;
    struct perf_regs regs_intr;
    u64 stack_user_size;
    u64 phys_addr;
    u64 cgroup;
    u64 data_page_size;
    u64 code_page_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 sample_flags;
    u64 period;
    u64 dyn_size;
    u64 type;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    struct (anon) cpu_entry;
    u64 ip;
    struct perf_callchain_entry * callchain;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    union perf_sample_weight weight;
    union perf_mem_data_src data_src;
    u64 txn;
    struct perf_regs regs_user;
    struct perf_regs regs_intr;
    u64 stack_user_size;
    u64 stream_id;
    u64 cgroup;
    u64 addr;
    u64 phys_addr;
    u64 data_page_size;
    u64 code_page_size;
    u64 aux_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 sample_flags;
    u64 period;
    u64 dyn_size;
    u64 type;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    struct (anon) cpu_entry;
    u64 ip;
    struct perf_callchain_entry * callchain;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 * br_stack_cntr;
    union perf_sample_weight weight;
    union perf_mem_data_src data_src;
    u64 txn;
    struct perf_regs regs_user;
    struct perf_regs regs_intr;
    u64 stack_user_size;
    u64 stream_id;
    u64 cgroup;
    u64 addr;
    u64 phys_addr;
    u64 data_page_size;
    u64 code_page_size;
    u64 aux_size;
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
struct perf_sample_data {
    u64 addr;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 period;
    u64 weight;
    u64 txn;
    union perf_mem_data_src data_src;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    struct perf_regs regs_user;
    struct pt_regs regs_user_copy;
    struct perf_regs regs_intr;
    u64 stack_user_size;
    u64 phys_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 addr;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 period;
    u64 weight;
    u64 txn;
    union perf_mem_data_src data_src;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    struct perf_regs regs_user;
    struct pt_regs regs_user_copy;
    struct perf_regs regs_intr;
    u64 stack_user_size;
    u64 phys_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 addr;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 period;
    u64 weight;
    u64 txn;
    union perf_mem_data_src data_src;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    struct perf_regs regs_user;
    struct pt_regs regs_user_copy;
    struct perf_regs regs_intr;
    u64 stack_user_size;
    u64 phys_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 addr;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 period;
    u64 weight;
    u64 txn;
    union perf_mem_data_src data_src;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    struct perf_regs regs_user;
    struct pt_regs regs_user_copy;
    struct perf_regs regs_intr;
    u64 stack_user_size;
    u64 phys_addr;
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
struct perf_sample_data {
    u64 addr;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 period;
    u64 weight;
    u64 txn;
    union perf_mem_data_src data_src;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    struct perf_regs regs_user;
    struct pt_regs regs_user_copy;
    struct perf_regs regs_intr;
    u64 stack_user_size;
    u64 phys_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 addr;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 period;
    u64 weight;
    u64 txn;
    union perf_mem_data_src data_src;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    struct perf_regs regs_user;
    struct pt_regs regs_user_copy;
    struct perf_regs regs_intr;
    u64 stack_user_size;
    u64 phys_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 addr;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 period;
    u64 weight;
    u64 txn;
    union perf_mem_data_src data_src;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    struct perf_regs regs_user;
    struct pt_regs regs_user_copy;
    struct perf_regs regs_intr;
    u64 stack_user_size;
    u64 phys_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct perf_sample_data {
    u64 addr;
    struct perf_raw_record * raw;
    struct perf_branch_stack * br_stack;
    u64 period;
    u64 weight;
    u64 txn;
    union perf_mem_data_src data_src;
    u64 type;
    u64 ip;
    struct (anon) tid_entry;
    u64 time;
    u64 id;
    u64 stream_id;
    struct (anon) cpu_entry;
    struct perf_callchain_entry * callchain;
    struct perf_regs regs_user;
    struct pt_regs regs_user_copy;
    struct perf_regs regs_intr;
    u64 stack_user_size;
    u64 phys_addr;
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 phys_addr</code>
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
<code>u64 aux_size</code>
</li>
<li>
<b>Field added. </b>
<code>u64 cgroup</code>
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
<code>u64 data_page_size</code>
</li>
<li>
<b>Field added. </b>
<code>u64 code_page_size</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pt_regs regs_user_copy</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>u64 weight</code> ➡️ <code>union perf_sample_weight weight</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 sample_flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 dyn_size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 * br_stack_cntr</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
