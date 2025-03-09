# Function: <code>edac_mc_handle_error</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```

```json
{
  "name": "edac_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586563808,
      "name": "edac_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1086",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586563808,
      "name": "edac_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1937
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```

```json
{
  "name": "edac_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587031344,
      "name": "edac_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1091",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587031344,
      "name": "edac_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1465
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```

```json
{
  "name": "edac_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1093",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587333772,
      "name": "edac_mc_handle_error.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071587329296,
      "name": "edac_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1373
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```

```json
{
  "name": "edac_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1086",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587512101,
      "name": "edac_mc_handle_error.cold.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071587507632,
      "name": "edac_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1373
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```

```json
{
  "name": "edac_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1082",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587785949,
      "name": "edac_mc_handle_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071587781568,
      "name": "edac_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1414
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```

```json
{
  "name": "edac_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1075",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587990685,
      "name": "edac_mc_handle_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071587986272,
      "name": "edac_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1451
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```

```json
{
  "name": "edac_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1012",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588844728,
      "name": "edac_mc_handle_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071588841696,
      "name": "edac_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```

```json
{
  "name": "edac_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1016",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591594221,
      "name": "edac_mc_handle_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071588857440,
      "name": "edac_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```

```json
{
  "name": "edac_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1016",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591537366,
      "name": "edac_mc_handle_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071588744544,
      "name": "edac_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1358
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```

```json
{
  "name": "edac_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1019",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592651218,
      "name": "edac_mc_handle_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589435008,
      "name": "edac_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1798
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```

```json
{
  "name": "edac_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590913392,
      "name": "edac_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:944",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590913392,
      "name": "edac_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1578
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```

```json
{
  "name": "edac_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592611632,
      "name": "edac_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:943",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592611632,
      "name": "edac_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1455
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```

```json
{
  "name": "edac_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593042224,
      "name": "edac_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:943",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593042224,
      "name": "edac_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1455
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```

```json
{
  "name": "edac_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593793664,
      "name": "edac_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:944",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593793664,
      "name": "edac_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1455
    }
  ]
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
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```

```json
{
  "name": "edac_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501231608,
      "name": "edac_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1075",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/altera_edac.c:altr_sdram_mc_err_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501231608,
      "name": "edac_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```

```json
{
  "name": "edac_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233734832,
      "name": "edac_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1075",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/armada_xp_edac.c:axp_mc_check",
        "drivers/edac/armada_xp_edac.c:axp_mc_check",
        "drivers/edac/armada_xp_edac.c:axp_mc_check",
        "drivers/edac/armada_xp_edac.c:axp_mc_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233734832,
      "name": "edac_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1552
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```

```json
{
  "name": "edac_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294760368,
      "name": "edac_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1075",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294760368,
      "name": "edac_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1696
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```

```json
{
  "name": "edac_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277926026,
      "name": "edac_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1075",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277926026,
      "name": "edac_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1360
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```

```json
{
  "name": "edac_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1075",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587621661,
      "name": "edac_mc_handle_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071587617248,
      "name": "edac_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1451
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```

```json
{
  "name": "edac_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1075",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587389677,
      "name": "edac_mc_handle_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071587385264,
      "name": "edac_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1451
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```

```json
{
  "name": "edac_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1075",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587946829,
      "name": "edac_mc_handle_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071587942416,
      "name": "edac_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1451
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```

```json
{
  "name": "edac_mc_handle_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_handle_error",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:1075",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588062173,
      "name": "edac_mc_handle_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071588057728,
      "name": "edac_mc_handle_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1476
    }
  ]
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void edac_mc_handle_error(const enum hw_event_mc_err_type type, struct mem_ctl_info * mci, const u16 error_count, const long unsigned int page_frame_number, const long unsigned int offset_in_page, const long unsigned int syndrome, const int top_layer, const int mid_layer, const int low_layer, const char * msg, const char * other_detail)
```
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
