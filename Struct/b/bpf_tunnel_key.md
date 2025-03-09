# Struct: <code>bpf_tunnel_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __u32 tunnel_label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __u32 tunnel_label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __u32 tunnel_label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __u32 tunnel_label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __u32 tunnel_label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __u32 tunnel_label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __u32 tunnel_label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __u32 tunnel_label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __u32 tunnel_label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __u32 tunnel_label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __u32 tunnel_label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __u32 tunnel_label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __u32 tunnel_label;
    __u32 local_ipv4;
    __u32[4] local_ipv6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __be16 tunnel_flags;
    __u32 tunnel_label;
    __u32 local_ipv4;
    __u32[4] local_ipv6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __be16 tunnel_flags;
    __u32 tunnel_label;
    __u32 local_ipv4;
    __u32[4] local_ipv6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __be16 tunnel_flags;
    __u32 tunnel_label;
    __u32 local_ipv4;
    __u32[4] local_ipv6;
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
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __u32 tunnel_label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __u32 tunnel_label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __u32 tunnel_label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __u32 tunnel_label;
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
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __u32 tunnel_label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __u32 tunnel_label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __u32 tunnel_label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bpf_tunnel_key {
    __u32 tunnel_id;
    __u32 remote_ipv4;
    __u32[4] remote_ipv6;
    __u8 tunnel_tos;
    __u8 tunnel_ttl;
    __u16 tunnel_ext;
    __u32 tunnel_label;
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
<code>__u32[4] remote_ipv6</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 tunnel_tos</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 tunnel_ttl</code>
</li>
<li>
<b>Field added. </b>
<code>__u16 tunnel_ext</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 tunnel_label</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u32 local_ipv4</code>
</li>
<li>
<b>Field added. </b>
<code>__u32[4] local_ipv6</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__be16 tunnel_flags</code>
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
