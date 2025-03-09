# Struct: <code>napi_gro_cb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 gro_remcsum_start;
    long unsigned int age;
    u16 proto;
    u8 same_flow;
    u8 udp_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    __wsum csum;
    struct sk_buff * last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 gro_remcsum_start;
    long unsigned int age;
    u16 proto;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    __wsum csum;
    struct sk_buff * last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 gro_remcsum_start;
    long unsigned int age;
    u16 proto;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    __wsum csum;
    struct sk_buff * last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 gro_remcsum_start;
    long unsigned int age;
    u16 proto;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    __wsum csum;
    struct sk_buff * last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 gro_remcsum_start;
    long unsigned int age;
    u16 proto;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    __wsum csum;
    struct sk_buff * last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 gro_remcsum_start;
    long unsigned int age;
    u16 proto;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    __wsum csum;
    struct sk_buff * last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 gro_remcsum_start;
    long unsigned int age;
    u16 proto;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    __wsum csum;
    struct sk_buff * last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 gro_remcsum_start;
    long unsigned int age;
    u16 proto;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    __wsum csum;
    struct sk_buff * last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 gro_remcsum_start;
    long unsigned int age;
    u16 proto;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    __wsum csum;
    struct sk_buff * last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 gro_remcsum_start;
    long unsigned int age;
    u16 proto;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    u8 is_flist;
    __wsum csum;
    struct sk_buff * last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 gro_remcsum_start;
    long unsigned int age;
    u16 proto;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    u8 is_flist;
    __wsum csum;
    struct sk_buff * last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 gro_remcsum_start;
    long unsigned int age;
    u16 proto;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    u8 is_flist;
    __wsum csum;
    struct sk_buff * last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 gro_remcsum_start;
    long unsigned int age;
    u16 proto;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    u8 is_flist;
    __wsum csum;
    struct sk_buff * last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 proto;
    long unsigned int age;
    u16 gro_remcsum_start;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    u8 is_flist;
    struct (anon) zeroed;
    __wsum csum;
    struct sk_buff * last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 proto;
    long unsigned int age;
    u16 gro_remcsum_start;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    u8 is_flist;
    struct (anon) zeroed;
    __wsum csum;
    struct sk_buff * last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    struct sk_buff * last;
    long unsigned int age;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 proto;
    u16 gro_remcsum_start;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    u8 is_flist;
    struct (anon) zeroed;
    __wsum csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    struct sk_buff * last;
    long unsigned int age;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 proto;
    u16 gro_remcsum_start;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    u8 is_flist;
    struct (anon) zeroed;
    __wsum csum;
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
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 gro_remcsum_start;
    long unsigned int age;
    u16 proto;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    __wsum csum;
    struct sk_buff * last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 gro_remcsum_start;
    long unsigned int age;
    u16 proto;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    __wsum csum;
    struct sk_buff * last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 gro_remcsum_start;
    long unsigned int age;
    u16 proto;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    __wsum csum;
    struct sk_buff * last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 gro_remcsum_start;
    long unsigned int age;
    u16 proto;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    __wsum csum;
    struct sk_buff * last;
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
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 gro_remcsum_start;
    long unsigned int age;
    u16 proto;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    __wsum csum;
    struct sk_buff * last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 gro_remcsum_start;
    long unsigned int age;
    u16 proto;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    __wsum csum;
    struct sk_buff * last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 gro_remcsum_start;
    long unsigned int age;
    u16 proto;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    __wsum csum;
    struct sk_buff * last;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct napi_gro_cb {
    void * frag0;
    unsigned int frag0_len;
    int data_offset;
    u16 flush;
    u16 flush_id;
    u16 count;
    u16 gro_remcsum_start;
    long unsigned int age;
    u16 proto;
    u8 same_flow;
    u8 encap_mark;
    u8 csum_valid;
    u8 csum_cnt;
    u8 free;
    u8 is_ipv6;
    u8 is_fou;
    u8 is_atomic;
    u8 recursion_counter;
    __wsum csum;
    struct sk_buff * last;
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 encap_mark</code>
</li>
<li>
<b>Field added. </b>
<code>u8 is_fou</code>
</li>
<li>
<b>Field added. </b>
<code>u8 is_atomic</code>
</li>
<li>
<b>Field added. </b>
<code>u8 recursion_counter</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 udp_mark</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 is_flist</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct (anon) zeroed</code>
</li>
</ul>
</details>
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
