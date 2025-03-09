# Struct: <code>rctx</code>

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
struct rctx {
    be128[8] buf;
    be128 t;
    be128 * ext;
    struct scatterlist[2] srcbuf;
    struct scatterlist[2] dstbuf;
    struct scatterlist * src;
    struct scatterlist * dst;
    unsigned int left;
    struct skcipher_request subreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rctx {
    le128[8] buf;
    le128 t;
    le128 * ext;
    struct scatterlist[2] srcbuf;
    struct scatterlist[2] dstbuf;
    struct scatterlist * src;
    struct scatterlist * dst;
    unsigned int left;
    struct skcipher_request subreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rctx {
    le128[8] buf;
    le128 t;
    le128 * ext;
    struct scatterlist[2] srcbuf;
    struct scatterlist[2] dstbuf;
    struct scatterlist * src;
    struct scatterlist * dst;
    unsigned int left;
    struct skcipher_request subreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rctx {
    le128[8] buf;
    le128 t;
    le128 * ext;
    struct scatterlist[2] srcbuf;
    struct scatterlist[2] dstbuf;
    struct scatterlist * src;
    struct scatterlist * dst;
    unsigned int left;
    struct skcipher_request subreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rctx {
    le128 t;
    struct skcipher_request subreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rctx {
    le128 t;
    struct skcipher_request subreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rctx {
    le128 t;
    struct scatterlist * tail;
    struct scatterlist[2] sg;
    struct skcipher_request subreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rctx {
    le128 t;
    struct scatterlist * tail;
    struct scatterlist[2] sg;
    struct skcipher_request subreq;
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct rctx {
    le128 t;
    struct scatterlist * tail;
    struct scatterlist[2] sg;
    struct skcipher_request subreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rctx {
    le128 t;
    struct scatterlist * tail;
    struct scatterlist[2] sg;
    struct skcipher_request subreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rctx {
    le128 t;
    struct scatterlist * tail;
    struct scatterlist[2] sg;
    struct skcipher_request subreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rctx {
    le128 t;
    struct scatterlist * tail;
    struct scatterlist[2] sg;
    struct skcipher_request subreq;
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
struct rctx {
    le128 t;
    struct scatterlist * tail;
    struct scatterlist[2] sg;
    struct skcipher_request subreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rctx {
    le128 t;
    struct scatterlist * tail;
    struct scatterlist[2] sg;
    struct skcipher_request subreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rctx {
    le128 t;
    struct scatterlist * tail;
    struct scatterlist[2] sg;
    struct skcipher_request subreq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rctx {
    le128 t;
    struct scatterlist * tail;
    struct scatterlist[2] sg;
    struct skcipher_request subreq;
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
struct rctx {
    be128[8] buf;
    be128 t;
    be128 * ext;
    struct scatterlist[2] srcbuf;
    struct scatterlist[2] dstbuf;
    struct scatterlist * src;
    struct scatterlist * dst;
    unsigned int left;
    struct skcipher_request subreq;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>be128[8] buf</code> ➡️ <code>le128[8] buf</code>
</li>
<li>
<b>Field type changed. </b>
<code>be128 t</code> ➡️ <code>le128 t</code>
</li>
<li>
<b>Field type changed. </b>
<code>be128 * ext</code> ➡️ <code>le128 * ext</code>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>le128[8] buf</code>
</li>
<li>
<b>Field removed. </b>
<code>le128 * ext</code>
</li>
<li>
<b>Field removed. </b>
<code>struct scatterlist[2] srcbuf</code>
</li>
<li>
<b>Field removed. </b>
<code>struct scatterlist[2] dstbuf</code>
</li>
<li>
<b>Field removed. </b>
<code>struct scatterlist * src</code>
</li>
<li>
<b>Field removed. </b>
<code>struct scatterlist * dst</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int left</code>
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
<b>Field added. </b>
<code>struct scatterlist * tail</code>
</li>
<li>
<b>Field added. </b>
<code>struct scatterlist[2] sg</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
struct rctx {
    le128 t;
    struct scatterlist * tail;
    struct scatterlist[2] sg;
    struct skcipher_request subreq;
}
```
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
