# Struct: <code>flowi_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    struct flowi_tunnel flowic_tun_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    struct flowi_tunnel flowic_tun_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    struct flowi_tunnel flowic_tun_key;
    kuid_t flowic_uid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    struct flowi_tunnel flowic_tun_key;
    kuid_t flowic_uid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    struct flowi_tunnel flowic_tun_key;
    kuid_t flowic_uid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    struct flowi_tunnel flowic_tun_key;
    kuid_t flowic_uid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    kuid_t flowic_uid;
    struct flowi_tunnel flowic_tun_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    kuid_t flowic_uid;
    struct flowi_tunnel flowic_tun_key;
    __u32 flowic_multipath_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    kuid_t flowic_uid;
    struct flowi_tunnel flowic_tun_key;
    __u32 flowic_multipath_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    kuid_t flowic_uid;
    struct flowi_tunnel flowic_tun_key;
    __u32 flowic_multipath_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    kuid_t flowic_uid;
    struct flowi_tunnel flowic_tun_key;
    __u32 flowic_multipath_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    kuid_t flowic_uid;
    struct flowi_tunnel flowic_tun_key;
    __u32 flowic_multipath_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    kuid_t flowic_uid;
    struct flowi_tunnel flowic_tun_key;
    __u32 flowic_multipath_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    int flowic_l3mdev;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    kuid_t flowic_uid;
    struct flowi_tunnel flowic_tun_key;
    __u32 flowic_multipath_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    int flowic_l3mdev;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    kuid_t flowic_uid;
    struct flowi_tunnel flowic_tun_key;
    __u32 flowic_multipath_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    int flowic_l3mdev;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    kuid_t flowic_uid;
    struct flowi_tunnel flowic_tun_key;
    __u32 flowic_multipath_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    int flowic_l3mdev;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    kuid_t flowic_uid;
    __u32 flowic_multipath_hash;
    struct flowi_tunnel flowic_tun_key;
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
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    kuid_t flowic_uid;
    struct flowi_tunnel flowic_tun_key;
    __u32 flowic_multipath_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    kuid_t flowic_uid;
    struct flowi_tunnel flowic_tun_key;
    __u32 flowic_multipath_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    kuid_t flowic_uid;
    struct flowi_tunnel flowic_tun_key;
    __u32 flowic_multipath_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    kuid_t flowic_uid;
    struct flowi_tunnel flowic_tun_key;
    __u32 flowic_multipath_hash;
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
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    kuid_t flowic_uid;
    struct flowi_tunnel flowic_tun_key;
    __u32 flowic_multipath_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    kuid_t flowic_uid;
    struct flowi_tunnel flowic_tun_key;
    __u32 flowic_multipath_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    kuid_t flowic_uid;
    struct flowi_tunnel flowic_tun_key;
    __u32 flowic_multipath_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct flowi_common {
    int flowic_oif;
    int flowic_iif;
    __u32 flowic_mark;
    __u8 flowic_tos;
    __u8 flowic_scope;
    __u8 flowic_proto;
    __u8 flowic_flags;
    __u32 flowic_secid;
    kuid_t flowic_uid;
    struct flowi_tunnel flowic_tun_key;
    __u32 flowic_multipath_hash;
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
<code>kuid_t flowic_uid</code>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u32 flowic_multipath_hash</code>
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
<code>int flowic_l3mdev</code>
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
