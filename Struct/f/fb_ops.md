# Struct: <code>fb_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    void (*)(struct fb_info *, int) fb_rotate;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
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
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
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
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fb_ops {
    struct module * owner;
    int (*)(struct fb_info *, int) fb_open;
    int (*)(struct fb_info *, int) fb_release;
    ssize_t (*)(struct fb_info *, char *, size_t, loff_t *) fb_read;
    ssize_t (*)(struct fb_info *, const char *, size_t, loff_t *) fb_write;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_check_var;
    int (*)(struct fb_info *) fb_set_par;
    int (*)(unsigned int, unsigned int, unsigned int, unsigned int, unsigned int, struct fb_info *) fb_setcolreg;
    int (*)(struct fb_cmap *, struct fb_info *) fb_setcmap;
    int (*)(int, struct fb_info *) fb_blank;
    int (*)(struct fb_var_screeninfo *, struct fb_info *) fb_pan_display;
    void (*)(struct fb_info *, const struct fb_fillrect *) fb_fillrect;
    void (*)(struct fb_info *, const struct fb_copyarea *) fb_copyarea;
    void (*)(struct fb_info *, const struct fb_image *) fb_imageblit;
    int (*)(struct fb_info *, struct fb_cursor *) fb_cursor;
    int (*)(struct fb_info *) fb_sync;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_ioctl;
    int (*)(struct fb_info *, unsigned int, long unsigned int) fb_compat_ioctl;
    int (*)(struct fb_info *, struct vm_area_struct *) fb_mmap;
    void (*)(struct fb_info *, struct fb_blit_caps *, struct fb_var_screeninfo *) fb_get_caps;
    void (*)(struct fb_info *) fb_destroy;
    int (*)(struct fb_info *) fb_debug_enter;
    int (*)(struct fb_info *) fb_debug_leave;
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
<b>Field removed. </b>
<code>void (*)(struct fb_info *, int) fb_rotate</code>
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
