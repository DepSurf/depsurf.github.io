# Struct: <code>md_cluster_operations</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    int (*)(struct md_rdev *) gather_bitmaps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
    void (*)(struct mddev *, sector_t) update_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
    void (*)(struct mddev *, sector_t) update_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
    void (*)(struct mddev *, sector_t) update_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    void (*)(struct mddev *, sector_t *, sector_t *) resync_info_get;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *, sector_t, sector_t) resize_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
    void (*)(struct mddev *, sector_t) update_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    void (*)(struct mddev *, sector_t *, sector_t *) resync_info_get;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *, sector_t, sector_t) resize_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
    void (*)(struct mddev *, sector_t) update_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    void (*)(struct mddev *, sector_t *, sector_t *) resync_info_get;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *, sector_t, sector_t) resize_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
    void (*)(struct mddev *, sector_t) update_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    void (*)(struct mddev *, sector_t *, sector_t *) resync_info_get;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *, sector_t, sector_t) resize_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
    void (*)(struct mddev *, sector_t) update_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    void (*)(struct mddev *, sector_t *, sector_t *) resync_info_get;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *, sector_t, sector_t) resize_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
    void (*)(struct mddev *, sector_t) update_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    void (*)(struct mddev *, sector_t *, sector_t *) resync_info_get;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *, sector_t, sector_t) resize_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
    void (*)(struct mddev *, sector_t) update_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    void (*)(struct mddev *, sector_t *, sector_t *) resync_info_get;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *, sector_t, sector_t) resize_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
    void (*)(struct mddev *, sector_t) update_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    void (*)(struct mddev *, sector_t *, sector_t *) resync_info_get;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *, sector_t, sector_t) resize_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
    void (*)(struct mddev *, sector_t) update_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    void (*)(struct mddev *, sector_t *, sector_t *) resync_info_get;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *, sector_t, sector_t) resize_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
    void (*)(struct mddev *, sector_t) update_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    void (*)(struct mddev *, sector_t *, sector_t *) resync_info_get;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *, sector_t, sector_t) resize_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
    void (*)(struct mddev *, sector_t) update_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    void (*)(struct mddev *, sector_t *, sector_t *) resync_info_get;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *, sector_t, sector_t) resize_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
    void (*)(struct mddev *, sector_t) update_size;
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
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    void (*)(struct mddev *, sector_t *, sector_t *) resync_info_get;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *, sector_t, sector_t) resize_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
    void (*)(struct mddev *, sector_t) update_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    void (*)(struct mddev *, sector_t *, sector_t *) resync_info_get;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *, sector_t, sector_t) resize_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
    void (*)(struct mddev *, sector_t) update_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    void (*)(struct mddev *, sector_t *, sector_t *) resync_info_get;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *, sector_t, sector_t) resize_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
    void (*)(struct mddev *, sector_t) update_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    void (*)(struct mddev *, sector_t *, sector_t *) resync_info_get;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *, sector_t, sector_t) resize_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
    void (*)(struct mddev *, sector_t) update_size;
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
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    void (*)(struct mddev *, sector_t *, sector_t *) resync_info_get;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *, sector_t, sector_t) resize_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
    void (*)(struct mddev *, sector_t) update_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    void (*)(struct mddev *, sector_t *, sector_t *) resync_info_get;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *, sector_t, sector_t) resize_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
    void (*)(struct mddev *, sector_t) update_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    void (*)(struct mddev *, sector_t *, sector_t *) resync_info_get;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *, sector_t, sector_t) resize_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
    void (*)(struct mddev *, sector_t) update_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct md_cluster_operations {
    int (*)(struct mddev *, int) join;
    int (*)(struct mddev *) leave;
    int (*)(struct mddev *) slot_number;
    int (*)(struct mddev *, sector_t, sector_t) resync_info_update;
    void (*)(struct mddev *, sector_t *, sector_t *) resync_info_get;
    int (*)(struct mddev *) metadata_update_start;
    int (*)(struct mddev *) metadata_update_finish;
    void (*)(struct mddev *) metadata_update_cancel;
    int (*)(struct mddev *) resync_start;
    int (*)(struct mddev *) resync_finish;
    int (*)(struct mddev *, int, sector_t, sector_t) area_resyncing;
    int (*)(struct mddev *, struct md_rdev *) add_new_disk;
    void (*)(struct mddev *) add_new_disk_cancel;
    int (*)(struct mddev *, bool) new_disk_ack;
    int (*)(struct mddev *, struct md_rdev *) remove_disk;
    void (*)(struct mddev *, int) load_bitmaps;
    int (*)(struct md_rdev *) gather_bitmaps;
    int (*)(struct mddev *, sector_t, sector_t) resize_bitmaps;
    int (*)(struct mddev *) lock_all_bitmaps;
    void (*)(struct mddev *) unlock_all_bitmaps;
    void (*)(struct mddev *, sector_t) update_size;
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
<code>void (*)(struct mddev *, int) load_bitmaps</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct mddev *) lock_all_bitmaps</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct mddev *) unlock_all_bitmaps</code>
</li>
</ul>
</details>
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
<code>void (*)(struct mddev *, sector_t) update_size</code>
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
<b>Field added. </b>
<code>void (*)(struct mddev *, sector_t *, sector_t *) resync_info_get</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct mddev *, sector_t, sector_t) resize_bitmaps</code>
</li>
</ul>
</details>
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
