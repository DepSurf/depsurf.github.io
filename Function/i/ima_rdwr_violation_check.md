# Function: <code>ima_rdwr_violation_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582610755,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:80",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582856729,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:79",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void ima_rdwr_violation_check(struct file * file, struct integrity_iint_cache * iint, int must_measure, char * * pathbuf, const char * * pathname)
```

```json
{
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582952384,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:79",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582952384,
      "name": "ima_rdwr_violation_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void ima_rdwr_violation_check(struct file * file, struct integrity_iint_cache * iint, int must_measure, char * * pathbuf, const char * * pathname)
```

```json
{
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583002352,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:79",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583002352,
      "name": "ima_rdwr_violation_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
void ima_rdwr_violation_check(struct file * file, struct integrity_iint_cache * iint, int must_measure, char * * pathbuf, const char * * pathname)
```

```json
{
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583166480,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:83",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583166480,
      "name": "ima_rdwr_violation_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583372787,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:83",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement"
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
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583491148,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:85",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement"
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
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583677722,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:106",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement"
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
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583784435,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:106",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement"
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
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584175365,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:104",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement"
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
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584294381,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:110",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement"
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
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584328228,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:110",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement"
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
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584715734,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:115",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement"
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
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585391380,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:115",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement"
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
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586144064,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:115",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement"
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
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586381302,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:115",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement"
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
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586645892,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:116",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement"
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
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495588296,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:106",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement"
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
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228948720,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:106",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement"
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
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289688556,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:106",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement"
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
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274753078,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:106",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement"
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
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583753171,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:106",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement"
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
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583690227,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:106",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement"
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
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583736947,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:106",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement"
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
  "name": "ima_rdwr_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583837875,
      "name": "ima_rdwr_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:106",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement"
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void ima_rdwr_violation_check(struct file * file, struct integrity_iint_cache * iint, int must_measure, char * * pathbuf, const char * * pathname)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void ima_rdwr_violation_check(struct file * file, struct integrity_iint_cache * iint, int must_measure, char * * pathbuf, const char * * pathname)
```
</details>
</li>
</ul>
