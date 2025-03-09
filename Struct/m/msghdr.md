# Struct: <code>msghdr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    struct iov_iter msg_iter;
    void * msg_control;
    __kernel_size_t msg_controllen;
    unsigned int msg_flags;
    struct kiocb * msg_iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    struct iov_iter msg_iter;
    void * msg_control;
    __kernel_size_t msg_controllen;
    unsigned int msg_flags;
    struct kiocb * msg_iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    struct iov_iter msg_iter;
    void * msg_control;
    __kernel_size_t msg_controllen;
    unsigned int msg_flags;
    struct kiocb * msg_iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    struct iov_iter msg_iter;
    void * msg_control;
    __kernel_size_t msg_controllen;
    unsigned int msg_flags;
    struct kiocb * msg_iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    struct iov_iter msg_iter;
    void * msg_control;
    __kernel_size_t msg_controllen;
    unsigned int msg_flags;
    struct kiocb * msg_iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    struct iov_iter msg_iter;
    void * msg_control;
    __kernel_size_t msg_controllen;
    unsigned int msg_flags;
    struct kiocb * msg_iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    struct iov_iter msg_iter;
    void * msg_control;
    __kernel_size_t msg_controllen;
    unsigned int msg_flags;
    struct kiocb * msg_iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    struct iov_iter msg_iter;
    void * msg_control;
    __kernel_size_t msg_controllen;
    unsigned int msg_flags;
    struct kiocb * msg_iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    struct iov_iter msg_iter;
    void * msg_control;
    __kernel_size_t msg_controllen;
    unsigned int msg_flags;
    struct kiocb * msg_iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    struct iov_iter msg_iter;
    void * msg_control;
    void * msg_control_user;
    bool msg_control_is_user;
    __kernel_size_t msg_controllen;
    unsigned int msg_flags;
    struct kiocb * msg_iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    struct iov_iter msg_iter;
    void * msg_control;
    void * msg_control_user;
    bool msg_control_is_user;
    __kernel_size_t msg_controllen;
    unsigned int msg_flags;
    struct kiocb * msg_iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    struct iov_iter msg_iter;
    void * msg_control;
    void * msg_control_user;
    bool msg_control_is_user;
    __kernel_size_t msg_controllen;
    unsigned int msg_flags;
    struct kiocb * msg_iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    struct iov_iter msg_iter;
    void * msg_control;
    void * msg_control_user;
    bool msg_control_is_user;
    __kernel_size_t msg_controllen;
    unsigned int msg_flags;
    struct kiocb * msg_iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    int msg_inq;
    struct iov_iter msg_iter;
    void * msg_control;
    void * msg_control_user;
    bool msg_control_is_user;
    bool msg_get_inq;
    unsigned int msg_flags;
    __kernel_size_t msg_controllen;
    struct kiocb * msg_iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    int msg_inq;
    struct iov_iter msg_iter;
    void * msg_control;
    void * msg_control_user;
    bool msg_control_is_user;
    bool msg_get_inq;
    unsigned int msg_flags;
    __kernel_size_t msg_controllen;
    struct kiocb * msg_iocb;
    struct ubuf_info * msg_ubuf;
    int (*)(struct sock *, struct sk_buff *, struct iov_iter *, size_t) sg_from_iter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    int msg_inq;
    struct iov_iter msg_iter;
    void * msg_control;
    void * msg_control_user;
    bool msg_control_is_user;
    bool msg_get_inq;
    unsigned int msg_flags;
    __kernel_size_t msg_controllen;
    struct kiocb * msg_iocb;
    struct ubuf_info * msg_ubuf;
    int (*)(struct sock *, struct sk_buff *, struct iov_iter *, size_t) sg_from_iter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    int msg_inq;
    struct iov_iter msg_iter;
    void * msg_control;
    void * msg_control_user;
    bool msg_control_is_user;
    bool msg_get_inq;
    unsigned int msg_flags;
    __kernel_size_t msg_controllen;
    struct kiocb * msg_iocb;
    struct ubuf_info * msg_ubuf;
    int (*)(struct sock *, struct sk_buff *, struct iov_iter *, size_t) sg_from_iter;
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
struct msghdr {
    void * msg_name;
    int msg_namelen;
    struct iov_iter msg_iter;
    void * msg_control;
    __kernel_size_t msg_controllen;
    unsigned int msg_flags;
    struct kiocb * msg_iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    struct iov_iter msg_iter;
    void * msg_control;
    __kernel_size_t msg_controllen;
    unsigned int msg_flags;
    struct kiocb * msg_iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    struct iov_iter msg_iter;
    void * msg_control;
    __kernel_size_t msg_controllen;
    unsigned int msg_flags;
    struct kiocb * msg_iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    struct iov_iter msg_iter;
    void * msg_control;
    __kernel_size_t msg_controllen;
    unsigned int msg_flags;
    struct kiocb * msg_iocb;
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
struct msghdr {
    void * msg_name;
    int msg_namelen;
    struct iov_iter msg_iter;
    void * msg_control;
    __kernel_size_t msg_controllen;
    unsigned int msg_flags;
    struct kiocb * msg_iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    struct iov_iter msg_iter;
    void * msg_control;
    __kernel_size_t msg_controllen;
    unsigned int msg_flags;
    struct kiocb * msg_iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    struct iov_iter msg_iter;
    void * msg_control;
    __kernel_size_t msg_controllen;
    unsigned int msg_flags;
    struct kiocb * msg_iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct msghdr {
    void * msg_name;
    int msg_namelen;
    struct iov_iter msg_iter;
    void * msg_control;
    __kernel_size_t msg_controllen;
    unsigned int msg_flags;
    struct kiocb * msg_iocb;
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * msg_control_user</code>
</li>
<li>
<b>Field added. </b>
<code>bool msg_control_is_user</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int msg_inq</code>
</li>
<li>
<b>Field added. </b>
<code>bool msg_get_inq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct ubuf_info * msg_ubuf</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sock *, struct sk_buff *, struct iov_iter *, size_t) sg_from_iter</code>
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
