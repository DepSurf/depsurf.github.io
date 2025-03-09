# Struct: <code>selinux_state</code>

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
struct selinux_state {
    bool disabled;
    bool enforcing;
    bool checkreqprot;
    bool initialized;
    bool[6] policycap;
    struct selinux_avc * avc;
    struct selinux_ss * ss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct selinux_state {
    bool disabled;
    bool enforcing;
    bool checkreqprot;
    bool initialized;
    bool[6] policycap;
    struct selinux_avc * avc;
    struct selinux_ss * ss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct selinux_state {
    bool disabled;
    bool enforcing;
    bool checkreqprot;
    bool initialized;
    bool[6] policycap;
    struct selinux_avc * avc;
    struct selinux_ss * ss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct selinux_state {
    bool disabled;
    bool enforcing;
    bool checkreqprot;
    bool initialized;
    bool[6] policycap;
    struct selinux_avc * avc;
    struct selinux_ss * ss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct selinux_state {
    bool enforcing;
    bool checkreqprot;
    bool initialized;
    bool[7] policycap;
    struct page * status_page;
    struct mutex status_lock;
    struct selinux_avc * avc;
    struct selinux_ss * ss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct selinux_state {
    bool enforcing;
    bool checkreqprot;
    bool initialized;
    bool[7] policycap;
    struct page * status_page;
    struct mutex status_lock;
    struct selinux_avc * avc;
    struct selinux_policy * policy;
    struct mutex policy_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct selinux_state {
    bool enforcing;
    bool checkreqprot;
    bool initialized;
    bool[7] policycap;
    struct page * status_page;
    struct mutex status_lock;
    struct selinux_avc * avc;
    struct selinux_policy * policy;
    struct mutex policy_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct selinux_state {
    bool enforcing;
    bool checkreqprot;
    bool initialized;
    bool[7] policycap;
    struct page * status_page;
    struct mutex status_lock;
    struct selinux_avc * avc;
    struct selinux_policy * policy;
    struct mutex policy_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct selinux_state {
    bool enforcing;
    bool checkreqprot;
    bool initialized;
    bool[8] policycap;
    struct page * status_page;
    struct mutex status_lock;
    struct selinux_avc * avc;
    struct selinux_policy * policy;
    struct mutex policy_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct selinux_state {
    bool enforcing;
    bool checkreqprot;
    bool initialized;
    bool[8] policycap;
    struct page * status_page;
    struct mutex status_lock;
    struct selinux_avc * avc;
    struct selinux_policy * policy;
    struct mutex policy_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct selinux_state {
    bool enforcing;
    bool initialized;
    bool[8] policycap;
    struct page * status_page;
    struct mutex status_lock;
    struct selinux_policy * policy;
    struct mutex policy_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct selinux_state {
    bool enforcing;
    bool initialized;
    bool[9] policycap;
    struct page * status_page;
    struct mutex status_lock;
    struct selinux_policy * policy;
    struct mutex policy_mutex;
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
struct selinux_state {
    bool disabled;
    bool enforcing;
    bool checkreqprot;
    bool initialized;
    bool[6] policycap;
    struct selinux_avc * avc;
    struct selinux_ss * ss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct selinux_state {
    bool disabled;
    bool enforcing;
    bool checkreqprot;
    bool initialized;
    bool[6] policycap;
    struct selinux_avc * avc;
    struct selinux_ss * ss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct selinux_state {
    bool disabled;
    bool enforcing;
    bool checkreqprot;
    bool initialized;
    bool[6] policycap;
    struct selinux_avc * avc;
    struct selinux_ss * ss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct selinux_state {
    bool disabled;
    bool enforcing;
    bool checkreqprot;
    bool initialized;
    bool[6] policycap;
    struct selinux_avc * avc;
    struct selinux_ss * ss;
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
struct selinux_state {
    bool disabled;
    bool enforcing;
    bool checkreqprot;
    bool initialized;
    bool[6] policycap;
    struct selinux_avc * avc;
    struct selinux_ss * ss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct selinux_state {
    bool disabled;
    bool enforcing;
    bool checkreqprot;
    bool initialized;
    bool[6] policycap;
    struct selinux_avc * avc;
    struct selinux_ss * ss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct selinux_state {
    bool disabled;
    bool enforcing;
    bool checkreqprot;
    bool initialized;
    bool[6] policycap;
    struct selinux_avc * avc;
    struct selinux_ss * ss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct selinux_state {
    bool disabled;
    bool enforcing;
    bool checkreqprot;
    bool initialized;
    bool[6] policycap;
    struct selinux_avc * avc;
    struct selinux_ss * ss;
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
struct selinux_state {
    bool disabled;
    bool enforcing;
    bool checkreqprot;
    bool initialized;
    bool[6] policycap;
    struct selinux_avc * avc;
    struct selinux_ss * ss;
}
```
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct page * status_page</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex status_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>bool disabled</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool[6] policycap</code> ➡️ <code>bool[7] policycap</code>
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
<code>struct selinux_policy * policy</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex policy_mutex</code>
</li>
<li>
<b>Field removed. </b>
<code>struct selinux_ss * ss</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>bool[7] policycap</code> ➡️ <code>bool[8] policycap</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool checkreqprot</code>
</li>
<li>
<b>Field removed. </b>
<code>struct selinux_avc * avc</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>bool[8] policycap</code> ➡️ <code>bool[9] policycap</code>
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
