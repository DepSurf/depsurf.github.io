# Function: <code>format_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t format_flags(const struct net_device * dev, char * buf)
```

```json
{
  "name": "format_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586403888,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:318",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586403888,
      "name": "format_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
char * format_flags(char * buf, char * end, long unsigned int flags, const struct trace_print_flags * names)
```

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583276472,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1408",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:flags_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586846592,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:321",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586846592,
      "name": "format_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
char * format_flags(char * buf, char * end, long unsigned int flags, const struct trace_print_flags * names)
```

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583395224,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1408",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:flags_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587037344,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:321",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587037344,
      "name": "format_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t format_flags(const struct net_device * dev, char * buf)
```

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587165344,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:322",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588251176,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1409",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:flags_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587165344,
      "name": "format_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t format_flags(const struct net_device * dev, char * buf)
```

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587670592,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:326",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588802792,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1464",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:flags_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587670592,
      "name": "format_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t format_flags(const struct net_device * dev, char * buf)
```

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588000480,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:347",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1483",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:flags_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588000480,
      "name": "format_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t format_flags(const struct net_device * dev, char * buf)
```

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588160464,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:348",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1667",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:flags_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588160464,
      "name": "format_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t format_flags(const struct net_device * dev, char * buf)
```

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588485568,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:343",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589866623,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1808",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:flags_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588485568,
      "name": "format_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t format_flags(const struct net_device * dev, char * buf)
```

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588693248,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:343",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590092431,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1817",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:flags_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588693248,
      "name": "format_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1889",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:flags_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589564340,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:355",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:flags_show"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1893",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:flags_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589571492,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:356",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:flags_show"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
char * format_flags(char * buf, char * end, long unsigned int flags, const struct trace_print_flags * names)
```

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585128832,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1955",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:flags_string"
      ]
    },
    {
      "addr": 18446744071589471492,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:356",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:flags_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585128832,
      "name": "format_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
char * format_flags(char * buf, char * end, long unsigned int flags, const struct trace_print_flags * names)
```

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585578576,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1972",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:flags_string"
      ]
    },
    {
      "addr": 18446744071590208676,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:376",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:flags_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585578576,
      "name": "format_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
char * format_flags(char * buf, char * end, long unsigned int flags, const struct trace_print_flags * names)
```

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586733760,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1960",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:flags_string"
      ]
    },
    {
      "addr": 18446744071591782676,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:378",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:flags_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586733760,
      "name": "format_flags",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t format_flags(const struct net_device * dev, char * buf)
```

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593576612,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:378",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:flags_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595896672,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1961",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:flags_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595896672,
      "name": "format_flags",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t format_flags(const struct net_device * dev, char * buf)
```

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594047732,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:378",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:flags_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596414208,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1961",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:flags_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596414208,
      "name": "format_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t format_flags(const struct net_device * dev, char * buf)
```

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594838132,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:390",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:flags_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597309488,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1963",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:flags_string",
        "lib/vsprintf.c:flags_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597309488,
      "name": "format_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t format_flags(const struct net_device * dev, char * buf)
```

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502251352,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:343",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503871044,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1817",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:flags_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502251352,
      "name": "format_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t format_flags(const struct net_device * dev, char * buf)
```

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234995856,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:343",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236502904,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1817",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:flags_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234995856,
      "name": "format_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t format_flags(const struct net_device * dev, char * buf)
```

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295744448,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:343",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297732636,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1817",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:flags_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295744448,
      "name": "format_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t format_flags(const struct net_device * dev, char * buf)
```

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278490156,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:343",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279766284,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1817",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:flags_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278490156,
      "name": "format_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t format_flags(const struct net_device * dev, char * buf)
```

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588299984,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:343",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589694687,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1817",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:flags_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588299984,
      "name": "format_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t format_flags(const struct net_device * dev, char * buf)
```

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588012800,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:343",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589420479,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1817",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:flags_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588012800,
      "name": "format_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t format_flags(const struct net_device * dev, char * buf)
```

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588631808,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:343",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590138063,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1817",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:flags_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588631808,
      "name": "format_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t format_flags(const struct net_device * dev, char * buf)
```

```json
{
  "name": "format_flags",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588771200,
      "name": "format_flags",
      "external": false,
      "loc": "net/core/net-sysfs.c:343",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590188447,
      "name": "format_flags",
      "external": false,
      "loc": "lib/vsprintf.c:1817",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:flags_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588771200,
      "name": "format_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>char * end</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Param added. </b>
<code>const struct trace_print_flags * names</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct net_device * dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, buf</code> ➡️ <code>buf, end, flags, names</code>
</li>
<li>
<b>Return type changed. </b>
<code>ssize_t</code> ➡️ <code>char *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct net_device * dev</code>
</li>
<li>
<b>Param removed. </b>
<code>char * end</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct trace_print_flags * names</code>
</li>
<li>
<b>Param reordered. </b>
<code>buf, end, flags, names</code> ➡️ <code>dev, buf</code>
</li>
<li>
<b>Return type changed. </b>
<code>char *</code> ➡️ <code>ssize_t</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
ssize_t format_flags(const struct net_device * dev, char * buf)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
char * format_flags(char * buf, char * end, long unsigned int flags, const struct trace_print_flags * names)
```
</details>
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
<b>Param added. </b>
<code>const struct net_device * dev</code>
</li>
<li>
<b>Param removed. </b>
<code>char * end</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct trace_print_flags * names</code>
</li>
<li>
<b>Param reordered. </b>
<code>buf, end, flags, names</code> ➡️ <code>dev, buf</code>
</li>
<li>
<b>Return type changed. </b>
<code>char *</code> ➡️ <code>ssize_t</code>
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
