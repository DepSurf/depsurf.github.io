# Function: <code>ext4_fname_from_fscrypt_name</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fname_from_fscrypt_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582697924,
      "name": "ext4_fname_from_fscrypt_name",
      "external": false,
      "loc": "fs/ext4/ext4.h:2316",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fname_from_fscrypt_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582800132,
      "name": "ext4_fname_from_fscrypt_name",
      "external": false,
      "loc": "fs/ext4/ext4.h:2374",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fname_from_fscrypt_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583112532,
      "name": "ext4_fname_from_fscrypt_name",
      "external": false,
      "loc": "fs/ext4/ext4.h:2472",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fname_from_fscrypt_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583191540,
      "name": "ext4_fname_from_fscrypt_name",
      "external": false,
      "loc": "fs/ext4/ext4.h:2604",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fname_from_fscrypt_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583219456,
      "name": "ext4_fname_from_fscrypt_name",
      "external": false,
      "loc": "fs/ext4/ext4.h:2656",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fname_from_fscrypt_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583563168,
      "name": "ext4_fname_from_fscrypt_name",
      "external": false,
      "loc": "fs/ext4/ext4.h:2726",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void ext4_fname_from_fscrypt_name(struct ext4_filename * dst, const struct fscrypt_name * src)
```

```json
{
  "name": "ext4_fname_from_fscrypt_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584335712,
      "name": "ext4_fname_from_fscrypt_name",
      "external": false,
      "loc": "fs/ext4/crypto.c:10",
      "file": "fs/ext4/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/crypto.c:ext4_fname_prepare_lookup",
        "fs/ext4/crypto.c:ext4_fname_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584335712,
      "name": "ext4_fname_from_fscrypt_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void ext4_fname_from_fscrypt_name(struct ext4_filename * dst, const struct fscrypt_name * src)
```

```json
{
  "name": "ext4_fname_from_fscrypt_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584984768,
      "name": "ext4_fname_from_fscrypt_name",
      "external": false,
      "loc": "fs/ext4/crypto.c:10",
      "file": "fs/ext4/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/crypto.c:ext4_fname_prepare_lookup",
        "fs/ext4/crypto.c:ext4_fname_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584984768,
      "name": "ext4_fname_from_fscrypt_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void ext4_fname_from_fscrypt_name(struct ext4_filename * dst, const struct fscrypt_name * src)
```

```json
{
  "name": "ext4_fname_from_fscrypt_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585212784,
      "name": "ext4_fname_from_fscrypt_name",
      "external": false,
      "loc": "fs/ext4/crypto.c:10",
      "file": "fs/ext4/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/crypto.c:ext4_fname_prepare_lookup",
        "fs/ext4/crypto.c:ext4_fname_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585212784,
      "name": "ext4_fname_from_fscrypt_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void ext4_fname_from_fscrypt_name(struct ext4_filename * dst, const struct fscrypt_name * src)
```

```json
{
  "name": "ext4_fname_from_fscrypt_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585445616,
      "name": "ext4_fname_from_fscrypt_name",
      "external": false,
      "loc": "fs/ext4/crypto.c:10",
      "file": "fs/ext4/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/crypto.c:ext4_fname_prepare_lookup",
        "fs/ext4/crypto.c:ext4_fname_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585445616,
      "name": "ext4_fname_from_fscrypt_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fname_from_fscrypt_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494470144,
      "name": "ext4_fname_from_fscrypt_name",
      "external": false,
      "loc": "fs/ext4/ext4.h:2374",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fname_from_fscrypt_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227916600,
      "name": "ext4_fname_from_fscrypt_name",
      "external": false,
      "loc": "fs/ext4/ext4.h:2374",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fname_from_fscrypt_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288227996,
      "name": "ext4_fname_from_fscrypt_name",
      "external": false,
      "loc": "fs/ext4/ext4.h:2374",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
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
  "name": "ext4_fname_from_fscrypt_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273875416,
      "name": "ext4_fname_from_fscrypt_name",
      "external": false,
      "loc": "fs/ext4/ext4.h:2374",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fname_from_fscrypt_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582768868,
      "name": "ext4_fname_from_fscrypt_name",
      "external": false,
      "loc": "fs/ext4/ext4.h:2374",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fname_from_fscrypt_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582706036,
      "name": "ext4_fname_from_fscrypt_name",
      "external": false,
      "loc": "fs/ext4/ext4.h:2374",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fname_from_fscrypt_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582750653,
      "name": "ext4_fname_from_fscrypt_name",
      "external": false,
      "loc": "fs/ext4/ext4.h:2374",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fname_from_fscrypt_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582844020,
      "name": "ext4_fname_from_fscrypt_name",
      "external": false,
      "loc": "fs/ext4/ext4.h:2374",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void ext4_fname_from_fscrypt_name(struct ext4_filename * dst, const struct fscrypt_name * src)
```
</details>
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
