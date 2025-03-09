# Function: <code>get_user_pages_unlocked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int get_user_pages_unlocked(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, int write, int force, struct page * * pages)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580660416,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:791",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/gup.c:get_user_pages_fast",
        "mm/util.c:get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580660416,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 469
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, int write, int force, struct page * * pages)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580769216,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:898",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/gup.c:get_user_pages_fast",
        "mm/util.c:get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580769216,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580834720,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:900",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/gup.c:get_user_pages_fast",
        "mm/util.c:get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580834720,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580877344,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:981",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580877344,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580972640,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:1006",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580972640,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581108064,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:1004",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581108064,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581187968,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:1029",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581187968,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581258688,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:1678",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581258688,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581317360,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:1681",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581317360,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581507552,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:2065",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_unlocked",
        "mm/gup.c:internal_get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581507552,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 639
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581547776,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:1921",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_unlocked",
        "mm/gup.c:internal_get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581547776,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 784
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581570704,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:1987",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_unlocked",
        "mm/gup.c:internal_get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570704,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 779
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581835248,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:2075",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_unlocked",
        "mm/gup.c:internal_get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581835248,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 809
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582226944,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:2205",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_unlocked",
        "mm/gup.c:internal_get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226944,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 767
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582718928,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:2242",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_unlocked",
        "mm/gup.c:internal_get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582718928,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582932464,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:2389",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582932464,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 817
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583107360,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:2407",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583107360,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 872
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492723440,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:1681",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:__gfn_to_pfn_memslot",
        "mm/gup.c:get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492723440,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226554584,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:1681",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226554584,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286068560,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:1681",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286068560,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272716132,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:1681",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272716132,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581286208,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:1681",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581286208,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581232016,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:1681",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581232016,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581277408,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:1681",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581277408,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
long int get_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "get_user_pages_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581341328,
      "name": "get_user_pages_unlocked",
      "external": true,
      "loc": "mm/gup.c:1681",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581341328,
      "name": "get_user_pages_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct * tsk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct * mm</code>
</li>
<li>
<b>Param reordered. </b>
<code>tsk, mm, start, nr_pages, write, force, pages</code> ➡️ <code>start, nr_pages, write, force, pages</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int gup_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int write</code>
</li>
<li>
<b>Param removed. </b>
<code>int force</code>
</li>
<li>
<b>Param reordered. </b>
<code>start, nr_pages, write, force, pages</code> ➡️ <code>start, nr_pages, pages, gup_flags</code>
</li>
</ul>
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
