# Function: <code>LZ4_decompress_safe</code>

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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
```

```json
{
  "name": "LZ4_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583539296,
      "name": "LZ4_decompress_safe",
      "external": true,
      "loc": "lib/lz4/lz4_decompress.c:337",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress",
        "lib/decompress_unlz4.c:unlz4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583539296,
      "name": "LZ4_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1075
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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
```

```json
{
  "name": "LZ4_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583724544,
      "name": "LZ4_decompress_safe",
      "external": true,
      "loc": "lib/lz4/lz4_decompress.c:337",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress",
        "lib/decompress_unlz4.c:unlz4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583724544,
      "name": "LZ4_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 939
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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
```

```json
{
  "name": "LZ4_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583942800,
      "name": "LZ4_decompress_safe",
      "external": true,
      "loc": "lib/lz4/lz4_decompress.c:337",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress",
        "lib/decompress_unlz4.c:unlz4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583942800,
      "name": "LZ4_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 918
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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
```

```json
{
  "name": "LZ4_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584027392,
      "name": "LZ4_decompress_safe",
      "external": true,
      "loc": "lib/lz4/lz4_decompress.c:449",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/decompress_unlz4.c:unlz4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584027392,
      "name": "LZ4_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1095
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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
```

```json
{
  "name": "LZ4_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584211824,
      "name": "LZ4_decompress_safe",
      "external": true,
      "loc": "lib/lz4/lz4_decompress.c:449",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/decompress_unlz4.c:unlz4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584211824,
      "name": "LZ4_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1084
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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
```

```json
{
  "name": "LZ4_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584346624,
      "name": "LZ4_decompress_safe",
      "external": true,
      "loc": "lib/lz4/lz4_decompress.c:449",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/decompress_unlz4.c:unlz4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584346624,
      "name": "LZ4_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1084
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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
```

```json
{
  "name": "LZ4_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584778432,
      "name": "LZ4_decompress_safe",
      "external": true,
      "loc": "lib/lz4/lz4_decompress.c:452",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/decompress_unlz4.c:unlz4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584778432,
      "name": "LZ4_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1077
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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
```

```json
{
  "name": "LZ4_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584891840,
      "name": "LZ4_decompress_safe",
      "external": true,
      "loc": "lib/lz4/lz4_decompress.c:456",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/decompress_unlz4.c:unlz4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584891840,
      "name": "LZ4_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1083
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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
```

```json
{
  "name": "LZ4_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584915456,
      "name": "LZ4_decompress_safe",
      "external": true,
      "loc": "lib/lz4/lz4_decompress.c:456",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/decompress_unlz4.c:unlz4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584915456,
      "name": "LZ4_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1075
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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
```

```json
{
  "name": "LZ4_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585350848,
      "name": "LZ4_decompress_safe",
      "external": true,
      "loc": "lib/lz4/lz4_decompress.c:456",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/decompress_unlz4.c:unlz4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585350848,
      "name": "LZ4_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1138
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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
```

```json
{
  "name": "LZ4_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586209888,
      "name": "LZ4_decompress_safe",
      "external": true,
      "loc": "lib/lz4/lz4_decompress.c:460",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/decompress_unlz4.c:unlz4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586209888,
      "name": "LZ4_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1024
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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
```

```json
{
  "name": "LZ4_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587204416,
      "name": "LZ4_decompress_safe",
      "external": true,
      "loc": "lib/lz4/lz4_decompress.c:460",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/decompress_unlz4.c:unlz4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587204416,
      "name": "LZ4_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1024
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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
```

```json
{
  "name": "LZ4_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587467552,
      "name": "LZ4_decompress_safe",
      "external": true,
      "loc": "lib/lz4/lz4_decompress.c:460",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/decompress_unlz4.c:unlz4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587467552,
      "name": "LZ4_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1246
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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
```

```json
{
  "name": "LZ4_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587802336,
      "name": "LZ4_decompress_safe",
      "external": true,
      "loc": "lib/lz4/lz4_decompress.c:460",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/decompress_unlz4.c:unlz4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587802336,
      "name": "LZ4_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1246
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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
```

```json
{
  "name": "LZ4_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496232512,
      "name": "LZ4_decompress_safe",
      "external": true,
      "loc": "lib/lz4/lz4_decompress.c:449",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/decompress_unlz4.c:unlz4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496232512,
      "name": "LZ4_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1376
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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
```

```json
{
  "name": "LZ4_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229577052,
      "name": "LZ4_decompress_safe",
      "external": true,
      "loc": "lib/lz4/lz4_decompress.c:449",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/decompress_unlz4.c:unlz4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229577052,
      "name": "LZ4_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1380
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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
```

```json
{
  "name": "LZ4_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290526304,
      "name": "LZ4_decompress_safe",
      "external": true,
      "loc": "lib/lz4/lz4_decompress.c:449",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/decompress_unlz4.c:unlz4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290526304,
      "name": "LZ4_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1472
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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
```

```json
{
  "name": "LZ4_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275281794,
      "name": "LZ4_decompress_safe",
      "external": true,
      "loc": "lib/lz4/lz4_decompress.c:449",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/decompress_unlz4.c:unlz4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275281794,
      "name": "LZ4_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1704
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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
```

```json
{
  "name": "LZ4_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584315360,
      "name": "LZ4_decompress_safe",
      "external": true,
      "loc": "lib/lz4/lz4_decompress.c:449",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/decompress_unlz4.c:unlz4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584315360,
      "name": "LZ4_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1084
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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
```

```json
{
  "name": "LZ4_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584250560,
      "name": "LZ4_decompress_safe",
      "external": true,
      "loc": "lib/lz4/lz4_decompress.c:449",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/decompress_unlz4.c:unlz4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584250560,
      "name": "LZ4_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1084
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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
```

```json
{
  "name": "LZ4_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584298272,
      "name": "LZ4_decompress_safe",
      "external": true,
      "loc": "lib/lz4/lz4_decompress.c:449",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/decompress_unlz4.c:unlz4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584298272,
      "name": "LZ4_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1084
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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
```

```json
{
  "name": "LZ4_decompress_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584404304,
      "name": "LZ4_decompress_safe",
      "external": true,
      "loc": "lib/lz4/lz4_decompress.c:449",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict",
        "lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue",
        "lib/decompress_unlz4.c:unlz4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584404304,
      "name": "LZ4_decompress_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1084
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
int LZ4_decompress_safe(const char * source, char * dest, int compressedSize, int maxDecompressedSize)
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
