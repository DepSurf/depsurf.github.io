# Struct: <code>crypto_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    struct crypto_alg * (*)(const char *, u32, u32) lookup;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    struct crypto_alg * (*)(const char *, u32, u32) lookup;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    struct crypto_alg * (*)(const char *, u32, u32) lookup;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    struct crypto_alg * (*)(const char *, u32, u32) lookup;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    struct crypto_alg * (*)(const char *, u32, u32) lookup;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    void (*)(struct crypto_instance *) free;
    int (*)(struct sk_buff *, struct crypto_alg *) report_stat;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    void (*)(struct crypto_instance *) free;
    int (*)(struct sk_buff *, struct crypto_alg *) report_stat;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
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
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
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
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct crypto_type {
    unsigned int (*)(struct crypto_alg *, u32, u32) ctxsize;
    unsigned int (*)(struct crypto_alg *) extsize;
    int (*)(struct crypto_tfm *, u32, u32) init;
    int (*)(struct crypto_tfm *) init_tfm;
    void (*)(struct seq_file *, struct crypto_alg *) show;
    int (*)(struct sk_buff *, struct crypto_alg *) report;
    void (*)(struct crypto_instance *) free;
    unsigned int type;
    unsigned int maskclear;
    unsigned int maskset;
    unsigned int tfmsize;
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
<b>Field removed. </b>
<code>struct crypto_alg * (*)(const char *, u32, u32) lookup</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct sk_buff *, struct crypto_alg *) report_stat</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct crypto_tfm *, u32, u32) init</code>
</li>
</ul>
</details>
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
