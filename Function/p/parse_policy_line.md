# Function: <code>parse_policy_line</code>

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
  "name": "parse_policy_line",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583667645,
      "name": "parse_policy_line",
      "external": false,
      "loc": "security/safesetid/securityfs.c:30",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
  "name": "parse_policy_line",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583773917,
      "name": "parse_policy_line",
      "external": false,
      "loc": "security/safesetid/securityfs.c:30",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int parse_policy_line(struct file * file, char * buf, struct setuid_rule * rule)
```

```json
{
  "name": "parse_policy_line",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584163920,
      "name": "parse_policy_line",
      "external": false,
      "loc": "security/safesetid/securityfs.c:30",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:handle_policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584163920,
      "name": "parse_policy_line",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int parse_policy_line(struct file * file, char * buf, struct setid_rule * rule)
```

```json
{
  "name": "parse_policy_line",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584282768,
      "name": "parse_policy_line",
      "external": false,
      "loc": "security/safesetid/securityfs.c:31",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:handle_policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584282768,
      "name": "parse_policy_line",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
  "name": "parse_policy_line",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584308271,
      "name": "parse_policy_line",
      "external": false,
      "loc": "security/safesetid/securityfs.c:31",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:handle_policy_update"
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
  "name": "parse_policy_line",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584694831,
      "name": "parse_policy_line",
      "external": false,
      "loc": "security/safesetid/securityfs.c:31",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:handle_policy_update"
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
  "name": "parse_policy_line",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585358478,
      "name": "parse_policy_line",
      "external": false,
      "loc": "security/safesetid/securityfs.c:31",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:handle_policy_update"
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
  "name": "parse_policy_line",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586108044,
      "name": "parse_policy_line",
      "external": false,
      "loc": "security/safesetid/securityfs.c:31",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:handle_policy_update"
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
  "name": "parse_policy_line",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586346668,
      "name": "parse_policy_line",
      "external": false,
      "loc": "security/safesetid/securityfs.c:31",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:handle_policy_update"
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
  "name": "parse_policy_line",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586613672,
      "name": "parse_policy_line",
      "external": false,
      "loc": "security/safesetid/securityfs.c:31",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:handle_policy_update"
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
  "name": "parse_policy_line",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495575480,
      "name": "parse_policy_line",
      "external": false,
      "loc": "security/safesetid/securityfs.c:30",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
  "name": "parse_policy_line",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228937580,
      "name": "parse_policy_line",
      "external": false,
      "loc": "security/safesetid/securityfs.c:30",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
  "name": "parse_policy_line",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289671368,
      "name": "parse_policy_line",
      "external": false,
      "loc": "security/safesetid/securityfs.c:30",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
  "name": "parse_policy_line",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274742714,
      "name": "parse_policy_line",
      "external": false,
      "loc": "security/safesetid/securityfs.c:30",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
  "name": "parse_policy_line",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583742653,
      "name": "parse_policy_line",
      "external": false,
      "loc": "security/safesetid/securityfs.c:30",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
  "name": "parse_policy_line",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583679709,
      "name": "parse_policy_line",
      "external": false,
      "loc": "security/safesetid/securityfs.c:30",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
  "name": "parse_policy_line",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583726429,
      "name": "parse_policy_line",
      "external": false,
      "loc": "security/safesetid/securityfs.c:30",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
  "name": "parse_policy_line",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583827181,
      "name": "parse_policy_line",
      "external": false,
      "loc": "security/safesetid/securityfs.c:30",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int parse_policy_line(struct file * file, char * buf, struct setuid_rule * rule)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct setuid_rule * rule</code> ➡️ <code>struct setid_rule * rule</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int parse_policy_line(struct file * file, char * buf, struct setid_rule * rule)
```
</details>
</li>
</ul>
