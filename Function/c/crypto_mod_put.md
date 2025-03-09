# Function: <code>crypto_mod_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582630782,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:45",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:__crypto_alg_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/algapi.c:crypto_register_instance",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/ablkcipher.c:crypto_givcipher_default",
        "crypto/ablkcipher.c:crypto_givcipher_default",
        "crypto/ablkcipher.c:crypto_lookup_skcipher",
        "crypto/ablkcipher.c:crypto_lookup_skcipher",
        "crypto/ablkcipher.c:crypto_grab_skcipher",
        "crypto/ablkcipher.c:crypto_alloc_ablkcipher",
        "crypto/blkcipher.c:skcipher_geniv_alloc",
        "crypto/shash.c:crypto_init_shash_ops",
        "crypto/shash.c:crypto_init_shash_ops_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582630928,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582882167,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:45",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/algapi.c:crypto_register_instance",
        "crypto/skcipher.c:crypto_skcipher_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880528,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582978727,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:45",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/algapi.c:crypto_register_instance",
        "crypto/skcipher.c:crypto_skcipher_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/scompress.c:crypto_init_scomp_ops_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582977056,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583028551,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:45",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/algapi.c:crypto_register_instance",
        "crypto/skcipher.c:crypto_skcipher_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/scompress.c:crypto_init_scomp_ops_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583026864,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583193799,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:46",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/algapi.c:crypto_register_instance",
        "crypto/skcipher.c:crypto_skcipher_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/scompress.c:crypto_init_scomp_ops_async",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583192064,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583402304,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:46",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/skcipher.c:crypto_skcipher_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/scompress.c:crypto_init_scomp_ops_async",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583400512,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583522432,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:46",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/skcipher.c:crypto_skcipher_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/scompress.c:crypto_init_scomp_ops_async",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583520384,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583710322,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:41",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/skcipher.c:crypto_skcipher_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/scompress.c:crypto_init_scomp_ops_async",
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583708064,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583819938,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:41",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/skcipher.c:crypto_skcipher_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/scompress.c:crypto_init_scomp_ops_async",
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583817648,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584213024,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:41",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:__crypto_alg_lookup",
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/algapi.c:crypto_register_instance",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/scompress.c:crypto_init_scomp_ops_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584213024,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584331232,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:41",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm_node",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:__crypto_alg_lookup",
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/algapi.c:crypto_register_instance",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/scompress.c:crypto_init_scomp_ops_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584331232,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584365776,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:41",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_alloc_tfm_node",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:__crypto_alg_lookup",
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/algapi.c:crypto_register_instance",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/scompress.c:crypto_init_scomp_ops_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584365776,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584760944,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:41",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_alloc_tfm_node",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_destroy",
        "crypto/api.c:__crypto_alg_lookup",
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/algapi.c:crypto_register_instance",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/scompress.c:crypto_init_scomp_ops_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584760944,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585443424,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:45",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm_node",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_destroy",
        "crypto/api.c:__crypto_alg_lookup",
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/algapi.c:crypto_register_instance",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/scompress.c:crypto_init_scomp_ops_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585443424,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586201680,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:47",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm_node",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_destroy",
        "crypto/api.c:__crypto_alg_lookup",
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/algapi.c:crypto_register_instance",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/scompress.c:crypto_init_scomp_ops_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586201680,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586439536,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:47",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_alloc_tfm_node",
        "crypto/api.c:crypto_clone_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_destroy",
        "crypto/api.c:__crypto_alg_lookup",
        "crypto/cipher.c:crypto_clone_cipher",
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/algapi.c:crypto_register_instance",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/akcipher.c:crypto_init_akcipher_ops_sig",
        "crypto/scompress.c:crypto_init_scomp_ops_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586439536,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586705392,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:47",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_alloc_tfm_node",
        "crypto/api.c:crypto_clone_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_destroy",
        "crypto/api.c:__crypto_alg_lookup",
        "crypto/cipher.c:crypto_clone_cipher",
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/algapi.c:crypto_register_instance",
        "crypto/lskcipher.c:crypto_init_lskcipher_ops_sg",
        "crypto/ahash.c:crypto_ahash_init_tfm",
        "crypto/akcipher.c:crypto_init_akcipher_ops_sig",
        "crypto/scompress.c:crypto_init_scomp_ops_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586705392,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495626488,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:41",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/skcipher.c:crypto_skcipher_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/scompress.c:crypto_init_scomp_ops_async",
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495623992,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228984680,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:41",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/skcipher.c:crypto_skcipher_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/scompress.c:crypto_init_scomp_ops_async",
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228982856,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289751396,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:41",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_destroy",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/skcipher.c:crypto_skcipher_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/scompress.c:crypto_init_scomp_ops_async",
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289746976,
      "name": "crypto_mod_put",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274782770,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:41",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:__crypto_alg_lookup",
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/skcipher.c:crypto_skcipher_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/scompress.c:crypto_init_scomp_ops_async",
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274782770,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583788674,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:41",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/skcipher.c:crypto_skcipher_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/scompress.c:crypto_init_scomp_ops_async",
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583786384,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583725730,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:41",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/skcipher.c:crypto_skcipher_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/scompress.c:crypto_init_scomp_ops_async",
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583723440,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583772434,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:41",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/skcipher.c:crypto_skcipher_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/scompress.c:crypto_init_scomp_ops_async",
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583770144,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void crypto_mod_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_mod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583873426,
      "name": "crypto_mod_put",
      "external": true,
      "loc": "crypto/api.c:41",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": [
        "crypto/algapi.c:crypto_type_has_alg",
        "crypto/algapi.c:crypto_spawn_tfm2",
        "crypto/algapi.c:crypto_spawn_tfm",
        "crypto/algapi.c:crypto_grab_spawn",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/skcipher.c:crypto_skcipher_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/scompress.c:crypto_init_scomp_ops_async",
        "crypto/ecb.c:crypto_ecb_create",
        "crypto/cbc.c:crypto_cbc_create",
        "crypto/ctr.c:crypto_ctr_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583871136,
      "name": "crypto_mod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
