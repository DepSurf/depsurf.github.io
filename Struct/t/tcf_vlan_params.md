# Struct: <code>tcf_vlan_params</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tcf_vlan_params {
    int tcfv_action;
    u16 tcfv_push_vid;
    __be16 tcfv_push_proto;
    u8 tcfv_push_prio;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tcf_vlan_params {
    int tcfv_action;
    u16 tcfv_push_vid;
    __be16 tcfv_push_proto;
    u8 tcfv_push_prio;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tcf_vlan_params {
    int tcfv_action;
    u16 tcfv_push_vid;
    __be16 tcfv_push_proto;
    u8 tcfv_push_prio;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tcf_vlan_params {
    int tcfv_action;
    unsigned char[6] tcfv_push_dst;
    unsigned char[6] tcfv_push_src;
    u16 tcfv_push_vid;
    __be16 tcfv_push_proto;
    u8 tcfv_push_prio;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tcf_vlan_params {
    int tcfv_action;
    unsigned char[6] tcfv_push_dst;
    unsigned char[6] tcfv_push_src;
    u16 tcfv_push_vid;
    __be16 tcfv_push_proto;
    u8 tcfv_push_prio;
    bool tcfv_push_prio_exists;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tcf_vlan_params {
    int tcfv_action;
    unsigned char[6] tcfv_push_dst;
    unsigned char[6] tcfv_push_src;
    u16 tcfv_push_vid;
    __be16 tcfv_push_proto;
    u8 tcfv_push_prio;
    bool tcfv_push_prio_exists;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct tcf_vlan_params {
    int tcfv_action;
    u16 tcfv_push_vid;
    __be16 tcfv_push_proto;
    u8 tcfv_push_prio;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tcf_vlan_params {
    int tcfv_action;
    u16 tcfv_push_vid;
    __be16 tcfv_push_proto;
    u8 tcfv_push_prio;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tcf_vlan_params {
    int tcfv_action;
    u16 tcfv_push_vid;
    __be16 tcfv_push_proto;
    u8 tcfv_push_prio;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tcf_vlan_params {
    int tcfv_action;
    u16 tcfv_push_vid;
    __be16 tcfv_push_proto;
    u8 tcfv_push_prio;
    struct callback_head rcu;
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
struct tcf_vlan_params {
    int tcfv_action;
    u16 tcfv_push_vid;
    __be16 tcfv_push_proto;
    u8 tcfv_push_prio;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tcf_vlan_params {
    int tcfv_action;
    u16 tcfv_push_vid;
    __be16 tcfv_push_proto;
    u8 tcfv_push_prio;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tcf_vlan_params {
    int tcfv_action;
    u16 tcfv_push_vid;
    __be16 tcfv_push_proto;
    u8 tcfv_push_prio;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tcf_vlan_params {
    int tcfv_action;
    u16 tcfv_push_vid;
    __be16 tcfv_push_proto;
    u8 tcfv_push_prio;
    struct callback_head rcu;
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct tcf_vlan_params {
    int tcfv_action;
    u16 tcfv_push_vid;
    __be16 tcfv_push_proto;
    u8 tcfv_push_prio;
    struct callback_head rcu;
}
```
</details>
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
<code>unsigned char[6] tcfv_push_dst</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned char[6] tcfv_push_src</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool tcfv_push_prio_exists</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct tcf_vlan_params {
    int tcfv_action;
    unsigned char[6] tcfv_push_dst;
    unsigned char[6] tcfv_push_src;
    u16 tcfv_push_vid;
    __be16 tcfv_push_proto;
    u8 tcfv_push_prio;
    bool tcfv_push_prio_exists;
    struct callback_head rcu;
}
```
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
