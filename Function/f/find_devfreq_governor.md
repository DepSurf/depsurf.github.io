# Function: <code>find_devfreq_governor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586106192,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:132",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_add_governor",
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:governor_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586106192,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586519568,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:173",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586519568,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586699232,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:178",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586699232,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586825008,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:176",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586825008,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587308912,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:205",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587308912,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587611760,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:205",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587611760,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587740080,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:203",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587740080,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:203",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor",
        "drivers/devfreq/devfreq.c:try_then_request_governor",
        "drivers/devfreq/devfreq.c:try_then_request_governor",
        "drivers/devfreq/devfreq.c:try_then_request_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588043552,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071588051404,
      "name": "find_devfreq_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588257457,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:204",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588254032,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071588257457,
      "name": "find_devfreq_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589136608,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:257",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589130208,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071589136608,
      "name": "find_devfreq_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591621093,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:264",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589129152,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071591621093,
      "name": "find_devfreq_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591564458,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:265",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589018912,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071591564458,
      "name": "find_devfreq_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592685587,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:265",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589734656,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071592685587,
      "name": "find_devfreq_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594570932,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:262",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591247152,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071594570932,
      "name": "find_devfreq_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593006229,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:262",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:governor_store"
      ],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593000128,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593457749,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:262",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:governor_store"
      ],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593451600,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594204693,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:262",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:governor_store"
      ],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594198272,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501708024,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:204",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor",
        "drivers/devfreq/devfreq.c:try_then_request_governor",
        "drivers/devfreq/devfreq.c:try_then_request_governor",
        "drivers/devfreq/devfreq.c:try_then_request_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501708024,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234236732,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:204",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234236732,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295155296,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:204",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295155296,
      "name": "find_devfreq_governor",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278125984,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:204",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278125984,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587869153,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:204",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587865728,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071587869153,
      "name": "find_devfreq_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587595953,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:204",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587592528,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071587595953,
      "name": "find_devfreq_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588194513,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:204",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588191088,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071588194513,
      "name": "find_devfreq_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct devfreq_governor * find_devfreq_governor(const char * name)
```

```json
{
  "name": "find_devfreq_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588329809,
      "name": "find_devfreq_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:204",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_remove_governor",
        "drivers/devfreq/devfreq.c:devfreq_add_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588326384,
      "name": "find_devfreq_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071588329809,
      "name": "find_devfreq_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
