# Struct: <code>address_space_operations</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct page *) readpage;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    int (*)(struct page *) set_page_dirty;
    int (*)(struct file *, struct address_space *, struct list_head *, unsigned int) readpages;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct page *, unsigned int, unsigned int) invalidatepage;
    int (*)(struct page *, gfp_t) releasepage;
    void (*)(struct page *) freepage;
    ssize_t (*)(struct kiocb *, struct iov_iter *, loff_t) direct_IO;
    int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage;
    int (*)(struct page *) launder_page;
    int (*)(struct page *, long unsigned int, long unsigned int) is_partially_uptodate;
    void (*)(struct page *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct page *) readpage;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    int (*)(struct page *) set_page_dirty;
    int (*)(struct file *, struct address_space *, struct list_head *, unsigned int) readpages;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct page *, unsigned int, unsigned int) invalidatepage;
    int (*)(struct page *, gfp_t) releasepage;
    void (*)(struct page *) freepage;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage;
    bool (*)(struct page *, isolate_mode_t) isolate_page;
    void (*)(struct page *) putback_page;
    int (*)(struct page *) launder_page;
    int (*)(struct page *, long unsigned int, long unsigned int) is_partially_uptodate;
    void (*)(struct page *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct page *) readpage;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    int (*)(struct page *) set_page_dirty;
    int (*)(struct file *, struct address_space *, struct list_head *, unsigned int) readpages;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct page *, unsigned int, unsigned int) invalidatepage;
    int (*)(struct page *, gfp_t) releasepage;
    void (*)(struct page *) freepage;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage;
    bool (*)(struct page *, isolate_mode_t) isolate_page;
    void (*)(struct page *) putback_page;
    int (*)(struct page *) launder_page;
    int (*)(struct page *, long unsigned int, long unsigned int) is_partially_uptodate;
    void (*)(struct page *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct page *) readpage;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    int (*)(struct page *) set_page_dirty;
    int (*)(struct file *, struct address_space *, struct list_head *, unsigned int) readpages;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct page *, unsigned int, unsigned int) invalidatepage;
    int (*)(struct page *, gfp_t) releasepage;
    void (*)(struct page *) freepage;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage;
    bool (*)(struct page *, isolate_mode_t) isolate_page;
    void (*)(struct page *) putback_page;
    int (*)(struct page *) launder_page;
    int (*)(struct page *, long unsigned int, long unsigned int) is_partially_uptodate;
    void (*)(struct page *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct page *) readpage;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    int (*)(struct page *) set_page_dirty;
    int (*)(struct file *, struct address_space *, struct list_head *, unsigned int) readpages;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct page *, unsigned int, unsigned int) invalidatepage;
    int (*)(struct page *, gfp_t) releasepage;
    void (*)(struct page *) freepage;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage;
    bool (*)(struct page *, isolate_mode_t) isolate_page;
    void (*)(struct page *) putback_page;
    int (*)(struct page *) launder_page;
    int (*)(struct page *, long unsigned int, long unsigned int) is_partially_uptodate;
    void (*)(struct page *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct page *) readpage;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    int (*)(struct page *) set_page_dirty;
    int (*)(struct file *, struct address_space *, struct list_head *, unsigned int) readpages;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct page *, unsigned int, unsigned int) invalidatepage;
    int (*)(struct page *, gfp_t) releasepage;
    void (*)(struct page *) freepage;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage;
    bool (*)(struct page *, isolate_mode_t) isolate_page;
    void (*)(struct page *) putback_page;
    int (*)(struct page *) launder_page;
    int (*)(struct page *, long unsigned int, long unsigned int) is_partially_uptodate;
    void (*)(struct page *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct page *) readpage;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    int (*)(struct page *) set_page_dirty;
    int (*)(struct file *, struct address_space *, struct list_head *, unsigned int) readpages;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct page *, unsigned int, unsigned int) invalidatepage;
    int (*)(struct page *, gfp_t) releasepage;
    void (*)(struct page *) freepage;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage;
    bool (*)(struct page *, isolate_mode_t) isolate_page;
    void (*)(struct page *) putback_page;
    int (*)(struct page *) launder_page;
    int (*)(struct page *, long unsigned int, long unsigned int) is_partially_uptodate;
    void (*)(struct page *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct page *) readpage;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    int (*)(struct page *) set_page_dirty;
    int (*)(struct file *, struct address_space *, struct list_head *, unsigned int) readpages;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct page *, unsigned int, unsigned int) invalidatepage;
    int (*)(struct page *, gfp_t) releasepage;
    void (*)(struct page *) freepage;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage;
    bool (*)(struct page *, isolate_mode_t) isolate_page;
    void (*)(struct page *) putback_page;
    int (*)(struct page *) launder_page;
    int (*)(struct page *, long unsigned int, long unsigned int) is_partially_uptodate;
    void (*)(struct page *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct page *) readpage;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    int (*)(struct page *) set_page_dirty;
    int (*)(struct file *, struct address_space *, struct list_head *, unsigned int) readpages;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct page *, unsigned int, unsigned int) invalidatepage;
    int (*)(struct page *, gfp_t) releasepage;
    void (*)(struct page *) freepage;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage;
    bool (*)(struct page *, isolate_mode_t) isolate_page;
    void (*)(struct page *) putback_page;
    int (*)(struct page *) launder_page;
    int (*)(struct page *, long unsigned int, long unsigned int) is_partially_uptodate;
    void (*)(struct page *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct page *) readpage;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    int (*)(struct page *) set_page_dirty;
    int (*)(struct file *, struct address_space *, struct list_head *, unsigned int) readpages;
    void (*)(struct readahead_control *) readahead;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct page *, unsigned int, unsigned int) invalidatepage;
    int (*)(struct page *, gfp_t) releasepage;
    void (*)(struct page *) freepage;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage;
    bool (*)(struct page *, isolate_mode_t) isolate_page;
    void (*)(struct page *) putback_page;
    int (*)(struct page *) launder_page;
    int (*)(struct page *, long unsigned int, long unsigned int) is_partially_uptodate;
    void (*)(struct page *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct page *) readpage;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    int (*)(struct page *) set_page_dirty;
    int (*)(struct file *, struct address_space *, struct list_head *, unsigned int) readpages;
    void (*)(struct readahead_control *) readahead;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct page *, unsigned int, unsigned int) invalidatepage;
    int (*)(struct page *, gfp_t) releasepage;
    void (*)(struct page *) freepage;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage;
    bool (*)(struct page *, isolate_mode_t) isolate_page;
    void (*)(struct page *) putback_page;
    int (*)(struct page *) launder_page;
    int (*)(struct page *, long unsigned int, long unsigned int) is_partially_uptodate;
    void (*)(struct page *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct page *) readpage;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    int (*)(struct page *) set_page_dirty;
    int (*)(struct file *, struct address_space *, struct list_head *, unsigned int) readpages;
    void (*)(struct readahead_control *) readahead;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct page *, unsigned int, unsigned int) invalidatepage;
    int (*)(struct page *, gfp_t) releasepage;
    void (*)(struct page *) freepage;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage;
    bool (*)(struct page *, isolate_mode_t) isolate_page;
    void (*)(struct page *) putback_page;
    int (*)(struct page *) launder_page;
    int (*)(struct page *, long unsigned int, long unsigned int) is_partially_uptodate;
    void (*)(struct page *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct page *) readpage;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    int (*)(struct page *) set_page_dirty;
    int (*)(struct file *, struct address_space *, struct list_head *, unsigned int) readpages;
    void (*)(struct readahead_control *) readahead;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct page *, unsigned int, unsigned int) invalidatepage;
    int (*)(struct page *, gfp_t) releasepage;
    void (*)(struct page *) freepage;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage;
    bool (*)(struct page *, isolate_mode_t) isolate_page;
    void (*)(struct page *) putback_page;
    int (*)(struct page *) launder_page;
    int (*)(struct page *, long unsigned int, long unsigned int) is_partially_uptodate;
    void (*)(struct page *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct folio *) read_folio;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    bool (*)(struct address_space *, struct folio *) dirty_folio;
    void (*)(struct readahead_control *) readahead;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct folio *, size_t, size_t) invalidate_folio;
    bool (*)(struct folio *, gfp_t) release_folio;
    void (*)(struct folio *) free_folio;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage;
    bool (*)(struct page *, isolate_mode_t) isolate_page;
    void (*)(struct page *) putback_page;
    int (*)(struct folio *) launder_folio;
    bool (*)(struct folio *, size_t, size_t) is_partially_uptodate;
    void (*)(struct folio *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
    int (*)(struct kiocb *, struct iov_iter *) swap_rw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct folio *) read_folio;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    bool (*)(struct address_space *, struct folio *) dirty_folio;
    void (*)(struct readahead_control *) readahead;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct folio *, size_t, size_t) invalidate_folio;
    bool (*)(struct folio *, gfp_t) release_folio;
    void (*)(struct folio *) free_folio;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct folio *, struct folio *, enum migrate_mode) migrate_folio;
    int (*)(struct folio *) launder_folio;
    bool (*)(struct folio *, size_t, size_t) is_partially_uptodate;
    void (*)(struct folio *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
    int (*)(struct kiocb *, struct iov_iter *) swap_rw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct folio *) read_folio;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    bool (*)(struct address_space *, struct folio *) dirty_folio;
    void (*)(struct readahead_control *) readahead;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct folio *, size_t, size_t) invalidate_folio;
    bool (*)(struct folio *, gfp_t) release_folio;
    void (*)(struct folio *) free_folio;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct folio *, struct folio *, enum migrate_mode) migrate_folio;
    int (*)(struct folio *) launder_folio;
    bool (*)(struct folio *, size_t, size_t) is_partially_uptodate;
    void (*)(struct folio *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
    int (*)(struct kiocb *, struct iov_iter *) swap_rw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct folio *) read_folio;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    bool (*)(struct address_space *, struct folio *) dirty_folio;
    void (*)(struct readahead_control *) readahead;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct folio *, size_t, size_t) invalidate_folio;
    bool (*)(struct folio *, gfp_t) release_folio;
    void (*)(struct folio *) free_folio;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct folio *, struct folio *, enum migrate_mode) migrate_folio;
    int (*)(struct folio *) launder_folio;
    bool (*)(struct folio *, size_t, size_t) is_partially_uptodate;
    void (*)(struct folio *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct folio *) error_remove_folio;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
    int (*)(struct kiocb *, struct iov_iter *) swap_rw;
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
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct page *) readpage;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    int (*)(struct page *) set_page_dirty;
    int (*)(struct file *, struct address_space *, struct list_head *, unsigned int) readpages;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct page *, unsigned int, unsigned int) invalidatepage;
    int (*)(struct page *, gfp_t) releasepage;
    void (*)(struct page *) freepage;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage;
    bool (*)(struct page *, isolate_mode_t) isolate_page;
    void (*)(struct page *) putback_page;
    int (*)(struct page *) launder_page;
    int (*)(struct page *, long unsigned int, long unsigned int) is_partially_uptodate;
    void (*)(struct page *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct page *) readpage;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    int (*)(struct page *) set_page_dirty;
    int (*)(struct file *, struct address_space *, struct list_head *, unsigned int) readpages;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct page *, unsigned int, unsigned int) invalidatepage;
    int (*)(struct page *, gfp_t) releasepage;
    void (*)(struct page *) freepage;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage;
    bool (*)(struct page *, isolate_mode_t) isolate_page;
    void (*)(struct page *) putback_page;
    int (*)(struct page *) launder_page;
    int (*)(struct page *, long unsigned int, long unsigned int) is_partially_uptodate;
    void (*)(struct page *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct page *) readpage;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    int (*)(struct page *) set_page_dirty;
    int (*)(struct file *, struct address_space *, struct list_head *, unsigned int) readpages;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct page *, unsigned int, unsigned int) invalidatepage;
    int (*)(struct page *, gfp_t) releasepage;
    void (*)(struct page *) freepage;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage;
    bool (*)(struct page *, isolate_mode_t) isolate_page;
    void (*)(struct page *) putback_page;
    int (*)(struct page *) launder_page;
    int (*)(struct page *, long unsigned int, long unsigned int) is_partially_uptodate;
    void (*)(struct page *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct page *) readpage;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    int (*)(struct page *) set_page_dirty;
    int (*)(struct file *, struct address_space *, struct list_head *, unsigned int) readpages;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct page *, unsigned int, unsigned int) invalidatepage;
    int (*)(struct page *, gfp_t) releasepage;
    void (*)(struct page *) freepage;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage;
    bool (*)(struct page *, isolate_mode_t) isolate_page;
    void (*)(struct page *) putback_page;
    int (*)(struct page *) launder_page;
    int (*)(struct page *, long unsigned int, long unsigned int) is_partially_uptodate;
    void (*)(struct page *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
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
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct page *) readpage;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    int (*)(struct page *) set_page_dirty;
    int (*)(struct file *, struct address_space *, struct list_head *, unsigned int) readpages;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct page *, unsigned int, unsigned int) invalidatepage;
    int (*)(struct page *, gfp_t) releasepage;
    void (*)(struct page *) freepage;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage;
    bool (*)(struct page *, isolate_mode_t) isolate_page;
    void (*)(struct page *) putback_page;
    int (*)(struct page *) launder_page;
    int (*)(struct page *, long unsigned int, long unsigned int) is_partially_uptodate;
    void (*)(struct page *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct page *) readpage;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    int (*)(struct page *) set_page_dirty;
    int (*)(struct file *, struct address_space *, struct list_head *, unsigned int) readpages;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct page *, unsigned int, unsigned int) invalidatepage;
    int (*)(struct page *, gfp_t) releasepage;
    void (*)(struct page *) freepage;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage;
    bool (*)(struct page *, isolate_mode_t) isolate_page;
    void (*)(struct page *) putback_page;
    int (*)(struct page *) launder_page;
    int (*)(struct page *, long unsigned int, long unsigned int) is_partially_uptodate;
    void (*)(struct page *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct page *) readpage;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    int (*)(struct page *) set_page_dirty;
    int (*)(struct file *, struct address_space *, struct list_head *, unsigned int) readpages;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct page *, unsigned int, unsigned int) invalidatepage;
    int (*)(struct page *, gfp_t) releasepage;
    void (*)(struct page *) freepage;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage;
    bool (*)(struct page *, isolate_mode_t) isolate_page;
    void (*)(struct page *) putback_page;
    int (*)(struct page *) launder_page;
    int (*)(struct page *, long unsigned int, long unsigned int) is_partially_uptodate;
    void (*)(struct page *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct address_space_operations {
    int (*)(struct page *, struct writeback_control *) writepage;
    int (*)(struct file *, struct page *) readpage;
    int (*)(struct address_space *, struct writeback_control *) writepages;
    int (*)(struct page *) set_page_dirty;
    int (*)(struct file *, struct address_space *, struct list_head *, unsigned int) readpages;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page * *, void * *) write_begin;
    int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page *, void *) write_end;
    sector_t (*)(struct address_space *, sector_t) bmap;
    void (*)(struct page *, unsigned int, unsigned int) invalidatepage;
    int (*)(struct page *, gfp_t) releasepage;
    void (*)(struct page *) freepage;
    ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO;
    int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage;
    bool (*)(struct page *, isolate_mode_t) isolate_page;
    void (*)(struct page *) putback_page;
    int (*)(struct page *) launder_page;
    int (*)(struct page *, long unsigned int, long unsigned int) is_partially_uptodate;
    void (*)(struct page *, bool *, bool *) is_dirty_writeback;
    int (*)(struct address_space *, struct page *) error_remove_page;
    int (*)(struct swap_info_struct *, struct file *, sector_t *) swap_activate;
    void (*)(struct file *) swap_deactivate;
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
<code>bool (*)(struct page *, isolate_mode_t) isolate_page</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct page *) putback_page</code>
</li>
<li>
<b>Field type changed. </b>
<code>ssize_t (*)(struct kiocb *, struct iov_iter *, loff_t) direct_IO</code> ➡️ <code>ssize_t (*)(struct kiocb *, struct iov_iter *) direct_IO</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct readahead_control *) readahead</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct file *, struct folio *) read_folio</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(struct address_space *, struct folio *) dirty_folio</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct folio *, size_t, size_t) invalidate_folio</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(struct folio *, gfp_t) release_folio</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct folio *) free_folio</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct folio *) launder_folio</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct kiocb *, struct iov_iter *) swap_rw</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct file *, struct page *) readpage</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct page *) set_page_dirty</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct file *, struct address_space *, struct list_head *, unsigned int) readpages</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct page *, unsigned int, unsigned int) invalidatepage</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct page *, gfp_t) releasepage</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct page *) freepage</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct page *) launder_page</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct file *, struct address_space *, loff_t, unsigned int, unsigned int, struct page * *, void * *) write_begin</code> ➡️ <code>int (*)(struct file *, struct address_space *, loff_t, unsigned int, struct page * *, void * *) write_begin</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct page *, long unsigned int, long unsigned int) is_partially_uptodate</code> ➡️ <code>bool (*)(struct folio *, size_t, size_t) is_partially_uptodate</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct page *, bool *, bool *) is_dirty_writeback</code> ➡️ <code>void (*)(struct folio *, bool *, bool *) is_dirty_writeback</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct address_space *, struct folio *, struct folio *, enum migrate_mode) migrate_folio</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct address_space *, struct page *, struct page *, enum migrate_mode) migratepage</code>
</li>
<li>
<b>Field removed. </b>
<code>bool (*)(struct page *, isolate_mode_t) isolate_page</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct page *) putback_page</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct address_space *, struct folio *) error_remove_folio</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct address_space *, struct page *) error_remove_page</code>
</li>
</ul>
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
