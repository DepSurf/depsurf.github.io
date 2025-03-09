# Function: <code>pwmchip_find_by_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583222443,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:87",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwm_get"
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
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583529538,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:88",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwm_get"
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
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583665570,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:88",
      "file": "drivers/pwm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwm_get"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pwm_chip * pwmchip_find_by_name(const char * name)
```

```json
{
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583704544,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:88",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583704544,
      "name": "pwmchip_find_by_name",
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
struct pwm_chip * pwmchip_find_by_name(const char * name)
```

```json
{
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583961904,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:88",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583961904,
      "name": "pwmchip_find_by_name",
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
struct pwm_chip * pwmchip_find_by_name(const char * name)
```

```json
{
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584156720,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:88",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584156720,
      "name": "pwmchip_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
struct pwm_chip * pwmchip_find_by_name(const char * name)
```

```json
{
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584244448,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:88",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584244448,
      "name": "pwmchip_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
struct pwm_chip * pwmchip_find_by_name(const char * name)
```

```json
{
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584436768,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:76",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584436768,
      "name": "pwmchip_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
struct pwm_chip * pwmchip_find_by_name(const char * name)
```

```json
{
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584573536,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:76",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584573536,
      "name": "pwmchip_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
struct pwm_chip * pwmchip_find_by_name(const char * name)
```

```json
{
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585247792,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:79",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585247792,
      "name": "pwmchip_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
struct pwm_chip * pwmchip_find_by_name(const char * name)
```

```json
{
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585405376,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:79",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585405376,
      "name": "pwmchip_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
struct pwm_chip * pwmchip_find_by_name(const char * name)
```

```json
{
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585286352,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:69",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585286352,
      "name": "pwmchip_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
struct pwm_chip * pwmchip_find_by_name(const char * name)
```

```json
{
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585742448,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:69",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585742448,
      "name": "pwmchip_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
struct pwm_chip * pwmchip_find_by_name(const char * name)
```

```json
{
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586924944,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:69",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586924944,
      "name": "pwmchip_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
struct pwm_chip * pwmchip_find_by_name(const char * name)
```

```json
{
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588081072,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:76",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588081072,
      "name": "pwmchip_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
struct pwm_chip * pwmchip_find_by_name(const char * name)
```

```json
{
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588355568,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:62",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588355568,
      "name": "pwmchip_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
struct pwm_chip * pwmchip_find_by_name(const char * name)
```

```json
{
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588649920,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:35",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588649920,
      "name": "pwmchip_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
struct pwm_chip * pwmchip_find_by_name(const char * name)
```

```json
{
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496806576,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:76",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496806576,
      "name": "pwmchip_find_by_name",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pwm_chip * pwmchip_find_by_name(const char * name)
```

```json
{
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230092072,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:76",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230092072,
      "name": "pwmchip_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct pwm_chip * pwmchip_find_by_name(const char * name)
```

```json
{
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290874992,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:76",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290874992,
      "name": "pwmchip_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
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
struct pwm_chip * pwmchip_find_by_name(const char * name)
```

```json
{
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275518392,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:76",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275518392,
      "name": "pwmchip_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
struct pwm_chip * pwmchip_find_by_name(const char * name)
```

```json
{
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584527984,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:76",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584527984,
      "name": "pwmchip_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pwm_chip * pwmchip_find_by_name(const char * name)
```

```json
{
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584523696,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:76",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584523696,
      "name": "pwmchip_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
struct pwm_chip * pwmchip_find_by_name(const char * name)
```

```json
{
  "name": "pwmchip_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584631472,
      "name": "pwmchip_find_by_name",
      "external": false,
      "loc": "drivers/pwm/core.c:76",
      "file": "drivers/pwm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584631472,
      "name": "pwmchip_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct pwm_chip * pwmchip_find_by_name(const char * name)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct pwm_chip * pwmchip_find_by_name(const char * name)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
