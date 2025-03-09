# Function: <code>__block_write_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581225232,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:1905",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:nobh_write_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581225232,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581397468,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2036",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581393616,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581475812,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2077",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581472000,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581530721,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2074",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581527376,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581673294,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2034",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581669664,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581837065,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2005",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581833280,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581924329,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2014",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581920560,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582061689,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2015",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582057792,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582139481,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2015",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582135584,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582377060,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2059",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582375808,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582433005,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2058",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582431904,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582459933,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2078",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582458832,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582783614,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2057",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582782480,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583335725,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2053",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583334592,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583920097,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2038",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583919216,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584142647,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2175",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584142048,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584358615,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2149",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584358048,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493684728,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2015",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493680744,
      "name": "__block_write_begin",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227217088,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2015",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227213000,
      "name": "__block_write_begin",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287288320,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2015",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287283024,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273307552,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2015",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273304396,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582108217,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2015",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582104320,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582045657,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2015",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582041760,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582098697,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2015",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582094800,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int __block_write_begin(struct page * page, loff_t pos, unsigned int len, get_block_t * get_block)
```

```json
{
  "name": "__block_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582171655,
      "name": "__block_write_begin",
      "external": true,
      "loc": "fs/buffer.c:2015",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582167616,
      "name": "__block_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
