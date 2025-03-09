# Function: <code>ebitmap_cpy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ebitmap_cpy(struct ebitmap * dst, struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582308096,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:49",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_insert",
        "security/selinux/ss/sidtab.c:sidtab_insert",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582308096,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
int ebitmap_cpy(struct ebitmap * dst, struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582529248,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:49",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_insert",
        "security/selinux/ss/sidtab.c:sidtab_insert",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582529248,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
int ebitmap_cpy(struct ebitmap * dst, struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582622048,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:49",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_insert",
        "security/selinux/ss/sidtab.c:sidtab_insert",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582622048,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
int ebitmap_cpy(struct ebitmap * dst, struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582715120,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:51",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_insert",
        "security/selinux/ss/sidtab.c:sidtab_insert",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_cpy_high",
        "security/selinux/ss/mls.c:mls_context_cpy_high"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582715120,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int ebitmap_cpy(struct ebitmap * dst, struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582871008,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:52",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_insert",
        "security/selinux/ss/sidtab.c:sidtab_insert",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_cpy_high",
        "security/selinux/ss/mls.c:mls_context_cpy_high"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582871008,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int ebitmap_cpy(struct ebitmap * dst, struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583069200,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:52",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_insert",
        "security/selinux/ss/sidtab.c:sidtab_insert",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583069200,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int ebitmap_cpy(struct ebitmap * dst, struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583182688,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:52",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583182688,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int ebitmap_cpy(struct ebitmap * dst, struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583370048,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:52",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583370048,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int ebitmap_cpy(struct ebitmap * dst, struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583476000,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:52",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583476000,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int ebitmap_cpy(struct ebitmap * dst, struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583819760,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:53",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583819760,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int ebitmap_cpy(struct ebitmap * dst, struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583941136,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:53",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583941136,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int ebitmap_cpy(struct ebitmap * dst, struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583968080,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:53",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583968080,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int ebitmap_cpy(struct ebitmap * dst, struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584333120,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:53",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333120,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int ebitmap_cpy(struct ebitmap * dst, struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584953856,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:53",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584953856,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int ebitmap_cpy(struct ebitmap * dst, const struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585666672,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:53",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585666672,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int ebitmap_cpy(struct ebitmap * dst, const struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585896496,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:53",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585896496,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int ebitmap_cpy(struct ebitmap * dst, const struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586144960,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:53",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586144960,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int ebitmap_cpy(struct ebitmap * dst, struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495240744,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:52",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495240744,
      "name": "ebitmap_cpy",
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
int ebitmap_cpy(struct ebitmap * dst, struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228622392,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:52",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228622392,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int ebitmap_cpy(struct ebitmap * dst, struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289206576,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:52",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289206576,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int ebitmap_cpy(struct ebitmap * dst, struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274466450,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:52",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274466450,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int ebitmap_cpy(struct ebitmap * dst, struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583444736,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:52",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583444736,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int ebitmap_cpy(struct ebitmap * dst, struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583381808,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:52",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583381808,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int ebitmap_cpy(struct ebitmap * dst, struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583428512,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:52",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583428512,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int ebitmap_cpy(struct ebitmap * dst, struct ebitmap * src)
```

```json
{
  "name": "ebitmap_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583524784,
      "name": "ebitmap_cpy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:52",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583524784,
      "name": "ebitmap_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ebitmap * src</code> ➡️ <code>const struct ebitmap * src</code>
</li>
</ul>
</details>
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
