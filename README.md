# Linux Server

## Understanding Tailscale

Tailscale creates a private network that virtualises a LAN regardless of where the connected devices are.

First install tailscale for your OS

## Useful commands

```
	tailscale status # lists all the relative IPs of the devices on the tailscale network
```

```
	tailscale up # starts up tailscale daemon
```

```
	tailscale down # stops tailscale daemon
```

```
	ssh <username>@<IP_of_device> # ssh into that device
```

```
	tailscale ping <IP_of_device> # shows ping trace of that device (best for debugging network issues)
```

PLEASE ADD MORE
