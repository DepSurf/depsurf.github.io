# Function: <code>tnode_new</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586839376,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:350",
      "file": "net/ipv4/fib_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:fib_insert_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586839376,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587288848,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:348",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_alias",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587288848,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587490688,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:475",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_alias",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587490688,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587627216,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:380",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_alias",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587627216,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588151632,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:381",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_alias",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588151632,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588506000,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:382",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_alias",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588506000,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588701056,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:382",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_alias",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588701056,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589119008,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:378",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_alias",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589119008,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589343104,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:378",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_alias",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589343104,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590319808,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:375",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_node",
        "net/ipv4/fib_trie.c:halve",
        "net/ipv4/fib_trie.c:halve",
        "net/ipv4/fib_trie.c:inflate",
        "net/ipv4/fib_trie.c:inflate",
        "net/ipv4/fib_trie.c:inflate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590319808,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590373184,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:375",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_node",
        "net/ipv4/fib_trie.c:halve",
        "net/ipv4/fib_trie.c:halve",
        "net/ipv4/fib_trie.c:inflate",
        "net/ipv4/fib_trie.c:inflate",
        "net/ipv4/fib_trie.c:inflate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590373184,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590288448,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:375",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_alias",
        "net/ipv4/fib_trie.c:halve",
        "net/ipv4/fib_trie.c:halve",
        "net/ipv4/fib_trie.c:inflate",
        "net/ipv4/fib_trie.c:inflate",
        "net/ipv4/fib_trie.c:inflate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590288448,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:375",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_alias",
        "net/ipv4/fib_trie.c:halve",
        "net/ipv4/fib_trie.c:halve",
        "net/ipv4/fib_trie.c:inflate",
        "net/ipv4/fib_trie.c:inflate",
        "net/ipv4/fib_trie.c:inflate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591075280,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    },
    {
      "addr": 18446744071592727384,
      "name": "tnode_new.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:376",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_alias",
        "net/ipv4/fib_trie.c:halve",
        "net/ipv4/fib_trie.c:halve",
        "net/ipv4/fib_trie.c:inflate",
        "net/ipv4/fib_trie.c:inflate",
        "net/ipv4/fib_trie.c:inflate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592724880,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    },
    {
      "addr": 18446744071594613615,
      "name": "tnode_new.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:376",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_alias",
        "net/ipv4/fib_trie.c:halve",
        "net/ipv4/fib_trie.c:halve",
        "net/ipv4/fib_trie.c:inflate",
        "net/ipv4/fib_trie.c:inflate",
        "net/ipv4/fib_trie.c:inflate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594595392,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071596348490,
      "name": "tnode_new.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:376",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_alias",
        "net/ipv4/fib_trie.c:halve",
        "net/ipv4/fib_trie.c:halve",
        "net/ipv4/fib_trie.c:inflate",
        "net/ipv4/fib_trie.c:inflate",
        "net/ipv4/fib_trie.c:inflate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594987152,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071596877514,
      "name": "tnode_new.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:377",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_alias",
        "net/ipv4/fib_trie.c:halve",
        "net/ipv4/fib_trie.c:halve",
        "net/ipv4/fib_trie.c:inflate",
        "net/ipv4/fib_trie.c:inflate",
        "net/ipv4/fib_trie.c:inflate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595799648,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071597801608,
      "name": "tnode_new.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502983040,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:378",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_alias",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502983040,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235672496,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:378",
      "file": "net/ipv4/fib_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_alias",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235672496,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296668512,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:378",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_alias",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296668512,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279060362,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:378",
      "file": "net/ipv4/fib_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_alias",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279060362,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588949280,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:378",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_alias",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588949280,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588661216,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:378",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_alias",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588661216,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589385664,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:378",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_alias",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589385664,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
struct key_vector * tnode_new(t_key key, int pos, int bits)
```

```json
{
  "name": "tnode_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589428688,
      "name": "tnode_new",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:378",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_insert_alias",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589428688,
      "name": "tnode_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
