# Struct: <code>bpf_func_proto</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
    enum bpf_arg_type[5] arg_type;
    int * btf_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
    enum bpf_arg_type[5] arg_type;
    u32 * arg1_btf_id;
    u32 * arg2_btf_id;
    u32 * arg3_btf_id;
    u32 * arg4_btf_id;
    u32 * arg5_btf_id;
    u32 *[5] arg_btf_id;
    int * ret_btf_id;
    bool (*)(const struct bpf_prog *) allowed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
    enum bpf_arg_type[5] arg_type;
    u32 * arg1_btf_id;
    u32 * arg2_btf_id;
    u32 * arg3_btf_id;
    u32 * arg4_btf_id;
    u32 * arg5_btf_id;
    u32 *[5] arg_btf_id;
    int * ret_btf_id;
    bool (*)(const struct bpf_prog *) allowed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
    enum bpf_arg_type[5] arg_type;
    u32 * arg1_btf_id;
    u32 * arg2_btf_id;
    u32 * arg3_btf_id;
    u32 * arg4_btf_id;
    u32 * arg5_btf_id;
    u32 *[5] arg_btf_id;
    int * ret_btf_id;
    bool (*)(const struct bpf_prog *) allowed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
    enum bpf_arg_type[5] arg_type;
    u32 * arg1_btf_id;
    u32 * arg2_btf_id;
    u32 * arg3_btf_id;
    u32 * arg4_btf_id;
    u32 * arg5_btf_id;
    u32 *[5] arg_btf_id;
    int * ret_btf_id;
    bool (*)(const struct bpf_prog *) allowed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    bool might_sleep;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
    enum bpf_arg_type[5] arg_type;
    u32 * arg1_btf_id;
    u32 * arg2_btf_id;
    u32 * arg3_btf_id;
    u32 * arg4_btf_id;
    u32 * arg5_btf_id;
    u32 *[5] arg_btf_id;
    size_t arg1_size;
    size_t arg2_size;
    size_t arg3_size;
    size_t arg4_size;
    size_t arg5_size;
    size_t[5] arg_size;
    int * ret_btf_id;
    bool (*)(const struct bpf_prog *) allowed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    bool might_sleep;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
    enum bpf_arg_type[5] arg_type;
    u32 * arg1_btf_id;
    u32 * arg2_btf_id;
    u32 * arg3_btf_id;
    u32 * arg4_btf_id;
    u32 * arg5_btf_id;
    u32 *[5] arg_btf_id;
    size_t arg1_size;
    size_t arg2_size;
    size_t arg3_size;
    size_t arg4_size;
    size_t arg5_size;
    size_t[5] arg_size;
    int * ret_btf_id;
    bool (*)(const struct bpf_prog *) allowed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    bool might_sleep;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
    enum bpf_arg_type[5] arg_type;
    u32 * arg1_btf_id;
    u32 * arg2_btf_id;
    u32 * arg3_btf_id;
    u32 * arg4_btf_id;
    u32 * arg5_btf_id;
    u32 *[5] arg_btf_id;
    size_t arg1_size;
    size_t arg2_size;
    size_t arg3_size;
    size_t arg4_size;
    size_t arg5_size;
    size_t[5] arg_size;
    int * ret_btf_id;
    bool (*)(const struct bpf_prog *) allowed;
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
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
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
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bpf_func_proto {
    u64 (*)(u64, u64, u64, u64, u64) func;
    bool gpl_only;
    bool pkt_access;
    enum bpf_return_type ret_type;
    enum bpf_arg_type arg1_type;
    enum bpf_arg_type arg2_type;
    enum bpf_arg_type arg3_type;
    enum bpf_arg_type arg4_type;
    enum bpf_arg_type arg5_type;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool pkt_access</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum bpf_arg_type[5] arg_type</code>
</li>
<li>
<b>Field added. </b>
<code>int * btf_id</code>
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
<code>u32 * arg1_btf_id</code>
</li>
<li>
<b>Field added. </b>
<code>u32 * arg2_btf_id</code>
</li>
<li>
<b>Field added. </b>
<code>u32 * arg3_btf_id</code>
</li>
<li>
<b>Field added. </b>
<code>u32 * arg4_btf_id</code>
</li>
<li>
<b>Field added. </b>
<code>u32 * arg5_btf_id</code>
</li>
<li>
<b>Field added. </b>
<code>u32 *[5] arg_btf_id</code>
</li>
<li>
<b>Field added. </b>
<code>int * ret_btf_id</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(const struct bpf_prog *) allowed</code>
</li>
<li>
<b>Field removed. </b>
<code>int * btf_id</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool might_sleep</code>
</li>
<li>
<b>Field added. </b>
<code>size_t arg1_size</code>
</li>
<li>
<b>Field added. </b>
<code>size_t arg2_size</code>
</li>
<li>
<b>Field added. </b>
<code>size_t arg3_size</code>
</li>
<li>
<b>Field added. </b>
<code>size_t arg4_size</code>
</li>
<li>
<b>Field added. </b>
<code>size_t arg5_size</code>
</li>
<li>
<b>Field added. </b>
<code>size_t[5] arg_size</code>
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
