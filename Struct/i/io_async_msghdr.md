# Struct: <code>io_async_msghdr</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct io_async_msghdr {
    struct iovec[8] fast_iov;
    struct iovec * iov;
    struct sockaddr * uaddr;
    struct msghdr msg;
    struct __kernel_sockaddr_storage addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct io_async_msghdr {
    struct iovec[8] fast_iov;
    struct iovec * iov;
    struct sockaddr * uaddr;
    struct msghdr msg;
    struct __kernel_sockaddr_storage addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct io_async_msghdr {
    struct iovec[8] fast_iov;
    struct iovec * free_iov;
    struct sockaddr * uaddr;
    struct msghdr msg;
    struct __kernel_sockaddr_storage addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct io_async_msghdr {
    struct iovec[8] fast_iov;
    struct iovec * free_iov;
    struct sockaddr * uaddr;
    struct msghdr msg;
    struct __kernel_sockaddr_storage addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct io_async_msghdr {
    struct iovec[8] fast_iov;
    struct iovec * free_iov;
    struct sockaddr * uaddr;
    struct msghdr msg;
    struct __kernel_sockaddr_storage addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct io_async_msghdr {
    struct iovec[8] fast_iov;
    struct iovec fast_iov_one;
    __kernel_size_t controllen;
    int namelen;
    __kernel_size_t payloadlen;
    struct io_cache_entry cache;
    struct iovec * free_iov;
    struct sockaddr * uaddr;
    struct msghdr msg;
    struct __kernel_sockaddr_storage addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct io_async_msghdr {
    struct iovec[8] fast_iov;
    struct iovec fast_iov_one;
    __kernel_size_t controllen;
    int namelen;
    __kernel_size_t payloadlen;
    struct io_cache_entry cache;
    struct iovec * free_iov;
    struct sockaddr * uaddr;
    struct msghdr msg;
    struct __kernel_sockaddr_storage addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct io_async_msghdr {
    struct iovec[8] fast_iov;
    struct iovec fast_iov_one;
    __kernel_size_t controllen;
    int namelen;
    __kernel_size_t payloadlen;
    struct io_cache_entry cache;
    struct iovec * free_iov;
    struct sockaddr * uaddr;
    struct msghdr msg;
    struct __kernel_sockaddr_storage addr;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct io_async_msghdr {
    struct iovec[8] fast_iov;
    struct iovec * iov;
    struct sockaddr * uaddr;
    struct msghdr msg;
    struct __kernel_sockaddr_storage addr;
}
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct iovec * free_iov</code>
</li>
<li>
<b>Field removed. </b>
<code>struct iovec * iov</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct iovec fast_iov_one</code>
</li>
<li>
<b>Field added. </b>
<code>__kernel_size_t controllen</code>
</li>
<li>
<b>Field added. </b>
<code>int namelen</code>
</li>
<li>
<b>Field added. </b>
<code>__kernel_size_t payloadlen</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_cache_entry cache</code>
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
