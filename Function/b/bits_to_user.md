# Function: <code>bits_to_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585583696,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:730",
      "file": "drivers/input/evdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_do_ioctl"
      ],
      "caller_func": [
        "drivers/input/evdev.c:evdev_handle_get_val",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585583696,
      "name": "bits_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585979344,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:730",
      "file": "drivers/input/evdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585979344,
      "name": "bits_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586167664,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:730",
      "file": "drivers/input/evdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586167664,
      "name": "bits_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586258096,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:730",
      "file": "drivers/input/evdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586258096,
      "name": "bits_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586721504,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:730",
      "file": "drivers/input/evdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586721504,
      "name": "bits_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586988064,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:736",
      "file": "drivers/input/evdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586988064,
      "name": "bits_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587149216,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:737",
      "file": "drivers/input/evdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587149216,
      "name": "bits_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587414288,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:733",
      "file": "drivers/input/evdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587414288,
      "name": "bits_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587616048,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:711",
      "file": "drivers/input/evdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587616048,
      "name": "bits_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588478704,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:702",
      "file": "drivers/input/evdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588478704,
      "name": "bits_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588508080,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:702",
      "file": "drivers/input/evdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588508080,
      "name": "bits_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588390576,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:702",
      "file": "drivers/input/evdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588390576,
      "name": "bits_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589061544,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:702",
      "file": "drivers/input/evdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_do_ioctl"
      ],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589054800,
      "name": "bits_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590504108,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:702",
      "file": "drivers/input/evdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_do_ioctl"
      ],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590500288,
      "name": "bits_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592150961,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:702",
      "file": "drivers/input/evdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_do_ioctl"
      ],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_get_mask",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592146880,
      "name": "bits_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592574346,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:702",
      "file": "drivers/input/evdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_do_ioctl"
      ],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_get_mask",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592570304,
      "name": "bits_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593318970,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:702",
      "file": "drivers/input/evdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_do_ioctl"
      ],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_get_mask",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593314928,
      "name": "bits_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500768680,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:711",
      "file": "drivers/input/evdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500768680,
      "name": "bits_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233280912,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:745",
      "file": "drivers/input/evdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233280912,
      "name": "bits_to_user.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294219824,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:711",
      "file": "drivers/input/evdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294219824,
      "name": "bits_to_user",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277602500,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:745",
      "file": "drivers/input/evdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277602500,
      "name": "bits_to_user.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587308864,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:711",
      "file": "drivers/input/evdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587308864,
      "name": "bits_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587077248,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:711",
      "file": "drivers/input/evdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587077248,
      "name": "bits_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587567296,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:711",
      "file": "drivers/input/evdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587567296,
      "name": "bits_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
```

```json
{
  "name": "bits_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587679040,
      "name": "bits_to_user",
      "external": false,
      "loc": "drivers/input/evdev.c:711",
      "file": "drivers/input/evdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587679040,
      "name": "bits_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
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
int bits_to_user(long unsigned int * bits, unsigned int maxbit, unsigned int maxlen, void * p, int compat)
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
