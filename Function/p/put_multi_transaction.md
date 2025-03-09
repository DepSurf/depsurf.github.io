# Function: <code>put_multi_transaction</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void put_multi_transaction(struct multi_transaction * t)
```

```json
{
  "name": "put_multi_transaction",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582877136,
      "name": "put_multi_transaction",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:835",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582877136,
      "name": "put_multi_transaction",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_multi_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583047106,
      "name": "put_multi_transaction",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:836",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_multi_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583247646,
      "name": "put_multi_transaction",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:833",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_multi_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583365582,
      "name": "put_multi_transaction",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:831",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_multi_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583553200,
      "name": "put_multi_transaction",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:836",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
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
  "name": "put_multi_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583658880,
      "name": "put_multi_transaction",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:804",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
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
  "name": "put_multi_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584018448,
      "name": "put_multi_transaction",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:835",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
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
  "name": "put_multi_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584138384,
      "name": "put_multi_transaction",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:835",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
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
  "name": "put_multi_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584165392,
      "name": "put_multi_transaction",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:835",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
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
  "name": "put_multi_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584549392,
      "name": "put_multi_transaction",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:835",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_multi_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585191077,
      "name": "put_multi_transaction",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:837",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_multi_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585920021,
      "name": "put_multi_transaction",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1004",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_multi_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586152229,
      "name": "put_multi_transaction",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1049",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_multi_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586401429,
      "name": "put_multi_transaction",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1050",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "put_multi_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495452416,
      "name": "put_multi_transaction",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:804",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495439736,
      "name": "put_multi_transaction.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "put_multi_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228818876,
      "name": "put_multi_transaction",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:804",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228807312,
      "name": "put_multi_transaction.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void put_multi_transaction(struct multi_transaction * t)
```

```json
{
  "name": "put_multi_transaction",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289480048,
      "name": "put_multi_transaction",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:804",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289480048,
      "name": "put_multi_transaction",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "put_multi_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274641728,
      "name": "put_multi_transaction",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:804",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
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
  "name": "put_multi_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583627616,
      "name": "put_multi_transaction",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:804",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
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
  "name": "put_multi_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583564672,
      "name": "put_multi_transaction",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:804",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
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
  "name": "put_multi_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583611392,
      "name": "put_multi_transaction",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:804",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
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
  "name": "put_multi_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583709152,
      "name": "put_multi_transaction",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:804",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_release",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void put_multi_transaction(struct multi_transaction * t)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void put_multi_transaction(struct multi_transaction * t)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void put_multi_transaction(struct multi_transaction * t)
```
</details>
</li>
</ul>
