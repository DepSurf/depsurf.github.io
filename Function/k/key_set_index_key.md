# Function: <code>key_set_index_key</code>

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
void key_set_index_key(struct keyring_index_key * index_key)
```

```json
{
  "name": "key_set_index_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583224000,
      "name": "key_set_index_key",
      "external": true,
      "loc": "security/keys/keyring.c:214",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583224000,
      "name": "key_set_index_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
void key_set_index_key(struct keyring_index_key * index_key)
```

```json
{
  "name": "key_set_index_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583329808,
      "name": "key_set_index_key",
      "external": true,
      "loc": "security/keys/keyring.c:214",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583329808,
      "name": "key_set_index_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
void key_set_index_key(struct keyring_index_key * index_key)
```

```json
{
  "name": "key_set_index_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583663808,
      "name": "key_set_index_key",
      "external": true,
      "loc": "security/keys/keyring.c:214",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/persistent.c:key_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583663808,
      "name": "key_set_index_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void key_set_index_key(struct keyring_index_key * index_key)
```

```json
{
  "name": "key_set_index_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583785264,
      "name": "key_set_index_key",
      "external": true,
      "loc": "security/keys/keyring.c:214",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/persistent.c:key_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583785264,
      "name": "key_set_index_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void key_set_index_key(struct keyring_index_key * index_key)
```

```json
{
  "name": "key_set_index_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583809440,
      "name": "key_set_index_key",
      "external": true,
      "loc": "security/keys/keyring.c:214",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/persistent.c:key_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583809440,
      "name": "key_set_index_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void key_set_index_key(struct keyring_index_key * index_key)
```

```json
{
  "name": "key_set_index_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584172064,
      "name": "key_set_index_key",
      "external": true,
      "loc": "security/keys/keyring.c:214",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/persistent.c:key_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584172064,
      "name": "key_set_index_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void key_set_index_key(struct keyring_index_key * index_key)
```

```json
{
  "name": "key_set_index_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584771760,
      "name": "key_set_index_key",
      "external": true,
      "loc": "security/keys/keyring.c:214",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/persistent.c:key_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584771760,
      "name": "key_set_index_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void key_set_index_key(struct keyring_index_key * index_key)
```

```json
{
  "name": "key_set_index_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585468048,
      "name": "key_set_index_key",
      "external": true,
      "loc": "security/keys/keyring.c:214",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/persistent.c:key_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585468048,
      "name": "key_set_index_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void key_set_index_key(struct keyring_index_key * index_key)
```

```json
{
  "name": "key_set_index_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585699696,
      "name": "key_set_index_key",
      "external": true,
      "loc": "security/keys/keyring.c:214",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:__key_create_or_update",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/persistent.c:key_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585699696,
      "name": "key_set_index_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void key_set_index_key(struct keyring_index_key * index_key)
```

```json
{
  "name": "key_set_index_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585946736,
      "name": "key_set_index_key",
      "external": true,
      "loc": "security/keys/keyring.c:214",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:__key_create_or_update",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/persistent.c:key_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585946736,
      "name": "key_set_index_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void key_set_index_key(struct keyring_index_key * index_key)
```

```json
{
  "name": "key_set_index_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495072712,
      "name": "key_set_index_key",
      "external": true,
      "loc": "security/keys/keyring.c:214",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495072712,
      "name": "key_set_index_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
void key_set_index_key(struct keyring_index_key * index_key)
```

```json
{
  "name": "key_set_index_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228468244,
      "name": "key_set_index_key",
      "external": true,
      "loc": "security/keys/keyring.c:214",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228468244,
      "name": "key_set_index_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
void key_set_index_key(struct keyring_index_key * index_key)
```

```json
{
  "name": "key_set_index_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288968688,
      "name": "key_set_index_key",
      "external": true,
      "loc": "security/keys/keyring.c:214",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288968688,
      "name": "key_set_index_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
void key_set_index_key(struct keyring_index_key * index_key)
```

```json
{
  "name": "key_set_index_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274339914,
      "name": "key_set_index_key",
      "external": true,
      "loc": "security/keys/keyring.c:214",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274339914,
      "name": "key_set_index_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
void key_set_index_key(struct keyring_index_key * index_key)
```

```json
{
  "name": "key_set_index_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583298544,
      "name": "key_set_index_key",
      "external": true,
      "loc": "security/keys/keyring.c:214",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583298544,
      "name": "key_set_index_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
void key_set_index_key(struct keyring_index_key * index_key)
```

```json
{
  "name": "key_set_index_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583235680,
      "name": "key_set_index_key",
      "external": true,
      "loc": "security/keys/keyring.c:214",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583235680,
      "name": "key_set_index_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
void key_set_index_key(struct keyring_index_key * index_key)
```

```json
{
  "name": "key_set_index_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583282576,
      "name": "key_set_index_key",
      "external": true,
      "loc": "security/keys/keyring.c:214",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583282576,
      "name": "key_set_index_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
void key_set_index_key(struct keyring_index_key * index_key)
```

```json
{
  "name": "key_set_index_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583377120,
      "name": "key_set_index_key",
      "external": true,
      "loc": "security/keys/keyring.c:214",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_alloc",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583377120,
      "name": "key_set_index_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
void key_set_index_key(struct keyring_index_key * index_key)
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
