# Struct: <code>nvdimm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int * dsm_mask;
    struct device dev;
    atomic_t busy;
    int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
    const char * dimm_id;
    struct (anon) sec;
    struct delayed_work dwork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
    const char * dimm_id;
    struct (anon) sec;
    struct delayed_work dwork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
    const char * dimm_id;
    struct (anon) sec;
    struct delayed_work dwork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
    const char * dimm_id;
    struct (anon) sec;
    struct delayed_work dwork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
    const char * dimm_id;
    struct (anon) sec;
    struct delayed_work dwork;
    const struct nvdimm_fw_ops * fw_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
    const char * dimm_id;
    struct (anon) sec;
    struct delayed_work dwork;
    const struct nvdimm_fw_ops * fw_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
    const char * dimm_id;
    struct (anon) sec;
    struct delayed_work dwork;
    const struct nvdimm_fw_ops * fw_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
    const char * dimm_id;
    struct (anon) sec;
    struct delayed_work dwork;
    const struct nvdimm_fw_ops * fw_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
    const char * dimm_id;
    struct (anon) sec;
    struct delayed_work dwork;
    const struct nvdimm_fw_ops * fw_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
    const char * dimm_id;
    struct (anon) sec;
    struct delayed_work dwork;
    const struct nvdimm_fw_ops * fw_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
    const char * dimm_id;
    struct (anon) sec;
    struct delayed_work dwork;
    const struct nvdimm_fw_ops * fw_ops;
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
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
    const char * dimm_id;
    struct (anon) sec;
    struct delayed_work dwork;
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
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
    const char * dimm_id;
    struct (anon) sec;
    struct delayed_work dwork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
    const char * dimm_id;
    struct (anon) sec;
    struct delayed_work dwork;
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
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
    const char * dimm_id;
    struct (anon) sec;
    struct delayed_work dwork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
    const char * dimm_id;
    struct (anon) sec;
    struct delayed_work dwork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
    const char * dimm_id;
    struct (anon) sec;
    struct delayed_work dwork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
    const char * dimm_id;
    struct (anon) sec;
    struct delayed_work dwork;
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
<code>long unsigned int cmd_mask</code>
</li>
<li>
<b>Field added. </b>
<code>int num_flush</code>
</li>
<li>
<b>Field added. </b>
<code>struct resource * flush_wpq</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int * dsm_mask</code>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const char * dimm_id</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) sec</code>
</li>
<li>
<b>Field added. </b>
<code>struct delayed_work dwork</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct nvdimm_fw_ops * fw_ops</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct nvdimm {
    long unsigned int flags;
    void * provider_data;
    long unsigned int cmd_mask;
    struct device dev;
    atomic_t busy;
    int id;
    int num_flush;
    struct resource * flush_wpq;
    const char * dimm_id;
    struct (anon) sec;
    struct delayed_work dwork;
}
```
</details>
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
