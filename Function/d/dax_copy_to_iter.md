# Function: <code>dax_copy_to_iter</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t dax_copy_to_iter(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "dax_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586061328,
      "name": "dax_copy_to_iter",
      "external": true,
      "loc": "drivers/dax/super.c:298",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586061328,
      "name": "dax_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
size_t dax_copy_to_iter(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "dax_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586205744,
      "name": "dax_copy_to_iter",
      "external": true,
      "loc": "drivers/dax/super.c:297",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586205744,
      "name": "dax_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
size_t dax_copy_to_iter(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "dax_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586442816,
      "name": "dax_copy_to_iter",
      "external": true,
      "loc": "drivers/dax/super.c:337",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586442816,
      "name": "dax_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
size_t dax_copy_to_iter(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "dax_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586590752,
      "name": "dax_copy_to_iter",
      "external": true,
      "loc": "drivers/dax/super.c:337",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586590752,
      "name": "dax_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
size_t dax_copy_to_iter(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "dax_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587376608,
      "name": "dax_copy_to_iter",
      "external": true,
      "loc": "drivers/dax/super.c:341",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587376608,
      "name": "dax_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
size_t dax_copy_to_iter(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "dax_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587437296,
      "name": "dax_copy_to_iter",
      "external": true,
      "loc": "drivers/dax/super.c:349",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587437296,
      "name": "dax_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
size_t dax_copy_to_iter(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "dax_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587319072,
      "name": "dax_copy_to_iter",
      "external": true,
      "loc": "drivers/dax/super.c:349",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587319072,
      "name": "dax_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
size_t dax_copy_to_iter(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "dax_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587886256,
      "name": "dax_copy_to_iter",
      "external": true,
      "loc": "drivers/dax/super.c:341",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_iter",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587886256,
      "name": "dax_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
size_t dax_copy_to_iter(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "dax_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589238048,
      "name": "dax_copy_to_iter",
      "external": true,
      "loc": "drivers/dax/super.c:165",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589238048,
      "name": "dax_copy_to_iter",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
size_t dax_copy_to_iter(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "dax_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590796784,
      "name": "dax_copy_to_iter",
      "external": true,
      "loc": "drivers/dax/super.c:187",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590796784,
      "name": "dax_copy_to_iter",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
size_t dax_copy_to_iter(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "dax_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591138304,
      "name": "dax_copy_to_iter",
      "external": true,
      "loc": "drivers/dax/super.c:187",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591138304,
      "name": "dax_copy_to_iter",
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
size_t dax_copy_to_iter(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "dax_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591484000,
      "name": "dax_copy_to_iter",
      "external": true,
      "loc": "drivers/dax/super.c:187",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591484000,
      "name": "dax_copy_to_iter",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
size_t dax_copy_to_iter(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "dax_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499473944,
      "name": "dax_copy_to_iter",
      "external": true,
      "loc": "drivers/dax/super.c:337",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499473944,
      "name": "dax_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
size_t dax_copy_to_iter(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "dax_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231948396,
      "name": "dax_copy_to_iter",
      "external": true,
      "loc": "drivers/dax/super.c:337",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231948396,
      "name": "dax_copy_to_iter",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
size_t dax_copy_to_iter(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "dax_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292752448,
      "name": "dax_copy_to_iter",
      "external": true,
      "loc": "drivers/dax/super.c:337",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292752448,
      "name": "dax_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
size_t dax_copy_to_iter(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "dax_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276693918,
      "name": "dax_copy_to_iter",
      "external": true,
      "loc": "drivers/dax/super.c:337",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276693918,
      "name": "dax_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
size_t dax_copy_to_iter(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "dax_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586281232,
      "name": "dax_copy_to_iter",
      "external": true,
      "loc": "drivers/dax/super.c:337",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586281232,
      "name": "dax_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
size_t dax_copy_to_iter(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "dax_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586118720,
      "name": "dax_copy_to_iter",
      "external": true,
      "loc": "drivers/dax/super.c:337",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586118720,
      "name": "dax_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
size_t dax_copy_to_iter(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "dax_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586538720,
      "name": "dax_copy_to_iter",
      "external": true,
      "loc": "drivers/dax/super.c:337",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586538720,
      "name": "dax_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
size_t dax_copy_to_iter(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "dax_copy_to_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586650976,
      "name": "dax_copy_to_iter",
      "external": true,
      "loc": "drivers/dax/super.c:337",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "drivers/md/dm-linear.c:linear_dax_copy_to_iter",
        "drivers/md/dm-stripe.c:stripe_dax_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586650976,
      "name": "dax_copy_to_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
size_t dax_copy_to_iter(struct dax_device * dax_dev, long unsigned int pgoff, void * addr, size_t bytes, struct iov_iter * i)
```
</details>
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
