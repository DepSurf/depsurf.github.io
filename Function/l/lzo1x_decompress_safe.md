# Function: <code>lzo1x_decompress_safe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583097136,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:38",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "crypto/lzo.c:lzo_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583097136,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1433
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583391344,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:38",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583391344,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1410
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583516720,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:38",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583516720,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1410
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583537904,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:38",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583537904,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1334
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583723152,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:38",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583723152,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1334
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583941440,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:38",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583941440,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1307
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584026032,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:38",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584026032,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1307
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584210080,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:39",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "crypto/lzo-rle.c:lzorle_sdecompress",
        "crypto/lzo-rle.c:lzorle_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584210080,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1691
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584344880,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:39",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "crypto/lzo-rle.c:lzorle_sdecompress",
        "crypto/lzo-rle.c:lzorle_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584344880,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1691
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584756096,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:39",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "crypto/lzo-rle.c:lzorle_sdecompress",
        "crypto/lzo-rle.c:lzorle_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584756096,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1691
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584869552,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:39",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "crypto/lzo-rle.c:lzorle_sdecompress",
        "crypto/lzo-rle.c:lzorle_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584869552,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1708
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584913696,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:39",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "crypto/lzo-rle.c:lzorle_sdecompress",
        "crypto/lzo-rle.c:lzorle_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584913696,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1698
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585349104,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:39",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "crypto/lzo-rle.c:lzorle_sdecompress",
        "crypto/lzo-rle.c:lzorle_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585349104,
      "name": "lzo1x_decompress_safe",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586208160,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:39",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "crypto/lzo-rle.c:lzorle_sdecompress",
        "crypto/lzo-rle.c:lzorle_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586208160,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1661
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587202656,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:39",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "crypto/lzo-rle.c:lzorle_sdecompress",
        "crypto/lzo-rle.c:lzorle_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587202656,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1661
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587465776,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:39",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "crypto/lzo-rle.c:lzorle_sdecompress",
        "crypto/lzo-rle.c:lzorle_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587465776,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1665
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587800560,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:39",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "crypto/lzo-rle.c:lzorle_sdecompress",
        "crypto/lzo-rle.c:lzorle_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587800560,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1665
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496230936,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:39",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "crypto/lzo-rle.c:lzorle_sdecompress",
        "crypto/lzo-rle.c:lzorle_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496230936,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1540
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229575492,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:39",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "crypto/lzo-rle.c:lzorle_sdecompress",
        "crypto/lzo-rle.c:lzorle_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229575492,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1512
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290524256,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:39",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "crypto/lzo-rle.c:lzorle_sdecompress",
        "crypto/lzo-rle.c:lzorle_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290524256,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1988
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275280750,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:39",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "crypto/lzo-rle.c:lzorle_sdecompress",
        "crypto/lzo-rle.c:lzorle_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275280750,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1016
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584313616,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:39",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "crypto/lzo-rle.c:lzorle_sdecompress",
        "crypto/lzo-rle.c:lzorle_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584313616,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1691
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584248816,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:39",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "crypto/lzo-rle.c:lzorle_sdecompress",
        "crypto/lzo-rle.c:lzorle_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584248816,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1691
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584296528,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:39",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "crypto/lzo-rle.c:lzorle_sdecompress",
        "crypto/lzo-rle.c:lzorle_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584296528,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1691
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
int lzo1x_decompress_safe(const unsigned char * in, size_t in_len, unsigned char * out, size_t * out_len)
```

```json
{
  "name": "lzo1x_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584402560,
      "name": "lzo1x_decompress_safe",
      "external": true,
      "loc": "lib/lzo/lzo1x_decompress_safe.c:39",
      "file": "lib/lzo/lzo1x_decompress_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress",
        "crypto/lzo.c:lzo_sdecompress",
        "crypto/lzo.c:lzo_decompress",
        "crypto/lzo-rle.c:lzorle_sdecompress",
        "crypto/lzo-rle.c:lzorle_decompress",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584402560,
      "name": "lzo1x_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1691
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
