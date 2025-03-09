# Struct: <code>lzma_dec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
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
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
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
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct lzma_dec {
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
    enum lzma_state state;
    uint32_t len;
    uint32_t lc;
    uint32_t literal_pos_mask;
    uint32_t pos_mask;
    uint16_t[192] is_match;
    uint16_t[12] is_rep;
    uint16_t[12] is_rep0;
    uint16_t[12] is_rep1;
    uint16_t[12] is_rep2;
    uint16_t[192] is_rep0_long;
    uint16_t[256] dist_slot;
    uint16_t[114] dist_special;
    uint16_t[16] dist_align;
    struct lzma_len_dec match_len_dec;
    struct lzma_len_dec rep_len_dec;
    uint16_t[12288] literal;
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
