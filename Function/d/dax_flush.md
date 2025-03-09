# Function: <code>dax_flush</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dax_flush(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t size)
```

```json
{
  "name": "dax_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585387280,
      "name": "dax_flush",
      "external": true,
      "loc": "drivers/dax/super.c:258",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:__dax_zero_page_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "drivers/md/dm-linear.c:linear_dax_flush",
        "drivers/md/dm-stripe.c:stripe_dax_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585387280,
      "name": "dax_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void dax_flush(struct dax_device * dax_dev, void * addr, size_t size)
```

```json
{
  "name": "dax_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585814592,
      "name": "dax_flush",
      "external": true,
      "loc": "drivers/dax/super.c:284",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:__dax_zero_page_range",
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585814592,
      "name": "dax_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void dax_flush(struct dax_device * dax_dev, void * addr, size_t size)
```

```json
{
  "name": "dax_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586060784,
      "name": "dax_flush",
      "external": true,
      "loc": "drivers/dax/super.c:310",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586060784,
      "name": "dax_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void dax_flush(struct dax_device * dax_dev, void * addr, size_t size)
```

```json
{
  "name": "dax_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586205200,
      "name": "dax_flush",
      "external": true,
      "loc": "drivers/dax/super.c:309",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586205200,
      "name": "dax_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void dax_flush(struct dax_device * dax_dev, void * addr, size_t size)
```

```json
{
  "name": "dax_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586442352,
      "name": "dax_flush",
      "external": true,
      "loc": "drivers/dax/super.c:349",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586442352,
      "name": "dax_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void dax_flush(struct dax_device * dax_dev, void * addr, size_t size)
```

```json
{
  "name": "dax_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586590288,
      "name": "dax_flush",
      "external": true,
      "loc": "drivers/dax/super.c:349",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586590288,
      "name": "dax_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void dax_flush(struct dax_device * dax_dev, void * addr, size_t size)
```

```json
{
  "name": "dax_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587376144,
      "name": "dax_flush",
      "external": true,
      "loc": "drivers/dax/super.c:370",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_writeback_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587376144,
      "name": "dax_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void dax_flush(struct dax_device * dax_dev, void * addr, size_t size)
```

```json
{
  "name": "dax_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587436832,
      "name": "dax_flush",
      "external": true,
      "loc": "drivers/dax/super.c:378",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_writeback_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587436832,
      "name": "dax_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void dax_flush(struct dax_device * dax_dev, void * addr, size_t size)
```

```json
{
  "name": "dax_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587318608,
      "name": "dax_flush",
      "external": true,
      "loc": "drivers/dax/super.c:378",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_writeback_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587318608,
      "name": "dax_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void dax_flush(struct dax_device * dax_dev, void * addr, size_t size)
```

```json
{
  "name": "dax_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587885840,
      "name": "dax_flush",
      "external": true,
      "loc": "drivers/dax/super.c:370",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_writeback_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587885840,
      "name": "dax_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void dax_flush(struct dax_device * dax_dev, void * addr, size_t size)
```

```json
{
  "name": "dax_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589236656,
      "name": "dax_flush",
      "external": true,
      "loc": "drivers/dax/super.c:209",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_zero_range",
        "fs/dax.c:dax_writeback_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589236656,
      "name": "dax_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void dax_flush(struct dax_device * dax_dev, void * addr, size_t size)
```

```json
{
  "name": "dax_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590794704,
      "name": "dax_flush",
      "external": true,
      "loc": "drivers/dax/super.c:254",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_zero_range",
        "fs/dax.c:dax_iomap_copy_around",
        "fs/dax.c:dax_iomap_copy_around",
        "fs/dax.c:dax_writeback_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590794704,
      "name": "dax_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void dax_flush(struct dax_device * dax_dev, void * addr, size_t size)
```

```json
{
  "name": "dax_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591136240,
      "name": "dax_flush",
      "external": true,
      "loc": "drivers/dax/super.c:257",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_memzero",
        "fs/dax.c:dax_unshare_iter",
        "fs/dax.c:dax_iomap_copy_around",
        "fs/dax.c:dax_iomap_copy_around",
        "fs/dax.c:dax_writeback_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591136240,
      "name": "dax_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void dax_flush(struct dax_device * dax_dev, void * addr, size_t size)
```

```json
{
  "name": "dax_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591481936,
      "name": "dax_flush",
      "external": true,
      "loc": "drivers/dax/super.c:257",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_memzero",
        "fs/dax.c:dax_unshare_iter",
        "fs/dax.c:dax_iomap_copy_around",
        "fs/dax.c:dax_iomap_copy_around",
        "fs/dax.c:dax_writeback_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591481936,
      "name": "dax_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void dax_flush(struct dax_device * dax_dev, void * addr, size_t size)
```

```json
{
  "name": "dax_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499473336,
      "name": "dax_flush",
      "external": true,
      "loc": "drivers/dax/super.c:349",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499473336,
      "name": "dax_flush",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void dax_flush(struct dax_device * dax_dev, void * addr, size_t size)
```

```json
{
  "name": "dax_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231946964,
      "name": "dax_flush",
      "external": true,
      "loc": "drivers/dax/super.c:357",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231946964,
      "name": "dax_flush",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void dax_flush(struct dax_device * dax_dev, void * addr, size_t size)
```

```json
{
  "name": "dax_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292750928,
      "name": "dax_flush",
      "external": true,
      "loc": "drivers/dax/super.c:349",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292750928,
      "name": "dax_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void dax_flush(struct dax_device * dax_dev, void * addr, size_t size)
```

```json
{
  "name": "dax_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276692926,
      "name": "dax_flush",
      "external": true,
      "loc": "drivers/dax/super.c:357",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276692926,
      "name": "dax_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void dax_flush(struct dax_device * dax_dev, void * addr, size_t size)
```

```json
{
  "name": "dax_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586280768,
      "name": "dax_flush",
      "external": true,
      "loc": "drivers/dax/super.c:349",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586280768,
      "name": "dax_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void dax_flush(struct dax_device * dax_dev, void * addr, size_t size)
```

```json
{
  "name": "dax_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586118256,
      "name": "dax_flush",
      "external": true,
      "loc": "drivers/dax/super.c:349",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586118256,
      "name": "dax_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void dax_flush(struct dax_device * dax_dev, void * addr, size_t size)
```

```json
{
  "name": "dax_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586538256,
      "name": "dax_flush",
      "external": true,
      "loc": "drivers/dax/super.c:349",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586538256,
      "name": "dax_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void dax_flush(struct dax_device * dax_dev, void * addr, size_t size)
```

```json
{
  "name": "dax_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586649984,
      "name": "dax_flush",
      "external": true,
      "loc": "drivers/dax/super.c:349",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586649984,
      "name": "dax_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void dax_flush(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int pgoff</code>
</li>
<li>
<b>Param reordered. </b>
<code>dax_dev, pgoff, addr, size</code> ➡️ <code>dax_dev, addr, size</code>
</li>
</ul>
</details>
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
