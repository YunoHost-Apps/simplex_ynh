option 1:

    after installing, you need to find your fingerprint of your server:
    `sudo cat /etc/opt/simplex/fingerprint`

    now make your server address:

`smp://<fingerprint_from_previous_step>[:<password>]@<public_hostname>[,<onion_hostname>]`

    add it to your simplex app under Settings > Network & Servers > SMP Servers > + Add server

options 2:
maybe during the CLI install, it could spit out the fingerprint address to the terminal. then we can copy & paste it.