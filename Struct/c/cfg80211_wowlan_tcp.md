# Struct: <code>cfg80211_wowlan_tcp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
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
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
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
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cfg80211_wowlan_tcp {
    struct socket * sock;
    __be32 src;
    __be32 dst;
    u16 src_port;
    u16 dst_port;
    u8[6] dst_mac;
    int payload_len;
    const u8 * payload;
    struct nl80211_wowlan_tcp_data_seq payload_seq;
    u32 data_interval;
    u32 wake_len;
    const u8 * wake_data;
    const u8 * wake_mask;
    u32 tokens_size;
    struct nl80211_wowlan_tcp_data_token payload_tok;
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
