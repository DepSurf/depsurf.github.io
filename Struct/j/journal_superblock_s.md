# Struct: <code>journal_superblock_s</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __u32[42] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __u32[42] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __u32[42] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __u32[42] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __u32[42] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __u32[42] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __u32[42] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __u32[42] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __u32[42] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __u32[42] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __be32 s_num_fc_blks;
    __u32[41] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __be32 s_num_fc_blks;
    __u32[41] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __be32 s_num_fc_blks;
    __u32[41] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __be32 s_num_fc_blks;
    __u32[41] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __be32 s_num_fc_blks;
    __u32[41] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __be32 s_num_fc_blks;
    __be32 s_head;
    __u32[40] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __be32 s_num_fc_blks;
    __be32 s_head;
    __u32[40] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
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
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __u32[42] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __u32[42] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __u32[42] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __u32[42] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
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
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __u32[42] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __u32[42] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __u32[42] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct journal_superblock_s {
    journal_header_t s_header;
    __be32 s_blocksize;
    __be32 s_maxlen;
    __be32 s_first;
    __be32 s_sequence;
    __be32 s_start;
    __be32 s_errno;
    __be32 s_feature_compat;
    __be32 s_feature_incompat;
    __be32 s_feature_ro_compat;
    __u8[16] s_uuid;
    __be32 s_nr_users;
    __be32 s_dynsuper;
    __be32 s_max_transaction;
    __be32 s_max_trans_data;
    __u8 s_checksum_type;
    __u8[3] s_padding2;
    __u32[42] s_padding;
    __be32 s_checksum;
    __u8[768] s_users;
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__be32 s_num_fc_blks</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32[42] s_padding</code> ➡️ <code>__u32[41] s_padding</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__be32 s_head</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32[41] s_padding</code> ➡️ <code>__u32[40] s_padding</code>
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
