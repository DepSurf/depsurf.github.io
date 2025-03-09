# Function: <code>netlbl_domhsh_search</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587283536,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:140",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587283536,
      "name": "netlbl_domhsh_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587750464,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:150",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587750464,
      "name": "netlbl_domhsh_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587965680,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:150",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587965680,
      "name": "netlbl_domhsh_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588123808,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:150",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588123808,
      "name": "netlbl_domhsh_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588671632,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:150",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588671632,
      "name": "netlbl_domhsh_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589038192,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:150",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589038192,
      "name": "netlbl_domhsh_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589264192,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:150",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589264192,
      "name": "netlbl_domhsh_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589719472,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:136",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589719472,
      "name": "netlbl_domhsh_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589943776,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:136",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589943776,
      "name": "netlbl_domhsh_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590977347,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:137",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590973792,
      "name": "netlbl_domhsh_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591042046,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:137",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591038576,
      "name": "netlbl_domhsh_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590972638,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:137",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590969152,
      "name": "netlbl_domhsh_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591810174,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:137",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591806688,
      "name": "netlbl_domhsh_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593522246,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:137",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593518448,
      "name": "netlbl_domhsh_search",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595442454,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:137",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595438512,
      "name": "netlbl_domhsh_search",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595949414,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:137",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595945488,
      "name": "netlbl_domhsh_search",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596811286,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:137",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596807312,
      "name": "netlbl_domhsh_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503674864,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:136",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503674864,
      "name": "netlbl_domhsh_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236311864,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:136",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236311864,
      "name": "netlbl_domhsh_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297506056,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:136",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6"
      ],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297499936,
      "name": "netlbl_domhsh_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
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
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279615158,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:136",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6"
      ],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279611318,
      "name": "netlbl_domhsh_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589547376,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:136",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589547376,
      "name": "netlbl_domhsh_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589271952,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:136",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589271952,
      "name": "netlbl_domhsh_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589989408,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:136",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589989408,
      "name": "netlbl_domhsh_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
struct netlbl_dom_map * netlbl_domhsh_search(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590039296,
      "name": "netlbl_domhsh_search",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:136",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590039296,
      "name": "netlbl_domhsh_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
<code>u16 family</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
