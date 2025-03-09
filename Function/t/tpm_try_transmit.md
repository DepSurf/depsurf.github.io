# Function: <code>tpm_try_transmit</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_try_transmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585493611,
      "name": "tpm_try_transmit",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:429",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
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
  "name": "tpm_try_transmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585621439,
      "name": "tpm_try_transmit",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:164",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_try_transmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585842046,
      "name": "tpm_try_transmit",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:60",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_try_transmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585984734,
      "name": "tpm_try_transmit",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:60",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t tpm_try_transmit(struct tpm_chip * chip, void * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_try_transmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_try_transmit",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:61",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586725568,
      "name": "tpm_try_transmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
    },
    {
      "addr": 18446744071586726943,
      "name": "tpm_try_transmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
ssize_t tpm_try_transmit(struct tpm_chip * chip, void * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_try_transmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_try_transmit",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:61",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586821136,
      "name": "tpm_try_transmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
    },
    {
      "addr": 18446744071591469948,
      "name": "tpm_try_transmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
ssize_t tpm_try_transmit(struct tpm_chip * chip, void * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_try_transmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_try_transmit",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:61",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586701136,
      "name": "tpm_try_transmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
    },
    {
      "addr": 18446744071591411215,
      "name": "tpm_try_transmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
ssize_t tpm_try_transmit(struct tpm_chip * chip, void * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_try_transmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_try_transmit",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:61",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587250496,
      "name": "tpm_try_transmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    },
    {
      "addr": 18446744071592463049,
      "name": "tpm_try_transmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
ssize_t tpm_try_transmit(struct tpm_chip * chip, void * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_try_transmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_try_transmit",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:61",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588559472,
      "name": "tpm_try_transmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
    },
    {
      "addr": 18446744071594332844,
      "name": "tpm_try_transmit.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
ssize_t tpm_try_transmit(struct tpm_chip * chip, void * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_try_transmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590012320,
      "name": "tpm_try_transmit",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:61",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590012320,
      "name": "tpm_try_transmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
ssize_t tpm_try_transmit(struct tpm_chip * chip, void * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_try_transmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590321648,
      "name": "tpm_try_transmit",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:61",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590321648,
      "name": "tpm_try_transmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
ssize_t tpm_try_transmit(struct tpm_chip * chip, void * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_try_transmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590663040,
      "name": "tpm_try_transmit",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:61",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590663040,
      "name": "tpm_try_transmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
  "name": "tpm_try_transmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498779916,
      "name": "tpm_try_transmit",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:60",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
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
  "name": "tpm_try_transmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231394600,
      "name": "tpm_try_transmit",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:60",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "tpm_try_transmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291971188,
      "name": "tpm_try_transmit",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:60",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_try_transmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276273922,
      "name": "tpm_try_transmit",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:60",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_try_transmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585745710,
      "name": "tpm_try_transmit",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:60",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_try_transmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585604894,
      "name": "tpm_try_transmit",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:60",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_try_transmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585934750,
      "name": "tpm_try_transmit",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:60",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_try_transmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586042734,
      "name": "tpm_try_transmit",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:60",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
ssize_t tpm_try_transmit(struct tpm_chip * chip, void * buf, size_t bufsiz)
```
</details>
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
