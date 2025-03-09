# Struct: <code>fbcon_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct timer_list cursor_timer;
    struct fb_cursor cursor_state;
    struct display * p;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    int flags;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct timer_list cursor_timer;
    struct fb_cursor cursor_state;
    struct display * p;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    int flags;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct timer_list cursor_timer;
    struct fb_cursor cursor_state;
    struct display * p;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    int flags;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct timer_list cursor_timer;
    struct fb_cursor cursor_state;
    struct display * p;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    int flags;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct timer_list cursor_timer;
    struct fb_cursor cursor_state;
    struct display * p;
    struct fb_info * info;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    int flags;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct timer_list cursor_timer;
    struct fb_cursor cursor_state;
    struct display * p;
    struct fb_info * info;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    int flags;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct timer_list cursor_timer;
    struct fb_cursor cursor_state;
    struct display * p;
    struct fb_info * info;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    int flags;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct timer_list cursor_timer;
    struct fb_cursor cursor_state;
    struct fbcon_display * p;
    struct fb_info * info;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    int flags;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct timer_list cursor_timer;
    struct fb_cursor cursor_state;
    struct fbcon_display * p;
    struct fb_info * info;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    int flags;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct timer_list cursor_timer;
    struct fb_cursor cursor_state;
    struct fbcon_display * p;
    struct fb_info * info;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    int flags;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct timer_list cursor_timer;
    struct fb_cursor cursor_state;
    struct fbcon_display * p;
    struct fb_info * info;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    int flags;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct timer_list cursor_timer;
    struct fb_cursor cursor_state;
    struct fbcon_display * p;
    struct fb_info * info;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    int flags;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct timer_list cursor_timer;
    struct fb_cursor cursor_state;
    struct fbcon_display * p;
    struct fb_info * info;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    int flags;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct delayed_work cursor_work;
    struct fb_cursor cursor_state;
    struct fbcon_display * p;
    struct fb_info * info;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    bool initialized;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct delayed_work cursor_work;
    struct fb_cursor cursor_state;
    struct fbcon_display * p;
    struct fb_info * info;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    bool initialized;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct delayed_work cursor_work;
    struct fb_cursor cursor_state;
    struct fbcon_display * p;
    struct fb_info * info;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    bool initialized;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct delayed_work cursor_work;
    struct fb_cursor cursor_state;
    struct fbcon_display * p;
    struct fb_info * info;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    bool initialized;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
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
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct timer_list cursor_timer;
    struct fb_cursor cursor_state;
    struct fbcon_display * p;
    struct fb_info * info;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    int flags;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct timer_list cursor_timer;
    struct fb_cursor cursor_state;
    struct fbcon_display * p;
    struct fb_info * info;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    int flags;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct timer_list cursor_timer;
    struct fb_cursor cursor_state;
    struct fbcon_display * p;
    struct fb_info * info;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    int flags;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct timer_list cursor_timer;
    struct fb_cursor cursor_state;
    struct fbcon_display * p;
    struct fb_info * info;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    int flags;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
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
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct timer_list cursor_timer;
    struct fb_cursor cursor_state;
    struct fbcon_display * p;
    struct fb_info * info;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    int flags;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct timer_list cursor_timer;
    struct fb_cursor cursor_state;
    struct fbcon_display * p;
    struct fb_info * info;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    int flags;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct timer_list cursor_timer;
    struct fb_cursor cursor_state;
    struct fbcon_display * p;
    struct fb_info * info;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    int flags;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fbcon_ops {
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int, int, int) bmove;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) clear;
    void (*)(struct vc_data *, struct fb_info *, const short unsigned int *, int, int, int, int, int) putcs;
    void (*)(struct vc_data *, struct fb_info *, int, int) clear_margins;
    void (*)(struct vc_data *, struct fb_info *, int, int, int, int) cursor;
    int (*)(struct fb_info *) update_start;
    int (*)(struct fb_info *, struct vc_data *) rotate_font;
    struct fb_var_screeninfo var;
    struct timer_list cursor_timer;
    struct fb_cursor cursor_state;
    struct fbcon_display * p;
    struct fb_info * info;
    int currcon;
    int cur_blink_jiffies;
    int cursor_flash;
    int cursor_reset;
    int blank_state;
    int graphics;
    int save_graphics;
    int flags;
    int rotate;
    int cur_rotate;
    char * cursor_data;
    u8 * fontbuffer;
    u8 * fontdata;
    u8 * cursor_src;
    u32 cursor_size;
    u32 fd_size;
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct fb_info * info</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct vc_data *, struct fb_info *, int) clear_margins</code> ➡️ <code>void (*)(struct vc_data *, struct fb_info *, int, int) clear_margins</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct display * p</code> ➡️ <code>struct fbcon_display * p</code>
</li>
</ul>
</details>
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
<code>void (*)(struct vc_data *, struct fb_info *, int, int, int, int) cursor</code> ➡️ <code>void (*)(struct vc_data *, struct fb_info *, int, int, int) cursor</code>
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
<code>struct delayed_work cursor_work</code>
</li>
<li>
<b>Field added. </b>
<code>bool initialized</code>
</li>
<li>
<b>Field removed. </b>
<code>struct timer_list cursor_timer</code>
</li>
<li>
<b>Field removed. </b>
<code>int flags</code>
</li>
</ul>
</details>
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
