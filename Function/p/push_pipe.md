# Function: <code>push_pipe</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
size_t push_pipe(struct iov_iter * i, size_t size, int * idxp, size_t * offp)
```

```json
{
  "name": "push_pipe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583430608,
      "name": "push_pipe",
      "external": false,
      "loc": "lib/iov_iter.c:468",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583430608,
      "name": "push_pipe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
size_t push_pipe(struct iov_iter * i, size_t size, int * idxp, size_t * offp)
```

```json
{
  "name": "push_pipe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583451840,
      "name": "push_pipe",
      "external": false,
      "loc": "lib/iov_iter.c:488",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583451840,
      "name": "push_pipe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
size_t push_pipe(struct iov_iter * i, size_t size, int * idxp, size_t * offp)
```

```json
{
  "name": "push_pipe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583631936,
      "name": "push_pipe",
      "external": false,
      "loc": "lib/iov_iter.c:488",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583631936,
      "name": "push_pipe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
size_t push_pipe(struct iov_iter * i, size_t size, int * idxp, size_t * offp)
```

```json
{
  "name": "push_pipe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583848432,
      "name": "push_pipe",
      "external": false,
      "loc": "lib/iov_iter.c:488",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_to_iter_mcsafe",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583848432,
      "name": "push_pipe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
size_t push_pipe(struct iov_iter * i, size_t size, int * idxp, size_t * offp)
```

```json
{
  "name": "push_pipe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583932304,
      "name": "push_pipe",
      "external": false,
      "loc": "lib/iov_iter.c:494",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_to_iter_mcsafe",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583932304,
      "name": "push_pipe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
size_t push_pipe(struct iov_iter * i, size_t size, int * idxp, size_t * offp)
```

```json
{
  "name": "push_pipe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584110496,
      "name": "push_pipe",
      "external": false,
      "loc": "lib/iov_iter.c:495",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_to_iter_mcsafe",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584110496,
      "name": "push_pipe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
size_t push_pipe(struct iov_iter * i, size_t size, int * idxp, size_t * offp)
```

```json
{
  "name": "push_pipe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584233296,
      "name": "push_pipe",
      "external": false,
      "loc": "lib/iov_iter.c:495",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_to_iter_mcsafe",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584233296,
      "name": "push_pipe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
size_t push_pipe(struct iov_iter * i, size_t size, int * iter_headp, size_t * offp)
```

```json
{
  "name": "push_pipe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584640624,
      "name": "push_pipe",
      "external": false,
      "loc": "lib/iov_iter.c:504",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:pipe_zero",
        "lib/iov_iter.c:copy_pipe_to_iter_mcsafe",
        "lib/iov_iter.c:csum_and_copy_to_pipe_iter",
        "lib/iov_iter.c:copy_pipe_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584640624,
      "name": "push_pipe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
size_t push_pipe(struct iov_iter * i, size_t size, int * iter_headp, size_t * offp)
```

```json
{
  "name": "push_pipe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584761424,
      "name": "push_pipe",
      "external": false,
      "loc": "lib/iov_iter.c:511",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:pipe_zero",
        "lib/iov_iter.c:copy_mc_pipe_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_pipe_iter",
        "lib/iov_iter.c:copy_pipe_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584761424,
      "name": "push_pipe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
size_t push_pipe(struct iov_iter * i, size_t size, int * iter_headp, size_t * offp)
```

```json
{
  "name": "push_pipe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584789792,
      "name": "push_pipe",
      "external": false,
      "loc": "lib/iov_iter.c:532",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584789792,
      "name": "push_pipe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
size_t push_pipe(struct iov_iter * i, size_t size, int * iter_headp, size_t * offp)
```

```json
{
  "name": "push_pipe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585223776,
      "name": "push_pipe",
      "external": false,
      "loc": "lib/iov_iter.c:501",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:pipe_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585223776,
      "name": "push_pipe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
size_t push_pipe(struct iov_iter * i, size_t size, int * iter_headp, size_t * offp)
```

```json
{
  "name": "push_pipe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586060960,
      "name": "push_pipe",
      "external": false,
      "loc": "lib/iov_iter.c:546",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:pipe_get_pages_alloc",
        "lib/iov_iter.c:pipe_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:copy_mc_pipe_to_iter",
        "lib/iov_iter.c:copy_pipe_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586060960,
      "name": "push_pipe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
size_t push_pipe(struct iov_iter * i, size_t size, int * idxp, size_t * offp)
```

```json
{
  "name": "push_pipe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496109112,
      "name": "push_pipe",
      "external": false,
      "loc": "lib/iov_iter.c:495",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496109112,
      "name": "push_pipe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
size_t push_pipe(struct iov_iter * i, size_t size, int * idxp, size_t * offp)
```

```json
{
  "name": "push_pipe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229434476,
      "name": "push_pipe",
      "external": false,
      "loc": "lib/iov_iter.c:495",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229434476,
      "name": "push_pipe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
size_t push_pipe(struct iov_iter * i, size_t size, int * idxp, size_t * offp)
```

```json
{
  "name": "push_pipe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290357840,
      "name": "push_pipe",
      "external": false,
      "loc": "lib/iov_iter.c:495",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_to_iter_mcsafe",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290357840,
      "name": "push_pipe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
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
size_t push_pipe(struct iov_iter * i, size_t size, int * idxp, size_t * offp)
```

```json
{
  "name": "push_pipe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275174710,
      "name": "push_pipe",
      "external": false,
      "loc": "lib/iov_iter.c:495",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275174710,
      "name": "push_pipe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
size_t push_pipe(struct iov_iter * i, size_t size, int * idxp, size_t * offp)
```

```json
{
  "name": "push_pipe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584202032,
      "name": "push_pipe",
      "external": false,
      "loc": "lib/iov_iter.c:495",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_to_iter_mcsafe",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584202032,
      "name": "push_pipe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
size_t push_pipe(struct iov_iter * i, size_t size, int * idxp, size_t * offp)
```

```json
{
  "name": "push_pipe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584137248,
      "name": "push_pipe",
      "external": false,
      "loc": "lib/iov_iter.c:495",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_to_iter_mcsafe",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584137248,
      "name": "push_pipe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
size_t push_pipe(struct iov_iter * i, size_t size, int * idxp, size_t * offp)
```

```json
{
  "name": "push_pipe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584185792,
      "name": "push_pipe",
      "external": false,
      "loc": "lib/iov_iter.c:495",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_to_iter_mcsafe",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584185792,
      "name": "push_pipe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
size_t push_pipe(struct iov_iter * i, size_t size, int * idxp, size_t * offp)
```

```json
{
  "name": "push_pipe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584290144,
      "name": "push_pipe",
      "external": false,
      "loc": "lib/iov_iter.c:495",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_to_iter_mcsafe",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584290144,
      "name": "push_pipe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
size_t push_pipe(struct iov_iter * i, size_t size, int * idxp, size_t * offp)
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int * iter_headp</code>
</li>
<li>
<b>Param removed. </b>
<code>int * idxp</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
size_t push_pipe(struct iov_iter * i, size_t size, int * iter_headp, size_t * offp)
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
