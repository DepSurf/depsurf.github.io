# Function: <code>unwind_dump</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unwind_dump",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579278530,
      "name": "unwind_dump",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:24",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/unwind_frame.c:unwind_next_frame"
      ],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:unwind_next_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579278080,
      "name": "unwind_dump.isra.4.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
void unwind_dump(struct unwind_state * state)
```

```json
{
  "name": "unwind_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274352,
      "name": "unwind_dump",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:28",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274352,
      "name": "unwind_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
void unwind_dump(struct unwind_state * state)
```

```json
{
  "name": "unwind_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579292912,
      "name": "unwind_dump",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:30",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579292912,
      "name": "unwind_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void unwind_dump(struct unwind_state * state)
```

```json
{
  "name": "unwind_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unwind_dump",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:30",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304912,
      "name": "unwind_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071579306220,
      "name": "unwind_dump.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void unwind_dump(struct unwind_state * state)
```

```json
{
  "name": "unwind_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unwind_dump",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:30",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329440,
      "name": "unwind_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    },
    {
      "addr": 18446744071579330812,
      "name": "unwind_dump.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void unwind_dump(struct unwind_state * state)
```

```json
{
  "name": "unwind_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unwind_dump",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:31",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579344736,
      "name": "unwind_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071579346076,
      "name": "unwind_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void unwind_dump(struct unwind_state * state)
```

```json
{
  "name": "unwind_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unwind_dump",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:31",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579349072,
      "name": "unwind_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071579350412,
      "name": "unwind_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void unwind_dump(struct unwind_state * state)
```

```json
{
  "name": "unwind_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unwind_dump",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:31",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579378784,
      "name": "unwind_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071579380140,
      "name": "unwind_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void unwind_dump(struct unwind_state * state)
```

```json
{
  "name": "unwind_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unwind_dump",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:31",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579377424,
      "name": "unwind_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071591265131,
      "name": "unwind_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void unwind_dump(struct unwind_state * state)
```

```json
{
  "name": "unwind_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unwind_dump",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:31",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579381040,
      "name": "unwind_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071591207336,
      "name": "unwind_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void unwind_dump(struct unwind_state * state)
```

```json
{
  "name": "unwind_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unwind_dump",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:31",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579443040,
      "name": "unwind_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071592080655,
      "name": "unwind_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
void unwind_dump(struct unwind_state * state)
```

```json
{
  "name": "unwind_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unwind_dump",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:31",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:unwind_next_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513328,
      "name": "unwind_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071593847994,
      "name": "unwind_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void unwind_dump(struct unwind_state * state)
```

```json
{
  "name": "unwind_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unwind_dump",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:31",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:unwind_next_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611984,
      "name": "unwind_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071595967934,
      "name": "unwind_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void unwind_dump(struct unwind_state * state)
```

```json
{
  "name": "unwind_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unwind_dump",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:31",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:unwind_next_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579624592,
      "name": "unwind_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071596485551,
      "name": "unwind_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void unwind_dump(struct unwind_state * state)
```

```json
{
  "name": "unwind_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unwind_dump",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:31",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/unwind_frame.c:unwind_next_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653648,
      "name": "unwind_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071597382161,
      "name": "unwind_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void unwind_dump(struct unwind_state * state)
```

```json
{
  "name": "unwind_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unwind_dump",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:31",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579344976,
      "name": "unwind_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071579346316,
      "name": "unwind_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void unwind_dump(struct unwind_state * state)
```

```json
{
  "name": "unwind_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unwind_dump",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:31",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579277184,
      "name": "unwind_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071579278524,
      "name": "unwind_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void unwind_dump(struct unwind_state * state)
```

```json
{
  "name": "unwind_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unwind_dump",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:31",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579344896,
      "name": "unwind_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071579346236,
      "name": "unwind_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void unwind_dump(struct unwind_state * state)
```

```json
{
  "name": "unwind_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unwind_dump",
      "external": false,
      "loc": "arch/x86/kernel/unwind_frame.c:31",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579353344,
      "name": "unwind_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071579354684,
      "name": "unwind_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void unwind_dump(struct unwind_state * state)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void unwind_dump(struct unwind_state * state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void unwind_dump(struct unwind_state * state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void unwind_dump(struct unwind_state * state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void unwind_dump(struct unwind_state * state)
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
