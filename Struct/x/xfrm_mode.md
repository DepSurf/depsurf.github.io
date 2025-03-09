# Struct: <code>xfrm_mode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mode {
    int (*)(struct xfrm_state *, struct sk_buff *) input2;
    int (*)(struct xfrm_state *, struct sk_buff *) input;
    int (*)(struct xfrm_state *, struct sk_buff *) output2;
    int (*)(struct xfrm_state *, struct sk_buff *) output;
    struct xfrm_state_afinfo * afinfo;
    struct module * owner;
    unsigned int encap;
    int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mode {
    int (*)(struct xfrm_state *, struct sk_buff *) input2;
    int (*)(struct xfrm_state *, struct sk_buff *) input;
    int (*)(struct xfrm_state *, struct sk_buff *) output2;
    int (*)(struct xfrm_state *, struct sk_buff *) output;
    struct xfrm_state_afinfo * afinfo;
    struct module * owner;
    unsigned int encap;
    int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mode {
    int (*)(struct xfrm_state *, struct sk_buff *) input2;
    int (*)(struct xfrm_state *, struct sk_buff *) input;
    int (*)(struct xfrm_state *, struct sk_buff *) output2;
    int (*)(struct xfrm_state *, struct sk_buff *) output;
    struct xfrm_state_afinfo * afinfo;
    struct module * owner;
    unsigned int encap;
    int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mode {
    int (*)(struct xfrm_state *, struct sk_buff *) input2;
    int (*)(struct xfrm_state *, struct sk_buff *) input;
    int (*)(struct xfrm_state *, struct sk_buff *) output2;
    int (*)(struct xfrm_state *, struct sk_buff *) output;
    struct sk_buff * (*)(struct xfrm_state *, struct sk_buff *, netdev_features_t) gso_segment;
    void (*)(struct xfrm_state *, struct sk_buff *) xmit;
    struct xfrm_state_afinfo * afinfo;
    struct module * owner;
    unsigned int encap;
    int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mode {
    int (*)(struct xfrm_state *, struct sk_buff *) input2;
    int (*)(struct xfrm_state *, struct sk_buff *) input;
    int (*)(struct xfrm_state *, struct sk_buff *) output2;
    int (*)(struct xfrm_state *, struct sk_buff *) output;
    struct sk_buff * (*)(struct xfrm_state *, struct sk_buff *, netdev_features_t) gso_segment;
    void (*)(struct xfrm_state *, struct sk_buff *) xmit;
    struct xfrm_state_afinfo * afinfo;
    struct module * owner;
    unsigned int encap;
    int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mode {
    int (*)(struct xfrm_state *, struct sk_buff *) input2;
    int (*)(struct xfrm_state *, struct sk_buff *) input;
    int (*)(struct xfrm_state *, struct sk_buff *) output2;
    int (*)(struct xfrm_state *, struct sk_buff *) output;
    struct sk_buff * (*)(struct xfrm_state *, struct sk_buff *, netdev_features_t) gso_segment;
    void (*)(struct xfrm_state *, struct sk_buff *) xmit;
    struct xfrm_state_afinfo * afinfo;
    struct module * owner;
    unsigned int encap;
    int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mode {
    int (*)(struct xfrm_state *, struct sk_buff *) input2;
    int (*)(struct xfrm_state *, struct sk_buff *) input;
    int (*)(struct xfrm_state *, struct sk_buff *) output2;
    int (*)(struct xfrm_state *, struct sk_buff *) output;
    struct sk_buff * (*)(struct xfrm_state *, struct sk_buff *, netdev_features_t) gso_segment;
    void (*)(struct xfrm_state *, struct sk_buff *) xmit;
    struct xfrm_state_afinfo * afinfo;
    struct module * owner;
    unsigned int encap;
    int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mode {
    u8 encap;
    u8 family;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mode {
    u8 encap;
    u8 family;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mode {
    u8 encap;
    u8 family;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mode {
    u8 encap;
    u8 family;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mode {
    u8 encap;
    u8 family;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mode {
    u8 encap;
    u8 family;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mode {
    u8 encap;
    u8 family;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mode {
    u8 encap;
    u8 family;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mode {
    u8 encap;
    u8 family;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct xfrm_mode {
    u8 encap;
    u8 family;
    u8 flags;
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
struct xfrm_mode {
    u8 encap;
    u8 family;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct xfrm_mode {
    u8 encap;
    u8 family;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct xfrm_mode {
    u8 encap;
    u8 family;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct xfrm_mode {
    u8 encap;
    u8 family;
    u8 flags;
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
struct xfrm_mode {
    u8 encap;
    u8 family;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct xfrm_mode {
    u8 encap;
    u8 family;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct xfrm_mode {
    u8 encap;
    u8 family;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct xfrm_mode {
    u8 encap;
    u8 family;
    u8 flags;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct sk_buff * (*)(struct xfrm_state *, struct sk_buff *, netdev_features_t) gso_segment</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct xfrm_state *, struct sk_buff *) xmit</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 family</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct xfrm_state *, struct sk_buff *) input2</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct xfrm_state *, struct sk_buff *) input</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct xfrm_state *, struct sk_buff *) output2</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct xfrm_state *, struct sk_buff *) output</code>
</li>
<li>
<b>Field removed. </b>
<code>struct sk_buff * (*)(struct xfrm_state *, struct sk_buff *, netdev_features_t) gso_segment</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct xfrm_state *, struct sk_buff *) xmit</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xfrm_state_afinfo * afinfo</code>
</li>
<li>
<b>Field removed. </b>
<code>struct module * owner</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int encap</code> ➡️ <code>u8 encap</code>
</li>
<li>
<b>Field type changed. </b>
<code>int flags</code> ➡️ <code>u8 flags</code>
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
