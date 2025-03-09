# Function: <code>keyring_search_rcu</code>

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
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context * ctx)
```

```json
{
  "name": "keyring_search_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583225696,
      "name": "keyring_search_rcu",
      "external": true,
      "loc": "security/keys/keyring.c:903",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_search",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:get_user_session_keyring_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583225696,
      "name": "keyring_search_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context * ctx)
```

```json
{
  "name": "keyring_search_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583331504,
      "name": "keyring_search_rcu",
      "external": true,
      "loc": "security/keys/keyring.c:903",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_search",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:get_user_session_keyring_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583331504,
      "name": "keyring_search_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context * ctx)
```

```json
{
  "name": "keyring_search_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583665152,
      "name": "keyring_search_rcu",
      "external": true,
      "loc": "security/keys/keyring.c:899",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_search",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:get_user_session_keyring_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583665152,
      "name": "keyring_search_rcu",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context * ctx)
```

```json
{
  "name": "keyring_search_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583786608,
      "name": "keyring_search_rcu",
      "external": true,
      "loc": "security/keys/keyring.c:899",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_search",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:get_user_session_keyring_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583786608,
      "name": "keyring_search_rcu",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context * ctx)
```

```json
{
  "name": "keyring_search_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583810752,
      "name": "keyring_search_rcu",
      "external": true,
      "loc": "security/keys/keyring.c:899",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_search",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:get_user_session_keyring_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583810752,
      "name": "keyring_search_rcu",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context * ctx)
```

```json
{
  "name": "keyring_search_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584173792,
      "name": "keyring_search_rcu",
      "external": true,
      "loc": "security/keys/keyring.c:899",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_search",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:get_user_session_keyring_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584173792,
      "name": "keyring_search_rcu",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context * ctx)
```

```json
{
  "name": "keyring_search_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584773712,
      "name": "keyring_search_rcu",
      "external": true,
      "loc": "security/keys/keyring.c:899",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_search",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:get_user_session_keyring_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584773712,
      "name": "keyring_search_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context * ctx)
```

```json
{
  "name": "keyring_search_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585470080,
      "name": "keyring_search_rcu",
      "external": true,
      "loc": "security/keys/keyring.c:899",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_search",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:get_user_session_keyring_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585470080,
      "name": "keyring_search_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context * ctx)
```

```json
{
  "name": "keyring_search_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585701680,
      "name": "keyring_search_rcu",
      "external": true,
      "loc": "security/keys/keyring.c:899",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_search",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:get_user_session_keyring_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585701680,
      "name": "keyring_search_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context * ctx)
```

```json
{
  "name": "keyring_search_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585948720,
      "name": "keyring_search_rcu",
      "external": true,
      "loc": "security/keys/keyring.c:899",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_search",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:get_user_session_keyring_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585948720,
      "name": "keyring_search_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context * ctx)
```

```json
{
  "name": "keyring_search_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495074424,
      "name": "keyring_search_rcu",
      "external": true,
      "loc": "security/keys/keyring.c:903",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_search",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:get_user_session_keyring_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495074424,
      "name": "keyring_search_rcu",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context * ctx)
```

```json
{
  "name": "keyring_search_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228470000,
      "name": "keyring_search_rcu",
      "external": true,
      "loc": "security/keys/keyring.c:903",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_search",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:get_user_session_keyring_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228470000,
      "name": "keyring_search_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context * ctx)
```

```json
{
  "name": "keyring_search_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288970960,
      "name": "keyring_search_rcu",
      "external": true,
      "loc": "security/keys/keyring.c:903",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_search",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:get_user_session_keyring_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288970960,
      "name": "keyring_search_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context * ctx)
```

```json
{
  "name": "keyring_search_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274341354,
      "name": "keyring_search_rcu",
      "external": true,
      "loc": "security/keys/keyring.c:903",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_search",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:get_user_session_keyring_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274341354,
      "name": "keyring_search_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context * ctx)
```

```json
{
  "name": "keyring_search_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583300240,
      "name": "keyring_search_rcu",
      "external": true,
      "loc": "security/keys/keyring.c:903",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_search",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:get_user_session_keyring_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583300240,
      "name": "keyring_search_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context * ctx)
```

```json
{
  "name": "keyring_search_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583237376,
      "name": "keyring_search_rcu",
      "external": true,
      "loc": "security/keys/keyring.c:903",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_search",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:get_user_session_keyring_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583237376,
      "name": "keyring_search_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context * ctx)
```

```json
{
  "name": "keyring_search_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583284272,
      "name": "keyring_search_rcu",
      "external": true,
      "loc": "security/keys/keyring.c:903",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_search",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:get_user_session_keyring_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583284272,
      "name": "keyring_search_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context * ctx)
```

```json
{
  "name": "keyring_search_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583378848,
      "name": "keyring_search_rcu",
      "external": true,
      "loc": "security/keys/keyring.c:903",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_search",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:search_cred_keyrings_rcu",
        "security/keys/process_keys.c:get_user_session_keyring_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583378848,
      "name": "keyring_search_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
key_ref_t keyring_search_rcu(key_ref_t keyring_ref, struct keyring_search_context * ctx)
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
