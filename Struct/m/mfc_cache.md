# Struct: <code>mfc_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mfc_cache {
    struct list_head list;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    vifi_t mfc_parent;
    int mfc_flags;
    union (anon) mfc_un;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mfc_cache {
    struct list_head list;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    vifi_t mfc_parent;
    int mfc_flags;
    union (anon) mfc_un;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mfc_cache {
    struct list_head list;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    vifi_t mfc_parent;
    int mfc_flags;
    union (anon) mfc_un;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mfc_cache {
    struct rhlist_head mnode;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    struct mfc_cache_cmp_arg cmparg;
    vifi_t mfc_parent;
    int mfc_flags;
    union (anon) mfc_un;
    struct list_head list;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mfc_cache {
    struct rhlist_head mnode;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    struct mfc_cache_cmp_arg cmparg;
    vifi_t mfc_parent;
    int mfc_flags;
    union (anon) mfc_un;
    struct list_head list;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mfc_cache {
    struct mr_mfc _c;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    struct mfc_cache_cmp_arg cmparg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mfc_cache {
    struct mr_mfc _c;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    struct mfc_cache_cmp_arg cmparg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mfc_cache {
    struct mr_mfc _c;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    struct mfc_cache_cmp_arg cmparg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mfc_cache {
    struct mr_mfc _c;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    struct mfc_cache_cmp_arg cmparg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mfc_cache {
    struct mr_mfc _c;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    struct mfc_cache_cmp_arg cmparg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mfc_cache {
    struct mr_mfc _c;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    struct mfc_cache_cmp_arg cmparg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mfc_cache {
    struct mr_mfc _c;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    struct mfc_cache_cmp_arg cmparg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mfc_cache {
    struct mr_mfc _c;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    struct mfc_cache_cmp_arg cmparg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mfc_cache {
    struct mr_mfc _c;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    struct mfc_cache_cmp_arg cmparg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mfc_cache {
    struct mr_mfc _c;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    struct mfc_cache_cmp_arg cmparg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mfc_cache {
    struct mr_mfc _c;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    struct mfc_cache_cmp_arg cmparg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mfc_cache {
    struct mr_mfc _c;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    struct mfc_cache_cmp_arg cmparg;
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
struct mfc_cache {
    struct mr_mfc _c;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    struct mfc_cache_cmp_arg cmparg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mfc_cache {
    struct mr_mfc _c;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    struct mfc_cache_cmp_arg cmparg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mfc_cache {
    struct mr_mfc _c;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    struct mfc_cache_cmp_arg cmparg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mfc_cache {
    struct mr_mfc _c;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    struct mfc_cache_cmp_arg cmparg;
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
struct mfc_cache {
    struct mr_mfc _c;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    struct mfc_cache_cmp_arg cmparg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct mfc_cache {
    struct mr_mfc _c;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    struct mfc_cache_cmp_arg cmparg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mfc_cache {
    struct mr_mfc _c;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    struct mfc_cache_cmp_arg cmparg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mfc_cache {
    struct mr_mfc _c;
    __be32 mfc_mcastgrp;
    __be32 mfc_origin;
    struct mfc_cache_cmp_arg cmparg;
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
<code>struct rhlist_head mnode</code>
</li>
<li>
<b>Field added. </b>
<code>struct mfc_cache_cmp_arg cmparg</code>
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
<code>struct mr_mfc _c</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rhlist_head mnode</code>
</li>
<li>
<b>Field removed. </b>
<code>vifi_t mfc_parent</code>
</li>
<li>
<b>Field removed. </b>
<code>int mfc_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>union (anon) mfc_un</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head rcu</code>
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
