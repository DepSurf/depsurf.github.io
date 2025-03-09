# Struct: <code>spi_controller_mem_ops</code>

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
struct spi_controller_mem_ops {
    int (*)(struct spi_mem *, struct spi_mem_op *) adjust_op_size;
    bool (*)(struct spi_mem *, const struct spi_mem_op *) supports_op;
    int (*)(struct spi_mem *, const struct spi_mem_op *) exec_op;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct spi_controller_mem_ops {
    int (*)(struct spi_mem *, struct spi_mem_op *) adjust_op_size;
    bool (*)(struct spi_mem *, const struct spi_mem_op *) supports_op;
    int (*)(struct spi_mem *, const struct spi_mem_op *) exec_op;
    const char * (*)(struct spi_mem *) get_name;
    int (*)(struct spi_mem_dirmap_desc *) dirmap_create;
    void (*)(struct spi_mem_dirmap_desc *) dirmap_destroy;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, void *) dirmap_read;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, const void *) dirmap_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct spi_controller_mem_ops {
    int (*)(struct spi_mem *, struct spi_mem_op *) adjust_op_size;
    bool (*)(struct spi_mem *, const struct spi_mem_op *) supports_op;
    int (*)(struct spi_mem *, const struct spi_mem_op *) exec_op;
    const char * (*)(struct spi_mem *) get_name;
    int (*)(struct spi_mem_dirmap_desc *) dirmap_create;
    void (*)(struct spi_mem_dirmap_desc *) dirmap_destroy;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, void *) dirmap_read;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, const void *) dirmap_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct spi_controller_mem_ops {
    int (*)(struct spi_mem *, struct spi_mem_op *) adjust_op_size;
    bool (*)(struct spi_mem *, const struct spi_mem_op *) supports_op;
    int (*)(struct spi_mem *, const struct spi_mem_op *) exec_op;
    const char * (*)(struct spi_mem *) get_name;
    int (*)(struct spi_mem_dirmap_desc *) dirmap_create;
    void (*)(struct spi_mem_dirmap_desc *) dirmap_destroy;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, void *) dirmap_read;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, const void *) dirmap_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct spi_controller_mem_ops {
    int (*)(struct spi_mem *, struct spi_mem_op *) adjust_op_size;
    bool (*)(struct spi_mem *, const struct spi_mem_op *) supports_op;
    int (*)(struct spi_mem *, const struct spi_mem_op *) exec_op;
    const char * (*)(struct spi_mem *) get_name;
    int (*)(struct spi_mem_dirmap_desc *) dirmap_create;
    void (*)(struct spi_mem_dirmap_desc *) dirmap_destroy;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, void *) dirmap_read;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, const void *) dirmap_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct spi_controller_mem_ops {
    int (*)(struct spi_mem *, struct spi_mem_op *) adjust_op_size;
    bool (*)(struct spi_mem *, const struct spi_mem_op *) supports_op;
    int (*)(struct spi_mem *, const struct spi_mem_op *) exec_op;
    const char * (*)(struct spi_mem *) get_name;
    int (*)(struct spi_mem_dirmap_desc *) dirmap_create;
    void (*)(struct spi_mem_dirmap_desc *) dirmap_destroy;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, void *) dirmap_read;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, const void *) dirmap_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct spi_controller_mem_ops {
    int (*)(struct spi_mem *, struct spi_mem_op *) adjust_op_size;
    bool (*)(struct spi_mem *, const struct spi_mem_op *) supports_op;
    int (*)(struct spi_mem *, const struct spi_mem_op *) exec_op;
    const char * (*)(struct spi_mem *) get_name;
    int (*)(struct spi_mem_dirmap_desc *) dirmap_create;
    void (*)(struct spi_mem_dirmap_desc *) dirmap_destroy;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, void *) dirmap_read;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, const void *) dirmap_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct spi_controller_mem_ops {
    int (*)(struct spi_mem *, struct spi_mem_op *) adjust_op_size;
    bool (*)(struct spi_mem *, const struct spi_mem_op *) supports_op;
    int (*)(struct spi_mem *, const struct spi_mem_op *) exec_op;
    const char * (*)(struct spi_mem *) get_name;
    int (*)(struct spi_mem_dirmap_desc *) dirmap_create;
    void (*)(struct spi_mem_dirmap_desc *) dirmap_destroy;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, void *) dirmap_read;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, const void *) dirmap_write;
    int (*)(struct spi_mem *, const struct spi_mem_op *, u16, u16, long unsigned int, long unsigned int, long unsigned int) poll_status;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct spi_controller_mem_ops {
    int (*)(struct spi_mem *, struct spi_mem_op *) adjust_op_size;
    bool (*)(struct spi_mem *, const struct spi_mem_op *) supports_op;
    int (*)(struct spi_mem *, const struct spi_mem_op *) exec_op;
    const char * (*)(struct spi_mem *) get_name;
    int (*)(struct spi_mem_dirmap_desc *) dirmap_create;
    void (*)(struct spi_mem_dirmap_desc *) dirmap_destroy;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, void *) dirmap_read;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, const void *) dirmap_write;
    int (*)(struct spi_mem *, const struct spi_mem_op *, u16, u16, long unsigned int, long unsigned int, long unsigned int) poll_status;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct spi_controller_mem_ops {
    int (*)(struct spi_mem *, struct spi_mem_op *) adjust_op_size;
    bool (*)(struct spi_mem *, const struct spi_mem_op *) supports_op;
    int (*)(struct spi_mem *, const struct spi_mem_op *) exec_op;
    const char * (*)(struct spi_mem *) get_name;
    int (*)(struct spi_mem_dirmap_desc *) dirmap_create;
    void (*)(struct spi_mem_dirmap_desc *) dirmap_destroy;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, void *) dirmap_read;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, const void *) dirmap_write;
    int (*)(struct spi_mem *, const struct spi_mem_op *, u16, u16, long unsigned int, long unsigned int, long unsigned int) poll_status;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct spi_controller_mem_ops {
    int (*)(struct spi_mem *, struct spi_mem_op *) adjust_op_size;
    bool (*)(struct spi_mem *, const struct spi_mem_op *) supports_op;
    int (*)(struct spi_mem *, const struct spi_mem_op *) exec_op;
    const char * (*)(struct spi_mem *) get_name;
    int (*)(struct spi_mem_dirmap_desc *) dirmap_create;
    void (*)(struct spi_mem_dirmap_desc *) dirmap_destroy;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, void *) dirmap_read;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, const void *) dirmap_write;
    int (*)(struct spi_mem *, const struct spi_mem_op *, u16, u16, long unsigned int, long unsigned int, long unsigned int) poll_status;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct spi_controller_mem_ops {
    int (*)(struct spi_mem *, struct spi_mem_op *) adjust_op_size;
    bool (*)(struct spi_mem *, const struct spi_mem_op *) supports_op;
    int (*)(struct spi_mem *, const struct spi_mem_op *) exec_op;
    const char * (*)(struct spi_mem *) get_name;
    int (*)(struct spi_mem_dirmap_desc *) dirmap_create;
    void (*)(struct spi_mem_dirmap_desc *) dirmap_destroy;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, void *) dirmap_read;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, const void *) dirmap_write;
    int (*)(struct spi_mem *, const struct spi_mem_op *, u16, u16, long unsigned int, long unsigned int, long unsigned int) poll_status;
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
struct spi_controller_mem_ops {
    int (*)(struct spi_mem *, struct spi_mem_op *) adjust_op_size;
    bool (*)(struct spi_mem *, const struct spi_mem_op *) supports_op;
    int (*)(struct spi_mem *, const struct spi_mem_op *) exec_op;
    const char * (*)(struct spi_mem *) get_name;
    int (*)(struct spi_mem_dirmap_desc *) dirmap_create;
    void (*)(struct spi_mem_dirmap_desc *) dirmap_destroy;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, void *) dirmap_read;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, const void *) dirmap_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct spi_controller_mem_ops {
    int (*)(struct spi_mem *, struct spi_mem_op *) adjust_op_size;
    bool (*)(struct spi_mem *, const struct spi_mem_op *) supports_op;
    int (*)(struct spi_mem *, const struct spi_mem_op *) exec_op;
    const char * (*)(struct spi_mem *) get_name;
    int (*)(struct spi_mem_dirmap_desc *) dirmap_create;
    void (*)(struct spi_mem_dirmap_desc *) dirmap_destroy;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, void *) dirmap_read;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, const void *) dirmap_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct spi_controller_mem_ops {
    int (*)(struct spi_mem *, struct spi_mem_op *) adjust_op_size;
    bool (*)(struct spi_mem *, const struct spi_mem_op *) supports_op;
    int (*)(struct spi_mem *, const struct spi_mem_op *) exec_op;
    const char * (*)(struct spi_mem *) get_name;
    int (*)(struct spi_mem_dirmap_desc *) dirmap_create;
    void (*)(struct spi_mem_dirmap_desc *) dirmap_destroy;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, void *) dirmap_read;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, const void *) dirmap_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct spi_controller_mem_ops {
    int (*)(struct spi_mem *, struct spi_mem_op *) adjust_op_size;
    bool (*)(struct spi_mem *, const struct spi_mem_op *) supports_op;
    int (*)(struct spi_mem *, const struct spi_mem_op *) exec_op;
    const char * (*)(struct spi_mem *) get_name;
    int (*)(struct spi_mem_dirmap_desc *) dirmap_create;
    void (*)(struct spi_mem_dirmap_desc *) dirmap_destroy;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, void *) dirmap_read;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, const void *) dirmap_write;
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
struct spi_controller_mem_ops {
    int (*)(struct spi_mem *, struct spi_mem_op *) adjust_op_size;
    bool (*)(struct spi_mem *, const struct spi_mem_op *) supports_op;
    int (*)(struct spi_mem *, const struct spi_mem_op *) exec_op;
    const char * (*)(struct spi_mem *) get_name;
    int (*)(struct spi_mem_dirmap_desc *) dirmap_create;
    void (*)(struct spi_mem_dirmap_desc *) dirmap_destroy;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, void *) dirmap_read;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, const void *) dirmap_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct spi_controller_mem_ops {
    int (*)(struct spi_mem *, struct spi_mem_op *) adjust_op_size;
    bool (*)(struct spi_mem *, const struct spi_mem_op *) supports_op;
    int (*)(struct spi_mem *, const struct spi_mem_op *) exec_op;
    const char * (*)(struct spi_mem *) get_name;
    int (*)(struct spi_mem_dirmap_desc *) dirmap_create;
    void (*)(struct spi_mem_dirmap_desc *) dirmap_destroy;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, void *) dirmap_read;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, const void *) dirmap_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct spi_controller_mem_ops {
    int (*)(struct spi_mem *, struct spi_mem_op *) adjust_op_size;
    bool (*)(struct spi_mem *, const struct spi_mem_op *) supports_op;
    int (*)(struct spi_mem *, const struct spi_mem_op *) exec_op;
    const char * (*)(struct spi_mem *) get_name;
    int (*)(struct spi_mem_dirmap_desc *) dirmap_create;
    void (*)(struct spi_mem_dirmap_desc *) dirmap_destroy;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, void *) dirmap_read;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, const void *) dirmap_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct spi_controller_mem_ops {
    int (*)(struct spi_mem *, struct spi_mem_op *) adjust_op_size;
    bool (*)(struct spi_mem *, const struct spi_mem_op *) supports_op;
    int (*)(struct spi_mem *, const struct spi_mem_op *) exec_op;
    const char * (*)(struct spi_mem *) get_name;
    int (*)(struct spi_mem_dirmap_desc *) dirmap_create;
    void (*)(struct spi_mem_dirmap_desc *) dirmap_destroy;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, void *) dirmap_read;
    ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, const void *) dirmap_write;
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
struct spi_controller_mem_ops {
    int (*)(struct spi_mem *, struct spi_mem_op *) adjust_op_size;
    bool (*)(struct spi_mem *, const struct spi_mem_op *) supports_op;
    int (*)(struct spi_mem *, const struct spi_mem_op *) exec_op;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const char * (*)(struct spi_mem *) get_name</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct spi_mem_dirmap_desc *) dirmap_create</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct spi_mem_dirmap_desc *) dirmap_destroy</code>
</li>
<li>
<b>Field added. </b>
<code>ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, void *) dirmap_read</code>
</li>
<li>
<b>Field added. </b>
<code>ssize_t (*)(struct spi_mem_dirmap_desc *, u64, size_t, const void *) dirmap_write</code>
</li>
</ul>
</details>
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
<code>int (*)(struct spi_mem *, const struct spi_mem_op *, u16, u16, long unsigned int, long unsigned int, long unsigned int) poll_status</code>
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
