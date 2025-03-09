# Function: <code>extcon_dev_allocate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586115503,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:669",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:devm_extcon_dev_allocate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586117632,
      "name": "extcon_dev_allocate",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586530480,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:540",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586530480,
      "name": "extcon_dev_allocate",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586712176,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:1016",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586712176,
      "name": "extcon_dev_allocate",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586838368,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:1058",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586838368,
      "name": "extcon_dev_allocate",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587326128,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:1048",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587326128,
      "name": "extcon_dev_allocate",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587629104,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:1049",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587629104,
      "name": "extcon_dev_allocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587758064,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:1049",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587758064,
      "name": "extcon_dev_allocate",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588062512,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:1041",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588062512,
      "name": "extcon_dev_allocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588268416,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:1041",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588268416,
      "name": "extcon_dev_allocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589148208,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:1041",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589148208,
      "name": "extcon_dev_allocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589147136,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:1041",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589147136,
      "name": "extcon_dev_allocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589037232,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:1041",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589037232,
      "name": "extcon_dev_allocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589753776,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:1041",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589753776,
      "name": "extcon_dev_allocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591266560,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:1035",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591266560,
      "name": "extcon_dev_allocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593022256,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:1045",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593022256,
      "name": "extcon_dev_allocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593473952,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:1056",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593473952,
      "name": "extcon_dev_allocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594221056,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:1056",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594221056,
      "name": "extcon_dev_allocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501730400,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:1041",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501730400,
      "name": "extcon_dev_allocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234259364,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:1041",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234259364,
      "name": "extcon_dev_allocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295178240,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:1041",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295178240,
      "name": "extcon_dev_allocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278143598,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:1041",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278143598,
      "name": "extcon_dev_allocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587880112,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:1041",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587880112,
      "name": "extcon_dev_allocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588205472,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:1041",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588205472,
      "name": "extcon_dev_allocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
```

```json
{
  "name": "extcon_dev_allocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588340768,
      "name": "extcon_dev_allocate",
      "external": true,
      "loc": "drivers/extcon/extcon.c:1041",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588340768,
      "name": "extcon_dev_allocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct extcon_dev * extcon_dev_allocate(const unsigned int * supported_cable)
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
