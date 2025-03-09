# Function: <code>netlbl_domhsh_search_def</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587283936,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:170",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6"
      ],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587283936,
      "name": "netlbl_domhsh_search_def.part.0",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587750992,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:184",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
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
      "addr": 18446744071587750992,
      "name": "netlbl_domhsh_search_def",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587966208,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:184",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
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
      "addr": 18446744071587966208,
      "name": "netlbl_domhsh_search_def",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588124336,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:184",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
      "addr": 18446744071588124336,
      "name": "netlbl_domhsh_search_def",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588672160,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:184",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
      "addr": 18446744071588672160,
      "name": "netlbl_domhsh_search_def",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589038688,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:184",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
      "addr": 18446744071589038688,
      "name": "netlbl_domhsh_search_def",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589264688,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:184",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
      "addr": 18446744071589264688,
      "name": "netlbl_domhsh_search_def",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589719968,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:170",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
      "addr": 18446744071589719968,
      "name": "netlbl_domhsh_search_def",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589944272,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:170",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
      "addr": 18446744071589944272,
      "name": "netlbl_domhsh_search_def",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590977701,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:172",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_default",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590974288,
      "name": "netlbl_domhsh_search_def",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591042325,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:172",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591039072,
      "name": "netlbl_domhsh_search_def",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590972917,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:172",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590969648,
      "name": "netlbl_domhsh_search_def",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591810453,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:172",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591807184,
      "name": "netlbl_domhsh_search_def",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593522597,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:172",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593518992,
      "name": "netlbl_domhsh_search_def",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595442869,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:172",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595439088,
      "name": "netlbl_domhsh_search_def",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595949829,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:172",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595946064,
      "name": "netlbl_domhsh_search_def",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596811701,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:172",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596807888,
      "name": "netlbl_domhsh_search_def",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503675520,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:170",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
      "addr": 18446603336503675520,
      "name": "netlbl_domhsh_search_def",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236312428,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:170",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
      "addr": 3236312428,
      "name": "netlbl_domhsh_search_def",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297506368,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:170",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6"
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
      "addr": 13835058055297501216,
      "name": "netlbl_domhsh_search_def.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 13835058055297501280,
      "name": "netlbl_domhsh_search_def",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279615404,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:170",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_getentry_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6"
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
      "addr": 18446743936279611932,
      "name": "netlbl_domhsh_search_def.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446743936279611980,
      "name": "netlbl_domhsh_search_def",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589547872,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:170",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
      "addr": 18446744071589547872,
      "name": "netlbl_domhsh_search_def",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589272448,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:170",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
      "addr": 18446744071589272448,
      "name": "netlbl_domhsh_search_def",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589989904,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:170",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
      "addr": 18446744071589989904,
      "name": "netlbl_domhsh_search_def",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```

```json
{
  "name": "netlbl_domhsh_search_def",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590039792,
      "name": "netlbl_domhsh_search_def",
      "external": false,
      "loc": "net/netlabel/netlabel_domainhash.c:170",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
      "addr": 18446744071590039792,
      "name": "netlbl_domhsh_search_def",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct netlbl_dom_map * netlbl_domhsh_search_def(const char * domain, u16 family)
```
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
