# Struct: <code>netlink_ext_ack</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    u8[20] cookie;
    u8 cookie_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    u8[20] cookie;
    u8 cookie_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    u8[20] cookie;
    u8 cookie_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    u8[20] cookie;
    u8 cookie_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    u8[20] cookie;
    u8 cookie_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    u8[20] cookie;
    u8 cookie_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    u8[20] cookie;
    u8 cookie_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    const struct nla_policy * policy;
    u8[20] cookie;
    u8 cookie_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    const struct nla_policy * policy;
    u8[20] cookie;
    u8 cookie_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    const struct nla_policy * policy;
    u8[20] cookie;
    u8 cookie_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    const struct nla_policy * policy;
    u8[20] cookie;
    u8 cookie_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    const struct nla_policy * policy;
    const struct nlattr * miss_nest;
    u16 miss_type;
    u8[20] cookie;
    u8 cookie_len;
    char[80] _msg_buf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    const struct nla_policy * policy;
    const struct nlattr * miss_nest;
    u16 miss_type;
    u8[20] cookie;
    u8 cookie_len;
    char[80] _msg_buf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    const struct nla_policy * policy;
    const struct nlattr * miss_nest;
    u16 miss_type;
    u8[20] cookie;
    u8 cookie_len;
    char[80] _msg_buf;
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
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    u8[20] cookie;
    u8 cookie_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    u8[20] cookie;
    u8 cookie_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    u8[20] cookie;
    u8 cookie_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    u8[20] cookie;
    u8 cookie_len;
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
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    u8[20] cookie;
    u8 cookie_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    u8[20] cookie;
    u8 cookie_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    u8[20] cookie;
    u8 cookie_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    u8[20] cookie;
    u8 cookie_len;
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct netlink_ext_ack {
    const char * _msg;
    const struct nlattr * bad_attr;
    u8[20] cookie;
    u8 cookie_len;
}
```
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
<b>Field added. </b>
<code>const struct nla_policy * policy</code>
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
<code>const struct nlattr * miss_nest</code>
</li>
<li>
<b>Field added. </b>
<code>u16 miss_type</code>
</li>
<li>
<b>Field added. </b>
<code>char[80] _msg_buf</code>
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
