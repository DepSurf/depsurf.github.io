# Function: <code>blake2s_compress</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void blake2s_compress(struct blake2s_state * state, const u8 * block, size_t nblocks, const u32 inc)
```

```json
{
  "name": "blake2s_compress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579606944,
      "name": "blake2s_compress",
      "external": true,
      "loc": "arch/x86/crypto/blake2s-glue.c:29",
      "file": "arch/x86/crypto/blake2s-glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/blake2s.c:blake2s_final",
        "lib/crypto/blake2s.c:blake2s_update",
        "lib/crypto/blake2s.c:blake2s_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579606944,
      "name": "blake2s_compress",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void blake2s_compress(struct blake2s_state * state, const u8 * block, size_t nblocks, const u32 inc)
```

```json
{
  "name": "blake2s_compress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579720944,
      "name": "blake2s_compress",
      "external": true,
      "loc": "arch/x86/crypto/blake2s-glue.c:29",
      "file": "arch/x86/crypto/blake2s-glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/blake2s.c:blake2s_final",
        "lib/crypto/blake2s.c:blake2s_update",
        "lib/crypto/blake2s.c:blake2s_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579720944,
      "name": "blake2s_compress",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void blake2s_compress(struct blake2s_state * state, const u8 * block, size_t nblocks, const u32 inc)
```

```json
{
  "name": "blake2s_compress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579767344,
      "name": "blake2s_compress",
      "external": true,
      "loc": "arch/x86/crypto/blake2s-glue.c:28",
      "file": "arch/x86/crypto/blake2s-glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/blake2s.c:blake2s_final",
        "lib/crypto/blake2s.c:blake2s_update",
        "lib/crypto/blake2s.c:blake2s_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579767344,
      "name": "blake2s_compress",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void blake2s_compress(struct blake2s_state * state, const u8 * block, size_t nblocks, const u32 inc)
```

```json
{
  "name": "blake2s_compress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579802288,
      "name": "blake2s_compress",
      "external": true,
      "loc": "arch/x86/crypto/blake2s-glue.c:28",
      "file": "arch/x86/crypto/blake2s-glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/blake2s.c:blake2s_final",
        "lib/crypto/blake2s.c:blake2s_update",
        "lib/crypto/blake2s.c:blake2s_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579802288,
      "name": "blake2s_compress",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void blake2s_compress(struct blake2s_state * state, const u8 * block, size_t nblocks, const u32 inc)
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
