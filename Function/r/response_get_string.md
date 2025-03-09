# Function: <code>response_get_string</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "response_get_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583426288,
      "name": "response_get_string",
      "external": false,
      "loc": "block/sed-opal.c:859",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583426288,
      "name": "response_get_string.constprop.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
  "name": "response_get_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583606192,
      "name": "response_get_string",
      "external": false,
      "loc": "block/sed-opal.c:871",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583606192,
      "name": "response_get_string.constprop.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
  "name": "response_get_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583829312,
      "name": "response_get_string",
      "external": false,
      "loc": "block/sed-opal.c:868",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583829312,
      "name": "response_get_string.constprop.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "response_get_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583905376,
      "name": "response_get_string",
      "external": false,
      "loc": "block/sed-opal.c:868",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583905376,
      "name": "response_get_string.constprop.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "response_get_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584089056,
      "name": "response_get_string",
      "external": false,
      "loc": "block/sed-opal.c:915",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:get_active_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584089056,
      "name": "response_get_string.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "response_get_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584211776,
      "name": "response_get_string",
      "external": false,
      "loc": "block/sed-opal.c:913",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:get_active_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584211776,
      "name": "response_get_string.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
size_t response_get_string(const struct parsed_resp * resp, int n, const char * * store)
```

```json
{
  "name": "response_get_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584598160,
      "name": "response_get_string",
      "external": false,
      "loc": "block/sed-opal.c:915",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:get_active_key_cont"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584598160,
      "name": "response_get_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
size_t response_get_string(const struct parsed_resp * resp, int n, const char * * store)
```

```json
{
  "name": "response_get_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584717008,
      "name": "response_get_string",
      "external": false,
      "loc": "block/sed-opal.c:915",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:get_active_key_cont"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584717008,
      "name": "response_get_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
size_t response_get_string(const struct parsed_resp * resp, int n, const char * * store)
```

```json
{
  "name": "response_get_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584744816,
      "name": "response_get_string",
      "external": false,
      "loc": "block/sed-opal.c:915",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:get_active_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584744816,
      "name": "response_get_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
size_t response_get_string(const struct parsed_resp * resp, int n, const char * * store)
```

```json
{
  "name": "response_get_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585172864,
      "name": "response_get_string",
      "external": false,
      "loc": "block/sed-opal.c:915",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:get_active_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585172864,
      "name": "response_get_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
size_t response_get_string(const struct parsed_resp * resp, int n, const char * * store)
```

```json
{
  "name": "response_get_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585909760,
      "name": "response_get_string",
      "external": false,
      "loc": "block/sed-opal.c:915",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_active_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585909760,
      "name": "response_get_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
size_t response_get_string(const struct parsed_resp * resp, int n, const char * * store)
```

```json
{
  "name": "response_get_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586698896,
      "name": "response_get_string",
      "external": false,
      "loc": "block/sed-opal.c:955",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_active_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586698896,
      "name": "response_get_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
size_t response_get_string(const struct parsed_resp * resp, int n, const char * * store)
```

```json
{
  "name": "response_get_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586959504,
      "name": "response_get_string",
      "external": false,
      "loc": "block/sed-opal.c:963",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_active_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586959504,
      "name": "response_get_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
size_t response_get_string(const struct parsed_resp * resp, int n, const char * * store)
```

```json
{
  "name": "response_get_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587239760,
      "name": "response_get_string",
      "external": false,
      "loc": "block/sed-opal.c:1080",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_active_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587239760,
      "name": "response_get_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
  "name": "response_get_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496082480,
      "name": "response_get_string",
      "external": false,
      "loc": "block/sed-opal.c:913",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:get_active_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496082480,
      "name": "response_get_string.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
  "name": "response_get_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229412504,
      "name": "response_get_string",
      "external": false,
      "loc": "block/sed-opal.c:913",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:get_active_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229412504,
      "name": "response_get_string.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "response_get_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290323936,
      "name": "response_get_string",
      "external": false,
      "loc": "block/sed-opal.c:913",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:get_active_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290323936,
      "name": "response_get_string.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
  "name": "response_get_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275155580,
      "name": "response_get_string",
      "external": false,
      "loc": "block/sed-opal.c:913",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:get_active_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275155580,
      "name": "response_get_string.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
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
  "name": "response_get_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584180512,
      "name": "response_get_string",
      "external": false,
      "loc": "block/sed-opal.c:913",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:get_active_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584180512,
      "name": "response_get_string.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "response_get_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584115760,
      "name": "response_get_string",
      "external": false,
      "loc": "block/sed-opal.c:913",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:get_active_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584115760,
      "name": "response_get_string.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "response_get_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584164272,
      "name": "response_get_string",
      "external": false,
      "loc": "block/sed-opal.c:913",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:get_active_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584164272,
      "name": "response_get_string.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "response_get_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584268656,
      "name": "response_get_string",
      "external": false,
      "loc": "block/sed-opal.c:913",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:get_active_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584268656,
      "name": "response_get_string.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    }
  ]
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
size_t response_get_string(const struct parsed_resp * resp, int n, const char * * store)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
