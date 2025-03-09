# Struct: <code>rio_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u32, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
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
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
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
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rio_ops {
    int (*)(struct rio_mport *, int, u32, int, u32 *) lcread;
    int (*)(struct rio_mport *, int, u32, int, u32) lcwrite;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32 *) cread;
    int (*)(struct rio_mport *, int, u16, u8, u32, int, u32) cwrite;
    int (*)(struct rio_mport *, int, u16, u16) dsend;
    int (*)(struct rio_mport *, int) pwenable;
    int (*)(struct rio_mport *, void *, int, int) open_outb_mbox;
    void (*)(struct rio_mport *, int) close_outb_mbox;
    int (*)(struct rio_mport *, void *, int, int) open_inb_mbox;
    void (*)(struct rio_mport *, int) close_inb_mbox;
    int (*)(struct rio_mport *, struct rio_dev *, int, void *, size_t) add_outb_message;
    int (*)(struct rio_mport *, int, void *) add_inb_buffer;
    void * (*)(struct rio_mport *, int) get_inb_message;
    int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb;
    void (*)(struct rio_mport *, dma_addr_t) unmap_inb;
    int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport;
    int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb;
    void (*)(struct rio_mport *, u16, u64) unmap_outb;
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct rio_mport *, struct rio_mport_attr *) query_mport</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct rio_mport *, u16, u64, u32, u32, dma_addr_t *) map_outb</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct rio_mport *, u16, u64) unmap_outb</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct rio_mport *, dma_addr_t, u64, u32, u32) map_inb</code> ➡️ <code>int (*)(struct rio_mport *, dma_addr_t, u64, u64, u32) map_inb</code>
</li>
</ul>
</details>
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
