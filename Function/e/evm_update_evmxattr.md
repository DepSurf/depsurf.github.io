# Function: <code>evm_update_evmxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582627456,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:199",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_verify_hmac",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582627456,
      "name": "evm_update_evmxattr",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582877040,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:242",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582877040,
      "name": "evm_update_evmxattr",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582974496,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:251",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582974496,
      "name": "evm_update_evmxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583025120,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:252",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583025120,
      "name": "evm_update_evmxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583190288,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:252",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583190288,
      "name": "evm_update_evmxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583397152,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:303",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583397152,
      "name": "evm_update_evmxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583517200,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:304",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583517200,
      "name": "evm_update_evmxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583704848,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:302",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583704848,
      "name": "evm_update_evmxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583814624,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:302",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583814624,
      "name": "evm_update_evmxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584210096,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:300",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584210096,
      "name": "evm_update_evmxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584328496,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:303",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584328496,
      "name": "evm_update_evmxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584362992,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:303",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584362992,
      "name": "evm_update_evmxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584758048,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:359",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584758048,
      "name": "evm_update_evmxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585440224,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:356",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585440224,
      "name": "evm_update_evmxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586198144,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:357",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586198144,
      "name": "evm_update_evmxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586435760,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:356",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586435760,
      "name": "evm_update_evmxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586701520,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:356",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586701520,
      "name": "evm_update_evmxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495620744,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:302",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495620744,
      "name": "evm_update_evmxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228979916,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:302",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228979916,
      "name": "evm_update_evmxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289741776,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:302",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289741776,
      "name": "evm_update_evmxattr",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274780022,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:302",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274780022,
      "name": "evm_update_evmxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583783360,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:302",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583783360,
      "name": "evm_update_evmxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583720416,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:302",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583720416,
      "name": "evm_update_evmxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583767120,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:302",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583767120,
      "name": "evm_update_evmxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int evm_update_evmxattr(struct dentry * dentry, const char * xattr_name, const char * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_update_evmxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583868112,
      "name": "evm_update_evmxattr",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:302",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_post_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_removexattr",
        "security/integrity/evm/evm_main.c:evm_inode_post_setxattr",
        "security/integrity/evm/evm_main.c:evm_verify_hmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583868112,
      "name": "evm_update_evmxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
