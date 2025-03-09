# Function: <code>palmas_gpio_set</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "palmas_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "palmas_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-palmas.c:69",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
  "name": "palmas_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "palmas_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-palmas.c:69",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
  "name": "palmas_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "palmas_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-palmas.c:69",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
  "name": "palmas_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "palmas_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-palmas.c:69",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void palmas_gpio_set(struct gpio_chip * gc, unsigned int offset, int value)
```

```json
{
  "name": "palmas_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584152800,
      "name": "palmas_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-palmas.c:69",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584152800,
      "name": "palmas_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void palmas_gpio_set(struct gpio_chip * gc, unsigned int offset, int value)
```

```json
{
  "name": "palmas_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584240528,
      "name": "palmas_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-palmas.c:69",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584240528,
      "name": "palmas_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void palmas_gpio_set(struct gpio_chip * gc, unsigned int offset, int value)
```

```json
{
  "name": "palmas_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "palmas_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-palmas.c:58",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584429712,
      "name": "palmas_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071584430489,
      "name": "palmas_gpio_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void palmas_gpio_set(struct gpio_chip * gc, unsigned int offset, int value)
```

```json
{
  "name": "palmas_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "palmas_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-palmas.c:58",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584566496,
      "name": "palmas_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071584567273,
      "name": "palmas_gpio_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void palmas_gpio_set(struct gpio_chip * gc, unsigned int offset, int value)
```

```json
{
  "name": "palmas_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "palmas_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-palmas.c:58",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585240944,
      "name": "palmas_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071585241717,
      "name": "palmas_gpio_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void palmas_gpio_set(struct gpio_chip * gc, unsigned int offset, int value)
```

```json
{
  "name": "palmas_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "palmas_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-palmas.c:58",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585398608,
      "name": "palmas_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071591389940,
      "name": "palmas_gpio_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void palmas_gpio_set(struct gpio_chip * gc, unsigned int offset, int value)
```

```json
{
  "name": "palmas_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "palmas_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-palmas.c:58",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585281312,
      "name": "palmas_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071591332286,
      "name": "palmas_gpio_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
void palmas_gpio_set(struct gpio_chip * gc, unsigned int offset, int value)
```

```json
{
  "name": "palmas_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "palmas_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-palmas.c:58",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585737936,
      "name": "palmas_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071592356095,
      "name": "palmas_gpio_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
void palmas_gpio_set(struct gpio_chip * gc, unsigned int offset, int value)
```

```json
{
  "name": "palmas_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "palmas_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-palmas.c:58",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586920464,
      "name": "palmas_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071594218593,
      "name": "palmas_gpio_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void palmas_gpio_set(struct gpio_chip * gc, unsigned int offset, int value)
```

```json
{
  "name": "palmas_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588075760,
      "name": "palmas_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-palmas.c:58",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588075760,
      "name": "palmas_gpio_set",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void palmas_gpio_set(struct gpio_chip * gc, unsigned int offset, int value)
```

```json
{
  "name": "palmas_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588350288,
      "name": "palmas_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-palmas.c:58",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588350288,
      "name": "palmas_gpio_set",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void palmas_gpio_set(struct gpio_chip * gc, unsigned int offset, int value)
```

```json
{
  "name": "palmas_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588644896,
      "name": "palmas_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-palmas.c:57",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588644896,
      "name": "palmas_gpio_set",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void palmas_gpio_set(struct gpio_chip * gc, unsigned int offset, int value)
```

```json
{
  "name": "palmas_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496786648,
      "name": "palmas_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-palmas.c:58",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496786648,
      "name": "palmas_gpio_set",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void palmas_gpio_set(struct gpio_chip * gc, unsigned int offset, int value)
```

```json
{
  "name": "palmas_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230066076,
      "name": "palmas_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-palmas.c:58",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230066076,
      "name": "palmas_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void palmas_gpio_set(struct gpio_chip * gc, unsigned int offset, int value)
```

```json
{
  "name": "palmas_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290857296,
      "name": "palmas_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-palmas.c:58",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290857296,
      "name": "palmas_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
void palmas_gpio_set(struct gpio_chip * gc, unsigned int offset, int value)
```

```json
{
  "name": "palmas_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275508460,
      "name": "palmas_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-palmas.c:58",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275508460,
      "name": "palmas_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void palmas_gpio_set(struct gpio_chip * gc, unsigned int offset, int value)
```

```json
{
  "name": "palmas_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "palmas_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-palmas.c:58",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584518160,
      "name": "palmas_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071584518937,
      "name": "palmas_gpio_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void palmas_gpio_set(struct gpio_chip * gc, unsigned int offset, int value)
```

```json
{
  "name": "palmas_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "palmas_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-palmas.c:58",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584624432,
      "name": "palmas_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071584625209,
      "name": "palmas_gpio_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
void palmas_gpio_set(struct gpio_chip * gc, unsigned int offset, int value)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void palmas_gpio_set(struct gpio_chip * gc, unsigned int offset, int value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void palmas_gpio_set(struct gpio_chip * gc, unsigned int offset, int value)
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
