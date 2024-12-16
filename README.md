# 📄 **Intra Domain Routing**

## **Configuration**

![Intra Routing Configuration](https://github.com/Proyek-Jarkomlan/IntraDomainRouting/blob/main/assets/Intra%20Domain%20Routing.jpg?raw=true)

## **Steps**
1. Clone this repository:
   ```bash
   git clone https://github.com/Proyek-Jarkomlan/IntraDomainRouting.git
2. Navigate directory to the project:
   ```bash
   cd IntraDomainRouting
3. Run the project with this command:
   ```bash
   sudo python3 ospf-lab.py -c frr-config
4. Run this command to test the project:
   ```bash
   C1_1 traceroute -I C2_1
5. Run the different traceroute command to test the project:
   ```bash
   C1_1 traceroute -I C3_2
6. If you have successfully traceroute, the project is successful.
