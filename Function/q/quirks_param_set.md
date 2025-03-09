# Function: <code>quirks_param_set</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int quirks_param_set(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "quirks_param_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586369760,
      "name": "quirks_param_set",
      "external": false,
      "loc": "drivers/usb/core/quirks.c:28",
      "file": "drivers/usb/core/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586369760,
      "name": "quirks_param_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 688
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
int quirks_param_set(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "quirks_param_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586627392,
      "name": "quirks_param_set",
      "external": false,
      "loc": "drivers/usb/core/quirks.c:28",
      "file": "drivers/usb/core/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586627392,
      "name": "quirks_param_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
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
int quirks_param_set(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "quirks_param_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586776336,
      "name": "quirks_param_set",
      "external": false,
      "loc": "drivers/usb/core/quirks.c:28",
      "file": "drivers/usb/core/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586776336,
      "name": "quirks_param_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 793
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int quirks_param_set(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "quirks_param_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587032496,
      "name": "quirks_param_set",
      "external": false,
      "loc": "drivers/usb/core/quirks.c:28",
      "file": "drivers/usb/core/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587032496,
      "name": "quirks_param_set.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 802
    },
    {
      "addr": 18446744071587033312,
      "name": "quirks_param_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int quirks_param_set(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "quirks_param_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587232704,
      "name": "quirks_param_set",
      "external": false,
      "loc": "drivers/usb/core/quirks.c:28",
      "file": "drivers/usb/core/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587232704,
      "name": "quirks_param_set.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 802
    },
    {
      "addr": 18446744071587233520,
      "name": "quirks_param_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int quirks_param_set(const char * value, const struct kernel_param * kp)
```

```json
{
  "name": "quirks_param_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588086400,
      "name": "quirks_param_set",
      "external": false,
      "loc": "drivers/usb/core/quirks.c:28",
      "file": "drivers/usb/core/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588086400,
      "name": "quirks_param_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
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
int quirks_param_set(const char * value, const struct kernel_param * kp)
```

```json
{
  "name": "quirks_param_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588128480,
      "name": "quirks_param_set",
      "external": false,
      "loc": "drivers/usb/core/quirks.c:28",
      "file": "drivers/usb/core/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588128480,
      "name": "quirks_param_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
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
int quirks_param_set(const char * value, const struct kernel_param * kp)
```

```json
{
  "name": "quirks_param_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588010816,
      "name": "quirks_param_set",
      "external": false,
      "loc": "drivers/usb/core/quirks.c:28",
      "file": "drivers/usb/core/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588010816,
      "name": "quirks_param_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 862
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
int quirks_param_set(const char * value, const struct kernel_param * kp)
```

```json
{
  "name": "quirks_param_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588626080,
      "name": "quirks_param_set",
      "external": false,
      "loc": "drivers/usb/core/quirks.c:28",
      "file": "drivers/usb/core/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588626080,
      "name": "quirks_param_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 862
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
int quirks_param_set(const char * value, const struct kernel_param * kp)
```

```json
{
  "name": "quirks_param_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590041488,
      "name": "quirks_param_set",
      "external": false,
      "loc": "drivers/usb/core/quirks.c:28",
      "file": "drivers/usb/core/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590041488,
      "name": "quirks_param_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 872
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
int quirks_param_set(const char * value, const struct kernel_param * kp)
```

```json
{
  "name": "quirks_param_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591645520,
      "name": "quirks_param_set",
      "external": false,
      "loc": "drivers/usb/core/quirks.c:28",
      "file": "drivers/usb/core/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591645520,
      "name": "quirks_param_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 872
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
int quirks_param_set(const char * value, const struct kernel_param * kp)
```

```json
{
  "name": "quirks_param_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592068208,
      "name": "quirks_param_set",
      "external": false,
      "loc": "drivers/usb/core/quirks.c:28",
      "file": "drivers/usb/core/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592068208,
      "name": "quirks_param_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 868
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
int quirks_param_set(const char * value, const struct kernel_param * kp)
```

```json
{
  "name": "quirks_param_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592808464,
      "name": "quirks_param_set",
      "external": false,
      "loc": "drivers/usb/core/quirks.c:28",
      "file": "drivers/usb/core/quirks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592808464,
      "name": "quirks_param_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int quirks_param_set(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "quirks_param_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500328952,
      "name": "quirks_param_set",
      "external": false,
      "loc": "drivers/usb/core/quirks.c:28",
      "file": "drivers/usb/core/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500328952,
      "name": "quirks_param_set.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 752
    },
    {
      "addr": 18446603336500329704,
      "name": "quirks_param_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
int quirks_param_set(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "quirks_param_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232789148,
      "name": "quirks_param_set",
      "external": false,
      "loc": "drivers/usb/core/quirks.c:28",
      "file": "drivers/usb/core/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3232789148,
      "name": "quirks_param_set.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 732
    },
    {
      "addr": 3232789880,
      "name": "quirks_param_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int quirks_param_set(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "quirks_param_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293636688,
      "name": "quirks_param_set",
      "external": false,
      "loc": "drivers/usb/core/quirks.c:28",
      "file": "drivers/usb/core/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293636688,
      "name": "quirks_param_set.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1060
    },
    {
      "addr": 13835058055293637760,
      "name": "quirks_param_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int quirks_param_set(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "quirks_param_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277223250,
      "name": "quirks_param_set",
      "external": false,
      "loc": "drivers/usb/core/quirks.c:28",
      "file": "drivers/usb/core/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277223250,
      "name": "quirks_param_set.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
    },
    {
      "addr": 18446743936277223828,
      "name": "quirks_param_set",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int quirks_param_set(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "quirks_param_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586938784,
      "name": "quirks_param_set",
      "external": false,
      "loc": "drivers/usb/core/quirks.c:28",
      "file": "drivers/usb/core/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586938784,
      "name": "quirks_param_set.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 802
    },
    {
      "addr": 18446744071586939600,
      "name": "quirks_param_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int quirks_param_set(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "quirks_param_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586879952,
      "name": "quirks_param_set",
      "external": false,
      "loc": "drivers/usb/core/quirks.c:28",
      "file": "drivers/usb/core/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586879952,
      "name": "quirks_param_set.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 802
    },
    {
      "addr": 18446744071586880768,
      "name": "quirks_param_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int quirks_param_set(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "quirks_param_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587187264,
      "name": "quirks_param_set",
      "external": false,
      "loc": "drivers/usb/core/quirks.c:28",
      "file": "drivers/usb/core/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587187264,
      "name": "quirks_param_set.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 802
    },
    {
      "addr": 18446744071587188080,
      "name": "quirks_param_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int quirks_param_set(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "quirks_param_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587294336,
      "name": "quirks_param_set",
      "external": false,
      "loc": "drivers/usb/core/quirks.c:28",
      "file": "drivers/usb/core/quirks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587294336,
      "name": "quirks_param_set.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 802
    },
    {
      "addr": 18446744071587295152,
      "name": "quirks_param_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int quirks_param_set(const char * val, const struct kernel_param * kp)
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char * value</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * val</code>
</li>
</ul>
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
