# Function: <code>seg6_push_hmac</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587909456,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:330",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587909456,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588067760,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:330",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588067760,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588611920,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:331",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588611920,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588977728,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:331",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588977728,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589201760,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:332",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589201760,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589655488,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:327",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589655488,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589879888,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:327",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589879888,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590908032,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:326",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_rthdr4",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590908032,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590971552,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:325",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_rthdr4",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590971552,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590902464,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:325",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_rthdr4",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590902464,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591736160,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:325",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_rthdr4",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591736160,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593438400,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:325",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_rthdr4",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593438400,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595354256,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:325",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_rthdr4",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595354256,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595751216,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:325",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_rthdr4",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595751216,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596599392,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:325",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_rthdr4",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596599392,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503601496,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:327",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503601496,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236244388,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:327",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236244388,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297413200,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:327",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297413200,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279554272,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:327",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279554272,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589484256,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:327",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589484256,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589209248,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:327",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589209248,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589921120,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:327",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589921120,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
```

```json
{
  "name": "seg6_push_hmac",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589975088,
      "name": "seg6_push_hmac",
      "external": true,
      "loc": "net/ipv6/seg6_hmac.c:327",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_push_nfrag_opts",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589975088,
      "name": "seg6_push_hmac",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int seg6_push_hmac(struct net * net, struct in6_addr * saddr, struct ipv6_sr_hdr * srh)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
