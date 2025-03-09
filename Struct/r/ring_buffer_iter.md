# Struct: <code>ring_buffer_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    long unsigned int next_event;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
    u64 page_stamp;
    struct ring_buffer_event * event;
    int missed_events;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    long unsigned int next_event;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
    u64 page_stamp;
    struct ring_buffer_event * event;
    int missed_events;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    long unsigned int next_event;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
    u64 page_stamp;
    struct ring_buffer_event * event;
    int missed_events;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    long unsigned int next_event;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
    u64 page_stamp;
    struct ring_buffer_event * event;
    int missed_events;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    long unsigned int next_event;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
    u64 page_stamp;
    struct ring_buffer_event * event;
    int missed_events;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    long unsigned int next_event;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
    u64 page_stamp;
    struct ring_buffer_event * event;
    int missed_events;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    long unsigned int next_event;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    long unsigned int cache_pages_removed;
    u64 read_stamp;
    u64 page_stamp;
    struct ring_buffer_event * event;
    int missed_events;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    long unsigned int next_event;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    long unsigned int cache_pages_removed;
    u64 read_stamp;
    u64 page_stamp;
    struct ring_buffer_event * event;
    size_t event_size;
    int missed_events;
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
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
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
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ring_buffer_iter {
    struct ring_buffer_per_cpu * cpu_buffer;
    long unsigned int head;
    struct buffer_page * head_page;
    struct buffer_page * cache_reader_page;
    long unsigned int cache_read;
    u64 read_stamp;
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
<code>long unsigned int next_event</code>
</li>
<li>
<b>Field added. </b>
<code>u64 page_stamp</code>
</li>
<li>
<b>Field added. </b>
<code>struct ring_buffer_event * event</code>
</li>
<li>
<b>Field added. </b>
<code>int missed_events</code>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int cache_pages_removed</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>size_t event_size</code>
</li>
</ul>
</details>
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
