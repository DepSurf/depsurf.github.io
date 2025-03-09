# Function: <code>__key_link_lock</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __key_link_lock(struct key * keyring, const struct keyring_index_key * index_key)
```

```json
{
  "name": "__key_link_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583226512,
      "name": "__key_link_lock",
      "external": true,
      "loc": "security/keys/keyring.c:1238",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583226512,
      "name": "__key_link_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int __key_link_lock(struct key * keyring, const struct keyring_index_key * index_key)
```

```json
{
  "name": "__key_link_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583332320,
      "name": "__key_link_lock",
      "external": true,
      "loc": "security/keys/keyring.c:1238",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583332320,
      "name": "__key_link_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int __key_link_lock(struct key * keyring, const struct keyring_index_key * index_key)
```

```json
{
  "name": "__key_link_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583666972,
      "name": "__key_link_lock",
      "external": true,
      "loc": "security/keys/keyring.c:1236",
      "file": "security/keys/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:key_link"
      ],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/request_key.c:construct_alloc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583666064,
      "name": "__key_link_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int __key_link_lock(struct key * keyring, const struct keyring_index_key * index_key)
```

```json
{
  "name": "__key_link_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583788444,
      "name": "__key_link_lock",
      "external": true,
      "loc": "security/keys/keyring.c:1236",
      "file": "security/keys/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:key_link"
      ],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/request_key.c:construct_alloc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583787536,
      "name": "__key_link_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int __key_link_lock(struct key * keyring, const struct keyring_index_key * index_key)
```

```json
{
  "name": "__key_link_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583812572,
      "name": "__key_link_lock",
      "external": true,
      "loc": "security/keys/keyring.c:1236",
      "file": "security/keys/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:key_link"
      ],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/request_key.c:construct_alloc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583811664,
      "name": "__key_link_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int __key_link_lock(struct key * keyring, const struct keyring_index_key * index_key)
```

```json
{
  "name": "__key_link_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584175612,
      "name": "__key_link_lock",
      "external": true,
      "loc": "security/keys/keyring.c:1236",
      "file": "security/keys/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:key_link"
      ],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/request_key.c:construct_alloc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584174704,
      "name": "__key_link_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int __key_link_lock(struct key * keyring, const struct keyring_index_key * index_key)
```

```json
{
  "name": "__key_link_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584775707,
      "name": "__key_link_lock",
      "external": true,
      "loc": "security/keys/keyring.c:1236",
      "file": "security/keys/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:key_link"
      ],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/request_key.c:construct_alloc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584774688,
      "name": "__key_link_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int __key_link_lock(struct key * keyring, const struct keyring_index_key * index_key)
```

```json
{
  "name": "__key_link_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585472235,
      "name": "__key_link_lock",
      "external": true,
      "loc": "security/keys/keyring.c:1236",
      "file": "security/keys/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:key_link"
      ],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/request_key.c:construct_alloc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585471120,
      "name": "__key_link_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int __key_link_lock(struct key * keyring, const struct keyring_index_key * index_key)
```

```json
{
  "name": "__key_link_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585703819,
      "name": "__key_link_lock",
      "external": true,
      "loc": "security/keys/keyring.c:1236",
      "file": "security/keys/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:key_link"
      ],
      "caller_func": [
        "security/keys/key.c:__key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/request_key.c:construct_alloc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585702720,
      "name": "__key_link_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int __key_link_lock(struct key * keyring, const struct keyring_index_key * index_key)
```

```json
{
  "name": "__key_link_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585950859,
      "name": "__key_link_lock",
      "external": true,
      "loc": "security/keys/keyring.c:1236",
      "file": "security/keys/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:key_link"
      ],
      "caller_func": [
        "security/keys/key.c:__key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/request_key.c:construct_alloc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585949760,
      "name": "__key_link_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int __key_link_lock(struct key * keyring, const struct keyring_index_key * index_key)
```

```json
{
  "name": "__key_link_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495075384,
      "name": "__key_link_lock",
      "external": true,
      "loc": "security/keys/keyring.c:1238",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495075384,
      "name": "__key_link_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int __key_link_lock(struct key * keyring, const struct keyring_index_key * index_key)
```

```json
{
  "name": "__key_link_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228470872,
      "name": "__key_link_lock",
      "external": true,
      "loc": "security/keys/keyring.c:1238",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228470872,
      "name": "__key_link_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int __key_link_lock(struct key * keyring, const struct keyring_index_key * index_key)
```

```json
{
  "name": "__key_link_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288972640,
      "name": "__key_link_lock",
      "external": true,
      "loc": "security/keys/keyring.c:1238",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288972640,
      "name": "__key_link_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int __key_link_lock(struct key * keyring, const struct keyring_index_key * index_key)
```

```json
{
  "name": "__key_link_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274342104,
      "name": "__key_link_lock",
      "external": true,
      "loc": "security/keys/keyring.c:1238",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274342104,
      "name": "__key_link_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int __key_link_lock(struct key * keyring, const struct keyring_index_key * index_key)
```

```json
{
  "name": "__key_link_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583301056,
      "name": "__key_link_lock",
      "external": true,
      "loc": "security/keys/keyring.c:1238",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583301056,
      "name": "__key_link_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int __key_link_lock(struct key * keyring, const struct keyring_index_key * index_key)
```

```json
{
  "name": "__key_link_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583238192,
      "name": "__key_link_lock",
      "external": true,
      "loc": "security/keys/keyring.c:1238",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583238192,
      "name": "__key_link_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int __key_link_lock(struct key * keyring, const struct keyring_index_key * index_key)
```

```json
{
  "name": "__key_link_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583285088,
      "name": "__key_link_lock",
      "external": true,
      "loc": "security/keys/keyring.c:1238",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583285088,
      "name": "__key_link_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int __key_link_lock(struct key * keyring, const struct keyring_index_key * index_key)
```

```json
{
  "name": "__key_link_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583379680,
      "name": "__key_link_lock",
      "external": true,
      "loc": "security/keys/keyring.c:1238",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583379680,
      "name": "__key_link_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int __key_link_lock(struct key * keyring, const struct keyring_index_key * index_key)
```
</details>
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
