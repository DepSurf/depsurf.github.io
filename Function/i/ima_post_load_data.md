# Function: <code>ima_post_load_data</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int ima_post_load_data(char * buf, loff_t size, enum kernel_load_data_id load_id, char * description)
```

```json
{
  "name": "ima_post_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_post_load_data",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:795",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_post_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591369697,
      "name": "ima_post_load_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584298240,
      "name": "ima_post_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int ima_post_load_data(char * buf, loff_t size, enum kernel_load_data_id load_id, char * description)
```

```json
{
  "name": "ima_post_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_post_load_data",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:809",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_post_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591312387,
      "name": "ima_post_load_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071584332368,
      "name": "ima_post_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int ima_post_load_data(char * buf, loff_t size, enum kernel_load_data_id load_id, char * description)
```

```json
{
  "name": "ima_post_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_post_load_data",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:826",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_post_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592308312,
      "name": "ima_post_load_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071584720096,
      "name": "ima_post_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int ima_post_load_data(char * buf, loff_t size, enum kernel_load_data_id load_id, char * description)
```

```json
{
  "name": "ima_post_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_post_load_data",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:849",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_post_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594090616,
      "name": "ima_post_load_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585395232,
      "name": "ima_post_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int ima_post_load_data(char * buf, loff_t size, enum kernel_load_data_id load_id, char * description)
```

```json
{
  "name": "ima_post_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586148192,
      "name": "ima_post_load_data",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:859",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_post_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586148192,
      "name": "ima_post_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int ima_post_load_data(char * buf, loff_t size, enum kernel_load_data_id load_id, char * description)
```

```json
{
  "name": "ima_post_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586386400,
      "name": "ima_post_load_data",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:878",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_post_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586386400,
      "name": "ima_post_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int ima_post_load_data(char * buf, loff_t size, enum kernel_load_data_id load_id, char * description)
```

```json
{
  "name": "ima_post_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586651200,
      "name": "ima_post_load_data",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:892",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_post_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586651200,
      "name": "ima_post_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int ima_post_load_data(char * buf, loff_t size, enum kernel_load_data_id load_id, char * description)
```
</details>
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
