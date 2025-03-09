# Function: <code>kobject_namespace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
const void * kobject_namespace(struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582956144,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:30",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_add_internal",
        "drivers/base/core.c:device_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582956144,
      "name": "kobject_namespace",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
const void * kobject_namespace(struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583243840,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:30",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "drivers/base/core.c:device_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583243840,
      "name": "kobject_namespace",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
const void * kobject_namespace(struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583359152,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:30",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "drivers/base/core.c:device_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583359152,
      "name": "kobject_namespace",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
const void * kobject_namespace(struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588209488,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:30",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_rename",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588209488,
      "name": "kobject_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
const void * kobject_namespace(struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588759056,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:30",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_rename",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588759056,
      "name": "kobject_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
const void * kobject_namespace(struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589137360,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:28",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_rename",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589137360,
      "name": "kobject_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
const void * kobject_namespace(struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589372208,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:28",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_rename",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589372208,
      "name": "kobject_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
const void * kobject_namespace(struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589829232,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:28",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_rename",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589829232,
      "name": "kobject_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
const void * kobject_namespace(struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590055376,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:28",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_rename",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590055376,
      "name": "kobject_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
const void * kobject_namespace(struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585050464,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:28",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:create_dir",
        "drivers/base/core.c:device_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585050464,
      "name": "kobject_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
const void * kobject_namespace(struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585200256,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:28",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:create_dir",
        "drivers/base/core.c:device_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585200256,
      "name": "kobject_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
const void * kobject_namespace(struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585083328,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:28",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:create_dir",
        "drivers/base/core.c:device_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585083328,
      "name": "kobject_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
const void * kobject_namespace(struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585530256,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:28",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:create_dir",
        "drivers/base/core.c:device_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585530256,
      "name": "kobject_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
const void * kobject_namespace(struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586684128,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:28",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal",
        "drivers/base/core.c:device_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586684128,
      "name": "kobject_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
const void * kobject_namespace(const struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595765008,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:28",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_rename",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595765008,
      "name": "kobject_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
const void * kobject_namespace(const struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596289408,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:30",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_rename",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596289408,
      "name": "kobject_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
const void * kobject_namespace(const struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597174272,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:30",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_rename",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597174272,
      "name": "kobject_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
const void * kobject_namespace(struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503831936,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:28",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_rename",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503831936,
      "name": "kobject_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
const void * kobject_namespace(struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236451512,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:28",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_rename",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236451512,
      "name": "kobject_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
const void * kobject_namespace(struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297680240,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:28",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_rename",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297680240,
      "name": "kobject_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
const void * kobject_namespace(struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279724744,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:28",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_rename",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279724744,
      "name": "kobject_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
const void * kobject_namespace(struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589657632,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:28",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_rename",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589657632,
      "name": "kobject_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
const void * kobject_namespace(struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589383456,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:28",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_rename",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589383456,
      "name": "kobject_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
const void * kobject_namespace(struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590101008,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:28",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_rename",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590101008,
      "name": "kobject_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
const void * kobject_namespace(struct kobject * kobj)
```

```json
{
  "name": "kobject_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590151312,
      "name": "kobject_namespace",
      "external": true,
      "loc": "lib/kobject.c:28",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_rename",
        "lib/kobject.c:kobject_move",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590151312,
      "name": "kobject_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct kobject * kobj</code> ➡️ <code>const struct kobject * kobj</code>
</li>
</ul>
</details>
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
