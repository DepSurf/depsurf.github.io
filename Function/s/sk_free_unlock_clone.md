# Function: <code>sk_free_unlock_clone</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void sk_free_unlock_clone(struct sock * sk)
```

```json
{
  "name": "sk_free_unlock_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586927616,
      "name": "sk_free_unlock_clone",
      "external": true,
      "loc": "net/core/sock.c:1740",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586927616,
      "name": "sk_free_unlock_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void sk_free_unlock_clone(struct sock * sk)
```

```json
{
  "name": "sk_free_unlock_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587420288,
      "name": "sk_free_unlock_clone",
      "external": true,
      "loc": "net/core/sock.c:1751",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587420288,
      "name": "sk_free_unlock_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void sk_free_unlock_clone(struct sock * sk)
```

```json
{
  "name": "sk_free_unlock_clone",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587725047,
      "name": "sk_free_unlock_clone",
      "external": true,
      "loc": "net/core/sock.c:1771",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587724320,
      "name": "sk_free_unlock_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void sk_free_unlock_clone(struct sock * sk)
```

```json
{
  "name": "sk_free_unlock_clone",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587857367,
      "name": "sk_free_unlock_clone",
      "external": true,
      "loc": "net/core/sock.c:1767",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587856640,
      "name": "sk_free_unlock_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void sk_free_unlock_clone(struct sock * sk)
```

```json
{
  "name": "sk_free_unlock_clone",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588161899,
      "name": "sk_free_unlock_clone",
      "external": true,
      "loc": "net/core/sock.c:1899",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588161120,
      "name": "sk_free_unlock_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void sk_free_unlock_clone(struct sock * sk)
```

```json
{
  "name": "sk_free_unlock_clone",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588367167,
      "name": "sk_free_unlock_clone",
      "external": true,
      "loc": "net/core/sock.c:1912",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588366384,
      "name": "sk_free_unlock_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void sk_free_unlock_clone(struct sock * sk)
```

```json
{
  "name": "sk_free_unlock_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589226368,
      "name": "sk_free_unlock_clone",
      "external": true,
      "loc": "net/core/sock.c:2009",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589226368,
      "name": "sk_free_unlock_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void sk_free_unlock_clone(struct sock * sk)
```

```json
{
  "name": "sk_free_unlock_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589223888,
      "name": "sk_free_unlock_clone",
      "external": true,
      "loc": "net/core/sock.c:2001",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589223888,
      "name": "sk_free_unlock_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void sk_free_unlock_clone(struct sock * sk)
```

```json
{
  "name": "sk_free_unlock_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589118880,
      "name": "sk_free_unlock_clone",
      "external": true,
      "loc": "net/core/sock.c:2030",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589118880,
      "name": "sk_free_unlock_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void sk_free_unlock_clone(struct sock * sk)
```

```json
{
  "name": "sk_free_unlock_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589837296,
      "name": "sk_free_unlock_clone",
      "external": true,
      "loc": "net/core/sock.c:2154",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589837296,
      "name": "sk_free_unlock_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void sk_free_unlock_clone(struct sock * sk)
```

```json
{
  "name": "sk_free_unlock_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591360416,
      "name": "sk_free_unlock_clone",
      "external": true,
      "loc": "net/core/sock.c:2289",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591360416,
      "name": "sk_free_unlock_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void sk_free_unlock_clone(struct sock * sk)
```

```json
{
  "name": "sk_free_unlock_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593117488,
      "name": "sk_free_unlock_clone",
      "external": true,
      "loc": "net/core/sock.c:2368",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593117488,
      "name": "sk_free_unlock_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void sk_free_unlock_clone(struct sock * sk)
```

```json
{
  "name": "sk_free_unlock_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593570192,
      "name": "sk_free_unlock_clone",
      "external": true,
      "loc": "net/core/sock.c:2415",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593570192,
      "name": "sk_free_unlock_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void sk_free_unlock_clone(struct sock * sk)
```

```json
{
  "name": "sk_free_unlock_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594342784,
      "name": "sk_free_unlock_clone",
      "external": true,
      "loc": "net/core/sock.c:2395",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594342784,
      "name": "sk_free_unlock_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void sk_free_unlock_clone(struct sock * sk)
```

```json
{
  "name": "sk_free_unlock_clone",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501876876,
      "name": "sk_free_unlock_clone",
      "external": true,
      "loc": "net/core/sock.c:1912",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501876360,
      "name": "sk_free_unlock_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void sk_free_unlock_clone(struct sock * sk)
```

```json
{
  "name": "sk_free_unlock_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234640468,
      "name": "sk_free_unlock_clone",
      "external": true,
      "loc": "net/core/sock.c:1912",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234640468,
      "name": "sk_free_unlock_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void sk_free_unlock_clone(struct sock * sk)
```

```json
{
  "name": "sk_free_unlock_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295282992,
      "name": "sk_free_unlock_clone",
      "external": true,
      "loc": "net/core/sock.c:1912",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295282992,
      "name": "sk_free_unlock_clone",
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
void sk_free_unlock_clone(struct sock * sk)
```

```json
{
  "name": "sk_free_unlock_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278198396,
      "name": "sk_free_unlock_clone",
      "external": true,
      "loc": "net/core/sock.c:1912",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278198396,
      "name": "sk_free_unlock_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void sk_free_unlock_clone(struct sock * sk)
```

```json
{
  "name": "sk_free_unlock_clone",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587973951,
      "name": "sk_free_unlock_clone",
      "external": true,
      "loc": "net/core/sock.c:1912",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587973168,
      "name": "sk_free_unlock_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void sk_free_unlock_clone(struct sock * sk)
```

```json
{
  "name": "sk_free_unlock_clone",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587687055,
      "name": "sk_free_unlock_clone",
      "external": true,
      "loc": "net/core/sock.c:1912",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587686272,
      "name": "sk_free_unlock_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void sk_free_unlock_clone(struct sock * sk)
```

```json
{
  "name": "sk_free_unlock_clone",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588305727,
      "name": "sk_free_unlock_clone",
      "external": true,
      "loc": "net/core/sock.c:1912",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588304944,
      "name": "sk_free_unlock_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void sk_free_unlock_clone(struct sock * sk)
```

```json
{
  "name": "sk_free_unlock_clone",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588440943,
      "name": "sk_free_unlock_clone",
      "external": true,
      "loc": "net/core/sock.c:1912",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_clone_lock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588440128,
      "name": "sk_free_unlock_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void sk_free_unlock_clone(struct sock * sk)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
