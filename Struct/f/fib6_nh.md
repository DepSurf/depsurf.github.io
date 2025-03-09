# Struct: <code>fib6_nh</code>

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
struct fib6_nh {
    struct in6_addr nh_gw;
    struct net_device * nh_dev;
    struct lwtunnel_state * nh_lwtstate;
    unsigned int nh_flags;
    atomic_t nh_upper_bound;
    int nh_weight;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct fib6_nh {
    struct in6_addr nh_gw;
    struct net_device * nh_dev;
    struct lwtunnel_state * nh_lwtstate;
    unsigned int nh_flags;
    atomic_t nh_upper_bound;
    int nh_weight;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct fib6_nh {
    struct fib_nh_common nh_common;
    long unsigned int last_probe;
    struct rt6_info * * rt6i_pcpu;
    struct rt6_exception_bucket * rt6i_exception_bucket;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fib6_nh {
    struct fib_nh_common nh_common;
    long unsigned int last_probe;
    struct rt6_info * * rt6i_pcpu;
    struct rt6_exception_bucket * rt6i_exception_bucket;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fib6_nh {
    struct fib_nh_common nh_common;
    long unsigned int last_probe;
    struct rt6_info * * rt6i_pcpu;
    struct rt6_exception_bucket * rt6i_exception_bucket;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fib6_nh {
    struct fib_nh_common nh_common;
    long unsigned int last_probe;
    struct rt6_info * * rt6i_pcpu;
    struct rt6_exception_bucket * rt6i_exception_bucket;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fib6_nh {
    struct fib_nh_common nh_common;
    long unsigned int last_probe;
    struct rt6_info * * rt6i_pcpu;
    struct rt6_exception_bucket * rt6i_exception_bucket;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fib6_nh {
    struct fib_nh_common nh_common;
    long unsigned int last_probe;
    struct rt6_info * * rt6i_pcpu;
    struct rt6_exception_bucket * rt6i_exception_bucket;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fib6_nh {
    struct fib_nh_common nh_common;
    long unsigned int last_probe;
    struct rt6_info * * rt6i_pcpu;
    struct rt6_exception_bucket * rt6i_exception_bucket;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fib6_nh {
    struct fib_nh_common nh_common;
    long unsigned int last_probe;
    struct rt6_info * * rt6i_pcpu;
    struct rt6_exception_bucket * rt6i_exception_bucket;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fib6_nh {
    struct fib_nh_common nh_common;
    long unsigned int last_probe;
    struct rt6_info * * rt6i_pcpu;
    struct rt6_exception_bucket * rt6i_exception_bucket;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fib6_nh {
    struct fib_nh_common nh_common;
    long unsigned int last_probe;
    struct rt6_info * * rt6i_pcpu;
    struct rt6_exception_bucket * rt6i_exception_bucket;
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
struct fib6_nh {
    struct fib_nh_common nh_common;
    long unsigned int last_probe;
    struct rt6_info * * rt6i_pcpu;
    struct rt6_exception_bucket * rt6i_exception_bucket;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fib6_nh {
    struct fib_nh_common nh_common;
    long unsigned int last_probe;
    struct rt6_info * * rt6i_pcpu;
    struct rt6_exception_bucket * rt6i_exception_bucket;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fib6_nh {
    struct fib_nh_common nh_common;
    long unsigned int last_probe;
    struct rt6_info * * rt6i_pcpu;
    struct rt6_exception_bucket * rt6i_exception_bucket;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fib6_nh {
    struct fib_nh_common nh_common;
    long unsigned int last_probe;
    struct rt6_info * * rt6i_pcpu;
    struct rt6_exception_bucket * rt6i_exception_bucket;
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
struct fib6_nh {
    struct fib_nh_common nh_common;
    long unsigned int last_probe;
    struct rt6_info * * rt6i_pcpu;
    struct rt6_exception_bucket * rt6i_exception_bucket;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fib6_nh {
    struct fib_nh_common nh_common;
    long unsigned int last_probe;
    struct rt6_info * * rt6i_pcpu;
    struct rt6_exception_bucket * rt6i_exception_bucket;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fib6_nh {
    struct fib_nh_common nh_common;
    long unsigned int last_probe;
    struct rt6_info * * rt6i_pcpu;
    struct rt6_exception_bucket * rt6i_exception_bucket;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fib6_nh {
    struct fib_nh_common nh_common;
    long unsigned int last_probe;
    struct rt6_info * * rt6i_pcpu;
    struct rt6_exception_bucket * rt6i_exception_bucket;
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
struct fib6_nh {
    struct in6_addr nh_gw;
    struct net_device * nh_dev;
    struct lwtunnel_state * nh_lwtstate;
    unsigned int nh_flags;
    atomic_t nh_upper_bound;
    int nh_weight;
}
```
</details>
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
<code>struct fib_nh_common nh_common</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int last_probe</code>
</li>
<li>
<b>Field added. </b>
<code>struct rt6_info * * rt6i_pcpu</code>
</li>
<li>
<b>Field added. </b>
<code>struct rt6_exception_bucket * rt6i_exception_bucket</code>
</li>
<li>
<b>Field removed. </b>
<code>struct in6_addr nh_gw</code>
</li>
<li>
<b>Field removed. </b>
<code>struct net_device * nh_dev</code>
</li>
<li>
<b>Field removed. </b>
<code>struct lwtunnel_state * nh_lwtstate</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int nh_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t nh_upper_bound</code>
</li>
<li>
<b>Field removed. </b>
<code>int nh_weight</code>
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
