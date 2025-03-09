# Struct: <code>msdos_sb_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
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
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
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
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct msdos_sb_info {
    short unsigned int sec_per_clus;
    short unsigned int cluster_bits;
    unsigned int cluster_size;
    unsigned char fats;
    unsigned char fat_bits;
    short unsigned int fat_start;
    long unsigned int fat_length;
    long unsigned int dir_start;
    short unsigned int dir_entries;
    long unsigned int data_start;
    long unsigned int max_cluster;
    long unsigned int root_cluster;
    long unsigned int fsinfo_sector;
    struct mutex fat_lock;
    struct mutex nfs_build_inode_lock;
    struct mutex s_lock;
    unsigned int prev_free;
    unsigned int free_clusters;
    unsigned int free_clus_valid;
    struct fat_mount_options options;
    struct nls_table * nls_disk;
    struct nls_table * nls_io;
    const void * dir_ops;
    int dir_per_block;
    int dir_per_block_bits;
    unsigned int vol_id;
    int fatent_shift;
    const struct fatent_operations * fatent_ops;
    struct inode * fat_inode;
    struct inode * fsinfo_inode;
    struct ratelimit_state ratelimit;
    spinlock_t inode_hash_lock;
    struct hlist_head[256] inode_hashtable;
    spinlock_t dir_hash_lock;
    struct hlist_head[256] dir_hashtable;
    unsigned int dirty;
    struct callback_head rcu;
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
<b>Field type changed. </b>
<code>struct fatent_operations * fatent_ops</code> ➡️ <code>const struct fatent_operations * fatent_ops</code>
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
