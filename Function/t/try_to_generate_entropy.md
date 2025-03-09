# Function: <code>try_to_generate_entropy</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "try_to_generate_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585908572,
      "name": "try_to_generate_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1758",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void try_to_generate_entropy()
```

```json
{
  "name": "try_to_generate_entropy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586648400,
      "name": "try_to_generate_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1603",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586648400,
      "name": "try_to_generate_entropy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
void try_to_generate_entropy()
```

```json
{
  "name": "try_to_generate_entropy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586759040,
      "name": "try_to_generate_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1602",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586759040,
      "name": "try_to_generate_entropy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "try_to_generate_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586640088,
      "name": "try_to_generate_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1578",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "try_to_generate_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587186965,
      "name": "try_to_generate_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1598",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
void try_to_generate_entropy()
```

```json
{
  "name": "try_to_generate_entropy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594323079,
      "name": "try_to_generate_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1175",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:urandom_read_iter",
        "drivers/char/random.c:wait_for_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594323079,
      "name": "try_to_generate_entropy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
void try_to_generate_entropy()
```

```json
{
  "name": "try_to_generate_entropy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589940416,
      "name": "try_to_generate_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1266",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:urandom_read_iter",
        "drivers/char/random.c:wait_for_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589940416,
      "name": "try_to_generate_entropy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
void try_to_generate_entropy()
```

```json
{
  "name": "try_to_generate_entropy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590249696,
      "name": "try_to_generate_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1266",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:urandom_read_iter",
        "drivers/char/random.c:wait_for_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590249696,
      "name": "try_to_generate_entropy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
void try_to_generate_entropy()
```

```json
{
  "name": "try_to_generate_entropy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590590688,
      "name": "try_to_generate_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1266",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:urandom_read_iter",
        "drivers/char/random.c:wait_for_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590590688,
      "name": "try_to_generate_entropy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
  "name": "try_to_generate_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498733172,
      "name": "try_to_generate_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1758",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "try_to_generate_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231357116,
      "name": "try_to_generate_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1758",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "try_to_generate_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291887820,
      "name": "try_to_generate_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1758",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "try_to_generate_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276240362,
      "name": "try_to_generate_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1758",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "try_to_generate_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585669564,
      "name": "try_to_generate_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1758",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "try_to_generate_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585529916,
      "name": "try_to_generate_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1758",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "try_to_generate_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585858972,
      "name": "try_to_generate_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1758",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "try_to_generate_entropy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585967326,
      "name": "try_to_generate_entropy",
      "external": false,
      "loc": "drivers/char/random.c:1758",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void try_to_generate_entropy()
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void try_to_generate_entropy()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void try_to_generate_entropy()
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
