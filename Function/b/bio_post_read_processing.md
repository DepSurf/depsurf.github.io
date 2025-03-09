# Function: <code>bio_post_read_processing</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_post_read_processing(struct bio_post_read_ctx * ctx)
```

```json
{
  "name": "bio_post_read_processing",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582827232,
      "name": "bio_post_read_processing",
      "external": false,
      "loc": "fs/ext4/readpage.c:128",
      "file": "fs/ext4/readpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:decrypt_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582827232,
      "name": "bio_post_read_processing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void bio_post_read_processing(struct bio_post_read_ctx * ctx)
```

```json
{
  "name": "bio_post_read_processing",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583139063,
      "name": "bio_post_read_processing",
      "external": false,
      "loc": "fs/ext4/readpage.c:128",
      "file": "fs/ext4/readpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:decrypt_work"
      ],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583138752,
      "name": "bio_post_read_processing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void bio_post_read_processing(struct bio_post_read_ctx * ctx)
```

```json
{
  "name": "bio_post_read_processing",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583219799,
      "name": "bio_post_read_processing",
      "external": false,
      "loc": "fs/ext4/readpage.c:128",
      "file": "fs/ext4/readpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:decrypt_work"
      ],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583219488,
      "name": "bio_post_read_processing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void bio_post_read_processing(struct bio_post_read_ctx * ctx)
```

```json
{
  "name": "bio_post_read_processing",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583247639,
      "name": "bio_post_read_processing",
      "external": false,
      "loc": "fs/ext4/readpage.c:128",
      "file": "fs/ext4/readpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:decrypt_work"
      ],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583247328,
      "name": "bio_post_read_processing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void bio_post_read_processing(struct bio_post_read_ctx * ctx)
```

```json
{
  "name": "bio_post_read_processing",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583589927,
      "name": "bio_post_read_processing",
      "external": false,
      "loc": "fs/ext4/readpage.c:128",
      "file": "fs/ext4/readpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:decrypt_work"
      ],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583589296,
      "name": "bio_post_read_processing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void bio_post_read_processing(struct bio_post_read_ctx * ctx)
```

```json
{
  "name": "bio_post_read_processing",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584128662,
      "name": "bio_post_read_processing",
      "external": false,
      "loc": "fs/ext4/readpage.c:127",
      "file": "fs/ext4/readpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:decrypt_work"
      ],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584128304,
      "name": "bio_post_read_processing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void bio_post_read_processing(struct bio_post_read_ctx * ctx)
```

```json
{
  "name": "bio_post_read_processing",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584762128,
      "name": "bio_post_read_processing",
      "external": false,
      "loc": "fs/ext4/readpage.c:125",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:decrypt_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584762128,
      "name": "bio_post_read_processing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void bio_post_read_processing(struct bio_post_read_ctx * ctx)
```

```json
{
  "name": "bio_post_read_processing",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584985824,
      "name": "bio_post_read_processing",
      "external": false,
      "loc": "fs/ext4/readpage.c:123",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:decrypt_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584985824,
      "name": "bio_post_read_processing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void bio_post_read_processing(struct bio_post_read_ctx * ctx)
```

```json
{
  "name": "bio_post_read_processing",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585217456,
      "name": "bio_post_read_processing",
      "external": false,
      "loc": "fs/ext4/readpage.c:116",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:decrypt_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585217456,
      "name": "bio_post_read_processing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void bio_post_read_processing(struct bio_post_read_ctx * ctx)
```

```json
{
  "name": "bio_post_read_processing",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494499688,
      "name": "bio_post_read_processing",
      "external": false,
      "loc": "fs/ext4/readpage.c:128",
      "file": "fs/ext4/readpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:decrypt_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494499688,
      "name": "bio_post_read_processing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void bio_post_read_processing(struct bio_post_read_ctx * ctx)
```

```json
{
  "name": "bio_post_read_processing",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227935556,
      "name": "bio_post_read_processing",
      "external": false,
      "loc": "fs/ext4/readpage.c:128",
      "file": "fs/ext4/readpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:decrypt_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227935556,
      "name": "bio_post_read_processing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void bio_post_read_processing(struct bio_post_read_ctx * ctx)
```

```json
{
  "name": "bio_post_read_processing",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288264528,
      "name": "bio_post_read_processing",
      "external": false,
      "loc": "fs/ext4/readpage.c:128",
      "file": "fs/ext4/readpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:decrypt_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288264528,
      "name": "bio_post_read_processing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void bio_post_read_processing(struct bio_post_read_ctx * ctx)
```

```json
{
  "name": "bio_post_read_processing",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273897818,
      "name": "bio_post_read_processing",
      "external": false,
      "loc": "fs/ext4/readpage.c:128",
      "file": "fs/ext4/readpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:decrypt_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273897818,
      "name": "bio_post_read_processing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void bio_post_read_processing(struct bio_post_read_ctx * ctx)
```

```json
{
  "name": "bio_post_read_processing",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582795968,
      "name": "bio_post_read_processing",
      "external": false,
      "loc": "fs/ext4/readpage.c:128",
      "file": "fs/ext4/readpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:decrypt_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582795968,
      "name": "bio_post_read_processing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void bio_post_read_processing(struct bio_post_read_ctx * ctx)
```

```json
{
  "name": "bio_post_read_processing",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582733120,
      "name": "bio_post_read_processing",
      "external": false,
      "loc": "fs/ext4/readpage.c:128",
      "file": "fs/ext4/readpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:decrypt_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582733120,
      "name": "bio_post_read_processing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void bio_post_read_processing(struct bio_post_read_ctx * ctx)
```

```json
{
  "name": "bio_post_read_processing",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582784848,
      "name": "bio_post_read_processing",
      "external": false,
      "loc": "fs/ext4/readpage.c:128",
      "file": "fs/ext4/readpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:decrypt_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582784848,
      "name": "bio_post_read_processing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void bio_post_read_processing(struct bio_post_read_ctx * ctx)
```

```json
{
  "name": "bio_post_read_processing",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582871248,
      "name": "bio_post_read_processing",
      "external": false,
      "loc": "fs/ext4/readpage.c:128",
      "file": "fs/ext4/readpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/readpage.c:decrypt_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582871248,
      "name": "bio_post_read_processing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void bio_post_read_processing(struct bio_post_read_ctx * ctx)
```
</details>
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
