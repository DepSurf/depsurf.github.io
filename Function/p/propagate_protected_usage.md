# Function: <code>propagate_protected_usage</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void propagate_protected_usage(struct page_counter * c, long unsigned int usage)
```

```json
{
  "name": "propagate_protected_usage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581459072,
      "name": "propagate_protected_usage",
      "external": false,
      "loc": "mm/page_counter.c:16",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_counter.c:page_counter_set_low",
        "mm/page_counter.c:page_counter_set_min",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459072,
      "name": "propagate_protected_usage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void propagate_protected_usage(struct page_counter * c, long unsigned int usage)
```

```json
{
  "name": "propagate_protected_usage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581542768,
      "name": "propagate_protected_usage",
      "external": false,
      "loc": "mm/page_counter.c:16",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_counter.c:page_counter_set_low",
        "mm/page_counter.c:page_counter_set_min",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581542768,
      "name": "propagate_protected_usage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void propagate_protected_usage(struct page_counter * c, long unsigned int usage)
```

```json
{
  "name": "propagate_protected_usage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581651776,
      "name": "propagate_protected_usage",
      "external": false,
      "loc": "mm/page_counter.c:16",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_counter.c:page_counter_set_low",
        "mm/page_counter.c:page_counter_set_min",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581651776,
      "name": "propagate_protected_usage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void propagate_protected_usage(struct page_counter * c, long unsigned int usage)
```

```json
{
  "name": "propagate_protected_usage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581724304,
      "name": "propagate_protected_usage",
      "external": false,
      "loc": "mm/page_counter.c:16",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_counter.c:page_counter_set_low",
        "mm/page_counter.c:page_counter_set_min",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581724304,
      "name": "propagate_protected_usage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void propagate_protected_usage(struct page_counter * c, long unsigned int usage)
```

```json
{
  "name": "propagate_protected_usage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581942128,
      "name": "propagate_protected_usage",
      "external": false,
      "loc": "mm/page_counter.c:16",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_counter.c:page_counter_set_low",
        "mm/page_counter.c:page_counter_set_min",
        "mm/page_counter.c:page_counter_uncharge",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581942128,
      "name": "propagate_protected_usage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void propagate_protected_usage(struct page_counter * c, long unsigned int usage)
```

```json
{
  "name": "propagate_protected_usage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989472,
      "name": "propagate_protected_usage",
      "external": false,
      "loc": "mm/page_counter.c:16",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_counter.c:page_counter_set_low",
        "mm/page_counter.c:page_counter_set_min",
        "mm/page_counter.c:page_counter_uncharge",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989472,
      "name": "propagate_protected_usage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void propagate_protected_usage(struct page_counter * c, long unsigned int usage)
```

```json
{
  "name": "propagate_protected_usage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582017280,
      "name": "propagate_protected_usage",
      "external": false,
      "loc": "mm/page_counter.c:16",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_counter.c:page_counter_set_low",
        "mm/page_counter.c:page_counter_set_min",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_charge",
        "mm/page_counter.c:page_counter_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582017280,
      "name": "propagate_protected_usage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void propagate_protected_usage(struct page_counter * c, long unsigned int usage)
```

```json
{
  "name": "propagate_protected_usage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582319920,
      "name": "propagate_protected_usage",
      "external": false,
      "loc": "mm/page_counter.c:16",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_counter.c:page_counter_set_low",
        "mm/page_counter.c:page_counter_set_min",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_charge",
        "mm/page_counter.c:page_counter_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582319920,
      "name": "propagate_protected_usage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void propagate_protected_usage(struct page_counter * c, long unsigned int usage)
```

```json
{
  "name": "propagate_protected_usage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582812128,
      "name": "propagate_protected_usage",
      "external": false,
      "loc": "mm/page_counter.c:16",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_counter.c:page_counter_set_low",
        "mm/page_counter.c:page_counter_set_min",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_charge",
        "mm/page_counter.c:page_counter_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812128,
      "name": "propagate_protected_usage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void propagate_protected_usage(struct page_counter * c, long unsigned int usage)
```

```json
{
  "name": "propagate_protected_usage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583354528,
      "name": "propagate_protected_usage",
      "external": false,
      "loc": "mm/page_counter.c:16",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_counter.c:page_counter_set_low",
        "mm/page_counter.c:page_counter_set_min",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_charge",
        "mm/page_counter.c:page_counter_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583354528,
      "name": "propagate_protected_usage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void propagate_protected_usage(struct page_counter * c, long unsigned int usage)
```

```json
{
  "name": "propagate_protected_usage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583573856,
      "name": "propagate_protected_usage",
      "external": false,
      "loc": "mm/page_counter.c:16",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_counter.c:page_counter_set_low",
        "mm/page_counter.c:page_counter_set_min",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_charge",
        "mm/page_counter.c:page_counter_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583573856,
      "name": "propagate_protected_usage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void propagate_protected_usage(struct page_counter * c, long unsigned int usage)
```

```json
{
  "name": "propagate_protected_usage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583767264,
      "name": "propagate_protected_usage",
      "external": false,
      "loc": "mm/page_counter.c:16",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_counter.c:page_counter_set_low",
        "mm/page_counter.c:page_counter_set_min",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_charge",
        "mm/page_counter.c:page_counter_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583767264,
      "name": "propagate_protected_usage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void propagate_protected_usage(struct page_counter * c, long unsigned int usage)
```

```json
{
  "name": "propagate_protected_usage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493173104,
      "name": "propagate_protected_usage",
      "external": false,
      "loc": "mm/page_counter.c:16",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_counter.c:page_counter_set_low",
        "mm/page_counter.c:page_counter_set_min",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493173104,
      "name": "propagate_protected_usage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void propagate_protected_usage(struct page_counter * c, long unsigned int usage)
```

```json
{
  "name": "propagate_protected_usage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226808564,
      "name": "propagate_protected_usage",
      "external": false,
      "loc": "mm/page_counter.c:16",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_counter.c:page_counter_set_low",
        "mm/page_counter.c:page_counter_set_min",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226808564,
      "name": "propagate_protected_usage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void propagate_protected_usage(struct page_counter * c, long unsigned int usage)
```

```json
{
  "name": "propagate_protected_usage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286667952,
      "name": "propagate_protected_usage",
      "external": false,
      "loc": "mm/page_counter.c:16",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_counter.c:page_counter_set_low",
        "mm/page_counter.c:page_counter_set_min",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286667952,
      "name": "propagate_protected_usage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
void propagate_protected_usage(struct page_counter * c, long unsigned int usage)
```

```json
{
  "name": "propagate_protected_usage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272958104,
      "name": "propagate_protected_usage",
      "external": false,
      "loc": "mm/page_counter.c:16",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_counter.c:page_counter_set_low",
        "mm/page_counter.c:page_counter_set_min",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272958104,
      "name": "propagate_protected_usage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void propagate_protected_usage(struct page_counter * c, long unsigned int usage)
```

```json
{
  "name": "propagate_protected_usage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581693040,
      "name": "propagate_protected_usage",
      "external": false,
      "loc": "mm/page_counter.c:16",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_counter.c:page_counter_set_low",
        "mm/page_counter.c:page_counter_set_min",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581693040,
      "name": "propagate_protected_usage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void propagate_protected_usage(struct page_counter * c, long unsigned int usage)
```

```json
{
  "name": "propagate_protected_usage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581632064,
      "name": "propagate_protected_usage",
      "external": false,
      "loc": "mm/page_counter.c:16",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_counter.c:page_counter_set_low",
        "mm/page_counter.c:page_counter_set_min",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581632064,
      "name": "propagate_protected_usage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void propagate_protected_usage(struct page_counter * c, long unsigned int usage)
```

```json
{
  "name": "propagate_protected_usage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581684352,
      "name": "propagate_protected_usage",
      "external": false,
      "loc": "mm/page_counter.c:16",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_counter.c:page_counter_set_low",
        "mm/page_counter.c:page_counter_set_min",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581684352,
      "name": "propagate_protected_usage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void propagate_protected_usage(struct page_counter * c, long unsigned int usage)
```

```json
{
  "name": "propagate_protected_usage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581751232,
      "name": "propagate_protected_usage",
      "external": false,
      "loc": "mm/page_counter.c:16",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_counter.c:page_counter_set_low",
        "mm/page_counter.c:page_counter_set_min",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751232,
      "name": "propagate_protected_usage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void propagate_protected_usage(struct page_counter * c, long unsigned int usage)
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
