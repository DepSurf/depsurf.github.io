# Function: <code>request_key_and_link</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct key * request_key_and_link(struct key_type * type, const char * description, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582206592,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:508",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:SyS_request_key",
        "security/keys/request_key.c:request_key",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key_async",
        "security/keys/request_key.c:request_key_async_with_auxdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582206592,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1470
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
struct key * request_key_and_link(struct key_type * type, const char * description, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582423600,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:508",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:SyS_request_key",
        "security/keys/request_key.c:request_key_async_with_auxdata",
        "security/keys/request_key.c:request_key_async",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582423600,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1424
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
struct key * request_key_and_link(struct key_type * type, const char * description, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582515776,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:508",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:SyS_request_key",
        "security/keys/request_key.c:request_key_async_with_auxdata",
        "security/keys/request_key.c:request_key_async",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582515776,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1424
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
struct key * request_key_and_link(struct key_type * type, const char * description, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582597312,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:509",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:SyS_request_key",
        "security/keys/request_key.c:request_key_async_with_auxdata",
        "security/keys/request_key.c:request_key_async",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582597312,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1406
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
struct key * request_key_and_link(struct key_type * type, const char * description, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582750352,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:537",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:SyS_request_key",
        "security/keys/request_key.c:request_key_async_with_auxdata",
        "security/keys/request_key.c:request_key_async",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582750352,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1799
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
struct key * request_key_and_link(struct key_type * type, const char * description, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582950400,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:537",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/request_key.c:request_key_async_with_auxdata",
        "security/keys/request_key.c:request_key_async",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582950400,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1742
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
struct key * request_key_and_link(struct key_type * type, const char * description, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583059552,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:523",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/request_key.c:request_key_async_with_auxdata",
        "security/keys/request_key.c:request_key_async",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583059552,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1672
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
struct key * request_key_and_link(struct key_type * type, const char * description, struct key_tag * domain_tag, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583245264,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:558",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583245264,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
struct key * request_key_and_link(struct key_type * type, const char * description, struct key_tag * domain_tag, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583351088,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:558",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583351088,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
struct key * request_key_and_link(struct key_type * type, const char * description, struct key_tag * domain_tag, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583687136,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:558",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583687136,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
struct key * request_key_and_link(struct key_type * type, const char * description, struct key_tag * domain_tag, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583808704,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:558",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583808704,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
struct key * request_key_and_link(struct key_type * type, const char * description, struct key_tag * domain_tag, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583832976,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:558",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583832976,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
struct key * request_key_and_link(struct key_type * type, const char * description, struct key_tag * domain_tag, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584195648,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:558",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584195648,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 793
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
struct key * request_key_and_link(struct key_type * type, const char * description, struct key_tag * domain_tag, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584797120,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:558",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584797120,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 879
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
struct key * request_key_and_link(struct key_type * type, const char * description, struct key_tag * domain_tag, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585495232,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:558",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585495232,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
struct key * request_key_and_link(struct key_type * type, const char * description, struct key_tag * domain_tag, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585726784,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:574",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585726784,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
struct key * request_key_and_link(struct key_type * type, const char * description, struct key_tag * domain_tag, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585973968,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:574",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585973968,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
struct key * request_key_and_link(struct key_type * type, const char * description, struct key_tag * domain_tag, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495095352,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:558",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__arm64_sys_request_key",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495095352,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
struct key * request_key_and_link(struct key_type * type, const char * description, struct key_tag * domain_tag, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228488896,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:558",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__se_sys_request_key",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228488896,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
struct key * request_key_and_link(struct key_type * type, const char * description, struct key_tag * domain_tag, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288997792,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:558",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__se_sys_request_key",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288997792,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
struct key * request_key_and_link(struct key_type * type, const char * description, struct key_tag * domain_tag, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274357096,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:558",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__se_sys_request_key",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274357096,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
struct key * request_key_and_link(struct key_type * type, const char * description, struct key_tag * domain_tag, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583319824,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:558",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583319824,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
struct key * request_key_and_link(struct key_type * type, const char * description, struct key_tag * domain_tag, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583256928,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:558",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583256928,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
struct key * request_key_and_link(struct key_type * type, const char * description, struct key_tag * domain_tag, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583303632,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:558",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583303632,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
struct key * request_key_and_link(struct key_type * type, const char * description, struct key_tag * domain_tag, const void * callout_info, size_t callout_len, void * aux, struct key * dest_keyring, long unsigned int flags)
```

```json
{
  "name": "request_key_and_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583398544,
      "name": "request_key_and_link",
      "external": true,
      "loc": "security/keys/request_key.c:558",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/request_key.c:request_key_with_auxdata",
        "security/keys/request_key.c:request_key_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583398544,
      "name": "request_key_and_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct key_tag * domain_tag</code>
</li>
<li>
<b>Param reordered. </b>
<code>type, description, callout_info, callout_len, aux, dest_keyring, flags</code> ➡️ <code>type, description, domain_tag, callout_info, callout_len, aux, dest_keyring, flags</code>
</li>
</ul>
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
