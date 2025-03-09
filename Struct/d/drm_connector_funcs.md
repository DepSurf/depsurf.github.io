# Struct: <code>drm_connector_funcs</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct drm_connector_funcs {
    int (*)(struct drm_connector *, int) dpms;
    void (*)(struct drm_connector *) reset;
    enum drm_connector_status (*)(struct drm_connector *, bool) detect;
    void (*)(struct drm_connector *) force;
    int (*)(struct drm_connector *, uint32_t, uint32_t) fill_modes;
    int (*)(struct drm_connector *, struct drm_property *, uint64_t) set_property;
    int (*)(struct drm_connector *) late_register;
    void (*)(struct drm_connector *) early_unregister;
    void (*)(struct drm_connector *) destroy;
    struct drm_connector_state * (*)(struct drm_connector *) atomic_duplicate_state;
    void (*)(struct drm_connector *, struct drm_connector_state *) atomic_destroy_state;
    int (*)(struct drm_connector *, struct drm_connector_state *, struct drm_property *, uint64_t) atomic_set_property;
    int (*)(struct drm_connector *, const struct drm_connector_state *, struct drm_property *, uint64_t *) atomic_get_property;
    void (*)(struct drm_printer *, const struct drm_connector_state *) atomic_print_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct drm_connector_funcs {
    int (*)(struct drm_connector *, int) dpms;
    void (*)(struct drm_connector *) reset;
    enum drm_connector_status (*)(struct drm_connector *, bool) detect;
    void (*)(struct drm_connector *) force;
    int (*)(struct drm_connector *, uint32_t, uint32_t) fill_modes;
    int (*)(struct drm_connector *, struct drm_property *, uint64_t) set_property;
    int (*)(struct drm_connector *) late_register;
    void (*)(struct drm_connector *) early_unregister;
    void (*)(struct drm_connector *) destroy;
    struct drm_connector_state * (*)(struct drm_connector *) atomic_duplicate_state;
    void (*)(struct drm_connector *, struct drm_connector_state *) atomic_destroy_state;
    int (*)(struct drm_connector *, struct drm_connector_state *, struct drm_property *, uint64_t) atomic_set_property;
    int (*)(struct drm_connector *, const struct drm_connector_state *, struct drm_property *, uint64_t *) atomic_get_property;
    void (*)(struct drm_printer *, const struct drm_connector_state *) atomic_print_state;
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct drm_connector_funcs {
    int (*)(struct drm_connector *, int) dpms;
    void (*)(struct drm_connector *) reset;
    enum drm_connector_status (*)(struct drm_connector *, bool) detect;
    void (*)(struct drm_connector *) force;
    int (*)(struct drm_connector *, uint32_t, uint32_t) fill_modes;
    int (*)(struct drm_connector *, struct drm_property *, uint64_t) set_property;
    int (*)(struct drm_connector *) late_register;
    void (*)(struct drm_connector *) early_unregister;
    void (*)(struct drm_connector *) destroy;
    struct drm_connector_state * (*)(struct drm_connector *) atomic_duplicate_state;
    void (*)(struct drm_connector *, struct drm_connector_state *) atomic_destroy_state;
    int (*)(struct drm_connector *, struct drm_connector_state *, struct drm_property *, uint64_t) atomic_set_property;
    int (*)(struct drm_connector *, const struct drm_connector_state *, struct drm_property *, uint64_t *) atomic_get_property;
    void (*)(struct drm_printer *, const struct drm_connector_state *) atomic_print_state;
    void (*)(struct drm_connector *, enum drm_connector_status) oob_hotplug_event;
    void (*)(struct drm_connector *, struct dentry *) debugfs_init;
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
struct drm_connector_funcs {
    int (*)(struct drm_connector *, int) dpms;
    void (*)(struct drm_connector *) reset;
    enum drm_connector_status (*)(struct drm_connector *, bool) detect;
    void (*)(struct drm_connector *) force;
    int (*)(struct drm_connector *, uint32_t, uint32_t) fill_modes;
    int (*)(struct drm_connector *, struct drm_property *, uint64_t) set_property;
    int (*)(struct drm_connector *) late_register;
    void (*)(struct drm_connector *) early_unregister;
    void (*)(struct drm_connector *) destroy;
    struct drm_connector_state * (*)(struct drm_connector *) atomic_duplicate_state;
    void (*)(struct drm_connector *, struct drm_connector_state *) atomic_destroy_state;
    int (*)(struct drm_connector *, struct drm_connector_state *, struct drm_property *, uint64_t) atomic_set_property;
    int (*)(struct drm_connector *, const struct drm_connector_state *, struct drm_property *, uint64_t *) atomic_get_property;
    void (*)(struct drm_printer *, const struct drm_connector_state *) atomic_print_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct drm_connector_funcs {
    int (*)(struct drm_connector *, int) dpms;
    void (*)(struct drm_connector *) reset;
    enum drm_connector_status (*)(struct drm_connector *, bool) detect;
    void (*)(struct drm_connector *) force;
    int (*)(struct drm_connector *, uint32_t, uint32_t) fill_modes;
    int (*)(struct drm_connector *, struct drm_property *, uint64_t) set_property;
    int (*)(struct drm_connector *) late_register;
    void (*)(struct drm_connector *) early_unregister;
    void (*)(struct drm_connector *) destroy;
    struct drm_connector_state * (*)(struct drm_connector *) atomic_duplicate_state;
    void (*)(struct drm_connector *, struct drm_connector_state *) atomic_destroy_state;
    int (*)(struct drm_connector *, struct drm_connector_state *, struct drm_property *, uint64_t) atomic_set_property;
    int (*)(struct drm_connector *, const struct drm_connector_state *, struct drm_property *, uint64_t *) atomic_get_property;
    void (*)(struct drm_printer *, const struct drm_connector_state *) atomic_print_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct drm_connector_funcs {
    int (*)(struct drm_connector *, int) dpms;
    void (*)(struct drm_connector *) reset;
    enum drm_connector_status (*)(struct drm_connector *, bool) detect;
    void (*)(struct drm_connector *) force;
    int (*)(struct drm_connector *, uint32_t, uint32_t) fill_modes;
    int (*)(struct drm_connector *, struct drm_property *, uint64_t) set_property;
    int (*)(struct drm_connector *) late_register;
    void (*)(struct drm_connector *) early_unregister;
    void (*)(struct drm_connector *) destroy;
    struct drm_connector_state * (*)(struct drm_connector *) atomic_duplicate_state;
    void (*)(struct drm_connector *, struct drm_connector_state *) atomic_destroy_state;
    int (*)(struct drm_connector *, struct drm_connector_state *, struct drm_property *, uint64_t) atomic_set_property;
    int (*)(struct drm_connector *, const struct drm_connector_state *, struct drm_property *, uint64_t *) atomic_get_property;
    void (*)(struct drm_printer *, const struct drm_connector_state *) atomic_print_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct drm_connector_funcs {
    int (*)(struct drm_connector *, int) dpms;
    void (*)(struct drm_connector *) reset;
    enum drm_connector_status (*)(struct drm_connector *, bool) detect;
    void (*)(struct drm_connector *) force;
    int (*)(struct drm_connector *, uint32_t, uint32_t) fill_modes;
    int (*)(struct drm_connector *, struct drm_property *, uint64_t) set_property;
    int (*)(struct drm_connector *) late_register;
    void (*)(struct drm_connector *) early_unregister;
    void (*)(struct drm_connector *) destroy;
    struct drm_connector_state * (*)(struct drm_connector *) atomic_duplicate_state;
    void (*)(struct drm_connector *, struct drm_connector_state *) atomic_destroy_state;
    int (*)(struct drm_connector *, struct drm_connector_state *, struct drm_property *, uint64_t) atomic_set_property;
    int (*)(struct drm_connector *, const struct drm_connector_state *, struct drm_property *, uint64_t *) atomic_get_property;
    void (*)(struct drm_printer *, const struct drm_connector_state *) atomic_print_state;
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
struct drm_connector_funcs {
    int (*)(struct drm_connector *, int) dpms;
    void (*)(struct drm_connector *) reset;
    enum drm_connector_status (*)(struct drm_connector *, bool) detect;
    void (*)(struct drm_connector *) force;
    int (*)(struct drm_connector *, uint32_t, uint32_t) fill_modes;
    int (*)(struct drm_connector *, struct drm_property *, uint64_t) set_property;
    int (*)(struct drm_connector *) late_register;
    void (*)(struct drm_connector *) early_unregister;
    void (*)(struct drm_connector *) destroy;
    struct drm_connector_state * (*)(struct drm_connector *) atomic_duplicate_state;
    void (*)(struct drm_connector *, struct drm_connector_state *) atomic_destroy_state;
    int (*)(struct drm_connector *, struct drm_connector_state *, struct drm_property *, uint64_t) atomic_set_property;
    int (*)(struct drm_connector *, const struct drm_connector_state *, struct drm_property *, uint64_t *) atomic_get_property;
    void (*)(struct drm_printer *, const struct drm_connector_state *) atomic_print_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct drm_connector_funcs {
    int (*)(struct drm_connector *, int) dpms;
    void (*)(struct drm_connector *) reset;
    enum drm_connector_status (*)(struct drm_connector *, bool) detect;
    void (*)(struct drm_connector *) force;
    int (*)(struct drm_connector *, uint32_t, uint32_t) fill_modes;
    int (*)(struct drm_connector *, struct drm_property *, uint64_t) set_property;
    int (*)(struct drm_connector *) late_register;
    void (*)(struct drm_connector *) early_unregister;
    void (*)(struct drm_connector *) destroy;
    struct drm_connector_state * (*)(struct drm_connector *) atomic_duplicate_state;
    void (*)(struct drm_connector *, struct drm_connector_state *) atomic_destroy_state;
    int (*)(struct drm_connector *, struct drm_connector_state *, struct drm_property *, uint64_t) atomic_set_property;
    int (*)(struct drm_connector *, const struct drm_connector_state *, struct drm_property *, uint64_t *) atomic_get_property;
    void (*)(struct drm_printer *, const struct drm_connector_state *) atomic_print_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct drm_connector_funcs {
    int (*)(struct drm_connector *, int) dpms;
    void (*)(struct drm_connector *) reset;
    enum drm_connector_status (*)(struct drm_connector *, bool) detect;
    void (*)(struct drm_connector *) force;
    int (*)(struct drm_connector *, uint32_t, uint32_t) fill_modes;
    int (*)(struct drm_connector *, struct drm_property *, uint64_t) set_property;
    int (*)(struct drm_connector *) late_register;
    void (*)(struct drm_connector *) early_unregister;
    void (*)(struct drm_connector *) destroy;
    struct drm_connector_state * (*)(struct drm_connector *) atomic_duplicate_state;
    void (*)(struct drm_connector *, struct drm_connector_state *) atomic_destroy_state;
    int (*)(struct drm_connector *, struct drm_connector_state *, struct drm_property *, uint64_t) atomic_set_property;
    int (*)(struct drm_connector *, const struct drm_connector_state *, struct drm_property *, uint64_t *) atomic_get_property;
    void (*)(struct drm_printer *, const struct drm_connector_state *) atomic_print_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct drm_connector_funcs {
    int (*)(struct drm_connector *, int) dpms;
    void (*)(struct drm_connector *) reset;
    enum drm_connector_status (*)(struct drm_connector *, bool) detect;
    void (*)(struct drm_connector *) force;
    int (*)(struct drm_connector *, uint32_t, uint32_t) fill_modes;
    int (*)(struct drm_connector *, struct drm_property *, uint64_t) set_property;
    int (*)(struct drm_connector *) late_register;
    void (*)(struct drm_connector *) early_unregister;
    void (*)(struct drm_connector *) destroy;
    struct drm_connector_state * (*)(struct drm_connector *) atomic_duplicate_state;
    void (*)(struct drm_connector *, struct drm_connector_state *) atomic_destroy_state;
    int (*)(struct drm_connector *, struct drm_connector_state *, struct drm_property *, uint64_t) atomic_set_property;
    int (*)(struct drm_connector *, const struct drm_connector_state *, struct drm_property *, uint64_t *) atomic_get_property;
    void (*)(struct drm_printer *, const struct drm_connector_state *) atomic_print_state;
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct drm_connector_funcs {
    int (*)(struct drm_connector *, int) dpms;
    void (*)(struct drm_connector *) reset;
    enum drm_connector_status (*)(struct drm_connector *, bool) detect;
    void (*)(struct drm_connector *) force;
    int (*)(struct drm_connector *, uint32_t, uint32_t) fill_modes;
    int (*)(struct drm_connector *, struct drm_property *, uint64_t) set_property;
    int (*)(struct drm_connector *) late_register;
    void (*)(struct drm_connector *) early_unregister;
    void (*)(struct drm_connector *) destroy;
    struct drm_connector_state * (*)(struct drm_connector *) atomic_duplicate_state;
    void (*)(struct drm_connector *, struct drm_connector_state *) atomic_destroy_state;
    int (*)(struct drm_connector *, struct drm_connector_state *, struct drm_property *, uint64_t) atomic_set_property;
    int (*)(struct drm_connector *, const struct drm_connector_state *, struct drm_property *, uint64_t *) atomic_get_property;
    void (*)(struct drm_printer *, const struct drm_connector_state *) atomic_print_state;
}
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct drm_connector_funcs {
    int (*)(struct drm_connector *, int) dpms;
    void (*)(struct drm_connector *) reset;
    enum drm_connector_status (*)(struct drm_connector *, bool) detect;
    void (*)(struct drm_connector *) force;
    int (*)(struct drm_connector *, uint32_t, uint32_t) fill_modes;
    int (*)(struct drm_connector *, struct drm_property *, uint64_t) set_property;
    int (*)(struct drm_connector *) late_register;
    void (*)(struct drm_connector *) early_unregister;
    void (*)(struct drm_connector *) destroy;
    struct drm_connector_state * (*)(struct drm_connector *) atomic_duplicate_state;
    void (*)(struct drm_connector *, struct drm_connector_state *) atomic_destroy_state;
    int (*)(struct drm_connector *, struct drm_connector_state *, struct drm_property *, uint64_t) atomic_set_property;
    int (*)(struct drm_connector *, const struct drm_connector_state *, struct drm_property *, uint64_t *) atomic_get_property;
    void (*)(struct drm_printer *, const struct drm_connector_state *) atomic_print_state;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct drm_connector_funcs {
    int (*)(struct drm_connector *, int) dpms;
    void (*)(struct drm_connector *) reset;
    enum drm_connector_status (*)(struct drm_connector *, bool) detect;
    void (*)(struct drm_connector *) force;
    int (*)(struct drm_connector *, uint32_t, uint32_t) fill_modes;
    int (*)(struct drm_connector *, struct drm_property *, uint64_t) set_property;
    int (*)(struct drm_connector *) late_register;
    void (*)(struct drm_connector *) early_unregister;
    void (*)(struct drm_connector *) destroy;
    struct drm_connector_state * (*)(struct drm_connector *) atomic_duplicate_state;
    void (*)(struct drm_connector *, struct drm_connector_state *) atomic_destroy_state;
    int (*)(struct drm_connector *, struct drm_connector_state *, struct drm_property *, uint64_t) atomic_set_property;
    int (*)(struct drm_connector *, const struct drm_connector_state *, struct drm_property *, uint64_t *) atomic_get_property;
    void (*)(struct drm_printer *, const struct drm_connector_state *) atomic_print_state;
    void (*)(struct drm_connector *, enum drm_connector_status) oob_hotplug_event;
    void (*)(struct drm_connector *, struct dentry *) debugfs_init;
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
