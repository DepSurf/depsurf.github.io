# Struct: <code>netns_nftables</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct netns_nftables {
    struct list_head af_info;
    struct list_head commit_list;
    struct nft_af_info * ipv4;
    struct nft_af_info * ipv6;
    struct nft_af_info * inet;
    struct nft_af_info * arp;
    struct nft_af_info * bridge;
    struct nft_af_info * netdev;
    unsigned int base_seq;
    u8 gencursor;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct netns_nftables {
    struct list_head af_info;
    struct list_head commit_list;
    struct nft_af_info * ipv4;
    struct nft_af_info * ipv6;
    struct nft_af_info * inet;
    struct nft_af_info * arp;
    struct nft_af_info * bridge;
    struct nft_af_info * netdev;
    unsigned int base_seq;
    u8 gencursor;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct netns_nftables {
    struct list_head af_info;
    struct list_head commit_list;
    struct nft_af_info * ipv4;
    struct nft_af_info * ipv6;
    struct nft_af_info * inet;
    struct nft_af_info * arp;
    struct nft_af_info * bridge;
    struct nft_af_info * netdev;
    unsigned int base_seq;
    u8 gencursor;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct netns_nftables {
    struct list_head af_info;
    struct list_head commit_list;
    struct nft_af_info * ipv4;
    struct nft_af_info * ipv6;
    struct nft_af_info * inet;
    struct nft_af_info * arp;
    struct nft_af_info * bridge;
    struct nft_af_info * netdev;
    unsigned int base_seq;
    u8 gencursor;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct netns_nftables {
    struct list_head af_info;
    struct list_head commit_list;
    struct nft_af_info * ipv4;
    struct nft_af_info * ipv6;
    struct nft_af_info * inet;
    struct nft_af_info * arp;
    struct nft_af_info * bridge;
    struct nft_af_info * netdev;
    unsigned int base_seq;
    u8 gencursor;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct netns_nftables {
    struct list_head tables;
    struct list_head commit_list;
    unsigned int base_seq;
    u8 gencursor;
    u8 validate_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct netns_nftables {
    struct list_head tables;
    struct list_head commit_list;
    struct mutex commit_mutex;
    unsigned int base_seq;
    u8 gencursor;
    u8 validate_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct netns_nftables {
    struct list_head tables;
    struct list_head commit_list;
    struct mutex commit_mutex;
    unsigned int base_seq;
    u8 gencursor;
    u8 validate_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct netns_nftables {
    struct list_head tables;
    struct list_head commit_list;
    struct list_head module_list;
    struct mutex commit_mutex;
    unsigned int base_seq;
    u8 gencursor;
    u8 validate_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct netns_nftables {
    struct list_head tables;
    struct list_head commit_list;
    struct list_head module_list;
    struct mutex commit_mutex;
    unsigned int base_seq;
    u8 gencursor;
    u8 validate_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct netns_nftables {
    struct list_head tables;
    struct list_head commit_list;
    struct list_head module_list;
    struct list_head notify_list;
    struct mutex commit_mutex;
    unsigned int base_seq;
    u8 gencursor;
    u8 validate_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct netns_nftables {
    u8 gencursor;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct netns_nftables {
    u8 gencursor;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct netns_nftables {
    u8 gencursor;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct netns_nftables {
    u8 gencursor;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct netns_nftables {
    u8 gencursor;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct netns_nftables {
    u8 gencursor;
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
struct netns_nftables {
    struct list_head tables;
    struct list_head commit_list;
    struct list_head module_list;
    struct mutex commit_mutex;
    unsigned int base_seq;
    u8 gencursor;
    u8 validate_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct netns_nftables {
    struct list_head tables;
    struct list_head commit_list;
    struct list_head module_list;
    struct mutex commit_mutex;
    unsigned int base_seq;
    u8 gencursor;
    u8 validate_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct netns_nftables {
    struct list_head tables;
    struct list_head commit_list;
    struct list_head module_list;
    struct mutex commit_mutex;
    unsigned int base_seq;
    u8 gencursor;
    u8 validate_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct netns_nftables {
    struct list_head tables;
    struct list_head commit_list;
    struct list_head module_list;
    struct mutex commit_mutex;
    unsigned int base_seq;
    u8 gencursor;
    u8 validate_state;
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
struct netns_nftables {
    struct list_head tables;
    struct list_head commit_list;
    struct list_head module_list;
    struct mutex commit_mutex;
    unsigned int base_seq;
    u8 gencursor;
    u8 validate_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct netns_nftables {
    struct list_head tables;
    struct list_head commit_list;
    struct list_head module_list;
    struct mutex commit_mutex;
    unsigned int base_seq;
    u8 gencursor;
    u8 validate_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct netns_nftables {
    struct list_head tables;
    struct list_head commit_list;
    struct list_head module_list;
    struct mutex commit_mutex;
    unsigned int base_seq;
    u8 gencursor;
    u8 validate_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct netns_nftables {
    struct list_head tables;
    struct list_head commit_list;
    struct list_head module_list;
    struct mutex commit_mutex;
    unsigned int base_seq;
    u8 gencursor;
    u8 validate_state;
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
<code>struct list_head tables</code>
</li>
<li>
<b>Field added. </b>
<code>u8 validate_state</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head af_info</code>
</li>
<li>
<b>Field removed. </b>
<code>struct nft_af_info * ipv4</code>
</li>
<li>
<b>Field removed. </b>
<code>struct nft_af_info * ipv6</code>
</li>
<li>
<b>Field removed. </b>
<code>struct nft_af_info * inet</code>
</li>
<li>
<b>Field removed. </b>
<code>struct nft_af_info * arp</code>
</li>
<li>
<b>Field removed. </b>
<code>struct nft_af_info * bridge</code>
</li>
<li>
<b>Field removed. </b>
<code>struct nft_af_info * netdev</code>
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
<code>struct mutex commit_mutex</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head module_list</code>
</li>
</ul>
</details>
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
<code>struct list_head notify_list</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct list_head tables</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head commit_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head module_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head notify_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex commit_mutex</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int base_seq</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 validate_state</code>
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
