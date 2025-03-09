# Struct: <code>vc_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_color;
    unsigned char vc_s_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    unsigned int vc_x;
    unsigned int vc_y;
    unsigned int vc_saved_x;
    unsigned int vc_saved_y;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_charset;
    unsigned int vc_s_charset;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_deccolm;
    unsigned int vc_intensity;
    unsigned int vc_italic;
    unsigned int vc_underline;
    unsigned int vc_blink;
    unsigned int vc_reverse;
    unsigned int vc_s_intensity;
    unsigned int vc_s_italic;
    unsigned int vc_s_underline;
    unsigned int vc_s_blink;
    unsigned int vc_s_reverse;
    unsigned int vc_ques;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    unsigned int[8] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned char vc_G0_charset;
    unsigned char vc_G1_charset;
    unsigned char vc_saved_G0;
    unsigned char vc_saved_G1;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedir * vc_uni_pagedir;
    struct uni_pagedir * * vc_uni_pagedir_loc;
    bool vc_panic_force_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_color;
    unsigned char vc_s_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    unsigned int vc_x;
    unsigned int vc_y;
    unsigned int vc_saved_x;
    unsigned int vc_saved_y;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_charset;
    unsigned int vc_s_charset;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_intensity;
    unsigned int vc_italic;
    unsigned int vc_underline;
    unsigned int vc_blink;
    unsigned int vc_reverse;
    unsigned int vc_s_intensity;
    unsigned int vc_s_italic;
    unsigned int vc_s_underline;
    unsigned int vc_s_blink;
    unsigned int vc_s_reverse;
    unsigned int vc_ques;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    unsigned int[8] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned char vc_G0_charset;
    unsigned char vc_G1_charset;
    unsigned char vc_saved_G0;
    unsigned char vc_saved_G1;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedir * vc_uni_pagedir;
    struct uni_pagedir * * vc_uni_pagedir_loc;
    bool vc_panic_force_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_color;
    unsigned char vc_s_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    unsigned int vc_x;
    unsigned int vc_y;
    unsigned int vc_saved_x;
    unsigned int vc_saved_y;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_charset;
    unsigned int vc_s_charset;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_intensity;
    unsigned int vc_italic;
    unsigned int vc_underline;
    unsigned int vc_blink;
    unsigned int vc_reverse;
    unsigned int vc_s_intensity;
    unsigned int vc_s_italic;
    unsigned int vc_s_underline;
    unsigned int vc_s_blink;
    unsigned int vc_s_reverse;
    unsigned int vc_ques;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    unsigned int[8] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned char vc_G0_charset;
    unsigned char vc_G1_charset;
    unsigned char vc_saved_G0;
    unsigned char vc_saved_G1;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedir * vc_uni_pagedir;
    struct uni_pagedir * * vc_uni_pagedir_loc;
    bool vc_panic_force_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_color;
    unsigned char vc_s_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    unsigned int vc_x;
    unsigned int vc_y;
    unsigned int vc_saved_x;
    unsigned int vc_saved_y;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_charset;
    unsigned int vc_s_charset;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_intensity;
    unsigned int vc_italic;
    unsigned int vc_underline;
    unsigned int vc_blink;
    unsigned int vc_reverse;
    unsigned int vc_s_intensity;
    unsigned int vc_s_italic;
    unsigned int vc_s_underline;
    unsigned int vc_s_blink;
    unsigned int vc_s_reverse;
    unsigned int vc_ques;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    unsigned int[8] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned char vc_G0_charset;
    unsigned char vc_G1_charset;
    unsigned char vc_saved_G0;
    unsigned char vc_saved_G1;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedir * vc_uni_pagedir;
    struct uni_pagedir * * vc_uni_pagedir_loc;
    bool vc_panic_force_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_color;
    unsigned char vc_s_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    unsigned int vc_x;
    unsigned int vc_y;
    unsigned int vc_saved_x;
    unsigned int vc_saved_y;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_charset;
    unsigned int vc_s_charset;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_intensity;
    unsigned int vc_italic;
    unsigned int vc_underline;
    unsigned int vc_blink;
    unsigned int vc_reverse;
    unsigned int vc_s_intensity;
    unsigned int vc_s_italic;
    unsigned int vc_s_underline;
    unsigned int vc_s_blink;
    unsigned int vc_s_reverse;
    unsigned int vc_ques;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    unsigned int[8] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned char vc_G0_charset;
    unsigned char vc_G1_charset;
    unsigned char vc_saved_G0;
    unsigned char vc_saved_G1;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedir * vc_uni_pagedir;
    struct uni_pagedir * * vc_uni_pagedir_loc;
    bool vc_panic_force_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_color;
    unsigned char vc_s_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    unsigned int vc_x;
    unsigned int vc_y;
    unsigned int vc_saved_x;
    unsigned int vc_saved_y;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_charset;
    unsigned int vc_s_charset;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_intensity;
    unsigned int vc_italic;
    unsigned int vc_underline;
    unsigned int vc_blink;
    unsigned int vc_reverse;
    unsigned int vc_s_intensity;
    unsigned int vc_s_italic;
    unsigned int vc_s_underline;
    unsigned int vc_s_blink;
    unsigned int vc_s_reverse;
    unsigned int vc_ques;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    unsigned int[8] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned char vc_G0_charset;
    unsigned char vc_G1_charset;
    unsigned char vc_saved_G0;
    unsigned char vc_saved_G1;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedir * vc_uni_pagedir;
    struct uni_pagedir * * vc_uni_pagedir_loc;
    bool vc_panic_force_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_color;
    unsigned char vc_s_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    unsigned int vc_x;
    unsigned int vc_y;
    unsigned int vc_saved_x;
    unsigned int vc_saved_y;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_charset;
    unsigned int vc_s_charset;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_intensity;
    unsigned int vc_italic;
    unsigned int vc_underline;
    unsigned int vc_blink;
    unsigned int vc_reverse;
    unsigned int vc_s_intensity;
    unsigned int vc_s_italic;
    unsigned int vc_s_underline;
    unsigned int vc_s_blink;
    unsigned int vc_s_reverse;
    unsigned int vc_ques;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    unsigned int[8] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned char vc_G0_charset;
    unsigned char vc_G1_charset;
    unsigned char vc_saved_G0;
    unsigned char vc_saved_G1;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedir * vc_uni_pagedir;
    struct uni_pagedir * * vc_uni_pagedir_loc;
    struct uni_screen * vc_uni_screen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_color;
    unsigned char vc_s_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    unsigned int vc_x;
    unsigned int vc_y;
    unsigned int vc_saved_x;
    unsigned int vc_saved_y;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_charset;
    unsigned int vc_s_charset;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_intensity;
    unsigned int vc_italic;
    unsigned int vc_underline;
    unsigned int vc_blink;
    unsigned int vc_reverse;
    unsigned int vc_s_intensity;
    unsigned int vc_s_italic;
    unsigned int vc_s_underline;
    unsigned int vc_s_blink;
    unsigned int vc_s_reverse;
    unsigned int vc_priv;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    unsigned int[8] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned char vc_G0_charset;
    unsigned char vc_G1_charset;
    unsigned char vc_saved_G0;
    unsigned char vc_saved_G1;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedir * vc_uni_pagedir;
    struct uni_pagedir * * vc_uni_pagedir_loc;
    struct uni_screen * vc_uni_screen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_color;
    unsigned char vc_s_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    unsigned int vc_x;
    unsigned int vc_y;
    unsigned int vc_saved_x;
    unsigned int vc_saved_y;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_charset;
    unsigned int vc_s_charset;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_intensity;
    unsigned int vc_italic;
    unsigned int vc_underline;
    unsigned int vc_blink;
    unsigned int vc_reverse;
    unsigned int vc_s_intensity;
    unsigned int vc_s_italic;
    unsigned int vc_s_underline;
    unsigned int vc_s_blink;
    unsigned int vc_s_reverse;
    unsigned int vc_priv;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    unsigned int[8] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned char vc_G0_charset;
    unsigned char vc_G1_charset;
    unsigned char vc_saved_G0;
    unsigned char vc_saved_G1;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedir * vc_uni_pagedir;
    struct uni_pagedir * * vc_uni_pagedir_loc;
    struct uni_screen * vc_uni_screen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_color;
    unsigned char vc_s_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    unsigned int vc_x;
    unsigned int vc_y;
    unsigned int vc_saved_x;
    unsigned int vc_saved_y;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_charset;
    unsigned int vc_s_charset;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_intensity;
    unsigned int vc_italic;
    unsigned int vc_underline;
    unsigned int vc_blink;
    unsigned int vc_reverse;
    unsigned int vc_s_intensity;
    unsigned int vc_s_italic;
    unsigned int vc_s_underline;
    unsigned int vc_s_blink;
    unsigned int vc_s_reverse;
    unsigned int vc_priv;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    unsigned int[8] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned char vc_G0_charset;
    unsigned char vc_G1_charset;
    unsigned char vc_saved_G0;
    unsigned char vc_saved_G1;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedir * vc_uni_pagedir;
    struct uni_pagedir * * vc_uni_pagedir_loc;
    struct uni_screen * vc_uni_screen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    struct vc_state state;
    struct vc_state saved_state;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_priv;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    long unsigned int[4] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedir * vc_uni_pagedir;
    struct uni_pagedir * * vc_uni_pagedir_loc;
    struct uni_screen * vc_uni_screen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    struct vc_state state;
    struct vc_state saved_state;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    unsigned int vc_cell_height;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_priv;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    long unsigned int[4] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedir * vc_uni_pagedir;
    struct uni_pagedir * * vc_uni_pagedir_loc;
    struct uni_screen * vc_uni_screen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    struct vc_state state;
    struct vc_state saved_state;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    unsigned int vc_cell_height;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_priv;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    long unsigned int[4] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedir * vc_uni_pagedir;
    struct uni_pagedir * * vc_uni_pagedir_loc;
    struct uni_screen * vc_uni_screen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    struct vc_state state;
    struct vc_state saved_state;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    unsigned int vc_cell_height;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_priv;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    long unsigned int[4] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedir * vc_uni_pagedir;
    struct uni_pagedir * * vc_uni_pagedir_loc;
    struct uni_screen * vc_uni_screen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    struct vc_state state;
    struct vc_state saved_state;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    unsigned int vc_cell_height;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_priv;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    long unsigned int[4] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedict * uni_pagedict;
    struct uni_pagedict * * uni_pagedict_loc;
    struct uni_screen * vc_uni_screen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    struct vc_state state;
    struct vc_state saved_state;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    unsigned int vc_cell_height;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_priv;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    long unsigned int[4] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedict * uni_pagedict;
    struct uni_pagedict * * uni_pagedict_loc;
    u32 * * vc_uni_lines;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    struct vc_state state;
    struct vc_state saved_state;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    unsigned int vc_cell_height;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_priv;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    long unsigned int[4] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedict * uni_pagedict;
    struct uni_pagedict * * uni_pagedict_loc;
    u32 * * vc_uni_lines;
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
struct vc_data {
    struct tty_port port;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_color;
    unsigned char vc_s_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    unsigned int vc_x;
    unsigned int vc_y;
    unsigned int vc_saved_x;
    unsigned int vc_saved_y;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_charset;
    unsigned int vc_s_charset;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_intensity;
    unsigned int vc_italic;
    unsigned int vc_underline;
    unsigned int vc_blink;
    unsigned int vc_reverse;
    unsigned int vc_s_intensity;
    unsigned int vc_s_italic;
    unsigned int vc_s_underline;
    unsigned int vc_s_blink;
    unsigned int vc_s_reverse;
    unsigned int vc_priv;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    unsigned int[8] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned char vc_G0_charset;
    unsigned char vc_G1_charset;
    unsigned char vc_saved_G0;
    unsigned char vc_saved_G1;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedir * vc_uni_pagedir;
    struct uni_pagedir * * vc_uni_pagedir_loc;
    struct uni_screen * vc_uni_screen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_color;
    unsigned char vc_s_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    unsigned int vc_x;
    unsigned int vc_y;
    unsigned int vc_saved_x;
    unsigned int vc_saved_y;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_charset;
    unsigned int vc_s_charset;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_intensity;
    unsigned int vc_italic;
    unsigned int vc_underline;
    unsigned int vc_blink;
    unsigned int vc_reverse;
    unsigned int vc_s_intensity;
    unsigned int vc_s_italic;
    unsigned int vc_s_underline;
    unsigned int vc_s_blink;
    unsigned int vc_s_reverse;
    unsigned int vc_priv;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    unsigned int[8] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned char vc_G0_charset;
    unsigned char vc_G1_charset;
    unsigned char vc_saved_G0;
    unsigned char vc_saved_G1;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedir * vc_uni_pagedir;
    struct uni_pagedir * * vc_uni_pagedir_loc;
    struct uni_screen * vc_uni_screen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_color;
    unsigned char vc_s_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    unsigned int vc_x;
    unsigned int vc_y;
    unsigned int vc_saved_x;
    unsigned int vc_saved_y;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_charset;
    unsigned int vc_s_charset;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_intensity;
    unsigned int vc_italic;
    unsigned int vc_underline;
    unsigned int vc_blink;
    unsigned int vc_reverse;
    unsigned int vc_s_intensity;
    unsigned int vc_s_italic;
    unsigned int vc_s_underline;
    unsigned int vc_s_blink;
    unsigned int vc_s_reverse;
    unsigned int vc_priv;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    unsigned int[8] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned char vc_G0_charset;
    unsigned char vc_G1_charset;
    unsigned char vc_saved_G0;
    unsigned char vc_saved_G1;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedir * vc_uni_pagedir;
    struct uni_pagedir * * vc_uni_pagedir_loc;
    struct uni_screen * vc_uni_screen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_color;
    unsigned char vc_s_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    unsigned int vc_x;
    unsigned int vc_y;
    unsigned int vc_saved_x;
    unsigned int vc_saved_y;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_charset;
    unsigned int vc_s_charset;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_intensity;
    unsigned int vc_italic;
    unsigned int vc_underline;
    unsigned int vc_blink;
    unsigned int vc_reverse;
    unsigned int vc_s_intensity;
    unsigned int vc_s_italic;
    unsigned int vc_s_underline;
    unsigned int vc_s_blink;
    unsigned int vc_s_reverse;
    unsigned int vc_priv;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    unsigned int[8] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned char vc_G0_charset;
    unsigned char vc_G1_charset;
    unsigned char vc_saved_G0;
    unsigned char vc_saved_G1;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedir * vc_uni_pagedir;
    struct uni_pagedir * * vc_uni_pagedir_loc;
    struct uni_screen * vc_uni_screen;
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
struct vc_data {
    struct tty_port port;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_color;
    unsigned char vc_s_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    unsigned int vc_x;
    unsigned int vc_y;
    unsigned int vc_saved_x;
    unsigned int vc_saved_y;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_charset;
    unsigned int vc_s_charset;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_intensity;
    unsigned int vc_italic;
    unsigned int vc_underline;
    unsigned int vc_blink;
    unsigned int vc_reverse;
    unsigned int vc_s_intensity;
    unsigned int vc_s_italic;
    unsigned int vc_s_underline;
    unsigned int vc_s_blink;
    unsigned int vc_s_reverse;
    unsigned int vc_priv;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    unsigned int[8] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned char vc_G0_charset;
    unsigned char vc_G1_charset;
    unsigned char vc_saved_G0;
    unsigned char vc_saved_G1;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedir * vc_uni_pagedir;
    struct uni_pagedir * * vc_uni_pagedir_loc;
    struct uni_screen * vc_uni_screen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_color;
    unsigned char vc_s_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    unsigned int vc_x;
    unsigned int vc_y;
    unsigned int vc_saved_x;
    unsigned int vc_saved_y;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_charset;
    unsigned int vc_s_charset;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_intensity;
    unsigned int vc_italic;
    unsigned int vc_underline;
    unsigned int vc_blink;
    unsigned int vc_reverse;
    unsigned int vc_s_intensity;
    unsigned int vc_s_italic;
    unsigned int vc_s_underline;
    unsigned int vc_s_blink;
    unsigned int vc_s_reverse;
    unsigned int vc_priv;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    unsigned int[8] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned char vc_G0_charset;
    unsigned char vc_G1_charset;
    unsigned char vc_saved_G0;
    unsigned char vc_saved_G1;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedir * vc_uni_pagedir;
    struct uni_pagedir * * vc_uni_pagedir_loc;
    struct uni_screen * vc_uni_screen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_color;
    unsigned char vc_s_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    unsigned int vc_x;
    unsigned int vc_y;
    unsigned int vc_saved_x;
    unsigned int vc_saved_y;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_charset;
    unsigned int vc_s_charset;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_intensity;
    unsigned int vc_italic;
    unsigned int vc_underline;
    unsigned int vc_blink;
    unsigned int vc_reverse;
    unsigned int vc_s_intensity;
    unsigned int vc_s_italic;
    unsigned int vc_s_underline;
    unsigned int vc_s_blink;
    unsigned int vc_s_reverse;
    unsigned int vc_priv;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    unsigned int[8] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned char vc_G0_charset;
    unsigned char vc_G1_charset;
    unsigned char vc_saved_G0;
    unsigned char vc_saved_G1;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedir * vc_uni_pagedir;
    struct uni_pagedir * * vc_uni_pagedir_loc;
    struct uni_screen * vc_uni_screen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct vc_data {
    struct tty_port port;
    short unsigned int vc_num;
    unsigned int vc_cols;
    unsigned int vc_rows;
    unsigned int vc_size_row;
    unsigned int vc_scan_lines;
    long unsigned int vc_origin;
    long unsigned int vc_scr_end;
    long unsigned int vc_visible_origin;
    unsigned int vc_top;
    unsigned int vc_bottom;
    const struct consw * vc_sw;
    short unsigned int * vc_screenbuf;
    unsigned int vc_screenbuf_size;
    unsigned char vc_mode;
    unsigned char vc_attr;
    unsigned char vc_def_color;
    unsigned char vc_color;
    unsigned char vc_s_color;
    unsigned char vc_ulcolor;
    unsigned char vc_itcolor;
    unsigned char vc_halfcolor;
    unsigned int vc_cursor_type;
    short unsigned int vc_complement_mask;
    short unsigned int vc_s_complement_mask;
    unsigned int vc_x;
    unsigned int vc_y;
    unsigned int vc_saved_x;
    unsigned int vc_saved_y;
    long unsigned int vc_pos;
    short unsigned int vc_hi_font_mask;
    struct console_font vc_font;
    short unsigned int vc_video_erase_char;
    unsigned int vc_state;
    unsigned int vc_npar;
    unsigned int[16] vc_par;
    struct vt_mode vt_mode;
    struct pid * vt_pid;
    int vt_newvt;
    wait_queue_head_t paste_wait;
    unsigned int vc_charset;
    unsigned int vc_s_charset;
    unsigned int vc_disp_ctrl;
    unsigned int vc_toggle_meta;
    unsigned int vc_decscnm;
    unsigned int vc_decom;
    unsigned int vc_decawm;
    unsigned int vc_deccm;
    unsigned int vc_decim;
    unsigned int vc_intensity;
    unsigned int vc_italic;
    unsigned int vc_underline;
    unsigned int vc_blink;
    unsigned int vc_reverse;
    unsigned int vc_s_intensity;
    unsigned int vc_s_italic;
    unsigned int vc_s_underline;
    unsigned int vc_s_blink;
    unsigned int vc_s_reverse;
    unsigned int vc_priv;
    unsigned int vc_need_wrap;
    unsigned int vc_can_do_color;
    unsigned int vc_report_mouse;
    unsigned char vc_utf;
    unsigned char vc_utf_count;
    int vc_utf_char;
    unsigned int[8] vc_tab_stop;
    unsigned char[48] vc_palette;
    short unsigned int * vc_translate;
    unsigned char vc_G0_charset;
    unsigned char vc_G1_charset;
    unsigned char vc_saved_G0;
    unsigned char vc_saved_G1;
    unsigned int vc_resize_user;
    unsigned int vc_bell_pitch;
    unsigned int vc_bell_duration;
    short unsigned int vc_cur_blink_ms;
    struct vc_data * * vc_display_fg;
    struct uni_pagedir * vc_uni_pagedir;
    struct uni_pagedir * * vc_uni_pagedir_loc;
    struct uni_screen * vc_uni_screen;
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
<code>unsigned int vc_deccolm</code>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct uni_screen * vc_uni_screen</code>
</li>
<li>
<b>Field removed. </b>
<code>bool vc_panic_force_write</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int vc_priv</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int vc_ques</code>
</li>
</ul>
</details>
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
<b>Field added. </b>
<code>struct vc_state state</code>
</li>
<li>
<b>Field added. </b>
<code>struct vc_state saved_state</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char vc_color</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char vc_s_color</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int vc_x</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int vc_y</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int vc_saved_x</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int vc_saved_y</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int vc_charset</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int vc_s_charset</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int vc_intensity</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int vc_italic</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int vc_underline</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int vc_blink</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int vc_reverse</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int vc_s_intensity</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int vc_s_italic</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int vc_s_underline</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int vc_s_blink</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int vc_s_reverse</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char vc_G0_charset</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char vc_G1_charset</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char vc_saved_G0</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char vc_saved_G1</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int[8] vc_tab_stop</code> ➡️ <code>long unsigned int[4] vc_tab_stop</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int vc_cell_height</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct uni_pagedict * uni_pagedict</code>
</li>
<li>
<b>Field added. </b>
<code>struct uni_pagedict * * uni_pagedict_loc</code>
</li>
<li>
<b>Field removed. </b>
<code>struct uni_pagedir * vc_uni_pagedir</code>
</li>
<li>
<b>Field removed. </b>
<code>struct uni_pagedir * * vc_uni_pagedir_loc</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 * * vc_uni_lines</code>
</li>
<li>
<b>Field removed. </b>
<code>struct uni_screen * vc_uni_screen</code>
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
