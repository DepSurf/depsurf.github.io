# Function: <code>dax_zero_page_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int dax_zero_page_range(struct inode * inode, loff_t from, unsigned int length, get_block_t * get_block)
```

```json
{
  "name": "dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581330112,
      "name": "dax_zero_page_range",
      "external": true,
      "loc": "fs/dax.c:736",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_truncate_page",
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581330112,
      "name": "dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
int dax_zero_page_range(struct inode * inode, loff_t from, unsigned int length, get_block_t * get_block)
```

```json
{
  "name": "dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581493760,
      "name": "dax_zero_page_range",
      "external": true,
      "loc": "fs/dax.c:1204",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_truncate_page",
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581493760,
      "name": "dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
    }
  ]
}
```
</details>
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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int dax_zero_page_range(struct dax_device * dax_dev, long unsigned int pgoff, size_t nr_pages)
```

```json
{
  "name": "dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587375792,
      "name": "dax_zero_page_range",
      "external": true,
      "loc": "drivers/dax/super.c:351",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_zero",
        "drivers/md/dm-linear.c:linear_dax_zero_page_range",
        "drivers/md/dm-stripe.c:stripe_dax_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587375792,
      "name": "dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int dax_zero_page_range(struct dax_device * dax_dev, long unsigned int pgoff, size_t nr_pages)
```

```json
{
  "name": "dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587436480,
      "name": "dax_zero_page_range",
      "external": true,
      "loc": "drivers/dax/super.c:359",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_zero",
        "drivers/md/dm-linear.c:linear_dax_zero_page_range",
        "drivers/md/dm-stripe.c:stripe_dax_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587436480,
      "name": "dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int dax_zero_page_range(struct dax_device * dax_dev, long unsigned int pgoff, size_t nr_pages)
```

```json
{
  "name": "dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587318256,
      "name": "dax_zero_page_range",
      "external": true,
      "loc": "drivers/dax/super.c:359",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_zero",
        "drivers/md/dm-linear.c:linear_dax_zero_page_range",
        "drivers/md/dm-stripe.c:stripe_dax_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587318256,
      "name": "dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int dax_zero_page_range(struct dax_device * dax_dev, long unsigned int pgoff, size_t nr_pages)
```

```json
{
  "name": "dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587885488,
      "name": "dax_zero_page_range",
      "external": true,
      "loc": "drivers/dax/super.c:351",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_zero",
        "drivers/md/dm-linear.c:linear_dax_zero_page_range",
        "drivers/md/dm-stripe.c:stripe_dax_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587885488,
      "name": "dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int dax_zero_page_range(struct dax_device * dax_dev, long unsigned int pgoff, size_t nr_pages)
```

```json
{
  "name": "dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589235936,
      "name": "dax_zero_page_range",
      "external": true,
      "loc": "drivers/dax/super.c:181",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_zero_range",
        "drivers/md/dm-linear.c:linear_dax_zero_page_range",
        "drivers/md/dm-stripe.c:stripe_dax_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589235936,
      "name": "dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int dax_zero_page_range(struct dax_device * dax_dev, long unsigned int pgoff, size_t nr_pages)
```

```json
{
  "name": "dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590794528,
      "name": "dax_zero_page_range",
      "external": true,
      "loc": "drivers/dax/super.c:203",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_zero_range",
        "drivers/md/dm-linear.c:linear_dax_zero_page_range",
        "drivers/md/dm-stripe.c:stripe_dax_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590794528,
      "name": "dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int dax_zero_page_range(struct dax_device * dax_dev, long unsigned int pgoff, size_t nr_pages)
```

```json
{
  "name": "dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591136032,
      "name": "dax_zero_page_range",
      "external": true,
      "loc": "drivers/dax/super.c:203",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_zero_range",
        "drivers/md/dm-linear.c:linear_dax_zero_page_range",
        "drivers/md/dm-stripe.c:stripe_dax_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591136032,
      "name": "dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int dax_zero_page_range(struct dax_device * dax_dev, long unsigned int pgoff, size_t nr_pages)
```

```json
{
  "name": "dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591481728,
      "name": "dax_zero_page_range",
      "external": true,
      "loc": "drivers/dax/super.c:203",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_zero_range",
        "drivers/md/dm-linear.c:linear_dax_zero_page_range",
        "drivers/md/dm-stripe.c:stripe_dax_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591481728,
      "name": "dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
int dax_zero_page_range(struct inode * inode, loff_t from, unsigned int length, get_block_t * get_block)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int dax_zero_page_range(struct dax_device * dax_dev, long unsigned int pgoff, size_t nr_pages)
```
</details>
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
