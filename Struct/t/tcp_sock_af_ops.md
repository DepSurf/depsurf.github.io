# Struct: <code>tcp_sock_af_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, char *, int) md5_parse;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, char *, int) md5_parse;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, char *, int) md5_parse;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, int, char *, int) md5_parse;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, int, char *, int) md5_parse;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, int, char *, int) md5_parse;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, int, char *, int) md5_parse;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, int, char *, int) md5_parse;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, int, char *, int) md5_parse;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, int, char *, int) md5_parse;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, int, sockptr_t, int) md5_parse;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, int, sockptr_t, int) md5_parse;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, int, sockptr_t, int) md5_parse;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, int, sockptr_t, int) md5_parse;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, int, sockptr_t, int) md5_parse;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, int, sockptr_t, int) md5_parse;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, int, sockptr_t, int) md5_parse;
    int (*)(struct sock *, int, sockptr_t, int) ao_parse;
    struct tcp_ao_key * (*)(const struct sock *, struct sock *, int, int) ao_lookup;
    int (*)(struct tcp_ao_key *, u8 *, const struct sock *, __be32, __be32, bool) ao_calc_key_sk;
    int (*)(char *, struct tcp_ao_key *, const struct sock *, const struct sk_buff *, const u8 *, int, u32) calc_ao_hash;
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
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, int, char *, int) md5_parse;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, int, char *, int) md5_parse;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, int, char *, int) md5_parse;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, int, char *, int) md5_parse;
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
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, int, char *, int) md5_parse;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, int, char *, int) md5_parse;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, int, char *, int) md5_parse;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tcp_sock_af_ops {
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    int (*)(struct sock *, int, char *, int) md5_parse;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct sock *, char *, int) md5_parse</code> ➡️ <code>int (*)(struct sock *, int, char *, int) md5_parse</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct sock *, int, char *, int) md5_parse</code> ➡️ <code>int (*)(struct sock *, int, sockptr_t, int) md5_parse</code>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct sock *, int, sockptr_t, int) ao_parse</code>
</li>
<li>
<b>Field added. </b>
<code>struct tcp_ao_key * (*)(const struct sock *, struct sock *, int, int) ao_lookup</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct tcp_ao_key *, u8 *, const struct sock *, __be32, __be32, bool) ao_calc_key_sk</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(char *, struct tcp_ao_key *, const struct sock *, const struct sk_buff *, const u8 *, int, u32) calc_ao_hash</code>
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
