# Function: <code>submit_bh_wbc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int submit_bh_wbc(int rw, struct buffer_head * bh, long unsigned int bio_flags, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581223392,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:2999",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:_submit_bh",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581223392,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
int submit_bh_wbc(int op, int op_flags, struct buffer_head * bh, long unsigned int bio_flags, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581388576,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:3055",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:_submit_bh",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581388576,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
int submit_bh_wbc(int op, int op_flags, struct buffer_head * bh, long unsigned int bio_flags, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581467056,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:3096",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:_submit_bh",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581467056,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int submit_bh_wbc(int op, int op_flags, struct buffer_head * bh, enum rw_hint write_hint, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581522576,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:3090",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581522576,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
int submit_bh_wbc(int op, int op_flags, struct buffer_head * bh, enum rw_hint write_hint, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581664848,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:3058",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581664848,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
int submit_bh_wbc(int op, int op_flags, struct buffer_head * bh, enum rw_hint write_hint, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581828160,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:3029",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581828160,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
int submit_bh_wbc(int op, int op_flags, struct buffer_head * bh, enum rw_hint write_hint, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581915408,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:3041",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581915408,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
int submit_bh_wbc(int op, int op_flags, struct buffer_head * bh, enum rw_hint write_hint, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582052576,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:3048",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582052576,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
int submit_bh_wbc(int op, int op_flags, struct buffer_head * bh, enum rw_hint write_hint, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582130240,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:3025",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582130240,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
int submit_bh_wbc(int op, int op_flags, struct buffer_head * bh, enum rw_hint write_hint, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582357104,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:3026",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582357104,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
int submit_bh_wbc(int op, int op_flags, struct buffer_head * bh, enum rw_hint write_hint, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582413808,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:3009",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582413808,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
int submit_bh_wbc(int op, int op_flags, struct buffer_head * bh, enum rw_hint write_hint, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582441008,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:3030",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441008,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int submit_bh_wbc(int op, int op_flags, struct buffer_head * bh, enum rw_hint write_hint, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582763824,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:3009",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582763824,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
int submit_bh_wbc(int op, int op_flags, struct buffer_head * bh, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583313728,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:2997",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:bh_submit_read",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583313728,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
void submit_bh_wbc(blk_opf_t opf, struct buffer_head * bh, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583900160,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:2659",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:__bh_read",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583900160,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
void submit_bh_wbc(blk_opf_t opf, struct buffer_head * bh, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584123600,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:2798",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:__bh_read",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123600,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
void submit_bh_wbc(blk_opf_t opf, struct buffer_head * bh, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:2758",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:__bh_read",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584340272,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071597479367,
      "name": "submit_bh_wbc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int submit_bh_wbc(int op, int op_flags, struct buffer_head * bh, enum rw_hint write_hint, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493673840,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:3025",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493673840,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
int submit_bh_wbc(int op, int op_flags, struct buffer_head * bh, enum rw_hint write_hint, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227205944,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:3025",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227205944,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
int submit_bh_wbc(int op, int op_flags, struct buffer_head * bh, enum rw_hint write_hint, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287275440,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:3025",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287275440,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
int submit_bh_wbc(int op, int op_flags, struct buffer_head * bh, enum rw_hint write_hint, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273299376,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:3025",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273299376,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int submit_bh_wbc(int op, int op_flags, struct buffer_head * bh, enum rw_hint write_hint, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582098976,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:3025",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582098976,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
int submit_bh_wbc(int op, int op_flags, struct buffer_head * bh, enum rw_hint write_hint, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582036416,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:3025",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582036416,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
int submit_bh_wbc(int op, int op_flags, struct buffer_head * bh, enum rw_hint write_hint, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582089456,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:3025",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582089456,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
int submit_bh_wbc(int op, int op_flags, struct buffer_head * bh, enum rw_hint write_hint, struct writeback_control * wbc)
```

```json
{
  "name": "submit_bh_wbc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582162192,
      "name": "submit_bh_wbc",
      "external": false,
      "loc": "fs/buffer.c:3025",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582162192,
      "name": "submit_bh_wbc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int op</code>
</li>
<li>
<b>Param added. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
<li>
<b>Param reordered. </b>
<code>rw, bh, bio_flags, wbc</code> ➡️ <code>op, op_flags, bh, bio_flags, wbc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum rw_hint write_hint</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int bio_flags</code>
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
<b>Param removed. </b>
<code>enum rw_hint write_hint</code>
</li>
<li>
<b>Param reordered. </b>
<code>op, op_flags, bh, write_hint, wbc</code> ➡️ <code>op, op_flags, bh, wbc</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_opf_t opf</code>
</li>
<li>
<b>Param removed. </b>
<code>int op</code>
</li>
<li>
<b>Param removed. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>op, op_flags, bh, wbc</code> ➡️ <code>opf, bh, wbc</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
