General explanation of the program:

1.Detector match the MAC of the sender IP for sender authentication:

  A. SNIFFING on the same network card accessing the external network.
  B. Capture packets from the network card.
  C. Verify the data (IP and MAC ADDRESS) with queries to the sender IP.
  
2. Print to CMD when there is a mismatch between the sending MAC and the MAC we received in response to a query.

3.Displays a panel with text to the user with a warning message about ARP SPOOFING attack.

4.Turn off the network card services of the attacked computer in order to avoid exposing sensitive information.

5.WRITE EVENT LOG into WINDOWS EVENT LOGS for a future analysis.
