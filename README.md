proxies:
  - name: Google Cloud Indonesia 🇮🇩 TLS
    server: img.email1.vidio.com
    port: 443
    type: vless
    uuid: 5d77882b-7197-41f0-b9a3-98a877c5d4c9
    cipher: auto
    tls: true
    skip-cert-verify: true
    servername: id.workercloud.xyz
    network: ws
    ws-opts: 
      path: /vpnjatim
      headers: 
        Host: id.workercloud.xyz
    udp: true
