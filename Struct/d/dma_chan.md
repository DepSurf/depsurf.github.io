# Struct: <code>dma_chan</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dma_chan {
    int lock;
    const char * device_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dma_chan {
    int lock;
    const char * device_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dma_chan {
    int lock;
    const char * device_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dma_chan {
    int lock;
    const char * device_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dma_chan {
    int lock;
    const char * device_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dma_chan {
    int lock;
    const char * device_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dma_chan {
    int lock;
    const char * device_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dma_chan {
    int lock;
    const char * device_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dma_chan {
    int lock;
    const char * device_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dma_chan {
    int lock;
    const char * device_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dma_chan {
    int lock;
    const char * device_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dma_chan {
    int lock;
    const char * device_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dma_chan {
    int lock;
    const char * device_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dma_chan {
    int lock;
    const char * device_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dma_chan {
    int lock;
    const char * device_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dma_chan {
    int lock;
    const char * device_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dma_chan {
    int lock;
    const char * device_id;
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
struct dma_chan {
    struct dma_device * device;
    dma_cookie_t cookie;
    dma_cookie_t completed_cookie;
    int chan_id;
    struct dma_chan_dev * dev;
    struct list_head device_node;
    struct dma_chan_percpu * local;
    int client_count;
    int table_count;
    struct dma_router * router;
    void * route_data;
    void * private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dma_chan {
    struct dma_device * device;
    dma_cookie_t cookie;
    dma_cookie_t completed_cookie;
    int chan_id;
    struct dma_chan_dev * dev;
    struct list_head device_node;
    struct dma_chan_percpu * local;
    int client_count;
    int table_count;
    struct dma_router * router;
    void * route_data;
    void * private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dma_chan {
    int lock;
    const char * device_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dma_chan {
    struct dma_device * device;
    dma_cookie_t cookie;
    dma_cookie_t completed_cookie;
    int chan_id;
    struct dma_chan_dev * dev;
    struct list_head device_node;
    struct dma_chan_percpu * local;
    int client_count;
    int table_count;
    struct dma_router * router;
    void * route_data;
    void * private;
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
struct dma_chan {
    int lock;
    const char * device_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dma_chan {
    int lock;
    const char * device_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dma_chan {
    int lock;
    const char * device_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dma_chan {
    int lock;
    const char * device_id;
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct dma_device * device</code>
</li>
<li>
<b>Field added. </b>
<code>dma_cookie_t cookie</code>
</li>
<li>
<b>Field added. </b>
<code>dma_cookie_t completed_cookie</code>
</li>
<li>
<b>Field added. </b>
<code>int chan_id</code>
</li>
<li>
<b>Field added. </b>
<code>struct dma_chan_dev * dev</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head device_node</code>
</li>
<li>
<b>Field added. </b>
<code>struct dma_chan_percpu * local</code>
</li>
<li>
<b>Field added. </b>
<code>int client_count</code>
</li>
<li>
<b>Field added. </b>
<code>int table_count</code>
</li>
<li>
<b>Field added. </b>
<code>struct dma_router * router</code>
</li>
<li>
<b>Field added. </b>
<code>void * route_data</code>
</li>
<li>
<b>Field added. </b>
<code>void * private</code>
</li>
<li>
<b>Field removed. </b>
<code>int lock</code>
</li>
<li>
<b>Field removed. </b>
<code>const char * device_id</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct dma_device * device</code>
</li>
<li>
<b>Field added. </b>
<code>dma_cookie_t cookie</code>
</li>
<li>
<b>Field added. </b>
<code>dma_cookie_t completed_cookie</code>
</li>
<li>
<b>Field added. </b>
<code>int chan_id</code>
</li>
<li>
<b>Field added. </b>
<code>struct dma_chan_dev * dev</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head device_node</code>
</li>
<li>
<b>Field added. </b>
<code>struct dma_chan_percpu * local</code>
</li>
<li>
<b>Field added. </b>
<code>int client_count</code>
</li>
<li>
<b>Field added. </b>
<code>int table_count</code>
</li>
<li>
<b>Field added. </b>
<code>struct dma_router * router</code>
</li>
<li>
<b>Field added. </b>
<code>void * route_data</code>
</li>
<li>
<b>Field added. </b>
<code>void * private</code>
</li>
<li>
<b>Field removed. </b>
<code>int lock</code>
</li>
<li>
<b>Field removed. </b>
<code>const char * device_id</code>
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
<b>Field added. </b>
<code>struct dma_device * device</code>
</li>
<li>
<b>Field added. </b>
<code>dma_cookie_t cookie</code>
</li>
<li>
<b>Field added. </b>
<code>dma_cookie_t completed_cookie</code>
</li>
<li>
<b>Field added. </b>
<code>int chan_id</code>
</li>
<li>
<b>Field added. </b>
<code>struct dma_chan_dev * dev</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head device_node</code>
</li>
<li>
<b>Field added. </b>
<code>struct dma_chan_percpu * local</code>
</li>
<li>
<b>Field added. </b>
<code>int client_count</code>
</li>
<li>
<b>Field added. </b>
<code>int table_count</code>
</li>
<li>
<b>Field added. </b>
<code>struct dma_router * router</code>
</li>
<li>
<b>Field added. </b>
<code>void * route_data</code>
</li>
<li>
<b>Field added. </b>
<code>void * private</code>
</li>
<li>
<b>Field removed. </b>
<code>int lock</code>
</li>
<li>
<b>Field removed. </b>
<code>const char * device_id</code>
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
