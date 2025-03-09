# Function: <code>parse_histogram</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585850095,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:909",
      "file": "drivers/md/dm-stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586244699,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:908",
      "file": "drivers/md/dm-stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586449866,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:909",
      "file": "drivers/md/dm-stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586555622,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:904",
      "file": "drivers/md/dm-stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587023129,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:905",
      "file": "drivers/md/dm-stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587321749,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:906",
      "file": "drivers/md/dm-stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587501989,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:906",
      "file": "drivers/md/dm-stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int parse_histogram(const char * h, unsigned int * n_histogram_entries, long long unsigned int * * histogram_boundaries)
```

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587769312,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:906",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stats.c:message_stats_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587769312,
      "name": "parse_histogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int parse_histogram(const char * h, unsigned int * n_histogram_entries, long long unsigned int * * histogram_boundaries)
```

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587973760,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:906",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stats.c:message_stats_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587973760,
      "name": "parse_histogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int parse_histogram(const char * h, unsigned int * n_histogram_entries, long long unsigned int * * histogram_boundaries)
```

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588828272,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:906",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stats.c:message_stats_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588828272,
      "name": "parse_histogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int parse_histogram(const char * h, unsigned int * n_histogram_entries, long long unsigned int * * histogram_boundaries)
```

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588844784,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:906",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stats.c:message_stats_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588844784,
      "name": "parse_histogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int parse_histogram(const char * h, unsigned int * n_histogram_entries, long long unsigned int * * histogram_boundaries)
```

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588731856,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:906",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stats.c:message_stats_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588731856,
      "name": "parse_histogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int parse_histogram(const char * h, unsigned int * n_histogram_entries, long long unsigned int * * histogram_boundaries)
```

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589421856,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:906",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stats.c:message_stats_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589421856,
      "name": "parse_histogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int parse_histogram(const char * h, unsigned int * n_histogram_entries, long long unsigned int * * histogram_boundaries)
```

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590901456,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:941",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stats.c:message_stats_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590901456,
      "name": "parse_histogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int parse_histogram(const char * h, unsigned int * n_histogram_entries, long long unsigned int * * histogram_boundaries)
```

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592595376,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:941",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stats.c:message_stats_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592595376,
      "name": "parse_histogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int parse_histogram(const char * h, unsigned int * n_histogram_entries, long long unsigned int * * histogram_boundaries)
```

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593025952,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:953",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stats.c:message_stats_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593025952,
      "name": "parse_histogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int parse_histogram(const char * h, unsigned int * n_histogram_entries, long long unsigned int * * histogram_boundaries)
```

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593777376,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:962",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stats.c:message_stats_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593777376,
      "name": "parse_histogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501221580,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:906",
      "file": "drivers/md/dm-stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:message_stats_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233725052,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:906",
      "file": "drivers/md/dm-stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:message_stats_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int parse_histogram(const char * h, unsigned int * n_histogram_entries, long long unsigned int * * histogram_boundaries)
```

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294744016,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:906",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stats.c:message_stats_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294744016,
      "name": "parse_histogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277919522,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:906",
      "file": "drivers/md/dm-stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int parse_histogram(const char * h, unsigned int * n_histogram_entries, long long unsigned int * * histogram_boundaries)
```

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587604736,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:906",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stats.c:message_stats_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587604736,
      "name": "parse_histogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int parse_histogram(const char * h, unsigned int * n_histogram_entries, long long unsigned int * * histogram_boundaries)
```

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587374272,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:906",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stats.c:message_stats_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587374272,
      "name": "parse_histogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int parse_histogram(const char * h, unsigned int * n_histogram_entries, long long unsigned int * * histogram_boundaries)
```

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587929904,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:906",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stats.c:message_stats_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587929904,
      "name": "parse_histogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int parse_histogram(const char * h, unsigned int * n_histogram_entries, long long unsigned int * * histogram_boundaries)
```

```json
{
  "name": "parse_histogram",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588045328,
      "name": "parse_histogram",
      "external": false,
      "loc": "drivers/md/dm-stats.c:906",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-stats.c:message_stats_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588045328,
      "name": "parse_histogram",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int parse_histogram(const char * h, unsigned int * n_histogram_entries, long long unsigned int * * histogram_boundaries)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int parse_histogram(const char * h, unsigned int * n_histogram_entries, long long unsigned int * * histogram_boundaries)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int parse_histogram(const char * h, unsigned int * n_histogram_entries, long long unsigned int * * histogram_boundaries)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int parse_histogram(const char * h, unsigned int * n_histogram_entries, long long unsigned int * * histogram_boundaries)
```
</details>
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
