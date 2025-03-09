# Struct: <code>scsi_eh_save</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct request * next_rq;
    unsigned char[16] eh_cmnd;
    struct scatterlist sense_sgl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct request * next_rq;
    unsigned char[16] eh_cmnd;
    struct scatterlist sense_sgl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct request * next_rq;
    unsigned char[16] eh_cmnd;
    struct scatterlist sense_sgl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    int eh_eflags;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct request * next_rq;
    unsigned char[16] eh_cmnd;
    struct scatterlist sense_sgl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    int eh_eflags;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct request * next_rq;
    unsigned char[16] eh_cmnd;
    struct scatterlist sense_sgl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    int eh_eflags;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct request * next_rq;
    unsigned char[16] eh_cmnd;
    struct scatterlist sense_sgl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    int eh_eflags;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct request * next_rq;
    unsigned char[16] eh_cmnd;
    struct scatterlist sense_sgl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    int eh_eflags;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    unsigned char[16] eh_cmnd;
    struct scatterlist sense_sgl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    unsigned int resid_len;
    int eh_eflags;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    unsigned char[16] eh_cmnd;
    struct scatterlist sense_sgl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    unsigned int resid_len;
    int eh_eflags;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    unsigned char[16] eh_cmnd;
    struct scatterlist sense_sgl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    unsigned int resid_len;
    int eh_eflags;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    unsigned char[16] eh_cmnd;
    struct scatterlist sense_sgl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    unsigned int resid_len;
    int eh_eflags;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    unsigned char[16] eh_cmnd;
    struct scatterlist sense_sgl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    unsigned int resid_len;
    int eh_eflags;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    unsigned char[16] eh_cmnd;
    struct scatterlist sense_sgl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    unsigned int resid_len;
    int eh_eflags;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char[32] cmnd;
    struct scsi_data_buffer sdb;
    struct scatterlist sense_sgl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    unsigned int resid_len;
    int eh_eflags;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char[32] cmnd;
    struct scsi_data_buffer sdb;
    struct scatterlist sense_sgl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    unsigned int resid_len;
    int eh_eflags;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char[32] cmnd;
    struct scsi_data_buffer sdb;
    struct scatterlist sense_sgl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    unsigned int resid_len;
    int eh_eflags;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char[32] cmnd;
    struct scsi_data_buffer sdb;
    struct scatterlist sense_sgl;
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
struct scsi_eh_save {
    int result;
    unsigned int resid_len;
    int eh_eflags;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    unsigned char[16] eh_cmnd;
    struct scatterlist sense_sgl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    unsigned int resid_len;
    int eh_eflags;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    unsigned char[16] eh_cmnd;
    struct scatterlist sense_sgl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    unsigned int resid_len;
    int eh_eflags;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    unsigned char[16] eh_cmnd;
    struct scatterlist sense_sgl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    unsigned int resid_len;
    int eh_eflags;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    unsigned char[16] eh_cmnd;
    struct scatterlist sense_sgl;
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
struct scsi_eh_save {
    int result;
    unsigned int resid_len;
    int eh_eflags;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    unsigned char[16] eh_cmnd;
    struct scatterlist sense_sgl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    unsigned int resid_len;
    int eh_eflags;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    unsigned char[16] eh_cmnd;
    struct scatterlist sense_sgl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    unsigned int resid_len;
    int eh_eflags;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    unsigned char[16] eh_cmnd;
    struct scatterlist sense_sgl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct scsi_eh_save {
    int result;
    unsigned int resid_len;
    int eh_eflags;
    enum dma_data_direction data_direction;
    unsigned int underflow;
    unsigned char cmd_len;
    unsigned char prot_op;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    unsigned char[16] eh_cmnd;
    struct scatterlist sense_sgl;
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
<b>Field added. </b>
<code>int eh_eflags</code>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct request * next_rq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int resid_len</code>
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
<b>Field removed. </b>
<code>unsigned char[16] eh_cmnd</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned char * cmnd</code> ➡️ <code>unsigned char[32] cmnd</code>
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
