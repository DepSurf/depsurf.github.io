# Function: <code>__key_link_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582194048,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1071",
      "file": "security/keys/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582194048,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582410528,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1095",
      "file": "security/keys/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582410528,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582502720,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1095",
      "file": "security/keys/keyring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582502720,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582583984,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1207",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582583984,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582737056,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1209",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582737056,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582935712,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1202",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582935712,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583044256,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1200",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583044256,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583226784,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1294",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583226784,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583332592,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1294",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583332592,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583666336,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1292",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_alloc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583666336,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583787808,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1292",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_alloc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583787808,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583811936,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1292",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_alloc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583811936,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584174976,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1292",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_alloc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584174976,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584774992,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1292",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_alloc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584774992,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585471456,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1292",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_alloc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585471456,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585703040,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1292",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:__key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_alloc_key",
        "security/keys/request_key.c:construct_alloc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585703040,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585950080,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1292",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:__key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_alloc_key",
        "security/keys/request_key.c:construct_alloc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585950080,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495075728,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1294",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495075728,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228471128,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1294",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228471128,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288973120,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1294",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288973120,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274342396,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1294",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274342396,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583301328,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1294",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583301328,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583238464,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1294",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583238464,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583285360,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1294",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583285360,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int __key_link_begin(struct key * keyring, const struct keyring_index_key * index_key, struct assoc_array_edit * * _edit)
```

```json
{
  "name": "__key_link_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583379952,
      "name": "__key_link_begin",
      "external": true,
      "loc": "security/keys/keyring.c:1294",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:key_instantiate_and_link",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_link",
        "security/keys/request_key.c:construct_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583379952,
      "name": "__key_link_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
