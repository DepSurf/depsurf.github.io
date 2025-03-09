# Struct: <code>mempolicy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    union (anon) v;
    union (anon) w;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    union (anon) v;
    union (anon) w;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    union (anon) v;
    union (anon) w;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    union (anon) v;
    union (anon) w;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    union (anon) v;
    union (anon) w;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    union (anon) v;
    union (anon) w;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    union (anon) v;
    union (anon) w;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    union (anon) v;
    union (anon) w;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    union (anon) v;
    union (anon) w;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    union (anon) v;
    union (anon) w;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    union (anon) v;
    union (anon) w;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    union (anon) v;
    union (anon) w;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    nodemask_t nodes;
    union (anon) w;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    nodemask_t nodes;
    int home_node;
    union (anon) w;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    nodemask_t nodes;
    int home_node;
    union (anon) w;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    nodemask_t nodes;
    int home_node;
    union (anon) w;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    nodemask_t nodes;
    int home_node;
    union (anon) w;
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
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    union (anon) v;
    union (anon) w;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mempolicy {
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    union (anon) v;
    union (anon) w;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mempolicy {
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
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    union (anon) v;
    union (anon) w;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    union (anon) v;
    union (anon) w;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    union (anon) v;
    union (anon) w;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mempolicy {
    atomic_t refcnt;
    short unsigned int mode;
    short unsigned int flags;
    union (anon) v;
    union (anon) w;
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
<code>nodemask_t nodes</code>
</li>
<li>
<b>Field removed. </b>
<code>union (anon) v</code>
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
<code>int home_node</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>atomic_t refcnt</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int mode</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int flags</code>
</li>
<li>
<b>Field removed. </b>
<code>union (anon) v</code>
</li>
<li>
<b>Field removed. </b>
<code>union (anon) w</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>atomic_t refcnt</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int mode</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int flags</code>
</li>
<li>
<b>Field removed. </b>
<code>union (anon) v</code>
</li>
<li>
<b>Field removed. </b>
<code>union (anon) w</code>
</li>
</ul>
</details>
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
