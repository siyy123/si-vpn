# si-vpn
a simple but fast free vpn

si-vpn is a vpn based on IKEv2 protocol which provide security and nonblocking access. And it is free!

Notice! si-vpn is still a beta version, and the server may be unstable.

si-vpn is free to use. donation is welcomed.

my bitcoin address: 35U1EudqszMnCFy5MhPuAVqXjdx5ZzrVKW
i need money to keep the server running.

# how to use
1. import the CA certificate. You should choose Local computer and Trusted Root CA
2. add a vpn profile:

  server : 45.77.158.226

  username choose anything you want
  
  password: Siyy123
  
  protocol: IKEv2
  
  IKE proposal: aes256-sha1-modp1024 (some OS need this to connect)

and connect!

You would also need to enable IPv4 Gateway at Control Panel--Network--your vpn profile--Network--IPv4--Advanced

sometimes the server may report wrong username or password, just choose another username

si-vpn now supports windows, macOS, android. ios is developing.

#Todos

add support for IKEv1 XAUTH/PSK for native Android to connect.

add support for iOS IKEv2

add multi-node for improved bandwidth and latency.
