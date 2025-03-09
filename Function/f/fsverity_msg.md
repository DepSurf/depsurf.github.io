# Function: <code>fsverity_msg</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void fsverity_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fsverity_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582320315,
      "name": "fsverity_msg",
      "external": true,
      "loc": "fs/verity/init.c:12",
      "file": "fs/verity/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582320315,
      "name": "fsverity_msg",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void fsverity_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fsverity_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582609566,
      "name": "fsverity_msg",
      "external": true,
      "loc": "fs/verity/init.c:12",
      "file": "fs/verity/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/open.c:ensure_verity_info",
        "fs/verity/open.c:ensure_verity_info",
        "fs/verity/open.c:ensure_verity_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582609566,
      "name": "fsverity_msg",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void fsverity_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fsverity_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591343303,
      "name": "fsverity_msg",
      "external": true,
      "loc": "fs/verity/init.c:12",
      "file": "fs/verity/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/open.c:ensure_verity_info",
        "fs/verity/open.c:ensure_verity_info",
        "fs/verity/open.c:ensure_verity_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591343303,
      "name": "fsverity_msg",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void fsverity_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fsverity_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591286043,
      "name": "fsverity_msg",
      "external": true,
      "loc": "fs/verity/init.c:12",
      "file": "fs/verity/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591286043,
      "name": "fsverity_msg",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void fsverity_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fsverity_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592242721,
      "name": "fsverity_msg",
      "external": true,
      "loc": "fs/verity/init.c:12",
      "file": "fs/verity/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592242721,
      "name": "fsverity_msg",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void fsverity_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fsverity_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594021725,
      "name": "fsverity_msg",
      "external": true,
      "loc": "fs/verity/init.c:12",
      "file": "fs/verity/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594021725,
      "name": "fsverity_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
void fsverity_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fsverity_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584109440,
      "name": "fsverity_msg",
      "external": true,
      "loc": "fs/verity/init.c:12",
      "file": "fs/verity/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584109440,
      "name": "fsverity_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void fsverity_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fsverity_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584335264,
      "name": "fsverity_msg",
      "external": true,
      "loc": "fs/verity/init.c:12",
      "file": "fs/verity/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:write_merkle_tree_block",
        "fs/verity/hash_algs.c:fsverity_hash_block",
        "fs/verity/hash_algs.c:fsverity_hash_block",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/verify.c:verify_data_block",
        "fs/verity/verify.c:verify_data_block",
        "fs/verity/verify.c:verify_data_block",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584335264,
      "name": "fsverity_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void fsverity_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fsverity_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584553056,
      "name": "fsverity_msg",
      "external": true,
      "loc": "fs/verity/init.c:42",
      "file": "fs/verity/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:write_merkle_tree_block",
        "fs/verity/hash_algs.c:fsverity_hash_block",
        "fs/verity/hash_algs.c:fsverity_hash_block",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/verify.c:verify_data_block",
        "fs/verity/verify.c:verify_data_block",
        "fs/verity/verify.c:verify_data_block",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584553056,
      "name": "fsverity_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void fsverity_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fsverity_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493900424,
      "name": "fsverity_msg",
      "external": true,
      "loc": "fs/verity/init.c:12",
      "file": "fs/verity/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493900424,
      "name": "fsverity_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void fsverity_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fsverity_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227379932,
      "name": "fsverity_msg",
      "external": true,
      "loc": "fs/verity/init.c:12",
      "file": "fs/verity/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227379932,
      "name": "fsverity_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void fsverity_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fsverity_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287537664,
      "name": "fsverity_msg",
      "external": true,
      "loc": "fs/verity/init.c:12",
      "file": "fs/verity/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287537664,
      "name": "fsverity_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void fsverity_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fsverity_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273457846,
      "name": "fsverity_msg",
      "external": true,
      "loc": "fs/verity/init.c:12",
      "file": "fs/verity/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273457846,
      "name": "fsverity_msg",
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
void fsverity_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fsverity_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582289051,
      "name": "fsverity_msg",
      "external": true,
      "loc": "fs/verity/init.c:12",
      "file": "fs/verity/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582289051,
      "name": "fsverity_msg",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void fsverity_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fsverity_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582226811,
      "name": "fsverity_msg",
      "external": true,
      "loc": "fs/verity/init.c:12",
      "file": "fs/verity/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226811,
      "name": "fsverity_msg",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void fsverity_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fsverity_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582279531,
      "name": "fsverity_msg",
      "external": true,
      "loc": "fs/verity/init.c:12",
      "file": "fs/verity/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582279531,
      "name": "fsverity_msg",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void fsverity_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fsverity_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582358091,
      "name": "fsverity_msg",
      "external": true,
      "loc": "fs/verity/init.c:12",
      "file": "fs/verity/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_hash_page",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/open.c:fsverity_init_merkle_tree_params",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "fs/verity/signature.c:fsverity_verify_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582358091,
      "name": "fsverity_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void fsverity_msg(const struct inode * inode, const char * level, const char * fmt, void (anon))
```
</details>
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
