# Struct: <code>nla_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct nla_policy {
    u16 type;
    u16 len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct nla_policy {
    u16 type;
    u16 len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct nla_policy {
    u16 type;
    u16 len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct nla_policy {
    u16 type;
    u16 len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nla_policy {
    u16 type;
    u16 len;
    void * validation_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nla_policy {
    u16 type;
    u16 len;
    void * validation_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nla_policy {
    u8 type;
    u8 validation_type;
    u16 len;
    const void * validation_data;
    s16 min;
    s16 max;
    int (*)(const struct nlattr *, struct netlink_ext_ack *) validate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nla_policy {
    u8 type;
    u8 validation_type;
    u16 len;
    const void * validation_data;
    s16 min;
    s16 max;
    int (*)(const struct nlattr *, struct netlink_ext_ack *) validate;
    u16 strict_start_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nla_policy {
    u8 type;
    u8 validation_type;
    u16 len;
    const void * validation_data;
    s16 min;
    s16 max;
    int (*)(const struct nlattr *, struct netlink_ext_ack *) validate;
    u16 strict_start_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct nla_policy {
    u8 type;
    u8 validation_type;
    u16 len;
    const u32 bitfield32_valid;
    const char * reject_message;
    const struct nla_policy * nested_policy;
    struct netlink_range_validation * range;
    struct netlink_range_validation_signed * range_signed;
    s16 min;
    s16 max;
    int (*)(const struct nlattr *, struct netlink_ext_ack *) validate;
    u16 strict_start_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct nla_policy {
    u8 type;
    u8 validation_type;
    u16 len;
    const u32 bitfield32_valid;
    const u32 mask;
    const char * reject_message;
    const struct nla_policy * nested_policy;
    struct netlink_range_validation * range;
    struct netlink_range_validation_signed * range_signed;
    s16 min;
    s16 max;
    int (*)(const struct nlattr *, struct netlink_ext_ack *) validate;
    u16 strict_start_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct nla_policy {
    u8 type;
    u8 validation_type;
    u16 len;
    const u32 bitfield32_valid;
    const u32 mask;
    const char * reject_message;
    const struct nla_policy * nested_policy;
    struct netlink_range_validation * range;
    struct netlink_range_validation_signed * range_signed;
    s16 min;
    s16 max;
    int (*)(const struct nlattr *, struct netlink_ext_ack *) validate;
    u16 strict_start_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nla_policy {
    u8 type;
    u8 validation_type;
    u16 len;
    const u32 bitfield32_valid;
    const u32 mask;
    const char * reject_message;
    const struct nla_policy * nested_policy;
    struct netlink_range_validation * range;
    struct netlink_range_validation_signed * range_signed;
    s16 min;
    s16 max;
    int (*)(const struct nlattr *, struct netlink_ext_ack *) validate;
    u16 strict_start_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nla_policy {
    u8 type;
    u8 validation_type;
    u16 len;
    const u32 bitfield32_valid;
    const u32 mask;
    const char * reject_message;
    const struct nla_policy * nested_policy;
    struct netlink_range_validation * range;
    struct netlink_range_validation_signed * range_signed;
    s16 min;
    s16 max;
    int (*)(const struct nlattr *, struct netlink_ext_ack *) validate;
    u16 strict_start_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nla_policy {
    u8 type;
    u8 validation_type;
    u16 len;
    u16 strict_start_type;
    const u32 bitfield32_valid;
    const u32 mask;
    const char * reject_message;
    const struct nla_policy * nested_policy;
    struct netlink_range_validation * range;
    struct netlink_range_validation_signed * range_signed;
    s16 min;
    s16 max;
    int (*)(const struct nlattr *, struct netlink_ext_ack *) validate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nla_policy {
    u8 type;
    u8 validation_type;
    u16 len;
    u16 strict_start_type;
    const u32 bitfield32_valid;
    const u32 mask;
    const char * reject_message;
    const struct nla_policy * nested_policy;
    struct netlink_range_validation * range;
    struct netlink_range_validation_signed * range_signed;
    s16 min;
    s16 max;
    int (*)(const struct nlattr *, struct netlink_ext_ack *) validate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nla_policy {
    u8 type;
    u8 validation_type;
    u16 len;
    u16 strict_start_type;
    const u32 bitfield32_valid;
    const u32 mask;
    const char * reject_message;
    const struct nla_policy * nested_policy;
    const struct netlink_range_validation * range;
    const struct netlink_range_validation_signed * range_signed;
    s16 min;
    s16 max;
    int (*)(const struct nlattr *, struct netlink_ext_ack *) validate;
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
struct nla_policy {
    u8 type;
    u8 validation_type;
    u16 len;
    const void * validation_data;
    s16 min;
    s16 max;
    int (*)(const struct nlattr *, struct netlink_ext_ack *) validate;
    u16 strict_start_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct nla_policy {
    u8 type;
    u8 validation_type;
    u16 len;
    const void * validation_data;
    s16 min;
    s16 max;
    int (*)(const struct nlattr *, struct netlink_ext_ack *) validate;
    u16 strict_start_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nla_policy {
    u8 type;
    u8 validation_type;
    u16 len;
    const void * validation_data;
    s16 min;
    s16 max;
    int (*)(const struct nlattr *, struct netlink_ext_ack *) validate;
    u16 strict_start_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nla_policy {
    u8 type;
    u8 validation_type;
    u16 len;
    const void * validation_data;
    s16 min;
    s16 max;
    int (*)(const struct nlattr *, struct netlink_ext_ack *) validate;
    u16 strict_start_type;
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
struct nla_policy {
    u8 type;
    u8 validation_type;
    u16 len;
    const void * validation_data;
    s16 min;
    s16 max;
    int (*)(const struct nlattr *, struct netlink_ext_ack *) validate;
    u16 strict_start_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nla_policy {
    u8 type;
    u8 validation_type;
    u16 len;
    const void * validation_data;
    s16 min;
    s16 max;
    int (*)(const struct nlattr *, struct netlink_ext_ack *) validate;
    u16 strict_start_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nla_policy {
    u8 type;
    u8 validation_type;
    u16 len;
    const void * validation_data;
    s16 min;
    s16 max;
    int (*)(const struct nlattr *, struct netlink_ext_ack *) validate;
    u16 strict_start_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nla_policy {
    u8 type;
    u8 validation_type;
    u16 len;
    const void * validation_data;
    s16 min;
    s16 max;
    int (*)(const struct nlattr *, struct netlink_ext_ack *) validate;
    u16 strict_start_type;
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * validation_data</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 validation_type</code>
</li>
<li>
<b>Field added. </b>
<code>s16 min</code>
</li>
<li>
<b>Field added. </b>
<code>s16 max</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(const struct nlattr *, struct netlink_ext_ack *) validate</code>
</li>
<li>
<b>Field type changed. </b>
<code>u16 type</code> ➡️ <code>u8 type</code>
</li>
<li>
<b>Field type changed. </b>
<code>void * validation_data</code> ➡️ <code>const void * validation_data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u16 strict_start_type</code>
</li>
</ul>
</details>
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
<code>const u32 bitfield32_valid</code>
</li>
<li>
<b>Field added. </b>
<code>const char * reject_message</code>
</li>
<li>
<b>Field added. </b>
<code>const struct nla_policy * nested_policy</code>
</li>
<li>
<b>Field added. </b>
<code>struct netlink_range_validation * range</code>
</li>
<li>
<b>Field added. </b>
<code>struct netlink_range_validation_signed * range_signed</code>
</li>
<li>
<b>Field removed. </b>
<code>const void * validation_data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const u32 mask</code>
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
<b>Field type changed. </b>
<code>struct netlink_range_validation * range</code> ➡️ <code>const struct netlink_range_validation * range</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct netlink_range_validation_signed * range_signed</code> ➡️ <code>const struct netlink_range_validation_signed * range_signed</code>
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
