# Function: <code>lsm_key_alloc</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int lsm_key_alloc(struct key * key)
```

```json
{
  "name": "lsm_key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582651666,
      "name": "lsm_key_alloc",
      "external": true,
      "loc": "security/security.c:585",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_key_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582637168,
      "name": "lsm_key_alloc",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int lsm_key_alloc(struct key * key)
```

```json
{
  "name": "lsm_key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582806237,
      "name": "lsm_key_alloc",
      "external": true,
      "loc": "security/security.c:543",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_key_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582791056,
      "name": "lsm_key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int lsm_key_alloc(struct key * key)
```

```json
{
  "name": "lsm_key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586051801,
      "name": "lsm_key_alloc",
      "external": true,
      "loc": "security/security.c:793",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_key_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586029696,
      "name": "lsm_key_alloc",
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int lsm_key_alloc(struct key * key)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int lsm_key_alloc(struct key * key)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int lsm_key_alloc(struct key * key)
```
</details>
</li>
</ul>
