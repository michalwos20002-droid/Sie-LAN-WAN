# Projekt strukturalnej sieci LAN/WAN dla studia animacji

Pełne opracowanie techniczne architektury fizycznej i logicznej sieci lokalnej dla dwukondygnacyjnego budynku biurowego o powierzchni 400 m2 na potrzeby studia animacji komputerowej.

## 🛠️ Technologie i sprzęt enterprise
* **Urządzenia sieciowe:** Router Cisco ISR 4331, przełączniki Cisco Catalyst 1000-24T-4G-L, punkty dostępu Ubiquiti U7-Pro
* **Okablowanie:** Skrętka UTP kat. 6 (standard 1000Base-T, szkielet pionowy: światłowód wielomodowy OM3/OM4 10GBase-SR)
* **Zasilanie i bezpieczeństwo:** UPS APC Smart-UPS SMT1500I, wbudowany firewall, system monitoringu CCTV
* **Oprogramowanie i protokoły:** LibreNMS (SNMP), Wireshark, IPv4 Subnetting, DHCP, DNS, TCP/IP, VLAN (IEEE 802.1Q)
* **Normy techniczne:** PN-EN 50173, PN-EN 50174

## 📋 Zakres projektu i obliczenia inżynierskie
* **Kalkulacja okablowania:** Dokładne liczbowe oszacowanie zapotrzebowania na okablowanie strukturalne (łącznie 661 m kabla instalacyjnego UTP oraz 15 m światłowodu).
* **Adresacja IP:** Logiczny podział sieci na podsieci za pomocą masek o zmiennej długości (VLSM) dla optymalizacji ruchu sieciowego i separacji działu animacji od części biznesowej.
* **Topologia:** Zastosowanie topologii gwiazdy rozszerzonej (hierarchicznej) z centralnym punktem dystrybucyjnym w serwerowni.
* **Zarządzanie siecią:** Skonfigurowanie monitoringu wydajności urządzeń przez protokół SNMP za pomocą LibreNMS oraz analiza pakietów w programie Wireshark.
