# Function: <code>search_process_keyrings_rcu</code>

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
key_ref_t search_process_keyrings_rcu(struct keyring_search_context * ctx)
```

```json
{
  "name": "search_process_keyrings_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583240192,
      "name": "search_process_keyrings_rcu",
      "external": true,
      "loc": "security/keys/process_keys.c:539",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key_auth.c:key_get_instantiation_authkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583240192,
      "name": "search_process_keyrings_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
key_ref_t search_process_keyrings_rcu(struct keyring_search_context * ctx)
```

```json
{
  "name": "search_process_keyrings_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583346016,
      "name": "search_process_keyrings_rcu",
      "external": true,
      "loc": "security/keys/process_keys.c:539",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key_auth.c:key_get_instantiation_authkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583346016,
      "name": "search_process_keyrings_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
key_ref_t search_process_keyrings_rcu(struct keyring_search_context * ctx)
```

```json
{
  "name": "search_process_keyrings_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583680848,
      "name": "search_process_keyrings_rcu",
      "external": true,
      "loc": "security/keys/process_keys.c:539",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_alloc_key",
        "security/keys/request_key_auth.c:key_get_instantiation_authkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583680848,
      "name": "search_process_keyrings_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
key_ref_t search_process_keyrings_rcu(struct keyring_search_context * ctx)
```

```json
{
  "name": "search_process_keyrings_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583802352,
      "name": "search_process_keyrings_rcu",
      "external": true,
      "loc": "security/keys/process_keys.c:539",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_alloc_key",
        "security/keys/request_key_auth.c:key_get_instantiation_authkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583802352,
      "name": "search_process_keyrings_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
key_ref_t search_process_keyrings_rcu(struct keyring_search_context * ctx)
```

```json
{
  "name": "search_process_keyrings_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583826544,
      "name": "search_process_keyrings_rcu",
      "external": true,
      "loc": "security/keys/process_keys.c:539",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_alloc_key",
        "security/keys/request_key_auth.c:key_get_instantiation_authkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583826544,
      "name": "search_process_keyrings_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
key_ref_t search_process_keyrings_rcu(struct keyring_search_context * ctx)
```

```json
{
  "name": "search_process_keyrings_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584189584,
      "name": "search_process_keyrings_rcu",
      "external": true,
      "loc": "security/keys/process_keys.c:539",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_alloc_key",
        "security/keys/request_key_auth.c:key_get_instantiation_authkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584189584,
      "name": "search_process_keyrings_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
key_ref_t search_process_keyrings_rcu(struct keyring_search_context * ctx)
```

```json
{
  "name": "search_process_keyrings_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584790576,
      "name": "search_process_keyrings_rcu",
      "external": true,
      "loc": "security/keys/process_keys.c:539",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_alloc_key",
        "security/keys/request_key.c:construct_alloc_key",
        "security/keys/request_key_auth.c:key_get_instantiation_authkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584790576,
      "name": "search_process_keyrings_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
key_ref_t search_process_keyrings_rcu(struct keyring_search_context * ctx)
```

```json
{
  "name": "search_process_keyrings_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585488016,
      "name": "search_process_keyrings_rcu",
      "external": true,
      "loc": "security/keys/process_keys.c:539",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_alloc_key",
        "security/keys/request_key.c:construct_alloc_key",
        "security/keys/request_key_auth.c:key_get_instantiation_authkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585488016,
      "name": "search_process_keyrings_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
key_ref_t search_process_keyrings_rcu(struct keyring_search_context * ctx)
```

```json
{
  "name": "search_process_keyrings_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585719488,
      "name": "search_process_keyrings_rcu",
      "external": true,
      "loc": "security/keys/process_keys.c:539",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_alloc_key",
        "security/keys/request_key.c:construct_alloc_key",
        "security/keys/request_key_auth.c:key_get_instantiation_authkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585719488,
      "name": "search_process_keyrings_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
key_ref_t search_process_keyrings_rcu(struct keyring_search_context * ctx)
```

```json
{
  "name": "search_process_keyrings_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585966608,
      "name": "search_process_keyrings_rcu",
      "external": true,
      "loc": "security/keys/process_keys.c:539",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_alloc_key",
        "security/keys/request_key.c:construct_alloc_key",
        "security/keys/request_key_auth.c:key_get_instantiation_authkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585966608,
      "name": "search_process_keyrings_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
key_ref_t search_process_keyrings_rcu(struct keyring_search_context * ctx)
```

```json
{
  "name": "search_process_keyrings_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495090256,
      "name": "search_process_keyrings_rcu",
      "external": true,
      "loc": "security/keys/process_keys.c:539",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key_auth.c:key_get_instantiation_authkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495090256,
      "name": "search_process_keyrings_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
key_ref_t search_process_keyrings_rcu(struct keyring_search_context * ctx)
```

```json
{
  "name": "search_process_keyrings_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228483844,
      "name": "search_process_keyrings_rcu",
      "external": true,
      "loc": "security/keys/process_keys.c:539",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key_auth.c:key_get_instantiation_authkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228483844,
      "name": "search_process_keyrings_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
key_ref_t search_process_keyrings_rcu(struct keyring_search_context * ctx)
```

```json
{
  "name": "search_process_keyrings_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288991104,
      "name": "search_process_keyrings_rcu",
      "external": true,
      "loc": "security/keys/process_keys.c:539",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key_auth.c:key_get_instantiation_authkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288991104,
      "name": "search_process_keyrings_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
key_ref_t search_process_keyrings_rcu(struct keyring_search_context * ctx)
```

```json
{
  "name": "search_process_keyrings_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274352972,
      "name": "search_process_keyrings_rcu",
      "external": true,
      "loc": "security/keys/process_keys.c:539",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key_auth.c:key_get_instantiation_authkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274352972,
      "name": "search_process_keyrings_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
key_ref_t search_process_keyrings_rcu(struct keyring_search_context * ctx)
```

```json
{
  "name": "search_process_keyrings_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583314752,
      "name": "search_process_keyrings_rcu",
      "external": true,
      "loc": "security/keys/process_keys.c:539",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key_auth.c:key_get_instantiation_authkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583314752,
      "name": "search_process_keyrings_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
key_ref_t search_process_keyrings_rcu(struct keyring_search_context * ctx)
```

```json
{
  "name": "search_process_keyrings_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583251856,
      "name": "search_process_keyrings_rcu",
      "external": true,
      "loc": "security/keys/process_keys.c:539",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key_auth.c:key_get_instantiation_authkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583251856,
      "name": "search_process_keyrings_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
key_ref_t search_process_keyrings_rcu(struct keyring_search_context * ctx)
```

```json
{
  "name": "search_process_keyrings_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583298784,
      "name": "search_process_keyrings_rcu",
      "external": true,
      "loc": "security/keys/process_keys.c:539",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key_auth.c:key_get_instantiation_authkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583298784,
      "name": "search_process_keyrings_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
key_ref_t search_process_keyrings_rcu(struct keyring_search_context * ctx)
```

```json
{
  "name": "search_process_keyrings_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583393408,
      "name": "search_process_keyrings_rcu",
      "external": true,
      "loc": "security/keys/process_keys.c:539",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key_auth.c:key_get_instantiation_authkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583393408,
      "name": "search_process_keyrings_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
key_ref_t search_process_keyrings_rcu(struct keyring_search_context * ctx)
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
