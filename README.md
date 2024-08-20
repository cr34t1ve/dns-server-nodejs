# DNS Server implementation with NodeJS

I built this in order to understand what goes on when a URL call is made in a browser or anywhere else. This project encapsulates the following concepts:

- Understanding what makes up a zone record
- Parsing Zone records
- Catching calls over a UDP connection
- Making a call to a DNS server to perform lookup for a Resource Record (rr), using zig

## Resouces

- [dns-server by EngineerHead](https://engineerhead.github.io/dns-server/)
- [RFC-1034](https://datatracker.ietf.org/doc/html/rfc1035)

## How to use

Start server:

```bash
node index.js
```

Then make a query to the server for rr

```bash
dig example.com @127.0.0.1
```
