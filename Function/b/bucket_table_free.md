# Function: <code>bucket_table_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583039296,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:98",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:bucket_table_free_rcu",
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:bucket_table_alloc",
        "lib/rhashtable.c:rhashtable_insert_rehash",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583039296,
      "name": "bucket_table_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583331952,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:102",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:rhashtable_insert_rehash",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:bucket_table_alloc",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583331952,
      "name": "bucket_table_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583457264,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:102",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:bucket_table_alloc",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583457264,
      "name": "bucket_table_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583478304,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:138",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:rhashtable_rehash_alloc",
        "lib/rhashtable.c:bucket_table_alloc",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583478304,
      "name": "bucket_table_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583659280,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:138",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:rhashtable_rehash_alloc",
        "lib/rhashtable.c:bucket_table_alloc",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583659280,
      "name": "bucket_table_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583876048,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:102",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:rhashtable_rehash_alloc",
        "lib/rhashtable.c:bucket_table_alloc",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583876048,
      "name": "bucket_table_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583959040,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:102",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:rhashtable_rehash_alloc",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583959040,
      "name": "bucket_table_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584139296,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:100",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584139296,
      "name": "bucket_table_free",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584261744,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:100",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584261744,
      "name": "bucket_table_free",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584671424,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:109",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_destroy",
        "lib/rhashtable.c:rhashtable_insert_rehash",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:rhashtable_shrink",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584671424,
      "name": "bucket_table_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584789040,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:109",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_destroy",
        "lib/rhashtable.c:rhashtable_insert_rehash",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584789040,
      "name": "bucket_table_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584834192,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:109",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_destroy",
        "lib/rhashtable.c:rhashtable_try_insert",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584834192,
      "name": "bucket_table_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:109",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_destroy",
        "lib/rhashtable.c:rhashtable_try_insert",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585253296,
      "name": "bucket_table_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071592324157,
      "name": "bucket_table_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:109",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_destroy",
        "lib/rhashtable.c:rhashtable_try_insert",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586095040,
      "name": "bucket_table_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071594128654,
      "name": "bucket_table_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:109",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_destroy",
        "lib/rhashtable.c:rhashtable_try_insert",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587078608,
      "name": "bucket_table_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071596115578,
      "name": "bucket_table_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:109",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_destroy",
        "lib/rhashtable.c:rhashtable_try_insert",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587337568,
      "name": "bucket_table_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071596641270,
      "name": "bucket_table_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:109",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_destroy",
        "lib/rhashtable.c:rhashtable_try_insert",
        "lib/rhashtable.c:rht_deferred_worker",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587621040,
      "name": "bucket_table_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071597549335,
      "name": "bucket_table_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496143096,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:100",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496143096,
      "name": "bucket_table_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229465088,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:100",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:rhashtable_rehash_alloc",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229465088,
      "name": "bucket_table_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290402208,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:100",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290402208,
      "name": "bucket_table_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275198640,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:100",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275198640,
      "name": "bucket_table_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584230480,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:100",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584230480,
      "name": "bucket_table_free",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584165680,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:100",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584165680,
      "name": "bucket_table_free",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584214240,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:100",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584214240,
      "name": "bucket_table_free",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void bucket_table_free(const struct bucket_table * tbl)
```

```json
{
  "name": "bucket_table_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584319104,
      "name": "bucket_table_free",
      "external": false,
      "loc": "lib/rhashtable.c:100",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_free_and_destroy",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:bucket_table_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584319104,
      "name": "bucket_table_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
