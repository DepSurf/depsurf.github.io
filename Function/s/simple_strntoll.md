# Function: <code>simple_strntoll</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "simple_strntoll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585122579,
      "name": "simple_strntoll",
      "external": false,
      "loc": "lib/vsprintf.c:126",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:simple_strtoll",
        "lib/vsprintf.c:simple_strtoll"
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
  "name": "simple_strntoll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585572270,
      "name": "simple_strntoll",
      "external": false,
      "loc": "lib/vsprintf.c:127",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:simple_strtoll",
        "lib/vsprintf.c:simple_strtoll"
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
  "name": "simple_strntoll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586727032,
      "name": "simple_strntoll",
      "external": false,
      "loc": "lib/vsprintf.c:131",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:simple_strtoll",
        "lib/vsprintf.c:simple_strtoll"
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
  "name": "simple_strntoll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595889736,
      "name": "simple_strntoll",
      "external": false,
      "loc": "lib/vsprintf.c:132",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:simple_strtoll",
        "lib/vsprintf.c:simple_strtoll"
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
  "name": "simple_strntoll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596407128,
      "name": "simple_strntoll",
      "external": false,
      "loc": "lib/vsprintf.c:132",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:simple_strtoll",
        "lib/vsprintf.c:simple_strtoll"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long long int simple_strntoll(const char * cp, char * * endp, unsigned int base, size_t max_chars)
```

```json
{
  "name": "simple_strntoll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597298480,
      "name": "simple_strntoll",
      "external": false,
      "loc": "lib/vsprintf.c:135",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:simple_strtoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597298480,
      "name": "simple_strntoll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
long long int simple_strntoll(const char * cp, char * * endp, unsigned int base, size_t max_chars)
```
</details>
</li>
</ul>
