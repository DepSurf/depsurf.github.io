# Struct: <code>nf_tcp_net</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct nf_tcp_net {
    struct nf_proto_net pn;
    unsigned int[14] timeouts;
    unsigned int tcp_loose;
    unsigned int tcp_be_liberal;
    unsigned int tcp_max_retrans;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct nf_tcp_net {
    struct nf_proto_net pn;
    unsigned int[14] timeouts;
    unsigned int tcp_loose;
    unsigned int tcp_be_liberal;
    unsigned int tcp_max_retrans;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct nf_tcp_net {
    struct nf_proto_net pn;
    unsigned int[14] timeouts;
    unsigned int tcp_loose;
    unsigned int tcp_be_liberal;
    unsigned int tcp_max_retrans;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct nf_tcp_net {
    struct nf_proto_net pn;
    unsigned int[14] timeouts;
    unsigned int tcp_loose;
    unsigned int tcp_be_liberal;
    unsigned int tcp_max_retrans;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nf_tcp_net {
    struct nf_proto_net pn;
    unsigned int[14] timeouts;
    unsigned int tcp_loose;
    unsigned int tcp_be_liberal;
    unsigned int tcp_max_retrans;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nf_tcp_net {
    struct nf_proto_net pn;
    unsigned int[14] timeouts;
    unsigned int tcp_loose;
    unsigned int tcp_be_liberal;
    unsigned int tcp_max_retrans;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nf_tcp_net {
    struct nf_proto_net pn;
    unsigned int[14] timeouts;
    unsigned int tcp_loose;
    unsigned int tcp_be_liberal;
    unsigned int tcp_max_retrans;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nf_tcp_net {
    unsigned int[14] timeouts;
    int tcp_loose;
    int tcp_be_liberal;
    int tcp_max_retrans;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nf_tcp_net {
    unsigned int[14] timeouts;
    int tcp_loose;
    int tcp_be_liberal;
    int tcp_max_retrans;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct nf_tcp_net {
    unsigned int[14] timeouts;
    int tcp_loose;
    int tcp_be_liberal;
    int tcp_max_retrans;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct nf_tcp_net {
    unsigned int[14] timeouts;
    int tcp_loose;
    int tcp_be_liberal;
    int tcp_max_retrans;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct nf_tcp_net {
    unsigned int[14] timeouts;
    u8 tcp_loose;
    u8 tcp_be_liberal;
    u8 tcp_max_retrans;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nf_tcp_net {
    unsigned int[14] timeouts;
    u8 tcp_loose;
    u8 tcp_be_liberal;
    u8 tcp_max_retrans;
    u8 tcp_ignore_invalid_rst;
    unsigned int offload_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nf_tcp_net {
    unsigned int[14] timeouts;
    u8 tcp_loose;
    u8 tcp_be_liberal;
    u8 tcp_max_retrans;
    u8 tcp_ignore_invalid_rst;
    unsigned int offload_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nf_tcp_net {
    unsigned int[14] timeouts;
    u8 tcp_loose;
    u8 tcp_be_liberal;
    u8 tcp_max_retrans;
    u8 tcp_ignore_invalid_rst;
    unsigned int offload_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nf_tcp_net {
    unsigned int[14] timeouts;
    u8 tcp_loose;
    u8 tcp_be_liberal;
    u8 tcp_max_retrans;
    u8 tcp_ignore_invalid_rst;
    unsigned int offload_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nf_tcp_net {
    unsigned int[14] timeouts;
    u8 tcp_loose;
    u8 tcp_be_liberal;
    u8 tcp_max_retrans;
    u8 tcp_ignore_invalid_rst;
    unsigned int offload_timeout;
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
struct nf_tcp_net {
    unsigned int[14] timeouts;
    int tcp_loose;
    int tcp_be_liberal;
    int tcp_max_retrans;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct nf_tcp_net {
    unsigned int[14] timeouts;
    int tcp_loose;
    int tcp_be_liberal;
    int tcp_max_retrans;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nf_tcp_net {
    unsigned int[14] timeouts;
    int tcp_loose;
    int tcp_be_liberal;
    int tcp_max_retrans;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nf_tcp_net {
    unsigned int[14] timeouts;
    int tcp_loose;
    int tcp_be_liberal;
    int tcp_max_retrans;
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
struct nf_tcp_net {
    unsigned int[14] timeouts;
    int tcp_loose;
    int tcp_be_liberal;
    int tcp_max_retrans;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nf_tcp_net {
    unsigned int[14] timeouts;
    int tcp_loose;
    int tcp_be_liberal;
    int tcp_max_retrans;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nf_tcp_net {
    unsigned int[14] timeouts;
    int tcp_loose;
    int tcp_be_liberal;
    int tcp_max_retrans;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nf_tcp_net {
    unsigned int[14] timeouts;
    int tcp_loose;
    int tcp_be_liberal;
    int tcp_max_retrans;
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct nf_proto_net pn</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int tcp_loose</code> ➡️ <code>int tcp_loose</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int tcp_be_liberal</code> ➡️ <code>int tcp_be_liberal</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int tcp_max_retrans</code> ➡️ <code>int tcp_max_retrans</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int tcp_loose</code> ➡️ <code>u8 tcp_loose</code>
</li>
<li>
<b>Field type changed. </b>
<code>int tcp_be_liberal</code> ➡️ <code>u8 tcp_be_liberal</code>
</li>
<li>
<b>Field type changed. </b>
<code>int tcp_max_retrans</code> ➡️ <code>u8 tcp_max_retrans</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 tcp_ignore_invalid_rst</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int offload_timeout</code>
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
