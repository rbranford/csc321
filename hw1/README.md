LAYER 2: DATALINK


How many different things are listed in the output of the arp -a command?

    - After running the apr - a command, there were 10 different listings for the output of the command. 

Start an IPython console (i.e. just type ipython in PowerShell/Termina) in the same directory as netlayers.py. In that console, type the following:

    import netlayers
    netlayers.arp_table()

What are the different devices connected to your home network? Can you identify what they are based on this information?

    - 192.168.0.1      58:8b:f3:e5:2f:e7  ZyXELCommunications Corporation
      192.168.0.11     5c:93:a2:8d:91:61  Liteon Technology Corporation
      192.168.0.37     c0:d2:f3:20:66:ca  Hui Zhou Gaoshengda Technology Co.,LTD
      192.168.0.70     d8:13:99:66:e0:b5  Hui Zhou Gaoshengda Technology Co.,LTD
      192.168.0.255    ff:ff:ff:ff:ff:ff
      224.0.0.22       01:00:5e:00:00:16
      224.0.0.251      01:00:5e:00:00:fb
      224.0.0.252      01:00:5e:00:00:fc
      239.255.255.250  01:00:5e:7f:ff:fa
      255.255.255.255  ff:ff:ff:ff:ff:ff 


      I am unable to identify what any of these are which is probably not a good thing. 


LAYER 3: NETWORK

Run the following commands in your console.

Windows:

    ping google.com
    ping localhost

macOS:

    ping -c 5 google.com
    ping -c 5 localhost

What are the differences between the two commands?

    - Pinging google.com [64.233.185.113] with 32 bytes of data:

    Ping statistics for 64.233.185.113:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
    Approximate round trip times in milli-seconds:
    Minimum = 47ms, Maximum = 61ms, Average = 51ms

    Pinging DESKTOP-FDDNHBD [::1] with 32 bytes of data:

    Ping statistics for ::1:
        Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
    Approximate round trip times in milli-seconds:
        Minimum = 0ms, Maximum = 0ms, Average = 0ms

