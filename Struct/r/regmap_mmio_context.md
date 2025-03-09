# Struct: <code>regmap_mmio_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int reg_bytes;
    unsigned int val_bytes;
    unsigned int pad_bytes;
    struct clk * clk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    bool attached_clk;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    bool attached_clk;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    bool attached_clk;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    bool attached_clk;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    bool attached_clk;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    bool relaxed_mmio;
    bool attached_clk;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    bool relaxed_mmio;
    bool attached_clk;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    bool relaxed_mmio;
    bool attached_clk;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    bool relaxed_mmio;
    bool attached_clk;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    bool big_endian;
    bool attached_clk;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    bool big_endian;
    bool attached_clk;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    bool big_endian;
    bool attached_clk;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
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
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    bool attached_clk;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    bool attached_clk;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    bool attached_clk;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    bool attached_clk;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
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
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    bool attached_clk;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    bool attached_clk;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    bool attached_clk;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct regmap_mmio_context {
    void * regs;
    unsigned int val_bytes;
    bool attached_clk;
    struct clk * clk;
    void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write;
    unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read;
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
<code>void (*)(struct regmap_mmio_context *, unsigned int, unsigned int) reg_write</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int (*)(struct regmap_mmio_context *, unsigned int) reg_read</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int reg_bytes</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int pad_bytes</code>
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool attached_clk</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool relaxed_mmio</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool big_endian</code>
</li>
<li>
<b>Field removed. </b>
<code>bool relaxed_mmio</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct clk * clk</code> ➡️ <code>struct clk * clk</code>
</li>
</ul>
</details>
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
