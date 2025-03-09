# Struct: <code>merkle_tree_params</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct merkle_tree_params {
    const struct fsverity_hash_alg * hash_alg;
    const u8 * hashstate;
    unsigned int digest_size;
    unsigned int block_size;
    unsigned int hashes_per_block;
    unsigned int log_blocksize;
    unsigned int log_arity;
    unsigned int num_levels;
    u64 tree_size;
    u64[8] level_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct merkle_tree_params {
    struct fsverity_hash_alg * hash_alg;
    const u8 * hashstate;
    unsigned int digest_size;
    unsigned int block_size;
    unsigned int hashes_per_block;
    unsigned int log_blocksize;
    unsigned int log_arity;
    unsigned int num_levels;
    u64 tree_size;
    long unsigned int level0_blocks;
    u64[8] level_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct merkle_tree_params {
    struct fsverity_hash_alg * hash_alg;
    const u8 * hashstate;
    unsigned int digest_size;
    unsigned int block_size;
    unsigned int hashes_per_block;
    unsigned int log_blocksize;
    unsigned int log_arity;
    unsigned int num_levels;
    u64 tree_size;
    long unsigned int level0_blocks;
    u64[8] level_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct merkle_tree_params {
    struct fsverity_hash_alg * hash_alg;
    const u8 * hashstate;
    unsigned int digest_size;
    unsigned int block_size;
    unsigned int hashes_per_block;
    unsigned int log_blocksize;
    unsigned int log_arity;
    unsigned int num_levels;
    u64 tree_size;
    long unsigned int level0_blocks;
    u64[8] level_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct merkle_tree_params {
    struct fsverity_hash_alg * hash_alg;
    const u8 * hashstate;
    unsigned int digest_size;
    unsigned int block_size;
    unsigned int hashes_per_block;
    unsigned int log_blocksize;
    unsigned int log_arity;
    unsigned int num_levels;
    u64 tree_size;
    long unsigned int level0_blocks;
    u64[8] level_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct merkle_tree_params {
    struct fsverity_hash_alg * hash_alg;
    const u8 * hashstate;
    unsigned int digest_size;
    unsigned int block_size;
    unsigned int hashes_per_block;
    unsigned int log_blocksize;
    unsigned int log_arity;
    unsigned int num_levels;
    u64 tree_size;
    long unsigned int level0_blocks;
    u64[8] level_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct merkle_tree_params {
    struct fsverity_hash_alg * hash_alg;
    const u8 * hashstate;
    unsigned int digest_size;
    unsigned int block_size;
    unsigned int hashes_per_block;
    unsigned int log_blocksize;
    unsigned int log_arity;
    unsigned int num_levels;
    u64 tree_size;
    long unsigned int level0_blocks;
    u64[8] level_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct merkle_tree_params {
    const struct fsverity_hash_alg * hash_alg;
    const u8 * hashstate;
    unsigned int digest_size;
    unsigned int block_size;
    unsigned int hashes_per_block;
    unsigned int blocks_per_page;
    u8 log_digestsize;
    u8 log_blocksize;
    u8 log_arity;
    u8 log_blocks_per_page;
    unsigned int num_levels;
    u64 tree_size;
    long unsigned int tree_pages;
    long unsigned int[8] level_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct merkle_tree_params {
    const struct fsverity_hash_alg * hash_alg;
    const u8 * hashstate;
    unsigned int digest_size;
    unsigned int block_size;
    unsigned int hashes_per_block;
    unsigned int blocks_per_page;
    u8 log_digestsize;
    u8 log_blocksize;
    u8 log_arity;
    u8 log_blocks_per_page;
    unsigned int num_levels;
    u64 tree_size;
    long unsigned int tree_pages;
    long unsigned int[8] level_start;
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
struct merkle_tree_params {
    const struct fsverity_hash_alg * hash_alg;
    const u8 * hashstate;
    unsigned int digest_size;
    unsigned int block_size;
    unsigned int hashes_per_block;
    unsigned int log_blocksize;
    unsigned int log_arity;
    unsigned int num_levels;
    u64 tree_size;
    u64[8] level_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct merkle_tree_params {
    const struct fsverity_hash_alg * hash_alg;
    const u8 * hashstate;
    unsigned int digest_size;
    unsigned int block_size;
    unsigned int hashes_per_block;
    unsigned int log_blocksize;
    unsigned int log_arity;
    unsigned int num_levels;
    u64 tree_size;
    u64[8] level_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct merkle_tree_params {
    const struct fsverity_hash_alg * hash_alg;
    const u8 * hashstate;
    unsigned int digest_size;
    unsigned int block_size;
    unsigned int hashes_per_block;
    unsigned int log_blocksize;
    unsigned int log_arity;
    unsigned int num_levels;
    u64 tree_size;
    u64[8] level_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct merkle_tree_params {
    const struct fsverity_hash_alg * hash_alg;
    const u8 * hashstate;
    unsigned int digest_size;
    unsigned int block_size;
    unsigned int hashes_per_block;
    unsigned int log_blocksize;
    unsigned int log_arity;
    unsigned int num_levels;
    u64 tree_size;
    u64[8] level_start;
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
struct merkle_tree_params {
    const struct fsverity_hash_alg * hash_alg;
    const u8 * hashstate;
    unsigned int digest_size;
    unsigned int block_size;
    unsigned int hashes_per_block;
    unsigned int log_blocksize;
    unsigned int log_arity;
    unsigned int num_levels;
    u64 tree_size;
    u64[8] level_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct merkle_tree_params {
    const struct fsverity_hash_alg * hash_alg;
    const u8 * hashstate;
    unsigned int digest_size;
    unsigned int block_size;
    unsigned int hashes_per_block;
    unsigned int log_blocksize;
    unsigned int log_arity;
    unsigned int num_levels;
    u64 tree_size;
    u64[8] level_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct merkle_tree_params {
    const struct fsverity_hash_alg * hash_alg;
    const u8 * hashstate;
    unsigned int digest_size;
    unsigned int block_size;
    unsigned int hashes_per_block;
    unsigned int log_blocksize;
    unsigned int log_arity;
    unsigned int num_levels;
    u64 tree_size;
    u64[8] level_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct merkle_tree_params {
    const struct fsverity_hash_alg * hash_alg;
    const u8 * hashstate;
    unsigned int digest_size;
    unsigned int block_size;
    unsigned int hashes_per_block;
    unsigned int log_blocksize;
    unsigned int log_arity;
    unsigned int num_levels;
    u64 tree_size;
    u64[8] level_start;
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct merkle_tree_params {
    const struct fsverity_hash_alg * hash_alg;
    const u8 * hashstate;
    unsigned int digest_size;
    unsigned int block_size;
    unsigned int hashes_per_block;
    unsigned int log_blocksize;
    unsigned int log_arity;
    unsigned int num_levels;
    u64 tree_size;
    u64[8] level_start;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int level0_blocks</code>
</li>
<li>
<b>Field type changed. </b>
<code>const struct fsverity_hash_alg * hash_alg</code> ➡️ <code>struct fsverity_hash_alg * hash_alg</code>
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
<code>unsigned int blocks_per_page</code>
</li>
<li>
<b>Field added. </b>
<code>u8 log_digestsize</code>
</li>
<li>
<b>Field added. </b>
<code>u8 log_blocks_per_page</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int tree_pages</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int level0_blocks</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct fsverity_hash_alg * hash_alg</code> ➡️ <code>const struct fsverity_hash_alg * hash_alg</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int log_blocksize</code> ➡️ <code>u8 log_blocksize</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int log_arity</code> ➡️ <code>u8 log_arity</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64[8] level_start</code> ➡️ <code>long unsigned int[8] level_start</code>
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
