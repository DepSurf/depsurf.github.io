# Struct: <code>__ip6_tnl_parm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
    __u32 fwmark;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
    __u32 fwmark;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
    __u32 fwmark;
    __u32 index;
    __u8 erspan_ver;
    __u8 dir;
    __u16 hwid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
    __u32 fwmark;
    __u32 index;
    __u8 erspan_ver;
    __u8 dir;
    __u16 hwid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
    __u32 fwmark;
    __u32 index;
    __u8 erspan_ver;
    __u8 dir;
    __u16 hwid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
    __u32 fwmark;
    __u32 index;
    __u8 erspan_ver;
    __u8 dir;
    __u16 hwid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
    __u32 fwmark;
    __u32 index;
    __u8 erspan_ver;
    __u8 dir;
    __u16 hwid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
    __u32 fwmark;
    __u32 index;
    __u8 erspan_ver;
    __u8 dir;
    __u16 hwid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
    __u32 fwmark;
    __u32 index;
    __u8 erspan_ver;
    __u8 dir;
    __u16 hwid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
    __u32 fwmark;
    __u32 index;
    __u8 erspan_ver;
    __u8 dir;
    __u16 hwid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
    __u32 fwmark;
    __u32 index;
    __u8 erspan_ver;
    __u8 dir;
    __u16 hwid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
    __u32 fwmark;
    __u32 index;
    __u8 erspan_ver;
    __u8 dir;
    __u16 hwid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
    __u32 fwmark;
    __u32 index;
    __u8 erspan_ver;
    __u8 dir;
    __u16 hwid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
    __u32 fwmark;
    __u32 index;
    __u8 erspan_ver;
    __u8 dir;
    __u16 hwid;
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
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
    __u32 fwmark;
    __u32 index;
    __u8 erspan_ver;
    __u8 dir;
    __u16 hwid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
    __u32 fwmark;
    __u32 index;
    __u8 erspan_ver;
    __u8 dir;
    __u16 hwid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
    __u32 fwmark;
    __u32 index;
    __u8 erspan_ver;
    __u8 dir;
    __u16 hwid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
    __u32 fwmark;
    __u32 index;
    __u8 erspan_ver;
    __u8 dir;
    __u16 hwid;
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
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
    __u32 fwmark;
    __u32 index;
    __u8 erspan_ver;
    __u8 dir;
    __u16 hwid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
    __u32 fwmark;
    __u32 index;
    __u8 erspan_ver;
    __u8 dir;
    __u16 hwid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
    __u32 fwmark;
    __u32 index;
    __u8 erspan_ver;
    __u8 dir;
    __u16 hwid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct __ip6_tnl_parm {
    char[16] name;
    int link;
    __u8 proto;
    __u8 encap_limit;
    __u8 hop_limit;
    bool collect_md;
    __be32 flowinfo;
    __u32 flags;
    struct in6_addr laddr;
    struct in6_addr raddr;
    __be16 i_flags;
    __be16 o_flags;
    __be32 i_key;
    __be32 o_key;
    __u32 fwmark;
    __u32 index;
    __u8 erspan_ver;
    __u8 dir;
    __u16 hwid;
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
<code>bool collect_md</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u32 fwmark</code>
</li>
</ul>
</details>
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
<code>__u32 index</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 erspan_ver</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 dir</code>
</li>
<li>
<b>Field added. </b>
<code>__u16 hwid</code>
</li>
</ul>
</details>
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
