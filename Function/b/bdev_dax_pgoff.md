# Function: <code>bdev_dax_pgoff</code>

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
int bdev_dax_pgoff(struct block_device * bdev, sector_t sector, size_t size, long unsigned int * pgoff)
```

```json
{
  "name": "bdev_dax_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585386185,
      "name": "bdev_dax_pgoff",
      "external": true,
      "loc": "drivers/dax/super.c:49",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:__dax_zero_page_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "drivers/md/dm-linear.c:linear_dax_flush",
        "drivers/md/dm-linear.c:linear_dax_copy_from_iter",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_flush",
        "drivers/md/dm-stripe.c:stripe_dax_copy_from_iter",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585384832,
      "name": "bdev_dax_pgoff",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bdev_dax_pgoff(struct block_device * bdev, sector_t sector, size_t size, long unsigned int * pgoff)
```

```json
{
  "name": "bdev_dax_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585815507,
      "name": "bdev_dax_pgoff",
      "external": true,
      "loc": "drivers/dax/super.c:52",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:__dax_zero_page_range",
        "fs/dax.c:dax_iomap_pfn",
        "fs/dax.c:dax_writeback_mapping_range",
        "drivers/md/dm-linear.c:linear_dax_copy_from_iter",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_copy_from_iter",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585814032,
      "name": "bdev_dax_pgoff",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bdev_dax_pgoff(struct block_device * bdev, sector_t sector, size_t size, long unsigned int * pgoff)
```

```json
{
  "name": "bdev_dax_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586060352,
      "name": "bdev_dax_pgoff",
      "external": true,
      "loc": "drivers/dax/super.c:52",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-linear.c:linear_dax_copy_from_iter",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_from_iter",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586060352,
      "name": "bdev_dax_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bdev_dax_pgoff(struct block_device * bdev, sector_t sector, size_t size, long unsigned int * pgoff)
```

```json
{
  "name": "bdev_dax_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586204768,
      "name": "bdev_dax_pgoff",
      "external": true,
      "loc": "drivers/dax/super.c:52",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-linear.c:linear_dax_copy_from_iter",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_from_iter",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586204768,
      "name": "bdev_dax_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bdev_dax_pgoff(struct block_device * bdev, sector_t sector, size_t size, long unsigned int * pgoff)
```

```json
{
  "name": "bdev_dax_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586441840,
      "name": "bdev_dax_pgoff",
      "external": true,
      "loc": "drivers/dax/super.c:46",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-linear.c:linear_dax_copy_from_iter",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_from_iter",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586441840,
      "name": "bdev_dax_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bdev_dax_pgoff(struct block_device * bdev, sector_t sector, size_t size, long unsigned int * pgoff)
```

```json
{
  "name": "bdev_dax_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586589776,
      "name": "bdev_dax_pgoff",
      "external": true,
      "loc": "drivers/dax/super.c:46",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-linear.c:linear_dax_copy_from_iter",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_from_iter",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586589776,
      "name": "bdev_dax_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bdev_dax_pgoff(struct block_device * bdev, sector_t sector, size_t size, long unsigned int * pgoff)
```

```json
{
  "name": "bdev_dax_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587378733,
      "name": "bdev_dax_pgoff",
      "external": true,
      "loc": "drivers/dax/super.c:46",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_zero_page_range",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-linear.c:linear_dax_copy_from_iter",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_zero_page_range",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_from_iter",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587375616,
      "name": "bdev_dax_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bdev_dax_pgoff(struct block_device * bdev, sector_t sector, size_t size, long unsigned int * pgoff)
```

```json
{
  "name": "bdev_dax_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587439424,
      "name": "bdev_dax_pgoff",
      "external": true,
      "loc": "drivers/dax/super.c:46",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_zero_page_range",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-linear.c:linear_dax_copy_from_iter",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_zero_page_range",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_from_iter",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587436304,
      "name": "bdev_dax_pgoff",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bdev_dax_pgoff(struct block_device * bdev, sector_t sector, size_t size, long unsigned int * pgoff)
```

```json
{
  "name": "bdev_dax_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587320112,
      "name": "bdev_dax_pgoff",
      "external": true,
      "loc": "drivers/dax/super.c:46",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_zero_page_range",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-linear.c:linear_dax_copy_from_iter",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_zero_page_range",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_from_iter",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587318080,
      "name": "bdev_dax_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int bdev_dax_pgoff(struct block_device * bdev, sector_t sector, size_t size, long unsigned int * pgoff)
```

```json
{
  "name": "bdev_dax_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587887440,
      "name": "bdev_dax_pgoff",
      "external": true,
      "loc": "drivers/dax/super.c:100",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:generic_fsdax_supported",
        "drivers/dax/super.c:generic_fsdax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_fault_cow_page",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_iomap_zero",
        "drivers/md/dm-linear.c:linear_dax_zero_page_range",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-linear.c:linear_dax_copy_from_iter",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_zero_page_range",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_from_iter",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587885312,
      "name": "bdev_dax_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int bdev_dax_pgoff(struct block_device * bdev, sector_t sector, size_t size, long unsigned int * pgoff)
```

```json
{
  "name": "bdev_dax_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499472624,
      "name": "bdev_dax_pgoff",
      "external": true,
      "loc": "drivers/dax/super.c:46",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-linear.c:linear_dax_copy_from_iter",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_from_iter",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499472624,
      "name": "bdev_dax_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int bdev_dax_pgoff(struct block_device * bdev, sector_t sector, size_t size, long unsigned int * pgoff)
```

```json
{
  "name": "bdev_dax_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231946756,
      "name": "bdev_dax_pgoff",
      "external": true,
      "loc": "drivers/dax/super.c:46",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231946756,
      "name": "bdev_dax_pgoff",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int bdev_dax_pgoff(struct block_device * bdev, sector_t sector, size_t size, long unsigned int * pgoff)
```

```json
{
  "name": "bdev_dax_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292750240,
      "name": "bdev_dax_pgoff",
      "external": true,
      "loc": "drivers/dax/super.c:46",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-linear.c:linear_dax_copy_from_iter",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_from_iter",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292750240,
      "name": "bdev_dax_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int bdev_dax_pgoff(struct block_device * bdev, sector_t sector, size_t size, long unsigned int * pgoff)
```

```json
{
  "name": "bdev_dax_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276692722,
      "name": "bdev_dax_pgoff",
      "external": true,
      "loc": "drivers/dax/super.c:46",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-linear.c:linear_dax_copy_from_iter",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_from_iter",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276692722,
      "name": "bdev_dax_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int bdev_dax_pgoff(struct block_device * bdev, sector_t sector, size_t size, long unsigned int * pgoff)
```

```json
{
  "name": "bdev_dax_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586280256,
      "name": "bdev_dax_pgoff",
      "external": true,
      "loc": "drivers/dax/super.c:46",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-linear.c:linear_dax_copy_from_iter",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_from_iter",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586280256,
      "name": "bdev_dax_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bdev_dax_pgoff(struct block_device * bdev, sector_t sector, size_t size, long unsigned int * pgoff)
```

```json
{
  "name": "bdev_dax_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586117744,
      "name": "bdev_dax_pgoff",
      "external": true,
      "loc": "drivers/dax/super.c:46",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-linear.c:linear_dax_copy_from_iter",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_from_iter",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586117744,
      "name": "bdev_dax_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bdev_dax_pgoff(struct block_device * bdev, sector_t sector, size_t size, long unsigned int * pgoff)
```

```json
{
  "name": "bdev_dax_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586537744,
      "name": "bdev_dax_pgoff",
      "external": true,
      "loc": "drivers/dax/super.c:46",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-linear.c:linear_dax_copy_from_iter",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_from_iter",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586537744,
      "name": "bdev_dax_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bdev_dax_pgoff(struct block_device * bdev, sector_t sector, size_t size, long unsigned int * pgoff)
```

```json
{
  "name": "bdev_dax_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586649472,
      "name": "bdev_dax_pgoff",
      "external": true,
      "loc": "drivers/dax/super.c:46",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-linear.c:linear_dax_copy_from_iter",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_from_iter",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586649472,
      "name": "bdev_dax_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bdev_dax_pgoff(struct block_device * bdev, sector_t sector, size_t size, long unsigned int * pgoff)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int bdev_dax_pgoff(struct block_device * bdev, sector_t sector, size_t size, long unsigned int * pgoff)
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
