# Function: <code>drop_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int drop_buffers(struct page * page, struct buffer_head * * buffers_to_free)
```

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581215856,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:3186",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581215856,
      "name": "drop_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
int drop_buffers(struct page * page, struct buffer_head * * buffers_to_free)
```

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581386736,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:3245",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386736,
      "name": "drop_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
int drop_buffers(struct page * page, struct buffer_head * * buffers_to_free)
```

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581464656,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:3286",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581464656,
      "name": "drop_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
int drop_buffers(struct page * page, struct buffer_head * * buffers_to_free)
```

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581519984,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:3273",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581519984,
      "name": "drop_buffers",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int drop_buffers(struct page * page, struct buffer_head * * buffers_to_free)
```

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581661280,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:3241",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581661280,
      "name": "drop_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
int drop_buffers(struct page * page, struct buffer_head * * buffers_to_free)
```

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581824736,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:3212",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581824736,
      "name": "drop_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int drop_buffers(struct page * page, struct buffer_head * * buffers_to_free)
```

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581911872,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:3224",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581911872,
      "name": "drop_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int drop_buffers(struct page * page, struct buffer_head * * buffers_to_free)
```

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582049008,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:3231",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582049008,
      "name": "drop_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
int drop_buffers(struct page * page, struct buffer_head * * buffers_to_free)
```

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582126864,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:3208",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582126864,
      "name": "drop_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
int drop_buffers(struct page * page, struct buffer_head * * buffers_to_free)
```

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582366272,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:3218",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582366272,
      "name": "drop_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int drop_buffers(struct page * page, struct buffer_head * * buffers_to_free)
```

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582425072,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:3199",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582425072,
      "name": "drop_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582452736,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:3220",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582452736,
      "name": "drop_buffers.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582775376,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:3199",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582775376,
      "name": "drop_buffers.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583315920,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:3184",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583315920,
      "name": "drop_buffers.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583899680,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:2789",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583899680,
      "name": "drop_buffers.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584127536,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:2927",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584127536,
      "name": "drop_buffers.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584344160,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:2887",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584344160,
      "name": "drop_buffers.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int drop_buffers(struct page * page, struct buffer_head * * buffers_to_free)
```

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493663840,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:3208",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493663840,
      "name": "drop_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int drop_buffers(struct page * page, struct buffer_head * * buffers_to_free)
```

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227201736,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:3208",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227201736,
      "name": "drop_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int drop_buffers(struct page * page, struct buffer_head * * buffers_to_free)
```

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287269504,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:3208",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287269504,
      "name": "drop_buffers",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int drop_buffers(struct page * page, struct buffer_head * * buffers_to_free)
```

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273294116,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:3208",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273294116,
      "name": "drop_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int drop_buffers(struct page * page, struct buffer_head * * buffers_to_free)
```

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582095600,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:3208",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582095600,
      "name": "drop_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
int drop_buffers(struct page * page, struct buffer_head * * buffers_to_free)
```

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582033072,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:3208",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582033072,
      "name": "drop_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
int drop_buffers(struct page * page, struct buffer_head * * buffers_to_free)
```

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582086080,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:3208",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582086080,
      "name": "drop_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
int drop_buffers(struct page * page, struct buffer_head * * buffers_to_free)
```

```json
{
  "name": "drop_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582158768,
      "name": "drop_buffers",
      "external": false,
      "loc": "fs/buffer.c:3208",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582158768,
      "name": "drop_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int drop_buffers(struct page * page, struct buffer_head * * buffers_to_free)
```
</details>
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
