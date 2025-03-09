# Function: <code>i2c_check_7bit_addr_validity_strict</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585646752,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": false,
      "loc": "drivers/i2c/i2c-core.c:889",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core.c:i2c_do_add_adapter"
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
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586031312,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": false,
      "loc": "drivers/i2c/i2c-core.c:1022",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_slave_register",
        "drivers/i2c/i2c-core.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core.c:i2c_do_add_adapter"
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
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586241298,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": false,
      "loc": "drivers/i2c/i2c-core.c:1159",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core.c:i2c_do_add_adapter"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
```

```json
{
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586323019,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:561",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586323920,
      "name": "i2c_check_7bit_addr_validity_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
```

```json
{
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586786717,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:566",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586787840,
      "name": "i2c_check_7bit_addr_validity_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
```

```json
{
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587058678,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:547",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587060432,
      "name": "i2c_check_7bit_addr_validity_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
```

```json
{
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587218790,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:559",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587220480,
      "name": "i2c_check_7bit_addr_validity_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
```

```json
{
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587484790,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:557",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587481856,
      "name": "i2c_check_7bit_addr_validity_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
```

```json
{
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587688054,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:562",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587685120,
      "name": "i2c_check_7bit_addr_validity_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
```

```json
{
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588556422,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:572",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_scanned_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588552928,
      "name": "i2c_check_7bit_addr_validity_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
```

```json
{
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588581990,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:700",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_scanned_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588578352,
      "name": "i2c_check_7bit_addr_validity_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
```

```json
{
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588465558,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:744",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_scanned_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588461968,
      "name": "i2c_check_7bit_addr_validity_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
```

```json
{
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589133670,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:745",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_scanned_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589130064,
      "name": "i2c_check_7bit_addr_validity_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
```

```json
{
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590583334,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:746",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_scanned_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590579408,
      "name": "i2c_check_7bit_addr_validity_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
```

```json
{
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592241174,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:747",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_scanned_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592236592,
      "name": "i2c_check_7bit_addr_validity_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
```

```json
{
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592666291,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:762",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_scanned_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592661696,
      "name": "i2c_check_7bit_addr_validity_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
```

```json
{
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593411683,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:765",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_scanned_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect_address"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593406896,
      "name": "i2c_check_7bit_addr_validity_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
```

```json
{
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500848580,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:562",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-slave.c:i2c_slave_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500844912,
      "name": "i2c_check_7bit_addr_validity_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
```

```json
{
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233365632,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:562",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-slave.c:i2c_slave_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233362108,
      "name": "i2c_check_7bit_addr_validity_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
```

```json
{
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294312720,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:562",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294307872,
      "name": "i2c_check_7bit_addr_validity_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
```

```json
{
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277652546,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:562",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277649310,
      "name": "i2c_check_7bit_addr_validity_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
```

```json
{
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587639302,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:562",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587636368,
      "name": "i2c_check_7bit_addr_validity_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
```

```json
{
  "name": "i2c_check_7bit_addr_validity_strict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587750502,
      "name": "i2c_check_7bit_addr_validity_strict",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:562",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587747568,
      "name": "i2c_check_7bit_addr_validity_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr)
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
