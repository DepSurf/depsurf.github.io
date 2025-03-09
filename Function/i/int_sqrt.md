# Function: <code>int_sqrt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582953504,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/int_sqrt.c:17",
      "file": "lib/int_sqrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582953504,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583241120,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/int_sqrt.c:17",
      "file": "lib/int_sqrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "mm/vmscan.c:inactive_list_is_low",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583241120,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583356432,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/int_sqrt.c:17",
      "file": "lib/int_sqrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "mm/vmscan.c:inactive_list_is_low",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583356432,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588205248,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/int_sqrt.c:17",
      "file": "lib/int_sqrt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "mm/vmscan.c:inactive_list_is_low",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588205248,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588754368,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/int_sqrt.c:19",
      "file": "lib/int_sqrt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "mm/vmscan.c:inactive_list_is_low",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588754368,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589132368,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/int_sqrt.c:19",
      "file": "lib/int_sqrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "mm/vmscan.c:inactive_list_is_low",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589132368,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589366928,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/int_sqrt.c:19",
      "file": "lib/int_sqrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "mm/vmscan.c:inactive_list_is_low",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589366928,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584155552,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/math/int_sqrt.c:19",
      "file": "lib/math/int_sqrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:inactive_list_is_low",
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584155552,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584278176,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/math/int_sqrt.c:19",
      "file": "lib/math/int_sqrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:inactive_list_is_low",
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584278176,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584687488,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/math/int_sqrt.c:19",
      "file": "lib/math/int_sqrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:inactive_is_low",
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584687488,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584805104,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/math/int_sqrt.c:20",
      "file": "lib/math/int_sqrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:inactive_is_low",
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584805104,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584849568,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/math/int_sqrt.c:20",
      "file": "lib/math/int_sqrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:inactive_is_low",
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584849568,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/math/int_sqrt.c:20",
      "file": "lib/math/int_sqrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:inactive_is_low",
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592325139,
      "name": "int_sqrt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071585269792,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/math/int_sqrt.c:20",
      "file": "lib/math/int_sqrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:inactive_is_low",
        "mm/page_alloc.c:calculate_min_free_kbytes",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594129628,
      "name": "int_sqrt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586113920,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/math/int_sqrt.c:20",
      "file": "lib/math/int_sqrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:inactive_is_low",
        "mm/page_alloc.c:calculate_min_free_kbytes",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596116518,
      "name": "int_sqrt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071587100032,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/math/int_sqrt.c:20",
      "file": "lib/math/int_sqrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:inactive_is_low",
        "mm/page_alloc.c:calculate_min_free_kbytes",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596642301,
      "name": "int_sqrt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071587360096,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/math/int_sqrt.c:20",
      "file": "lib/math/int_sqrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_organize_nocb_kthreads",
        "mm/vmscan.c:inactive_is_low",
        "mm/page_alloc.c:calculate_min_free_kbytes",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597550515,
      "name": "int_sqrt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071587646688,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496163880,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/math/int_sqrt.c:19",
      "file": "lib/math/int_sqrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496163880,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229486420,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/math/int_sqrt.c:19",
      "file": "lib/math/int_sqrt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:inactive_list_is_low",
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229486420,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290428640,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/math/int_sqrt.c:19",
      "file": "lib/math/int_sqrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290428640,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275214692,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/math/int_sqrt.c:19",
      "file": "lib/math/int_sqrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275214692,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584246912,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/math/int_sqrt.c:19",
      "file": "lib/math/int_sqrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:inactive_list_is_low",
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584246912,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584182112,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/math/int_sqrt.c:19",
      "file": "lib/math/int_sqrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init_nohz",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584182112,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584230672,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/math/int_sqrt.c:19",
      "file": "lib/math/int_sqrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:inactive_list_is_low",
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584230672,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
long unsigned int int_sqrt(long unsigned int x)
```

```json
{
  "name": "int_sqrt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584335504,
      "name": "int_sqrt",
      "external": true,
      "loc": "lib/math/int_sqrt.c:19",
      "file": "lib/math/int_sqrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:inactive_list_is_low",
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "block/blk-wbt.c:rwb_arm_timer",
        "drivers/video/fbdev/core/fbmon.c:fb_timings_dclk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584335504,
      "name": "int_sqrt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
