# Struct: <code>iomap_dio</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct iomap_dio {
    struct kiocb * iocb;
    iomap_dio_end_io_t * end_io;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    struct (anon) submit;
    struct (anon) aio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct iomap_dio {
    struct kiocb * iocb;
    iomap_dio_end_io_t * end_io;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    struct (anon) submit;
    struct (anon) aio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct iomap_dio {
    struct kiocb * iocb;
    iomap_dio_end_io_t * end_io;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    struct (anon) submit;
    struct (anon) aio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct iomap_dio {
    struct kiocb * iocb;
    iomap_dio_end_io_t * end_io;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    bool wait_for_completion;
    struct (anon) submit;
    struct (anon) aio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct iomap_dio {
    struct kiocb * iocb;
    iomap_dio_end_io_t * end_io;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    bool wait_for_completion;
    struct (anon) submit;
    struct (anon) aio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct iomap_dio {
    struct kiocb * iocb;
    iomap_dio_end_io_t * end_io;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    bool wait_for_completion;
    struct (anon) submit;
    struct (anon) aio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct iomap_dio {
    struct kiocb * iocb;
    const struct iomap_dio_ops * dops;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    bool wait_for_completion;
    struct (anon) submit;
    struct (anon) aio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct iomap_dio {
    struct kiocb * iocb;
    const struct iomap_dio_ops * dops;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    bool wait_for_completion;
    struct (anon) submit;
    struct (anon) aio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct iomap_dio {
    struct kiocb * iocb;
    const struct iomap_dio_ops * dops;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    bool wait_for_completion;
    struct (anon) submit;
    struct (anon) aio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct iomap_dio {
    struct kiocb * iocb;
    const struct iomap_dio_ops * dops;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    bool wait_for_completion;
    struct (anon) submit;
    struct (anon) aio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct iomap_dio {
    struct kiocb * iocb;
    const struct iomap_dio_ops * dops;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    bool wait_for_completion;
    struct (anon) submit;
    struct (anon) aio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct iomap_dio {
    struct kiocb * iocb;
    const struct iomap_dio_ops * dops;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    size_t done_before;
    bool wait_for_completion;
    struct (anon) submit;
    struct (anon) aio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct iomap_dio {
    struct kiocb * iocb;
    const struct iomap_dio_ops * dops;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    size_t done_before;
    bool wait_for_completion;
    struct (anon) submit;
    struct (anon) aio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct iomap_dio {
    struct kiocb * iocb;
    const struct iomap_dio_ops * dops;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    size_t done_before;
    bool wait_for_completion;
    struct (anon) submit;
    struct (anon) aio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct iomap_dio {
    struct kiocb * iocb;
    const struct iomap_dio_ops * dops;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    size_t done_before;
    bool wait_for_completion;
    struct (anon) submit;
    struct (anon) aio;
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
struct iomap_dio {
    struct kiocb * iocb;
    const struct iomap_dio_ops * dops;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    bool wait_for_completion;
    struct (anon) submit;
    struct (anon) aio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct iomap_dio {
    struct kiocb * iocb;
    const struct iomap_dio_ops * dops;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    bool wait_for_completion;
    struct (anon) submit;
    struct (anon) aio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct iomap_dio {
    struct kiocb * iocb;
    const struct iomap_dio_ops * dops;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    bool wait_for_completion;
    struct (anon) submit;
    struct (anon) aio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct iomap_dio {
    struct kiocb * iocb;
    const struct iomap_dio_ops * dops;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    bool wait_for_completion;
    struct (anon) submit;
    struct (anon) aio;
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
struct iomap_dio {
    struct kiocb * iocb;
    const struct iomap_dio_ops * dops;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    bool wait_for_completion;
    struct (anon) submit;
    struct (anon) aio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct iomap_dio {
    struct kiocb * iocb;
    const struct iomap_dio_ops * dops;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    bool wait_for_completion;
    struct (anon) submit;
    struct (anon) aio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct iomap_dio {
    struct kiocb * iocb;
    const struct iomap_dio_ops * dops;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    bool wait_for_completion;
    struct (anon) submit;
    struct (anon) aio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct iomap_dio {
    struct kiocb * iocb;
    const struct iomap_dio_ops * dops;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    bool wait_for_completion;
    struct (anon) submit;
    struct (anon) aio;
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct iomap_dio {
    struct kiocb * iocb;
    iomap_dio_end_io_t * end_io;
    loff_t i_size;
    loff_t size;
    atomic_t ref;
    unsigned int flags;
    int error;
    struct (anon) submit;
    struct (anon) aio;
}
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<code>bool wait_for_completion</code>
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct iomap_dio_ops * dops</code>
</li>
<li>
<b>Field removed. </b>
<code>iomap_dio_end_io_t * end_io</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>size_t done_before</code>
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
