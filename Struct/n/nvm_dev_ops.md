# Struct: <code>nvm_dev_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev_ops {
    nvm_id_fn * identity;
    nvm_get_l2p_tbl_fn * get_l2p_tbl;
    nvm_op_bb_tbl_fn * get_bb_tbl;
    nvm_op_set_bb_fn * set_bb_tbl;
    nvm_submit_io_fn * submit_io;
    nvm_erase_blk_fn * erase_block;
    nvm_create_dma_pool_fn * create_dma_pool;
    nvm_destroy_dma_pool_fn * destroy_dma_pool;
    nvm_dev_dma_alloc_fn * dev_dma_alloc;
    nvm_dev_dma_free_fn * dev_dma_free;
    unsigned int max_phys_sect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev_ops {
    nvm_id_fn * identity;
    nvm_get_l2p_tbl_fn * get_l2p_tbl;
    nvm_op_bb_tbl_fn * get_bb_tbl;
    nvm_op_set_bb_fn * set_bb_tbl;
    nvm_submit_io_fn * submit_io;
    nvm_erase_blk_fn * erase_block;
    nvm_create_dma_pool_fn * create_dma_pool;
    nvm_destroy_dma_pool_fn * destroy_dma_pool;
    nvm_dev_dma_alloc_fn * dev_dma_alloc;
    nvm_dev_dma_free_fn * dev_dma_free;
    unsigned int max_phys_sect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev_ops {
    nvm_id_fn * identity;
    nvm_get_l2p_tbl_fn * get_l2p_tbl;
    nvm_op_bb_tbl_fn * get_bb_tbl;
    nvm_op_set_bb_fn * set_bb_tbl;
    nvm_submit_io_fn * submit_io;
    nvm_erase_blk_fn * erase_block;
    nvm_create_dma_pool_fn * create_dma_pool;
    nvm_destroy_dma_pool_fn * destroy_dma_pool;
    nvm_dev_dma_alloc_fn * dev_dma_alloc;
    nvm_dev_dma_free_fn * dev_dma_free;
    unsigned int max_phys_sect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev_ops {
    nvm_id_fn * identity;
    nvm_get_l2p_tbl_fn * get_l2p_tbl;
    nvm_op_bb_tbl_fn * get_bb_tbl;
    nvm_op_set_bb_fn * set_bb_tbl;
    nvm_submit_io_fn * submit_io;
    nvm_create_dma_pool_fn * create_dma_pool;
    nvm_destroy_dma_pool_fn * destroy_dma_pool;
    nvm_dev_dma_alloc_fn * dev_dma_alloc;
    nvm_dev_dma_free_fn * dev_dma_free;
    unsigned int max_phys_sect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev_ops {
    nvm_id_fn * identity;
    nvm_get_l2p_tbl_fn * get_l2p_tbl;
    nvm_op_bb_tbl_fn * get_bb_tbl;
    nvm_op_set_bb_fn * set_bb_tbl;
    nvm_submit_io_fn * submit_io;
    nvm_submit_io_sync_fn * submit_io_sync;
    nvm_create_dma_pool_fn * create_dma_pool;
    nvm_destroy_dma_pool_fn * destroy_dma_pool;
    nvm_dev_dma_alloc_fn * dev_dma_alloc;
    nvm_dev_dma_free_fn * dev_dma_free;
    unsigned int max_phys_sect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev_ops {
    nvm_id_fn * identity;
    nvm_op_bb_tbl_fn * get_bb_tbl;
    nvm_op_set_bb_fn * set_bb_tbl;
    nvm_get_chk_meta_fn * get_chk_meta;
    nvm_submit_io_fn * submit_io;
    nvm_submit_io_sync_fn * submit_io_sync;
    nvm_create_dma_pool_fn * create_dma_pool;
    nvm_destroy_dma_pool_fn * destroy_dma_pool;
    nvm_dev_dma_alloc_fn * dev_dma_alloc;
    nvm_dev_dma_free_fn * dev_dma_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev_ops {
    nvm_id_fn * identity;
    nvm_op_bb_tbl_fn * get_bb_tbl;
    nvm_op_set_bb_fn * set_bb_tbl;
    nvm_get_chk_meta_fn * get_chk_meta;
    nvm_submit_io_fn * submit_io;
    nvm_submit_io_sync_fn * submit_io_sync;
    nvm_create_dma_pool_fn * create_dma_pool;
    nvm_destroy_dma_pool_fn * destroy_dma_pool;
    nvm_dev_dma_alloc_fn * dev_dma_alloc;
    nvm_dev_dma_free_fn * dev_dma_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev_ops {
    nvm_id_fn * identity;
    nvm_op_bb_tbl_fn * get_bb_tbl;
    nvm_op_set_bb_fn * set_bb_tbl;
    nvm_get_chk_meta_fn * get_chk_meta;
    nvm_submit_io_fn * submit_io;
    nvm_submit_io_sync_fn * submit_io_sync;
    nvm_create_dma_pool_fn * create_dma_pool;
    nvm_destroy_dma_pool_fn * destroy_dma_pool;
    nvm_dev_dma_alloc_fn * dev_dma_alloc;
    nvm_dev_dma_free_fn * dev_dma_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev_ops {
    nvm_id_fn * identity;
    nvm_op_bb_tbl_fn * get_bb_tbl;
    nvm_op_set_bb_fn * set_bb_tbl;
    nvm_get_chk_meta_fn * get_chk_meta;
    nvm_submit_io_fn * submit_io;
    nvm_create_dma_pool_fn * create_dma_pool;
    nvm_destroy_dma_pool_fn * destroy_dma_pool;
    nvm_dev_dma_alloc_fn * dev_dma_alloc;
    nvm_dev_dma_free_fn * dev_dma_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev_ops {
    nvm_id_fn * identity;
    nvm_op_bb_tbl_fn * get_bb_tbl;
    nvm_op_set_bb_fn * set_bb_tbl;
    nvm_get_chk_meta_fn * get_chk_meta;
    nvm_submit_io_fn * submit_io;
    nvm_create_dma_pool_fn * create_dma_pool;
    nvm_destroy_dma_pool_fn * destroy_dma_pool;
    nvm_dev_dma_alloc_fn * dev_dma_alloc;
    nvm_dev_dma_free_fn * dev_dma_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev_ops {
    nvm_id_fn * identity;
    nvm_op_bb_tbl_fn * get_bb_tbl;
    nvm_op_set_bb_fn * set_bb_tbl;
    nvm_get_chk_meta_fn * get_chk_meta;
    nvm_submit_io_fn * submit_io;
    nvm_create_dma_pool_fn * create_dma_pool;
    nvm_destroy_dma_pool_fn * destroy_dma_pool;
    nvm_dev_dma_alloc_fn * dev_dma_alloc;
    nvm_dev_dma_free_fn * dev_dma_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev_ops {
    nvm_id_fn * identity;
    nvm_op_bb_tbl_fn * get_bb_tbl;
    nvm_op_set_bb_fn * set_bb_tbl;
    nvm_get_chk_meta_fn * get_chk_meta;
    nvm_submit_io_fn * submit_io;
    nvm_create_dma_pool_fn * create_dma_pool;
    nvm_destroy_dma_pool_fn * destroy_dma_pool;
    nvm_dev_dma_alloc_fn * dev_dma_alloc;
    nvm_dev_dma_free_fn * dev_dma_free;
}
```
</details>
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
struct nvm_dev_ops {
    nvm_id_fn * identity;
    nvm_op_bb_tbl_fn * get_bb_tbl;
    nvm_op_set_bb_fn * set_bb_tbl;
    nvm_get_chk_meta_fn * get_chk_meta;
    nvm_submit_io_fn * submit_io;
    nvm_create_dma_pool_fn * create_dma_pool;
    nvm_destroy_dma_pool_fn * destroy_dma_pool;
    nvm_dev_dma_alloc_fn * dev_dma_alloc;
    nvm_dev_dma_free_fn * dev_dma_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct nvm_dev_ops {
    nvm_id_fn * identity;
    nvm_op_bb_tbl_fn * get_bb_tbl;
    nvm_op_set_bb_fn * set_bb_tbl;
    nvm_get_chk_meta_fn * get_chk_meta;
    nvm_submit_io_fn * submit_io;
    nvm_create_dma_pool_fn * create_dma_pool;
    nvm_destroy_dma_pool_fn * destroy_dma_pool;
    nvm_dev_dma_alloc_fn * dev_dma_alloc;
    nvm_dev_dma_free_fn * dev_dma_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nvm_dev_ops {
    nvm_id_fn * identity;
    nvm_op_bb_tbl_fn * get_bb_tbl;
    nvm_op_set_bb_fn * set_bb_tbl;
    nvm_get_chk_meta_fn * get_chk_meta;
    nvm_submit_io_fn * submit_io;
    nvm_create_dma_pool_fn * create_dma_pool;
    nvm_destroy_dma_pool_fn * destroy_dma_pool;
    nvm_dev_dma_alloc_fn * dev_dma_alloc;
    nvm_dev_dma_free_fn * dev_dma_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nvm_dev_ops {
    nvm_id_fn * identity;
    nvm_op_bb_tbl_fn * get_bb_tbl;
    nvm_op_set_bb_fn * set_bb_tbl;
    nvm_get_chk_meta_fn * get_chk_meta;
    nvm_submit_io_fn * submit_io;
    nvm_create_dma_pool_fn * create_dma_pool;
    nvm_destroy_dma_pool_fn * destroy_dma_pool;
    nvm_dev_dma_alloc_fn * dev_dma_alloc;
    nvm_dev_dma_free_fn * dev_dma_free;
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
struct nvm_dev_ops {
    nvm_id_fn * identity;
    nvm_op_bb_tbl_fn * get_bb_tbl;
    nvm_op_set_bb_fn * set_bb_tbl;
    nvm_get_chk_meta_fn * get_chk_meta;
    nvm_submit_io_fn * submit_io;
    nvm_create_dma_pool_fn * create_dma_pool;
    nvm_destroy_dma_pool_fn * destroy_dma_pool;
    nvm_dev_dma_alloc_fn * dev_dma_alloc;
    nvm_dev_dma_free_fn * dev_dma_free;
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
struct nvm_dev_ops {
    nvm_id_fn * identity;
    nvm_op_bb_tbl_fn * get_bb_tbl;
    nvm_op_set_bb_fn * set_bb_tbl;
    nvm_get_chk_meta_fn * get_chk_meta;
    nvm_submit_io_fn * submit_io;
    nvm_create_dma_pool_fn * create_dma_pool;
    nvm_destroy_dma_pool_fn * destroy_dma_pool;
    nvm_dev_dma_alloc_fn * dev_dma_alloc;
    nvm_dev_dma_free_fn * dev_dma_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nvm_dev_ops {
    nvm_id_fn * identity;
    nvm_op_bb_tbl_fn * get_bb_tbl;
    nvm_op_set_bb_fn * set_bb_tbl;
    nvm_get_chk_meta_fn * get_chk_meta;
    nvm_submit_io_fn * submit_io;
    nvm_create_dma_pool_fn * create_dma_pool;
    nvm_destroy_dma_pool_fn * destroy_dma_pool;
    nvm_dev_dma_alloc_fn * dev_dma_alloc;
    nvm_dev_dma_free_fn * dev_dma_free;
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
<b>Field removed. </b>
<code>nvm_erase_blk_fn * erase_block</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>nvm_submit_io_sync_fn * submit_io_sync</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>nvm_get_chk_meta_fn * get_chk_meta</code>
</li>
<li>
<b>Field removed. </b>
<code>nvm_get_l2p_tbl_fn * get_l2p_tbl</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int max_phys_sect</code>
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>nvm_submit_io_sync_fn * submit_io_sync</code>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
struct nvm_dev_ops {
    nvm_id_fn * identity;
    nvm_op_bb_tbl_fn * get_bb_tbl;
    nvm_op_set_bb_fn * set_bb_tbl;
    nvm_get_chk_meta_fn * get_chk_meta;
    nvm_submit_io_fn * submit_io;
    nvm_create_dma_pool_fn * create_dma_pool;
    nvm_destroy_dma_pool_fn * destroy_dma_pool;
    nvm_dev_dma_alloc_fn * dev_dma_alloc;
    nvm_dev_dma_free_fn * dev_dma_free;
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct nvm_dev_ops {
    nvm_id_fn * identity;
    nvm_op_bb_tbl_fn * get_bb_tbl;
    nvm_op_set_bb_fn * set_bb_tbl;
    nvm_get_chk_meta_fn * get_chk_meta;
    nvm_submit_io_fn * submit_io;
    nvm_create_dma_pool_fn * create_dma_pool;
    nvm_destroy_dma_pool_fn * destroy_dma_pool;
    nvm_dev_dma_alloc_fn * dev_dma_alloc;
    nvm_dev_dma_free_fn * dev_dma_free;
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
