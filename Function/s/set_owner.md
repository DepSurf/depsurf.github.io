# Function: <code>set_owner</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585354688,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:528",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port",
        "drivers/usb/host/ehci-hcd.c:store_companion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585354688,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585751296,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:532",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:store_companion",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585751296,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585940304,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:540",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:store_companion",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585940304,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586026256,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:540",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:store_companion",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586026256,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586470464,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:527",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:store_companion",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586470464,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586736512,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:527",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:companion_store",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586736512,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586902352,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:535",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:companion_store",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586902352,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587159824,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:535",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:companion_store",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587159824,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587360240,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:535",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:companion_store",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587360240,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588208272,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:534",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:companion_store",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588208272,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588244912,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:537",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:companion_store",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588244912,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588129152,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:537",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:companion_store",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588129152,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588765552,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:537",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:companion_store",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588765552,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590163584,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:537",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:companion_store",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590163584,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591779200,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:537",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:companion_store",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591779200,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592202496,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:537",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:companion_store",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592202496,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592943216,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:537",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:companion_store",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592943216,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500465936,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:535",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:companion_store",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500465936,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232907308,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:535",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:companion_store",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232907308,
      "name": "set_owner",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293822976,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:535",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:companion_store",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293822976,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277358004,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:535",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:companion_store",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277358004,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587066320,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:535",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:companion_store",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587066320,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587314800,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:535",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:companion_store",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587314800,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```

```json
{
  "name": "set_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587394640,
      "name": "set_owner",
      "external": false,
      "loc": "drivers/usb/host/ehci-hub.c:535",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:companion_store",
        "drivers/usb/host/ehci-hcd.c:ehci_relinquish_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587394640,
      "name": "set_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void set_owner(struct ehci_hcd * ehci, int portnum, int new_owner)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
