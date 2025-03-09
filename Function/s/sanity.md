# Function: <code>sanity</code>

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
bool sanity(const struct iov_iter * i)
```

```json
{
  "name": "sanity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583430384,
      "name": "sanity",
      "external": false,
      "loc": "lib/iov_iter.c:300",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_npages",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583430384,
      "name": "sanity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
bool sanity(const struct iov_iter * i)
```

```json
{
  "name": "sanity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583451632,
      "name": "sanity",
      "external": false,
      "loc": "lib/iov_iter.c:320",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_npages",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583451632,
      "name": "sanity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
bool sanity(const struct iov_iter * i)
```

```json
{
  "name": "sanity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583631728,
      "name": "sanity",
      "external": false,
      "loc": "lib/iov_iter.c:320",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_npages",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583631728,
      "name": "sanity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
bool sanity(const struct iov_iter * i)
```

```json
{
  "name": "sanity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanity",
      "external": false,
      "loc": "lib/iov_iter.c:320",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_npages",
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
      "addr": 18446744071583848304,
      "name": "sanity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    },
    {
      "addr": 18446744071583867444,
      "name": "sanity.cold.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
bool sanity(const struct iov_iter * i)
```

```json
{
  "name": "sanity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanity",
      "external": false,
      "loc": "lib/iov_iter.c:324",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_npages",
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
      "addr": 18446744071583932176,
      "name": "sanity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    },
    {
      "addr": 18446744071583952733,
      "name": "sanity.cold.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
bool sanity(const struct iov_iter * i)
```

```json
{
  "name": "sanity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanity",
      "external": false,
      "loc": "lib/iov_iter.c:325",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_npages",
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
      "addr": 18446744071584110240,
      "name": "sanity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071584132107,
      "name": "sanity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
bool sanity(const struct iov_iter * i)
```

```json
{
  "name": "sanity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanity",
      "external": false,
      "loc": "lib/iov_iter.c:325",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_npages",
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
      "addr": 18446744071584233168,
      "name": "sanity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071584255024,
      "name": "sanity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool sanity(const struct iov_iter * i)
```

```json
{
  "name": "sanity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanity",
      "external": false,
      "loc": "lib/iov_iter.c:326",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_npages",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:pipe_zero",
        "lib/iov_iter.c:copy_pipe_to_iter_mcsafe",
        "lib/iov_iter.c:csum_and_copy_to_pipe_iter",
        "lib/iov_iter.c:copy_pipe_to_iter",
        "lib/iov_iter.c:copy_page_to_iter_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584640208,
      "name": "sanity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071584662786,
      "name": "sanity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
bool sanity(const struct iov_iter * i)
```

```json
{
  "name": "sanity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanity",
      "external": false,
      "loc": "lib/iov_iter.c:333",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_npages",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:pipe_zero",
        "lib/iov_iter.c:copy_mc_pipe_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_pipe_iter",
        "lib/iov_iter.c:copy_pipe_to_iter",
        "lib/iov_iter.c:copy_page_to_iter_pipe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584759712,
      "name": "sanity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071591378799,
      "name": "sanity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
bool sanity(const struct iov_iter * i)
```

```json
{
  "name": "sanity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanity",
      "external": false,
      "loc": "lib/iov_iter.c:375",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_npages",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:copy_page_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584788144,
      "name": "sanity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071591321034,
      "name": "sanity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool sanity(const struct iov_iter * i)
```

```json
{
  "name": "sanity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanity",
      "external": false,
      "loc": "lib/iov_iter.c:342",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_npages",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:pipe_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:copy_page_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585219376,
      "name": "sanity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071592323108,
      "name": "sanity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool sanity(const struct iov_iter * i)
```

```json
{
  "name": "sanity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanity",
      "external": false,
      "loc": "lib/iov_iter.c:340",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_npages",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:pipe_get_pages_alloc",
        "lib/iov_iter.c:pipe_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:copy_page_to_iter",
        "lib/iov_iter.c:copy_mc_pipe_to_iter",
        "lib/iov_iter.c:copy_pipe_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586057536,
      "name": "sanity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071594126949,
      "name": "sanity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
  "name": "sanity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587044800,
      "name": "sanity",
      "external": false,
      "loc": "lib/iov_iter.c:196",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_npages",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:pipe_get_pages",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:copy_page_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:copy_pipe_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587044800,
      "name": "sanity.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
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
bool sanity(const struct iov_iter * i)
```

```json
{
  "name": "sanity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496108856,
      "name": "sanity",
      "external": false,
      "loc": "lib/iov_iter.c:325",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_npages",
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
      "addr": 18446603336496108856,
      "name": "sanity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
bool sanity(const struct iov_iter * i)
```

```json
{
  "name": "sanity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229434192,
      "name": "sanity",
      "external": false,
      "loc": "lib/iov_iter.c:325",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_npages",
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
      "addr": 3229434192,
      "name": "sanity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
bool sanity(const struct iov_iter * i)
```

```json
{
  "name": "sanity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290357504,
      "name": "sanity",
      "external": false,
      "loc": "lib/iov_iter.c:325",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_npages",
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
      "addr": 13835058055290357504,
      "name": "sanity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
bool sanity(const struct iov_iter * i)
```

```json
{
  "name": "sanity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275174512,
      "name": "sanity",
      "external": false,
      "loc": "lib/iov_iter.c:325",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_npages",
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
      "addr": 18446743936275174512,
      "name": "sanity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
bool sanity(const struct iov_iter * i)
```

```json
{
  "name": "sanity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanity",
      "external": false,
      "loc": "lib/iov_iter.c:325",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_npages",
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
      "addr": 18446744071584201904,
      "name": "sanity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071584223760,
      "name": "sanity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
bool sanity(const struct iov_iter * i)
```

```json
{
  "name": "sanity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanity",
      "external": false,
      "loc": "lib/iov_iter.c:325",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_npages",
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
      "addr": 18446744071584137120,
      "name": "sanity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071584158976,
      "name": "sanity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
bool sanity(const struct iov_iter * i)
```

```json
{
  "name": "sanity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanity",
      "external": false,
      "loc": "lib/iov_iter.c:325",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_npages",
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
      "addr": 18446744071584185664,
      "name": "sanity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071584207520,
      "name": "sanity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
bool sanity(const struct iov_iter * i)
```

```json
{
  "name": "sanity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanity",
      "external": false,
      "loc": "lib/iov_iter.c:325",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_npages",
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
      "addr": 18446744071584290016,
      "name": "sanity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071584312080,
      "name": "sanity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
bool sanity(const struct iov_iter * i)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool sanity(const struct iov_iter * i)
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
