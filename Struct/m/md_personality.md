# Struct: <code>md_personality</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    void (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, int) congested;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    void (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, int) congested;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    void (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, int) congested;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    bool (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, int) congested;
    int (*)(struct mddev *, const char *) change_consistency_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    bool (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, int) congested;
    int (*)(struct mddev *, const char *) change_consistency_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    bool (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    int (*)(struct mddev *) start;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, int) congested;
    int (*)(struct mddev *, const char *) change_consistency_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    bool (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    int (*)(struct mddev *) start;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *) update_reshape_pos;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, int) congested;
    int (*)(struct mddev *, const char *) change_consistency_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    bool (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    int (*)(struct mddev *) start;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *) update_reshape_pos;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, int) congested;
    int (*)(struct mddev *, const char *) change_consistency_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    bool (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    int (*)(struct mddev *) start;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *) update_reshape_pos;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, int) congested;
    int (*)(struct mddev *, const char *) change_consistency_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    bool (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    int (*)(struct mddev *) start;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *) update_reshape_pos;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, int) congested;
    int (*)(struct mddev *, const char *) change_consistency_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    bool (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    int (*)(struct mddev *) start;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *) update_reshape_pos;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, const char *) change_consistency_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    bool (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    int (*)(struct mddev *) start;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *) update_reshape_pos;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, const char *) change_consistency_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    bool (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    int (*)(struct mddev *) start;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *) update_reshape_pos;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, const char *) change_consistency_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    bool (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    int (*)(struct mddev *) start;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *) update_reshape_pos;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, const char *) change_consistency_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    bool (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    int (*)(struct mddev *) start;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *) update_reshape_pos;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, const char *) change_consistency_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    bool (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    int (*)(struct mddev *) start;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *) update_reshape_pos;
    void (*)(struct mddev *) prepare_suspend;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, const char *) change_consistency_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    bool (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    int (*)(struct mddev *) start;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *) update_reshape_pos;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, const char *) change_consistency_policy;
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
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    bool (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    int (*)(struct mddev *) start;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *) update_reshape_pos;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, int) congested;
    int (*)(struct mddev *, const char *) change_consistency_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    bool (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    int (*)(struct mddev *) start;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *) update_reshape_pos;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, int) congested;
    int (*)(struct mddev *, const char *) change_consistency_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    bool (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    int (*)(struct mddev *) start;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *) update_reshape_pos;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, int) congested;
    int (*)(struct mddev *, const char *) change_consistency_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    bool (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    int (*)(struct mddev *) start;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *) update_reshape_pos;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, int) congested;
    int (*)(struct mddev *, const char *) change_consistency_policy;
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
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    bool (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    int (*)(struct mddev *) start;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *) update_reshape_pos;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, int) congested;
    int (*)(struct mddev *, const char *) change_consistency_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    bool (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    int (*)(struct mddev *) start;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *) update_reshape_pos;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, int) congested;
    int (*)(struct mddev *, const char *) change_consistency_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    bool (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    int (*)(struct mddev *) start;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *) update_reshape_pos;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, int) congested;
    int (*)(struct mddev *, const char *) change_consistency_policy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct md_personality {
    char * name;
    int level;
    struct list_head list;
    struct module * owner;
    bool (*)(struct mddev *, struct bio *) make_request;
    int (*)(struct mddev *) run;
    int (*)(struct mddev *) start;
    void (*)(struct mddev *, void *) free;
    void (*)(struct seq_file *, struct mddev *) status;
    void (*)(struct mddev *, struct md_rdev *) error_handler;
    int (*)(struct mddev *, struct md_rdev *) hot_add_disk;
    int (*)(struct mddev *, struct md_rdev *) hot_remove_disk;
    int (*)(struct mddev *) spare_active;
    sector_t (*)(struct mddev *, sector_t, int *) sync_request;
    int (*)(struct mddev *, sector_t) resize;
    sector_t (*)(struct mddev *, sector_t, int) size;
    int (*)(struct mddev *) check_reshape;
    int (*)(struct mddev *) start_reshape;
    void (*)(struct mddev *) finish_reshape;
    void (*)(struct mddev *) update_reshape_pos;
    void (*)(struct mddev *, int) quiesce;
    void * (*)(struct mddev *) takeover;
    int (*)(struct mddev *, int) congested;
    int (*)(struct mddev *, const char *) change_consistency_policy;
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
<b>Field added. </b>
<code>int (*)(struct mddev *, const char *) change_consistency_policy</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct mddev *, struct bio *) make_request</code> ➡️ <code>bool (*)(struct mddev *, struct bio *) make_request</code>
</li>
</ul>
</details>
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
<code>int (*)(struct mddev *) start</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct mddev *) update_reshape_pos</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct mddev *, int) congested</code>
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
<code>void (*)(struct mddev *) prepare_suspend</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>void (*)(struct mddev *) prepare_suspend</code>
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
