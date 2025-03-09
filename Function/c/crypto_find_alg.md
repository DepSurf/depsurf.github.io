# Function: <code>crypto_find_alg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582630112,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:499",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/algapi.c:crypto_attr_alg2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582630112,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582880286,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:499",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_attr_alg2",
        "crypto/algapi.c:crypto_grab_spawn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582879696,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582976814,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:483",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_attr_alg2",
        "crypto/algapi.c:crypto_grab_spawn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582976288,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583026622,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:483",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_attr_alg2",
        "crypto/algapi.c:crypto_grab_spawn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583026112,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583191826,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:484",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_attr_alg2",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583191280,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583402850,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:493",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_attr_alg2",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583402224,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583522178,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:493",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_attr_alg2",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583522096,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583710655,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:488",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_attr_alg2",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583710240,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583820271,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:489",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_attr_alg2",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583819856,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584215487,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:477",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_grab_spawn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584214640,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584333889,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:479",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm_node"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_grab_spawn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584332992,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584368433,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:479",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm_node"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_grab_spawn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584367536,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584763601,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:479",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm_node"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_grab_spawn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584762704,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585446662,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:534",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm_node"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_grab_spawn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585446320,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586204934,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:533",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm_node"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_grab_spawn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586204256,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586443046,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:569",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm_node"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_grab_spawn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586442656,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586708902,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:569",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm_node"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_grab_spawn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586708704,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495626844,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:489",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_attr_alg2",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495626320,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228984804,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:489",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_attr_alg2",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228984572,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289751012,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:489",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_attr_alg2",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289750832,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274784312,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:489",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_attr_alg2",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274784174,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583789007,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:489",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_attr_alg2",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583788592,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583726063,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:489",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_attr_alg2",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583725648,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583772767,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:489",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_attr_alg2",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583772352,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct crypto_alg * crypto_find_alg(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask)
```

```json
{
  "name": "crypto_find_alg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583873759,
      "name": "crypto_find_alg",
      "external": true,
      "loc": "crypto/api.c:489",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_attr_alg2",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583873344,
      "name": "crypto_find_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
