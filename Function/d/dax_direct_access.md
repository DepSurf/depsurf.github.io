# Function: <code>dax_direct_access</code>

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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, void * * kaddr, pfn_t * pfn)
```

```json
{
  "name": "dax_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585385232,
      "name": "dax_direct_access",
      "external": true,
      "loc": "drivers/dax/super.c:220",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:__dax_zero_page_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585385232,
      "name": "dax_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, void * * kaddr, pfn_t * pfn)
```

```json
{
  "name": "dax_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585814432,
      "name": "dax_direct_access",
      "external": true,
      "loc": "drivers/dax/super.c:244",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:__dax_zero_page_range",
        "fs/dax.c:dax_iomap_pfn",
        "fs/dax.c:dax_writeback_mapping_range",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585814432,
      "name": "dax_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, void * * kaddr, pfn_t * pfn)
```

```json
{
  "name": "dax_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586060416,
      "name": "dax_direct_access",
      "external": true,
      "loc": "drivers/dax/super.c:266",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586060416,
      "name": "dax_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, void * * kaddr, pfn_t * pfn)
```

```json
{
  "name": "dax_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586204832,
      "name": "dax_direct_access",
      "external": true,
      "loc": "drivers/dax/super.c:265",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586204832,
      "name": "dax_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, void * * kaddr, pfn_t * pfn)
```

```json
{
  "name": "dax_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586441904,
      "name": "dax_direct_access",
      "external": true,
      "loc": "drivers/dax/super.c:296",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586441904,
      "name": "dax_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, void * * kaddr, pfn_t * pfn)
```

```json
{
  "name": "dax_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586589840,
      "name": "dax_direct_access",
      "external": true,
      "loc": "drivers/dax/super.c:296",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586589840,
      "name": "dax_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, void * * kaddr, pfn_t * pfn)
```

```json
{
  "name": "dax_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587378823,
      "name": "dax_direct_access",
      "external": true,
      "loc": "drivers/dax/super.c:296",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587375680,
      "name": "dax_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, void * * kaddr, pfn_t * pfn)
```

```json
{
  "name": "dax_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587439516,
      "name": "dax_direct_access",
      "external": true,
      "loc": "drivers/dax/super.c:304",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587436368,
      "name": "dax_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, void * * kaddr, pfn_t * pfn)
```

```json
{
  "name": "dax_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587320204,
      "name": "dax_direct_access",
      "external": true,
      "loc": "drivers/dax/super.c:304",
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
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587318144,
      "name": "dax_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, void * * kaddr, pfn_t * pfn)
```

```json
{
  "name": "dax_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587887532,
      "name": "dax_direct_access",
      "external": true,
      "loc": "drivers/dax/super.c:309",
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
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587885376,
      "name": "dax_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, enum dax_access_mode mode, void * * kaddr, pfn_t * pfn)
```

```json
{
  "name": "dax_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589235776,
      "name": "dax_direct_access",
      "external": true,
      "loc": "drivers/dax/super.c:127",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_fault_cow_page",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_zero_range",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589235776,
      "name": "dax_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, enum dax_access_mode mode, void * * kaddr, pfn_t * pfn)
```

```json
{
  "name": "dax_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590794352,
      "name": "dax_direct_access",
      "external": true,
      "loc": "drivers/dax/super.c:149",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_fault_cow_page",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_zero_range",
        "fs/dax.c:dax_iomap_direct_access",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590794352,
      "name": "dax_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, enum dax_access_mode mode, void * * kaddr, pfn_t * pfn)
```

```json
{
  "name": "dax_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591135856,
      "name": "dax_direct_access",
      "external": true,
      "loc": "drivers/dax/super.c:149",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_fault_cow_page",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_memzero",
        "fs/dax.c:dax_iomap_direct_access",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591135856,
      "name": "dax_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, enum dax_access_mode mode, void * * kaddr, pfn_t * pfn)
```

```json
{
  "name": "dax_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591481552,
      "name": "dax_direct_access",
      "external": true,
      "loc": "drivers/dax/super.c:149",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_fault_cow_page",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_memzero",
        "fs/dax.c:dax_iomap_direct_access",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591481552,
      "name": "dax_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, void * * kaddr, pfn_t * pfn)
```

```json
{
  "name": "dax_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499472728,
      "name": "dax_direct_access",
      "external": true,
      "loc": "drivers/dax/super.c:296",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499472728,
      "name": "dax_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, void * * kaddr, pfn_t * pfn)
```

```json
{
  "name": "dax_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231946836,
      "name": "dax_direct_access",
      "external": true,
      "loc": "drivers/dax/super.c:296",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231946836,
      "name": "dax_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, void * * kaddr, pfn_t * pfn)
```

```json
{
  "name": "dax_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292750320,
      "name": "dax_direct_access",
      "external": true,
      "loc": "drivers/dax/super.c:296",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292750320,
      "name": "dax_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, void * * kaddr, pfn_t * pfn)
```

```json
{
  "name": "dax_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276692808,
      "name": "dax_direct_access",
      "external": true,
      "loc": "drivers/dax/super.c:296",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276692808,
      "name": "dax_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, void * * kaddr, pfn_t * pfn)
```

```json
{
  "name": "dax_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586280320,
      "name": "dax_direct_access",
      "external": true,
      "loc": "drivers/dax/super.c:296",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586280320,
      "name": "dax_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, void * * kaddr, pfn_t * pfn)
```

```json
{
  "name": "dax_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586117808,
      "name": "dax_direct_access",
      "external": true,
      "loc": "drivers/dax/super.c:296",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586117808,
      "name": "dax_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, void * * kaddr, pfn_t * pfn)
```

```json
{
  "name": "dax_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586537808,
      "name": "dax_direct_access",
      "external": true,
      "loc": "drivers/dax/super.c:296",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586537808,
      "name": "dax_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, void * * kaddr, pfn_t * pfn)
```

```json
{
  "name": "dax_direct_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586649536,
      "name": "dax_direct_access",
      "external": true,
      "loc": "drivers/dax/super.c:296",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-linear.c:linear_dax_direct_access",
        "drivers/md/dm-stripe.c:stripe_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586649536,
      "name": "dax_direct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
long int dax_direct_access(struct dax_device * dax_dev, long unsigned int pgoff, long int nr_pages, void * * kaddr, pfn_t * pfn)
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
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum dax_access_mode mode</code>
</li>
<li>
<b>Param reordered. </b>
<code>dax_dev, pgoff, nr_pages, kaddr, pfn</code> ➡️ <code>dax_dev, pgoff, nr_pages, mode, kaddr, pfn</code>
</li>
</ul>
</details>
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
