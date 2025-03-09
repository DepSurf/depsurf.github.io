# Function: <code>input_set_timestamp</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void input_set_timestamp(struct input_dev * dev, ktime_t timestamp)
```

```json
{
  "name": "input_set_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587589184,
      "name": "input_set_timestamp",
      "external": true,
      "loc": "drivers/input/input.c:1944",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/input.c:input_get_timestamp",
        "drivers/input/input.c:input_repeat_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587589184,
      "name": "input_set_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void input_set_timestamp(struct input_dev * dev, ktime_t timestamp)
```

```json
{
  "name": "input_set_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588455229,
      "name": "input_set_timestamp",
      "external": true,
      "loc": "drivers/input/input.c:1942",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_get_timestamp",
        "drivers/input/input.c:input_repeat_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588449824,
      "name": "input_set_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void input_set_timestamp(struct input_dev * dev, ktime_t timestamp)
```

```json
{
  "name": "input_set_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588484733,
      "name": "input_set_timestamp",
      "external": true,
      "loc": "drivers/input/input.c:2040",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_get_timestamp",
        "drivers/input/input.c:input_repeat_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588479872,
      "name": "input_set_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void input_set_timestamp(struct input_dev * dev, ktime_t timestamp)
```

```json
{
  "name": "input_set_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588367517,
      "name": "input_set_timestamp",
      "external": true,
      "loc": "drivers/input/input.c:2040",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_get_timestamp",
        "drivers/input/input.c:input_repeat_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588361696,
      "name": "input_set_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void input_set_timestamp(struct input_dev * dev, ktime_t timestamp)
```

```json
{
  "name": "input_set_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589031469,
      "name": "input_set_timestamp",
      "external": true,
      "loc": "drivers/input/input.c:2040",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_get_timestamp",
        "drivers/input/input.c:input_repeat_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589024752,
      "name": "input_set_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void input_set_timestamp(struct input_dev * dev, ktime_t timestamp)
```

```json
{
  "name": "input_set_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590472557,
      "name": "input_set_timestamp",
      "external": true,
      "loc": "drivers/input/input.c:2085",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_get_timestamp",
        "drivers/input/input.c:input_repeat_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590465184,
      "name": "input_set_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void input_set_timestamp(struct input_dev * dev, ktime_t timestamp)
```

```json
{
  "name": "input_set_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592124863,
      "name": "input_set_timestamp",
      "external": true,
      "loc": "drivers/input/input.c:2069",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_repeat_key",
        "drivers/input/input.c:input_get_timestamp"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592107936,
      "name": "input_set_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void input_set_timestamp(struct input_dev * dev, ktime_t timestamp)
```

```json
{
  "name": "input_set_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592548239,
      "name": "input_set_timestamp",
      "external": true,
      "loc": "drivers/input/input.c:2068",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_repeat_key",
        "drivers/input/input.c:input_get_timestamp"
      ],
      "caller_func": [
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592531680,
      "name": "input_set_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void input_set_timestamp(struct input_dev * dev, ktime_t timestamp)
```

```json
{
  "name": "input_set_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593292687,
      "name": "input_set_timestamp",
      "external": true,
      "loc": "drivers/input/input.c:2068",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_repeat_key",
        "drivers/input/input.c:input_get_timestamp"
      ],
      "caller_func": [
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593276160,
      "name": "input_set_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void input_set_timestamp(struct input_dev * dev, ktime_t timestamp)
```

```json
{
  "name": "input_set_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500731488,
      "name": "input_set_timestamp",
      "external": true,
      "loc": "drivers/input/input.c:1944",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/input.c:input_get_timestamp",
        "drivers/input/input.c:input_repeat_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500731488,
      "name": "input_set_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void input_set_timestamp(struct input_dev * dev, ktime_t timestamp)
```

```json
{
  "name": "input_set_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233254172,
      "name": "input_set_timestamp",
      "external": true,
      "loc": "drivers/input/input.c:1944",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/input.c:input_get_timestamp",
        "drivers/input/input.c:input_repeat_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233254172,
      "name": "input_set_timestamp",
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
void input_set_timestamp(struct input_dev * dev, ktime_t timestamp)
```

```json
{
  "name": "input_set_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294178336,
      "name": "input_set_timestamp",
      "external": true,
      "loc": "drivers/input/input.c:1944",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/input.c:input_get_timestamp",
        "drivers/input/input.c:input_repeat_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294178336,
      "name": "input_set_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void input_set_timestamp(struct input_dev * dev, ktime_t timestamp)
```

```json
{
  "name": "input_set_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277575756,
      "name": "input_set_timestamp",
      "external": true,
      "loc": "drivers/input/input.c:1944",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/input.c:input_get_timestamp",
        "drivers/input/input.c:input_repeat_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277575756,
      "name": "input_set_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void input_set_timestamp(struct input_dev * dev, ktime_t timestamp)
```

```json
{
  "name": "input_set_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587282000,
      "name": "input_set_timestamp",
      "external": true,
      "loc": "drivers/input/input.c:1944",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/input.c:input_get_timestamp",
        "drivers/input/input.c:input_repeat_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587282000,
      "name": "input_set_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void input_set_timestamp(struct input_dev * dev, ktime_t timestamp)
```

```json
{
  "name": "input_set_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587050432,
      "name": "input_set_timestamp",
      "external": true,
      "loc": "drivers/input/input.c:1944",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/input.c:input_get_timestamp",
        "drivers/input/input.c:input_repeat_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587050432,
      "name": "input_set_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void input_set_timestamp(struct input_dev * dev, ktime_t timestamp)
```

```json
{
  "name": "input_set_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587540432,
      "name": "input_set_timestamp",
      "external": true,
      "loc": "drivers/input/input.c:1944",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/input.c:input_get_timestamp",
        "drivers/input/input.c:input_repeat_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587540432,
      "name": "input_set_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void input_set_timestamp(struct input_dev * dev, ktime_t timestamp)
```

```json
{
  "name": "input_set_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587651616,
      "name": "input_set_timestamp",
      "external": true,
      "loc": "drivers/input/input.c:1944",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/input.c:input_get_timestamp",
        "drivers/input/input.c:input_repeat_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587651616,
      "name": "input_set_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void input_set_timestamp(struct input_dev * dev, ktime_t timestamp)
```
</details>
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
