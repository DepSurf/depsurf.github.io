# Struct: <code>xfrm_state_afinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    unsigned int family;
    unsigned int proto;
    __be16 eth_proto;
    struct module * owner;
    const struct xfrm_type *[256] type_map;
    struct xfrm_mode *[5] mode_map;
    int (*)(struct xfrm_state *) init_flags;
    void (*)(struct xfrm_selector *, const struct flowi *) init_tempsel;
    void (*)(struct xfrm_state *, const struct xfrm_tmpl *, const xfrm_address_t *, const xfrm_address_t *) init_temprop;
    int (*)(struct xfrm_tmpl * *, struct xfrm_tmpl * *, int) tmpl_sort;
    int (*)(struct xfrm_state * *, struct xfrm_state * *, int) state_sort;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sock *, struct sk_buff *) output_finish;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_input;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    unsigned int family;
    unsigned int proto;
    __be16 eth_proto;
    struct module * owner;
    const struct xfrm_type *[256] type_map;
    struct xfrm_mode *[5] mode_map;
    int (*)(struct xfrm_state *) init_flags;
    void (*)(struct xfrm_selector *, const struct flowi *) init_tempsel;
    void (*)(struct xfrm_state *, const struct xfrm_tmpl *, const xfrm_address_t *, const xfrm_address_t *) init_temprop;
    int (*)(struct xfrm_tmpl * *, struct xfrm_tmpl * *, int) tmpl_sort;
    int (*)(struct xfrm_state * *, struct xfrm_state * *, int) state_sort;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sock *, struct sk_buff *) output_finish;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_input;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    unsigned int family;
    unsigned int proto;
    __be16 eth_proto;
    struct module * owner;
    const struct xfrm_type *[256] type_map;
    struct xfrm_mode *[5] mode_map;
    int (*)(struct xfrm_state *) init_flags;
    void (*)(struct xfrm_selector *, const struct flowi *) init_tempsel;
    void (*)(struct xfrm_state *, const struct xfrm_tmpl *, const xfrm_address_t *, const xfrm_address_t *) init_temprop;
    int (*)(struct xfrm_tmpl * *, struct xfrm_tmpl * *, int) tmpl_sort;
    int (*)(struct xfrm_state * *, struct xfrm_state * *, int) state_sort;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sock *, struct sk_buff *) output_finish;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_input;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    unsigned int family;
    unsigned int proto;
    __be16 eth_proto;
    struct module * owner;
    const struct xfrm_type *[256] type_map;
    const struct xfrm_type_offload *[256] type_offload_map;
    struct xfrm_mode *[5] mode_map;
    int (*)(struct xfrm_state *) init_flags;
    void (*)(struct xfrm_selector *, const struct flowi *) init_tempsel;
    void (*)(struct xfrm_state *, const struct xfrm_tmpl *, const xfrm_address_t *, const xfrm_address_t *) init_temprop;
    int (*)(struct xfrm_tmpl * *, struct xfrm_tmpl * *, int) tmpl_sort;
    int (*)(struct xfrm_state * *, struct xfrm_state * *, int) state_sort;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sock *, struct sk_buff *) output_finish;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_input;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    unsigned int family;
    unsigned int proto;
    __be16 eth_proto;
    struct module * owner;
    const struct xfrm_type *[256] type_map;
    const struct xfrm_type_offload *[256] type_offload_map;
    struct xfrm_mode *[5] mode_map;
    int (*)(struct xfrm_state *) init_flags;
    void (*)(struct xfrm_selector *, const struct flowi *) init_tempsel;
    void (*)(struct xfrm_state *, const struct xfrm_tmpl *, const xfrm_address_t *, const xfrm_address_t *) init_temprop;
    int (*)(struct xfrm_tmpl * *, struct xfrm_tmpl * *, int) tmpl_sort;
    int (*)(struct xfrm_state * *, struct xfrm_state * *, int) state_sort;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sock *, struct sk_buff *) output_finish;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_input;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    unsigned int family;
    unsigned int proto;
    __be16 eth_proto;
    struct module * owner;
    const struct xfrm_type *[256] type_map;
    const struct xfrm_type_offload *[256] type_offload_map;
    struct xfrm_mode *[5] mode_map;
    int (*)(struct xfrm_state *) init_flags;
    void (*)(struct xfrm_selector *, const struct flowi *) init_tempsel;
    void (*)(struct xfrm_state *, const struct xfrm_tmpl *, const xfrm_address_t *, const xfrm_address_t *) init_temprop;
    int (*)(struct xfrm_tmpl * *, struct xfrm_tmpl * *, int) tmpl_sort;
    int (*)(struct xfrm_state * *, struct xfrm_state * *, int) state_sort;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sock *, struct sk_buff *) output_finish;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_input;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    unsigned int family;
    unsigned int proto;
    __be16 eth_proto;
    struct module * owner;
    const struct xfrm_type *[256] type_map;
    const struct xfrm_type_offload *[256] type_offload_map;
    struct xfrm_mode *[5] mode_map;
    int (*)(struct xfrm_state *) init_flags;
    void (*)(struct xfrm_selector *, const struct flowi *) init_tempsel;
    void (*)(struct xfrm_state *, const struct xfrm_tmpl *, const xfrm_address_t *, const xfrm_address_t *) init_temprop;
    int (*)(struct xfrm_tmpl * *, struct xfrm_tmpl * *, int) tmpl_sort;
    int (*)(struct xfrm_state * *, struct xfrm_state * *, int) state_sort;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sock *, struct sk_buff *) output_finish;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_input;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    u8 family;
    u8 proto;
    const struct xfrm_type_offload * type_offload_esp;
    const struct xfrm_type * type_esp;
    const struct xfrm_type * type_ipip;
    const struct xfrm_type * type_ipip6;
    const struct xfrm_type * type_comp;
    const struct xfrm_type * type_ah;
    const struct xfrm_type * type_routing;
    const struct xfrm_type * type_dstopts;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sock *, struct sk_buff *) output_finish;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_input;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    u8 family;
    u8 proto;
    const struct xfrm_type_offload * type_offload_esp;
    const struct xfrm_type * type_esp;
    const struct xfrm_type * type_ipip;
    const struct xfrm_type * type_ipip6;
    const struct xfrm_type * type_comp;
    const struct xfrm_type * type_ah;
    const struct xfrm_type * type_routing;
    const struct xfrm_type * type_dstopts;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sock *, struct sk_buff *) output_finish;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_input;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    u8 family;
    u8 proto;
    const struct xfrm_type_offload * type_offload_esp;
    const struct xfrm_type * type_esp;
    const struct xfrm_type * type_ipip;
    const struct xfrm_type * type_ipip6;
    const struct xfrm_type * type_comp;
    const struct xfrm_type * type_ah;
    const struct xfrm_type * type_routing;
    const struct xfrm_type * type_dstopts;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    u8 family;
    u8 proto;
    const struct xfrm_type_offload * type_offload_esp;
    const struct xfrm_type * type_esp;
    const struct xfrm_type * type_ipip;
    const struct xfrm_type * type_ipip6;
    const struct xfrm_type * type_comp;
    const struct xfrm_type * type_ah;
    const struct xfrm_type * type_routing;
    const struct xfrm_type * type_dstopts;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    u8 family;
    u8 proto;
    const struct xfrm_type_offload * type_offload_esp;
    const struct xfrm_type * type_esp;
    const struct xfrm_type * type_ipip;
    const struct xfrm_type * type_ipip6;
    const struct xfrm_type * type_comp;
    const struct xfrm_type * type_ah;
    const struct xfrm_type * type_routing;
    const struct xfrm_type * type_dstopts;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    u8 family;
    u8 proto;
    const struct xfrm_type_offload * type_offload_esp;
    const struct xfrm_type * type_esp;
    const struct xfrm_type * type_ipip;
    const struct xfrm_type * type_ipip6;
    const struct xfrm_type * type_comp;
    const struct xfrm_type * type_ah;
    const struct xfrm_type * type_routing;
    const struct xfrm_type * type_dstopts;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    u8 family;
    u8 proto;
    const struct xfrm_type_offload * type_offload_esp;
    const struct xfrm_type * type_esp;
    const struct xfrm_type * type_ipip;
    const struct xfrm_type * type_ipip6;
    const struct xfrm_type * type_comp;
    const struct xfrm_type * type_ah;
    const struct xfrm_type * type_routing;
    const struct xfrm_type * type_dstopts;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    u8 family;
    u8 proto;
    const struct xfrm_type_offload * type_offload_esp;
    const struct xfrm_type * type_esp;
    const struct xfrm_type * type_ipip;
    const struct xfrm_type * type_ipip6;
    const struct xfrm_type * type_comp;
    const struct xfrm_type * type_ah;
    const struct xfrm_type * type_routing;
    const struct xfrm_type * type_dstopts;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    u8 family;
    u8 proto;
    const struct xfrm_type_offload * type_offload_esp;
    const struct xfrm_type * type_esp;
    const struct xfrm_type * type_ipip;
    const struct xfrm_type * type_ipip6;
    const struct xfrm_type * type_comp;
    const struct xfrm_type * type_ah;
    const struct xfrm_type * type_routing;
    const struct xfrm_type * type_dstopts;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    u8 family;
    u8 proto;
    const struct xfrm_type_offload * type_offload_esp;
    const struct xfrm_type * type_esp;
    const struct xfrm_type * type_ipip;
    const struct xfrm_type * type_ipip6;
    const struct xfrm_type * type_comp;
    const struct xfrm_type * type_ah;
    const struct xfrm_type * type_routing;
    const struct xfrm_type * type_dstopts;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
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
struct xfrm_state_afinfo {
    u8 family;
    u8 proto;
    const struct xfrm_type_offload * type_offload_esp;
    const struct xfrm_type * type_esp;
    const struct xfrm_type * type_ipip;
    const struct xfrm_type * type_ipip6;
    const struct xfrm_type * type_comp;
    const struct xfrm_type * type_ah;
    const struct xfrm_type * type_routing;
    const struct xfrm_type * type_dstopts;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sock *, struct sk_buff *) output_finish;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_input;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    u8 family;
    u8 proto;
    const struct xfrm_type_offload * type_offload_esp;
    const struct xfrm_type * type_esp;
    const struct xfrm_type * type_ipip;
    const struct xfrm_type * type_ipip6;
    const struct xfrm_type * type_comp;
    const struct xfrm_type * type_ah;
    const struct xfrm_type * type_routing;
    const struct xfrm_type * type_dstopts;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sock *, struct sk_buff *) output_finish;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_input;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    u8 family;
    u8 proto;
    const struct xfrm_type_offload * type_offload_esp;
    const struct xfrm_type * type_esp;
    const struct xfrm_type * type_ipip;
    const struct xfrm_type * type_ipip6;
    const struct xfrm_type * type_comp;
    const struct xfrm_type * type_ah;
    const struct xfrm_type * type_routing;
    const struct xfrm_type * type_dstopts;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sock *, struct sk_buff *) output_finish;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_input;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    u8 family;
    u8 proto;
    const struct xfrm_type_offload * type_offload_esp;
    const struct xfrm_type * type_esp;
    const struct xfrm_type * type_ipip;
    const struct xfrm_type * type_ipip6;
    const struct xfrm_type * type_comp;
    const struct xfrm_type * type_ah;
    const struct xfrm_type * type_routing;
    const struct xfrm_type * type_dstopts;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sock *, struct sk_buff *) output_finish;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_input;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
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
struct xfrm_state_afinfo {
    u8 family;
    u8 proto;
    const struct xfrm_type_offload * type_offload_esp;
    const struct xfrm_type * type_esp;
    const struct xfrm_type * type_ipip;
    const struct xfrm_type * type_ipip6;
    const struct xfrm_type * type_comp;
    const struct xfrm_type * type_ah;
    const struct xfrm_type * type_routing;
    const struct xfrm_type * type_dstopts;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sock *, struct sk_buff *) output_finish;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_input;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    u8 family;
    u8 proto;
    const struct xfrm_type_offload * type_offload_esp;
    const struct xfrm_type * type_esp;
    const struct xfrm_type * type_ipip;
    const struct xfrm_type * type_ipip6;
    const struct xfrm_type * type_comp;
    const struct xfrm_type * type_ah;
    const struct xfrm_type * type_routing;
    const struct xfrm_type * type_dstopts;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sock *, struct sk_buff *) output_finish;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_input;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    u8 family;
    u8 proto;
    const struct xfrm_type_offload * type_offload_esp;
    const struct xfrm_type * type_esp;
    const struct xfrm_type * type_ipip;
    const struct xfrm_type * type_ipip6;
    const struct xfrm_type * type_comp;
    const struct xfrm_type * type_ah;
    const struct xfrm_type * type_routing;
    const struct xfrm_type * type_dstopts;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sock *, struct sk_buff *) output_finish;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_input;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct xfrm_state_afinfo {
    u8 family;
    u8 proto;
    const struct xfrm_type_offload * type_offload_esp;
    const struct xfrm_type * type_esp;
    const struct xfrm_type * type_ipip;
    const struct xfrm_type * type_ipip6;
    const struct xfrm_type * type_comp;
    const struct xfrm_type * type_ah;
    const struct xfrm_type * type_routing;
    const struct xfrm_type * type_dstopts;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sock *, struct sk_buff *) output_finish;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_input;
    int (*)(struct xfrm_state *, struct sk_buff *) extract_output;
    int (*)(struct sk_buff *, int) transport_finish;
    void (*)(struct sk_buff *, u32) local_error;
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
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct xfrm_type_offload *[256] type_offload_map</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct xfrm_type_offload * type_offload_esp</code>
</li>
<li>
<b>Field added. </b>
<code>const struct xfrm_type * type_esp</code>
</li>
<li>
<b>Field added. </b>
<code>const struct xfrm_type * type_ipip</code>
</li>
<li>
<b>Field added. </b>
<code>const struct xfrm_type * type_ipip6</code>
</li>
<li>
<b>Field added. </b>
<code>const struct xfrm_type * type_comp</code>
</li>
<li>
<b>Field added. </b>
<code>const struct xfrm_type * type_ah</code>
</li>
<li>
<b>Field added. </b>
<code>const struct xfrm_type * type_routing</code>
</li>
<li>
<b>Field added. </b>
<code>const struct xfrm_type * type_dstopts</code>
</li>
<li>
<b>Field removed. </b>
<code>__be16 eth_proto</code>
</li>
<li>
<b>Field removed. </b>
<code>struct module * owner</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct xfrm_type *[256] type_map</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct xfrm_type_offload *[256] type_offload_map</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xfrm_mode *[5] mode_map</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct xfrm_state *) init_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct xfrm_selector *, const struct flowi *) init_tempsel</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct xfrm_state *, const struct xfrm_tmpl *, const xfrm_address_t *, const xfrm_address_t *) init_temprop</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct xfrm_tmpl * *, struct xfrm_tmpl * *, int) tmpl_sort</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct xfrm_state * *, struct xfrm_state * *, int) state_sort</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int family</code> ➡️ <code>u8 family</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int proto</code> ➡️ <code>u8 proto</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct sock *, struct sk_buff *) output_finish</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct xfrm_state *, struct sk_buff *) extract_input</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct xfrm_state *, struct sk_buff *) extract_output</code>
</li>
</ul>
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
