# Struct: <code>sctp_endpoint</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct sctp_endpoint {
    struct sctp_ep_common base;
    struct list_head asocs;
    __u8[32] secret_key;
    __u8 * digest;
    __u32 sndbuf_policy;
    __u32 rcvbuf_policy;
    struct crypto_shash * * auth_hmacs;
    struct sctp_hmac_algo_param * auth_hmacs_list;
    struct sctp_chunks_param * auth_chunk_list;
    struct list_head endpoint_shared_keys;
    __u16 active_key_id;
    __u8 auth_enable;
    __u8 prsctp_enable;
    __u8 reconf_enable;
    __u8 strreset_enable;
    u32 secid;
    u32 peer_secid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sctp_endpoint {
    struct sctp_ep_common base;
    struct list_head asocs;
    __u8[32] secret_key;
    __u8 * digest;
    __u32 sndbuf_policy;
    __u32 rcvbuf_policy;
    struct crypto_shash * * auth_hmacs;
    struct sctp_hmac_algo_param * auth_hmacs_list;
    struct sctp_chunks_param * auth_chunk_list;
    struct list_head endpoint_shared_keys;
    __u16 active_key_id;
    __u8 auth_enable;
    __u8 prsctp_enable;
    __u8 reconf_enable;
    __u8 strreset_enable;
    u32 secid;
    u32 peer_secid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sctp_endpoint {
    struct sctp_ep_common base;
    struct list_head asocs;
    __u8[32] secret_key;
    __u8 * digest;
    __u32 sndbuf_policy;
    __u32 rcvbuf_policy;
    struct crypto_shash * * auth_hmacs;
    struct sctp_hmac_algo_param * auth_hmacs_list;
    struct sctp_chunks_param * auth_chunk_list;
    struct list_head endpoint_shared_keys;
    __u16 active_key_id;
    __u8 auth_enable;
    __u8 intl_enable;
    __u8 prsctp_enable;
    __u8 reconf_enable;
    __u8 strreset_enable;
    u32 secid;
    u32 peer_secid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sctp_endpoint {
    struct sctp_ep_common base;
    struct list_head asocs;
    __u8[32] secret_key;
    __u8 * digest;
    __u32 sndbuf_policy;
    __u32 rcvbuf_policy;
    struct crypto_shash * * auth_hmacs;
    struct sctp_hmac_algo_param * auth_hmacs_list;
    struct sctp_chunks_param * auth_chunk_list;
    struct list_head endpoint_shared_keys;
    __u16 active_key_id;
    __u8 ecn_enable;
    __u8 auth_enable;
    __u8 intl_enable;
    __u8 prsctp_enable;
    __u8 asconf_enable;
    __u8 reconf_enable;
    __u8 strreset_enable;
    u32 secid;
    u32 peer_secid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sctp_endpoint {
    struct sctp_ep_common base;
    struct list_head asocs;
    __u8[32] secret_key;
    __u8 * digest;
    __u32 sndbuf_policy;
    __u32 rcvbuf_policy;
    struct crypto_shash * * auth_hmacs;
    struct sctp_hmac_algo_param * auth_hmacs_list;
    struct sctp_chunks_param * auth_chunk_list;
    struct list_head endpoint_shared_keys;
    __u16 active_key_id;
    __u8 ecn_enable;
    __u8 auth_enable;
    __u8 intl_enable;
    __u8 prsctp_enable;
    __u8 asconf_enable;
    __u8 reconf_enable;
    __u8 strreset_enable;
    u32 secid;
    u32 peer_secid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct sctp_endpoint {
    struct sctp_ep_common base;
    struct list_head asocs;
    __u8[32] secret_key;
    __u8 * digest;
    __u32 sndbuf_policy;
    __u32 rcvbuf_policy;
    struct crypto_shash * * auth_hmacs;
    struct sctp_hmac_algo_param * auth_hmacs_list;
    struct sctp_chunks_param * auth_chunk_list;
    struct list_head endpoint_shared_keys;
    __u16 active_key_id;
    __u8 ecn_enable;
    __u8 auth_enable;
    __u8 intl_enable;
    __u8 prsctp_enable;
    __u8 asconf_enable;
    __u8 reconf_enable;
    __u8 strreset_enable;
    u32 secid;
    u32 peer_secid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct sctp_endpoint {
    struct sctp_ep_common base;
    struct list_head asocs;
    __u8[32] secret_key;
    __u8 * digest;
    __u32 sndbuf_policy;
    __u32 rcvbuf_policy;
    struct crypto_shash * * auth_hmacs;
    struct sctp_hmac_algo_param * auth_hmacs_list;
    struct sctp_chunks_param * auth_chunk_list;
    struct list_head endpoint_shared_keys;
    __u16 active_key_id;
    __u8 ecn_enable;
    __u8 auth_enable;
    __u8 intl_enable;
    __u8 prsctp_enable;
    __u8 asconf_enable;
    __u8 reconf_enable;
    __u8 strreset_enable;
    u32 secid;
    u32 peer_secid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct sctp_endpoint {
    struct sctp_ep_common base;
    struct list_head asocs;
    __u8[32] secret_key;
    __u8 * digest;
    __u32 sndbuf_policy;
    __u32 rcvbuf_policy;
    struct crypto_shash * * auth_hmacs;
    struct sctp_hmac_algo_param * auth_hmacs_list;
    struct sctp_chunks_param * auth_chunk_list;
    struct list_head endpoint_shared_keys;
    __u16 active_key_id;
    __u8 ecn_enable;
    __u8 auth_enable;
    __u8 intl_enable;
    __u8 prsctp_enable;
    __u8 asconf_enable;
    __u8 reconf_enable;
    __u8 strreset_enable;
    u32 secid;
    u32 peer_secid;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sctp_endpoint {
    struct sctp_ep_common base;
    struct hlist_node node;
    int hashent;
    struct list_head asocs;
    __u8[32] secret_key;
    __u8 * digest;
    __u32 sndbuf_policy;
    __u32 rcvbuf_policy;
    struct crypto_shash * * auth_hmacs;
    struct sctp_hmac_algo_param * auth_hmacs_list;
    struct sctp_chunks_param * auth_chunk_list;
    struct list_head endpoint_shared_keys;
    __u16 active_key_id;
    __u8 ecn_enable;
    __u8 auth_enable;
    __u8 intl_enable;
    __u8 prsctp_enable;
    __u8 asconf_enable;
    __u8 reconf_enable;
    __u8 strreset_enable;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct sctp_endpoint {
    struct sctp_ep_common base;
    struct hlist_node node;
    int hashent;
    struct list_head asocs;
    __u8[32] secret_key;
    __u8 * digest;
    __u32 sndbuf_policy;
    __u32 rcvbuf_policy;
    struct crypto_shash * * auth_hmacs;
    struct sctp_hmac_algo_param * auth_hmacs_list;
    struct sctp_chunks_param * auth_chunk_list;
    struct list_head endpoint_shared_keys;
    __u16 active_key_id;
    __u8 ecn_enable;
    __u8 auth_enable;
    __u8 intl_enable;
    __u8 prsctp_enable;
    __u8 asconf_enable;
    __u8 reconf_enable;
    __u8 strreset_enable;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct sctp_endpoint {
    struct sctp_ep_common base;
    struct hlist_node node;
    int hashent;
    struct list_head asocs;
    __u8[32] secret_key;
    __u8 * digest;
    __u32 sndbuf_policy;
    __u32 rcvbuf_policy;
    struct crypto_shash * * auth_hmacs;
    struct sctp_hmac_algo_param * auth_hmacs_list;
    struct sctp_chunks_param * auth_chunk_list;
    struct list_head endpoint_shared_keys;
    __u16 active_key_id;
    __u8 ecn_enable;
    __u8 auth_enable;
    __u8 intl_enable;
    __u8 prsctp_enable;
    __u8 asconf_enable;
    __u8 reconf_enable;
    __u8 strreset_enable;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct sctp_endpoint {
    struct sctp_ep_common base;
    struct hlist_node node;
    int hashent;
    struct list_head asocs;
    __u8[32] secret_key;
    __u8 * digest;
    __u32 sndbuf_policy;
    __u32 rcvbuf_policy;
    struct crypto_shash * * auth_hmacs;
    struct sctp_hmac_algo_param * auth_hmacs_list;
    struct sctp_chunks_param * auth_chunk_list;
    struct list_head endpoint_shared_keys;
    __u16 active_key_id;
    __u8 ecn_enable;
    __u8 auth_enable;
    __u8 intl_enable;
    __u8 prsctp_enable;
    __u8 asconf_enable;
    __u8 reconf_enable;
    __u8 strreset_enable;
    struct callback_head rcu;
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
struct sctp_endpoint {
    struct sctp_ep_common base;
    struct list_head asocs;
    __u8[32] secret_key;
    __u8 * digest;
    __u32 sndbuf_policy;
    __u32 rcvbuf_policy;
    struct crypto_shash * * auth_hmacs;
    struct sctp_hmac_algo_param * auth_hmacs_list;
    struct sctp_chunks_param * auth_chunk_list;
    struct list_head endpoint_shared_keys;
    __u16 active_key_id;
    __u8 ecn_enable;
    __u8 auth_enable;
    __u8 intl_enable;
    __u8 prsctp_enable;
    __u8 asconf_enable;
    __u8 reconf_enable;
    __u8 strreset_enable;
    u32 secid;
    u32 peer_secid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sctp_endpoint {
    struct sctp_ep_common base;
    struct list_head asocs;
    __u8[32] secret_key;
    __u8 * digest;
    __u32 sndbuf_policy;
    __u32 rcvbuf_policy;
    struct crypto_shash * * auth_hmacs;
    struct sctp_hmac_algo_param * auth_hmacs_list;
    struct sctp_chunks_param * auth_chunk_list;
    struct list_head endpoint_shared_keys;
    __u16 active_key_id;
    __u8 ecn_enable;
    __u8 auth_enable;
    __u8 intl_enable;
    __u8 prsctp_enable;
    __u8 asconf_enable;
    __u8 reconf_enable;
    __u8 strreset_enable;
    u32 secid;
    u32 peer_secid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sctp_endpoint {
    struct sctp_ep_common base;
    struct list_head asocs;
    __u8[32] secret_key;
    __u8 * digest;
    __u32 sndbuf_policy;
    __u32 rcvbuf_policy;
    struct crypto_shash * * auth_hmacs;
    struct sctp_hmac_algo_param * auth_hmacs_list;
    struct sctp_chunks_param * auth_chunk_list;
    struct list_head endpoint_shared_keys;
    __u16 active_key_id;
    __u8 ecn_enable;
    __u8 auth_enable;
    __u8 intl_enable;
    __u8 prsctp_enable;
    __u8 asconf_enable;
    __u8 reconf_enable;
    __u8 strreset_enable;
    u32 secid;
    u32 peer_secid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sctp_endpoint {
    struct sctp_ep_common base;
    struct list_head asocs;
    __u8[32] secret_key;
    __u8 * digest;
    __u32 sndbuf_policy;
    __u32 rcvbuf_policy;
    struct crypto_shash * * auth_hmacs;
    struct sctp_hmac_algo_param * auth_hmacs_list;
    struct sctp_chunks_param * auth_chunk_list;
    struct list_head endpoint_shared_keys;
    __u16 active_key_id;
    __u8 ecn_enable;
    __u8 auth_enable;
    __u8 intl_enable;
    __u8 prsctp_enable;
    __u8 asconf_enable;
    __u8 reconf_enable;
    __u8 strreset_enable;
    u32 secid;
    u32 peer_secid;
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
struct sctp_endpoint {
    struct sctp_ep_common base;
    struct list_head asocs;
    __u8[32] secret_key;
    __u8 * digest;
    __u32 sndbuf_policy;
    __u32 rcvbuf_policy;
    struct crypto_shash * * auth_hmacs;
    struct sctp_hmac_algo_param * auth_hmacs_list;
    struct sctp_chunks_param * auth_chunk_list;
    struct list_head endpoint_shared_keys;
    __u16 active_key_id;
    __u8 ecn_enable;
    __u8 auth_enable;
    __u8 intl_enable;
    __u8 prsctp_enable;
    __u8 asconf_enable;
    __u8 reconf_enable;
    __u8 strreset_enable;
    u32 secid;
    u32 peer_secid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct sctp_endpoint {
    struct sctp_ep_common base;
    struct list_head asocs;
    __u8[32] secret_key;
    __u8 * digest;
    __u32 sndbuf_policy;
    __u32 rcvbuf_policy;
    struct crypto_shash * * auth_hmacs;
    struct sctp_hmac_algo_param * auth_hmacs_list;
    struct sctp_chunks_param * auth_chunk_list;
    struct list_head endpoint_shared_keys;
    __u16 active_key_id;
    __u8 ecn_enable;
    __u8 auth_enable;
    __u8 intl_enable;
    __u8 prsctp_enable;
    __u8 asconf_enable;
    __u8 reconf_enable;
    __u8 strreset_enable;
    u32 secid;
    u32 peer_secid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct sctp_endpoint {
    struct sctp_ep_common base;
    struct list_head asocs;
    __u8[32] secret_key;
    __u8 * digest;
    __u32 sndbuf_policy;
    __u32 rcvbuf_policy;
    struct crypto_shash * * auth_hmacs;
    struct sctp_hmac_algo_param * auth_hmacs_list;
    struct sctp_chunks_param * auth_chunk_list;
    struct list_head endpoint_shared_keys;
    __u16 active_key_id;
    __u8 ecn_enable;
    __u8 auth_enable;
    __u8 intl_enable;
    __u8 prsctp_enable;
    __u8 asconf_enable;
    __u8 reconf_enable;
    __u8 strreset_enable;
    u32 secid;
    u32 peer_secid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct sctp_endpoint {
    struct sctp_ep_common base;
    struct list_head asocs;
    __u8[32] secret_key;
    __u8 * digest;
    __u32 sndbuf_policy;
    __u32 rcvbuf_policy;
    struct crypto_shash * * auth_hmacs;
    struct sctp_hmac_algo_param * auth_hmacs_list;
    struct sctp_chunks_param * auth_chunk_list;
    struct list_head endpoint_shared_keys;
    __u16 active_key_id;
    __u8 ecn_enable;
    __u8 auth_enable;
    __u8 intl_enable;
    __u8 prsctp_enable;
    __u8 asconf_enable;
    __u8 reconf_enable;
    __u8 strreset_enable;
    u32 secid;
    u32 peer_secid;
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct sctp_endpoint {
    struct sctp_ep_common base;
    struct list_head asocs;
    __u8[32] secret_key;
    __u8 * digest;
    __u32 sndbuf_policy;
    __u32 rcvbuf_policy;
    struct crypto_shash * * auth_hmacs;
    struct sctp_hmac_algo_param * auth_hmacs_list;
    struct sctp_chunks_param * auth_chunk_list;
    struct list_head endpoint_shared_keys;
    __u16 active_key_id;
    __u8 auth_enable;
    __u8 prsctp_enable;
    __u8 reconf_enable;
    __u8 strreset_enable;
    u32 secid;
    u32 peer_secid;
}
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u8 intl_enable</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u8 ecn_enable</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 asconf_enable</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct callback_head rcu</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct hlist_node node</code>
</li>
<li>
<b>Field added. </b>
<code>int hashent</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 secid</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 peer_secid</code>
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
