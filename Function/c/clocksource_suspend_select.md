# Function: <code>clocksource_suspend_select</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void clocksource_suspend_select(bool fallback)
```

```json
{
  "name": "clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580049840,
      "name": "clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:488",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:clocksource_change_rating"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580049840,
      "name": "clocksource_suspend_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void clocksource_suspend_select(bool fallback)
```

```json
{
  "name": "clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580093408,
      "name": "clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:488",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:clocksource_change_rating"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580093408,
      "name": "clocksource_suspend_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void clocksource_suspend_select(bool fallback)
```

```json
{
  "name": "clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580142368,
      "name": "clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:495",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:clocksource_change_rating"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580142368,
      "name": "clocksource_suspend_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void clocksource_suspend_select(bool fallback)
```

```json
{
  "name": "clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:495",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:clocksource_change_rating"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580203408,
      "name": "clocksource_suspend_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071580207637,
      "name": "clocksource_suspend_select.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void clocksource_suspend_select(bool fallback)
```

```json
{
  "name": "clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:495",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:clocksource_change_rating"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580188144,
      "name": "clocksource_suspend_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071591311692,
      "name": "clocksource_suspend_select.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void clocksource_suspend_select(bool fallback)
```

```json
{
  "name": "clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:596",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:clocksource_change_rating"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580192384,
      "name": "clocksource_suspend_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071591254044,
      "name": "clocksource_suspend_select.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void clocksource_suspend_select(bool fallback)
```

```json
{
  "name": "clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:708",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:clocksource_change_rating"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580339008,
      "name": "clocksource_suspend_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071592154679,
      "name": "clocksource_suspend_select.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void clocksource_suspend_select(bool fallback)
```

```json
{
  "name": "clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:714",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:clocksource_change_rating"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580551952,
      "name": "clocksource_suspend_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071593929745,
      "name": "clocksource_suspend_select.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void clocksource_suspend_select(bool fallback)
```

```json
{
  "name": "clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580809984,
      "name": "clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:733",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:clocksource_change_rating"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580809984,
      "name": "clocksource_suspend_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void clocksource_suspend_select(bool fallback)
```

```json
{
  "name": "clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580893184,
      "name": "clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:744",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:clocksource_change_rating"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580893184,
      "name": "clocksource_suspend_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void clocksource_suspend_select(bool fallback)
```

```json
{
  "name": "clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580983616,
      "name": "clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:767",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:clocksource_change_rating"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580983616,
      "name": "clocksource_suspend_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void clocksource_suspend_select(bool fallback)
```

```json
{
  "name": "clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491363392,
      "name": "clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:495",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:clocksource_change_rating"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491363392,
      "name": "clocksource_suspend_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void clocksource_suspend_select(bool fallback)
```

```json
{
  "name": "clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225361544,
      "name": "clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:495",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:clocksource_change_rating"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225361544,
      "name": "clocksource_suspend_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void clocksource_suspend_select(bool fallback)
```

```json
{
  "name": "clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284298768,
      "name": "clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:495",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:clocksource_change_rating"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284298768,
      "name": "clocksource_suspend_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void clocksource_suspend_select(bool fallback)
```

```json
{
  "name": "clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271854924,
      "name": "clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:495",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:clocksource_change_rating"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271854924,
      "name": "clocksource_suspend_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void clocksource_suspend_select(bool fallback)
```

```json
{
  "name": "clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580111568,
      "name": "clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:495",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:clocksource_change_rating"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111568,
      "name": "clocksource_suspend_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void clocksource_suspend_select(bool fallback)
```

```json
{
  "name": "clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580056880,
      "name": "clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:495",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:clocksource_change_rating"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580056880,
      "name": "clocksource_suspend_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void clocksource_suspend_select(bool fallback)
```

```json
{
  "name": "clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580102640,
      "name": "clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:495",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:clocksource_change_rating"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580102640,
      "name": "clocksource_suspend_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void clocksource_suspend_select(bool fallback)
```

```json
{
  "name": "clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580154384,
      "name": "clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:495",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_unbind",
        "kernel/time/clocksource.c:clocksource_change_rating"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580154384,
      "name": "clocksource_suspend_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void clocksource_suspend_select(bool fallback)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
