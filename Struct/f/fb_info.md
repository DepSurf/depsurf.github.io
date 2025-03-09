# Struct: <code>fb_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct fb_info {
    atomic_t count;
    int node;
    int flags;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct work_struct queue;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    struct fb_deferred_io * fbdefio;
    struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct fb_info {
    atomic_t count;
    int node;
    int flags;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct work_struct queue;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    struct fb_deferred_io * fbdefio;
    struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct fb_info {
    atomic_t count;
    int node;
    int flags;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct work_struct queue;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    struct fb_deferred_io * fbdefio;
    struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct fb_info {
    atomic_t count;
    int node;
    int flags;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct work_struct queue;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    struct fb_deferred_io * fbdefio;
    struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct fb_info {
    atomic_t count;
    int node;
    int flags;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct work_struct queue;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    struct fb_deferred_io * fbdefio;
    struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct fb_info {
    atomic_t count;
    int node;
    int flags;
    int fbcon_rotate_hint;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct work_struct queue;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    struct fb_deferred_io * fbdefio;
    struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct fb_info {
    atomic_t count;
    int node;
    int flags;
    int fbcon_rotate_hint;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct work_struct queue;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    struct fb_deferred_io * fbdefio;
    struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct fb_info {
    atomic_t count;
    int node;
    int flags;
    int fbcon_rotate_hint;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct work_struct queue;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    struct fb_deferred_io * fbdefio;
    struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fb_info {
    atomic_t count;
    int node;
    int flags;
    int fbcon_rotate_hint;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct work_struct queue;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    struct fb_deferred_io * fbdefio;
    struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fb_info {
    atomic_t count;
    int node;
    int flags;
    int fbcon_rotate_hint;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct work_struct queue;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    struct fb_deferred_io * fbdefio;
    const struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fb_info {
    atomic_t count;
    int node;
    int flags;
    int fbcon_rotate_hint;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct work_struct queue;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    struct fb_deferred_io * fbdefio;
    const struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fb_info {
    atomic_t count;
    int node;
    int flags;
    int fbcon_rotate_hint;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct work_struct queue;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    struct fb_deferred_io * fbdefio;
    const struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fb_info {
    refcount_t count;
    int node;
    int flags;
    int fbcon_rotate_hint;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct work_struct queue;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    struct fb_deferred_io * fbdefio;
    const struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fb_info {
    refcount_t count;
    int node;
    int flags;
    int fbcon_rotate_hint;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    long unsigned int npagerefs;
    struct fb_deferred_io_pageref * pagerefs;
    struct fb_deferred_io * fbdefio;
    const struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
    bool forced_out;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fb_info {
    refcount_t count;
    int node;
    int flags;
    int fbcon_rotate_hint;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    long unsigned int npagerefs;
    struct fb_deferred_io_pageref * pagerefs;
    struct fb_deferred_io * fbdefio;
    const struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fb_info {
    refcount_t count;
    int node;
    int flags;
    int fbcon_rotate_hint;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    long unsigned int npagerefs;
    struct fb_deferred_io_pageref * pagerefs;
    struct fb_deferred_io * fbdefio;
    const struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    bool skip_vt_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fb_info {
    refcount_t count;
    int node;
    int flags;
    int fbcon_rotate_hint;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    long unsigned int npagerefs;
    struct fb_deferred_io_pageref * pagerefs;
    struct fb_deferred_io * fbdefio;
    const struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    bool skip_vt_switch;
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
struct fb_info {
    atomic_t count;
    int node;
    int flags;
    int fbcon_rotate_hint;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct work_struct queue;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    struct fb_deferred_io * fbdefio;
    struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fb_info {
    atomic_t count;
    int node;
    int flags;
    int fbcon_rotate_hint;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct work_struct queue;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    struct fb_deferred_io * fbdefio;
    struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fb_info {
    atomic_t count;
    int node;
    int flags;
    int fbcon_rotate_hint;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct work_struct queue;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    struct fb_deferred_io * fbdefio;
    struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fb_info {
    atomic_t count;
    int node;
    int flags;
    int fbcon_rotate_hint;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct work_struct queue;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    struct fb_deferred_io * fbdefio;
    struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
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
struct fb_info {
    atomic_t count;
    int node;
    int flags;
    int fbcon_rotate_hint;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct work_struct queue;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    struct fb_deferred_io * fbdefio;
    struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fb_info {
    atomic_t count;
    int node;
    int flags;
    int fbcon_rotate_hint;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct work_struct queue;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct delayed_work deferred_work;
    struct fb_deferred_io * fbdefio;
    struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fb_info {
    atomic_t count;
    int node;
    int flags;
    int fbcon_rotate_hint;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct work_struct queue;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    struct fb_deferred_io * fbdefio;
    struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fb_info {
    atomic_t count;
    int node;
    int flags;
    int fbcon_rotate_hint;
    struct mutex lock;
    struct mutex mm_lock;
    struct fb_var_screeninfo var;
    struct fb_fix_screeninfo fix;
    struct fb_monspecs monspecs;
    struct work_struct queue;
    struct fb_pixmap pixmap;
    struct fb_pixmap sprite;
    struct fb_cmap cmap;
    struct list_head modelist;
    struct fb_videomode * mode;
    struct backlight_device * bl_dev;
    struct mutex bl_curve_mutex;
    u8[128] bl_curve;
    struct delayed_work deferred_work;
    struct fb_deferred_io * fbdefio;
    struct fb_ops * fbops;
    struct device * device;
    struct device * dev;
    int class_flag;
    struct fb_tile_ops * tileops;
    char * screen_base;
    char * screen_buffer;
    long unsigned int screen_size;
    void * pseudo_palette;
    u32 state;
    void * fbcon_par;
    void * par;
    struct apertures_struct * apertures;
    bool skip_vt_switch;
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int fbcon_rotate_hint</code>
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
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct fb_ops * fbops</code> ➡️ <code>const struct fb_ops * fbops</code>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>atomic_t count</code> ➡️ <code>refcount_t count</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int npagerefs</code>
</li>
<li>
<b>Field added. </b>
<code>struct fb_deferred_io_pageref * pagerefs</code>
</li>
<li>
<b>Field added. </b>
<code>bool forced_out</code>
</li>
<li>
<b>Field removed. </b>
<code>struct work_struct queue</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool forced_out</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct apertures_struct * apertures</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct backlight_device * bl_dev</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex bl_curve_mutex</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[128] bl_curve</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
