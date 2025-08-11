### Task 5: Capture and Analyze Network Traffic Using Wireshark

## Tools
* Wireshark: A free and open-source packet analyzer.
* A computer with an internet connection.

## Deliverables
* Packet Capture File (.pcap): A file containing the raw network traffic captured during the exercise.
* Short Report (.md or .pdf): A summary of the protocols and traffic types identified, along with a brief analysis.

## Instructions
* Install Wireshark: If you don't already have it, download and install Wireshark from the official website.

## Choose an Interface: Open Wireshark and select the network interface you want to monitor (e.g., your primary Wi-Fi or Ethernet adapter).

## Start Capture: Click the "Start capturing packets" button (usually a blue shark fin icon).

## Generate Traffic: While Wireshark is running, perform some typical internet activities like:
* Opening a web browser and visiting a few websites (e.g., google.com, wikipedia.org).
* Using a messaging application.
* Performing a simple DNS query.

## Stop Capture: After a few minutes, click the "Stop capturing packets" button (usually a red square).

## Analyze Packets:
* Use the filter bar to isolate specific protocols (e.g., http, dns, arp).
* Examine the packet details pane to understand the structure of the data.
* Look for the source and destination IP addresses, ports, and payload data.

## Save the Capture: Go to File > Save and save the capture file with a .pcap extension.

# Write the Report: Create a short report detailing your findings. The report should include:
* A summary of the captured traffic.
* Descriptions of the protocols you identified.
* At least three specific examples of packets and what they reveal.
