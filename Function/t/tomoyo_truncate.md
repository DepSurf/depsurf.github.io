# Function: <code>tomoyo_truncate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582418293,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1919",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry"
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
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582650201,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1919",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582743262,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1919",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int tomoyo_truncate(char * str)
```

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582823584,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1919",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582823584,
      "name": "tomoyo_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
int tomoyo_truncate(char * str)
```

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582980400,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1920",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582980400,
      "name": "tomoyo_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int tomoyo_truncate(char * str)
```

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583180640,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1920",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583180640,
      "name": "tomoyo_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int tomoyo_truncate(char * str)
```

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583296960,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1921",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583296960,
      "name": "tomoyo_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int tomoyo_truncate(char * str)
```

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583484432,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1979",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583484432,
      "name": "tomoyo_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int tomoyo_truncate(char * str)
```

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583590384,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1981",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583590384,
      "name": "tomoyo_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
int tomoyo_truncate(char * str)
```

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583942848,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1981",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583942848,
      "name": "tomoyo_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
int tomoyo_truncate(char * str)
```

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584062688,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1981",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584062688,
      "name": "tomoyo_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
int tomoyo_truncate(char * str)
```

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584090656,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1981",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584090656,
      "name": "tomoyo_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
int tomoyo_truncate(char * str)
```

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584464176,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1981",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584464176,
      "name": "tomoyo_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
int tomoyo_truncate(char * str)
```

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585099184,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1972",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585099184,
      "name": "tomoyo_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
int tomoyo_truncate(char * str)
```

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585823056,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1972",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585823056,
      "name": "tomoyo_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
int tomoyo_truncate(char * str)
```

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586054992,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1972",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586054992,
      "name": "tomoyo_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
int tomoyo_truncate(char * str)
```

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586303952,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1973",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586303952,
      "name": "tomoyo_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int tomoyo_truncate(char * str)
```

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495369448,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1981",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495369448,
      "name": "tomoyo_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int tomoyo_truncate(char * str)
```

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228745060,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1981",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228745060,
      "name": "tomoyo_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int tomoyo_truncate(char * str)
```

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289383904,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1981",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289383904,
      "name": "tomoyo_truncate",
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
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274588028,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1981",
      "file": "security/tomoyo/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int tomoyo_truncate(char * str)
```

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583559120,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1981",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583559120,
      "name": "tomoyo_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int tomoyo_truncate(char * str)
```

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583496176,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1981",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583496176,
      "name": "tomoyo_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int tomoyo_truncate(char * str)
```

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583542896,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1981",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583542896,
      "name": "tomoyo_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int tomoyo_truncate(char * str)
```

```json
{
  "name": "tomoyo_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583640160,
      "name": "tomoyo_truncate",
      "external": false,
      "loc": "security/tomoyo/common.c:1981",
      "file": "security/tomoyo/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583640160,
      "name": "tomoyo_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int tomoyo_truncate(char * str)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int tomoyo_truncate(char * str)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
