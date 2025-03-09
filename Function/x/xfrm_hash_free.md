# Function: <code>xfrm_hash_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586952592,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:31",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586952592,
      "name": "xfrm_hash_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587398832,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:31",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587398832,
      "name": "xfrm_hash_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587602064,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:31",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587602064,
      "name": "xfrm_hash_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587748928,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:31",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587748928,
      "name": "xfrm_hash_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588276752,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:32",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588276752,
      "name": "xfrm_hash_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588631792,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:32",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588631792,
      "name": "xfrm_hash_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588847872,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:32",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588847872,
      "name": "xfrm_hash_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589282976,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:32",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589282976,
      "name": "xfrm_hash_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589507392,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:32",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589507392,
      "name": "xfrm_hash_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590499360,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:32",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_init",
        "net/xfrm/xfrm_policy.c:xfrm_policy_init",
        "net/xfrm/xfrm_policy.c:xfrm_bydst_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590499360,
      "name": "xfrm_hash_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590558800,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:32",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_init",
        "net/xfrm/xfrm_policy.c:xfrm_policy_init",
        "net/xfrm/xfrm_policy.c:xfrm_bydst_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590558800,
      "name": "xfrm_hash_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590484160,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:32",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_init",
        "net/xfrm/xfrm_policy.c:xfrm_policy_init",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590484160,
      "name": "xfrm_hash_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591288096,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:32",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591288096,
      "name": "xfrm_hash_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592954496,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:32",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592954496,
      "name": "xfrm_hash_free",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594840288,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:32",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594840288,
      "name": "xfrm_hash_free",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595231600,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:32",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595231600,
      "name": "xfrm_hash_free",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596072144,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:32",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596072144,
      "name": "xfrm_hash_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503171456,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:32",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503171456,
      "name": "xfrm_hash_free",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235846848,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:32",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235846848,
      "name": "xfrm_hash_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296897680,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:32",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_bydst_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296897680,
      "name": "xfrm_hash_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279214122,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:32",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279214122,
      "name": "xfrm_hash_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589111760,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:32",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589111760,
      "name": "xfrm_hash_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588836800,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:32",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588836800,
      "name": "xfrm_hash_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589548624,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:32",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589548624,
      "name": "xfrm_hash_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void xfrm_hash_free(struct hlist_head * n, unsigned int sz)
```

```json
{
  "name": "xfrm_hash_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589596016,
      "name": "xfrm_hash_free",
      "external": true,
      "loc": "net/xfrm/xfrm_hash.c:32",
      "file": "net/xfrm/xfrm_hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_fini",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_state_init",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589596016,
      "name": "xfrm_hash_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
