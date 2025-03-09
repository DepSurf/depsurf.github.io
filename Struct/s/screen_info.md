# Struct: <code>screen_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
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
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
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
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct screen_info {
    __u8 orig_x;
    __u8 orig_y;
    __u16 ext_mem_k;
    __u16 orig_video_page;
    __u8 orig_video_mode;
    __u8 orig_video_cols;
    __u8 flags;
    __u8 unused2;
    __u16 orig_video_ega_bx;
    __u16 unused3;
    __u8 orig_video_lines;
    __u8 orig_video_isVGA;
    __u16 orig_video_points;
    __u16 lfb_width;
    __u16 lfb_height;
    __u16 lfb_depth;
    __u32 lfb_base;
    __u32 lfb_size;
    __u16 cl_magic;
    __u16 cl_offset;
    __u16 lfb_linelength;
    __u8 red_size;
    __u8 red_pos;
    __u8 green_size;
    __u8 green_pos;
    __u8 blue_size;
    __u8 blue_pos;
    __u8 rsvd_size;
    __u8 rsvd_pos;
    __u16 vesapm_seg;
    __u16 vesapm_off;
    __u16 pages;
    __u16 vesa_attributes;
    __u32 capabilities;
    __u32 ext_lfb_base;
    __u8[2] _reserved;
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
