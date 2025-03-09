# Function: <code>skein_1024_process_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void skein_1024_process_block(struct skein_1024_ctx * ctx, const u8 * blk_ptr, size_t blk_cnt, size_t byte_cnt_add)
```

```json
{
  "name": "skein_1024_process_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586026832,
      "name": "skein_1024_process_block",
      "external": true,
      "loc": "drivers/staging/skein/skein_block.c:624",
      "file": "drivers/staging/skein/skein_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/staging/skein/skein_base.c:skein_1024_init",
        "drivers/staging/skein/skein_base.c:skein_1024_update",
        "drivers/staging/skein/skein_base.c:skein_1024_update",
        "drivers/staging/skein/skein_base.c:skein_1024_final",
        "drivers/staging/skein/skein_base.c:skein_1024_final",
        "drivers/staging/skein/skein_base.c:skein_1024_final_pad",
        "drivers/staging/skein/skein_base.c:skein_1024_init_ext",
        "drivers/staging/skein/skein_base.c:skein_1024_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586026832,
      "name": "skein_1024_process_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2965
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
void skein_1024_process_block(struct skein_1024_ctx * ctx, const u8 * blk_ptr, size_t blk_cnt, size_t byte_cnt_add)
```

```json
{
  "name": "skein_1024_process_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586436960,
      "name": "skein_1024_process_block",
      "external": true,
      "loc": "drivers/staging/skein/skein_block.c:629",
      "file": "drivers/staging/skein/skein_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/staging/skein/skein_base.c:skein_1024_output",
        "drivers/staging/skein/skein_base.c:skein_1024_final_pad",
        "drivers/staging/skein/skein_base.c:skein_1024_final",
        "drivers/staging/skein/skein_base.c:skein_1024_final",
        "drivers/staging/skein/skein_base.c:skein_1024_update",
        "drivers/staging/skein/skein_base.c:skein_1024_update",
        "drivers/staging/skein/skein_base.c:skein_1024_init_ext",
        "drivers/staging/skein/skein_base.c:skein_1024_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586436960,
      "name": "skein_1024_process_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2813
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
void skein_1024_process_block(struct skein_1024_ctx * ctx, const u8 * blk_ptr, size_t blk_cnt, size_t byte_cnt_add)
```

```json
{
  "name": "skein_1024_process_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586646416,
      "name": "skein_1024_process_block",
      "external": true,
      "loc": "drivers/staging/skein/skein_block.c:629",
      "file": "drivers/staging/skein/skein_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/staging/skein/skein_base.c:skein_1024_output",
        "drivers/staging/skein/skein_base.c:skein_1024_final_pad",
        "drivers/staging/skein/skein_base.c:skein_1024_final",
        "drivers/staging/skein/skein_base.c:skein_1024_final",
        "drivers/staging/skein/skein_base.c:skein_1024_update",
        "drivers/staging/skein/skein_base.c:skein_1024_update",
        "drivers/staging/skein/skein_base.c:skein_1024_init_ext",
        "drivers/staging/skein/skein_base.c:skein_1024_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586646416,
      "name": "skein_1024_process_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2813
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
void skein_1024_process_block(struct skein_1024_ctx * ctx, const u8 * blk_ptr, size_t blk_cnt, size_t byte_cnt_add)
```

```json
{
  "name": "skein_1024_process_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586770000,
      "name": "skein_1024_process_block",
      "external": true,
      "loc": "drivers/staging/skein/skein_block.c:631",
      "file": "drivers/staging/skein/skein_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/staging/skein/skein_base.c:skein_1024_output",
        "drivers/staging/skein/skein_base.c:skein_1024_final_pad",
        "drivers/staging/skein/skein_base.c:skein_1024_final",
        "drivers/staging/skein/skein_base.c:skein_1024_final",
        "drivers/staging/skein/skein_base.c:skein_1024_update",
        "drivers/staging/skein/skein_base.c:skein_1024_update",
        "drivers/staging/skein/skein_base.c:skein_1024_init_ext",
        "drivers/staging/skein/skein_base.c:skein_1024_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586770000,
      "name": "skein_1024_process_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2843
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
void skein_1024_process_block(struct skein_1024_ctx * ctx, const u8 * blk_ptr, size_t blk_cnt, size_t byte_cnt_add)
```

```json
{
  "name": "skein_1024_process_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587254992,
      "name": "skein_1024_process_block",
      "external": true,
      "loc": "drivers/staging/skein/skein_block.c:308",
      "file": "drivers/staging/skein/skein_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/staging/skein/skein_base.c:skein_1024_output",
        "drivers/staging/skein/skein_base.c:skein_1024_final_pad",
        "drivers/staging/skein/skein_base.c:skein_1024_final",
        "drivers/staging/skein/skein_base.c:skein_1024_final",
        "drivers/staging/skein/skein_base.c:skein_1024_update",
        "drivers/staging/skein/skein_base.c:skein_1024_update",
        "drivers/staging/skein/skein_base.c:skein_1024_init_ext",
        "drivers/staging/skein/skein_base.c:skein_1024_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587254992,
      "name": "skein_1024_process_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2843
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
void skein_1024_process_block(struct skein_1024_ctx * ctx, const u8 * blk_ptr, size_t blk_cnt, size_t byte_cnt_add)
```

```json
{
  "name": "skein_1024_process_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587557552,
      "name": "skein_1024_process_block",
      "external": true,
      "loc": "drivers/staging/skein/skein_block.c:308",
      "file": "drivers/staging/skein/skein_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/staging/skein/skein_base.c:skein_1024_output",
        "drivers/staging/skein/skein_base.c:skein_1024_final_pad",
        "drivers/staging/skein/skein_base.c:skein_1024_final",
        "drivers/staging/skein/skein_base.c:skein_1024_final",
        "drivers/staging/skein/skein_base.c:skein_1024_update",
        "drivers/staging/skein/skein_base.c:skein_1024_update",
        "drivers/staging/skein/skein_base.c:skein_1024_init_ext",
        "drivers/staging/skein/skein_base.c:skein_1024_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587557552,
      "name": "skein_1024_process_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2951
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void skein_1024_process_block(struct skein_1024_ctx * ctx, const u8 * blk_ptr, size_t blk_cnt, size_t byte_cnt_add)
```
</details>
</li>
</ul>
