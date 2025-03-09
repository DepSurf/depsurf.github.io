# Struct: <code>sdio_func</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8[4] tmpbuf;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8[4] tmpbuf;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8[4] tmpbuf;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8 * tmpbuf;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8 * tmpbuf;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8 * tmpbuf;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8 * tmpbuf;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8 * tmpbuf;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8 * tmpbuf;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8 * tmpbuf;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8 * tmpbuf;
    u8 major_rev;
    u8 minor_rev;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8 * tmpbuf;
    u8 major_rev;
    u8 minor_rev;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8 * tmpbuf;
    u8 major_rev;
    u8 minor_rev;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8 * tmpbuf;
    u8 major_rev;
    u8 minor_rev;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8 * tmpbuf;
    u8 major_rev;
    u8 minor_rev;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8 * tmpbuf;
    u8 major_rev;
    u8 minor_rev;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8 * tmpbuf;
    u8 major_rev;
    u8 minor_rev;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
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
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8 * tmpbuf;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8 * tmpbuf;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8 * tmpbuf;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8 * tmpbuf;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
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
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8 * tmpbuf;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8 * tmpbuf;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8 * tmpbuf;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>u8[4] tmpbuf</code> ➡️ <code>u8 * tmpbuf</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 major_rev</code>
</li>
<li>
<b>Field added. </b>
<code>u8 minor_rev</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct sdio_func {
    struct mmc_card * card;
    struct device dev;
    sdio_irq_handler_t * irq_handler;
    unsigned int num;
    unsigned char class;
    short unsigned int vendor;
    short unsigned int device;
    unsigned int max_blksize;
    unsigned int cur_blksize;
    unsigned int enable_timeout;
    unsigned int state;
    u8 * tmpbuf;
    unsigned int num_info;
    const char * * info;
    struct sdio_func_tuple * tuples;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
