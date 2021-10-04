![image](https://user-images.githubusercontent.com/75273945/135918066-1efcc0cb-71ce-43b1-9818-31c971a8a775.png)

<b><h3>General explanation of the program:</h3></b>
<h5>
1.Detector match the MAC of the sender IP for sender authentication
  <br>
  &nbsp;&nbsp;&nbsp;A. SNIFFING on the same network card accessing the external network.
  <br>
  &nbsp;&nbsp;&nbsp;B. Capture packets from the network card.
  <br>
  &nbsp;&nbsp;&nbsp;C. Verify the data (IP and MAC ADDRESS) with queries to the sender IP.
  <br>
2. Print to CMD when there is a mismatch between the sending MAC and the MAC we received in response to a query.
<br>
3.Displays a panel with text to the user with a warning message about ARP SPOOFING attack.
<br>
4.Turn off the network card services of the attacked computer in order to avoid exposing sensitive information.
<br>
5.WRITE EVENT LOG into WINDOWS EVENT LOGS for a future analysis.
</h5>
