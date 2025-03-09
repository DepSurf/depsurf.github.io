# Function: <code>kvfree_sensitive</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void kvfree_sensitive(const void * addr, size_t len)
```

```json
{
  "name": "kvfree_sensitive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581413456,
      "name": "kvfree_sensitive",
      "external": true,
      "loc": "mm/util.c:616",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:__do_sys_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413456,
      "name": "kvfree_sensitive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void kvfree_sensitive(const void * addr, size_t len)
```

```json
{
  "name": "kvfree_sensitive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581456304,
      "name": "kvfree_sensitive",
      "external": true,
      "loc": "mm/util.c:629",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:__do_sys_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581456304,
      "name": "kvfree_sensitive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void kvfree_sensitive(const void * addr, size_t len)
```

```json
{
  "name": "kvfree_sensitive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581477248,
      "name": "kvfree_sensitive",
      "external": true,
      "loc": "mm/util.c:629",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:__do_sys_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581477248,
      "name": "kvfree_sensitive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void kvfree_sensitive(const void * addr, size_t len)
```

```json
{
  "name": "kvfree_sensitive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581731712,
      "name": "kvfree_sensitive",
      "external": true,
      "loc": "mm/util.c:635",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:__do_sys_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581731712,
      "name": "kvfree_sensitive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void kvfree_sensitive(const void * addr, size_t len)
```

```json
{
  "name": "kvfree_sensitive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582111552,
      "name": "kvfree_sensitive",
      "external": true,
      "loc": "mm/util.c:668",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "block/blk-crypto-profile.c:blk_crypto_profile_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582111552,
      "name": "kvfree_sensitive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void kvfree_sensitive(const void * addr, size_t len)
```

```json
{
  "name": "kvfree_sensitive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582585888,
      "name": "kvfree_sensitive",
      "external": true,
      "loc": "mm/util.c:640",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "block/blk-crypto-profile.c:blk_crypto_profile_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582585888,
      "name": "kvfree_sensitive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void kvfree_sensitive(const void * addr, size_t len)
```

```json
{
  "name": "kvfree_sensitive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582793200,
      "name": "kvfree_sensitive",
      "external": true,
      "loc": "mm/util.c:663",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:__do_sys_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582793200,
      "name": "kvfree_sensitive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void kvfree_sensitive(const void * addr, size_t len)
```

```json
{
  "name": "kvfree_sensitive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582968224,
      "name": "kvfree_sensitive",
      "external": true,
      "loc": "mm/util.c:676",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:__do_sys_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582968224,
      "name": "kvfree_sensitive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void kvfree_sensitive(const void * addr, size_t len)
```
</details>
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
