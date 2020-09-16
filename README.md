LAYER 2: DATALINK


How many different things are listed in the output of the arp -a command?

    - After running the apr - a command, there were 10 different listings for the output of the command. 

Start an IPython console (i.e. just type ipython in PowerShell/Termina) in the same directory as netlayers.py. In that console, type the following:

    import netlayers
    netlayers.arp_table()

What are the different devices connected to your home network? Can you identify what they are based on this information?

    - There are multiple TV's connected to my home network as well as several verizon devices. Some are identifiable and others are not so easy to identify.  


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

