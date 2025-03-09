# Struct: <code>drm_mode_config_funcs</code>

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
struct drm_mode_config_funcs {
    struct drm_framebuffer * (*)(struct drm_device *, struct drm_file *, const struct drm_mode_fb_cmd2 *) fb_create;
    const struct drm_format_info * (*)(const struct drm_mode_fb_cmd2 *) get_format_info;
    void (*)(struct drm_device *) output_poll_changed;
    enum drm_mode_status (*)(struct drm_device *, const struct drm_display_mode *) mode_valid;
    int (*)(struct drm_device *, struct drm_atomic_state *) atomic_check;
    int (*)(struct drm_device *, struct drm_atomic_state *, bool) atomic_commit;
    struct drm_atomic_state * (*)(struct drm_device *) atomic_state_alloc;
    void (*)(struct drm_atomic_state *) atomic_state_clear;
    void (*)(struct drm_atomic_state *) atomic_state_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct drm_mode_config_funcs {
    struct drm_framebuffer * (*)(struct drm_device *, struct drm_file *, const struct drm_mode_fb_cmd2 *) fb_create;
    const struct drm_format_info * (*)(const struct drm_mode_fb_cmd2 *) get_format_info;
    void (*)(struct drm_device *) output_poll_changed;
    enum drm_mode_status (*)(struct drm_device *, const struct drm_display_mode *) mode_valid;
    int (*)(struct drm_device *, struct drm_atomic_state *) atomic_check;
    int (*)(struct drm_device *, struct drm_atomic_state *, bool) atomic_commit;
    struct drm_atomic_state * (*)(struct drm_device *) atomic_state_alloc;
    void (*)(struct drm_atomic_state *) atomic_state_clear;
    void (*)(struct drm_atomic_state *) atomic_state_free;
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
struct drm_mode_config_funcs {
    struct drm_framebuffer * (*)(struct drm_device *, struct drm_file *, const struct drm_mode_fb_cmd2 *) fb_create;
    const struct drm_format_info * (*)(const struct drm_mode_fb_cmd2 *) get_format_info;
    void (*)(struct drm_device *) output_poll_changed;
    enum drm_mode_status (*)(struct drm_device *, const struct drm_display_mode *) mode_valid;
    int (*)(struct drm_device *, struct drm_atomic_state *) atomic_check;
    int (*)(struct drm_device *, struct drm_atomic_state *, bool) atomic_commit;
    struct drm_atomic_state * (*)(struct drm_device *) atomic_state_alloc;
    void (*)(struct drm_atomic_state *) atomic_state_clear;
    void (*)(struct drm_atomic_state *) atomic_state_free;
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
struct drm_mode_config_funcs {
    struct drm_framebuffer * (*)(struct drm_device *, struct drm_file *, const struct drm_mode_fb_cmd2 *) fb_create;
    const struct drm_format_info * (*)(const struct drm_mode_fb_cmd2 *) get_format_info;
    void (*)(struct drm_device *) output_poll_changed;
    enum drm_mode_status (*)(struct drm_device *, const struct drm_display_mode *) mode_valid;
    int (*)(struct drm_device *, struct drm_atomic_state *) atomic_check;
    int (*)(struct drm_device *, struct drm_atomic_state *, bool) atomic_commit;
    struct drm_atomic_state * (*)(struct drm_device *) atomic_state_alloc;
    void (*)(struct drm_atomic_state *) atomic_state_clear;
    void (*)(struct drm_atomic_state *) atomic_state_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct drm_mode_config_funcs {
    struct drm_framebuffer * (*)(struct drm_device *, struct drm_file *, const struct drm_mode_fb_cmd2 *) fb_create;
    const struct drm_format_info * (*)(const struct drm_mode_fb_cmd2 *) get_format_info;
    void (*)(struct drm_device *) output_poll_changed;
    enum drm_mode_status (*)(struct drm_device *, const struct drm_display_mode *) mode_valid;
    int (*)(struct drm_device *, struct drm_atomic_state *) atomic_check;
    int (*)(struct drm_device *, struct drm_atomic_state *, bool) atomic_commit;
    struct drm_atomic_state * (*)(struct drm_device *) atomic_state_alloc;
    void (*)(struct drm_atomic_state *) atomic_state_clear;
    void (*)(struct drm_atomic_state *) atomic_state_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct drm_mode_config_funcs {
    struct drm_framebuffer * (*)(struct drm_device *, struct drm_file *, const struct drm_mode_fb_cmd2 *) fb_create;
    const struct drm_format_info * (*)(const struct drm_mode_fb_cmd2 *) get_format_info;
    void (*)(struct drm_device *) output_poll_changed;
    enum drm_mode_status (*)(struct drm_device *, const struct drm_display_mode *) mode_valid;
    int (*)(struct drm_device *, struct drm_atomic_state *) atomic_check;
    int (*)(struct drm_device *, struct drm_atomic_state *, bool) atomic_commit;
    struct drm_atomic_state * (*)(struct drm_device *) atomic_state_alloc;
    void (*)(struct drm_atomic_state *) atomic_state_clear;
    void (*)(struct drm_atomic_state *) atomic_state_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct drm_mode_config_funcs {
    struct drm_framebuffer * (*)(struct drm_device *, struct drm_file *, const struct drm_mode_fb_cmd2 *) fb_create;
    const struct drm_format_info * (*)(const struct drm_mode_fb_cmd2 *) get_format_info;
    void (*)(struct drm_device *) output_poll_changed;
    enum drm_mode_status (*)(struct drm_device *, const struct drm_display_mode *) mode_valid;
    int (*)(struct drm_device *, struct drm_atomic_state *) atomic_check;
    int (*)(struct drm_device *, struct drm_atomic_state *, bool) atomic_commit;
    struct drm_atomic_state * (*)(struct drm_device *) atomic_state_alloc;
    void (*)(struct drm_atomic_state *) atomic_state_clear;
    void (*)(struct drm_atomic_state *) atomic_state_free;
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
struct drm_mode_config_funcs {
    struct drm_framebuffer * (*)(struct drm_device *, struct drm_file *, const struct drm_mode_fb_cmd2 *) fb_create;
    const struct drm_format_info * (*)(const struct drm_mode_fb_cmd2 *) get_format_info;
    void (*)(struct drm_device *) output_poll_changed;
    enum drm_mode_status (*)(struct drm_device *, const struct drm_display_mode *) mode_valid;
    int (*)(struct drm_device *, struct drm_atomic_state *) atomic_check;
    int (*)(struct drm_device *, struct drm_atomic_state *, bool) atomic_commit;
    struct drm_atomic_state * (*)(struct drm_device *) atomic_state_alloc;
    void (*)(struct drm_atomic_state *) atomic_state_clear;
    void (*)(struct drm_atomic_state *) atomic_state_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct drm_mode_config_funcs {
    struct drm_framebuffer * (*)(struct drm_device *, struct drm_file *, const struct drm_mode_fb_cmd2 *) fb_create;
    const struct drm_format_info * (*)(const struct drm_mode_fb_cmd2 *) get_format_info;
    void (*)(struct drm_device *) output_poll_changed;
    enum drm_mode_status (*)(struct drm_device *, const struct drm_display_mode *) mode_valid;
    int (*)(struct drm_device *, struct drm_atomic_state *) atomic_check;
    int (*)(struct drm_device *, struct drm_atomic_state *, bool) atomic_commit;
    struct drm_atomic_state * (*)(struct drm_device *) atomic_state_alloc;
    void (*)(struct drm_atomic_state *) atomic_state_clear;
    void (*)(struct drm_atomic_state *) atomic_state_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct drm_mode_config_funcs {
    struct drm_framebuffer * (*)(struct drm_device *, struct drm_file *, const struct drm_mode_fb_cmd2 *) fb_create;
    const struct drm_format_info * (*)(const struct drm_mode_fb_cmd2 *) get_format_info;
    void (*)(struct drm_device *) output_poll_changed;
    enum drm_mode_status (*)(struct drm_device *, const struct drm_display_mode *) mode_valid;
    int (*)(struct drm_device *, struct drm_atomic_state *) atomic_check;
    int (*)(struct drm_device *, struct drm_atomic_state *, bool) atomic_commit;
    struct drm_atomic_state * (*)(struct drm_device *) atomic_state_alloc;
    void (*)(struct drm_atomic_state *) atomic_state_clear;
    void (*)(struct drm_atomic_state *) atomic_state_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct drm_mode_config_funcs {
    struct drm_framebuffer * (*)(struct drm_device *, struct drm_file *, const struct drm_mode_fb_cmd2 *) fb_create;
    const struct drm_format_info * (*)(const struct drm_mode_fb_cmd2 *) get_format_info;
    void (*)(struct drm_device *) output_poll_changed;
    enum drm_mode_status (*)(struct drm_device *, const struct drm_display_mode *) mode_valid;
    int (*)(struct drm_device *, struct drm_atomic_state *) atomic_check;
    int (*)(struct drm_device *, struct drm_atomic_state *, bool) atomic_commit;
    struct drm_atomic_state * (*)(struct drm_device *) atomic_state_alloc;
    void (*)(struct drm_atomic_state *) atomic_state_clear;
    void (*)(struct drm_atomic_state *) atomic_state_free;
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
struct drm_mode_config_funcs {
    struct drm_framebuffer * (*)(struct drm_device *, struct drm_file *, const struct drm_mode_fb_cmd2 *) fb_create;
    const struct drm_format_info * (*)(const struct drm_mode_fb_cmd2 *) get_format_info;
    void (*)(struct drm_device *) output_poll_changed;
    enum drm_mode_status (*)(struct drm_device *, const struct drm_display_mode *) mode_valid;
    int (*)(struct drm_device *, struct drm_atomic_state *) atomic_check;
    int (*)(struct drm_device *, struct drm_atomic_state *, bool) atomic_commit;
    struct drm_atomic_state * (*)(struct drm_device *) atomic_state_alloc;
    void (*)(struct drm_atomic_state *) atomic_state_clear;
    void (*)(struct drm_atomic_state *) atomic_state_free;
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
struct drm_mode_config_funcs {
    struct drm_framebuffer * (*)(struct drm_device *, struct drm_file *, const struct drm_mode_fb_cmd2 *) fb_create;
    const struct drm_format_info * (*)(const struct drm_mode_fb_cmd2 *) get_format_info;
    void (*)(struct drm_device *) output_poll_changed;
    enum drm_mode_status (*)(struct drm_device *, const struct drm_display_mode *) mode_valid;
    int (*)(struct drm_device *, struct drm_atomic_state *) atomic_check;
    int (*)(struct drm_device *, struct drm_atomic_state *, bool) atomic_commit;
    struct drm_atomic_state * (*)(struct drm_device *) atomic_state_alloc;
    void (*)(struct drm_atomic_state *) atomic_state_clear;
    void (*)(struct drm_atomic_state *) atomic_state_free;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct drm_mode_config_funcs {
    struct drm_framebuffer * (*)(struct drm_device *, struct drm_file *, const struct drm_mode_fb_cmd2 *) fb_create;
    const struct drm_format_info * (*)(const struct drm_mode_fb_cmd2 *) get_format_info;
    void (*)(struct drm_device *) output_poll_changed;
    enum drm_mode_status (*)(struct drm_device *, const struct drm_display_mode *) mode_valid;
    int (*)(struct drm_device *, struct drm_atomic_state *) atomic_check;
    int (*)(struct drm_device *, struct drm_atomic_state *, bool) atomic_commit;
    struct drm_atomic_state * (*)(struct drm_device *) atomic_state_alloc;
    void (*)(struct drm_atomic_state *) atomic_state_clear;
    void (*)(struct drm_atomic_state *) atomic_state_free;
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
