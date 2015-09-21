# Random stuff

### ipv6-ipv6_dnpt - IPv6-to-IPv6 Network Prefix Translation (RFC 6296)

Quick hack to calculate the private IP address when using stateless IPV6 NAT. It only works with /64 prefixes and will probably break easily if used in the wild.

When using DNPT on IPv6 it's not trivial to figure out what the private IP becomes after the translation. This code calculates it in a very crude and hackish way. (Read the RFC)[https://tools.ietf.org/html/rfc6296#section-3].
