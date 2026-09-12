# bgp-lab

A minimal BGP speaker in Python, peering with FRR in Docker.

Two containers on one network: `r1` runs FRR as AS 65002 at `172.20.0.2`,
`dev` runs code as AS 65001 at `172.20.0.3`. FRR is configured `passive`.

## Run it

```bash
docker compose up -d --build
```

