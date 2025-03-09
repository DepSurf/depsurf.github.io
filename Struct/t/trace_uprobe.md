# Struct: <code>trace_uprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct trace_uprobe {
    struct list_head list;
    struct trace_uprobe_filter filter;
    struct uprobe_consumer consumer;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int nhit;
    struct trace_probe tp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct trace_uprobe {
    struct list_head list;
    struct trace_uprobe_filter filter;
    struct uprobe_consumer consumer;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int nhit;
    struct trace_probe tp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct trace_uprobe {
    struct list_head list;
    struct trace_uprobe_filter filter;
    struct uprobe_consumer consumer;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int nhit;
    struct trace_probe tp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct trace_uprobe {
    struct list_head list;
    struct trace_uprobe_filter filter;
    struct uprobe_consumer consumer;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int nhit;
    struct trace_probe tp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct trace_uprobe {
    struct list_head list;
    struct trace_uprobe_filter filter;
    struct uprobe_consumer consumer;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int nhit;
    struct trace_probe tp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct trace_uprobe {
    struct list_head list;
    struct trace_uprobe_filter filter;
    struct uprobe_consumer consumer;
    struct path path;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int nhit;
    struct trace_probe tp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct trace_uprobe {
    struct dyn_event devent;
    struct trace_uprobe_filter filter;
    struct uprobe_consumer consumer;
    struct path path;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int ref_ctr_offset;
    long unsigned int nhit;
    struct trace_probe tp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct trace_uprobe {
    struct dyn_event devent;
    struct trace_uprobe_filter filter;
    struct uprobe_consumer consumer;
    struct path path;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int ref_ctr_offset;
    long unsigned int nhit;
    struct trace_probe tp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct trace_uprobe {
    struct dyn_event devent;
    struct uprobe_consumer consumer;
    struct path path;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int ref_ctr_offset;
    long unsigned int nhit;
    struct trace_probe tp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct trace_uprobe {
    struct dyn_event devent;
    struct uprobe_consumer consumer;
    struct path path;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int ref_ctr_offset;
    long unsigned int nhit;
    struct trace_probe tp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct trace_uprobe {
    struct dyn_event devent;
    struct uprobe_consumer consumer;
    struct path path;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int ref_ctr_offset;
    long unsigned int nhit;
    struct trace_probe tp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct trace_uprobe {
    struct dyn_event devent;
    struct uprobe_consumer consumer;
    struct path path;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int ref_ctr_offset;
    long unsigned int nhit;
    struct trace_probe tp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct trace_uprobe {
    struct dyn_event devent;
    struct uprobe_consumer consumer;
    struct path path;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int ref_ctr_offset;
    long unsigned int nhit;
    struct trace_probe tp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct trace_uprobe {
    struct dyn_event devent;
    struct uprobe_consumer consumer;
    struct path path;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int ref_ctr_offset;
    long unsigned int nhit;
    struct trace_probe tp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct trace_uprobe {
    struct dyn_event devent;
    struct uprobe_consumer consumer;
    struct path path;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int ref_ctr_offset;
    long unsigned int nhit;
    struct trace_probe tp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct trace_uprobe {
    struct dyn_event devent;
    struct uprobe_consumer consumer;
    struct path path;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int ref_ctr_offset;
    long unsigned int nhit;
    struct trace_probe tp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct trace_uprobe {
    struct dyn_event devent;
    struct uprobe_consumer consumer;
    struct path path;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int ref_ctr_offset;
    long unsigned int nhit;
    struct trace_probe tp;
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
struct trace_uprobe {
    struct dyn_event devent;
    struct uprobe_consumer consumer;
    struct path path;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int ref_ctr_offset;
    long unsigned int nhit;
    struct trace_probe tp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct trace_uprobe {
    struct dyn_event devent;
    struct uprobe_consumer consumer;
    struct path path;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int ref_ctr_offset;
    long unsigned int nhit;
    struct trace_probe tp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct trace_uprobe {
    struct dyn_event devent;
    struct uprobe_consumer consumer;
    struct path path;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int ref_ctr_offset;
    long unsigned int nhit;
    struct trace_probe tp;
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
struct trace_uprobe {
    struct dyn_event devent;
    struct uprobe_consumer consumer;
    struct path path;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int ref_ctr_offset;
    long unsigned int nhit;
    struct trace_probe tp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct trace_uprobe {
    struct dyn_event devent;
    struct uprobe_consumer consumer;
    struct path path;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int ref_ctr_offset;
    long unsigned int nhit;
    struct trace_probe tp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct trace_uprobe {
    struct dyn_event devent;
    struct uprobe_consumer consumer;
    struct path path;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int ref_ctr_offset;
    long unsigned int nhit;
    struct trace_probe tp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct trace_uprobe {
    struct dyn_event devent;
    struct uprobe_consumer consumer;
    struct path path;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int ref_ctr_offset;
    long unsigned int nhit;
    struct trace_probe tp;
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct path path</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct dyn_event devent</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int ref_ctr_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head list</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct trace_uprobe_filter filter</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct trace_uprobe {
    struct dyn_event devent;
    struct uprobe_consumer consumer;
    struct path path;
    struct inode * inode;
    char * filename;
    long unsigned int offset;
    long unsigned int ref_ctr_offset;
    long unsigned int nhit;
    struct trace_probe tp;
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
