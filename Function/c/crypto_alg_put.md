# Function: <code>crypto_alg_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582630789,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:113",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:__crypto_alg_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582634148,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:113",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582664080,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:113",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_probe",
        "crypto/algboss.c:cryptomgr_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582664080,
      "name": "crypto_alg_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582882174,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:116",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582883698,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:116",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582915920,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:116",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582915920,
      "name": "crypto_alg_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582978734,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:113",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582980274,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:113",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583018432,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:113",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583018432,
      "name": "crypto_alg_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583028558,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:113",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583030068,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:113",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583070176,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:113",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583070176,
      "name": "crypto_alg_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583193806,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:113",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583195332,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:113",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583236400,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:113",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583236400,
      "name": "crypto_alg_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583402311,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:108",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583403972,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:108",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583444080,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:108",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583444080,
      "name": "crypto_alg_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583522439,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:100",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:__crypto_alg_lookup",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583531432,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:100",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_remove_final",
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583566064,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:100",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583566064,
      "name": "crypto_alg_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583710322,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:95",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:__crypto_alg_lookup",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583719543,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:95",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_remove_final",
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583756548,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:95",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe",
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583754976,
      "name": "crypto_alg_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583819938,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:__crypto_alg_lookup",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583828423,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_remove_final",
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583866260,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe",
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583864688,
      "name": "crypto_alg_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584212826,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:92",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_mod_put",
        "crypto/api.c:crypto_mod_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584223723,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:92",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_spawn_alg",
        "crypto/algapi.c:crypto_spawn_alg",
        "crypto/algapi.c:crypto_remove_final",
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584254768,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:92",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_schedule_probe",
        "crypto/algboss.c:cryptomgr_probe"
      ]
    },
    {
      "addr": 18446744071584296633,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:92",
      "file": "crypto/rng.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_rng_reset",
        "crypto/rng.c:crypto_rng_reset"
      ],
      "caller_func": [
        "crypto/rng.c:crypto_rng_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584254768,
      "name": "crypto_alg_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071584296256,
      "name": "crypto_alg_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584330986,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:105",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_mod_put",
        "crypto/api.c:crypto_mod_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584342587,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:105",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_spawn_alg",
        "crypto/algapi.c:crypto_spawn_alg",
        "crypto/algapi.c:crypto_remove_final",
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584373504,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:105",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_schedule_probe",
        "crypto/algboss.c:cryptomgr_probe"
      ]
    },
    {
      "addr": 18446744071584415273,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:105",
      "file": "crypto/rng.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_rng_reset",
        "crypto/rng.c:crypto_rng_reset"
      ],
      "caller_func": [
        "crypto/rng.c:crypto_rng_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584373504,
      "name": "crypto_alg_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071584414896,
      "name": "crypto_alg_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584365530,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:105",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_mod_put",
        "crypto/api.c:crypto_mod_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584377336,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:105",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_spawn_alg",
        "crypto/algapi.c:crypto_spawn_alg",
        "crypto/algapi.c:crypto_remove_final",
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584407936,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:105",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_schedule_probe",
        "crypto/algboss.c:cryptomgr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584407936,
      "name": "crypto_alg_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584760698,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:117",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_mod_put",
        "crypto/api.c:crypto_mod_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584772008,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:117",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_spawn_alg",
        "crypto/algapi.c:crypto_spawn_alg",
        "crypto/algapi.c:crypto_remove_final",
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584803312,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:117",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_schedule_probe",
        "crypto/algboss.c:cryptomgr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584803312,
      "name": "crypto_alg_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585443124,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:122",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_mod_put",
        "crypto/api.c:crypto_mod_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585456392,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:122",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_spawn_alg",
        "crypto/algapi.c:crypto_spawn_alg",
        "crypto/algapi.c:crypto_remove_final",
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585493008,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:122",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_schedule_probe",
        "crypto/algboss.c:cryptomgr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585493008,
      "name": "crypto_alg_put",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586201332,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:140",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_mod_put",
        "crypto/api.c:crypto_mod_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586215304,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:140",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_spawn_alg",
        "crypto/algapi.c:crypto_spawn_alg",
        "crypto/algapi.c:crypto_remove_final",
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586255808,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:140",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_schedule_probe",
        "crypto/algboss.c:cryptomgr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586255808,
      "name": "crypto_alg_put",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586439892,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:167",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_mod_put",
        "crypto/api.c:crypto_mod_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586447009,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:167",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_spawn_alg",
        "crypto/algapi.c:crypto_spawn_alg",
        "crypto/algapi.c:crypto_remove_final",
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586496176,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:167",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_schedule_probe",
        "crypto/algboss.c:cryptomgr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586496176,
      "name": "crypto_alg_put",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586705748,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:167",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_mod_put",
        "crypto/api.c:crypto_mod_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586712865,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:167",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_spawn_alg",
        "crypto/algapi.c:crypto_spawn_alg",
        "crypto/algapi.c:crypto_remove_final",
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586766224,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:167",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_schedule_probe",
        "crypto/algboss.c:cryptomgr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586766224,
      "name": "crypto_alg_put",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495626496,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:__crypto_alg_lookup",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495638972,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_remove_final",
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495682656,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495682656,
      "name": "crypto_alg_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228984688,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:__crypto_alg_lookup",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 3228994808,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_remove_final",
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 3229033256,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229033256,
      "name": "crypto_alg_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289751404,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_larval_destroy",
        "crypto/api.c:crypto_larval_destroy",
        "crypto/api.c:__crypto_alg_lookup",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289770924,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_remove_final",
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289827348,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_probe",
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274782398,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_mod_put",
        "crypto/api.c:crypto_mod_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274794148,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_remove_final",
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274831986,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_probe",
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583788674,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:__crypto_alg_lookup",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583797159,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_remove_final",
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583834996,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe",
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583833424,
      "name": "crypto_alg_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583725730,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:__crypto_alg_lookup",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583734215,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_remove_final",
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583772052,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe",
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583770480,
      "name": "crypto_alg_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583772434,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:__crypto_alg_lookup",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583780919,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_remove_final",
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583818756,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe",
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583817184,
      "name": "crypto_alg_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```

```json
{
  "name": "crypto_alg_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583873426,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_has_alg",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_destroy_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_alg_lookup",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_wait",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:crypto_larval_kill",
        "crypto/api.c:__crypto_alg_lookup",
        "crypto/api.c:__crypto_alg_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583881911,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_decrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_skcipher_encrypt",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_remove_final",
        "crypto/algapi.c:crypto_remove_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583919828,
      "name": "crypto_alg_put",
      "external": false,
      "loc": "crypto/internal.h:94",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe",
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": [
        "crypto/algboss.c:cryptomgr_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583918256,
      "name": "crypto_alg_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void crypto_alg_put(struct crypto_alg * alg)
```
</details>
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
