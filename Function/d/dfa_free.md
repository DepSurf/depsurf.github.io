# Function: <code>dfa_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void dfa_free(struct aa_dfa * dfa)
```

```json
{
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582486496,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:195",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_dfa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582486496,
      "name": "dfa_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
void dfa_free(struct aa_dfa * dfa)
```

```json
{
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582719360,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:199",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_teardown_dfa_engine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582719360,
      "name": "dfa_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
void dfa_free(struct aa_dfa * dfa)
```

```json
{
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582814016,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:199",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_teardown_dfa_engine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582814016,
      "name": "dfa_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582901965,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:199",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_free_kref"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583060061,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:199",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_free_kref"
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
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583261005,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:250",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_free_kref"
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
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583378797,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:250",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_free_kref",
        "security/apparmor/match.c:aa_dfa_free_kref"
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
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583565596,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:246",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_free_kref",
        "security/apparmor/match.c:aa_dfa_free_kref"
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
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583671324,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:261",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_free_kref",
        "security/apparmor/match.c:aa_dfa_free_kref"
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
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584034512,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:271",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
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
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584153760,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:271",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
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
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584180531,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:271",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
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
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584565555,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:271",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
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
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585211400,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:271",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
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
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585943736,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:271",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_teardown_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine",
        "security/apparmor/match.c:aa_setup_dfa_engine"
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
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586175740,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:227",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_free_kref",
        "security/apparmor/match.c:aa_dfa_free_kref"
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
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586427019,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:227",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_free_kref",
        "security/apparmor/match.c:aa_dfa_free_kref"
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
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495466132,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:261",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_free_kref",
        "security/apparmor/match.c:aa_dfa_free_kref"
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
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228832272,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:261",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_free_kref",
        "security/apparmor/match.c:aa_dfa_free_kref"
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
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289518948,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:261",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_free_kref",
        "security/apparmor/match.c:aa_dfa_free_kref"
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
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274653610,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:261",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_free_kref",
        "security/apparmor/match.c:aa_dfa_free_kref"
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
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583640060,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:261",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_free_kref",
        "security/apparmor/match.c:aa_dfa_free_kref"
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
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583577116,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:261",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_free_kref",
        "security/apparmor/match.c:aa_dfa_free_kref"
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
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583623836,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:261",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_free_kref",
        "security/apparmor/match.c:aa_dfa_free_kref"
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
  "name": "dfa_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583721900,
      "name": "dfa_free",
      "external": false,
      "loc": "security/apparmor/match.c:261",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_unpack",
        "security/apparmor/match.c:aa_dfa_free_kref",
        "security/apparmor/match.c:aa_dfa_free_kref"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void dfa_free(struct aa_dfa * dfa)
```
</details>
</li>
</ul>
