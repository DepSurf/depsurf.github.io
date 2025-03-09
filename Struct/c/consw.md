# Struct: <code>consw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    int (*)(struct vc_data *, int, int, int, int) con_scroll;
    void (*)(struct vc_data *, int, int, int, int, int, int) con_bmove;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, int) con_font_copy;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    int (*)(struct vc_data *, unsigned char *) con_set_palette;
    int (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, u8, u8, u8, u8, u8) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    int (*)(struct vc_data *, int, int, int, int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, int) con_font_copy;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, u8, u8, u8, u8, u8) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, int) con_font_copy;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, u8, u8, u8, u8, u8) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, int) con_font_copy;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, u8, u8, u8, u8, u8) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    void (*)(struct vc_data *) con_flush_scrollback;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, int) con_font_copy;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, u8, u8, u8, u8, u8) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    void (*)(struct vc_data *) con_flush_scrollback;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, int) con_font_copy;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, u8, u8, u8, u8, u8) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    void (*)(struct vc_data *) con_flush_scrollback;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, int) con_font_copy;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, u8, u8, u8, u8, u8) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    void (*)(struct vc_data *) con_flush_scrollback;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, int) con_font_copy;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, u8, u8, u8, u8, u8) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    void (*)(struct vc_data *) con_flush_scrollback;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, int) con_font_copy;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, u8, u8, u8, u8, u8) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    void (*)(struct vc_data *) con_flush_scrollback;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, int) con_font_copy;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, u8, u8, u8, u8, u8) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    void (*)(struct vc_data *) con_flush_scrollback;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, enum vc_intensity, bool, bool, bool, bool) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(const struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    void (*)(struct vc_data *) con_flush_scrollback;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, enum vc_intensity, bool, bool, bool, bool) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(const struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    void (*)(struct vc_data *) con_flush_scrollback;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, enum vc_intensity, bool, bool, bool, bool) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(const struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    void (*)(struct vc_data *) con_flush_scrollback;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, enum vc_intensity, bool, bool, bool, bool) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(const struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    void (*)(struct vc_data *) con_flush_scrollback;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, enum vc_intensity, bool, bool, bool, bool) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(const struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    void (*)(struct vc_data *) con_flush_scrollback;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, enum vc_intensity, bool, bool, bool, bool) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(const struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    void (*)(struct vc_data *) con_flush_scrollback;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, enum vc_intensity, bool, bool, bool, bool) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(const struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    void (*)(struct vc_data *) con_flush_scrollback;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
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
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, int) con_font_copy;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, u8, u8, u8, u8, u8) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    void (*)(struct vc_data *) con_flush_scrollback;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, int) con_font_copy;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, u8, u8, u8, u8, u8) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    void (*)(struct vc_data *) con_flush_scrollback;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, int) con_font_copy;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, u8, u8, u8, u8, u8) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    void (*)(struct vc_data *) con_flush_scrollback;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, int) con_font_copy;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, u8, u8, u8, u8, u8) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    void (*)(struct vc_data *) con_flush_scrollback;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
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
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, int) con_font_copy;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, u8, u8, u8, u8, u8) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    void (*)(struct vc_data *) con_flush_scrollback;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, int) con_font_copy;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, u8, u8, u8, u8, u8) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    void (*)(struct vc_data *) con_flush_scrollback;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, int) con_font_copy;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, u8, u8, u8, u8, u8) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    void (*)(struct vc_data *) con_flush_scrollback;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct consw {
    struct module * owner;
    const char * (*)() con_startup;
    void (*)(struct vc_data *, int) con_init;
    void (*)(struct vc_data *) con_deinit;
    void (*)(struct vc_data *, int, int, int, int) con_clear;
    void (*)(struct vc_data *, int, int, int) con_putc;
    void (*)(struct vc_data *, const short unsigned int *, int, int, int) con_putcs;
    void (*)(struct vc_data *, int) con_cursor;
    bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll;
    int (*)(struct vc_data *) con_switch;
    int (*)(struct vc_data *, int, int) con_blank;
    int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set;
    int (*)(struct vc_data *, struct console_font *) con_font_get;
    int (*)(struct vc_data *, struct console_font *, char *) con_font_default;
    int (*)(struct vc_data *, int) con_font_copy;
    int (*)(struct vc_data *, unsigned int, unsigned int, unsigned int) con_resize;
    void (*)(struct vc_data *, const unsigned char *) con_set_palette;
    void (*)(struct vc_data *, int) con_scrolldelta;
    int (*)(struct vc_data *) con_set_origin;
    void (*)(struct vc_data *) con_save_screen;
    u8 (*)(struct vc_data *, u8, u8, u8, u8, u8, u8) con_build_attr;
    void (*)(struct vc_data *, u16 *, int) con_invert_region;
    u16 * (*)(struct vc_data *, int) con_screen_pos;
    long unsigned int (*)(struct vc_data *, long unsigned int, int *, int *) con_getxy;
    void (*)(struct vc_data *) con_flush_scrollback;
    int (*)(struct vc_data *) con_debug_enter;
    int (*)(struct vc_data *) con_debug_leave;
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
<code>void (*)(struct vc_data *, int, int, int, int, int, int) con_bmove</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct vc_data *, unsigned char *) con_set_palette</code> ➡️ <code>void (*)(struct vc_data *, const unsigned char *) con_set_palette</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct vc_data *, int) con_scrolldelta</code> ➡️ <code>void (*)(struct vc_data *, int) con_scrolldelta</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct vc_data *, int, int, int, int) con_scroll</code> ➡️ <code>bool (*)(struct vc_data *, unsigned int, unsigned int, enum con_scroll, unsigned int) con_scroll</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct vc_data *) con_flush_scrollback</code>
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
<b>Field removed. </b>
<code>int (*)(struct vc_data *, int) con_font_copy</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8 (*)(struct vc_data *, u8, u8, u8, u8, u8, u8) con_build_attr</code> ➡️ <code>u8 (*)(struct vc_data *, u8, enum vc_intensity, bool, bool, bool, bool) con_build_attr</code>
</li>
<li>
<b>Field type changed. </b>
<code>u16 * (*)(struct vc_data *, int) con_screen_pos</code> ➡️ <code>u16 * (*)(const struct vc_data *, int) con_screen_pos</code>
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
<b>Field type changed. </b>
<code>int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_set</code> ➡️ <code>int (*)(struct vc_data *, struct console_font *, unsigned int, unsigned int) con_font_set</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct vc_data *, struct console_font *) con_font_get</code> ➡️ <code>int (*)(struct vc_data *, struct console_font *, unsigned int) con_font_get</code>
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
