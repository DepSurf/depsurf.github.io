# Function: <code>swap_read_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```

```json
{
  "name": "swap_read_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579709488,
      "name": "swap_read_page",
      "external": false,
      "loc": "kernel/power/swap.c:996",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:load_image",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:swsusp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709488,
      "name": "swap_read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```

```json
{
  "name": "swap_read_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579729376,
      "name": "swap_read_page",
      "external": false,
      "loc": "kernel/power/swap.c:1016",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579729376,
      "name": "swap_read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```

```json
{
  "name": "swap_read_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579756768,
      "name": "swap_read_page",
      "external": false,
      "loc": "kernel/power/swap.c:1015",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579756768,
      "name": "swap_read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```

```json
{
  "name": "swap_read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579752848,
      "name": "swap_read_page",
      "external": false,
      "loc": "kernel/power/swap.c:1015",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579752848,
      "name": "swap_read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```

```json
{
  "name": "swap_read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579786240,
      "name": "swap_read_page",
      "external": false,
      "loc": "kernel/power/swap.c:1010",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579786240,
      "name": "swap_read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```

```json
{
  "name": "swap_read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579820256,
      "name": "swap_read_page",
      "external": false,
      "loc": "kernel/power/swap.c:1010",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579820256,
      "name": "swap_read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```

```json
{
  "name": "swap_read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579866960,
      "name": "swap_read_page",
      "external": false,
      "loc": "kernel/power/swap.c:1010",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866960,
      "name": "swap_read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```

```json
{
  "name": "swap_read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579901504,
      "name": "swap_read_page",
      "external": false,
      "loc": "kernel/power/swap.c:1007",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579901504,
      "name": "swap_read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```

```json
{
  "name": "swap_read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579951728,
      "name": "swap_read_page",
      "external": false,
      "loc": "kernel/power/swap.c:1007",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951728,
      "name": "swap_read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```

```json
{
  "name": "swap_read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579996960,
      "name": "swap_read_page",
      "external": false,
      "loc": "kernel/power/swap.c:1007",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579996960,
      "name": "swap_read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```

```json
{
  "name": "swap_read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579978976,
      "name": "swap_read_page",
      "external": false,
      "loc": "kernel/power/swap.c:1017",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579978976,
      "name": "swap_read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```

```json
{
  "name": "swap_read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579980944,
      "name": "swap_read_page",
      "external": false,
      "loc": "kernel/power/swap.c:1017",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980944,
      "name": "swap_read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```

```json
{
  "name": "swap_read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580112480,
      "name": "swap_read_page",
      "external": false,
      "loc": "kernel/power/swap.c:1017",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580112480,
      "name": "swap_read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```

```json
{
  "name": "swap_read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580252768,
      "name": "swap_read_page",
      "external": false,
      "loc": "kernel/power/swap.c:1018",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580252768,
      "name": "swap_read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```

```json
{
  "name": "swap_read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580453280,
      "name": "swap_read_page",
      "external": false,
      "loc": "kernel/power/swap.c:1016",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580453280,
      "name": "swap_read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```

```json
{
  "name": "swap_read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580523344,
      "name": "swap_read_page",
      "external": false,
      "loc": "kernel/power/swap.c:1016",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580523344,
      "name": "swap_read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```

```json
{
  "name": "swap_read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580584880,
      "name": "swap_read_page",
      "external": false,
      "loc": "kernel/power/swap.c:1017",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580584880,
      "name": "swap_read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```

```json
{
  "name": "swap_read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225162500,
      "name": "swap_read_page",
      "external": false,
      "loc": "kernel/power/swap.c:1007",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:load_image_lzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225162500,
      "name": "swap_read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swap_read_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579924050,
      "name": "swap_read_page",
      "external": false,
      "loc": "kernel/power/swap.c:1167",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:load_image"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```

```json
{
  "name": "swap_read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579858736,
      "name": "swap_read_page",
      "external": false,
      "loc": "kernel/power/swap.c:1007",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858736,
      "name": "swap_read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```

```json
{
  "name": "swap_read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579912000,
      "name": "swap_read_page",
      "external": false,
      "loc": "kernel/power/swap.c:1007",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579912000,
      "name": "swap_read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```

```json
{
  "name": "swap_read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579958048,
      "name": "swap_read_page",
      "external": false,
      "loc": "kernel/power/swap.c:1007",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579958048,
      "name": "swap_read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int swap_read_page(struct swap_map_handle * handle, void * buf, struct hib_bio_batch * hb)
```
</details>
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
