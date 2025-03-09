# Struct: <code>fib6_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct rt6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct rt6_info * rr_ptr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct rt6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct rt6_info * rr_ptr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct rt6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct rt6_info * rr_ptr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct rt6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct rt6_info * rr_ptr;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct rt6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct rt6_info * rr_ptr;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct fib6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct fib6_info * rr_ptr;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct fib6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct fib6_info * rr_ptr;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct fib6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct fib6_info * rr_ptr;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct fib6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct fib6_info * rr_ptr;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct fib6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct fib6_info * rr_ptr;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct fib6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct fib6_info * rr_ptr;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct fib6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct fib6_info * rr_ptr;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct fib6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct fib6_info * rr_ptr;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct fib6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct fib6_info * rr_ptr;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct fib6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct fib6_info * rr_ptr;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct fib6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct fib6_info * rr_ptr;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct fib6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct fib6_info * rr_ptr;
    struct callback_head rcu;
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
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct fib6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct fib6_info * rr_ptr;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct fib6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct fib6_info * rr_ptr;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct fib6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct fib6_info * rr_ptr;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct fib6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct fib6_info * rr_ptr;
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
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct fib6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct fib6_info * rr_ptr;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct fib6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct fib6_info * rr_ptr;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct fib6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct fib6_info * rr_ptr;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fib6_node {
    struct fib6_node * parent;
    struct fib6_node * left;
    struct fib6_node * right;
    struct fib6_node * subtree;
    struct fib6_info * leaf;
    __u16 fn_bit;
    __u16 fn_flags;
    int fn_sernum;
    struct fib6_info * rr_ptr;
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
<code>struct callback_head rcu</code>
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
<b>Field type changed. </b>
<code>struct rt6_info * leaf</code> ➡️ <code>struct fib6_info * leaf</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct rt6_info * rr_ptr</code> ➡️ <code>struct fib6_info * rr_ptr</code>
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
