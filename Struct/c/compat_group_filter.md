# Struct: <code>compat_group_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct compat_group_filter {
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[1] gf_slist;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct compat_group_filter {
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[1] gf_slist;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct compat_group_filter {
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[1] gf_slist;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct compat_group_filter {
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[1] gf_slist;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct compat_group_filter {
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[1] gf_slist;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct compat_group_filter {
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[1] gf_slist;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct compat_group_filter {
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[1] gf_slist;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct compat_group_filter {
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[1] gf_slist;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct compat_group_filter {
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[1] gf_slist;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct compat_group_filter {
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[1] gf_slist;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct compat_group_filter {
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[1] gf_slist;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct compat_group_filter {
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[1] gf_slist;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct compat_group_filter {
    __u32 gf_interface_aux;
    struct __kernel_sockaddr_storage gf_group_aux;
    __u32 gf_fmode_aux;
    __u32 gf_numsrc_aux;
    struct __kernel_sockaddr_storage[1] gf_slist;
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[0] gf_slist_flex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct compat_group_filter {
    __u32 gf_interface_aux;
    struct __kernel_sockaddr_storage gf_group_aux;
    __u32 gf_fmode_aux;
    __u32 gf_numsrc_aux;
    struct __kernel_sockaddr_storage[1] gf_slist;
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[0] gf_slist_flex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct compat_group_filter {
    __u32 gf_interface_aux;
    struct __kernel_sockaddr_storage gf_group_aux;
    __u32 gf_fmode_aux;
    __u32 gf_numsrc_aux;
    struct __kernel_sockaddr_storage[1] gf_slist;
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[0] gf_slist_flex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct compat_group_filter {
    __u32 gf_interface_aux;
    struct __kernel_sockaddr_storage gf_group_aux;
    __u32 gf_fmode_aux;
    __u32 gf_numsrc_aux;
    struct __kernel_sockaddr_storage[1] gf_slist;
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[0] gf_slist_flex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct compat_group_filter {
    __u32 gf_interface_aux;
    struct __kernel_sockaddr_storage gf_group_aux;
    __u32 gf_fmode_aux;
    __u32 gf_numsrc_aux;
    struct __kernel_sockaddr_storage[1] gf_slist;
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[0] gf_slist_flex;
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
struct compat_group_filter {
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[1] gf_slist;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct compat_group_filter {
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[1] gf_slist;
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct compat_group_filter {
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[1] gf_slist;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct compat_group_filter {
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[1] gf_slist;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct compat_group_filter {
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[1] gf_slist;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct compat_group_filter {
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[1] gf_slist;
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
<code>__u32 gf_interface_aux</code>
</li>
<li>
<b>Field added. </b>
<code>struct __kernel_sockaddr_storage gf_group_aux</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 gf_fmode_aux</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 gf_numsrc_aux</code>
</li>
<li>
<b>Field added. </b>
<code>struct __kernel_sockaddr_storage[0] gf_slist_flex</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct compat_group_filter {
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[1] gf_slist;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct compat_group_filter {
    __u32 gf_interface;
    struct __kernel_sockaddr_storage gf_group;
    __u32 gf_fmode;
    __u32 gf_numsrc;
    struct __kernel_sockaddr_storage[1] gf_slist;
}
```
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
